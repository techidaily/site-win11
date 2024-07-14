---
title: Tackling Disrupted Photo Packaging in Windows 10 & 11
date: 2024-07-13T10:32:34.584Z
updated: 2024-07-14T10:32:34.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Disrupted Photo Packaging in Windows 10 & 11
excerpt: This Article Describes Tackling Disrupted Photo Packaging in Windows 10 & 11
keywords: PhotoPackagingW10,W10DisruptionSolutions,W11PackagingChallenges,WinPackagingIssues,PackagingTechWindows10,Windows10Photopack,PhotoPackWin11
thumbnail: https://thmb.techidaily.com/c2347da6ec78a1b069be335abb7dc18b2b1262d176e6b4d47161337afbbb6cd1.jpeg
---

## Tackling Disrupted Photo Packaging in Windows 10 & 11

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://printer-issues.techidaily.com/hp-print-driver-missing-in-windows-1110/"><u>HP Print Driver Missing in Windows 11/10</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-samsung-galaxy-s21-fe-5g-2023-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Samsung Galaxy S21 FE 5G (2023) phone? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-how-to-go-live-with-recorded-material-on-the-worlds-largest-social-network-for-2024/"><u>[New] How to Go Live with Recorded Material on the World's Largest Social Network for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-vivo-v30-pro-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Vivo V30 Pro Data? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-zero-to-hero-in-the-youtube-world-starting-your-channel-and-earning-money/"><u>[New] 2024 Approved  From Zero to Hero in the Youtube World  Starting Your Channel & Earning Money</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-11-i-do-get-answers-here-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 11 i Do? Get Answers here</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-quick-guide-how-to-download-windows-movie-maker-6/"><u>[Updated] Quick Guide  How to Download Windows Movie Maker 6</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-quick-tips-for-creating-and-editing-snapchat-duos/"><u>[Updated] 2024 Approved  Quick Tips for Creating and Editing Snapchat Duos</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-hidden-login-screens-in-windows-11/"><u>Eradicating Hidden Login Screens in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clipit-woes-uncover-top-fixes-for-swift-recovery/"><u>ClipIt Woes? Uncover Top Fixes for Swift Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-dual-display-the-netflix-floating-window-guide/"><u>Navigating Dual Display  The Netflix Floating Window Guide</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-filing-mastery-key-principles-max-156/"><u>Windows Filing Mastery: Key Principles (Max 156)</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-the-ultimate-guide-to-video-brightening-top-apps-for-android-and-ios/"><u>New In 2024, The Ultimate Guide to Video Brightening Top Apps for Android and iOS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-prime-recording-option-elevate-your-youtube-channel/"><u>[Updated] Prime Recording Option  Elevate Your YouTube Channel</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-a-comprehensive-look-at-editing-and-uploading-virtual-reality-videos-to-youtube-for-2024/"><u>[New] A Comprehensive Look at Editing and Uploading Virtual Reality Videos to YouTube for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-extending-your-content-a-detailed-youtube-video-upload-manual/"><u>2024 Approved  Extending Your Content  A Detailed YouTube Video Upload Manual</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-tecno-spark-10-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Tecno Spark 10 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-mastering-sound-intervals-techniques-for-manipulating-audio-timestamps-in-final-cut-pro-x/"><u>New In 2024, Mastering Sound Intervals Techniques for Manipulating Audio Timestamps in Final Cut Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttered-windows-desktop-at-a-glance/"><u>Uncluttered Windows Desktop at a Glance</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-insight-into-the-finest-iphone-tools-for-image-watermarks/"><u>2024 Approved  Insight Into the Finest iPhone Tools for Image Watermarks</u></a></li>
<li><a href="https://driver-install.techidaily.com/corrective-actions-for-hp-printer-in-10-os/"><u>Corrective Actions for HP Printer in 10 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-java-vm-error-on-windows/"><u>Unraveling the Mystery of Java VM Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-redesigned-windows-11-widget-pickers/"><u>Enabling Redesigned Windows 11 Widget Pickers</u></a></li>
<li><a href="https://win11.techidaily.com/visual-clarity-in-note-taking-with-obsidian-design/"><u>Visual Clarity in Note-Taking with Obsidian Design</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-zero-empty-directories-issue-in-windows-11-and-11/"><u>Tackling the Zero-Empty Directories Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/cease-auditory-gain-on-windows-operating-system/"><u>Cease Auditory Gain on Windows Operating System</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-tech-enthusiasts-guide-to-ios-screen-record-2023/"><u>[Updated] Tech Enthusiast's Guide to iOS Screen Record 2023</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-oppo-a2-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-server-errors-a-windows-guide-to-apex-success-(156-chars/"><u>Eliminating No-Server Errors: A Windows Guide to Apex Success (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/monetizing-popularity-pay-per-million-views/"><u>Monetizing Popularity  Pay Per Million Views</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/dancefloor-dynamics-top-rated-dj-video-selections/"><u>Dancefloor Dynamics  Top-Rated DJ Video Selections</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-photo-and-video-edits-made-easy-select-the-best-8-apps-for-android-ios/"><u>[New] Photo & Video Edits Made Easy  Select the Best 8 Apps for Android, iOS</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pathways-to-windows-performance-details/"><u>Efficient Pathways to Windows Performance Details</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-why-windows-fails-to-execute-exe-files/"><u>Decoding Why Windows Fails to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-parsing-hiccup-code-0xc00ce556/"><u>Correcting Windows Parsing Hiccup Code 0xC00CE556</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-log-your-favorites-6-proven-methods-for-webcast-capture-for-2024/"><u>How to Log Your Favorites  6 Proven Methods for Webcast Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-app-install-failures-on-microsoft-store/"><u>Correcting App Install Failures on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-window-task-completion-via-key-combinations/"><u>Speedy Window Task Completion via Key Combinations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-power-play-top-10-apps-to-increase-followers-and-posts-for-2024/"><u>[Updated] Instagram Power Play  Top 10 Apps to Increase Followers & Posts for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-s23-fe-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy S23 FE to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-a-strategy-to-resolve-locked-windows-update/"><u>Unveiling a Strategy to Resolve Locked Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-beast-boosting-fps-in-cs-go/"><u>Unleash the Beast - Boosting FPS in CS Go</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-operation-failed-error-code-0x0000011b/"><u>Tackling Operation Failed Error: Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-out-of-place-window-elements/"><u>Correcting Out-of-Place Window Elements</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-collage-artistry-with-precision/"><u>[Updated] Mastering Collage Artistry with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-11-installation-with-these-essential-tweaks/"><u>Streamline Your Windows 11 Installation with These Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/the-unmatched-features-in-windows-10-why-its-superior-to-win11/"><u>The Unmatched Features in Windows 10: Why It's Superior to Win11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-realme-c67-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Realme C67 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-usage-options-on-windows-11-devices-and-systems/"><u>Streamlining Usage Options on Windows 11 Devices and Systems</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-windows-error-0xc1900101/"><u>Strategies for Correcting Windows Error 0xC1900101</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-10-steadicam-choices-for-drone-cinematography-pros/"><u>In 2024, Top 10 Steadicam Choices for Drone Cinematography Pros</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-digital-dynamics-mastering-youtube-video-distribution-on-facebook/"><u>[Updated] Digital Dynamics  Mastering YouTube Video Distribution on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-audio-access-failures-in-audacity/"><u>Troubleshooting Audio Access Failures in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-role-and-usage-of-windows-component-services/"><u>Deciphering the Role & Usage of Windows Component Services</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stop-system-spontaneities-fixing-windows-11-restarts/"><u>Stop System Spontaneities: Fixing WIndows 11 Restarts</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-quick-guide-accessorizing-windows-with-a-clownfish-speech-modifier/"><u>[New] Quick Guide  Accessorizing Windows with a Clownfish Speech Modifier</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-skip-recurring-enter-credentials-messages/"><u>Techniques to Skip Recurring 'Enter Credentials' Messages</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-realme-c53-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Realme C53? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-infinix-smart-8-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Infinix Smart 8 Phone When You Forget the Password</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-complete-tutorial-on-using-autotune-with-audacity-users/"><u>In 2024, The Complete Tutorial on Using Autotune with Audacity Users</u></a></li>
</ul></div>
