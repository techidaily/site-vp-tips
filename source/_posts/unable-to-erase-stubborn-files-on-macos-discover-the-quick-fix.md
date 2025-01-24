---
title: Unable to Erase Stubborn Files on MacOS? Discover the Quick Fix!
date: 2025-01-17T16:02:28.867Z
updated: 2025-01-24T01:17:11.804Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/53526258387_b97fd9691e_o.jpg
---

## Unable to Erase Stubborn Files on MacOS? Discover the Quick Fix!

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What are Locked Files in MacOS?](https://twitter-videos.techidaily.com/updated-archive-awesome-perfecting-twitter-video-backups-for-2024/)
* [Unlocking Multiple Locked Files in a Folder](https://extra-resources.techidaily.com/getting-started-with-digital-image-detailing/)

 MacOS is arguably the most user-friendly desktop OS, but it's not perfect. There are a few things that can trip up users new and old, and one of them is unlocking multiple files in a folder so that they can be deleted. Here's two quick and easy ways to do it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What are Locked Files in MacOS?

 In macOS, you can lock a file by right-clicking on it, clicking "Get Info", and checking the "Locked" checkbox.

![Locking a file in MacOS.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/locked.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once locked, the file will display a little padlock on its icon, and you'll be [warned when you move it to the trash](https://support.apple.com/en-gb/guide/mac-help/mchlp1342/mac "https://support.apple.com/en-gb/guide/mac-help/mchlp1342/mac"). While locked files can be deleted from the trash, folders containing locked files cannot, and macOS isn't helpful in telling you where these locked files are actually located.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-from-monochrome-to-multicolor-learning-about-the-art-of-green-screens/"><u>[New] From Monochrome to Multicolor Learning About the Art of Green Screens</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-lit-tales-in-just-a-minute/"><u>[New] In 2024, Lit Tales in Just a Minute</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-optimizing-video-focus-in-virtual-collaboration-spaces-google-meet-edition/"><u>[New] In 2024, Optimizing Video Focus in Virtual Collaboration Spaces Google Meet Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-navigating-the-maze-of-tiktoks-bulk-video-transfer/"><u>[Updated] 2024 Approved Navigating the Maze of TikTok's Bulk Video Transfer</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-seamlessly-posting-online-content-to-ig-storypost/"><u>[Updated] 2024 Approved Seamlessly Posting Online Content to IG Story/Post</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-ultimate-guide-to-stunning-ig-video-creation/"><u>[Updated] 2024 Approved The Ultimate Guide to Stunning IG Video Creation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-comprehensive-analysis-mastering-the-art-of-video-editing-with-vivacut/"><u>[Updated] Comprehensive Analysis Mastering the Art of Video Editing With VivaCut</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-discovering-the-best-of-360-cams-pros-choice-roundup-2023/"><u>[Updated] Discovering the Best of 360° Cams Pros Choice Roundup, 2023</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-exclusive-screen-savers-best-12-with-unlimited-recording-for-2024/"><u>[Updated] Exclusive Screen Savers Best 12 with Unlimited Recording for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-exploring-next-gen-coding-is-av1-superior-to-vp9/"><u>[Updated] Exploring Next-Gen Coding Is AV1 Superior to VP9?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-demystifying-photo-editing-a-snapseed-introduction/"><u>[Updated] In 2024, Demystifying Photo Editing A Snapseed Introduction</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-hdr-mastery-the-complete-sdr-to-hdr-transformation/"><u>[Updated] In 2024, HDR Mastery The Complete SDR-to-HDR Transformation</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-art-of-audio-design-in-magix-vst-2023/"><u>2024 Approved The Art of Audio Design in Magix VST 2023</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-top-picks-iphone-solutions-for-effective-image-watermarks/"><u>2024 Approved Top Picks IPhone Solutions for Effective Image Watermarks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/audiophiles-guide-to-immersive-tales/"><u>Audiophile's Guide to Immersive Tales</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/elevating-virtual-meetings-using-zoom-proficiently-on-win11/"><u>Elevating Virtual Meetings Using Zoom Proficiently on Win11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-embracing-resilience-against-online-detractors/"><u>In 2024, Embracing Resilience Against Online Detractors</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-unleashing-the-power-of-youtube-finding-and-creating-partnerships/"><u>In 2024, Unleashing the Power of YouTube Finding and Creating Partnerships</u></a></li>
<li><a href="https://fox-that.techidaily.com/solve-the-problem-of-an-unresponsive-airpod-now/"><u>Solve the Problem of an Unresponsive AirPod Now!</u></a></li>
</ul></div>

