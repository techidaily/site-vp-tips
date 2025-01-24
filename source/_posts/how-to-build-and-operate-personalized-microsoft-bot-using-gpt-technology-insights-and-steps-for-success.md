---
title: "How to Build & Operate Personalized Microsoft Bot Using GPT Technology: Insights & Steps for Success"
date: 2025-01-20T20:47:45.392Z
updated: 2025-01-23T19:52:52.298Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5c8db21fb7e97eed2eddd025f3f66d3a9e58c7bc74fde8e765814f3eec97fd83.jpg
---

## How to Build & Operate Personalized Microsoft Bot Using GPT Technology: Insights & Steps for Success

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Why Would You Want Your Own Local AI Chatbot?](https://extra-information.techidaily.com/updated-10-best-live-streaming-platforms-you-should-know/)
* [How to Host Your Own Local GPT Chatbot on Windows](https://extra-guidance.techidaily.com/2024-approved-smart-shopping-tips-economical-gopro-cameras/)
* [Step 1: Install Docker and the Windows Terminal App](https://fox-glue.techidaily.com/updated-customizing-your-windows-photos-app-filters-and-music-sync-feature-for-2024/)
* [Step 2: Download the Text Generation Web UI GitHub Repository](https://win-solutions.techidaily.com/solving-the-outdated-driver-alert-in-minecraft-a-comprehensive-guide/)
* [Step 3: Launch the Text Generation Web UI](https://visual-screen-recording.techidaily.com/easy-peasy-guide-to-capturing-online-events-for-mac-and-windows-users/)
* [Step 4: Install the GPT-2 Model From OpenAI](https://extra-support.techidaily.com/lolkit-design-memes-and-graphics-with-a-click-for-2024/)
* [Step 5: Start Using Your Custom GPT AI Chatbot](https://some-approaches.techidaily.com/2024-approved-the-ultimate-key-to-exploring-without-boundaries-through-vr/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Running your own local GPT chatbot on Windows is free from online restrictions and censorship.
* Install text-generation-web-ui using Docker on a Windows PC with WSL support and a compatible GPU.
* Customize and train your GPT chatbot for your own specific use cases, like querying and summarizing your own documents, helping you write programs, or imitating your own characters.

 There are a number of advantages to running a GPT/AI chatbot on your own computer rather than accessing one on the Internet. We'll show why you might want to, and the easiest way to get it set up on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Why Would You Want Your Own Local AI Chatbot?

 While online AI chatbots like ChatGPT are dominant, with access to huge amounts of training data and up-to-date information, there are a few reasons you might want to run your own local chatbot on your Windows computer.

 Running your own AI tools locally is free, and comes without the restrictions of online tools: There's no censorship, and you can load whatever machine-learning models, tailor their responses and behavior, and provide any prompt, all without restriction (and in total privacy). It's also a good way to get an understanding of how modern large language model (LLM) AI tools work under the hood, especially if you are looking to get into the AI or tech industry.

 You can find models for just about anything, from fictional character interactions, to programming, to general knowledge, and many other use cases that more general online models may not cover.

##  How to Host Your Own Local GPT Chatbot on Windows

 This tutorial will use [text-generation-web-ui-docker](https://github.com/Atinoda/text-generation-webui-docker "https://github.com/oobabooga/text-generation-webui"), an open-source interface for large language models, that simplifies installing and using LLMs.

 text-generation-web-ui-docker bundles the text-generation-web-ui project using [Docker](https://vp-tips.techidaily.com/new-ultimate-auditory-interface-win-for-2024/), which removes the need for installing and managing all the complex dependencies that local AI tools usually require by storing everything in a container separate to your system. The only thing you need to run your local chatbot is a Windows PC that [supports Docker running using the Windows Subsystem for Linux (WSL)](https://docs.docker.com/desktop/install/windows-install/ "https://docs.docker.com/desktop/install/windows-install/"). You'll also need a fairly recent GPU, ideally one from NVIDIA, for maximum compatibility.

##  Step 1: Install Docker and the Windows Terminal App

 Docker containers are similar to [virtual machines](https://remote-screen-capture.techidaily.com/2024-approved-essential-guide-video-recording-with-vlc/) in that they contain a whole running system, but they are much more lightweight, and perfect for distributing applications and all of their requirements in a single, easy-to-install bundle. To run text-generation-web-ui-docker in Docker, [download and install Docker on your Windows system](https://www.docker.com/products/docker-desktop/ "https://www.docker.com/products/docker-desktop/").

 Docker can run on Windows in one of two ways: WSL or Hyper-V mode. WSL is recommended for most users, so you may need to [enable it](https://some-skills.techidaily.com/new-unveiling-paid-content-in-product-analysis/) before installing Docker.

 It's also recommended to [install the Windows Terminal app](https://youtube-tips.techidaily.com/ed-mastering-youtube-streaming-a-guide-for-gamers-for-2024/), as it provides a convenient interface for WSL, PowerShell, and the Windows command line.

##  Step 2: Download the Text Generation Web UI GitHub Repository

 To download text-generation-web-ui-docker, [visit its GitHub page](https://github.com/Atinoda/text-generation-webui-docker "https://github.com/oobabooga/text-generation-webui"). You can download a ".zip" file containing all the files you need by clicking on the green "Code" button and then clicking on "Download Zip" from the drop-down menu.

 The screenshot below shows you where to find this on the GitHub page.

![Where to download the .zip file for a GitHub repository.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/download-zip-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

[Extract the downloaded ZIP file](https://video-screen-grab.techidaily.com/updated-in-2024-essential-screen-capture-software-top-picks-ranked/) into its own folder, and then open the folder containing the unzipped files. Don't worry too much about the contents of this folder: it's all the moving parts for your AI chatbot, but Docker will take care of setting everything up for you.

##  Step 3: Launch the Text Generation Web UI

 Before you launch text-generation-web-ui-docker, you need to make sure it's configured for your PC hardware. Edit the file **docker-compose.yml** to specify the variant that matches your hardware: **default-nvidia** or **default-cpu** (if you don't have a compatible GPU).

![Configuring the docker image variant in docker-compose.yml.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/variant.png) 

Brad Morton / How-To Geek

 Then, still in the folder containing the downloaded and extracted files, right-click on an empty space and click "Open in Terminal" to open the directory in a new [PowerShell](https://some-guidance.techidaily.com/updated-unleash-creativity-fast-windows-10-photo-edits-made-simple/) window.

![The location of the 'Open in Terminal' in the context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/open-in-terminal.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

 Make sure Docker Desktop is running before typing in the following Docker command into the Terminal window:

docker compose up -d

 This command will do the following:

* Executes **docker compose**, the program that manages Docker applications
* Start the container using the **up** command
* Runs the container in the background (called detached mode, which is specified by the **\-d**)

![The command for bringing up a Docker container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/up.png) 

Brad Morton / How-To Geek

 If you haven't run this command before and the application needs to be downloaded (pulled), you might need to go and make a cup of tea, as it could take a while. Once the command has completed running successfully, you'll see that the text-generation-web-ui-docker Docker container has been created and started.

![Windows terminal showing the status of a newly created container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/created.png) 

Brad Morton / How-To Geek

 The running container will also appear in Docker Desktop, where you can stop, start, and manage it.

![Docker Desktop showing a running container.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/docker.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Brad Morton / How-To Geek

##  Step 4: Install the GPT-2 Model From OpenAI

 Once text-generation-web-ui-docker is up and running in Docker, you can access it by typing the address **http://localhost:7860** into your browser's address bar. [Localhost](https://youtube-docs.techidaily.com/cing-creativity-and-monetization-in-youtube-shorts-for-2024/) is the address your computer uses to access services it is running itself, each of which is assigned a unique port number (in this case 7860). You can see what ports a running Docker container has made available on localhost by opening it in Docker desktop.

 This is an older version of GPT than you get when you use ChatGPT on the internet. Consequently, it won't be as smart or as intuitive as what you might expect, but it is customizable and private.

 Navigate to the Model tab in the web interface and enter **openai-community/gpt2** into the "Download model or LoRA" box, and then click the Download button. This might take a few minutes.

![Downloading a model for use in text-generation-web-ui.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-6.png) 

Brad Morton / How-To Geek

 Click the Refresh icon in the top-left, then select the newly downloaded openai-community/gpt2 from the adjacent Model drop-down menu. Finally, click the "Load" button, and wait a few minutes until you see a success message.

![Loading a model in text-generation-web-ui.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-7.png) 

Brad Morton / How-To Geek

 This model works out of the box, and doesn't require any signup. As you get into AI and want to experiment with different models and AI tools, you can find more on [HuggingFace](https://huggingface.co/ "https://huggingface.co/").

##  Step 5: Start Using Your Custom GPT AI Chatbot

 This isn't quite like the AI chatbots you're used to using online, which are already set up for general use that cover a lot of situations. You'll need to tell the model how to behave before interacting with it, otherwise its output will be a bit... unhinged.

![A slightly unhinged response from an AI model that needs configuration.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/win-gpt-8.png) 

Brad Morton / How-To Geek

_Hoo boy, while it got the right answer, this AI chatbot needs a bit of fine-tuning._ 

 There's a lot you can tweak, and it can be a bit clunky at first, but with practice and experience, you can build a chatbot that is specific to your own usage, and that keeps your data 100% on your own computer, which is great for business and other confidential use-cases. To learn how to configure and train your local GPT chatbot, check out the [text-generation-web-ui documentation](https://github.com/oobabooga/text-generation-webui/wiki "https://github.com/oobabooga/text-generation-webui/wiki") and the [OpenAI GP2 docs on HuggingFace](https://huggingface.co/docs/transformers/en/model%5Fdoc/gpt2#openai-gpt2 "https://huggingface.co/docs/transformers/en/model_doc/gpt2#openai-gpt2").

 If you want to generate images using AI from your Windows PC, [you can use Fooocus to get easier and more immediate results.](https://facebook-video-share.techidaily.com/updated-upgrading-your-videos-appeal-youtube-thumbnail-resizing/)

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-audiovisual-harmony-music-integration-in-social-media/"><u>[New] 2024 Approved Audiovisual Harmony Music Integration in Social Media</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-ensuring-every-snapchatter-friendly-footage-via-mac/"><u>[New] 2024 Approved Ensuring Every Snapchatter-Friendly Footage via Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-iphones-ultimate-video-capture-list/"><u>[New] 2024 Approved IPhone's Ultimate Video Capture List</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-unparalleled-8-webcams-elevate-your-livestream-experience/"><u>[New] In 2024, Unparalleled 8 Webcams Elevate Your Livestream Experience</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-unveiling-novel-window-11-secrets-for-enhanced-usage/"><u>[New] In 2024, Unveiling Novel WINDOW 11 Secrets for Enhanced Usage</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-step-by-step-guide-building-high-quality-windows-11-videos/"><u>[New] Step-by-Step Guide Building High-Quality Windows 11 Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-clear-sky-route-to-free-unmarked-tiktok-videos/"><u>[New] The Clear-Sky Route to Free, Unmarked TikTok Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-apex-elite-comprehensive-4k-touch-desktops-for-2024/"><u>[Updated] Apex Elite Comprehensive 4K Touch Desktops for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-high-definition-streaming-wars-vmix-or-wirecast-for-2024/"><u>[Updated] High Definition Streaming Wars VMix or Wirecast for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-how-to-intensify-your-gaming-view-on-roblox-platforms/"><u>2024 Approved How to Intensify Your Gaming View on Roblox Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-unique.techidaily.com/convert-your-digital-tutors-online-learning-into-high-quality-mp4-videos-for-offline-study/"><u>Convert Your Digital Tutors Online Learning Into High-Quality MP4 Videos for Offline Study</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-realme-gt-5-lock-screen-password-by-drfone-android/"><u>How To Change Realme GT 5 Lock Screen Password?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-twitch-live-reset-guide/"><u>In 2024, Twitch Live Reset Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-motorola-moto-g24-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Motorola Moto G24 FRP Bypass</u></a></li>
<li><a href="https://win-solutions.techidaily.com/painless-remedies-to-address-lag-issues-while-playing-csgo/"><u>Painless Remedies to Address Lag Issues While Playing CS:GO</u></a></li>
<li><a href="https://common-error.techidaily.com/unstuck-from-the-steam-store-error-methods-to-successfully-load-and-access-games/"><u>Unstuck From the Steam Store Error: Methods to Successfully Load and Access Games</u></a></li>
</ul></div>

