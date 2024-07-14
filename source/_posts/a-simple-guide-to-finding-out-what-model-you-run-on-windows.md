---
title: A Simple Guide to Finding Out What Model You Run on Windows
date: 2024-07-13T11:10:30.661Z
updated: 2024-07-14T11:10:30.661Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Simple Guide to Finding Out What Model You Run on Windows
excerpt: This Article Describes A Simple Guide to Finding Out What Model You Run on Windows
keywords: Windows OS Model Info,Determine Windows Version,Identify Windows System Type,Discover Windows Installation,Find Windows Edition,Uncover Windows Suite,Windows Desktop Specification
thumbnail: https://thmb.techidaily.com/5835b7f75acb6f437f70d9b6865adddf58cf9307d1c89bac2789b98350d1bacd.jpg
---

## A Simple Guide to Finding Out What Model You Run on Windows

 Whether you want to find the correct hardware upgrade for your computer or want to fix an issue, knowing about your computer model name can come in handy in various situations. Here are 6 quick ways to check your computer model name on Windows.

## 1\. Using the Settings App

![Checking System Name in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-name.jpg)

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see [how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to [check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)

## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the [HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to [enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

## Get to Know Your Computer's Model on Windows

 These were all the working ways using which you can know your computer model name. However there are many other methods to check the name, but the ones mentioned above are among the quickest and easiest.

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
<li><a href="https://some-approaches.techidaily.com/2024-approved-superb-online-stores-where-to-find-and-purchase-youtube-ringtones/"><u>2024 Approved  Superb Online Stores  Where to Find & Purchase YouTube Ringtones?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quickly-discard-outdated-graphics-drivers-windows-style/"><u>Quickly Discard Outdated Graphics Drivers, Windows-Style</u></a></li>
<li><a href="https://win11.techidaily.com/1719231593414-unveiling-the-impact-of-eradicating-windows-11s-taskbar-chatting-functionality/"><u>Unveiling the Impact of Eradicating Windows 11'S Taskbar Chatting Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/remote-procedure-call-woes-five-quick-solutions/"><u>Remote Procedure Call Woes - Five Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/1719290483430-quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-duties-assigned-to-film-set-personnel/"><u>In 2024, Duties Assigned to Film Set Personnel</u></a></li>
<li><a href="https://win11.techidaily.com/1719228805701-quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-disabled-usb-wi-fi-adapters-in-windows/"><u>How To Reactivate Disabled USB Wi-Fi Adapters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719239311887-unlock-the-future-at-an-irresistible-price-best-windows-11-deal-612lifetime-key-lovers-delight/"><u>Unlock the Future at an Irresistible Price – Best Windows 11 Deal, $6.12/Lifetime, Key Lovers' Delight</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-comedic-choreography-producing-funny-mock-films/"><u>[New] 2024 Approved  Comedic Choreography  Producing Funny Mock Films</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-video-annotation-tools-add-watermarks-and-captions/"><u>Free Video Annotation Tools Add Watermarks and Captions</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-best-selling-digital-audio-recorders-compatible-with-pcs/"><u>New Best-Selling Digital Audio Recorders Compatible with PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1719303345531-dealing-with-dysfunctional-print-via-wwin-command-on-windows/"><u>Dealing with Dysfunctional Print via WWin Command on Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-see-old-stories-on-facebook-find-story-archive-easily/"><u>2024 Approved  How to See Old Stories on Facebook  Find Story Archive Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-step-by-step-guide-to-applying-new-colors-and-textures-on-past-media-for-2024/"><u>[Updated] Step-by-Step Guide to Applying New Colors & Textures on Past Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-mouse-properties-on-windows-11/"><u>10 Ways to Open Mouse Properties on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/15-key-improvements-added-to-windows-11s-next-version/"><u>15 Key Improvements Added to Windows 11'S Next Version</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-ways-you-can-master-to-make-claymation-videos/"><u>New 2024 Approved Ways You Can Master to Make Claymation Videos</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-guide-add-luts-in-premiere-pro-with-ease/"><u>Updated Guide Add LUTs in Premiere Pro with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-good-old-windows-photo-viewer-in-win1111-os/"><u>Revive the Good Old Windows Photo Viewer in Win11/11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719265441814-change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-can-filmora-create-an-audio-visualizer-project-for-a-song-all-steps-from-launching-the-app-to-editing-the-text-are-detailed-here/"><u>In 2024, How Can Filmora Create an Audio Visualizer Project for a Song? All Steps, From Launching the App to Editing the Text, Are Detailed Here</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-copyright-clash-violation-removal-came-quick/"><u>[Updated] In 2024, Copyright Clash  Violation, Removal Came Quick</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://win11.techidaily.com/1719289257399-black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime!</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-instagram-cultivating-a-robust-following/"><u>The Art of Instagram  Cultivating a Robust Following</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-visual-narratives-instagram-carousel/"><u>2024 Approved  Visual Narratives  Instagram Carousel</u></a></li>
<li><a href="https://win11.techidaily.com/1719275577489-winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them</u></a></li>
<li><a href="https://win11.techidaily.com/1719281206376-win11-printer-woes-solutions-here/"><u>Win11 Printer Woes? Solutions Here!</u></a></li>
<li><a href="https://win11.techidaily.com/10-effective-command-line-steps-for-info-exploration/"><u>10 Effective Command-Line Steps for Info Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/1719292127499-overcome-windows-shift-glitch/"><u>Overcome Windows Shift Glitch.</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/discover-top-free-cameras-for-live-streaming-for-2024/"><u>Discover Top Free Cameras for Live Streaming for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-perfecting-your-image-dimensions-a-comprehensive-ratio-guide-for-2024/"><u>New Perfecting Your Image Dimensions A Comprehensive Ratio Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11-sandbox-initialization/"><u>Navigating Through Windows 11 Sandbox Initialization</u></a></li>
<li><a href="https://win11.techidaily.com/1719286727564-gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-boosting-social-reach-share-tiktoks-with-a-twist-of-twitter/"><u>In 2024, Boosting Social Reach  Share TikToks with a Twist of Twitter</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-artistic-additions-free-designs-for-youtube-crafting-for-2024/"><u>[Updated] Artistic Additions  Free Designs for YouTube Crafting for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719224494525-revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-connect-with-telnet-three-steps-for-windows-users/"><u>Efficiently Connect with Telnet: Three Steps for Windows Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transformative-tools-for-uploading-videos-to-twitter/"><u>2024 Approved  Transformative Tools for Uploading Videos to Twitter</u></a></li>
<li><a href="https://win11.techidaily.com/10-early-symptoms-of-windows-needing-a-fresh-start/"><u>10 Early Symptoms of Windows Needing a Fresh Start</u></a></li>
<li><a href="https://win11.techidaily.com/1719261545557-eliminate-roblox-error-262-in-minutes/"><u>Eliminate Roblox Error 262 in Minutes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avi-video-editing-made-easy-top-trimming-tools-for-every-platform/"><u>AVI Video Editing Made Easy Top Trimming Tools for Every Platform</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/is-it-possible-to-use-miracast-with-apple-iphone-11-drfone-by-drfone-ios/"><u>Is it Possible to Use Miracast with Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/solved-photos-disappeared-from-iphone-xs-suddenly-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Photos Disappeared from iPhone XS Suddenly | Stellar</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-leveraging-tools-for-seamless-powerpoint-transcription/"><u>[Updated] 2024 Approved  Leveraging Tools for Seamless PowerPoint Transcription</u></a></li>
<li><a href="https://win11.techidaily.com/1719245846865-windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance</u></a></li>
<li><a href="https://win11.techidaily.com/1719298121554-troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/1719319756779-revive-your-frozen-shift-key-on-pc/"><u>Revive Your Frozen Shift Key on PC.</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-essential-5-audio-blender-apps-for-mac-users/"><u>Updated 2024 Approved Essential 5 Audio Blender Apps for Mac Users</u></a></li>
</ul></div>
