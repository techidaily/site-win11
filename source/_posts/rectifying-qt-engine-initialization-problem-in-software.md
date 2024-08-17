---
title: Rectifying Qt Engine Initialization Problem in Software
date: 2024-08-16T00:33:39.068Z
updated: 2024-08-17T00:33:39.068Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Qt Engine Initialization Problem in Software
excerpt: This Article Describes Rectifying Qt Engine Initialization Problem in Software
keywords: Fixing Qt Init Issue,Qt Engine Start-Up Errors,Resolving Qt Initialization,Qt Framework Correction,Debugging Qt Launch Problem,Qt Software Init Fix,Qt Initialize Failure Remedy
thumbnail: https://thmb.techidaily.com/580872e4bd4e21da3535470ce3b918e09ae5b8653067a4110ec11928ef11818a.jpg
---

## Rectifying Qt Engine Initialization Problem in Software

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.
6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are [more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out [how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->

## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.


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
<li><a href="https://screen-recording.techidaily.com/new-advanced-techniques-in-logitech-webcam-video-recording/"><u>[New] Advanced Techniques in Logitech Webcam Video Recording</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-how-to-screen-record-on-xiaomi-11t-mi-11mi-11-lite/"><u>[New] How to Screen Record on Xiaomi 11T/ Mi 11/Mi 11 Lite</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-pro-mkv-reader-for-personal-computers/"><u>[New] Pro MKV Reader for Personal Computers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-avoid-the-spinning-room-top-5-vr-motion-control-techniques/"><u>[Updated] In 2024, Avoid the Spinning Room  Top 5 VR Motion Control Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-intensify-your-videoleap-images-through-precision-zooming/"><u>2024 Approved  Intensify Your Videoleap Images Through Precision Zooming</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-optimizing-video-playback-for-engaged-audiences/"><u>2024 Approved  Optimizing Video Playback for Engaged Audiences</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-ultimate-guide-macbook-cam-filming-basics/"><u>2024 Approved  Ultimate Guide  MacBook Cam Filming Basics</u></a></li>
<li><a href="https://article-tips.techidaily.com/a-dive-into-the-best-filmora-edits-for-enthusiasts/"><u>A Dive Into the Best Filmora Edits for Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-untapped-windows-features-reliability-and-performance/"><u>Comparing Untapped Windows Features: Reliability & Performance</u></a></li>
<li><a href="https://win11.techidaily.com/conceal-or-show-taskbars-date-and-clock-in-win-11/"><u>Conceal or Show Taskbar's Date & Clock in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-worlds-android-pc-joint-venture-explained/"><u>Connecting Worlds: Android-PC Joint Venture Explained</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-xc0000142-on-win10-11/"><u>Correcting Error XC0000142 on Win10, 11</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-the-oled-world-asus-s15s-unique-appeal/"><u>Diving Into the OLED World: ASUS S15's Unique Appeal</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-freeze-and-crash-in-windows-epic-launcher/"><u>Eliminating Freeze and Crash in Windows Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-supercharge-your-startup-with-windows-11/"><u>Essential Steps to Supercharge Your Startup with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-xbox-app-working-again-on-your-windows-laptop/"><u>Get the Xbox App Working Again on Your Windows Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-action-plan-reactivating-your-menu-items/"><u>Immediate Action Plan: Reactivating Your Menu Items</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solutions-bringing-your-google-drive-back-online/"><u>Immediate Solutions: Bringing Your Google Drive Back Online</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-future-of-advertising-in-the-metaverse/"><u>In 2024, The Future of Advertising in the Metaverse</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-windows-updates-issue-code-x80246007/"><u>Mastering the Resolution of Windows Updates Issue Code X80246007</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigate-the-world-of-high-tech-hardware-with-insightful-guides-by-tom/"><u>Navigate the World of High-Tech Hardware with Insightful Guides by Tom</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-win11-for-a-smoother-jump-into-programs-on-startup/"><u>Optimizing Win11 for a Smoother Jump Into Programs on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-11-tools-for-unmatched-video-scripting-and-edits/"><u>Prime Windows 11 Tools for Unmatched Video Scripting & Edits</u></a></li>
<li><a href="https://win11.techidaily.com/quick-troubleshooting-tips-to-rescue-windows-apps/"><u>Quick Troubleshooting Tips to Rescue Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-nine-essential-tricks-for-reviving-apps-in-windows-11/"><u>Reclaim Your Lost Windows: Nine Essential Tricks for Reviving Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-vintage-directx-apps-by-harnessing-dxvk-power/"><u>Revitalizing Vintage DirectX Apps by Harnessing DXVK Power</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/selfies-on-snap-verifying-authenticity-for-2024/"><u>Selfies on Snap  Verifying Authenticity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/signs-your-pc-struggles-when-to-consider-clean-slate/"><u>Signs Your PC Struggles, When to Consider Clean Slate</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-files-using-powerrename-in-powertoys/"><u>Streamline Your Files: Using PowerRename in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-timely-purge-of-steam-dns-cache-on-pc/"><u>Techniques for Timely Purge of Steam DNS Cache on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-game-for-windows-xp781-on-microsoft-platforms/"><u>The End Game for Windows XP/7/8.1 on Microsoft Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-13-fixes-for-windows-restoration-woes/"><u>The Ultimate Guide: 13 Fixes for Windows Restoration Woes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-instantaneous-techniques-for-cutting-down-residual-hum-in-recordings/"><u>Updated Instantaneous Techniques for Cutting Down Residual Hum in Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-user-interface-an-insight/"><u>Windows 11 User Interface: An Insight</u></a></li>
</ul></div>
