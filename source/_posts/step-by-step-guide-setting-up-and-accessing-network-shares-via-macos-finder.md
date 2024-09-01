---
title: "Step-by-Step Guide: Setting Up and Accessing Network Shares via macOS Finder"
date: 2024-08-28 23:20:40
updated: 2024-08-29 12:12:15
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3da10c18ed5eb1d81fc33e9b77c3f37bbadf618042f3295c06f9d5e5b10aa5c0.jpg
---

## Step-by-Step Guide: Setting Up and Accessing Network Shares via macOS Finder

### Key Takeaways

* Avoid limitations of remote volumes and cloud storage apps like Google Drive Desktop by mounting a drive as if it were local using SSHFS and macFUSE.
* Use Terminal to mount your remote volumes, then access them as you would any other in Finder.
* Use a script to automate this process so that you can simply run the script to connect each time your Mac restarts (or the volumes are unmounted).

 If you regularly deal with remote volumes like a web server, you can get tired of interacting purely using a command line. Fortunately, you can use SSH functionality to mount a remote instance volume on your Mac and interact with it using Finder as if it were a local volume. Here's how.

##  Why Bother Doing This?

![Browsing my AWS EC2 web server in Finder using macFUSE and SSHFS.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/browsing-my-aws-ec2-webserver-in-finder-using-macfuse-and-sshfs.png) 

 So, why would someone want to use these tools to mount remote (internet) volumes in this fashion? Well, the potential uses for such configurations are myriad, but here are just a handful for your consideration.

###  Avoids Inherent Limitations of Google Drive Desktop

 Google Drive is an immensely popular choice for cloud storage, but its desktop app can be a touch restrictive. You may have noticed that syncing big files can be slow, and accessing your entire Drive without using up local storage can be a problem. For instance, Google Drive has a history of nasty habits like eating up tons of local storage in excessive cache files tucked away in hidden directories.

 Or maybe you have noticed that some other apps refuse to "see" the default macOS file path where cloud storage volumes are located. You can circumvent both of these using macFUSE and SSHFS. Though it takes some doing outside the scope of this specific guide, these tools can be used to mount your Google Drive or other remote storage as if it were local.

 This can serve to bypass these limitations, giving you direct access to your files without the need to actually sync them.

###  Smooth Out your Dual-Boot Config

 If you run a dual-boot system with macOS and another operating system, you already know how cumbersome accessing those files can be when you've booted into macOS. Skip all that extra fuss by using these tools to mount volumes associated with your other OS directly and access them in your current Mac session, allowing management in a single environment.

###  Drag and Drop to Remote Volumes for a Better Workflow

 I like working from the command line more than most, but mounting my remote volumes locally really speeds up my workflow, particularly when experiencing eye strain from looking at nothing but text for hours on end.

 For example, I run my personal website off of an AWS EC2 instance of Ubuntu Server. By nature, Ubuntu Server runs headless (without a graphic interface). When adding media to my web server, the ability to drag and drop files directly using Finder just flows faster than uploading via the terminal and also eliminates associated delays.

###  Provides a Platform to Experiment

 For tech enthusiasts and hobbyists, experimenting with different filesystems and server configurations can be a fun and educational experience. macFUSE and SSHFS provide an easy way to mount and interact with various filesystems, from the comfort of your macOS environment.

 This capability is particularly useful for those looking to learn about networked storage, server management, or even developing their own custom filesystems, without needing to dive deep into complex configurations.

##  What You Need Before We Begin

 Before we move on to mounting remote volumes, you'll need to install a few additional bits of software.

###  macFUSE

 macFUSE is software that improves macOS filesystem capabilities, allowing you to use different types of filesystems that aren't natively supported.

 To install macFUSE, first visit the [macFUSE GitHub repository](https://github.com/osxfuse/osxfuse/releases).

![Downloading macFUSE latest version from GitHub](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/downloading-macfuse-latest-version-from-github.png) 

 Download the latest version of the macFUSE installer, open it and follow the on-screen instructions to complete the installation. After installation, you may need to enable system extensions in System Settings> Security & Privacy.

 macFUSE is essential for enabling the other prerequisite for configuration, SSHFS.

###  SSHFS

 SSHFS stands for Secure SHell FileSystem. It is aptly named for its ability to allow users to mount remote filesystems over SSH. It uses the secure file transfer protocol (SFTP) to access files on a remote server, providing a secure and efficient way to manage remote data as if it were on your local machine.

 To install SSHFS, first make sure [you have Homebrew installed on your Mac](https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-motorola-edge-40-neo-pc-drfone-by-drfone-android/). Now open Terminal and run the command:

brew install sshfs

##  Using the SSHFS Command

 Mounting a remote filesystem using SSHFS utilizes the following command structure:

        `sshfs [user]@[host]:[remote_directory] [local_mount_point] -o IdentityFile=[path_to_private_key]`
    
 Here's a breakdown of the command:

* \[user\] is your username on the remote server.
* \[host\] is server's address (like a domain name or IP address).
* \[remote\_directory\] is the directory on the server that you want to mount.
* \[local\_mount\_point\] is the local directory where the remote filesystem will be mounted.
* IdentityFile specifies the private key file for authentication.

###  Using an SSHFS Script Command For Running With Minimal Effort

 The script I've written below simplifies the process of mounting a remote filesystem using SSHFS. It sets up the mount point, adjusts permissions, and mounts the remote filesystem with a custom volume name. Just replace the variables in the first section with those applicable to your remote volume.

        `#!/bin/zsh  
  
## Change the following variable fields with your own applicable info  
  
MOUNT_POINT="path/to/desired/mount/point"  
LOCAL_USER="YOUR macOS USERNAME"  
INSTANCE_USER="YOUR REMOTE USERNAME"  
INSTANCE_DNS="YOUR_INSTANT_DNS_ADDRESS OR URL"  
PRIVATE_KEY_PATH="path/to/your/private/key.pem"  
VOLUME_NAME="YOUR DESIRED VOLUME NAME"  
  
## Create the mount point if it doesn't exist  
if [! -d "$MOUNT_POINT"]; then  
    sudo mkdir -p "$MOUNT_POINT"  
    sudo chown "$LOCAL_USER":staff "$MOUNT_POINT"  
    sudo chmod 755 "$MOUNT_POINT"  
else  
    # Adjust permissions if the directory already exists  
    sudo chown "$LOCAL_USER":staff "$MOUNT_POINT"  
    sudo chmod 755 "$MOUNT_POINT"  
fi  
  
## Mount the remote filesystem with a custom volume name  
sshfs -o volname="$VOLUME_NAME",IdentityFile="$PRIVATE_KEY_PATH" $INSTANCE_USER@$INSTANCE_DNS:/ "$MOUNT_POINT"  
  
## Open the directory in Finder  
open "$MOUNT_POINT"`
    
 Once you've edited the script to fit your personal use case, save it as "mount\_remote.sh". Make it executable by opening Terminal and using:

chmod +x mount_remote.sh

 Now run it using

./mount_remote.sh

 This script automates the mounting process, making it quick and easy to access your remote files.

![Mounted remote volume with generic macFUSE icon.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/mounted-remote-volume-with-generic-macfuse-icon.png) 

###  Applying an Image of Your Choosing as a Drive Icon

 To personalize your mounted drive, you can apply a custom icon. Since macFUSE applies the same generic icon to remote mounts, this is useful for differentiating when using more than one.

 If opting to do this, use the script below, which is a lightly augmented version of the one provided above. The script already includes an option (\`volicon\`) to set the icon, which is specified by the \`VOLUME\_ICON\` variable. To use your own image:

 First, convert your image to the ICNS format using an online converter or software like Preview, then replace the "VOLUME\_ICON" path in the script with the path to your custom icon file.

        `#!/bin/zsh  
  
## Change the following variable fields with your own applicable info  
  
MOUNT_POINT="path/to/desired/mount/point"  
LOCAL_USER="YOUR macOS USERNAME"  
INSTANCE_USER="YOUR REMOTE USERNAME"  
INSTANCE_DNS="YOUR_INSTANT_DNS_ADDRESS"  
PRIVATE_KEY_PATH="path/to/your/private/key.pem"  
VOLUME_NAME="YOUR DESIRED VOLUME NAME"  
VOLUME_ICON="path/to/your/icon.icns"  
  
## Create the mount point if it doesn't exist  
if [! -d "$MOUNT_POINT"]; then  
   sudo mkdir -p "$MOUNT_POINT"  
   sudo chown "$LOCAL_USER":staff "$MOUNT_POINT"  
   sudo chmod 755 "$MOUNT_POINT"  
else  
   # Adjust permissions if the directory already exists  
   sudo chown "$LOCAL_USER":staff "$MOUNT_POINT"  
   sudo chmod 755 "$MOUNT_POINT"  
fi  
  
## Mount the remote filesystem with a custom volume name  
sshfs -o volname="$VOLUME_NAME",IdentityFile="$PRIVATE_KEY_PATH",volicon="$VOLUME_ICON" $INSTANCE_USER@$INSTANCE_DNS:/ "$MOUNT_POINT"  
  
## Open the directory in Finder  
open "$MOUNT_POINT"`
    
 After running this script, your remote volume will appear in Finder sporting whatever icon image you specified!

## ![Mounted remote volume with my own custom icon.](https://static0.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/mounted-remote-volume-with-my-own-custom-icon.png) 

---

 Mounting remote filesystems on macOS using macFUSE and SSHFS can greatly enhance your workflow, allowing for seamless access to remote data. Whether you're looking to bypass the limitations of cloud storage applications, streamline a dual-boot setup, or explore new filesystems, these tools provide a flexible and powerful solution.

 By following the steps outlined in this article and using the provided script, you can easily set up and automate the process, ensuring that your remote files are always just a click away.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
