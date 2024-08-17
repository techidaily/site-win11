---
title: Eliminating Package Registration Problems on Windows Devices
date: 2024-08-16T00:41:27.073Z
updated: 2024-08-17T00:41:27.073Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Package Registration Problems on Windows Devices
excerpt: This Article Describes Eliminating Package Registration Problems on Windows Devices
keywords: Fixing Packages Errors (Windows),Resolve WinPack Issues,Simplify Device Registration,Ease Windows Package Installation,Eliminate Devices' Logging Problems,Streamline Windows Update Process,Unhindered Packages on PCs
thumbnail: https://thmb.techidaily.com/d6473782f31868e794fc3ab8460fc67b139be82f000417effd74e9124ff9dff3.jpg
---

## Eliminating Package Registration Problems on Windows Devices

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/024-approved-tools-and-methods-how-to-resize-youtube-thumbnail/"><u>[New] 2024 Approved  [Tools & Methods] How To Resize YouTube Thumbnail</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-brain-busting-the-premier-room-challenge-list/"><u>[New] 2024 Approved  Brain-Busting  The Premier Room Challenge List</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-foster-community-with-unique-insta-story-questions-for-2024/"><u>[New] Foster Community with Unique Insta Story Questions for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-optimal-mac-animation-storer/"><u>[New] In 2024, Optimal Mac Animation Storer</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-boring-to-breathtaking-the-transformation-of-channel-titles/"><u>[Updated] From Boring to Breathtaking  The Transformation of Channel Titles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-hack-the-art-of-instagram-reels-creation/"><u>[Updated] Hack the Art of Instagram Reels Creation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-no-expense-yes-watch-one-frame-at-a-time-on-youtube/"><u>[Updated] No Expense? Yes! Watch One Frame at a Time on YouTube</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlining-video-editing-convert-avis-to-gifs-on-mac-and-pc-with-filmora/"><u>[Updated] Streamlining Video Editing  Convert AVIs to GIFs on Mac and PC with Filmora</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-windows-desktop-snappers-guide/"><u>[Updated] Windows Desktop Snappers Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-honor-magic-5-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-discover-top-affordable-video-editors-of-2023-today/"><u>2024 Approved  Discover Top Affordable Video Editors of 2023 Today</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-sharing-lifes-moments-with-your-online-audience/"><u>2024 Approved  Sharing Life's Moments with Your Online Audience</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-smart-solutions-for-gathering-visual-assets/"><u>2024 Approved  Smart Solutions for Gathering Visual Assets</u></a></li>
<li><a href="https://win11.techidaily.com/5-ingenious-cmd-puzzles-to-perplex-and-pleasure/"><u>5 Ingenious CMD Puzzles to Perplex and Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-steps-for-windows-hello-fingerprint-woes/"><u>9 Essential Steps for Windows Hello Fingerprint Woes</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-change-themes-on-windows-11/"><u>9 Ways to Change Themes On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-printer-administration-interface/"><u>A Comprehensive Look at Windows Printer Administration Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-and-upgrade-top-5-essentials-to-enhance-win-pcs/"><u>Accelerate and Upgrade: Top 5 Essentials to Enhance Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-efficiency-introducing-flow-launcher-methodology/"><u>Accelerate Workflow Efficiency: Introducing Flow Launcher Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-invisible-mode-quick-turnoff-of-windows-pcs/"><u>Activate Invisible Mode: Quick Turnoff of Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connectivity-issues-fix-iphone-images-not-uploading-in-windows/"><u>Addressing Connectivity Issues: Fix iPhone Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-issues-with-windows-alt-code-operations-53-characters/"><u>Addressing Issues with Windows Alt Code Operations (53 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-dll-issue-in-windows-810/"><u>Addressing Missing DLL Issue in Windows 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-security-strategies-in-powertoys/"><u>Advanced File Security Strategies in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-tray-graphics-windows-resource-indicators-displayed/"><u>Amplify Tray Graphics: Windows Resource Indicators Displayed</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-black-screen-in-windows-quick-fix-guide/"><u>Banish Black Screen in Windows - Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-novelties-the-next-gen-of-windows-11/"><u>Beyond Novelties: The Next Gen of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-audio-5-ways-for-above-100-output-on-pcs/"><u>Boosting Audio: 5 Ways for Above-100%% Output on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-explore-4-innovative-microsoft-paint-additions/"><u>Breaking Boundaries: Explore 4 Innovative Microsoft Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-the-mystery-of-where-are-my-youtube-comments-in-2024/"><u>Decoding the Mystery of Where Are My YouTube Comments, In 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-connectivity-asus-webcam-on-windows-10-revamped/"><u>Enhanced Connectivity: ASUS Webcam on Windows 10 Revamped</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-scripting-instant-stopwatch-integration-in-obs-for-2024/"><u>Essential Scripting  Instant Stopwatch Integration in OBS for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-remove-apple-iphone-11-pro-max-sim-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 11 Pro Max SIM Lock?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-a58-4g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo A58 4G to New Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-legal-pathways-for-youtube-to-mp4-file-downloading/"><u>In 2024, Legal Pathways for YouTube to MP4 File Downloading</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721100936688-missing-cpu-coprocessor-driver-in-windows-10-heres-how-to-fix-it/"><u>Missing CPU Coprocessor Driver in Windows 10? Here's How to Fix It!</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/optimizing-your-imovie-content-for-vimeo-display-for-2024/"><u>Optimizing Your iMovie Content for Vimeo Display for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-purchase-how-to-evade-monitor-shopping-fails/"><u>Perfect Purchase: How to Evade Monitor Shopping Fails</u></a></li>
<li><a href="https://change-location.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Vivo Y27 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719254765561-solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-social-media-elite-writes-back-six-essential-tips-to-elevate-your-instagram-presence/"><u>The Social Media Elite' Writes Back  Six Essential Tips to Elevate Your Instagram Presence</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-13t-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi 13T Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
</ul></div>
