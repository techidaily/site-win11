---
title: Solving The Application Was Unable to Start in Win10/11
date: 2024-08-28T00:56:01.060Z
updated: 2024-08-29T00:56:01.060Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving The Application Was Unable to Start in Win10/11
excerpt: This Article Describes Solving The Application Was Unable to Start in Win10/11
keywords: Windows Boot Issue,App Starts Problems,Win10/11 Start Trouble,Fixing App Error,Startup Application Fail,Windows OS Compatibility,System Boot Error
thumbnail: https://thmb.techidaily.com/0f7cc598462e00e671398d3de2bdb7c71a59af5f2607e912d55b8b85ab2b5c83.jpg
---

## Solving The Application Was Unable to Start in Win10/11

 Error 0xc000003e is among the more widely reported startup issues for Windows software packages. That error displays this message when users select to run recently installed software, “The application was unable to start correctly (0xc000003e).” As a result, users can’t open and utilize programs for which that error message pops up.

 The 0xc000003e error has been mostly reported for the Zoom and Discord apps, but it can arise for other software. It’s an issue that can occur on Windows 11, 10, and 8 platforms. Here are some probable resolutions for fixing the 0xc000003e error.

## 1\. Set the Affected Software to Run With Admin Rights

 Firstly, try opening affected software with administrative rights. Some apps the 0xc000003e error occurs for might need more elevated permissions to operate. You can set the software to run as an administrator like this:

1. Open Windows Explorer and open the installation directly that includes the affected software.
2. Right-click the EXE (application) file for the software error 0xc000003e occurs and select**Properties** .
3. Then click**Compatibility** to access the settings below.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/compatibility-tab.jpg)
4. Select**Run this program as administrator** to set the program to run with elevated permissions.
5. Click**Apply** to save the selected options.
6. Press the**OK** button to exit the window.

## 2\. Run the Compatibility Troubleshooter

 Error 0xc000003e can sometimes occur because of software compatibility issues. Windows has a Compatibility Troubleshooter that applies recommended compatibility settings for programs, which might help some users fix the 0xc000003e error. This is how you run that compatibility troubleshooter in Windows:

1. First, open the**Compatibility** tab for an affected program as instructed in steps one to three of this guide’s first potential resolution.
2. Click the**Run compatibility troubleshooter** button.
3. Select the**Try recommended settings** option.  
![The Try recommended settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/try-recommended-settings-option.jpg)
4. Press the**Test the program** button to see if the software works with recommended settings.  
![The Test the program button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/test-the-program-button.jpg)
5. Select**Next** on the Program Compatibility Troubleshooter window.
6. Click**Yes, save these settings** if the**Test Program** option opened the software.  
![The Yes, save these settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/yes-option.jpg)
7. Close out of the troubleshooter, and restart your PC.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair System Files

 System file corruption is one of the more regular causes of software startup errors in Windows. It’s recommended to run both Deployment Image Servicing and Management and System File Checker scans for repairing system files. A DISM scan can repair image component store corruption. These are the steps for running those scans in the Command Prompt:

1. Click the Windows taskbar’s search box or button (magnifying glass icon).
2. Type the search phrase**cmd** inside the text box.
3. Click**Command Prompt** with your mouse’s right button to select a**Run as administrator** option (see[how to run the Command Prompt as administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more methods).
4. Then input this Prompt command and press**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Enter and execute the following SFC command:  
`sfc /scannow`  
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-sfc-command.jpg)
6. Wait for the scan to reach a 100 percent mark and show a Windows Resource Protection outcome message.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

## 4\. Run a Check Disk Scan

 You might need to fix error 0xc000003e because of a drive issue. There could be bad disk sectors on your PC’s hard drive that store data for affected software packages. Running a Check Disk (Chkdsk) scan could resolve such an issue. You can run such as scan with Windows’ Chkdsk utility as follows:

1. Bring up Command Prompt with administrative rights, as covered in resolution three.
2. Type in and execute this Chkdsk command:  
`chkdsk c: /f /r`
3. Press**Y** and**Enter** when prompted to schedule the scan for a restart.  
![A Chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/chkdsk-scan.jpg)
4. Next, select to restart Windows 11 or 10\. The Chkdsk utility will start its scanning after the restart.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Run an Antivirus Scan

 Malware is another possible cause for the error 0xc000003e. So, it’s recommended users manually run an antivirus scan in Windows. This is how you can run an antivirus scan with the built-in Windows Security utility:

1. Open Windows Security by double-clicking the system tray (shield) icon for that app.
2. Select the**Virus & threat protection** tab.  
![The Home tab in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-virus-threat-protection-tab.jpg)
3. Click**Scan options** to view all settings for scanning.  
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-scan-options-link.jpg)
4. Select the radio button for the**Full scan** option.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/full-scan-option.jpg)
5. Click**Scan now** to start the antivirus scanning.

## 6\. Temporarily Turn Off Antivirus Protection

 It’s not uncommon for some third-party antivirus software to sound false positive alarms for legitimate software processes. Such incorrect detection can generate all kinds of startup errors for flagged programs. If you have installed a third-party antivirus utility, turn its shield off and then try launching any software for which error 0xc000003e occurs.

 How exactly you disable third-party antivirus utilities varies between apps. However, you can usually select to turn off antivirus tools from their context menus. Right-click a system tray icon for your antivirus package to see if its context menu includes an option for disabling its shield. If it does, select to turn off the shield for an hour or so.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall the Program Affected With Error 0xc000003e

 The 0xc000003e error can also arise because of corrupted software installations. You can fix a corrupted software installation by reinstalling the app. Reinstalling will also ensure you have the latest app version, which can address compatibility issues.

 Uninstall the affected app with one of the methods in our guide on[how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Roll Back Windows With the System Restore Tool

 If you have System Restore enabled on your PC, that utility may provide a potential fix for 0xc000003e. System Restore enables you to roll Windows back to saved restoration points, which can fix corrupted system files. Selecting a restore point that predates the 0xc000003e error on your PC could fix the issue.

 Our guide on[how to create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) includes full instructions about how to roll back Windows with System Restore. Note that any software you installed after a selected restore point will not be available after rolling back Windows. You’ll need to reinstall the software packages removed for a chosen restoration point.

![The System Restore point tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-system-restore-point.jpg)

## Get Error 0xc000003e Sorted on Your PC

 So, that’s how you can get the 0xc000003e error sorted out in Windows 11 and 10\. We don’t promise those possible solutions will work for everybody. However, they’re some of the most likely ways to fix error 0xc000003e. Beyond those resolutions, clean booting and updating Windows might also help some users resolve error 0xc000003e.

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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-the-basics-of-electronic-story-craftsmanship/"><u>[Updated] 2024 Approved  The Basics of Electronic Story Craftsmanship</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-the-complete-process-for-crafting-your-own-ringtone-from-tiktok-music/"><u>[Updated] 2024 Approved  The Complete Process for Crafting Your Own Ringtone From TikTok Music</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-metaverse-laughter-creating-your-own-funny-online-jokes/"><u>[Updated] Exploring Metaverse Laughter  Creating Your Own Funny Online Jokes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-complete-guide-for-capturing-stunning-details-on-film/"><u>[Updated] The Complete Guide for Capturing Stunning Details on Film</u></a></li>
<li><a href="https://ai-voice.techidaily.com/an-ultimate-guide-of-best-narrator-voice-generators-for-2024/"><u>An Ultimate Guide of Best Narrator Voice Generators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-the-no-scripts-allowed-error-in-windows-ps-four-fixes-at-hand/"><u>Conquering the 'No Scripts Allowed' Error in Windows PS: Four Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-audio-issue-in-win11-error-0xc00d36b4/"><u>Correcting Audio Issue in Win11, Error 0xC00D36B4</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-swiftly-engage-windows-support-services/"><u>Discover How to Swiftly Engage Windows' Support Services</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-from-your-apple-iphone-6-plus-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password From your Apple iPhone 6 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-mystery-of-not-found-in-windows-pc/"><u>Fixing the Mystery of 'Not Found' In Windows PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/flying-high-hubsan-h501x4-drone-unveiled/"><u>Flying High  Hubsan H501X4 Drone Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-solve-unplayable-video-files-on-windows/"><u>Guides to Solve Unplayable Video Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/has-windows-subsystem-for-linux-helped-linux-gain-desktop-market-share/"><u>Has Windows Subsystem for Linux Helped Linux Gain Desktop Market Share?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-0x800700e1-in-windows-10-and-11/"><u>How to Fix Error 0X800700E1 in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-the-application-couldnt-start-error-code-0xc000003e-on-win11/"><u>How to Rectify The The Application Couldn't Start Error Code 0XC000003e on Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-samsung-galaxy-a23-5g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Samsung Galaxy A23 5G Phone?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-no-more-quick-yt-thumbnails-full-length-viewing/"><u>In 2024, No More Quick YT Thumbnails  Full-Length Viewing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/journey-through-filmora-editing-10-standout-functions/"><u>Journey Through Filmora Editing  10 Standout Functions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-contextual-menu-additions-in-win1011/"><u>Mastering Contextual Menu Additions in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-control-in-windows-11-os/"><u>Mastering Highlight Control in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ipmac-discovery-on-windows-ps-style/"><u>Mastering IP/MAC Discovery on Windows, PS Style</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-enhancing-gameplay-with-amd-tweaks/"><u>Mastering the Art of Enhancing Gameplay with AMD Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-regulation-of-biometrics-by-windows-11-users/"><u>Mastering the Regulation of Biometrics by Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-net-ensuring-stable-connections/"><u>Mastering Windows Net: Ensuring Stable Connections</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-direct-image-access-with-windows-11/"><u>Maximizing Direct Image Access with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-malfunctions-in-windows/"><u>Resolving Steam Cloud Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-slack-notification-functionality/"><u>Restoring Lost Slack Notification Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solutions-for-win-11-issues-through-shortcut-buttons-guide/"><u>Speedy Solutions for Win 11 Issues Through Shortcut Buttons Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-control-panel-writable-error/"><u>Steps to Fix Windows Control Panel' Writable Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-unblock-printer-access-in-windows-11/"><u>Steps to Unblock Printer Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-way-inout-of-terminals-focused-mode/"><u>Streamlining Your Way In/Out of Terminal’s Focused Mode</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/swift-fixes-to-rectify-non-sending-videos-on-the-social-networking-platform-iphoneandroid/"><u>Swift Fixes to Rectify Non-Sending Videos on the Social Networking Platform iPhone/Android</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-streamlining-storage-in-win-11/"><u>The Ultimate Guide to Streamlining Storage in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3dx939dll-absence-on-windows-11/"><u>Troubleshooting D3DX9_39.dll Absence on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-the-isdonedll-isarcextract-fault-on-pcs/"><u>Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-install-clipchamp-on-windows-11-try-these-fixes/"><u>Unable to Install ClipChamp on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-apk-setup-made-simple-with-one-click/"><u>Windows 11 APK Setup Made Simple With One Click</u></a></li>
</ul></div>
