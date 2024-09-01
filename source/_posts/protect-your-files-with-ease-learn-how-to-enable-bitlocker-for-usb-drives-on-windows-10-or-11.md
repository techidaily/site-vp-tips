---
title: "Protect Your Files with Ease: Learn How to Enable BitLocker for USB Drives on Windows 10 or 11"
date: 2024-08-26 11:56:49
updated: 2024-08-29 11:57:21
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8357b168f14ad6299dbc663fee70693f53617c625c6e0b9ad212abd473aa163b.jpg
---

## Protect Your Files with Ease: Learn How to Enable BitLocker for USB Drives on Windows 10 or 11

### Quick Links

* [What Is BitLocker (And Why Use It)?](https://www.howtogeek.com/encrypt-usb-flash-drive-windows/#what-is-bitlocker-and-why-use-it)
* [How to Encrypt a USB Flash Drive in Windows 10 or 11](https://fox-that.techidaily.com/iphone-glitched-into-headphones-try-these-8-troubleshooting-steps-to-restore-normal-functioning/)
* [How to Decrypt a USB Flash Drive in Windows 10 or 11](https://extra-resources.techidaily.com/the-ultimate-platform-showdown-podcast-vs-youtube/)
* [Third-Party Encryption Options](https://tech-hub.techidaily.com/how-to-harness-the-power-of-gpt-3-in-your-openai-experiments/)

### Key Takeaways

* Windows 10 and 11 Pro users can easily encrypt and decrypt flash drives using the built-in BitLocker feature, providing a convenient way to protect sensitive information.
* BitLocker uses powerful encryption technology (AES-128) that is virtually impossible to crack, ensuring the security of your data.
* While BitLocker is suitable for protecting sensitive information on portable computers, there are third-party encryption options available for Windows Home users.

 Flash drives are convenient, but they're also easy to lose and often contain sensitive information you don't want in the wrong hands. Luckily, Windows 10 and 11 Pro users can easily encrypt and decrypt flash drives with no additional software.

##  What Is BitLocker (And Why Use It)?

 BitLocker is a powerful encryption feature in Windows 10 and 11 Pro that protects the data on your drives so that no one can read their contents without the encryption key. The default level of encryption is AES-128, which would take millions or even billions of years to crack using current supercomputers.

 To use BitLocker, in addition to having the right version of Windows, your computer must be equipped with a TPM (Trusted Platform Module) of at least version 1.2\. If your computer doesn't have one, you'll need to [create a startup USB key](https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/). However, this is only relevant to internal system drives, and here we're discussing removable media. Likewise, encrypting the drive that contains Windows has special requirements regarding how the drive must be partitioned, but these requirements don't apply to secondary internal drives or removable, non-bootable drives.

 Full disk encryption isn't something everyone needs to do, but if your computer has sensitive information on it that could harm you if the drive were stolen, BitLocker is a good way to protect yourself. It's particularly useful for portable computers, since these have a much higher chance of being lost or stolen than a desktop system.

##  How to Encrypt a USB Flash Drive in Windows 10 or 11

 If you've decided that BitLocker is the right solution for your removable drive, here's how to set it up:

 1\. Plug in your USB drive.

 2\. Open File Explorer. You can use Windows+E to do this quickly.

 3\. Right-click on the flash drive in Explorer and select "Turn on BitLocker". In Windows 11, you'll have to click on "Show more details" first.

![A red arrow points to the 'Turn on bitlocker' option in the right-click context menu for a drive in Windows Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1.jpg) 

 4\. Wait for BitLocker to initialize the drive.

![Window showing the startup sequence for BitLocker Drive Encryption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2.jpg) 

 5\. Choose a password.

![BItLocker Window asking how the user wants to unlock the drive that's about to be encrypted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/3.jpg) 

 6\. Choose where and how to save your recovery key, which will let you decrypt the drive if you forget your password.

![BitLocker offering several recovery key back up options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/4.jpg) 

 7\. Choose whether to encrypt the whole drive or only used space. If the drive is empty and formatted, choose "Used Space"; otherwise, choose "Entire Drive."

![Bitlocker asking the user whether they want to encrypt the entire disk or only part of it](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/5.jpg) 

 8\. Choose the encryption type, which in almost all cases should be "Compatibility Mode." This ensures that older versions of Windows can read the drive. Since we're encrypting a portable drive, this is presumably something you want. However, if you're only going to use this drive with one computer, feel free to select the newer encryption option instead.

![Bitlocker offering either the new encryption mode or the older compatible mode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/7.jpg) 

 9\. Click "Start Encrypting" and wait for the process to finish.

![The BitLocker Ready screen with a 'Start Encrypting' button.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/8.jpg) 

 If the process was successful, your drive is now protected by strong encryption and can only be accessed using its password.

##  How to Decrypt a USB Flash Drive in Windows 10 or 11

 So what if you don't want to have an encrypted flash drive anymore? One option is simply to format the drive, which will get rid of the encryption, but also all the data on the drive! If you don't need the data anymore, this is the fastest and easiest way to get the drive back to its factory condition.

 If you still need the data, you should simply copy it to another drive that's not encrypted before formatting the encrypted drive. This is just a fast workaround, however. The proper way to [decrypt the drive](https://desktop-recording.techidaily.com/androids-top-10-moba-gaming-spectacles/) and preserve all the data on it is as follows:

 Right-click on the drive in File Explorer and select "Manage BitLocker." On Windows 11, you'll have to click "Show more options" first.

![A right-click context menu showing the option to manage BitLocker](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/9.jpg) 

 In the BitLocker management Windows, choose "Turn off BitLocker" for the drive in question.

![A window showing the option to turn off Bitlocker](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/10.jpg) 

 Then simply confirm as you did when first encrypting the drive.

##  Third-Party Encryption Options

 As mentioned earlier, BitLocker isn't included in Home versions of Windows. That doesn't mean you have to be left in the lurch when it comes to keeping your data safe.

 If you're using a Home version of Windows, third-party apps like [VeraCrypt](https://www.veracrypt.fr/code/VeraCrypt/) (a free, open-source tool known for its robust security features) and [AxCrypt](https://axcrypt.net/) (a user-friendly app with a subscription model) are great alternatives.

 VeraCrypt is best for those who need high-level security without cost concerns, while AxCrypt offers a balance of ease of use and security for a modest fee.

---

 Securing your data, especially on portable media that's easily lost or stolen, is more important than ever. If you must carry sensitive information on-the-go, BitLocker is an excellent and easy solution.

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
