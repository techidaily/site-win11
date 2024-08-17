---
title: Addressing 'Occupied' File Problems in Windows 11
date: 2024-08-15T23:20:12.407Z
updated: 2024-08-16T23:20:12.407Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'Occupied' File Problems in Windows 11
excerpt: This Article Describes Addressing 'Occupied' File Problems in Windows 11
keywords: Win11 Files Issue Resolution,Windows 11 Occupation Error Fix,Addressing Filenames in Win11,Troubleshoot Win11 File Labels,Resolve Occupied Files in Win11,Overcoming Win11 Naming Conflicts,Win11 Fix
thumbnail: https://thmb.techidaily.com/246d0000b4a8f8f8e29a0c282b538c53c7dcabe9e936ddda4c95b0a712854944.jpg
---

## Addressing 'Occupied' File Problems in Windows 11

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
5. Then try moving or copying your files again.

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
3. Select the **Full scan** setting.
4. Click **Scan now** to initiate the malware scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-full-scan-radio-button.jpg)
5. Wait for the scanning to finish and select **Start actions** to remove detected malware.

 If you find Microsoft Defender is disabled and cannot turn it on, that’s a surefire sign the SmartService malware has infected your PC. SmartService is a rootkit trojan that blocks users from utilizing antivirus tools. That malware can also block the installation of some antivirus apps. In this case, the “requested resource in use” error can also occur when you try to run security apps.

 To circumvent such a block, try running a Windows Security or third-party app antivirus scan in safe mode instead. Our guide to [booting into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) includes a few different methods for entering that troubleshooting mode. Select to enable safe mode with networking.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
3. Right-click on the suspected SmartService malware and select **Uninstall**.
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-15-high-performing-instagram-content-extractors/"><u>[New] 2024 Approved  15 High-Performing Instagram Content Extractors</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-audiovisual-virtuoso-capturing-emotion-in-harmony/"><u>[New] 2024 Approved  Audiovisual Virtuoso  Capturing Emotion in Harmony</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-crafting-compelling-gopro-livestreams-on-facebook-and-periscope/"><u>[New] 2024 Approved  Crafting Compelling GoPro Livestreams on Facebook & Periscope</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-decoding-the-language-of-asmr-videos/"><u>[New] 2024 Approved  Decoding the Language of ASMR Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-speech-reader-feedback-summary/"><u>[New] In 2024, Speech Reader Feedback Summary</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-fast-track-to-youtube-partner-level-achieve-10k-views/"><u>[Updated] Fast Track to YouTube Partner Level - Achieve 10K Views</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-immerse-in-youtubes-best-vr-visual-feasts/"><u>[Updated] Immerse in YouTube's Best VR Visual Feasts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-innovative-methods-for-time-loop-illusions/"><u>[Updated] In 2024, Innovative Methods for Time Loop Illusions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-power-players-unleashed-youtubes-female-elite/"><u>[Updated] Power Players Unleashed  YouTube’s Female Elite</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-best-4k-blu-ray-experience-ranking-of-devices/"><u>[Updated] The Best 4K Blu-Ray Experience  Ranking of Devices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/10-ai-forecasters-sharing-their-outlook/"><u>10 AI Forecasters Sharing Their Outlook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-examination-of-xcreative-vision-studio-a-complete-guide/"><u>2024 Approved  In-Depth Examination of XCreative Vision Studio - A Complete Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/a-guide-to-pinpointing-posted-videos-in-fb-groups/"><u>A Guide to Pinpointing Posted Videos in FB Groups</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-plan-9-steps-to-stop-wwe-crashes-in-windows/"><u>Accelerated Action Plan: 9 Steps to Stop WWE Crashes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-menu-items-in-windows-11-desktop/"><u>Addressing Frozen Menu Items in Windows 11 Desktop</u></a></li>
<li><a href="https://vp-tips.techidaily.com/computational-photography-what-are-auto-hdr-smart-hdr-3-and-4-shooting-modes/"><u>Computational Photography  What Are Auto HDR, Smart HDR 3 & 4 Shooting Modes?</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-effective-power-indicators-in-windows/"><u>Crafting Effective Power Indicators in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-chkdsk-sfc-and-dism-for-system-repairing/"><u>Decoding CHKDSK, SFC & DISM for System Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-spotify-connectivity-fails/"><u>Eliminating Windows 11'S Spotify Connectivity Fails</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-fb-soundbank-freeness-central/"><u>In 2024, FB Soundbank  Freeness Central</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-lava-blaze-2-5g-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Lava Blaze 2 5G? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-plus-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 8 Plus without Passcode or Face ID</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-a38-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo A38 Device</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/lut-lovers-delight-complimentary-sets-for-djis-miniair2-for-2024/"><u>LUT Lovers Delight  Complimentary Sets for DJI's Mini/Air2 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-your-windows-stylus-device/"><u>Mastering the Art of Fixing Your Windows Stylus Device</u></a></li>
<li><a href="https://win11.techidaily.com/max-1-antivirus-for-windows-optimize-system-performance/"><u>Max 1 Antivirus for WIndows: Optimize System Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-failed-0x0000011b-in-windows/"><u>Overcoming Operation Failed 0X0000011B in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-inactive-session-limit/"><u>Personalizing Windows Inactive Session Limit</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/proactive-steps-for-gpu-faults-no-pc-lockdown/"><u>Proactive Steps for GPU Faults, No PC Lockdown</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-xiaomi-redmi-note-13-5g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Xiaomi Redmi Note 13 5G Black and White | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-original-look-for-discoloured-extend-volume/"><u>Reclaim Original Look for Discoloured Extend Volume</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-gaming-with-dxvk-the-windows-perspective/"><u>Revolutionizing Gaming with DXVK - The Windows Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unhandled-exception-strategies-to-mitigate-on-pc/"><u>Simplifying Unhandled Exception: Strategies to Mitigate on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-asus-rog-phone-8-pro-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Asus ROG Phone 8 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-retrieve-faded-bios-messages/"><u>Tips to Retrieve Faded BIOS Messages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-10-must-watch-free-films-on-youtube-for-july-2024/"><u>Top 10 Must-Watch Free Films on YouTube for July 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-gaming-potential-android-on-win-11-through-google-services-access/"><u>Unlock Gaming Potential: Android on Win 11 Through Google Services Access</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-clipchamp-solve-windows-11-install-problems/"><u>Unlocking ClipChamp: Solve Windows 11 Install Problems</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-covert-query-beam-of-windows-11/"><u>Unveiling the Covert Query Beam of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-windows-experience-adding-contextual-items/"><u>Upgrading Your Windows Experience: Adding Contextual Items</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
</ul></div>
