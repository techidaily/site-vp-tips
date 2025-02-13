---
title: Resolving Handbrake Issues for Mac Users With the New M1 Chip Architecture
date: 2025-02-06T23:59:29.645Z
updated: 2025-02-13T02:35:32.661Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/25f844691822ba4cb5e360ab99f911dddda24c96d9c140ba9ad85b4664a5d151.png
---

## Resolving Handbrake Issues for Mac Users With the New M1 Chip Architecture

[![macx dvd ripper pro icon](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon12.png)](https://tools.techidaily.com/macxdvd/products/)

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [Guide](https://tools.techidaily.com/macxdvd/products/)
* [Support](https://tools.techidaily.com/macxdvd/products/)
* [Free Download](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon7.png) [Home](https://tools.techidaily.com/macxdvd/products/) \> [DVD](https://tools.techidaily.com/macxdvd/products/) \> [Rip DVDs](https://tools.techidaily.com/macxdvd/products/) \> Handbrake Apple Silicon Mac 

## Does Handbrake Run on M1 Mac? Fixes Handbrake Errors on M1 Macs

_Summary: Handbrake VideoToolbox encoder is not using the GPU on M1 MacBook Pro/Air, iMac, or mini? Why Handbrake libdvdcss isn’t working properly on M1 Pro/Max? How to convert protected DVDs on Apple Silicon Macs easily?_

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon6.png) By [Bella Brown](https://tools.techidaily.com/macxdvd/products/) ｜Last updated on January 22, 2022 

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-fa.jpg)](https://www.facebook.com/sharer/sharer.php?u=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-tw.jpg)](https://twitter.com/intent/tweet?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-go.jpg)](https://pinterest.com/pin/create/button/?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm&title=&summary=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm&source=)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Apple's silicon SoC M-series chips have been used on several Mac models, including MacBook Pro, iMac, MacBook Air, and mini released since 2020\. The good news is that Handbrake released V1.4.0 with the support for Apple Silicon based Macs. However, there are still users getting errors when using Handbrake on M1 Pro/Max Mac. In this article, we’ll talk about Handbrake libdvdcss, videotoolbox, errors, etc. on M1 Macs.

![install Handbrake libdvdcss 64 bit windows](https://www.macxdvd.com/mac-dvd-video-converter-how-to/article-image/handbrake-m1-mac.jpg) 

srouce: bit.ly/344eDx6

### Does Handbrake work with M1 Macs?

Yes, Handbrake add the support to Apple Silicon based Macs since V1.4.0\. If your Handbrake won't work properly on an Apple silicon Mac, try to download the latest Handbrake.

### Does Handbrake use VideoToolBox on M1 Macs?

_"My M1 iMac throttles down Handbrake to 300% CPU with the CPU temperature went up to 93/94 degrees celsius. The encoding takes nearly 2.5 times than before. Does Handbrake support hardware encoding on the M1 Pro/Mx Socs?"_

_"I'm also facing serious performance issues with Handbrake on M1 Max 16-in MKB encoding with Videotoolbox. Handbrake is using the M1 CPU at 98% but the GPU idles at under 10%. Does Handbrake take advantage of the GPU in the M1 Macs?"_

Handbrake can use the hardware acceleration on M1 Mac if you choose a VideoToolbox encoder. However, the VideoToolbox is Apples Abstract API for hardware encoder(s). It's not a GPU encoder and does not in any way accelerate x264 or x265 encoders. Therefore, the audio decoding/encoding, video filtering (crop and scale, etc.) and sometimes video decoding also run on the CPU. 

More than that, Handbrake VideoToolbox encoding has been broken on Mac M1 Pro/Max running macOS Monterey. According to the investigated results provided by M1 Mac users, Handbrake VideoToolbox h.265 encoder shows a lower performance on M1 Pro and Max, with significantly slower speed and higher CPU usage. 

### Handbrake DVD ripping errors on M1 Macs?

When some users start to rip DVDs on Apple Silicon M1 Macs using Handbrake, errors occur. Some M1 Macs reboots with frozen mouse, no error/warning messages. Sometimes, it won't read a DVD with "no valid source found" error messages. All the problems happen when libdvdcss is installed on the M1 Macs for Handbrake. Using handbrake to rip copy-protected disks is not supported. But it can handle DVD encryptions with libdvdcss. But it seems that Handbrake can't recognize/use the libdvdcss properly when ripping a protected DVD. Why [Handbrake libdvdcss won't work](https://tools.techidaily.com/macxdvd/products/)on M1 Macs?

First, the Apple Silicon M1 is an ARM-based architecture similar to the A-series chips used in iPhones and iPads for years now. If you download and install an x86 64-bit version of libdvdcss on an M1 Mac, Handbrake can't use it. Then you need to download an Arm architecture-compatible version of libdvdcss. Here is how to install an ARM version libdvdcss via Homebrew: 

![install Handbrake libdvdcss 64 bit windows](https://www.macxdvd.com/mac-dvd-video-converter-how-to/article-image/arm-libdvdcss.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

srouce: bit.ly/344eDx6

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Easily Rip Protected DVDs on M1 Macs with Handbrake Alternative 

[**MacX DVD Ripper Pro**](https://tools.techidaily.com/macxdvd/products/)is able to rip any protected DVDs on M1 Max/Pro MacBook Pro, iMac, MacBook Air, and mini**[](https://tools.techidaily.com/macxdvd/products/)** without downloading any libdvdcss or other third-party software: 

* **Decrypt DVDs protected by region codes,**  bad sectors, 99 titles, CSS, RCE, UOPs, ARccOS, Disney fake, etc.
* **Convert DVDs to MP4**, H.264, HEVC, MOV, AVI, MKV, MPEG, iPhone, iPad, Android, Chromecast, Plex, 420+ profiles.
* **1:1** Backup DVD with main/full title to single MPEG-2 file; copy DVD to ISO image.
* **5x faster** than Handbrake with GPU (Intel/Nvidia/AMD) hardware acceleration tech.

[Download for Mac](https://tools.techidaily.com/macxdvd/products/) [Download for PC](https://tools.techidaily.com/macxdvd/products/) 

_Notice: We only advocate copying and ripping DVDs under the concept of Fair Use and do not encourage any illegal reproduction or distribution of copyrighted content. Please abide by the local DVD copyright law before ripping any DVD._ 

Still have any problem on how to use Handbrake on Apple Silicon M1 Macs, just [email us >>](https://tools.techidaily.com/macxdvd/products/)

Tags: [DVD](https://tools.techidaily.com/macxdvd/products/) [Rip DVDs](https://tools.techidaily.com/macxdvd/products/) Handbrake M1 Mac 

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/bella.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps him build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.

Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

[How to Make Handbrake Decrypt DVD Protection](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

[How to Download and Install Handbrake Successfully on PC/Mac](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

[Struggling with HandBrake Won't Scan DVD Problems? Fixes Here!](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[Can Handbrake Skip Bad Sectors? Answer is Here!](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

[Handbrake Error Reading from DVD Tackled!](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

[Handbrake doesn't Convert Whole Movie? Fixed Here!](https://tools.techidaily.com/macxdvd/products/) 

![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

### Company

* [About Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Tech & Sales FAQ >>](https://tools.techidaily.com/macxdvd/products/)
* [User Guides >>](https://tools.techidaily.com/macxdvd/products/)
* [Contact Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Partner >>](https://tools.techidaily.com/macxdvd/products/)

[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

Copyright © 2024 Digiarty Software, Inc (MacXDVD). All rights reserved

Apple, the Apple logo, Mac, iPhone, iPad, iPod and iTunes are trademarks of Apple Inc, registered in the U.S. and other countries.  
Digiarty Software is not developed by or affiliated with Apple Inc.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-dissecting-popularity-ten-facts-about-reels-unmasked/"><u>[New] 2024 Approved Dissecting Popularity Ten Facts About Reels, Unmasked</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-crafting-videos-with-precision-leveraging-storyremix-in-windows-11/"><u>[New] Crafting Videos with Precision Leveraging StoryRemix in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-maintain-a-shadowy-presence-on-instagram-livestreams/"><u>[New] How to Maintain a Shadowy Presence on Instagram Livestreams</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-top-7-social-media-screen-grabs/"><u>[New] Top 7 Social Media Screen Grabs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-insights-the-best-apps-to-supercharge-your-profile/"><u>[Updated] Instagram Insights The Best Apps to Supercharge Your Profile</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-creative-potential-using-luts-for-color-grading-in-ae/"><u>2024 Approved Unlocking Creative Potential Using LUTs for Color Grading in AE</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/anticipating-innovations-at-apple-event-dive-into-exclusives-on-the-m4-powered-mac-mini-revamped-ipads-and-leaps-forward-in-smart-assistants-the-digital-gur85/"><u>Anticipating Innovations at Apple Event - Dive Into Exclusives on the M4 Powered Mac Mini, Revamped iPads and Leaps Forward in Smart Assistants | The Digital Guru Blog</u></a></li>
<li><a href="https://vp-tips.techidaily.com/conversione-gratuita-da-dts-a-mp4-con-movavi-soluzione-veloce-ed-efficace/"><u>Conversione Gratuita Da DTS a MP4 Con Movavi - Soluzione Veloce Ed Efficace</u></a></li>
<li><a href="https://vp-tips.techidaily.com/flac-mp3-on/"><u>FLAC 파일을 MP3로 원형으로 자유롭게 전환하는 방법 - Onラ인</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-networked-video-streaming-with-vlc/"><u>In 2024, Navigating Networked Video Streaming with VLC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/is-picku-eclipse-in-the-best-photo-editor-arena-for-android-devices/"><u>Is PickU Eclipse in the Best Photo Editor Arena for Android Devices?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/los-top-12-escogidos-para-la-postproduccion-de-video-en-2024-opciones-economicas-y-premium/"><u>Los Top 12 Escogidos Para La Postproducción De Video en 2024: Opciones Económicas Y Premium</u></a></li>
<li><a href="https://vp-tips.techidaily.com/m4v-to-avi-file-conversion-quick-simple-and-no-cost-solution-by-movavi/"><u>M4V to AVI File Conversion - Quick, Simple & No Cost Solution by Movavi</u></a></li>
<li><a href="https://vp-tips.techidaily.com/movavim4a-wav/"><u>Movaviで無料で行える、オンラインM4A WAV音声コンバートツール</u></a></li>
<li><a href="https://vp-tips.techidaily.com/registrati-per-una-chiamata-di-videoprezzo-su-whatsapp-tecniche-piu-efficaci-nel-2024/"><u>Registrati per Una Chiamata Di Videoprezzo Su WhatsApp - Tecniche Più Efficaci Nel 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/tod-movavi/"><u>オンラインTODファイルの転送 -MOVAVIで自由に変換する方法</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1726223215216-mp4mov-movavi/"><u>オンラインで手軽にMP4/MOVファイルを無料で変換: Movaviの紹介</u></a></li>
</ul></div>

