---
title: "Mastering Base64 Encoding/Decoding in Linux: A Step-by-Step Guide"
date: 2024-08-31T08:54:35.337Z
updated: 2024-09-01T08:54:35.337Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7111378cc0205319da99cc8db3992a3d311982c554186166a280e12ee8590487.png
---

## Mastering Base64 Encoding/Decoding in Linux: A Step-by-Step Guide

Want to learn how to encode and decode strings using the base64 binary-to-text scheme? This tutorial will show you two methods to encode and decode a string on Linux using the base64 command and the Python programming language.

##  Where Is base64 Used?

 base64 is widely used in different domains. Some of the most common areas include email attachments, web development, networking, and URL encoding.

 Some email systems use base64 to encode binary data such as images and documents into text format so that these can be safely transmitted with the message. Web developers also use base64 to embed images into HTML and CSS to reduce the number of HTTP requests and improve page load speed.

 Another common use of base64 encoding is in authentication tokens. Usernames and passwords are sometimes masked using this encoding scheme and added to HTTP headers or URL parameters. In networking, base64 is used in protocols that use text-based communication, such as HTTP and SMTP, for transmitting data without corruption.

 What you should know is that base64 is only an encoding scheme. The encoded data can be easily decoded to get the original data back. You should never use it if you need to [encrypt data instead](https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-g54-5g-drfone-by-drfone-virtual-android/).

##  Encoding a String Using the base64 Command

 The most basic way to encode a string using base64 is to output it to the terminal using [the echo command](https://facebook.techidaily.com/cut-out-controversy-refresh-your-feed-focus/). The trick is to [pipe the output](https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) of the echo command to base64, like this:

echo 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-9.png) 

 Because of the default behavior of the echo command, there's a trailing newline character at the end of the string. If you'd like to omit that and only use the string, run:

echo -n 'I love Linux' | base64

![The Linux terminal displaying the process of encoding a string using base64 omitting the newline character](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-10.png) 

 As you can notice, the output is different from the previous one. You can also do this using the printf command which doesn't automatically append a newline character to the string. The format is given below:

printf 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string received from the printf command using base64](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-8.png) 

 This output is the same as the previous one because there are no newline characters this time. If you're familiar with [here-strings](https://tldp.org/LDP/abs/html/x17837.html) on Linux, you can also use them to send your string output to the base64 command like this:

base64 <<< 'I love Linux'

![The Linux terminal showcases how to encode a string using the base64 command with the help of here string operator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-9.png) 

 Similar to the echo command, here-strings also add a newline character at the end of the string.

##  Encoding Files Using the base64 Command

 To encode a file using base64, you can pass the file directly as an option to the base64 command.

 To test it out, [create a new file](https://youtube-sure.techidaily.com/ed-2024-approved-effortless-subtitling-and-cc-addition-techniques-for-youtube-users/) and [append some text to it](https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-8-by-drfone-ios/). If you already have a text file, then use that. I've created a file called base.txt. To encode the file's content to base64, run:

base64 base.txt

![The Linux terminal displaying the process of encoding a file to base64 using the base64 command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-7.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 Remember to replace base.txt with your file name. The above command only displays the output in the terminal. It doesn't save the encoded string anywhere. However, you can easily do that by redirecting the output to a new file. I've created another file called output.txt. This time I'll save the output to that empty file. Here's the command for that:

base64 base.txt > output.txt

![The Linux terminal showcasing the process of encoding the content of a file to base64 and saving it to another file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-7.png) 

 As you can see, the terminal didn't display the output. This command saved it to another file instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##  Decoding a base64 String Using the base64 Command

 For decoding a base64 string and turning it into a regular string, you'll need to use the "-d" flag with the base64 command. Let's see a demonstration using the echo command.

echo 'SG93VG9HZWVrCg==' | base64 -d

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of the echo command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-8.png) 

 If you'd like to use here-strings for decoding a base64 string, then use:

base64 -d <<< SG93VG9HZWVrCg==

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of here-strings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-7.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Sometimes, there might be non-alphanumeric characters in a string. You can ignore those while decoding the string by using the "-i" option.

##  Using Python to Encode and Decode a base64 String

 If you're a Python programmer or are more familiar with the [Python programming language](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/) than Bash, then this method will be more suitable for you. Python has a base64 module that you can use for encoding and decoding strings. You can either use the python3 terminal command or write a full program. I'll show you both ways.

 The python3 command has a "-m" or module flag. You can use this flag to invoke the base64 module. Then you can pass your string with the help of the echo command or here-strings. Here's the full command:

echo 'I love Linux' | python3 -m base64 # Using the echo commandpython3 -m base64 <<< 'I love Linux' # Using here-strings

![The Linux terminal displays the process of encoding a string to base64 using Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-4.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
 To decode a base64 string, all you need to do is use the "-d" flag as seen previously with the base64 command. The syntax is below:

echo 'SSBsb3ZlIExpbnV4Cg==' | python3 -m base64 -d # Using the echo command​​​​​​python3 -m base64 -d <<< 'SSBsb3ZlIExpbnV4Cg==' # Using here-strings

![The Linux terminal showing the process of decoding a base64 string using the Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-5.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Of course, the convenient way is to create a Python program that can handle the encoding and decoding by taking user input. First, let's create a program that will encode a string. Here's the encoding code:

        `import base64  
## Get input string from the user  
input_string = input("Enter the string to encode: ")  
## Encode the string using base64  
encoded_string = base64.b64encode(input_string.encode('utf-8'))  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Decode the encoded string to ensure it's correct (optional)  
decoded_string = base64.b64decode(encoded_string).decode('utf-8')  
## Print the encoded and decoded strings  
print("Encoded string:", encoded_string.decode('utf-8'))  
print("Decoded string (verification):", decoded_string)  
`
    
 Save the file with a suitable name and a ".py" extension. I'm saving it by the name base64\_encoder.py. Once done, run the program with:

python3 base64_encoder.py

![The Linux terminal showcasing the process of encoding a string using a Python program](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/11-3.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 You can also create a program to decode a base64 string. Here's a code snippet you can use:

        `import base64  
## Get input base64 string from the user  
encoded_string = input("Enter the Base64 string to decode: ")  
try:  
   # Decode the string using base64.b64decode()  
   decoded_string = base64.b64decode(encoded_string).decode('utf-8')  
   print("Decoded string:", decoded_string)  
except Exception as e:  
   print(f"Error decoding string: {e}")  
`
    
 Save the file and run the program in the same way.

python3 base64_decoder.py

![The Linux terminal displaying the process of decoding a base64 string using a Python program](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12-4.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Now you can use these Python programs to encode and decode any strings.

---

 So these are two of the easiest ways to encode and decode strings using base64\. If you'd like to learn more about the base64 command on Linux, it's better to check out [its manual page](https://linux.die.net/man/1/base64).

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
<li><a href="https://fox-helps.techidaily.com/new-dividing-top-4k-captures-best-gimbal-pairings/"><u>[New] Dividing Top 4K Captures  Best Gimbal Pairings</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-inside-track-to-superior-srt-upgrades/"><u>[New] In 2024, Inside Track to Superior SRT Upgrades</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insta-film-conversion-blueprints-to-mp3-formats/"><u>[New] Insta Film Conversion Blueprints to MP3 Formats</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-task-mastery-top-picks-for-efficient-calendar-management-in-fb/"><u>[New] Task Mastery  Top Picks for Efficient Calendar Management in FB</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-mastering-ez-grabber-a-comprehensive-guide/"><u>[Updated] In 2024, Mastering EZ Grabber  A Comprehensive Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-visual-data-harvester/"><u>[Updated] Visual Data Harvester</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2022-guide-exceeding-whatsapps-video-size-restrictions-with-ease-and-securely-sharing-large-files/"><u>2022 Guide: Exceeding WhatsApp's Video Size Restrictions with Ease and Securely Sharing Large Files</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-infusing-humor-into-your-social-media-posts/"><u>2024 Approved  Infusing Humor Into Your Social Media Posts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/accelerate-video-processing-with-hevc-hardware-encoding-the-key-to-lightning-fast-speeds/"><u>Accelerate Video Processing with HEVC Hardware Encoding: The Key to Lightning-Fast Speeds</u></a></li>
<li><a href="https://buynow-info.techidaily.com/appearance/"><u>Appearance</u></a></li>
<li><a href="https://vp-tips.techidaily.com/avoid-redbox-hiccups-essential-tips-for-seamless-dvd-viewing-on-computers/"><u>Avoid RedBox Hiccups: Essential Tips for Seamless DVD Viewing on Computers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/buy-macx-gear-from-our-online-store-the-ultimate-destination-for-all-your-macx-needs/"><u>Buy MacX Gear From Our Online Store – The Ultimate Destination for All Your MacX Needs</u></a></li>
<li><a href="https://techtrends.techidaily.com/comparing-iphones-to-androids-which-device-fits-your-lifestyle/"><u>Comparing iPhones to Androids: Which Device Fits Your Lifestyle?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/compatible-video-and-audio-formats-on-apple-tv-streaming-devices/"><u>Compatible Video & Audio Formats on Apple TV Streaming Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/cross-platform-data-exchange-with-iphone-ipad-mac-and-pc/"><u>Cross-Platform Data Exchange with iPhone, iPad, Mac, and PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/digiarty-technical-assistance-einvernehmliche-losungen-durch-kontinuierliches-kundenfeedback-gewahrleistet/"><u>Digiarty Technical Assistance: Einvernehmliche Lösungen Durch Kontinuierliches Kundenfeedback Gewährleistet</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-free-ultra-hd-8k-video-players-compatible-with-ios-android-and-pc/"><u>Download Free Ultra HD 8K Video Players - Compatible with iOS, Android & PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/download-now-the-speedier-way-to-transfer-dvd-content-to-quicktime-on-your-mac-for-free/"><u>Download Now: The Speedier Way to Transfer DVD Content to QuickTime on Your Mac for Free!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/efficiently-storing-instagram-reels-two-simplified-techniques-for-2024/"><u>Efficiently Storing Instagram Reels  Two Simplified Techniques for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/effortless-mp3-downloader-with-one-click-youtube-converter/"><u>Effortless MP3 Downloader with One-Click YouTube Converter</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fastest-free-video-converter-top-ranking-tools-for-quick-avi-file-transformation/"><u>Fastest Free Video Converter: Top Ranking Tools for Quick AVI File Transformation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-mac-app-for-securely-converting-dvds-to-ipod-friendly-formats-with-macx/"><u>Free Mac App for Securely Converting DVDs to iPod-Friendly Formats with MacX</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guide-effortless-steps-to-stream-or-rip-your-dvds-on-chromecast-via-pc/"><u>Guide: Effortless Steps to Stream or Rip Your DVDs on Chromecast via PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-honor-magic-6-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/handy-brake/"><u>HANDY Brake 最新リリース: 迅速かつ安全なダウンロードと設定手順をご案内!</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-iphone-7-plus-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On iPhone 7 Plus Online</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-x8b-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor X8b Phones with/without a PC</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-transform-your-fb-videos-into-1080p720p-mp4-seamlessly-for-free/"><u>In 2024, Transform Your FB Videos Into 1080P/720p MP4 Seamlessly, For Free</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mactop5/"><u>Macで音楽ダウンロードする簡単なTOP5手順 - 評判の良さとゼロコスト</u></a></li>
<li><a href="https://youtube-help.techidaily.com/maximizing-your-creations-uploading-imovie-videos-to-youtube-for-2024/"><u>Maximizing Your Creations  Uploading IMovie Videos to YouTube for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/optimal-sustainable-screen-capture-tools-usage-strategies-for-2024/"><u>Optimal Sustainable Screen Capture Tools  Usage Strategies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/solving-the-mystery-of-error-code-0xe8000065-in-itunes-during-iphone-sync/"><u>Solving the Mystery of Error Code 0xE8000065 in iTunes During iPhone Sync</u></a></li>
<li><a href="https://vp-tips.techidaily.com/struggling-with-whatsapp-status-video-downloads-easy-solutions-inside/"><u>Struggling with WhatsApp Status Video Downloads? Easy Solutions Inside!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-ranked-warner-bros-film-classics-and-exciting-2amo-releases/"><u>Top-Ranked Warner Bros. Film Classics & Exciting 2Amo Releases</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-rated-mac-webm-to-video-format-converters-swiftly-transform-webm-into-mp4-avi-and-mov/"><u>Top-Rated Mac WebM to Video Format Converters: Swiftly Transform WebM Into MP4, AVI & MOV</u></a></li>
<li><a href="https://vp-tips.techidaily.com/troubleshooting-resolving-persistent-reboots-on-your-iphone-post-ios-17-upgrade/"><u>Troubleshooting: Resolving Persistent Reboots on Your iPhone Post-iOS 17 Upgrade</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-realme-narzo-60-pro-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Realme Narzo 60 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-guide-on-creating-picture-rich-dvds-with-idvd/"><u>Ultimate Guide on Creating Picture-Rich DVDs with iDVD</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-guide-14-leading-software-options-for-downloading-music-from-youtube-as-high-quality-mp3s/"><u>Ultimate Guide: 14 Leading Software Options for Downloading Music From YouTube as High-Quality MP3s</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimatives-benutzer-gebrauchsanweisung-fur-macx-dvd-ripper-pro-unter-windows-transkodieren-von-dvds-zu-mp4-avi-and-flv-fur-pc-und-mobile-gerate/"><u>Ultimatives Benutzer-Gebrauchsanweisung Für MacX DVD Ripper Pro Unter Windows – Transkodieren Von DVDs Zu MP4, AVI & FLV Für PC Und Mobile Geräte</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-full-access-2022-serial-numbers-for-macx-hd-video-encoder-professional-edition/"><u>Unlock Full Access: 2022 Serial Numbers for MacX HD Video Encoder Professional Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-hello-isnt-available-on-this-device-on-windows-10-solved/"><u>Windows Hello Isn’t Available on This Device on Windows 10 [Solved]</u></a></li>
</ul></div>
