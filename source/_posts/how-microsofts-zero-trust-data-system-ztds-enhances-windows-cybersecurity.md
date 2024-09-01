---
title: How Microsoft's Zero Trust Data System (ZTDS) Enhances Windows Cybersecurity
date: 2024-08-31T08:56:18.401Z
updated: 2024-09-01T08:56:18.401Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/windows-11-logo.jpg
---

## How Microsoft's Zero Trust Data System (ZTDS) Enhances Windows Cybersecurity

DNS is one of the biggest weak points in our devices' networking. It's often used without encryption, which is a problem when DNS is responsible for convering web addresses into the required server IP addresses. Microsoft is now planning some changes to Windows that could make DNS more secure and less vulnerable to tampering.

 Microsoft has revealed a comprehensive new security system, called Zero Trust DNS (ZTDNS for short), aimed at significantly bolstering the security of the Domain Name System (DNS) within Windows networks. [DNS](https://instagram-clips.techidaily.com/new-2024-approved-revealing-the-top-10-hidden-story-supporters/), essential for translating human-friendly website names into numerical IP addresses, has long been plagued by security risks. ZTDNS promises to resolve this by providing encrypted and authenticated communication channels between client devices and DNS servers, while also empowering administrators to tightly control which domains those servers can resolve.

 Historically, enhancing DNS security has often meant sacrificing administrative visibility into network traffic. This forces admins to choose between unencrypted DNS with monitoring capability but lacking protection, or encrypted DNS that blinds monitoring and control. Microsoft's ZTDNS integrates the Windows DNS engine and Windows Firewall directly into client devices to overcome this problem.

 The ZTDNS system blocks client devices from connecting to any IP address except for those of designated "protective DNS servers." When a client device needs to resolve a domain name, it communicates with a protective DNS server, which can optionally use client certificates for fine-grained policy control. Upon resolution, ZTDNS dynamically updates the Windows Firewall to allow connections to the newly resolved IP addresses, while blocking all other traffic by default. This creates a powerful domain-name-based lockdown tool.

 You can think of this as a series of processes where the ultimate result is that you can only visit websites that have been specifically approved, creating a super-secure environment. This differs from regular DNS resolving in a few ways—namely, the way your DNS is currently set up means that it can resolve any URL into an IP address, even if it's known to be malicious (with possible consequences ranging from malware downloading to even a potential entry point for a malicious actor).

 There are also potential concerns about what might happen when this technology is actually deployed. Although it's a promising thing for your online safety, it will also probably require careful planning and configuration by administrators to avoid accidental disruption of normal network functions. After all, DNS is a core feature needed for Internet access, and the new system could overreach and block actually non-harmful things that you might need to use. The good thing is that this won't be rolled out just yet, so there's still a bit of time to figure out how to properly set up things so that your Internet experience won't be accidentally broken or disrupted in the process.

 ZTDNS requires that DNS servers support encryption protocols like DNS over HTTPS (DoH) or DNS over TLS (DoT). Microsoft highlights that ZTDNS does not introduce any new network protocols, which helps in making it broadly compatible. ZTDNS is currently in "private preview," according to Microsoft—it's not immediately clear if it's only being internally tested by the company at the moment or whether a few select users are/will be getting access to it. Microsoft has not given any indication of when ZTDNS might become publicly available, and for now, the company has just said that Windows Insiders will get access to it at their own time, with a separate announcement planned when the time comes.

 For now, if you want to read more about ZTDNS and what to take into account when the time for a real-life deployment comes, you can [check out Microsoft's blog post](https://techcommunity.microsoft.com/t5/networking-blog/deployment-considerations-for-windows-ztdns-client/ba-p/4113372) with all the details.

 Source: [Microsoft](https://techcommunity.microsoft.com/t5/networking-blog/announcing-zero-trust-dns-private-preview/ba-p/4110366) via [Ars Technica](https://arstechnica.com/security/2024/05/microsoft-plans-to-lock-down-windows-dns-like-never-before-heres-how/)

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-bandicam-a-user-centric-review-and-guide/"><u>[New] 2024 Approved  Bandicam   A User-Centric Review & Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-cyber-currents-videos-flow-on-twitter-wave/"><u>[New] 2024 Approved  Cyber Currents  Videos Flow on Twitter Wave</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-crafting-cinematic-experiences-with-magix-video-pro-x/"><u>[New] Crafting Cinematic Experiences with Magix Video Pro X</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-breakneck-speed-photo-display-on-your-pc/"><u>[New] In 2024, Breakneck Speed Photo Display on Your PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-overcome-low-quality-feed-fix-blurry-videos-on-social-media/"><u>[New] Overcome Low-Quality Feed  Fix Blurry Videos on Social Media</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-quick-easy-fun-4-steps-to-showcasing-your-favorite-gifs-on-instagram/"><u>[New] Quick, Easy, Fun  4 Steps to Showcasing Your Favorite GIFs on Instagram</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-10-game-recorder-software-list/"><u>[New] Top 10 Game Recorder Software List</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-increase-viewership-fairly-insights-for-video-marketers/"><u>[Updated] 2024 Approved  Increase Viewership Fairly  Insights for Video Marketers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-beyond-traditional-viewing-vr-movies-alteration-for-2024/"><u>[Updated] Beyond Traditional Viewing  VR Movies Alteration for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-bright-ideas-top-17-lighting-setups-for-youtubers-for-2024/"><u>[Updated] Bright Ideas  Top 17 Lighting Setups for YouTubers for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-eliminate-discomfort-quick-tips-to-beat-vr-sickness/"><u>[Updated] Eliminate Discomfort  Quick Tips to Beat VR Sickness</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-epicurean-education-recipe-film-making/"><u>[Updated] Epicurean Education  Recipe Film-Making</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-leverage-your-xbox-gameplay-for-virtual-engagement-on-fb/"><u>[Updated] In 2024, Leverage Your Xbox Gameplay for Virtual Engagement on FB</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-sound-top-10-microphones/"><u>[Updated] Mastering Sound  Top 10 Microphones</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-your-next-favorite-youtuber-might-be-just-a-test-away-six-categories-explored/"><u>[Updated] Your Next Favorite YouTuber Might Be Just a Test Away  Six Categories Explored</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2-claim-your-ultimate-access-pass-to-professional-macxdvd-software-a-complimentary-elevation/"><u>2. Claim Your Ultimate Access Pass to Professional MacXDVD Software – A Complimentary Elevation!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-broadcasting-conferences-with-no-expense-account/"><u>2024 Approved  Broadcasting Conferences with No Expense Account</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-cutting-edge-strategies-to-capture-dynamic-audio-in-video-projects/"><u>2024 Approved  Cutting-Edge Strategies to Capture Dynamic Audio in Video Projects</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-graphic-design-journeys-from-passion-to-profession/"><u>2024 Approved  Graphic Design Journeys  From Passion to Profession</u></a></li>
<li><a href="https://vp-tips.techidaily.com/avchdmp4mac/"><u>最適なAVCHDからMP4への変換：使えるMac専用無料ソフトをご紹介！</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-chatbot-realities-revealed-uncovering-and-busting-9-common-myths/"><u>AI Chatbot Realities Revealed: Uncovering and Busting 9 Common Myths</u></a></li>
<li><a href="https://vp-tips.techidaily.com/best-free-mac-video-compression-software-in-2-top-picks/"><u>Best Free Mac Video Compression Software in 2#! - Top Picks</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/beyond-hype-identifying-pitfalls-of-artificial-intelligence-implementation-for-business-success/"><u>Beyond Hype: Identifying Pitfalls of Artificial Intelligence Implementation for Business Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/comparing-the-best-iphone-7-and-htc-10-face-off-in-our-2016-top-handset-showdown/"><u>Comparing the Best: IPhone 7 and HTC 10 Face Off in Our 2016 Top Handset Showdown</u></a></li>
<li><a href="https://vp-tips.techidaily.com/compatible-video-types-and-maximum-sizes-on-whatsapp/"><u>Compatible Video Types and Maximum Sizes on WhatsApp</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-childrens-dance-music-from-youtube-no-cost-perfect-for-family-fun/"><u>Download Children's Dance Music From YouTube - No Cost, Perfect for Family Fun!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-elite-hd-movie-collection-for-mobile-best-of-hollywood-with-hindi-voiceover/"><u>Download Elite HD Movie Collection for Mobile - Best of Hollywood with Hindi Voiceover!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-high-quality-hd-4k-3d-videos-with-ultimate-360-video-grabber/"><u>Download High-Quality HD 4K 3D Videos with Ultimate 360° Video Grabber</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-the-ultimate-free-macdvd-to-mov-conversion-tool-effortless-mov-file-creation-on-your-mac/"><u>Download the Ultimate Free MacDVD-to-MOV Conversion Tool: Effortless Mov File Creation on Your Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-the-ultimate-selection-of-free-iphone-music-apps-for-endless-earful-enjoyment-at-no-cost/"><u>Download the Ultimate Selection of Free iPhone Music Apps for Endless Earful Enjoyment at No Cost</u></a></li>
<li><a href="https://vp-tips.techidaily.com/hd-webcam-recording-tutorial-capturing-high-quality-videos-on-mac/"><u>HD Webcam Recording Tutorial: Capturing High-Quality Videos on Mac</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-effortlessly-transform-iso-images-into-high-quality-mov-videos-for-mac-users/"><u>How To Effortlessly Transform ISO Images Into High-Quality MOV Videos for Mac Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-oppo-a79-5g-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Oppo A79 5G?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-from-start-to-finish-a-complete-guide-to-editing-mp4-videos-on-mac-and-windows/"><u>In 2024, From Start to Finish A Complete Guide to Editing MP4 Videos on Mac and Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-15-plus-with-7-methods-drfone-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for iPhone 15 Plus With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-laugh-ledger-top-10-tweets-for-a-smile/"><u>In 2024, Laugh Ledger  Top 10 Tweets for a Smile</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-virtuality-unleashed-insightful-reviews-of-top-10-pc-vr-streamers/"><u>In 2024, Virtuality Unleashed  Insightful Reviews of Top 10 PC VR Streamers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-xiaomi-redmi-note-12-pro-4g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Xiaomi Redmi Note 12 Pro 4G Phones</u></a></li>
<li><a href="https://vp-tips.techidaily.com/m4a-mp3-ac3-wma/"><u>M4A形式解説: MP3, AC3, WMAとの比較分析</u></a></li>
<li><a href="https://vp-tips.techidaily.com/macx-dvd-ripper-professional-secure-dvd-copying-and-itunes-compatible-mp4-files-extraction-for-apple-devices/"><u>MacX DVD Ripper Professional - Secure DVD Copying & iTunes Compatible MP4 Files Extraction for Apple Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/macx-pro-the-ultimate-no-cost-converter-for-apple-users-convert-secure-dvds-to-mp4-flv-efficiently-on-macos/"><u>MacX Pro: The Ultimate No-Cost Converter for Apple Users - Convert Secure DVDs to MP4, FLV Efficiently on macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-video-encoding-a-comprehensive-look-at-gpu-enhanced-handbrake-with-nvenc-technology/"><u>Mastering Video Encoding: A Comprehensive Look at GPU-Enhanced Handbrake with NVENC Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/nas-explained-comprehensive-guide-to-network-attached-storage-in-just-2-minutes/"><u>NAS Explained: Comprehensive Guide to Network Attached Storage in Just 2 Minutes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/premier-networks-for-your-personalized-watchlist/"><u>Premier Networks for Your Personalized Watchlist</u></a></li>
<li><a href="https://vp-tips.techidaily.com/resolving-handbrake-issues-for-mac-users-with-the-new-m1-chip-architecture/"><u>Resolving Handbrake Issues for Mac Users With the New M1 Chip Architecture</u></a></li>
<li><a href="https://vp-tips.techidaily.com/schritt-fur-schritt-anleitung-zur-behebung-von-problemen-mit-dem-dvd-laufwerk-auf-einem-mac-computer/"><u>Schritt-Für-Schritt-Anleitung Zur Behebung Von Problemen Mit Dem DVD-Laufwerk Auf Einem Mac Computer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solving-iphone-unresponsive-issue-with-apple-logo-post-ios-17-update-step-by-step-solutions/"><u>Solving iPhone Unresponsive Issue with Apple Logo Post-iOS 17 Update: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-guide-resolving-ghost-runner-game-errors-on-windows-10-pc/"><u>Step-by-Step Guide: Resolving Ghost Runner Game Errors on Windows 10 PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-sharing-files-between-your-iphone-and-mac-using-airdrop/"><u>Step-by-Step Guide: Sharing Files Between Your iPhone & Mac Using AirDrop</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-transforming-your-images-from-full-hd-1080p-to-ultra-high-definition-uhd4k/"><u>Step-by-Step Guide: Transforming Your Images From Full HD (1080P) to Ultra High Definition (UHD/4k)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-xiaomi-redmi-note-12-pro-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Xiaomi Redmi Note 12 Pro 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-downsides-of-sharing-your-youtube-content-via-tube2gram-on-instagram/"><u>The Downsides of Sharing Your YouTube Content via Tube2Gram on Instagram</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-essential-journey-to-fluent-japanese-greetings/"><u>The Essential Journey to Fluent Japanese Greetings</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-pioneer-bdr-xs06-portability-without-compromise-on-performance-in-high-quality-dvd-burning/"><u>The Pioneer BDR-XS06 - Portability Without Compromise on Performance in High-Quality DVD Burning</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-guide-to-5-leading-wmv-file-players-on-macos-systems/"><u>The Ultimate Guide to 5 Leading WMV File Players on macOS Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-nativity-movie-countdown-10-festive-flicks-your-little-ones-will-love/"><u>The Ultimate Nativity Movie Countdown: 10 Festive Flicks Your Little Ones Will Love</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-25-tips-to-boost-your-macs-performance-and-speed/"><u>Top 25 Tips to Boost Your Mac's Performance & Speed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-3-methoden-zum-herunterladen-von-youtube-videos-auf-mac-pc-und-iphone-als-mp3-oder-mp4/"><u>Top 3 Methoden Zum Herunterladen Von YouTube-Videos Auf Mac, PC Und iPhone Als MP3 Oder MP4</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-9-no-cost-mac-mp4-video-converters-comprehensive-reviews/"><u>Top 9 No-Cost Mac MP4 Video Converters: Comprehensive Reviews</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-compact-external-hard-drives-for-mac-users-looking-to-create-a-dvd-collection/"><u>Top Compact External Hard Drives for Mac Users Looking to Create a DVD Collection</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-video-converter-for-avchd-to-hevc-h265-files-free-download-options/"><u>Top Rated Video Converter for AVCHD to HEVC H.265 Files - Free Download Options!</u></a></li>
<li><a href="https://games-able.techidaily.com/tricks-for-classic-joy-con-integration/"><u>Tricks for Classic Joy Con Integration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-guide-to-converting-hevc-format-videos-with-ease/"><u>Ultimate Guide to Converting HEVC Format Videos with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlocking-the-power-of-amd-gpus-the-ultimate-guide-to-using-h264h265-video-transcoding/"><u>Unlocking the Power of AMD GPUs: The Ultimate Guide to Using H.264/H.265 Video Transcoding</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-guide-logitech-c920-camera-driver-for-new-windows-versions/"><u>Update Guide: Logitech C920 Camera Driver for New Windows Versions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/your-comprehensive-handbook-on-accessing-free-yoga-instructional-videos-suitable-for-everyone/"><u>Your Comprehensive Handbook on Accessing Free Yoga Instructional Videos - Suitable for Everyone!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/and-iphone/"><u>スマホでの曲カット&分割方法: IPhoneアプリを使った簡単な音楽編集テクニック</u></a></li>
<li><a href="https://vp-tips.techidaily.com/dvdwindowsdvd/"><u>ディズニーのDVDコピープロテクトなしにWindows上で効率的なDVDコピー -ステップバイステップ</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->