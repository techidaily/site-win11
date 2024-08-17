---
title: "Regular Update: Reactivating Microsoft Store on Windows PCs"
date: 2024-08-16T00:48:34.479Z
updated: 2024-08-17T00:48:34.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regular Update: Reactivating Microsoft Store on Windows PCs"
excerpt: "This Article Describes Regular Update: Reactivating Microsoft Store on Windows PCs"
keywords: Reactivate MS Store,Re-Enable MS Store,MS Store Revival,Microsoft Store Update,Restore MS Store,Accessing MS Store,Windows Store Activation
thumbnail: https://thmb.techidaily.com/9c252b23b1e3ad8357c15bea477480a8c23a36edb5cd9b4be147d76d8870fe38.jpg
---

## Regular Update: Reactivating Microsoft Store on Windows PCs

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://instagram-clips.techidaily.com/new-journey-beyond-the-frantic-crafting-epic-slow-motion-content-for-instragram/"><u>[New] Journey Beyond the Frantic  Crafting Epic Slow Motion Content for Instragram</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-leading-cloud-services-for-android/"><u>[New] Leading Cloud Services for Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-video-conferencing-zooming-towards-youtube-streaming-excellence/"><u>[New] Mastering Video Conferencing  Zooming Towards YouTube Streaming Excellence</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-10-cost-free-multi-os-video-player-releases/"><u>[Updated] 2024 Approved  10 Cost-Free, Multi-OS Video Player Releases</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-fix-chrome-non-playing-androidios-videos-for-2024/"><u>[Updated] Fix Chrome  Non-Playing Android/iOS Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-10plus-free-tiktok-video-editing-appswebsite-on-mac/"><u>[Updated] In 2024, 10+ Free TikTok Video Editing Apps/Website on Mac</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-effortlessly-engage-with-an-array-of-available-youtube-content/"><u>[Updated] In 2024, Effortlessly Engage with an Array of Available YouTube Content</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-behind-the-scenes-unpacking-instagram-stories/"><u>2024 Approved  Behind the Scenes  Unpacking Instagram Stories</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-cross-media-iptv-synchronization/"><u>2024 Approved  Cross-Media IPTV Synchronization</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-witness-the-blend-the-top-ten-funny-and-deep-ig-meme-accounts/"><u>2024 Approved  Witness the Blend  The Top Ten Funny & Deep IG Meme Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-pinpointing-hardware-identification-in-windows/"><u>Advanced Strategies for Pinpointing Hardware Identification in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-x70-file-and-directory-recovery-on-windows-1011/"><u>Bypassing Error X70: File and Directory Recovery on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-edges-load-times-and-resource-use/"><u>Decreasing Edge's Load Times and Resource Use</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-audio-amps-for-youtubers-with-limited-dough/"><u>Econo Audio Amps for Youtubers with Limited Dough</u></a></li>
<li><a href="https://win11.techidaily.com/enliven-windows-11-desktop-a-step-by-step-guide-to-animated-walls/"><u>Enliven Windows 11 Desktop: A Step-by-Step Guide to Animated Walls</u></a></li>
<li><a href="https://win-forum.techidaily.com/error-resolution-strategies-starting-windows-11-successfully-on-any-pc/"><u>Error Resolution Strategies: Starting Windows 11 Successfully on Any PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-win11-dns-client-service-adjustment/"><u>Essential Tips for Win11 DNS Client Service Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-lens-6-simple-steps-for-picture-spin-on-windows-11/"><u>Flip Your Lens: 6 Simple Steps for Picture Spin on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/gently-lowering-highs-a-guide-to-windowed-serenity/"><u>Gently Lowering Highs: A Guide to Windowed Serenity</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-tecno-phantom-v-fold-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Tecno Phantom V Fold 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-tecno-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Tecno</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-xr-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone XR Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-elevate-your-youtube-videos-popularity-through-persistent-cc-licensing-for-2024/"><u>How to Elevate Your YouTube Video's Popularity Through Persistent CC Licensing for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ideal-choices-apps-that-convert-photos-to-films/"><u>Ideal Choices  Apps That Convert Photos to Films</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-oneplus-open-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring OnePlus Open PC | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-capturecanvas-hd-screen-toolkit/"><u>In 2024, CaptureCanvas HD Screen Toolkit</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-lava-blaze-2-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Lava Blaze 2 Phone? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-nubia-z50s-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Nubia Z50S Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-the-wealth-wave-of-the-philanthropic-maverick-mr-beast/"><u>In 2024, The Wealth Wave of the Philanthropic Maverick, Mr. Beast</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-bsod-data-for-system-debugging/"><u>Leveraging BSOD Data for System Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-grans-old-computer-senior-friendly-and-simple/"><u>Make Your Gran’s Old Computer Senior-Friendly & Simple</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-characters-on-windows-11-screen/"><u>Navigating the Characters on Windows 11 Screen</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-an-ultimate-guide-of-best-narrator-voice-generators-for-2024/"><u>New An Ultimate Guide of Best Narrator Voice Generators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-your-guide-to-color-perfection-on-windows/"><u>Overcoming Obstacles: Your Guide to Color Perfection on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systemsettings-crashes-in-windows-11/"><u>Overcoming SystemSettings Crashes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-system-sounds-in-windows-11-by-activating-mixer-feature/"><u>Perfect System Sounds in Windows 11 by Activating Mixer Feature</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-default-heat-reduction-rules-in-winos/"><u>Reclaiming Default Heat Reduction Rules in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-copy-pasting-malfunctions-in-windows-11/"><u>Rectifying Copy-Pasting Malfunctions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unseen-second-monitor-problems/"><u>Solving Unseen Second Monitor Problems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-huawei-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Huawei? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-notes-obsidian-canvas-approach/"><u>Streamline Your Notes: Obsidian Canvas Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-to-resolve-battlenet-login-on-pcs/"><u>Troubleshooting Steps to Resolve Battle.net Login on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-access-navigating-localized-onedrive-files/"><u>Unplugged Access: Navigating Localized OneDrive Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>Unraveling Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-expect-from-microsofts-win11-feb-release/"><u>What to Expect From Microsoft's Win11 Feb Release</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
</ul></div>
