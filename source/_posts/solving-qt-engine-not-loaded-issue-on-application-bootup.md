---
title: Solving Qt Engine Not Loaded Issue on Application Bootup
date: 2024-10-09T22:32:47.828Z
updated: 2024-10-15T18:33:36.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Qt Engine Not Loaded Issue on Application Bootup
excerpt: This Article Describes Solving Qt Engine Not Loaded Issue on Application Bootup
keywords: Qt Engine Load Failure,Application Start-Up Error,Qt Not Initialized,App QT Init Problem,Qt Library Loading Issue,Qt Engine Bootup Trouble,Fixing Qt Application Launch
thumbnail: https://thmb.techidaily.com/c4e970c61c745a22a93f179d1f650cdbb34448ec2a9158efa033c2403816542e.jpg
---

## Solving Qt Engine Not Loaded Issue on Application Bootup

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461">
  <img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-prime-video-streamers-camera-picks-for-quality-content/"><u>[New] 2024 Approved Prime Video Streamers' Camera Picks for Quality Content</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-top-7-video-streaming-innovations-excel-on-youtube-with-iphonesandroid-os/"><u>[Updated] Top 7 Video Streaming Innovations Excel on YouTube with iPhones/Android OS</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-enhance-phantom-flying-top-11-add-on-gear/"><u>2024 Approved Enhance Phantom Flying Top 11 Add-On Gear</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-picks-for-gaming-displays-on-xbox-series-x-console/"><u>2024 Approved Top Picks for Gaming Displays on Xbox Series X Console</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>A Detailed VPNa Fake GPS Location Free Review On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/charting-a-course-for-earthlings-inaugural-flight-tactics-and-advice/"><u>Charting a Course for Earthlings’ Inaugural Flight: Tactics and Advice</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-delays-in-your-windows-discord-experience/"><u>Eliminating Delays in Your Windows Discord Experience</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-vivo-y28-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Vivo Y28 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-vram-usage-for-optimal-rendering/"><u>Mastering Windows VRAM Usage for Optimal Rendering</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-addressing-pin-validation-glitch/"><u>Overcoming Windows 10/11: Addressing Pin Validation Glitch</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/reel-in-real-time-the-top-5-innovative-recorder-apps-for-browsers/"><u>Reel in Real-Time The Top 5 Innovative Recorder Apps for Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-downloads-on-windows-our-5-favorite-torrent-tools/"><u>Streamlined Downloads on Windows: Our 5 Favorite Torrent Tools</u></a></li>
<li><a href="https://win11.techidaily.com/synching-files-across-two-windows-pcs-made-easy-with-aoemi/"><u>Synching Files Across Two Windows PCs Made Easy with AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-qbittorrents-freeze-in-windows-environment/"><u>Troubleshooting qBittorrent's Freeze in Windows Environment</u></a></li>
</ul></div>

