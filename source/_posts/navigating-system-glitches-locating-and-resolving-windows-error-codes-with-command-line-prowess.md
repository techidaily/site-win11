---
title: "Navigating System Glitches: Locating & Resolving Windows Error Codes with Command Line Prowess"
date: 2024-09-11T09:37:44.519Z
updated: 2024-09-12T09:37:44.519Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating System Glitches: Locating & Resolving Windows Error Codes with Command Line Prowess"
excerpt: "This Article Describes Navigating System Glitches: Locating & Resolving Windows Error Codes with Command Line Prowess"
keywords: Fixing Win Errors,Command Line Repair,Windows Troubleshooting,Glitch Resolution Tools,System Diagnostic Commands,Error Codes Guide,Command Window Solutions
thumbnail: https://thmb.techidaily.com/ad574335e648a7deda4261a3d60c02e5050876ad97d3a8d2551786ec91da20e4.jpg
---

## Navigating System Glitches: Locating & Resolving Windows Error Codes with Command Line Prowess

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can[access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by[running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
3. Choose**Command Prompt** from the list of options available.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.

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
<li><a href="https://win-able.techidaily.com/fixed-steam-not-detecting-controller-on-windows/"><u>[Fixed] Steam Not Detecting Controller on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-privacy-pioneers-explore-instagram-stories-secretly/"><u>[New] In 2024, Privacy Pioneers Explore Instagram Stories Secretly</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-mastering-igtv-followers-essential-techniques-to-grow-your-audience-for-2024/"><u>[New] Mastering IGTV Followers Essential Techniques to Grow Your Audience for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-exploring-quantum-hdrs-impact-on-photography-for-2024/"><u>[Updated] Exploring Quantum HDR's Impact on Photography for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-high-end-methods-for-monitoring-and-recording-pc-sounds-for-2024/"><u>[Updated] High-End Methods for Monitoring and Recording PC Sounds for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-step-by-step-guide-to-background-dimming-in-videos/"><u>[Updated] In 2024, Step-by-Step Guide to Background Dimming in Videos</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-convert-youtube-videos-smoothly-into-professional-webm-files/"><u>2024 Approved Convert YouTube Videos Smoothly Into Professional WebM Files</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-iphone-hdr-a-step-by-step-journey-to-perfect-shots/"><u>2024 Approved IPhone HDR A Step-by-Step Journey to Perfect Shots</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-weekly-must-watch-excellence-in-igtv/"><u>2024 Approved Weekly Must-Watch Excellence in IGTV</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/a-step-by-step-approach-to-saving-your-screen-while-streaming/"><u>A Step-by-Step Approach to Saving Your Screen While Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/combating-valorant-communication-breakdowns-on-windows-78/"><u>Combating Valorant Communication Breakdowns on Windows 7/8</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-activities-deactivate-windows-eye-on-users/"><u>Concealing Activities: Deactivate Windows' Eye on Users</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/crescendo-video-tips-for-music-loving-snapchaters/"><u>Crescendo Video Tips for Music-Loving Snapchaters</u></a></li>
<li><a href="https://win11.techidaily.com/dazzling-display-holiday-themed-window-wonders/"><u>Dazzling Display: Holiday Themed Window Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/designing-keybindings-for-windows-applications/"><u>Designing Keybindings for Windows Applications</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721938666609-download-chatgpt-your-ai-companion-is-now-accessible-on-android-devices/"><u>Download ChatGPT: Your AI Companion Is Now Accessible on Android Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/earn-big-stay-safe-top-5-income-boosting-posts/"><u>Earn Big, Stay Safe Top 5 Income Boosting Posts</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-restoring-system-calls-on-win1111/"><u>Eliminating Obstacles: Restoring System Calls on Win11/11</u></a></li>
<li><a href="https://win11.techidaily.com/escalate-your-internet-speed-triumph-over-windows-100mbps-barrier/"><u>Escalate Your Internet Speed: Triumph Over Windows' 100Mbps Barrier</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-for-configuring-dns-in-windows-11/"><u>Expert Strategies for Configuring DNS in Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/free-screen-recorder-roundup-the-premium-selection-for-your-android-device-for-2024/"><u>Free Screen Recorder Roundup The Premium Selection for Your Android Device for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-activate-stellar-data-recovery-for-iphone-11-pro-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Activate Stellar Data Recovery for iPhone 11 Pro Max | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-system-errors-following-a-windows-update/"><u>How to Correct System Errors Following a Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-audio-error-windows-11-0xc00d36b4/"><u>How to Mend Audio Error: Windows 11, 0XC00D36B4</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-itel-p40plus-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Itel P40+ Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-spontaneous-command-window-flashes/"><u>How to Stop Spontaneous Command Window Flashes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-stop-automatic-windows-updates/"><u>How to Temporarily Stop Automatic Windows Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-18-breakthrough-metaverse-models-for-enhanced-perspective/"><u>In 2024, 18 Breakthrough Metaverse Models for Enhanced Perspective</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-14-pro-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone 14 Pro in the Best Ways</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-premium-top-5-budget-friendly-chromeos-recorders/"><u>In 2024, Premium Top 5 Budget-Friendly ChromeOS Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-unrealcefsubprocess-impact-on-system-resources/"><u>Lowering UnrealCEFSubprocess Impact on System Resources</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-connections-with-spotify/"><u>Mastering Windows 11 Connections with Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-resolution-0x80072f8f/"><u>Mastering Windows Error Resolution: 0X80072f8f</u></a></li>
<li><a href="https://tech-hub.techidaily.com/narrative-through-symbols-in-finance/"><u>Narrative Through Symbols in Finance</u></a></li>
<li><a href="https://win11.techidaily.com/nine-essential-tips-for-new-windows-11-users-avoid-these-errors/"><u>Nine Essential Tips for New Windows 11 Users - Avoid These Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-opening-of-file-explorer/"><u>Overcoming Excessive Opening of File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/relaunching-file-explorer-a-step-bystep-guide/"><u>Relaunching File Explorer: A Step-Bystep Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-samsung-galaxy-a54-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Samsung Galaxy A54 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-absence-of-msvcr120dll-in-windows-environments/"><u>Resolving Absence of MSVCR120.DLL in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-the-missing-dll-error-rockalldlldll/"><u>Resolving the Missing DLL Error: Rockalldll.dll</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solution-matching-internet-on-mobile-and-desktop/"><u>Speedy Solution: Matching Internet on Mobile & Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-windows-service-error-1053/"><u>Strategies for Overcoming Windows Service Error 1053</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/stylishly-streaming-to-your-tv-discover-the-benefits-of-antops-at-127-antenna-comprehensive-review/"><u>Stylishly Streaming to Your TV? Discover the Benefits of Antop's AT-127 Antenna - Comprehensive Review</u></a></li>
<li><a href="https://win11.techidaily.com/subtle-system-tweaks-windows-toolbars-unseen/"><u>Subtle System Tweaks: Windows Toolbars Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-signature-compliant-update-files-on-windows/"><u>Tackling Non-Signature Compliant Update Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-to-resolve-skies-sse-woes/"><u>The Quest to Resolve Skies' SSE Woes</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-for-designing-custom-lock-patterns-in-windows-11/"><u>The Ultimate Technique for Designing Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-to-fix-windows-error-message-0x8007007e/"><u>Tips and Tricks to Fix Windows Error Message 0X8007007E</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-review-expert-insights-on-computer-hardware-t17239718737473/"><u>Tom's Tech Review: Expert Insights on Computer Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-to-resolve-no-servers-found-navigating-apex-legends-windows-(156-chars/"><u>Top Tips to Resolve 'No Servers Found': Navigating Apex Legends Windows (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-microsoft-store-on-windows-10-and-11-with-x800704cf-error/"><u>Unblocking Microsoft Store on Windows 10 & 11 with X800704CF Error</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-honor-magic-vs-2-by-drfone-android/"><u>Universal Unlock Pattern for Honor Magic Vs 2</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-strategies-to-exit-s-mode/"><u>Unlocking Your PC: Strategies to Exit S Mode</u></a></li>
</ul></div>

