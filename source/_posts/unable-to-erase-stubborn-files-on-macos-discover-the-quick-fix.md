---
title: Unable to Erase Stubborn Files on MacOS? Discover the Quick Fix!
date: 2024-08-31T08:55:46.803Z
updated: 2024-09-01T08:55:46.803Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/53526258387_b97fd9691e_o.jpg
---

## Unable to Erase Stubborn Files on MacOS? Discover the Quick Fix!

### Quick Links

* [What are Locked Files in MacOS?](https://twitter-videos.techidaily.com/updated-archive-awesome-perfecting-twitter-video-backups-for-2024/)
* [Unlocking Multiple Locked Files in a Folder](https://extra-resources.techidaily.com/getting-started-with-digital-image-detailing/)

 MacOS is arguably the most user-friendly desktop OS, but it's not perfect. There are a few things that can trip up users new and old, and one of them is unlocking multiple files in a folder so that they can be deleted. Here's two quick and easy ways to do it.

##  What are Locked Files in MacOS?

 In macOS, you can lock a file by right-clicking on it, clicking "Get Info", and checking the "Locked" checkbox.

![Locking a file in MacOS.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/locked.png) 

 Once locked, the file will display a little padlock on its icon, and you'll be [warned when you move it to the trash](https://support.apple.com/en-gb/guide/mac-help/mchlp1342/mac "https://support.apple.com/en-gb/guide/mac-help/mchlp1342/mac"). While locked files can be deleted from the trash, folders containing locked files cannot, and macOS isn't helpful in telling you where these locked files are actually located.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Unlocking Multiple Locked Files in a Folder

 Unlocking multiple files isn't difficult, you just need to un-check the "Locked" checkbox in the file info window, but doing this for multiple files in a folder is tedious. If you can search for the files and display all of them in a Finder window, you can press the Option-Command-I key combination to show their combined information, and toggle the locked status all at once, but this can still be cumbersome.

 So, here's a quick Terminal command that will unlock all files in a folder and its sub-folders:

chflags -R nouchg ~/path/to/folder

 Launch the Terminal app on your Mac to run this command (you'll find it under Applications > Utilities, or you can [search for it with Spotlight](https://some-tips.techidaily.com/2024-approved-the-essential-tutorial-from-gif-art-to-sticky-fun-on-social-media/)).

 The [**chflags**](https://ss64.com/mac/chflags.html "https://ss64.com/mac/chflags.html") command changes a file or folder's properties, the **\-R** option tells it to do so recursively (so, for all files, and files in folders inside the target folder), and the option **nouchg** tells the command to unlock files. The final part of the command is the path to the folder you want to unlock all the files in (you can get this by dragging the folder from Finder into the terminal window, and the path will be inserted for you).

---

 It's important to always fully understand exactly what a command will do to your computer before you run it. [The terminal is a powerful tool](https://video-screen-grab.techidaily.com/alternative-game-capture-software-no-more-fbx-dependence-for-2024/) that can be used to resolve a lot of problems, but it can also do a lot of damage if you don't check your input carefully.

 It's wise to regularly [back up your Mac](https://vimeo-videos.techidaily.com/updated-2024-approved-skyrocketing-video-performance-on-vimeo/) so that if something does go wrong, you can quickly recover your important data.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-hidden-gems-to-hit-videos-strategies-for-success/"><u>[New] 2024 Approved  From Hidden Gems to Hit Videos  Strategies for Success</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-ensuring-authenticity-and-compliance-in-your-tiktoks/"><u>[New] Ensuring Authenticity & Compliance in Your TikToks</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-jujutsu-kaisens-universe-on-your-tiktok-feed-for-2024/"><u>[New] Jujutsu Kaisen’s Universe on Your TikTok Feed for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-personalizing-teams-windows-for-effective-calls-for-2024/"><u>[New] Personalizing Teams Windows for Effective Calls for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-prime-10-terraria-game-enhancements-for-2024/"><u>[New] Prime 10 Terraria Game Enhancements for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-essence-of-elongated-images-through-iphone-writings/"><u>[New] The Essence of Elongated Images Through iPhone’ Writings</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-skies-in-4k-with-mi-drone/"><u>[Updated] Exploring Skies in 4K with MI Drone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-streaming-software-showdown-the-verdict-between-obs-and-bandicam/"><u>[Updated] In 2024, Streaming Software Showdown  The Verdict Between OBS and Bandicam</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-simplify-your-work-the-best-5-mac-snipper-applications-for-2024/"><u>[Updated] Simplify Your Work  The Best 5 Mac Snipper Applications for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-the-art-of-crafting-engaging-youtube-screen-closures/"><u>2024 Approved  Mastering the Art of Crafting Engaging YouTube Screen Closures</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-vivo-y17s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-realme-c55-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/beating-the-directx-error-in-fifa-20-techniques-and-solutions-unveiled/"><u>Beating the DirectX Error in FIFA 20: Techniques and Solutions Unveiled</u></a></li>
<li><a href="https://vp-tips.techidaily.com/convert-mts-videos-to-mp4-free-and-easy-compatible-with-iphoneipadipod-on-mac/"><u>Convert MTS Videos to MP4 Free & Easy: Compatible with iPhone/iPad/iPod on Mac</u></a></li>
<li><a href="https://win-solutions.techidaily.com/deciphering-and-solving-gta-5-starting-troubleshoot/"><u>Deciphering and Solving GTA 5 Starting Troubleshoot</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-frontiers-expanded-by-facebooks-advanced-moderation-tech/"><u>Digital Frontiers Expanded by Facebook's Advanced Moderation Tech</u></a></li>
<li><a href="https://vp-tips.techidaily.com/easy-steps-for-moving-your-files-and-photos-from-an-iphone-x-to-an-iphone-8-or-plus-model/"><u>Easy Steps for Moving Your Files and Photos From an iPhone X to an iPhone 8 or Plus Model</u></a></li>
<li><a href="https://vp-tips.techidaily.com/eliminating-unnatural-distortions-from-fisheye-footage-for-enhanced-video-quality/"><u>Eliminating Unnatural Distortions From Fisheye Footage for Enhanced Video Quality</u></a></li>
<li><a href="https://vp-tips.techidaily.com/get-the-latest-instagram-app-on-mac-comprehensive-tutorial-for-a-free-download/"><u>Get the Latest Instagram App on Mac - Comprehensive Tutorial for a FREE Download</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-t2-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo T2 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simple-setup-winning-the-art-of-fishy-voice-transformation/"><u>In 2024, Simple Setup  Winning the Art of Fishy Voice Transformation</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-uncover-clarity-a-detailed-guide-to-purging-backgrounds-with-affinity/"><u>In 2024, Uncover Clarity  A Detailed Guide to Purging Backgrounds with Affinity</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ipoditunes-isync/"><u>IPodがiTunesに同期できない？これが音楽リンクの究極解決策！ - iSyncスキルアップのポイント</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-os-x-unveiled-exploring-its-core-concepts-and-distinctive-traits/"><u>Mac OS X Unveiled: Exploring Its Core Concepts and Distinctive Traits</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-users-handbook-transforming-dvd-media-into-wmv-files-with-ease/"><u>Mac Users' Handbook: Transforming DVD Media Into WMV Files with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mac-friendly-top-5-dvd-management-tools-essential-picks-for-optimal-performance/"><u>Mac-Friendly Top 5 DVD Management Tools: Essential Picks for Optimal Performance</u></a></li>
<li><a href="https://vp-tips.techidaily.com/macdvd-burn/"><u>Mac用DVD Burnとディスクコピー: 専門家が推薦する方法</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mp4-vs-avi-files-which-format-wins-the-video-quality-showdown/"><u>MP4 Vs. AVI Files: Which Format Wins the Video Quality Showdown?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/online-broadcasting-basics-a-streamers-guide-to-capture-for-2024/"><u>Online Broadcasting Basics  A Streamer’s Guide to Capture for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-startup-problems-solutions-for-your-computer-failed-to-boot/"><u>Overcoming Startup Problems: Solutions for 'Your Computer Failed to Boot'</u></a></li>
<li><a href="https://vp-tips.techidaily.com/seamless-video-conversion-tutorial-transforming-mp4-files-into-flv-format-for-free/"><u>Seamless Video Conversion Tutorial: Transforming MP4 Files Into FLV Format for Free</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solved-how-to-fix-iphone-connection-issues-during-itunes-backup-process/"><u>Solved: How to Fix iPhone Connection Issues During iTunes Backup Process</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solving-playback-timing-problems-fixing-offset-sound-on-digitized-video-files/"><u>Solving Playback Timing Problems: Fixing Offset Sound on Digitized Video Files</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-how-to-obtain-broadcom-driver-downloads-quickly/"><u>Step by Step Guide: How to Obtain Broadcom Driver Downloads Quickly</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-adding-voiceover-to-your-powerpoint-slides/"><u>Step-by-Step Guide: Adding Voiceover to Your PowerPoint Slides</u></a></li>
<li><a href="https://vp-tips.techidaily.com/streamline-video-storage-with-our-top-choice-for-shrinking-mov-files-into-mp4-avi-or-flv-formats/"><u>Streamline Video Storage with Our Top Choice for Shrinking MOV Files Into MP4, AVI, or FLV Formats</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-essential-list-top-10-video-editors-to-elevate-reels/"><u>The Essential List  Top 10 Video Editors to Elevate Reels</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-guide-choosing-the-right-ipod-mount-for-your-macbook-2020-edition/"><u>The Ultimate Guide: Choosing the Right iPod Mount for Your MacBook (2020 Edition)</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-nokia-c22-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Nokia C22.</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-2022-movie-debuts-exclusive-list-of-latest-films-available-now-on-itunes/"><u>Top 2022 Movie Debuts: Exclusive List of Latest Films Available Now on iTunes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-iphone-video-converter-apps-comprehensive-reviews/"><u>Top Rated iPhone Video Converter Apps: Comprehensive Reviews</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-lossless-encoder-for-ultra-hd-video-compression/"><u>Top Rated Lossless Encoder for Ultra HD Video Compression</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-ranked-fast-mac-video-conversion-tool-enhanced-by-cutting-edge-intel-quick-sync-technology/"><u>Top-Ranked Fast Mac Video Conversion Tool Enhanced by Cutting-Edge Intel Quick Sync Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-dvd-editor-programs-easy-trimming-cropping-and-compression-tools/"><u>Top-Rated DVD Editor Programs: Easy Trimming, Cropping & Compression Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/troubleshooting-non-functioning-iphone-ringtone-solutions-effectively/"><u>Troubleshooting Non-Functioning iPhone Ringtone Solutions Effectively</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-the-ultimate-apple-gadgets-deal-get-your-free-20k-copies-with-macxdvds-iphone-ipad-video-converter-for-halloween/"><u>Unlock the Ultimate Apple Gadgets Deal - Get Your FREE 20K Copies with MacXDVD's iPhone iPad Video Converter for Halloween!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unraveling-the-differences-iphone-7-vs-iphone-7-plus-comparison-guide/"><u>Unraveling the Differences: IPhone 7 Vs. IPhone 7 Plus Comparison Guide</u></a></li>
</ul></div>
