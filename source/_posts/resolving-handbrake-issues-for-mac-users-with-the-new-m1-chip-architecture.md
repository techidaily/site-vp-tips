---
title: Resolving Handbrake Issues for Mac Users With the New M1 Chip Architecture
date: 2024-08-24 23:33:57
updated: 2024-08-27 11:12:54
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
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-go.jpg)](https://pinterest.com/pin/create/button/?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm&title=&summary=https://www.macxdvd.com/mac-dvd-video-converter-how-to/handbrake-m1-mac.htm&source=)

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

srouce: bit.ly/344eDx6

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

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps him build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.



Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

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
