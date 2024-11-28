---
title: Correcting Application Launch Disruptions From Qt Shortfall
date: 2024-11-21T22:26:51.778Z
updated: 2024-11-27T16:39:42.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Application Launch Disruptions From Qt Shortfall
excerpt: This Article Describes Correcting Application Launch Disruptions From Qt Shortfall
keywords: QT App Launch Issues,Qt Development Pitfalls,Bug Fix in Qt Programs,Qt Error Handling,Qt Shortcut Solutions,Qt Application Stability,Qt Performance Tweaks
thumbnail: https://thmb.techidaily.com/d16299364ff8a12ac1730983e510ad0f5d027390038abb94b7b607447c1cc871.jpg
---

## Correcting Application Launch Disruptions From Qt Shortfall

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-information.techidaily.com/new-12-hacks-to-find-and-download-the-best-free-stock-photography/"><u>[New] 12 Hacks to Find and Download the Best Free Stock Photography</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-sparking-social-media-stories-facebook-fame-techniques/"><u>[New] 2024 Approved Sparking Social Media Stories Facebook Fame Techniques</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-expert-tips-for-effortless-green-screening-in-kinemaster-software/"><u>[New] Expert Tips for Effortless Green Screening in KineMaster Software</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-drone-giants-competing-dji-mavic-meets-karma/"><u>[New] In 2024, Drone Giants Competing DJi Mavic Meets Karma</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-depth-guide-to-extracting-vimeo-media-for-2024/"><u>[New] In-Depth Guide to Extracting Vimeo Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-connecting-your-computer-again/"><u>Bridge the Gap: Connecting Your Computer Again</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-quick-access-initiate-file-explorer-via-onedrive-link/"><u>Bypass Quick Access: Initiate File Explorer via OneDrive Link</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-error-0x80242016-for-updates/"><u>Circumventing Error 0X80242016 for Updates</u></a></li>
<li><a href="https://win11.techidaily.com/classic-diablo-playbook-step-by-step-guide/"><u>Classic Diablo Playbook: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-to-chatting-ease-on-your-pc/"><u>Clear the Path to Chatting Ease on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-successfully-downloading-from-the-ms-store/"><u>Clearing Errors: Successfully Downloading From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/combat-disappearing-steam-app-graphics/"><u>Combat Disappearing Steam App Graphics</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/how-innovative-technology-tackles-climate-change-discover-the-five-key-tools-shaping-our-environmental-strategy-featured-on-zdnet/"><u>How Innovative Technology Tackles Climate Change: Discover the Five Key Tools Shaping Our Environmental Strategy | Featured on ZDNET</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-13-pro-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone 13 Pro to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-unveiling-the-nuances-of-anime-dubbing-methodology-examples-and-best-practices-for-2024/"><u>New Unveiling the Nuances of Anime Dubbing Methodology, Examples, & Best Practices for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-easy-way-to-switch-from-dall-e-3-webp-images-to-accessible-jpgpng-versions/"><u>The Easy Way to Switch From DALL-E 3 WebP Images to Accessible JPG/PNG Versions</u></a></li>
</ul></div>

