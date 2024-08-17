---
title: How to Straighten Out Window Corners
date: 2024-08-16T00:28:19.392Z
updated: 2024-08-17T00:28:19.392Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Straighten Out Window Corners
excerpt: This Article Describes How to Straighten Out Window Corners
keywords: Straight Edge Windows,Window Corner Alignment,Fixed Window Edges,Smooth Corner Finish,Ledge Removal Technique,Tips for Corners Precision,Perfect Window Angles
thumbnail: https://thmb.techidaily.com/329d369e5db1c978f66185fe9a5482898ede3269e6a52b60eb890177d543e794.png
---

## How to Straighten Out Window Corners

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-maximize-your-webcam-hp-and-chromebook-strategies/"><u>[New] 2024 Approved  Maximize Your Webcam  HP & Chromebook Strategies</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-swift-circulation-of-playlists-on-youtube/"><u>[New] 2024 Approved  Swift Circulation of Playlists on YouTube</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-practices-for-seamless-transitions-using-b-roll/"><u>[New] Best Practices for Seamless Transitions Using B Roll</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/aximizing-vids-for-cash-comparing-dm-and-yo-strategies/"><u>[New] Maximizing Vids for Cash  Comparing Dm & Yo Strategies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-the-art-of-timelapses-recording-techniques-for-ipads/"><u>[Updated] In 2024, The Art of Timelapses  Recording Techniques for iPads</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-master-the-art-of-cutting-with-vivacuts-full-review-2024/"><u>[Updated] Master the Art of Cutting with VivaCut's Full Review 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-odins-revenge-ragnarok-coming-soon-in-2024/"><u>[Updated] Odin's Revenge  Ragnarök - Coming Soon, In 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unveiling-youtube-video-mastery-through-finalcut-pro-methods/"><u>[Updated] Unveiling YouTube Video Mastery Through FinalCut Pro Methods</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-expert-insights-on-optimal-fpv-drone-blades/"><u>2024 Approved  Expert Insights on Optimal FPV Drone Blades</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pioneering-virtual-play-samsungs-most-popular-titles/"><u>2024 Approved  Pioneering Virtual Play  Samsung's Most Popular Titles</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-top-phones-that-seamlessly-integrate-with-the-latest-gear-vr/"><u>2024 Approved  Top Phones That Seamlessly Integrate with the Latest Gear VR</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beware-the-fraudulent-chatgpt-extension-for-chrome-that-steals-facebook-account-logins/"><u>Beware the Fraudulent ChatGPT Extension for Chrome that Steals Facebook Account Logins</u></a></li>
<li><a href="https://win11.techidaily.com/boost-quality-with-these-5-free-windows-editors/"><u>Boost Quality with These 5 FREE Windows Editors</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://games-able.techidaily.com/comparing-computer-use-gaming-vs-professional-work/"><u>Comparing Computer Use: Gaming Vs. Professional Work</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comparing-the-latest-titans-samsung-galaxy-s23-ultra-vs-s21-ultra/"><u>Comparing the Latest Titans: Samsung Galaxy S23 Ultra vs S21 Ultra</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-nubia-red-magic-8s-proplus-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-the-world-of-usb-20-transmission-rates-cable-types-and-connectors-unveiled/"><u>Deciphering the World of USB 2.0: Transmission Rates, Cable Types, and Connectors Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-huawei-nova-y71-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Huawei Nova Y71 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-persistent-login-challenges-with-ms-teams/"><u>Eliminating Persistent Login Challenges with MS Teams</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://tech-revival.techidaily.com/expanding-possibilities-with-chatgpts-imagery-technology/"><u>Expanding Possibilities with ChatGPT’s Imagery Technology</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-bridging-imessage-between-devices/"><u>From iPhone to Desktop: Bridging iMessage Between Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-dedicated-video-ram-vram-in-windows-11-and-11/"><u>How to Increase Dedicated Video RAM (VRAM) in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-pcs-current-window-background-file/"><u>How to Locate PC's Current Window Background File</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-asus-rog-phone-7-ultimate-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Asus ROG Phone 7 Ultimate in Minutes | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-oppo-a1x-5g-drfone-by-drfone-android/"><u>How to Screen Mirroring Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-poco-c51-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Poco C51 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-a-brief-history-of-virtual-reality/"><u>In 2024, A Brief History of Virtual Reality</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-infinix-note-30-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Infinix Note 30 5G</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-lives-beyond-windows-11-expectations/"><u>Leading-Edge Lives: Beyond Windows 11 Expectations</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/navigating-accurately-through-ru-alphabets/"><u>Navigating Accurately Through RU Alphabets</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-administrator-settings-in-windows-security/"><u>Navigating Administrator Settings in Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-boot-failures-8-fixes-for-virtual-machines-on-wm11os/"><u>Overcome Boot Failures: 8 Fixes for Virtual Machines on WM11OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-windows-laptop-lag-on-dual-screens/"><u>Overcoming the Hurdle of Window's Laptop Lag on Dual Screens</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-tecno-pova-6-pro-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Tecno Pova 6 Pro 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-poco-m6-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Poco M6 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-experience-select-top-optimizers-ranked/"><u>Prime Windows Experience: Select Top Optimizers Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-alternative-pdf-printer-in-windows/"><u>Setting Alternative PDF Printer in Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/simple-steps-how-to-update-your-scansnap-ix500-drivers-on-windows/"><u>Simple Steps: How to Update Your ScanSnap iX500 Drivers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-sailing-through-full-screen-issues-sonic-style-on-w11/"><u>Smooth Sailing Through Full-Screen Issues, Sonic Style on W11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-bypassing-hiccups-and-blockades/"><u>Streamlining Windows 11: Bypassing Hiccups & Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-androidpc-junctioning/"><u>The Ultimate Guide to Android/PC Junctioning</u></a></li>
<li><a href="https://win11.techidaily.com/tranquil-technology-effortless-windows-11-shutdown/"><u>Tranquil Technology: Effortless Windows 11 Shutdown</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-tutorial-how-to-delete-win10-memory-dump-file/"><u>Ultimate Tutorial: How To Delete Win10 Memory Dump File</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-your-digital-sketchpad-launching-ms-paint-on-win11/"><u>Unveiling Your Digital Sketchpad: Launching MS Paint on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-cryptographic-solutions-ranked-148-chars/"><u>Window's Best Cryptographic Solutions Ranked (148 Chars)</u></a></li>
</ul></div>
