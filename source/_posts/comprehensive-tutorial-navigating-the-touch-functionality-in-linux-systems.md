---
title: "Comprehensive Tutorial: Navigating the Touch Functionality in Linux Systems"
date: 2025-01-19T16:40:34.428Z
updated: 2025-01-23T21:04:53.120Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e8e4a6d6a9bc5b040ff402928b53a2666775b46cc9d58e885cce92052d4219a2.jpg
---

## Comprehensive Tutorial: Navigating the Touch Functionality in Linux Systems

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is the touch Command?](https://extra-skills.techidaily.com/in-2024-photographic-lifelines-in-the-cloud-affordable-and-elite-storage-solutions/)
* [Creating Empty Files](https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-tecno-phantom-v-flip-frp-locks-by-drfone-android/)
* [Set the Access Time to the Current Time](https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-realme-12-pro-5g-by-drfone-android/)
* [Set the Modification Time to the Current Time](https://article-files.techidaily.com/updated-ultimate-8-gratis-4k-uhd-video-apps-for-pcos-x/)
* [Setting Access and Modification Times to Specific Times](https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-tecno-pova-6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Set Only One Time to a Specific Value](https://ios-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/)
* [Set the Access and Modification Times to Those of Another File](https://video-screen-grab.techidaily.com/2024-approved-perfecting-the-art-of-screen-recording-with-step-by-step-instructions-from-adobe-captivate/)
* [Don’t Create a File, Only Modify Existing Files](https://buynow-info.techidaily.com/tp-link-ac1200-wi-fi-range-extender-re305-review/)
* [A touch of Class](https://techtrends.techidaily.com/exploring-the-world-of-ray-tracing-techniques/)

### Key Takeaways

* The touch command updates access and modification times of files, useful for ensuring files are selected by backup routines and other processes.
* To create an empty file with touch, use a command like "touch new-file.txt".
* Use the -m flag to set the modification time to the current time, or the -a flag to set the access time to the current time.

 The touch command does more than make empty files. It updates access and modification times, ensuring routines like make scripts and backups include the files you want. Here’s how to use it.

##  What Is the touch Command?

 The touch command is part of the [GNU core utilities](https://www.gnu.org/software/coreutils/), and should be present on all Linux distributions. It’s an old tool, dating back to the late 1970s and the release of Unix version 7.

 I use it mostly as a quick and easy way to create files, but that’s actually a side effect of its main purpose. It allows you to set the access and modification times of files. It just so happens that its default action is to create the file too, if it doesn’t exist.

 touch overwrites a file’s metadata so that it looks like the file was accessed (opened and read), modified (had its contents changed), or both, at a certain time. It gives you quite a selection of ways to specify the times.

 Still, I’d guess its most common use probably leverages its happy side-effect of creating empty files.

##  Creating Empty Files

 Creating files with touch is child’s play.

        `touch new-file.txt  
touch ~/Documents/outlines/rough-outline.txt   
ls *.txt  
ls ~/Documents/outlines/*.txt`
    
![Using the touch command to create a new file from the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The files are created in their requested locations. They’re little more than a filename in the file system at this point,

        `ls -hl new-file.txt`
    
![Checking the newly created file actually exists, with ls on the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/2-1.png) 

 Our file definitely exists, even though it has a file size of zero bytes.

 To create multiple files, provide a list of their names on the command line.

        `touch new-file-2.txt new-file-3.txt new-file-4.txt   
ls *.txt `
    
![Using touch on the Linux command line to create multiple files at once.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/3.png) 

 If the files you’re going to create will have sequentially numbered names, you can create them all in one go like this.

        `touch even-more-files-{1..6}.txt   
ls even*  
`
    
![Using the topuch command to create sequentially numbered files on the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/4.png) 

##  Set the Access Time to the Current Time

 We’re going to be using a sample file to demonstrate the use of touch. We can use the [stat command](https://extra-information.techidaily.com/explore-free-virtual-music-pulse-analyzers/) to see what its timestamps are.

        `stat sample-file.txt`
    
![Using the stat command to display the access and moficiation timestamps of a file, on the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/5.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Its access timestamp is 14:32:47 on Aug. 5, 2024, and its modification timestamp is midnight on July 20, 2024.

 To set the access time to the current PC time, we use the -a (access) option.

        `touch -a sample-file.txt  
stat sample-file.txt`
    
![Using the touch command to set a file's access time to the current PC time, on the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The access timestamp has been changed to 10:42:00 on Aug. 6, 2024.

 Note that the change timestamp has been updated too. This is the time that the file was last changed, by any means. Setting new file permissions, for example, would be enough to update the change timestamp. Updating the access timestamp is a change, so the change timestamp gets refreshed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Set the Modification Time to the Current Time

 Setting the modification time is just as straightforward, but we use the -m (modify) option.

        `touch -m sample-file.txt  
stat sample-file.txt`
    
![Using the touch command to set a file's modification time to the current PC time, on the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/7.png) 

 Our modiffication timestamp is now showing 10:42:50 on Aug. 6, 2024.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Setting Access and Modification Times to Specific Times

 There are two ways to set both the access and the modification timestamps to a time of your choosing. That is, they don’t get set to the current PC time, they get set to the time and date value you provide on the command line.

 The only difference between them is the format you supply the time and date on the command line.

 The -d (date) option accepts a string formatted in a free format, human-readable style, like ‘Wed, 7 August 2024 16:00:00’ or “2024-7-11 16:00:00”, or even phrases like “next Sunday.”

 The -t (stamp) option requires a different, less friendly format. The format is:

        `[CC]YY]MMDDhhmm[.ss]`
    
 That’s century, century, year, year, then month, day, hour, minute, and seconds. Seconds, century, and year figures are optional. A period “.” is used to separate the seconds from the minutes.

 If you provide a year, the century figures are optional, and this century is assumed.

 Let’s use the -d option first.

        `touch -d "Wed, August 7 2024 16:00:00" sample-file.txt   
stat sample-file.txt `
    
![Using the touch -d option to set the access and modifcation times to a user specified time.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/8.png) 

 We’ll set the access and modify timestamps to midnight, on Halloween this year.

        `touch -t 2410310000.00 sample-file.txt  
stat sample-file.txt`
    
![Using the touch -t option to set the access and modifcation times to a user specified time.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/9.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Set Only One Time to a Specific Value

 The -t and -d options work on both timestamps at once. The -a and -m set a single timestamp, but to the current time, not a user-specified time.

 What about the case where you want to set a single timestamp to an arbitrary time? We can achieve that too. It’s simple, but a little counter-intuitive.

 Combining either the -a or -m options with one of the -t or -d options allows you to provide a time on the command line that applies to only the access or modification timestamps.

 Here’s an example. We’re going to set the modification timestamp to 1145 on December 21st of this year, 2024, which happens to be the shortest day of the year.

 Using the -t format string, we can write this as 12211145.00\. We’re not providing the CC or YY components, so touch will assume we mean the current year.

 Note that we're using both the -m and the -t options here. The -m option must come first.

        `touch -mt 12211145.00 sample-file.txt  
stat sample-file.txt`
    
![Using the touch -mt options to set the modifcation time to a user specified time.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/10.png) 

 We could do the same thing with the access timestamp, by using -at in the command.

##  Set the Access and Modification Times to Those of Another File

 We can tell touch to take the timestamps from an existing file and replicate them on a target file.

 This let’s you set the timestamps of a file or group of files to a existing file that you know has the timestamps you want. It saves you figuring out how to write the timestamps in either the -d or -t formats, and typing the format string on the command line.

 We have a file called reference-file.txt. These are its timestamps.

        `stat reference-file.txt`
    
![Using the stat fil;command to display the timestamps of a reference text file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/11.png) 

 We’ll apply these timestamps to our target file, and create another file called sample-2.txt at the same time. Our new file will have the timestamps from reference-file.txt applies to it too, instead of its actual creation time.

        `touch -r reference-file.txt sample-file.txt sample-2.txt  
stat sample-file.txt sample-2.txt`
    
![Using the touch command to copy the timestamps from a reference file to an existing file, and a newly created file, from the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/12.png) 

 We can see that touch applies the access and modification timestamps from the reference file to our existing and new files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Don’t Create a File, Only Modify Existing Files

 Sometimes, you don’t want touch to create a file if it doesn’t exist. You can override its default action by including the -c (no create) option.

        `ls missing-in-action.txt  
touch -c -mt 202409170900.00 sample-file.txt missing-in-action.txt  
stat sample-file.txt  
ls missing-in-action.txt`
    
![Using the -c option to supress the touch command's default action of creating missing files, from the Linux command line.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/13.png) 

 We verify that the missing-in-action.txt file doesn’t exist, then ask touch to update the modification timestamps of sample-file.txt and missing-in-action.txt, but only if they exist.

 We can see that the modification timestamp of sample-file.txt has been changed, but the missing-in-action.txt hasn’t been created.

##  A touch of Class

 You can create files using other techniques, such as redirection or cat, but those methods don't let you easily create multiple files like touch does. And only touch can set the file timestamps to whatever you want.

 It's that level of finesse that sets touch apart.

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
<li><a href="https://vp-tips.techidaily.com/new-excellent-envoys-top-laptops-to-edit-videos-in-4k-for-2024/"><u>[New] Excellent Envoys Top Laptops to Edit Videos in 4K for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-the-visual-narrative-crafting-your-podcasts-brand-image/"><u>[New] In 2024, The Visual Narrative Crafting Your Podcast's Brand Image</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-story-whats-not-in-public-knowledge-in-2024/"><u>[New] Instagram Story What's Not in Public Knowledge, In 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-master-easy-magnification-on-ios-devices/"><u>[New] Master Easy Magnification on iOS Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unlocking-the-potential-of-av1-technology/"><u>[New] Unlocking the Potential of AV1 Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unveiling-the-process-of-batched-tiktok-content-extraction-for-2024/"><u>[New] Unveiling the Process of Batched TikTok Content Extraction for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-mastering-the-nuances-of-softening-sounds-via-lumafusion/"><u>[Updated] 2024 Approved Mastering the Nuances of Softening Sounds via Lumafusion</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-setting-up-your-google-meet-profile/"><u>[Updated] 2024 Approved Setting Up Your Google Meet Profile</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-peak-visionary-suite-feedback/"><u>[Updated] Peak Visionary Suite Feedback</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-premier-networks-global-gems-with-local-spectacles-2024/"><u>[Updated] Premier Networks Global Gems with Local Spectacles, 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-be-amongst-the-few-essential-metaverse-technology/"><u>2024 Approved Be Amongst the Few Essential Metaverse Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/asus-proart-pa-329q-a-deep-dive-into-high-resolution-monitoring-for-2024/"><u>Asus ProArt PA 329Q A Deep Dive Into High-Resolution Monitoring for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/discover-the-7-leading-dvd-compression-tools-as-an-alternative-to-dvd-shrink-in-windows-1011/"><u>Discover the 7 Leading DVD Compression Tools as an Alternative to DVD Shrink in Windows 10/11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-detailed-review-obs-as-a-top-choice-for-screen-recorders/"><u>In 2024, Detailed Review OBS as a Top Choice for Screen Recorders</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/no-more-glitches-effective-solutions-for-stabilizing-age-of-wonders-planetfall-on-your-computer/"><u>No More Glitches: Effective Solutions for Stabilizing 'Age of Wonders: Planetfall' On Your Computer</u></a></li>
<li><a href="https://win-reviews.techidaily.com/transfer-learning-materials-from-artistworks-as-high-quality-mp4-files/"><u>Transfer Learning Materials From ArtistWorks as High-Quality MP4 Files</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win-1110-driver-fix-ms-bd-update/"><u>Win 11/10 DRIVER Fix: MS BD Update</u></a></li>
</ul></div>

