---
title: Expert Guide to Fixing Failed Windows MMC Creations
date: 2024-08-23T06:10:30.913Z
updated: 2024-08-24T06:10:30.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Guide to Fixing Failed Windows MMC Creations
excerpt: This Article Describes Expert Guide to Fixing Failed Windows MMC Creations
keywords: MMC Repair Tips,WinMM Solutions,Fixing MMC Issues,Windows MMCTools,MMC Recovery Guide,Faulty MMC Fixes,Restoring MMC Creations
thumbnail: https://thmb.techidaily.com/ec5c93589cbbf4437a85d01509aad074c0824b7a47a862a6e3798990cfe51fb1.png
---

## Expert Guide to Fixing Failed Windows MMC Creations

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/pixelpreserve-a-comprehensive-screen-record-review/"><u>'PixelPreserve'  A Comprehensive Screen Record Review</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-alter-default-store-place-for-mac-images/"><u>[New] 2024 Approved  Alter Default Store Place for Mac Images</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-cutting-edge-approaches-to-in-game-auditory-logging/"><u>[New] 2024 Approved  Cutting-Edge Approaches to In-Game Auditory Logging</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-electoral-enthusiasm-top-5-political-game-experiences/"><u>[New] 2024 Approved  Electoral Enthusiasm  Top 5 Political Game Experiences</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-from-past-to-present-a-detailed-tiktok-username-overhaul-guide-for-2024/"><u>[New] From Past to Present  A Detailed TikTok Username Overhaul Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-instagrams-video-upload-constraints-a-detailed-guide-for-2024/"><u>[New] Mastering Instagram's Video Upload Constraints  A Detailed Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-100plus-cool-gaming-channel-names-for-every-gamer/"><u>[Updated] 2024 Approved  100+ Cool Gaming Channel Names for Every Gamer</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-best-screen-recorder-no-ads-for-android/"><u>[Updated] In 2024, Best Screen Recorder No Ads for Android</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-perfect-your-windowsmac-call-records-with-15plus-tips-for-skype-users/"><u>[Updated] In 2024, Perfect Your Windows/Mac Call Records with 15+ Tips for Skype Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-honor-x50-gt-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Honor X50 GT Activity | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/can-you-unlock-apple-iphone-8-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>Can You Unlock Apple iPhone 8 After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/critique-free2x-app-for-webcam-capture/"><u>Critique  Free2X App for Webcam Capture</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-win-11-widget-features-efficiency-or-frivolous/"><u>Delving Into Win 11 Widget Features - Efficiency or Frivolous?</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-ai-driven-tools-on-microsofts-platform/"><u>Discovering AI-Driven Tools on Microsoft's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-uncover-and-clear-windows-usage-tracks/"><u>Efficient Methods to Uncover and Clear Windows Usage Tracks</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-no-servers-frustration-9-fixes-for-pc-apex-legends-errors-(156-chars/"><u>Eliminate 'No Servers' Frustration: 9 Fixes for PC Apex Legends Errors (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-server-unreachable-for-ea-games/"><u>Eliminating Server Unreachable for EA Games</u></a></li>
<li><a href="https://win11.techidaily.com/enriched-learning-through-ed-themed-ui-on-win-11/"><u>Enriched Learning Through Ed-Themed UI on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-file-notifications-in-windows-outlook/"><u>Eradicating File Notifications in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-roblox-fatal-app-failures-in-windows/"><u>Fixing Roblox Fatal App Failures in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/fostering-connections-advanced-tips-for-facebook-post-impact/"><u>Fostering Connections: Advanced Tips for Facebook Post Impact</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reinstating-deleted-windows-update-service/"><u>Guide to Reinstating Deleted Windows Update Service</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-taskbar-power-in-windows-11/"><u>Harnessing Taskbar Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-capture-gameplay-on-windows-with-intel-graphics-command-center/"><u>How to Capture Gameplay on Windows With Intel Graphics Command Center</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disregard-the-upcoming-expiry-alert-in-windows-1011/"><u>How To Disregard the “Upcoming Expiry” Alert in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-sound-error-code-0xc00d36b4-win11/"><u>How to Mend Sound Error: Code 0xC00D36B4, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-credential-manager-entry/"><u>How to Regain Credential Manager Entry</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-fostering-fandoms-top-three-storytelling-techniques/"><u>In 2024, Fostering Fandoms  Top Three Storytelling Techniques</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-oppo-a18-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Oppo A18 FRP Locks</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-love-in-motion-discovering-youtube-and-vimeos-top-7-wedding-films/"><u>In 2024, Love in Motion  Discovering YouTube & Vimeo's Top 7 Wedding Films</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-masterful-thumbnails-in-a-flash-professional-valorant-creations/"><u>In 2024, Masterful Thumbnails in a Flash  Professional Valorant Creations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-depth-look-at-final-cut-pro-functions-and-features/"><u>In-Depth Look at Final Cut Pro Functions and Features</u></a></li>
<li><a href="https://driver-install.techidaily.com/instructions-for-efficient-driver-installation-of-a6200-network-card/"><u>Instructions for Efficient Driver Installation of A6200 Network Card</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/learn-and-save-final-cut-pro-education-pricing-you-wont-want-to-miss/"><u>Learn and Save Final Cut Pro Education Pricing You Wont Want to Miss</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-rgb-lighting-in-windows-11/"><u>Learn to Control RGB Lighting in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-adjusting-admin-settings-on-windows-11/"><u>Master the Art of Adjusting Admin Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-ip-retrieval-via-command-line/"><u>Mastering: Windows IP Retrieval via Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-iomap64-freezebsod-in-windows-10-and-8-systems/"><u>Overcoming IOMap64 Freeze/BSOD in Windows 10 & 8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/reestablish-uninterrupted-gameplay-in-gaming-environment/"><u>Reestablish Uninterrupted Gameplay in Gaming Environment</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-5ghz-network-visibility-in-windows-11-top-fixes/"><u>Restore Your 5GHz Network Visibility in Windows 11 - Top Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-code-0xa00f4243-for-multiple-camera-usage/"><u>Sidestepping Error Code: 0XA00F4243 for Multiple Camera Usage</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unblocked-files-via-powershell-on-pc/"><u>Simplifying Unblocked Files via PowerShell on PC</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-no-error-message-in-win11-install/"><u>Steps to Overcome No Error Message in Win11 Install</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-error-0x80072f8f-0x20000/"><u>Strategies to Combat Error 0X80072f8f - 0X20000</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resuscitate-non-responsive-spotify-app-in-win11/"><u>Strategies to Resuscitate Non-Responsive Spotify App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-directdraw-errors-in-win1011/"><u>Swiftly Correcting DirectDraw Errors in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-hidden-net-identity-errors-windows/"><u>Tackling Hidden Net Identity Errors Windows</u></a></li>
<li><a href="https://win11.techidaily.com/take-your-windows-11-search-to-the-next-level-top-five-insights/"><u>Take Your Windows 11 Search to the Next Level: Top Five Insights</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-gone-security-questions-for-your-local-admin-user/"><u>The Guide to Gone Security Questions for Your Local Admin User</u></a></li>
<li><a href="https://win11.techidaily.com/the-shield-of-anonymity-network-file-security-on-windows/"><u>The Shield of Anonymity: Network File Security on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-iphone-xr-and-android-phones-by-drfone-ios/"><u>Top IMEI Unlokers for iPhone XR and Android Phones</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-tasks-admin-cmd-mode/"><u>Transform Windows Tasks: Admin CMD Mode</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-vintage-pc-a-step-by-step-guide-to-windows-11-to-go-and-rufus/"><u>Transform Your Vintage PC: A Step-by-Step Guide to Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultrafine-in-action-an-extended-review-of-lgs-4k-display-for-2024/"><u>UltraFine in Action  An Extended Review of LG’s 4K Display for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-creative-potential-using-paint-cocreator-to-make-ai-images-on-windows-11/"><u>Unleashing Your Creative Potential: Using Paint Cocreator to Make AI Images on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-secrets-to-hd-classic-quests-top-tips-and-tricks-on-windows-plus-scummvm/"><u>Unlock the Secrets to HD Classic Quests: Top Tips and Tricks on Windows + ScummVM</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>