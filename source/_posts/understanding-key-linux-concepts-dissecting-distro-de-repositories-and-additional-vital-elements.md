---
title: "Understanding Key Linux Concepts: Dissecting Distro, DE, Repositories, and Additional Vital Elements"
date: 2024-08-27 16:25:46
updated: 2024-08-29 11:53:57
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Understanding Key Linux Concepts: Dissecting Distro, DE, Repositories, and Additional Vital Elements

Are you new to Linux and feeling overwhelmed by all the jargon in the software stores, forums, and tutorials? Fear not, as in this article, I’ll explain essential Linux terminologies so you can confidently take part in Linux discussions.

##  The Linux Kernel

**The Linux Kernel** is the primary interface for all hardware-software interactions on your Linux operating system (OS). It enables software applications to efficiently utilize system hardware like processors, memory, peripherals, and more.

 It’s updated regularly to patch security issues, add support for new hardware, and [occasionally remove support](https://www.phoronix.com/news/Linux-Remove-a.out?%5F%5Fcf%5Fchl%5Ftk=4LG5PnOfJmzD8nZgFWmpm4e7XVCOlle5QBps0eBaw0k-1707836600-0-4133) for outdated and unused architectures. For instance, support for AMD’s Ryzen CPUs was added with [Linux Kernel version 4.10](https://www.pcworld.com/article/412265/kernel-410-gives-linux-support-for-zen-multithreading.html). Older Kernel versions would experience problems running the processor.

 To check your system's Linux Kernel version, type “uname -r” in the terminal.

![Checking Linux Kernel version in Ubuntu 22.04 through terminal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/checking-linux-kernel-version-in-ubuntu-22-04-through-terminal.png) 

 While some Linux distributions automatically update the kernel, others may require a manual OS update to access the latest version. As a rule of thumb, if you aren’t running bleeding-edge hardware, you should be fine with the default kernel version and routine updates you receive from your Linux distros.

##  Linux Distributions (Distros)

**Linux distributions**, or distros, are tailored operating systems built around the Linux Kernel, targeting specific users or user preferences. The term “distribution” stems from the early days of Linux, when people and organizations adopted the Linux kernel, bundled in additional tools and software–package managers, desktop environments, custom tweaks—and “distributed” it as a fully functional and cohesive operating system.

 Each Linux distro offers a unique out-of-the-box experience, thus favoring certain workflows over others. For example, Ubuntu is a stable general-purpose distro, whereas Garuda Linux is focused on gaming and cutting-edge software.

![Ubuntu 23.10 Default desktop](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/ubuntu-23-10-default-desktop.png) 

![The Garuda Linux Desktop.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/garuda-linux-desktop.png) 

Close 

[New to Linux? Ubuntu Isn't Your Only Option](https://facebook-record-videos.techidaily.com/updated-in-2024-elite-gamers-capturing-solutions/) 

##  Desktop Environments (DE)

**A desktop environment** is a collection of components that build the common graphical user interface (GUI). This includes icons, panels, taskbars, wallpapers, widgets, and, most importantly, the window manager–a system software that controls the placement and appearance of application windows.

 Unless you need [a "headless" server](https://digital-screen-recording.techidaily.com/updated-capture-the-thrill-mastering-4-techniques-of-xbox-screen-recording-for-2024/), it’s super important to focus on the DE while picking a Linux distro. It’ll dictate how you open apps, multitask, customize the appearance, and more.

![Ubuntu 23.10 overview feature and virtual desktop switcher-2](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/ubuntu-23-10-overview-feature-and-virtual-desktop-switcher-2.png) 

![Garuda Linux Mac-inspired workflow with Appmenu in panel, left-side windows button, and a dock for launching apps.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/garuda-linux-mac-inspired-workflow-with-appmenu-in-panel-left-side-windows-button-and-a-dock-for-launching-apps.png) 

Close 

 Also, a desktop environment will come with a set of integrated apps and utilities so that the apps and overall system follow the same design philosophy and look visually consistent. For example, the GNOME desktop environment ships with GTK apps, while KDE Plasma has Qt apps. As such, if you run GTK (or GNOME) apps on a KDE system, it may feel out of place with the rest of the desktop.

![Running GTK calculator app on a Qt system - Garuda Linux running KDE Plasma](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/running-gtk-calculator-app-on-a-qt-system-garuda-linux-running-kde-plasma.png) 

##  4\. Terminal and Console

 In modern Linux computing, a **terminal** or “terminal emulator” refers to the GUI window that creates a [command-line interface (CLI)](https://en.wikipedia.org/wiki/Command-line%5Finterface)for you to enter commands and view the system-generated outputs. For instance, here’s the GNOME terminal that’s accessible on distros running on GNOME:

![Image of Gnome Terminal running on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/image-of-gnome-terminal-running-on-ubuntu.png) 

 In contrast, a **console** or “virtual console” is a special type of terminal you get in minimal GUI-less Linux installations or server environments. This gives you direct access to the shell (a command-line interpreter), offering a straightforward, full-screen CLI experience. Many Linux distros allow you to access the “console” view through dedicated key combinations–either Alt+F1…F5 or Ctrl+Alt+F1…F5.

![Ubuntu 23.10 Teletypewriter view](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/ubuntu-23-10-teletypewriter-view.png) 

##  5\. Binaries, Packages, Dependencies, and Repositories (Repos)

**Binaries** are computer-readable code for a program (or part of a program) that the computer can run and process. **Packages** are binaries bundled with additional information such as configuration files, version numbers, software descriptions, installation instructions, dependencies, and more. Now, **dependencies** for a package are additional packages, binaries, or system components, necessary for that package to run.

 Different distros have their own packaging formats for creating distro specific software packages, like Steam, LibreOffice, or Firefox. They upload these packages to a large library called a repository so you can easily download and install them. For example, Debian and Debian-based distros support [DEB packages](https://facebook-video-share.techidaily.com/new-2024-approved-capturing-contentment-a-practical-guide-to-daily-vlogging/) which are maintained in the [Debian repository](https://wiki.debian.org/DebianRepository).

 Now, sometimes, the software you want won’t be in the official repository, at which point you can reference an unofficial collection called a third-party repository. For reference, [Personal Package Archives (PPAs)](https://buynow-help.techidaily.com/the-future-of-home-safety-evaluating-the-battery-version-of-googles-wireless-nest-doorbell/) is a third-party repo for DEB packages maintained by program developers or enthusiasts.

 Take this example: I’m trying to [install LibreOffice](https://screen-capture.techidaily.com/in-2024-the-filmmakers-guide-to-capturing-exceptional-vo-recordings/), but it isn't available in the Ubuntu 22.04 repository. So I had to add the PPA:libreoffice, where it’s available to install.

![Linux terminal displaying the addition of LibreOffice PPA to Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-11.png) 

 Only use PPAs from trusted sources (check reviews and ratings) to avoid installing malware on your system.

##  6\. Package Managers

**Package managers** are tools that connect you to a software repository so you can easily download, install, update, remove, and manage packages along with their dependencies. Just like packaging formats, there are distro-specific package managers. For example, there’s APT for managing DEB packages on Debian-based systems and DNF for managing RPM packages for Red Hat-based systems.

 This mode of distributing packages can be challenging for developers as they have to package their apps into multiple formats and keep them updated on multiple repositories to ensure availability across distros. To try solving this problem we have universal package managers like Snap and Flatpak.

![Installing Discord from Flathub the flatpak store](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/installing-discord-from-flathub-the-flatpak-store.png) 

![Installing Discord from the Snap Store](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/installing-discord-from-the-snap-store.png) 

Close 

**Universal package managers** distribute software that includes everything necessary to run it, making it easier to install and compatible with different distros. Moreover, they require minimal interaction with your system files, making them theoretically more secure. However, by bundling “all” necessary files, universal packages are more extensive and take up more space.

 Prioritize installing apps in the official repo because they are optimized for your system and take up less space. Use Snaps and Flatpaks when official repo packages are not available.

##  7\. Rolling Release and Point Release Model

 When looking into different Linux distros, you must have come across the terms “rolling release” and “point release”. This basically refers to how updates are delivered to a distro.

 In a **rolling release model**, your Linux distro gets continuous updates to the latest software. This means you'll always have access to the newest features and fixes. However, updating your system regularly (at least every two weeks) is essential to avoid compatibility issues with future updates. If you don't, your system might become outdated. Examples include Manjaro and Garuda Linux.

![Manjaro Linux Desktop.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/manjaro-linux-desktop.png) 

![The Garuda Linux Desktop.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/garuda-linux-desktop.png) 

Close 

**Point release distros** release new versions at specific intervals. You don't need to update your system as frequently, which can be convenient for professionals or servers that require stability. These releases, called "upgrades," update many core system files or replace them with newer packages. Examples include Ubuntu, Pop!\_OS, and Linux Mint.

![Ubuntu 23.10 Default desktop](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/ubuntu-23-10-default-desktop.png) 

![Pop!_OS Linux Desktop view.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/pop-_os-linux-desktop-view.png) 

![Linux Mint Desktop Overview.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/linux-mint-desktop-overview.png) 

Close 

 Point release distros have an "End of Life" date. After this date, they no longer receive updates, which can lead to security risks and compatibility issues if you keep using them. For example, Ubuntu 23.10 is supported for 9 months after its release, while Ubuntu 22.04 LTS (Long Term Support) gets 5 years of support.

---

 Understanding these essential Linux terms is the first step towards becoming a Linux power user. With this knowledge, you're now better equipped to navigate the Linux landscape, engage in discussions, and confidently continue your learning journey.

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
