---
title: Addressing Windows Error 0X80780119 on System Image
date: 2024-08-16T00:03:32.702Z
updated: 2024-08-17T00:03:32.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Error 0X80780119 on System Image
excerpt: This Article Describes Addressing Windows Error 0X80780119 on System Image
keywords: WinError0X8078,SystemImageFail,OSImagingError,X8078ErrorWin,ErrorCode0X8078,WindowsImageFault,OSImage0X8078
thumbnail: https://thmb.techidaily.com/64bcba811dca59ee452fde50283dc6af9516c46b5a87dc01f6fa89f4e4093f9a.jpg
---

## Addressing Windows Error 0X80780119 on System Image

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend [using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the following dialog, head over to the **System Protection** tab.
5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Once done, press the **Win** \+ **R** keys together to open Run.
6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-making-a-splash-with-youtube-ad-banners-and-thumbnails/"><u>[New] 2024 Approved  Making a Splash with YouTube Ad Banners & Thumbnails</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-professional-level-youtube-editing-techniques-you-need-to-know/"><u>[New] In 2024, Professional-Level Youtube Editing Techniques You Need To Know</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-iphone-and-ipad-screen-recording-top-methods-of-2023/"><u>[New] IPhone & iPad Screen Recording  Top Methods of 2023</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-spectrum-of-autonomous-flight-machines/"><u>[New] Spectrum of Autonomous Flight Machines</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-youtubes-intricate-view-count-mechanics/"><u>[Updated] In 2024, Decoding YouTube's Intricate View Count Mechanics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-embracing-constructive-feedback-ignoring-the-rest/"><u>[Updated] In 2024, Embracing Constructive Feedback, Ignoring the Rest</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-secrets-of-snapsharing-creating-invisible-chronicles-for-2024/"><u>[Updated] Secrets of Snapsharing  Creating Invisible Chronicles for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unveiling-social-screens-share-your-monitor-on-fb-live/"><u>[Updated] Unveiling Social Screens  Share Your Monitor on FB Live</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-videography-6-tips-for-making-macro-video/"><u>[Updated] Videography  6 Tips for Making Macro Video</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-social-streamers-guide-broadcast-from-phone-subscriber-free-edition/"><u>2024 Approved  Social Streamer's Guide  Broadcast From Phone, Subscriber-Free Edition</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unified-tint-harmonizer/"><u>2024 Approved  Unified Tint Harmonizer</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-nubia-z50-ultra-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Nubia Z50 Ultra? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-windows-voice-recording/"><u>A Step-By-Step Guide to Windows Voice Recording</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-deactivated-speech-recognition-microsofts-windows-11-guide/"><u>Addressing Deactivated Speech Recognition: Microsoft's Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-overestimated-cpu-usage-in-windows-performance-tool/"><u>Addressing Overestimated CPU Usage in Windows Performance Tool</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-play-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-driver-verification-on-windows-enforcement-off-unsigned-loaded/"><u>Bypass Driver Verification on Windows: Enforcement Off, Unsigned Loaded</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-verification-loading-unsigned-drivers-in-windows-2000xp/"><u>Bypassing Verification: Loading Unsigned Drivers in Windows 2000/XP</u></a></li>
<li><a href="https://win11.techidaily.com/check-it-out-quick-fixes-for-your-webcam-and-mic-test/"><u>Check It Out: Quick Fixes for Your Webcam & Mic Test</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-secrets-5-entertaining-hacks/"><u>Command Prompt Secrets: 5 Entertaining Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-walls-for-windows-11-setting-lively-desktop-backdrops/"><u>Dynamic Walls for Windows 11: Setting Lively Desktop Backdrops</u></a></li>
<li><a href="https://win-dash.techidaily.com/effective-solutions-for-lg-usb-drivers-malfunction-on-multiple-windows-versions/"><u>Effective Solutions for LG USB Drivers Malfunction on Multiple Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-for-battery-life-extension-on-notebooks/"><u>Effective Techniques for Battery Life Extension on Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nvidias-opengl-failure-no-3-in-windows-11/"><u>Eliminating NVIDIA's OpenGL Failure No. 3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-style-and-efficiency-of-the-swagtron-swagger-electric-scooter/"><u>Evaluating the Style and Efficiency of the Swagtron Swagger Electric Scooter</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-6-windows-usage-analysis-programs/"><u>Explore the Finest 6 Windows Usage Analysis Programs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/exploring-no-cost-cam-screens-reviews-and-high-alternatives/"><u>Exploring No-Cost Cam Screens  Reviews & High Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-abrupt-device-removal-errors-dxgi/"><u>Fixing Abrupt Device Removal Errors (DXGI)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unverified-session-error-by-steams-vac/"><u>Fixing Unverified Session Error by Steam's VAC</u></a></li>
<li><a href="https://win11.techidaily.com/four-practical-alternatives-to-bitlocker-in-winoss/"><u>Four Practical Alternatives to BitLocker in WinOSs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/full-guide-to-apple-iphone-11-icloud-bypass-by-drfone-ios/"><u>Full guide to Apple iPhone 11 iCloud Bypass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-se-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone SE? Complete Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-infinix-smart-8-plus-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Infinix Smart 8 Plus</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-channel-name-magic-ideas-for-impactful-titles/"><u>In 2024, Channel Name Magic  Ideas for Impactful Titles</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-infinix-smart-8-pro-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/innovative-methods-blurring-the-line-between-work-and-distractions/"><u>Innovative Methods  Blurring the Line Between Work and Distractions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/iphone-photo-perfection-implement-these-10-composition-tenets-for-2024/"><u>IPhone Photo Perfection  Implement These 10 Composition Tenets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-escalate-volumes-on-screen-sounds-for-enhanced-perception-for-2024/"><u>New Escalate Volumes on Screen Sounds for Enhanced Perception for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-innovations-and-standouts-10-premier-podcast-hosting-providers/"><u>New Innovations and Standouts 10 Premier Podcast Hosting Providers</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-visibility-to-system-startups-on-win-os/"><u>Restoring Visibility to System Startups on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-discords-inadequate-search-mechanism/"><u>Reviving Windows Discord's Inadequate Search Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-editing-with-these-win11-videoscripts/"><u>Streamline Editing with These Win11 Videoscripts</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-quick-and-accurate-screenshot-of-uac-prompts/"><u>Techniques for Quick and Accurate Screenshot of UAC Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-legacy-library-exploring-free-visual-echoes-for-2024/"><u>The Legacy Library  Exploring Free Visual Echoes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-puzzle-of-non-opening-apps-in-w11/"><u>Unlocking the Puzzle of Non-Opening Apps in W11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-feature-flashback-the-surviving-anniversary-of-7-elements/"><u>Windows 11 Feature Flashback: The Surviving Anniversary of 7 Elements</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-workstation-access-the-hidden-side-of-rdp-in-win-11/"><u>Zero-Entry Workstation Access: The Hidden Side of RDP in Win 11</u></a></li>
</ul></div>
