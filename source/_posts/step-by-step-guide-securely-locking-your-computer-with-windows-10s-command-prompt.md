---
title: "Step-by-Step Guide: Securely Locking Your Computer with Windows 10'S Command Prompt"
date: 2024-08-31T08:54:41.684Z
updated: 2024-09-01T08:54:41.684Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Step-by-Step Guide: Securely Locking Your Computer with Windows 10'S Command Prompt

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-film-fanatics-dream-the-ultimate-list-of-free-movies-streaming-on-youtube-for-2024/"><u>[New] Film Fanatics' Dream – The Ultimate List of Free Movies Streaming on YouTube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-quality-360-cameras-for-youtube-and-facebook-coverage/"><u>[New] High-Quality 360° Cameras for YouTube & Facebook Coverage</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-why-no-sound-the-twitter-video-amplification-guide-for-2024/"><u>[New] Why No Sound? The Twitter Video Amplification Guide for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-boost-your-content-quality-the-ultimate-guide-for-impressive-mac-made-tiktok-openers/"><u>[Updated] 2024 Approved  Boost Your Content Quality  The Ultimate Guide for Impressive Mac-Made TikTok Openers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unite-your-photos-cross-platform-instagram-collage/"><u>[Updated] 2024 Approved  Unite Your Photos  Cross-Platform Instagram Collage</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-captured-kinetics-mastering-the-art-of-twitvid-download/"><u>[Updated] Captured Kinetics  Mastering the Art of TwitVid Download</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-can-you-view-all-shared-videos-and-photos-on-messenger-for-2024/"><u>[Updated] How Can You View All Shared Videos And Photos on Messenger for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/macx-dvd-ripper-pro-winverdvd/"><u>[オフィシャル] MacX DVD Ripper Pro WinVer：迅速なデジタル化おすすめDVDコピーツール</u></a></li>
<li><a href="https://vp-tips.techidaily.com/dvddvd/"><u>【対策】高画質に変更! DVDを焼く際の画質低下・解決法とDVD書き込みソフトのおすすめ</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1-free-macdvd-to-music-converter-effortless-mp3mp4-extraction-from-dvds-using-macx/"><u>1. Free MacDVD-to-Music Converter: Effortless MP3/MP4 Extraction From DVDs Using MacX</u></a></li>
<li><a href="https://vp-tips.techidaily.com/cprm-mac-cprm/"><u>最新CPRM自由化ソフト Mac版お薦め - 快適にCPRMキャッシュ解除</u></a></li>
<li><a href="https://vp-tips.techidaily.com/digiartymacdvdand/"><u>Digiarty製Mac向けDVDコピー&ビデオ変換ソフトウェア最新版が登場</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-romantic-valentines-anthems-create-and-enjoy-a-personalized-love-song-collection/"><u>Download Romantic Valentine's Anthems: Create & Enjoy a Personalized Love Song Collection</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-the-ultimate-list-top-ranking-b-movies-from-history-no-charge/"><u>Download the Ultimate List: Top-Ranking B-Movies From History - No Charge</u></a></li>
<li><a href="https://vp-tips.techidaily.com/easy-guide-removing-apple-music-playlists-on-your-iphone-without-losing-tracks/"><u>Easy Guide: Removing Apple Music Playlists on Your iPhone Without Losing Tracks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/essential-guide-converting-videos-with-mpeg-streamclip-on-your-mac/"><u>Essential Guide: Converting Videos with MPEG StreamClip on Your Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/essential-guide-how-to-seamlessly-transform-mov-files-into-various-formats-like-mp4-and-flv-on-a-mac-using-top-converters/"><u>Essential Guide: How to Seamlessly Transform MOV Files Into Various Formats Like MP4 & FLV on a Mac Using Top Converters</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/exploring-the-best-tools-for-video-recording-a-bandicam-vs-camtasia-review/"><u>Exploring the Best Tools for Video Recording  A Bandicam Vs Camtasia Review</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/get-ready-to-connect-your-ai-conversation-guide/"><u>Get Ready to Connect: Your AI Conversation Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/gunstige-methode-geschutzte-dvds-mit-dem-mac-x-dvd-ripper-kostenlos-zu-extrahieren/"><u>Günstige Methode, Geschützte DVDs Mit Dem Mac X DVD Ripper Kostenlos Zu Extrahieren</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-solve-the-leaf-error-in-apex-legends-fix-guide-2022/"><u>How to Solve the 'Leaf' Error in Apex Legends (Fix Guide - 2022)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-samsung-galaxy-xcover-6-pro-tactical-edition-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Samsung Galaxy XCover 6 Pro Tactical Edition Through Google Earth?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-nokia-c210-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-infinix-smart-8-hd-by-drfone-android/"><u>In 2024, How to Bypass FRP from Infinix Smart 8 HD?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-y78plus-t1-edition-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo Y78+ (T1) Edition Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ios-17-downgrade-tutorial-switching-back-to-ios-eb-934-on-apple-devices-with-ease/"><u>IOS 17 Downgrade Tutorial: Switching Back to iOS Eb 9.3.4 on Apple Devices with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-xdvd-essentials-uncovering-top-solutions-and-guides-for-dvd-management/"><u>Mac XDVD Essentials: Uncovering Top Solutions and Guides for DVD Management</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-dvd-burning-craft-your-own-photo-discs-using-idvd/"><u>Mastering DVD Burning: Craft Your Own Photo Discs Using iDVD</u></a></li>
<li><a href="https://vp-tips.techidaily.com/optimize-your-movie-collection-with-dvd-shrink-pro-seamless-dvd-conversion-for-mac-users/"><u>Optimize Your Movie Collection with DVD Shrink Pro: Seamless DVD Conversion for Mac Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/optimizing-video-compression-maintain-quality-while-shrinking-file-size-on-your-mac/"><u>Optimizing Video Compression: Maintain Quality While Shrinking File Size on Your Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/quickest-and-easiest-intel-accelerated-video-conversion/"><u>Quickest & Easiest Intel Accelerated Video Conversion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-safeguarding-your-iphones-camera-roll-images-with-easy-backups/"><u>Step-by-Step Guide: Safeguarding Your iPhone's Camera Roll Images with Easy Backups</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-the-top-pick-of-gaming-keyboards-featuring-full-half-and-mini-sizes/"><u>The Ultimate Guide to the Top Pick of Gaming Keyboards : Featuring Full, Half & Mini Sizes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/troubleshooting-itunes-album-thumbnails-failure-in-sync-with-ios-devices-expert-solution/"><u>Troubleshooting iTunes Album Thumbnails Failure in Sync with iOS Devices - Expert Solution!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-guide-how-to-download-and-convert-youtube-videos-with-ease/"><u>Ultimate Guide: How to Download & Convert YouTube Videos with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unterstutzte-medientypen-fur-iphone-7-and-plus-unter-ios-version-10/"><u>Unterstützte Medientypen Für iPhone 7 & Plus Unter iOS Version 10</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-v27-pro-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo V27 Pro Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1724765909516-18/"><u>デジアーティー 18周年記念限定プロジェクトをご紹介</u></a></li>
</ul></div>
