---
title: Unable to Erase Stubborn Files on MacOS? Discover the Quick Fix!
date: 2024-08-26 16:40:13
updated: 2024-08-29 11:29:50
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
