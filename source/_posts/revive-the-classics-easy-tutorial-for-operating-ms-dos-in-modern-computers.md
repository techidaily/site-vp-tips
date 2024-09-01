---
title: "Revive the Classics: Easy Tutorial for Operating MS-DOS in Modern Computers"
date: 2024-08-27 18:21:10
updated: 2024-08-29 12:12:35
tags:
  - web
categories:
  - tech
thumbnail: https://thmb.techidaily.com/60ef5a3cb6d3ebf4383dc1944d7c5c6920d92b79ffebc24b472a5709fccd0d23.jpg
---

## Revive the Classics: Easy Tutorial for Operating MS-DOS in Modern Computers

### Quick Links

* [Run MS-DOS with DOSBox](https://youtube-videos.techidaily.com/demystifying-the-math-of-youtube-ratio-perfection-for-2024/)
* [Run DOS in Your Browser](https://fox-info.techidaily.com/updated-2024-approved-best-real-time-stage-performances/)
* [Can I Run MS-DOS in VirtualBox or VMWare?](https://unlock-android.techidaily.com/how-can-we-unlock-our-tecno-spark-go-2024-phone-screen-by-drfone-android/)

 DOS was (and is) an iconic part of the personal computer revolution, but modern hardware doesn't support it. If you want to give MS-DOS a spin today, you need an emulator or some ancient hardware. Here are a few easy ways to run MS-DOS.

##  Run MS-DOS with DOSBox

[DOSBox](https://www.dosbox.com/), an open-source DOS emulator, is the easiest way to run MS-DOS on your own PC. Since I'm on Windows, I'll [use the version for Windows](https://sourceforge.net/projects/dosbox/), but there is nothing stopping you from [running DOSBox on macOS or Linux](https://www.dosbox.com/download.php?main=1) if you want.

![Click the green Download button to get DOSBox.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/1-dosbox-dl.png) 

 Once it has downloaded, run the executable to get started with the installation. DOSBox is tiny, only some 5MB, so neither the download nor installation will take very long. There aren't really any settings to worry about, so just click through the installer.

Close 

 After the installation is complete, launch DOSBox. You're now using DOS—it's that easy. DOSBox has a crash course built in that will help you get started.

![DOSBox running on Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/4-dosbox-running.png) 

 The first thing you should do once you reach this point is to mount a folder from your regular PC in DOSBox, so that you can easily move files between your real PC and your MS-DOS operating system. I am going to place my folder in "C:\\dos" just because it makes the path very easy to type and remember, but you can put it wherever you want.

 Open up File Explorer, head to the C:\\ drive, then right-click empty space and click New > Folder. Name the new folder **dos**. Once you create the dos folder, open it up and create any sub-folders you might want. In my case, I'm going to be playing some vintage games, so I created a games folder.

Close 

 Now we need to tell our DOS operating system where to find this folder. Head over to your DOSBox console, then type the following command:

mount c c:\dos

 This tells DOS to create its own C:\\ drive based on the contents of the specified folder, in this case, C:\\dos. If you want to mount another folder to another drive, you just need to swap out the letters and folder paths accordingly. The general format you use is:

mount [Drive Letter You Want] [Path To Folder On Your Real PC]

![Our DOSBox has successfully added the DOS folder we created.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/dosbox-mounted-c.png) 

 Enter **C:** into the console to change to the C:\\ drive, then type **[dir](https://eaxpv-info.techidaily.com/streamline-your-soundtrack-selection-for-youtube-for-2024/)** to see what the C:\\ drive contains. In my case, I can see the games folder I created earlier.

![The Games folder visible in DOSBox.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/games-folder-visible.png) 

[Dir is the primary command you use to view the contents of folders](https://eaxpv-info.techidaily.com/streamline-your-soundtrack-selection-for-youtube-for-2024/), and an essential one if you plan on using Windows or DOS from the command line. Another vital command is cd, which stands for "Change Directory." It is used to [move between folders in Windows](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/), DOS, Linux, and macOS.

 There are some differences in syntax between DIR and CD on Windows and DIR and CD on DOS, however the fundamentals are largely the same. If something you find in a Windows article doesn't work, it probably isn't you—it just probably just doesn't exist in DOS.

 I was able to get Oregon Trail up and running in about 5 minutes total. 

![Oregon Trail running in DOSBox.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/oregon-trail.png) 

##  Run DOS in Your Browser

 If setting up DOSBox, another emulator, or running DOS "bare metal" (directly on old hardware) isn't for you, then you can always use an online service instead.

 I tested a few different services, but ultimately settled on [PCJs Machines](https://www.pcjs.org/software/pcx86/sys/dos/microsoft/6.22/).

 You can easily switch between different versions of MS-DOS, ranging from MS-DOS 2.00 up to the final release, MS-DOS 6.22\. However, it isn't limited to just MS-DOS. It offers access to a large range of other vintage operating systems and simulated hardware for you to tinker with—a nerdy delight.

![DOS in a browser.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/dos-in-a-browser.png) 

 It also includes some old games, like Microsoft Flight Simulator, if you want to take those out for a spin.

##  Can I Run MS-DOS in VirtualBox or VMWare?

 Yes, you can, but you probably shouldn't unless you have a good reason. This is especially true since [FreeDOS](https://freedos.org/download/)—an operating system designed to give you everything MS-DOS does—is safe, reliable, and freely available.

 Running MS-DOS itself has a few major problems. VirtualBox and VMWare both use image files (ISOs) to install operating systems. The trouble is that MS-DOS was never officially released as an ISO, so you have only two choices: get a physical copy of MS-DOS from somewhere (they can be found online, and I've seen them at garage sales before), or download an ISO that someone built from the floppies.

 While an MS-DOS ISO isn't a prime vector for malware, you should never trust unofficial operating system ISOs to be safe—they're potentially enormous security vulnerabilities.

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
