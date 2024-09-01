---
title: "Revive the Classics: Easy Tutorial for Operating MS-DOS in Modern Computers"
date: 2024-08-31T08:49:29.817Z
updated: 2024-09-01T08:49:29.817Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
##  Run DOS in Your Browser

 If setting up DOSBox, another emulator, or running DOS "bare metal" (directly on old hardware) isn't for you, then you can always use an online service instead.

 I tested a few different services, but ultimately settled on [PCJs Machines](https://www.pcjs.org/software/pcx86/sys/dos/microsoft/6.22/).

 You can easily switch between different versions of MS-DOS, ranging from MS-DOS 2.00 up to the final release, MS-DOS 6.22\. However, it isn't limited to just MS-DOS. It offers access to a large range of other vintage operating systems and simulated hardware for you to tinker with—a nerdy delight.

![DOS in a browser.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/dos-in-a-browser.png) 

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It also includes some old games, like Microsoft Flight Simulator, if you want to take those out for a spin.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-growth-acceleration-on-youtube-expert-tips-for-video-partnerships/"><u>[New] 2024 Approved  Growth Acceleration on YouTube  Expert Tips for Video Partnerships</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-critical-methods-to-record-lol-skirmishes-for-2024/"><u>[New] Critical Methods to Record LOL Skirmishes for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-dive-right-in-the-art-of-entering-a-tiktok-stream/"><u>[Updated] 2024 Approved  Dive Right In  The Art of Entering a TikTok Stream</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-film-quality-faceoff-hero-black-and-keymission-camera/"><u>[Updated] 2024 Approved  Film Quality Faceoff  HERO Black and Keymission Camera</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-beginners-pathway-utilizing-fade-transitions/"><u>[Updated] In 2024, Beginner's Pathway  Utilizing Fade Transitions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-low-end-pc-maximum-performance-via-obs/"><u>[Updated] Low-End Pc - Maximum Performance via OBS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-scrutinizing-free2x-tech-for-optimal-webcam-use-for-2024/"><u>[Updated] Scrutinizing Free2X Tech for Optimal Webcam Use for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-art-of-rebranding-online-expert-tips-for-transforming-your-tiktok-username-for-2024/"><u>[Updated] The Art of Rebranding Online  Expert Tips for Transforming Your TikTok Username for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-mobile-sound-treat-asmr/"><u>[Updated] The Ultimate Mobile Sound Treat  ASMR</u></a></li>
<li><a href="https://vp-tips.techidaily.com/15-must-watch-films-perfect-for-your-new-years-eve-celebration/"><u>15 Must-Watch Films Perfect for Your New Year's Eve Celebration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-simplifycast-the-ultimate-guide-to-starting-your-podcast-livestream/"><u>2024 Approved  SimplifyCast  The Ultimate Guide to Starting Your Podcast Livestream</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-step-by-step-process-for-crafting-tiktok-video-captions/"><u>2024 Approved  Step-by-Step Process for Crafting TikTok Video Captions</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-ways-to-track-apple-iphone-13-pro-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>3 Ways to Track Apple iPhone 13 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-restrictions-for-microsoft-store-on-win11/"><u>Clearing Restrictions for Microsoft Store on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-review-transform-your-images-with-facetune-for-2024/"><u>Comprehensive Review  Transform Your Images with Facetune for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/convert-mts-videos-to-mp4-free-and-easy-compatible-with-iphoneipadipod-on-mac/"><u>Convert MTS Videos to MP4 Free & Easy: Compatible with iPhone/iPad/iPod on Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/digiartys-spectacular-18th-anniversary-special-project/"><u>Digiarty's Spectacular 18Th Anniversary Special Project</u></a></li>
<li><a href="https://vp-tips.techidaily.com/easy-steps-for-moving-your-files-and-photos-from-an-iphone-x-to-an-iphone-8-or-plus-model/"><u>Easy Steps for Moving Your Files and Photos From an iPhone X to an iPhone 8 or Plus Model</u></a></li>
<li><a href="https://vp-tips.techidaily.com/effortless-transition-converting-dvds-for-seamless-integration-into-your-home-media-hub/"><u>Effortless Transition: Converting DVDs for Seamless Integration Into Your Home Media Hub</u></a></li>
<li><a href="https://vp-tips.techidaily.com/eliminating-unnatural-distortions-from-fisheye-footage-for-enhanced-video-quality/"><u>Eliminating Unnatural Distortions From Fisheye Footage for Enhanced Video Quality</u></a></li>
<li><a href="https://extra-resources.techidaily.com/experience-the-thrill-of-kinemaster-and-rank-10-online-alternatives-alike/"><u>Experience the Thrill of KineMaster and Rank 10 Online Alternatives Alike</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-on-immediate-termination-of-faulty-windows-software-using-revo-uninstaller/"><u>Expert Tips on Immediate Termination of Faulty Windows Software Using Revo Uninstaller</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-iphone-14-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/get-the-latest-instagram-app-on-mac-comprehensive-tutorial-for-a-free-download/"><u>Get the Latest Instagram App on Mac - Comprehensive Tutorial for a FREE Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-canon-mx492-printer-drivers-a-step-by-step-guide-for-seamless-windows-integration/"><u>Get the Newest Canon MX492 Printer Drivers: A Step-by-Step Guide for Seamless Windows Integration</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-samsung-galaxy-s24plus-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Samsung Galaxy S24+ to iPad | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ipoditunes-isync/"><u>IPodがiTunesに同期できない？これが音楽リンクの究極解決策！ - iSyncスキルアップのポイント</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-os-x-unveiled-exploring-its-core-concepts-and-distinctive-traits/"><u>Mac OS X Unveiled: Exploring Its Core Concepts and Distinctive Traits</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-users-handbook-transforming-dvd-media-into-wmv-files-with-ease/"><u>Mac Users' Handbook: Transforming DVD Media Into WMV Files with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-friendly-top-5-dvd-management-tools-essential-picks-for-optimal-performance/"><u>Mac-Friendly Top 5 DVD Management Tools: Essential Picks for Optimal Performance</u></a></li>
<li><a href="https://vp-tips.techidaily.com/macdvd-burn/"><u>Mac用DVD Burnとディスクコピー: 専門家が推薦する方法</u></a></li>
<li><a href="https://vp-tips.techidaily.com/maintain-excellent-picture-clarity-while-reducing-the-size-of-your-8k-high-definition-footage/"><u>Maintain Excellent Picture Clarity While Reducing the Size of Your 8K High-Definition Footage</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/micromobility-world-dates-news-rumors-and-everything-else-to-know/"><u>Micromobility World: Dates, News, Rumors, and Everything Else To Know</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mp4-vs-avi-files-which-format-wins-the-video-quality-showdown/"><u>MP4 Vs. AVI Files: Which Format Wins the Video Quality Showdown?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pioneering-hardware-reviews-by-tom-your-trusted-source/"><u>Pioneering Hardware Reviews by Tom - Your Trusted Source</u></a></li>
<li><a href="https://vp-tips.techidaily.com/seamless-video-conversion-tutorial-transforming-mp4-files-into-flv-format-for-free/"><u>Seamless Video Conversion Tutorial: Transforming MP4 Files Into FLV Format for Free</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/slipping-into-the-social-scene-of-online-tiktok-gigs/"><u>Slipping Into the Social Scene of Online TikTok Gigs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solved-how-to-fix-iphone-connection-issues-during-itunes-backup-process/"><u>Solved: How to Fix iPhone Connection Issues During iTunes Backup Process</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solving-playback-timing-problems-fixing-offset-sound-on-digitized-video-files/"><u>Solving Playback Timing Problems: Fixing Offset Sound on Digitized Video Files</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-adding-voiceover-to-your-powerpoint-slides/"><u>Step-by-Step Guide: Adding Voiceover to Your PowerPoint Slides</u></a></li>
<li><a href="https://vp-tips.techidaily.com/streamline-video-storage-with-our-top-choice-for-shrinking-mov-files-into-mp4-avi-or-flv-formats/"><u>Streamline Video Storage with Our Top Choice for Shrinking MOV Files Into MP4, AVI, or FLV Formats</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-guide-choosing-the-right-ipod-mount-for-your-macbook-2020-edition/"><u>The Ultimate Guide: Choosing the Right iPod Mount for Your MacBook (2020 Edition)</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-tutorial-adding-emoticons-and-emojis-to-texts-on-apples-iphone/"><u>The Ultimate Tutorial: Adding Emoticons and Emojis to Texts on Apple's iPhone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-2022-movie-debuts-exclusive-list-of-latest-films-available-now-on-itunes/"><u>Top 2022 Movie Debuts: Exclusive List of Latest Films Available Now on iTunes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-80s-cinema-classics-secure-download-and-easy-backup-options/"><u>Top 80S Cinema Classics - Secure Download and Easy Backup Options</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-mac-os-x-mp3-konvertierungsprogramme-auf-youtube-20172018-gratis-herunterladen/"><u>Top Mac OS X MP3 Konvertierungsprogramme Auf YouTube (2017/2018) - Gratis Herunterladen</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/top-picks-the-ultimate-guide-to-the-best-17-inch-laptops/"><u>Top Picks: The Ultimate Guide to the Best 17-Inch Laptops</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-iphone-video-converter-apps-comprehensive-reviews/"><u>Top Rated iPhone Video Converter Apps: Comprehensive Reviews</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-lossless-encoder-for-ultra-hd-video-compression/"><u>Top Rated Lossless Encoder for Ultra HD Video Compression</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-ranked-fast-mac-video-conversion-tool-enhanced-by-cutting-edge-intel-quick-sync-technology/"><u>Top-Ranked Fast Mac Video Conversion Tool Enhanced by Cutting-Edge Intel Quick Sync Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-dvd-editor-programs-easy-trimming-cropping-and-compression-tools/"><u>Top-Rated DVD Editor Programs: Easy Trimming, Cropping & Compression Tools</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-samsung-galaxy-s23-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Samsung Galaxy S23 Screen | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/troubleshooting-made-easy-how-to-prevent-assassins-creed-valhalla-crashes-on-pc/"><u>Troubleshooting Made Easy: How to Prevent Assassin's Creed Valhalla Crashes on PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/troubleshooting-non-functioning-iphone-ringtone-solutions-effectively/"><u>Troubleshooting Non-Functioning iPhone Ringtone Solutions Effectively</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-the-ultimate-apple-gadgets-deal-get-your-free-20k-copies-with-macxdvds-iphone-ipad-video-converter-for-halloween/"><u>Unlock the Ultimate Apple Gadgets Deal - Get Your FREE 20K Copies with MacXDVD's iPhone iPad Video Converter for Halloween!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unraveling-the-differences-iphone-7-vs-iphone-7-plus-comparison-guide/"><u>Unraveling the Differences: IPhone 7 Vs. IPhone 7 Plus Comparison Guide</u></a></li>
</ul></div>
