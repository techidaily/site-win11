---
title: "Win 11: Set Default Touch Input Placement"
date: 2024-08-15T23:45:22.036Z
updated: 2024-08-16T23:45:22.036Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Set Default Touch Input Placement"
excerpt: "This Article Describes Win 11: Set Default Touch Input Placement"
keywords: Win 11 Quickset,Win 11 Touchplacement,Win 11 DefaultInput,AdjustWinTouchInput,ChangeDefaultPlacement,Win11TouchSettings,InputPlacementWin11
thumbnail: https://thmb.techidaily.com/7e37922976a0cd02bd45d34c10fef6f069d63ae07942af07cd489ff374cb4abd.png
---

## Win 11: Set Default Touch Input Placement

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-innovative-editing-youtube-studio-edition-insights/"><u>[New] 2024 Approved  Innovative Editing  YouTube Studio Edition Insights</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-micro-enterprises-guide-to-viral-video-promotion/"><u>[New] 2024 Approved  Micro-Enterprises' Guide to Viral Video Promotion</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-beyond-basic-the-advanced-techniques-of-youtube-counts-for-2024/"><u>[New] Beyond Basic  The Advanced Techniques of YouTube Counts for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-elevating-visual-experience-youtubes-quality-boosting-guide/"><u>[New] Elevating Visual Experience  YouTube's Quality Boosting Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-delve-into-all-shared-visuals-within-a-chat-on-messenger/"><u>[New] In 2024, Delve Into All Shared Visuals Within a Chat on Messenger</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitters-viral-spotlight-top-10-tiktoks-of-the-week/"><u>[New] In 2024, Twitter's Viral Spotlight  Top 10 TikToks of the Week</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ncrease-your-online-presence-youtube-methods/"><u>[New] Increase Your Online Presence  YouTube Methods</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-swipe-right-on-virality-blend-tiktok-trends-into-insta-reels/"><u>[New] Swipe Right on Virality  Blend TikTok Trends Into Insta Reels</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unexpected-10-best-kept-facebook-memes-for-2024/"><u>[New] Unexpected  10 Best-Kept Facebook Memes for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unleashing-creativity-top-30-video-plans-for-2024/"><u>[New] Unleashing Creativity  Top 30 Video Plans for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-conquering-capture-a-detailed-walkthrough-for-ps4-recordings/"><u>[Updated] 2024 Approved  Conquering Capture  A Detailed Walkthrough for PS4 Recordings</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-mastering-fb-reel-creation-step-by-step-guide/"><u>[Updated] 2024 Approved  Mastering FB Reel Creation  Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-compare-and-contrast-leading-online-and-desktop-gif-tools-for-2024/"><u>[Updated] Compare & Contrast  Leading Online & Desktop GIF Tools for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-discover-how-to-thrive-in-tiktok-lives-from-desktop/"><u>[Updated] Discover How to Thrive in TikTok Lives From Desktop</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-e-identity-evolution-crafting-an-animated-persona/"><u>[Updated] E-Identity Evolution  Crafting an Animated Persona</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-skyrocket-your-view-count-youtube-success-via-sony-vegas-editing/"><u>[Updated] Skyrocket Your View Count  YouTube Success via Sony Vegas Editing</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-repairing-your-windows-headsets-microphone/"><u>Addressing and Repairing Your Windows Headset's Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-functionality-of-law-filters-for-windows-users/"><u>Decoding the Functionality of LAW Filters for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-mozilla-thunderbirds-new-release-version-52-is-here-now/"><u>Discover Mozilla Thunderbird's New Release - Version 52 Is Here Now</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-updated-killer-wireless-nic-card-driver-version-1535/"><u>Download and Install Updated Killer Wireless NIC Card Driver Version 1535</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-audio-archives-where-to-find-copyright-free-tunes/"><u>Essential Audio Archives  Where to Find Copyright-Free Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/expert-recording-software-for-desktop-hd-video-for-2024/"><u>Expert Recording Software for Desktop HD Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-itel-p55-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Itel P55 5G Devices | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/game-capture-software-rivalry-obs-vs-shadowplay/"><u>Game Capture Software Rivalry  OBS Vs. ShadowPlay</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-upgrade-error-0xc004f050/"><u>How to Fix the Windows Upgrade Error 0Xc004f050</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-12-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 12 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-3-ways-to-unlock-your-iphone-6-plus-for-free-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Your iPhone 6 Plus for Free</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-sony-xperia-10-v-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Sony Xperia 10 V to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-inspecting-and-cleaning-windows-logs/"><u>Mastering the Art of Inspecting & Cleaning Windows Logs</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-display-driver-found-on-windows-11/"><u>Overcoming No Display Driver Found on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-early-edge-tab-launches-on-windows-11/"><u>Prevent Early Edge Tab Launches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proper-methods-to-turn-windows-key-onoff/"><u>Proper Methods to Turn Windows Key On/Off</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-dormant-screen-saver-configurations-in-windows/"><u>Revitalizing Dormant Screen Saver Configurations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/scripting-efficient-files-a-python-server-guide-for-windows-os/"><u>Scripting Efficient Files: A Python Server Guide for Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pc-transferring-preferences-from-one-to-another/"><u>Securing Your PC: Transferring Preferences From One to Another</u></a></li>
<li><a href="https://win11.techidaily.com/shrouded-functionality-unveiling-hidden-context-menus-in-win11/"><u>Shrouded Functionality: Unveiling Hidden Context Menus in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-low-usb-availability-windows-wise/"><u>Steps to Rectify Low USB Availability Windows-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-rectifying-windows-error-code-0x80040610/"><u>Swift Solutions for Rectifying Windows Error Code 0X80040610</u></a></li>
<li><a href="https://win11.techidaily.com/the-final-countdown-for-windows-xp-7-and-81-lifeline-on-microsoft/"><u>The Final Countdown for Windows XP, 7 & 8.1 Lifeline on Microsoft</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-asus-rog-phone-7-frp-by-drfone-android/"><u>The Updated Method to Bypass Asus ROG Phone 7 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winmedia-server-error/"><u>Troubleshooting WinMedia Server Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-the-devices-not-recognized-issue-on-windows-7/"><u>Troubleshooting: How to Fix the 'Devices Not Recognized' Issue on Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-code-navigating-through-lost-windows-1110-patches/"><u>Unlock the Code: Navigating Through Lost Windows 11/10 Patches</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-potential-of-openais-ai-for-voice-to-text-in-windows/"><u>Unlocking the Potential of OpenAI's AI for Voice-to-Text in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-xiaomi-civi-3-disney-100th-anniversary-edition-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Xiaomi Civi 3 Disney 100th Anniversary Edition Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-lava-blaze-curve-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Lava Blaze Curve 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-customizable-spotlight-picture-guide/"><u>Windows Customizable Spotlight Picture Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/your-life-your-legacy-youtube-videos-that-matter/"><u>Your Life, Your Legacy  YouTube Videos That Matter</u></a></li>
</ul></div>
