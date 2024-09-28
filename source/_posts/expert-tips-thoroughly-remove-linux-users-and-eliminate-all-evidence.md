---
title: "Expert Tips: Thoroughly Remove Linux Users and Eliminate All Evidence"
date: 2024-08-31T08:54:27.998Z
updated: 2024-09-01T08:54:27.998Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/de7c313fd07e2524cf8d55d82a6066b369ed71aad2bc2f894ad55f60508b5e77.jpg
---

## Expert Tips: Thoroughly Remove Linux Users and Eliminate All Evidence

### Quick Links

* [User Accounts on Linux](https://tech-haven.techidaily.com/understanding-ai-prompt-injection-an-overview-of-the-technique-and-its-mechanisms/)
* [Why Delete an Account?](https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-realme-12plus-5g-tips-tricks-and-helpful-advice-by-drfone-android/)
* [Check the Login](https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-14-pro-by-drfone-ios/)
* [Reviewing The User's Processes](https://youtube-data.techidaily.com/ed-unlocking-collective-watch-strategies-for-multiple-channels-for-2024/)
* [Locking the Account](https://on-screen-recording.techidaily.com/2024-approved-joining-the-dots-obs-and-zoom-pairing-explained/)
* [Killing the Processes](https://unlock-android.techidaily.com/in-2024-how-to-reset-a-xiaomi-redmi-13c-phone-that-is-locked-by-drfone-android/)
* [Archiving the User's home Directory](https://unlock-android.techidaily.com/how-to-reset-a-locked-vivo-y100t-phone-by-drfone-android/)
* [Removing cron Jobs](https://screen-recording.techidaily.com/updated-in-2024-playcapture-pro-your-own-screen-recorder-free/)
* [Removing Print Jobs](https://some-skills.techidaily.com/2024-approved-the-complete-guide-to-shooting-with-a-green-screen/)
* [Deleting the User Account](https://extra-lessons.techidaily.com/volume-control-soft-fades-within-logic-pro-environment/)
* [It's a Wrap](https://techtrends.techidaily.com/master-the-internet-a-users-guide-on-enabling-browser-cookies/)

 Deleting a user on Linux involves more than you think. If you're a system administrator, you'll want to purge all traces of the account and its access from your systems. We'll show you the steps to take.

 If you just want to delete a user account from your system and aren't concerned about ending any running processes and other cleanup tasks, follow the steps in the "Deleting the User Account" section below. You'll need the `deluser` command on Debian-based distributions and the `userdel` command on other Linux distributions.

##  User Accounts on Linux

 Ever since the [first time-sharing systems appeared in the early 1960s](https://en.wikipedia.org/wiki/Compatible%5FTime-Sharing%5FSystem) and brought with them the capability for multiple users to work on a single computer, there's been a need to isolate and compartmentalize the files and data of each user from all the other users. And so user accounts—[and passwords—](https://en.wikipedia.org/wiki/Fernando%5FJ.%5FCorbat%C3%B3)were born.

 User accounts have an administrative overhead. They need to [be created](https://bypass-frp.techidaily.com/full-guide-to-bypass-itel-p55plus-frp-by-drfone-android/) when the user first needs access to the computer. They need to be removed when that access is no longer required. On Linux, there's a sequence of steps that should be followed in order to correctly and methodically remove the user, their files, and their account from the computer.

 If you're the system administrator that responsibility falls to you. Here's how to go about it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
##  Why Delete an Account?

 There's any number of reasons an account might need to be deleted. A staff member might be moving to a different team or leaving the company altogether. The account might have been set up for a short term collaboration with a visitor from another company. Team-ups are common in academia, where research projects can span departments, different universities, and even commercial entities. At the conclusion of the project, the system administrator has to perform the housekeeping and remove unnecessary accounts.

 The worst-case scenario is when someone leaves under a cloud because of a misdemeanor. Such events usually happen suddenly, with little fore-warning. That gives the system administrator very little time to plan, and an urgency to get the account locked, closed and deleted—with a copy of the user's files backed up in case they are needed for any post-closure forensics.

 In our scenario, we'll pretend that a user, Eric, has done something that warrants his immediate removal from the premises. At this moment he is unaware of this, he's still working, and logged in. As soon as you give the nod to security he's going to be escorted from the building.

 Everything's set. All eyes are on you.

##  Check the Login

 Let's see if he really is logged in and, if he is, how many sessions he's working with. The `who` command [will list active sessions](http://man7.org/linux/man-pages/man1/who.1.html).

who

![who in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/1-2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 Eric is logged in once. Let's see what processes he's running.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
##  Reviewing The User's Processes

 We can use the `ps` command to [list the processes this user is running](http://man7.org/linux/man-pages/man1/ps.1.html). The `-u` (user) option lets us tell `ps` to restrict its output to the processes running under the ownership of that user account.

ps -u eric

![ps -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/2-2.png) 

 We can see the same processes with more information using the `top` command. `top` also has an `-U` (user) option to restrict the output to the processes owned by a single user. Note that this time it is an uppercase "U."

top -U eric

![top -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/3-3.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 We can see the memory and CPU usage of each task, and can quickly look for anything with suspicious activity. We're about to forcibly kill all of his processes, so it is safest to take a moment to quickly review the processes, and check and make sure that other users are not going to be inconvenienced when you terminate user account `eric`'s processes.

![Output from top -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/4-2.png) 

 It doesn't look like he's doing much, just using `less` to view a file. We're safe to proceed. But before we kill his processes, we'll freeze the account by locking the password.

##  Locking the Account

 We'll lock the account before we kill the processes because when we kill the processes it will log out the user. If we've already changed his password, he won't be able to log back in.

 The encrypted user passwords are stored in the `/etc/shadow` file. You wouldn't normally bother with these next steps, but so that you can see what happens in the `/etc/shadow ` file when you lock the account we'll take a slight detour. We can use the following command to look at the first two fields of the entry for the `eric` user account.

sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow

![sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/20-1.png) 

 The awk command [parses fields from text files](http://man7.org/linux/man-pages/man1/awk.1p.html) and optionally manipulates them. We're using the `-F` (field separator) option to tell `awk` that the file uses a colon " `:` " to separate the fields. We're going to search for a line with the pattern "eric" in it. For matching lines, we'll print the first and second fields. These are the account name and the encrypted password.

 The entry for user account eric is printed for us.

 To lock the account we use the `passwd` command. We'll use the `-l` (lock) option and [pass in the name of the user account to lock](http://man7.org/linux/man-pages/man1/passwd.1.html).

sudo passwd -l eric

![sudo passwd -l eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/18.png) 

 If we check the `/etc/passwd` file again, we'll see what's happened.

sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow

![sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/21-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
 An exclamation mark has been added to the start of the encrypted password. It doesn't overwrite the first character, it's just added to the start of the password. That's all that's required to prevent a user from being able to log in to that account.

 Now that we've prevented the user from logging back in, we can kill his processes and log him out.

##  Killing the Processes

 There are different ways to [kill a user's processes](https://pokemon-go-android.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-honor-magic-v2-drfone-by-drfone-virtual-android/), but the command shown here is widely available and is a more modern implementation than some of the alternatives. The `pkill` command will find and kill processes. We're passing in the KILL signal, and using the `-u` (user) option.

sudo pkill -KILL -u eric

![sudo pkill -KILL -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/6-2.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You're returned to the command prompt in a decidedly anti-climactic fashion. To make sure something happened let's check `who` again:

who

![who in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/7-2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
 His session is gone. He's been logged off and his processes have been stopped. That's taken some of the urgency out of the situation. Now we can relax a bit and carry on with the rest of the mopping up as security takes a walk over to Eric's desk.

Related: [How to Add and Remove Users on Ubuntu](https://fox-links.techidaily.com/updated-gif-magic-transformations-without-extra-files-downloaded-for-2024/) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
##  Archiving the User's home Directory

 It's not out of the question that in a scenario such as this, access to the user's files will be required in the future. Either as part of an investigation or simply because their replacement may need to refer back to their predecessor's work. We'll use the `tar` command [to archive their entire home directory](http://man7.org/linux/man-pages/man1/tar.1.html).

 The options we're using are:

* **c**: Create an archive file.
* **f**: Use the specified filename for the name of the archive.
* **j**: Use bzip2 compression.
* **v**: Provide verbose output as the archive is created.

sudo tar cfjv eric-20200820.tar.bz /home/eric

![sudo tar cfjv eric-20200820.tar.bz /home/eric  in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/8-2.png) 

 A lot of screen output will scroll in the terminal window. To check the archive has been created, use the `ls` command. We're using the `-l` (long format) and `-h` (human-readable) options.

ls -lh eric-20200802.tar.bz

![sudo tar cfjv eric-20200820.tar.bz /home/eric  in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/9-1.png) 

 A file of 722 MB has been created. This can be copied somewhere safe for later review.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Removing cron Jobs

 We'd better check in case there are any `cron` jobs scheduled for user account `eric`. A `cron` job is a command that is triggered at specified times or intervals. We can check if there are any `cron` jobs scheduled for this user account by using `ls`:

sudo ls -lh /var/spool/cron/crontabs/eric

![sudo ls -lh /var/spool/cron/crontabs/eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/10-1.png) 

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If anything exists in this location it means there are `cron` jobs queued for that user account. We can delete them with this `crontab` command. The `-r` (remove) option will remove the jobs, and the `-u` (user) option tells `crontab` [whose jobs to remove](http://man7.org/linux/man-pages/man1/crontab.1.html).

sudo crontab -r -u eric

![sudo crontab -r -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/11-2.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
 The jobs are silently deleted. For all we know, if Eric had suspected he was about to be evicted he might have scheduled a malicious job. This step is best practice.

##  Removing Print Jobs

 Perhaps the user had pending print jobs? Just to be sure, we can purge the print queue of any jobs belonging to user account `eric`. The `lprm` command [removes jobs from the print queue](http://man7.org/linux/man-pages/man1/lprm.1.html). The `-U` (username) option lets you remove jobs owned by the named user account:

lprm -U eric

![lprm -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/12-2.png) 

 The jobs are removed and you are returned to the command line.

##  Deleting the User Account

 We've already backed up the files from the `/home/eric/` directory, so we can go ahead and delete the user account and delete the `/home/eric/` directory at the same time.

 The command to use depends on which distribution of Linux you're using. For [Debian based Linux distributions](https://manpages.ubuntu.com/manpages/noble/en/man8/deluser.8.html), the command is `deluser`, and [for the rest of the Linux world](http://man7.org/linux/man-pages/man8/userdel.8.html), it is `userdel`.

 Actually, on Ubuntu both commands are available. I half-expected one to be an alias of the other, but they are distinct binaries.

type deluser

type userdel

![type deluser in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/22-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 Although they're both available, the recommendation is to use `deluser` [on Debian-derived distributions](http://manpages.ubuntu.com/manpages/eoan/man8/userdel.8.html):

 "`userdel` is a low level utility for removing users. On Debian, administrators should usually use `deluser`(8) instead."

 That's clear enough, so the command to use on this Ubuntu computer is `deluser`. Because we also want their home directory to be removed we're using the `--remove-home` flag:

sudo deluser --remove-home eric

![sudo deluser --remove-home eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/14-2.png) 

 The command to use for non-Debian distributions is `userdel`, with the `--remove` flag:

sudo userdel --remove eric

 All traces of user account `eric` have been erased. We can check that the ` /home/eric/`directory has been removed:

ls /home

![ls /home in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/15-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 The `eric` group has also been removed because the user account `eric` was the only entry in it. We can check this quite easily by piping the contents of `/etc/group` through `grep`:

sudo less /etc/group | grep eric

![sudo less /etc/group | grep eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/16-1.png) 

##  It's a Wrap

 Eric, for his sins, is gone. Security is still walking him out of the building and you've already secured and archived his files, deleted his account, and purged the system of any remnants.

 Accuracy always trumps speed. Make sure you consider each step before you take it. You don't want someone walking up to your desk and saying "No, the other Eric."

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


