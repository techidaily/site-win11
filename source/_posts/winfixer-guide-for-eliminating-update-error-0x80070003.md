---
title: Winfixer Guide for Eliminating Update Error 0X80070003
date: 2024-09-11T09:34:30.271Z
updated: 2024-09-12T09:34:30.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winfixer Guide for Eliminating Update Error 0X80070003
excerpt: This Article Describes Winfixer Guide for Eliminating Update Error 0X80070003
keywords: Winfixer Error Fix,Elimination of Update Error,XError 0X80070003 Guide,Windows Update Error Solution,Correcting Windows Error 0X80070003,Resolving Update Failure in Windows,Fixing 0X80070003 Updater Issue
thumbnail: https://thmb.techidaily.com/7bdbd3764d17d309bfae3520695cdadc9f0f0ab5ea703a9227f88bc7f132643b.jpg
---

## Winfixer Guide for Eliminating Update Error 0X80070003

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123468/16836" target="_top" id="2123468">
  <img src="//a.impactradius-go.com/display-ad/16836-2123468" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123468/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-dial-back-your-playlist-quick-steps-to-reverse-order/"><u>[New] 2024 Approved Dial Back Your Playlist Quick Steps to Reverse Order</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-depth-look-the-prime-snipping-options-on-macos-for-2024/"><u>[New] In-Depth Look The Prime Snipping Options on macOS for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nlocking-youtube-melodies-safe-free-extraction-methods/"><u>[New] Unlocking YouTube Melodies Safe, Free Extraction Methods</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-navigating-your-net-gain-three-steps-to-quantify-your-youtube-earnings/"><u>[Updated] 2024 Approved Navigating Your Net Gain Three Steps to Quantify Your YouTube Earnings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-capturing-the-ultimate-xbox-experience-a-screen-recorders-manual/"><u>[Updated] Capturing the Ultimate Xbox Experience A Screen Recorder's Manual</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-game-ahead-with-funimates-easy-apk-instructions/"><u>[Updated] Game Ahead with Funimate's Easy APK Instructions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-gameplay-in-focus-scrutinizing-screen-recorders/"><u>[Updated] Gameplay in Focus Scrutinizing Screen Recorders</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-navigating-filmoras-fcc-initiative-a-guide/"><u>[Updated] Navigating Filmora's FCC Initiative A Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-premier-virtual-microphones/"><u>[Updated] Premier Virtual Microphones</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-prime-video-chat-solutions-for-pcs-and-phones-for-2024/"><u>[Updated] Prime Video Chat Solutions for PCs & Phones for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-synchronize-your-calendars-for-smooth-video-calls/"><u>[Updated] Synchronize Your Calendars for Smooth Video Calls</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-cinematic-brilliance-in-motion-kinemaster-techniques/"><u>2024 Approved Cinematic Brilliance in Motion Kinemaster Techniques</u></a></li>
<li><a href="https://article-files.techidaily.com/ace-your-channel-prime-title-generators/"><u>Ace Your Channel Prime Title Generators</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-acpi-errors-id-33a0/"><u>Correcting ACPI Errors - ID 33A0</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-screen-real-estate-win11s-best-practices/"><u>Customizing Screen Real Estate: Win11's Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-aggregatorhostexe-purpose-and-security/"><u>Demystifying Windows' AggregatorHost.exe: Purpose & Security</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-best-of-both-worlds-windows-and-games/"><u>Exploring the Best of Both Worlds: Windows & Games</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-world-of-gadgets-with-toms-hardware-reviews/"><u>Exploring the World of Gadgets with Tom's Hardware Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-restoring-lost-bluetooth-connectivity-in-win-11/"><u>Fix the Gap: Restoring Lost Bluetooth Connectivity in Win 11</u></a></li>
<li><a href="https://techidaily.com/hard-reset-honor-x9b-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Honor X9b in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-oppo-a78-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-capture-memories-in-high-quality-a-comprehensive-guide-to-logitech-webcam-use/"><u>In 2024, Capture Memories in High Quality A Comprehensive Guide to Logitech Webcam Use</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-realme-12-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Realme 12 5G Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insights-into-microsofts-comprehensive-ai-ecosystem/"><u>Insights Into Microsoft's Comprehensive AI Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/master-naming-conventions-for-windows-files-max-156/"><u>Master Naming Conventions for Windows Files (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-protection-ranked-encryption-tools-for-windows-150-chars/"><u>Mastering Data Protection: Ranked Encryption Tools for Windows (150 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-code-fixation-in-win10win11s-shop/"><u>Mastering Error Code Fixation in Win10/Win11's Shop</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-potential-through-efficient-use-of-law-filters/"><u>Maximizing Windows Potential Through Efficient Use of LAW Filters</u></a></li>
<li><a href="https://win11.techidaily.com/mute-to-noise-fixing-your-google-meet-mic-on-windows-pc/"><u>Mute to Noise? Fixing Your Google Meet Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winget-hurdles-on-windows-11-systems/"><u>Overcoming Winget Hurdles on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-absent-logins-in-windows-11-os/"><u>Recovering Absent Logins in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-prompt-gaps-seamless-action-integration-in-windows/"><u>Resolving Network Prompt Gaps: Seamless Action Integration in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-control-center-mastering-management-on-windows-11/"><u>Securing Your Control Center: Mastering Management on Windows 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/sifting-truth-in-online-medical-advice-by-ai/"><u>Sifting Truth in Online Medical Advice by AI</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win1011s-network-error-code-0x800704b3/"><u>Solving Win10/11's Network Error Code: 0X800704B3</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlining-dells-auditory-experience-with-updated-drivers/"><u>Streamlining Dell's Auditory Experience with Updated Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/switching-highlight-features-with-ease-in-windows-11/"><u>Switching Highlight Features with Ease in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/sync-fail-resolving-outlook-app-errors-on-pcs/"><u>Sync Fail: Resolving Outlook App Errors on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-drawing-apps-on-win-11/"><u>The Ultimate Guide to Choosing Drawing Apps on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-resource-for-streamlined-navigation-windows-narrator-keybindings/"><u>The Ultimate Resource for Streamlined Navigation: Windows Narrator Keybindings</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-malfunctioning-discord-game-checker-on-windows/"><u>Tips to Rectify Malfunctioning Discord Game Checker on Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-guide-converting-movies-into-dvds-using-nero-burning-rom/"><u>Ultimate Guide: Converting Movies Into DVDs Using Nero Burning ROM</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-frozen-firewall-settings-in-windows-11/"><u>Unfreezing Frozen Firewall Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-microsoft-store-quick-sign-in-fixes/"><u>Unlocking the Microsoft Store: Quick Sign-In Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-to-flawless-steam-logins-rustwindows-edition/"><u>Unlocking the Secret to Flawless Steam Logins: Rust/Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wallpaper-guide-incorporating-spotlight-photos/"><u>Windows Wallpaper Guide: Incorporating Spotlight Photos</u></a></li>
</ul></div>

