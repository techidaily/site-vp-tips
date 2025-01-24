---
title: "Step-by-Step Guide: Securely Locking Your Computer with Windows 10'S Command Prompt"
date: 2025-01-17T01:37:42.445Z
updated: 2025-01-24T01:01:33.804Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Step-by-Step Guide: Securely Locking Your Computer with Windows 10'S Command Prompt

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-advanced-3d-text-techniques-in-ai/"><u>[New] 2024 Approved Advanced 3D Text Techniques in AI</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-boosting-visuals-with-photoshops-motion-blur-effect-tutorial/"><u>[New] 2024 Approved Boosting Visuals with Photoshop's Motion Blur Effect Tutorial</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/reating-impact-with-high-converting-youtube-advertising-banners-for-2024/"><u>[New] Creating Impact with High-Converting YouTube Advertising Banners for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-elevating-your-iphone-with-custom-ringtones/"><u>[New] In 2024, Elevating Your iPhone with Custom Ringtones</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-precision-image-editing-on-iphone-with-best-apps-for-object-elimination/"><u>[New] In 2024, Precision Image Editing on iPhone with Best Apps for Object Elimination</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-the-best-5-book-video-promotions-ever-made/"><u>[New] In 2024, The Best 5 Book Video Promotions Ever Made</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-essential-simple-shelter-strategies-in-mc/"><u>[Updated] Essential Simple Shelter Strategies in MC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-best-4k-all-in-one-touch-screen-desktops/"><u>[Updated] In 2024, Best 4K All-in-One Touch Screen Desktops</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-subtitle-files-like-a-pro-in-macos/"><u>[Updated] Navigating Subtitle Files Like a Pro in macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-6-online-communities-catering-to-the-commercial-world/"><u>[Updated] Top 6 Online Communities Catering to the Commercial World</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-photo-frames-leading-software-reviews/"><u>2024 Approved Mastering Photo Frames Leading Software Reviews</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-navigating-through-hands-free-technological-advances/"><u>2024 Approved Navigating Through Hands-Free Technological Advances</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-perfecting-voice-broadcasts-on-apple-devices-the-pros-guide/"><u>2024 Approved Perfecting Voice Broadcasts on Apple Devices - The Pro's Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-guide-for-apple-iphone-15-plus-lock-screen-drfone-by-drfone-ios/"><u>Complete Guide For Apple iPhone 15 Plus Lock Screen | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/eliminating-vibrational-distortion-in-drone-footage/"><u>Eliminating Vibrational Distortion in Drone Footage</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-xiaomi-redmi-k70-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/identifying-and-resolving-the-7-frequent-display-issues-on-iphones/"><u>Identifying & Resolving the 7 Frequent Display Issues on iPhones</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-xiaomi-redmi-k70-pro-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Xiaomi Redmi K70 Pro to New Phone | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unveiling-the-power-of-gopro-hero5-sessions-for-2024/"><u>Unveiling the Power of GoPro Hero5 Sessions for 2024</u></a></li>
</ul></div>

