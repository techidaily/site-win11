---
title: Troubleshooting App Starts with Missing Qt Plugins
date: 2024-10-20T01:43:10.022Z
updated: 2024-10-27T02:13:32.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting App Starts with Missing Qt Plugins
excerpt: This Article Describes Troubleshooting App Starts with Missing Qt Plugins
keywords: Fix Qt Plugin Issue,Resolve App Start Error,Stop Qt Plugin Problems,Address Missing Qt Plugin,Correct Qt Plugin Failure,Tackle Qt Plugin Absence,Qt Plugin Loading Trouble
thumbnail: https://thmb.techidaily.com/91d802feac954d9a2b7218b9de82c000f339447018e6cb53073b6a41a90f92e5.jpg
---

## Troubleshooting App Starts with Missing Qt Plugins

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-minisculecam-record-evaluation-and-comparisons/"><u>[New] 2024 Approved MinisculeCam Record Evaluation & Comparisons</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-discover-the-finest-android-and-iphone-photo-overlays-at-no-cost-for-2024/"><u>[New] Discover the Finest Android & iPhone Photo Overlays at No Cost for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-leading-6-virtual-venues-propelling-professional-connections/"><u>[Updated] In 2024, Leading 6 Virtual Venues Propelling Professional Connections</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-selling-success-on-facebook-ideas-and-strategies-to-try/"><u>[Updated] In 2024, Selling Success on Facebook Ideas and Strategies to Try</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/discover-the-ultimate-selection-of-8-leading-photo-retouching-tools-for-vintage-images-on-your-smartphone/"><u>Discover the Ultimate Selection of 8 Leading Photo Retouching Tools for Vintage Images on Your Smartphone</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-web-mastering-facebook-twitter-instagram-and-youtube/"><u>Navigating the Web: Mastering Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-techniques-effortlessly-combining-multiple-videos-using-vlc-media-player/"><u>Seamless Techniques: Effortlessly Combining Multiple Videos Using VLC Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-videos-with-wonderfox-premium-copyright-watermarks/"><u>Secure Your Videos with WonderFox: Premium Copyright Watermarks</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-downloading-videos-from-naver-without-paying/"><u>Step-by-Step Guide: Downloading Videos From Naver Without Paying</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-recording-your-tango-calls-across-all-platforms/"><u>Step-by-Step Guide: Recording Your Tango Calls Across All Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/the-hunting-game-reversed-in-frozen-ground-dvd-release/"><u>The Hunting Game Reversed in 'Frozen Ground' DVD Release</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-7-shared-digital-calendars-perfect-for-managing-family-schedules/"><u>Top 7 Shared Digital Calendars Perfect for Managing Family Schedules</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-converting-mov-files-into-wav-format-a-comprehensive-guide/"><u>Top 8 Methods for Converting MOV Files Into WAV Format: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-mastering-the-function-fn-key/"><u>Unlocking Potential: Mastering the Function (Fn) Key</u></a></li>
</ul></div>

