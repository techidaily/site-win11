---
title: Remedying System Call Failure in Win10/11 Systems
date: 2024-07-13T10:23:59.217Z
updated: 2024-07-14T10:23:59.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying System Call Failure in Win10/11 Systems
excerpt: This Article Describes Remedying System Call Failure in Win10/11 Systems
keywords: Fix Windows Call Issues,Solve OS System Errors,Remedy Windows Signal Failures,Resolve Kernel Calls Errors,Rectify Win10/11 Signals,Correct System Call Faults,Address Win10/11 Call Problems
thumbnail: https://thmb.techidaily.com/b55c24263d5a9a2d0075e95ed2cba33cc134d0a45b0aad772e33e1d818e77a97.jpg
---

## Remedying System Call Failure in Win10/11 Systems

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-tips-to-uncover-powerful-handclap-auditory-illusions/"><u>Updated In 2024, Tips to Uncover Powerful Handclap Auditory Illusions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pitch-perfect-crafting-characters-spoken-language/"><u>2024 Approved  Pitch Perfect  Crafting Characters' Spoken Language</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-effortlessly-share-window-movie-creations-with-vimeo/"><u>[Updated] Effortlessly Share Window Movie Creations with Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-back-into-windows-service-tool-with-these-7-methods/"><u>Breathing Life Back Into Windows Service Tool With These 7 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-previewable-file-trouble-on-outlook-365-pc/"><u>Overcoming Non-Previewable File Trouble on Outlook 365 PC</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-delay-in-windows-11-keys-7-proven-methods/"><u>Reduce Delay in Windows 11 Keys: 7 Proven Methods</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unleash-your-creativity-best-free-video-editors-for-32-bit-windows-for-2024/"><u>New Unleash Your Creativity Best Free Video Editors for 32-Bit Windows for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-unsplash-your-brand-free-images-for-commercial-purposes/"><u>Updated In 2024, Unsplash Your Brand Free Images for Commercial Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-browser-scenarios-in-new-oss/"><u>Overcoming No-Browser Scenarios in New OSs</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-startup-program-management-for-a-flawless-windows-11-start/"><u>Mastering Startup Program Management for a Flawless Windows 11 Start</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-to-removing-windows-extract-error-1152/"><u>Unlocking Secrets to Removing Windows Extract Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-the-default-windows-clock-configuration/"><u>Protecting the Default Windows Clock Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-with-ease-open-mouse-prop-in-win11/"><u>Navigating with Ease: Open Mouse Prop in Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-list-of-10-best-fitness-focused-yoga-channels/"><u>2024 Approved  The Ultimate List of 10 Best Fitness-Focused Yoga Channels</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-pro-tip-8-key-sites-to-harvest-free-eco-friendly-filming-backdrops/"><u>[New] Pro Tip! 8 Key Sites to Harvest FREE Eco-Friendly Filming Backdrops</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dissolving-details-techniques-to-anonymize-youtube-media-for-2024/"><u>[Updated] Dissolving Details  Techniques to Anonymize YouTube Media for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/amplify-impact-through-effective-video-marketing-on-youtubes-top-5-moves-for-2024/"><u>Amplify Impact Through Effective Video Marketing on YouTube's Top 5 Moves for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-mastering-audio-with-sound-forge-an-assessment-review-for-2024/"><u>New Mastering Audio with Sound Forge An Assessment Review for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-master-the-art-of-console-game-recording-with-computer-assistance/"><u>[Updated] In 2024, Master the Art of Console Game Recording with Computer Assistance</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-familiarity-migrating-custom-powertoys-on-a-new-device/"><u>Bringing Familiarity: Migrating Custom PowerToys on a New Device</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-how-to-get-free-picture-frame-videos/"><u>[Updated] In 2024, How to Get Free Picture Frame Videos</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-windows-filter-keys/"><u>Navigating the Landscape of Windows' Filter Keys</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-capturing-creativity-the-ultimate-guide-to-roblox-videos-on-a-mac/"><u>In 2024, Capturing Creativity  The Ultimate Guide to Roblox Videos on a Mac</u></a></li>
<li><a href="https://win11.techidaily.com/1719350994094-winshift-stuck-heres-how-to-tackle-it/"><u>WinShift Stuck? Here's How to Tackle It</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/regain-access-to-microsoft-store-features-on-pcs/"><u>Regain Access to Microsoft Store Features on PCs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-quality-action-recorders-12-enhanced-with-gps-navigation/"><u>2024 Approved  High-Quality Action Recorders 12, Enhanced with GPS Navigation</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connectivity-windows-plus-playstation-3-pad/"><u>Effortless Connectivity: Windows + PlayStation 3 Pad</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-ultimate-playbook-navigating-tools-for-vimeo-content-grabs-for-2024/"><u>[New] The Ultimate Playbook  Navigating Tools for Vimeo Content Grabs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tactics-for-using-windows-explorer-not-ls/"><u>Powerful Tactics for Using Windows Explorer, Not LS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-spotlight-wallpaper-icon-from-win11/"><u>How to Clear Spotlight Wallpaper Icon From Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-earn-lost-achievement-points-on-steam/"><u>How to Re-Earn Lost Achievement Points on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/from-zero-to-zenith-master-desktop-design-in-wins/"><u>From Zero To Zenith: Master Desktop Design in Wins</u></a></li>
<li><a href="https://win11.techidaily.com/learn-9-methods-to-access-and-tweak-windows-sound-settings/"><u>Learn 9 Methods to Access and Tweak Windows Sound Settings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-inexpensive-pcs-optimized-video-settings-guide-for-2024/"><u>[New] Inexpensive PCs  Optimized Video Settings Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-access-to-computers-heartbeat-open-mouse-prop-on-win11/"><u>Effortless Access to Computer's Heartbeat: Open Mouse Prop on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-winapp-and-browser-dynamics/"><u>Controlling WinApp and Browser Dynamics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-tips-on-choosing-the-ideal-live-broadcast-service/"><u>Expert Tips on Choosing the Ideal Live Broadcast Service</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-infinix-hot-40-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Infinix Hot 40 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unidentified-component-in-windows-lsass/"><u>Quick Fixes for Unidentified Component in Windows Lsass</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-maze-quickly-entering-windows-support-space/"><u>Avoiding the Maze: Quickly Entering Windows' Support Space</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-revolutionize-your-sound-10-best-online-waveform-generators/"><u>New 2024 Approved Revolutionize Your Sound 10 Best Online Waveform Generators</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Motorola Razr 40 Ultra? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-creating-compelling-content-with-personalized-video-setups/"><u>2024 Approved  Creating Compelling Content with Personalized Video Setups</u></a></li>
<li><a href="https://win11.techidaily.com/winexe-enhancement-convert-batch-to-powerful-formats/"><u>WinEXE Enhancement: Convert Batch to Powerful Formats</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-crop-a-video-in-davinci-resolve-step-by-step/"><u>In 2024, How to Crop a Video in Davinci Resolve Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/remedial-actions-for-incorrect-app-configuration/"><u>Remedial Actions for Incorrect App Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-windows-file-explorer-efficiently/"><u>Reactivate Windows File Explorer Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-top-windows-11-fps-monitors-and-counter-tools/"><u>Unveiling Top Windows 11 FPS Monitors & Counter Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/windows-10s-premier-choice-of-video-grabber-software/"><u>Windows 10'S Premier Choice of Video Grabber Software</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-getting-past-windows-update-hitches/"><u>Quick Fixes: Getting Past Windows Update Hitches</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-top-10plus-instagram-content-downloaders-reviewed/"><u>In 2024, Top 10+ Instagram Content Downloaders Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-closing-several-programs-at-once-in-windows/"><u>Efficient Methods: Closing Several Programs at Once in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/digital-artistry-perfecting-subject-isolation-techniques/"><u>Digital Artistry: Perfecting Subject Isolation Techniques</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-vivo-t2-pro-5g-frp-by-drfone-android/"><u>Full Guide to Bypass Vivo T2 Pro 5G FRP</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-apple-iphone-6s-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On Apple iPhone 6s</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-tecno-spark-10c-by-drfone-android/"><u>Full Guide to Unlock Your Tecno Spark 10C</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-and-solving-isdonedll-failures-in-w10w11-oses/"><u>Unwrapping and Solving ISDone.dll Failures in W10/W11 OSes</u></a></li>
<li><a href="https://article-helps.techidaily.com/digital-decor-best-platforms-and-software-for-photo-frameups-for-2024/"><u>Digital Decor  Best Platforms & Software for Photo Frameups for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-navigating-sharex-critical-thoughts-and-alternatives/"><u>[Updated] In 2024, Navigating ShareX  Critical Thoughts & Alternatives</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-windows-10-wizards-handbook-achieving-clear-audio-recordings/"><u>2024 Approved The Windows 10 Wizards Handbook Achieving Clear Audio Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/halting-unintentional-launches-of-microsofts-storeapp/"><u>Halting Unintentional Launches of Microsoft's StoreApp</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-cpuram-drain-from-consuming-video-content/"><u>Reducing CPU/RAM Drain From Consuming Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-monochrome-troubles-with-store-app/"><u>Overcoming Monochrome Troubles with Store App</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-to-security-focused-dialogue-shortcuts/"><u>Windows 11: Guide to Security-Focused Dialogue Shortcuts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/free-studio-hd-screen-grab-audit/"><u>Free Studio HD Screen Grab Audit</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-tips-for-effective-screen-broadcasts-on-fb-live/"><u>[New] Tips for Effective Screen Broadcasts on FB Live</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-effortlessly-blur-images-captured-by-iphones-4-methods-for-2024/"><u>How to Effortlessly Blur Images Captured by iPhones (4 Methods) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-admin-command-center-on-windows/"><u>Navigating to Admin Command Center on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-tips-setting-up-outlook-preview-app-on-winoss/"><u>Efficient Tips: Setting Up Outlook Preview App on WinOSs</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-make-a-lasting-impression-top-movie-intro-design-software-for-2024/"><u>New Make a Lasting Impression Top Movie Intro Design Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/3-methods-to-shorten-windows-11-boot-time-effectively/"><u>3 Methods to Shorten Windows 11 Boot Time Effectively</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximizing-engagement-with-proper-yt-thumbnail-size/"><u>Maximizing Engagement with Proper YT Thumbnail Size</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-11-ranked-audio-recorders-of-the-year/"><u>[Updated] 11 Ranked Audio Recorders of the Year</u></a></li>
</ul></div>
