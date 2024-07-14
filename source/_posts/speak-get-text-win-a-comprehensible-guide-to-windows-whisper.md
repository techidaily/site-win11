---
title: "Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper"
date: 2024-07-13T11:07:09.378Z
updated: 2024-07-14T11:07:09.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper"
excerpt: "This Article Describes Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper"
keywords: Windows Whisper Techniques,Speak-to-Text Windows,Effective Text Entry Windows,Mastering Windows Commands,Winning with Windows Commands,Easy Text Input on PC,Command Prompt Shortcuts Guide
thumbnail: https://thmb.techidaily.com/7bdbd3764d17d309bfae3520695cdadc9f0f0ab5ea703a9227f88bc7f132643b.jpg
---

## Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper

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

## How to Record Your Voice

 You can use any sound-recording app to turn your voice into a WAV or MP3 file. Windows includes such an app—for more info on that, see [how to use the Windows 10 Voice Recorder app](https://www.makeuseof.com/how-to-use-the-windows-10-voice-recorder-app/) .

 For a more full-featured option, try**Audacity** . Learn how to do it with our guide on [how to use Audacity to record audio on Windows and Mac](https://www.makeuseof.com/how-to-use-audacity-to-record-audio/) .

![Recording voice with Audacity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/recording-voice-with-audacity.jpg)

## How to Start Transcribing With Whisper

 Although Whisper doesn't come with a user-friendly GUI, its use is ultra-simple.

 Let's say we have the file**LatestNote.mp3** which contains speech in Greek, in folder**c:\\MyAudioFiles** , and want to translate it to English and transcribe it into a text file.

1. We begin by running**Command Prompt** or**PowerShell** .
2. We "change directory" where the audio file is stored with this command:  
`cd C:\MyAudioFiles`
3. We unleash Whisper on the file with:  
`whisper --model base --language gr --task translate LatestNote.mp3`  
![Whisper translate gr](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-translate-gr.jpg)

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

## How to Streamline Your Transcription

 Having to type the whole Whisper command every time you want to transcribe some audio can quickly get boring. Let's make a globally accessible batch file to streamline the process.

1. Run**Windows Explorer** and visit your C: drive.
2. Create a folder for your scripts, and copy its path to the Clipboard.
3. In the Windows Start menu, search for "path" and select**Edit the system environment variables** .  
![Windows Start Edit The System Environment Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-start-edit-the-system-environment-variables.jpg)
4. Find the**Path** variable under**User variables for YOUR\_USERNAME** . Double-click on it to edit it. Click on**New** , and paste the path to your scripts folder. Click on**OK** to accept the changes.  
![Environment Variables User Account Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/environment-variables-user-account-path.jpg)
5. Return to your scripts folder in Windows Explorer. Create a new batch file there named "wht.bat". "Inside" it, place this command:  
`whisper --model tiny --language en %1`  
![Creating WHT Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-wht-batch-file.jpg)
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



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/strategies-for-ending-the-gpsvc-hang-up-loop/"><u>Strategies for Ending the GPSVC Hang-Up Loop</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-eternal-banishment-of-youtubes-quick-clips/"><u>[Updated] 2024 Approved  Eternal Banishment of YouTube's Quick Clips</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/how-to-get-more-nfl-viewers-for-your-sports-live-streaming-channel-for-2024/"><u>How To Get More NFL Viewers For Your Sports Live Streaming Channel for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-effective-command-line-steps-for-info-exploration/"><u>10 Effective Command-Line Steps for Info Exploration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-stores-error-x80131500/"><u>Troubleshooting Microsoft Store's Error X80131500</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-utilizing-smartphones-for-effective-home-based-filming/"><u>[New] 2024 Approved  Utilizing Smartphones for Effective Home-Based Filming</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ultimate-terria-customization-collection/"><u>[New] Ultimate Terria Customization Collection</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-downloads-in-microsofts-app-stores/"><u>Mastering Faster Downloads in Microsoft's App Stores</u></a></li>
<li><a href="https://win11.techidaily.com/15-key-improvements-added-to-windows-11s-next-version/"><u>15 Key Improvements Added to Windows 11'S Next Version</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-computer-written-record-with-ms-audits/"><u>Streamlining Your Computer’ Written Record with MS Audits</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-11s-mail-app-converting-html-in-emails-back-to-plain-text/"><u>Solutions for Windows 11'S Mail App: Converting HTML in Emails Back to Plain Text</u></a></li>
<li><a href="https://win11.techidaily.com/managing-intermittent-default-printer-choice/"><u>Managing Intermittent Default Printer Choice</u></a></li>
<li><a href="https://win11.techidaily.com/10-early-symptoms-of-windows-needing-a-fresh-start/"><u>10 Early Symptoms of Windows Needing a Fresh Start</u></a></li>
<li><a href="https://win11.techidaily.com/1719265441814-change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-microsoft-m365-flaw-error-30015-26/"><u>Mitigating Microsoft M365 Flaw: Error 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11-sandbox-initialization/"><u>Navigating Through Windows 11 Sandbox Initialization</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-stock-photographs-meme-lives-and-histories/"><u>[Updated] Iconic Stock Photographs  Meme Lives and Histories</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-mouse-properties-on-windows-11/"><u>10 Ways to Open Mouse Properties on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-control-key-operability-with-ease-on-windows-11/"><u>Restoring Control Key Operability with Ease on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719303345531-dealing-with-dysfunctional-print-via-wwin-command-on-windows/"><u>Dealing with Dysfunctional Print via WWin Command on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-photo-ordering-software-roundup/"><u>Essential Windows Photo Ordering Software Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-microphone-use-a-deep-dive-into-win-11/"><u>Conquering Microphone Use: A Deep Dive Into Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-note-30i-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Note 30i to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remote-procedure-call-woes-five-quick-solutions/"><u>Remote Procedure Call Woes - Five Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-disabled-usb-wi-fi-adapters-in-windows/"><u>How To Reactivate Disabled USB Wi-Fi Adapters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-good-old-windows-photo-viewer-in-win1111-os/"><u>Revive the Good Old Windows Photo Viewer in Win11/11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/1719319756779-revive-your-frozen-shift-key-on-pc/"><u>Revive Your Frozen Shift Key on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-devices-in-the-dormant-system-state/"><u>Controlling Devices in the Dormant System State</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-bring-your-vision-to-life-incorporating-free-lut-filters-into-obs-projects/"><u>[Updated] Bring Your Vision to Life  Incorporating Free LUT Filters Into OBS Projects</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-windows-n-variants-whats-worth-it/"><u>Comparing Windows N Variants: What's Worth It?</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-video-sequences-fixing-delay-on-windows/"><u>Speeding Up Video Sequences: Fixing Delay on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapshot-strategies-maintaining-consistent-snapstreaks/"><u>[New] Snapshot Strategies  Maintaining Consistent Snapstreaks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-your-path-to-perfect-videos-with-any-of-these-7-free-tools/"><u>[New] In 2024, Your Path to Perfect Videos with Any of These 7 Free Tools</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-message-rendering-issues-in-discord-desktop/"><u>Addressing Message Rendering Issues in Discord Desktop</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-capturing-online-seminars-for-2024/"><u>[New] Capturing Online Seminars for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-alignment-combat-overscan-effects/"><u>Perfect Windows Alignment: Combat Overscan Effects</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-itel-p40pluss-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Itel P40+s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-professional-livestreamers-vmix-or-wirecast/"><u>In 2024, The Ultimate Guide to Professional Livestreamers  VMix or Wirecast?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-win-ratio-valorant-optimization-guide/"><u>Enhancing Win Ratio: Valorant Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://win11.techidaily.com/1719286727564-gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://win11.techidaily.com/delve-into-artificially-inspired-visuals-how-to-use-paint-cocreator-win11/"><u>Delve Into Artificially Inspired Visuals: How to Use Paint Cocreator (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-connect-with-telnet-three-steps-for-windows-users/"><u>Efficiently Connect with Telnet: Three Steps for Windows Users</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-apple-iphone-se-2020-activation-lock-by-drfone-ios/"><u>How to Remove Apple iPhone SE (2020) Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
</ul></div>
