---
title: Ensuring Smooth Start of Programs Despite Qt Platform Missing
date: 2024-12-17T16:34:21.286Z
updated: 2024-12-22T17:00:10.757Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Smooth Start of Programs Despite Qt Platform Missing
excerpt: This Article Describes Ensuring Smooth Start of Programs Despite Qt Platform Missing
keywords: Qt Program Startups,Handling Qt Missing,Qt Platform Check,Program Launch Precautions,Qt Dependency Management,Smooth Qt Initiation,Mitigate Qt Absence
thumbnail: https://thmb.techidaily.com/0fdf2fa9392d7802826e32aaa7c1f7d7a9d236164e77dff001f4eb865ae62af5.jpg
---

## Ensuring Smooth Start of Programs Despite Qt Platform Missing

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/024-approved-teach-with-technology-effective-use-of-youtube-in-education/"><u>[New] 2024 Approved Teach with Technology Effective Use of YouTube in Education</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-building-interest-with-budget-friendly-youtube-video-intros-for-2024/"><u>[New] Building Interest with Budget-Friendly YouTube Video Intros for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-blueprints-for-constructing-a-high-definition-video-editing-beast/"><u>2024 Approved Blueprints for Constructing a High-Definition Video Editing Beast</u></a></li>
<li><a href="https://win-online.techidaily.com/comment-resoudre-limpossibilite-de-restaurer-ou-dextraire-des-fichiers-lors-du-demarrage-sous-windows-10/"><u>Comment Résoudre L'impossibilité De Restaurer Ou D'extraire Des Fichiers Lors Du Démarrage Sous Windows 10 ?</u></a></li>
<li><a href="https://fox-links.techidaily.com/e-comic-crafting-kit-for-2024/"><u>E-Comic Crafting Kit for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earning-potential-unveiled-youtube-adsense-earning-per-thousand-video-observations/"><u>Earning Potential Unveiled YouTube AdSense Earning per Thousand Video Observations</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-verify-pin-bluetooth-issue-on-windows-systems/"><u>Eliminating Verify Pin Bluetooth Issue on Windows Systems</u></a></li>
<li><a href="https://fox-http.techidaily.com/ideal-days-for-launching-a-podcast-for-2024/"><u>Ideal Days for Launching a Podcast for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-windows-11-serene-stop-background-jobs/"><u>Keeping Windows 11 Serene: Stop Background Jobs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-turn-off-windows-mobility-center/"><u>Navigate to Turn Off Windows Mobility Center</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-deadly-js-error-a-solution-guide-for-win-11-users/"><u>Navigating Past Deadly JS Error: A Solution Guide for Win 11 Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-extract-audio-from-mp4-the-best-mp4-to-mp3-converters/"><u>New Extract Audio From MP4 The Best MP4 to MP3 Converters</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-deadly-wow-glitch-on-new-windows-os/"><u>Overcoming the Deadly WoW Glitch on New Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-chromeedgefirefox-copy-pasting-failures/"><u>Quick Fixes for Chrome/Edge/Firefox Copy-Pasting Failures</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/step-up-your-vr-game-with-oculus-quest-2s-elite-wristband-extra-juice-pack-and-protective-travel-case-our-in-depth-review/"><u>Step Up Your VR Game with Oculus Quest 2'S Elite Wristband, Extra Juice Pack, and Protective Travel Case - Our In-Depth Review!</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-restoring-functional-download-feature-in-chrome-windows/"><u>Techniques for Restoring Functional Download Feature in Chrome, Windows</u></a></li>
</ul></div>

