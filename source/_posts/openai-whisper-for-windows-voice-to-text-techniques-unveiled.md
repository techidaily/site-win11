---
title: "OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled"
date: 2024-08-15T23:36:26.601Z
updated: 2024-08-16T23:36:26.601Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled"
excerpt: "This Article Describes OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled"
keywords: OpenAI Whisper,Windows Voice-To-Text,Whisper AI Speech,Texting Windows Audio,Whisper Techniques,OpenAI Windows Transcription,AI Voice Conversion
thumbnail: https://thmb.techidaily.com/3e9db891de75640d42280dabbfbbc511c64f55b10c2c6cccea4046ea3f8adbe3.jpg
---

## OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled

 OpenAI's Whisper is a new AI-powered solution that can turn your voice into text. Best of all, it comes at zero cost.

 However, there's a catch: it's more challenging to install and use than your average Windows utility. Especially if you want to use your Nvidia GPU's Tensor Cores to give it a nice boost.

 Don't fret, though. That's why we're here! Read on to find out how to install and use it, but also, if you own one, to have Whisper take advantage of your Nvidia GPU.

## What Is OpenAI's Whisper?

 ChatGPT is all the rage nowadays, and we already saw [how you can use ChatGPT by OpenAI](https://www.makeuseof.com/how-to-use-chatgpt-by-openai/) . And yet, it's not the only interesting project by OpenAI.

 Powered by deep learning and neural networks, Whisper is a natural language processing system that can "understand" speech and transcribe it into text. But it's also its own thing, sitting at a spot right among all similar solutions:

* Whisper is an AI solution "trained" on natural language. So, it's better at understanding "normal" human speech than older solutions.
* Whisper doesn't come with an interface, nor can it record audio. It can only take existing audio files and output text files.
* Since it's good at "making sense of language", Whisper also has the superpower of automatic translation in a single step.
* Whisper is not an online service and can work entirely offline.
* If you have a relatively modern Nvidia GPU (GTX970 or newer), Whisper can run in "hardware accelerated mode" to boost its speed.
* There's no requirement to register, purchase a license, or buy a subscription.

## Why Are AMD GPUs Not Supported?

 For GPUs to be useful for more than graphics, they'd have to act as fully programmable processors. That's why Nvidia created CUDA, officially deemed "a parallel computing platform and programming model". To learn more about CUDA and related hardware ("CUDA cores"), read our article on [what are CUDA cores and how they improve PC gaming](https://www.makeuseof.com/tag/what-are-cuda-cores-pc-gaming/) .

 CUDA is proprietary Nvidia technology, only compatible with Nvidia GPUs. The closest alternatives for AMD's hardware are OpenCL and Radeon Compute Platform. To learn more about how each company's solutions compare, check our article on [AMD Compute Units vs. Nvidia CUDA Cores](https://www.makeuseof.com/compute-units-vs-cuda-cores-whats-the-difference/) .

 Compared to the alternatives, CUDA is considered more mature, performant, and easier to use. Thus, most developers only target CUDA, which, in turn, means that their software only takes advantage of the hardware features on Nvidia GPUs. And that includes Whisper.

## How to Download and Install Whisper

 Unfortunately, Whisper is not a standalone app you can download, install, and run. It relies on other software, which must also be installed.

 For Windows, to keep this guide simple, we'll use Chocolatey extensively for installing most of the necessary software parts. Check our guide on [the quickest way to install Windows software](https://www.makeuseof.com/tag/quickest-way-install-windows-software-command-prompt/) for more info on Chocolatey.

 For Linux and Macs, the installation process (excluding the Windows path variable, and easy-to-use batch files we'll create) should be similar.

1. To install and use Whisper, you must have**Python** and its**PIP** tool installed and added to the Windows "Path" variable. For info on that, check our article on [how to install Python PIP on Windows, Mac, and Linux](https://www.makeuseof.com/tag/install-pip-for-python/) .
2. Install**FFMPEG** through Chocolatey with this command:  
`choco install ffmpeg`  
 Also, install its Python version with:  
`pip3 install python-ffmpeg`  
![pip install python ffmpeg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip-install-python-ffmpeg.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Finally, install Whisper from its Github page with:  
`pip3 install git+https://github.com/openai/whisper.git`

## Getting Whisper's CUDA-Enabled Version

 Although Whisper doesn't use Nvidia GPUs, the**torch** package it relies on offers a CUDA-accelerated version. Using this instead of the "plain" version can help Whisper complete its transcriptions much faster with the help of your Nvidia GPU.

To have Whisper use the CUDA cores of your Nvidia GPU:

1. If you already have the "vanilla" version of torch installed, uninstall and purge remnants of it with:  
`pip3 uninstall torch`  
 Once it's done, follow it up with:  
`pip cache purge`
2. Install torch's CUDA-enabled version with:  
`pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117`  
![pip3 install torch torchvision torchaudio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip3-install-torch-torchvision-torchaudio.jpg)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. To check if Whisper can use your Nvidia GPU, use:  
`whisper --help | findstr -i pytorch`  
 You should see**(default: cuda)** instead of**(default: cpu)** .

## What to Do if Torch Fails to Install

 If you encounter the "no version found" errorwhile installing torch, you may need to install an older version of Python parallel to your current one.

Use this command to do that:

`choco install python --version OLDER_VERSION --side-by-side`

Replace "OLDER\_VERSION" with a version, like 3.10.

![choco install python alternate version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choco-install-python-alternate-version.jpg)

 Then, use the path of the secondary version for all "generic" Whisper commands (e.g., "c:\\Python310\\Scripts\\pip.exe" rather than just "pip").

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Record Your Voice

 You can use any sound-recording app to turn your voice into a WAV or MP3 file. Windows includes such an app—for more info on that, see [how to use the Windows 10 Voice Recorder app](https://www.makeuseof.com/how-to-use-the-windows-10-voice-recorder-app/) .

 For a more full-featured option, try**Audacity** . Learn how to do it with our guide on [how to use Audacity to record audio on Windows and Mac](https://www.makeuseof.com/how-to-use-audacity-to-record-audio/) .

![Recording voice with Audacity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/recording-voice-with-audacity.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## How to Start Transcribing With Whisper

 Although Whisper doesn't come with a user-friendly GUI, its use is ultra-simple.

 Let's say we have the file**LatestNote.mp3** which contains speech in Greek, in folder**c:\\MyAudioFiles** , and want to translate it to English and transcribe it into a text file.

1. We begin by running**Command Prompt** or**PowerShell** .
2. We "change directory" where the audio file is stored with this command:  
`cd C:\MyAudioFiles`
3. We unleash Whisper on the file with:  
`whisper --model base --language gr --task translate LatestNote.mp3`  
![Whisper translate gr](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-translate-gr.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once processed, the text file (named "LatestNote.mp3.txt") will appear in the same folder. Open it in a text editor like**Notepad** to view the translated text.

 We used a translation example because English transcription is even more straightforward: you only have to "lose" the "--language" and "-task" flags. Thus, for plain transcription, the above command would be:

`whisper --model base LatestNote.mp3`

 The "model" flag is required because Whisper uses one out of various options. Let's expand on them to help you choose the best for your needs.

### Which Model to Choose?

 Whisper offers various language models. The larger the model, the more improved its accuracy, but also the higher its hardware requirements. They are:

1. Tiny.
2. Base.
3. Small.
4. Medium.
5. Large.

 Most native English speakers should be fine with the**tiny** or**base** models. Non-native English speakers may see better results with larger models, like**small** and**medium** .

 Note, though, that the medium and large models require over 8GBs of VRAM (that is, "your GPU's memory").

![whisper model small](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-model-small.jpg)

 To select one of them, specify the model after the "--model" switch in the command:

`whisper --model tiny/small/medium/large [file]`

For example:

`whisper --model small My_Voice_Note.mp3`

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Streamline Your Transcription

 Having to type the whole Whisper command every time you want to transcribe some audio can quickly get boring. Let's make a globally accessible batch file to streamline the process.

1. Run**Windows Explorer** and visit your C: drive.
2. Create a folder for your scripts, and copy its path to the Clipboard.
3. In the Windows Start menu, search for "path" and select**Edit the system environment variables** .  
![Windows Start Edit The System Environment Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-start-edit-the-system-environment-variables.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
4. Find the**Path** variable under**User variables for YOUR\_USERNAME** . Double-click on it to edit it. Click on**New** , and paste the path to your scripts folder. Click on**OK** to accept the changes.  
![Environment Variables User Account Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/environment-variables-user-account-path.jpg)
5. Return to your scripts folder in Windows Explorer. Create a new batch file there named "wht.bat". "Inside" it, place this command:  
`whisper --model tiny --language en %1`  
![Creating WHT Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-wht-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
6. Create two more batch files, "whs" and "whm".
7. Place this inside the first script:  
`whisper --model small --language en %1`
8. Place this inside the second:  
`whisper --model medium --language en %1`

 Congratulations, you now have three scripts for easily using Whisper's tiny, small, and medium models with your audio files! To transcribe any audio file to text:

1. Locate the file with**Windows File Explorer** .
2. **Right-click** on an empty spot and choose**Open in Terminal** .
3. Type this command, replacing "wht" with "whs" or "whm" to use the small or medium language models:  
`wht YOUR_AUDIO_FILE.mp3`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## Typing at the Speed of Sound With Whisper

 Even the quickest touch-typists can't match the speed at which we speak. However, until recently, talking instead of typing wasn't optimal for creating documents.

 Most voice-to-text solutions produced mediocre results. You could find a few solutions worth trying, but they were complicated to use, or costly. Thankfully, Whisper changed all that.

 After the steps above, you should be ready to transcribe or translate your voice with high accuracy, using only a single command.


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






