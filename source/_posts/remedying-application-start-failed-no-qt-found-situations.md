---
title: "Remedying 'Application Start Failed: No Qt Found' Situations"
date: 2024-12-03T18:32:45.864Z
updated: 2024-12-07T10:59:40.551Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Remedying 'Application Start Failed: No Qt Found' Situations"
excerpt: "This Article Describes Remedying 'Application Start Failed: No Qt Found' Situations"
keywords: Fixing Qt Application Fail,Resolve Qt Error Start,Unblock Qt App Launch,Qt Installation Woes,Clear Qt Application Failure,Qt Runtime Execution Problem,Qt Development Setup Tips
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## Remedying 'Application Start Failed: No Qt Found' Situations

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-rejuvenated-interview-framework-for-auditory-appeal/"><u>[New] 2024 Approved Rejuvenated Interview Framework for Auditory Appeal</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guide-to-structuring-youtube-content-with-separate-chapters-for-2024/"><u>[New] Guide to Structuring YouTube Content with Separate Chapters for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-the-power-of-shareable-internet-humor/"><u>[New] Unlocking the Power of Shareable Internet Humor</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quickquip-quartermotion-grip-for-2024/"><u>[Updated] QuickQuip QuarterMotion Grip for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-youtube-entrance-videos-with-the-top-tools-for-2024/"><u>Crafting YouTube Entrance Videos with the Top Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/easy-to-follow-guide-converting-mp3-files-into-professional-audio-cds-via-windows-and-imgburn/"><u>Easy-to-Follow Guide: Converting Mp3 Files Into Professional Audio CDs via Windows & ImgBurn</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/error-solved-excel-2023-file-is-not-in-recognizable-format-by-stellar-guide/"><u>Error Solved Excel 2023 file is not in recognizable format</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-hide-or-show-the-clock-and-date-from-the-taskbar-in-windows-10-and-11/"><u>How to Hide or Show the Clock and Date From the Taskbar in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-mending-ignored-drives/"><u>Identifying and Mending Ignored Drives</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-advanced-techniques-for-precise-online-image-cropping/"><u>In 2024, Advanced Techniques for Precise Online Image Cropping</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-oppo-f25-pro-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Oppo F25 Pro 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/instant-guide-to-restore-brightness-in-windows-steam/"><u>Instant Guide to Restore Brightness in Windows Steam</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-custom-screensavers/"><u>Mastering Windows 11 Custom Screensavers</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-shift-keys-functionality/"><u>Restore Your Shift Key's Functionality</u></a></li>
<li><a href="https://extra-support.techidaily.com/sharpviewzoomx7-professional-photo-size-controls-for-2024/"><u>SharpViewZoomX7 Professional Photo Size Controls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11-39/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11 (39)</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-windows-setup-for-optimal-mics/"><u>Tailoring Windows Setup for Optimal Mics</u></a></li>
<li><a href="https://win11.techidaily.com/why-windows-updated-outlook-is-a-must-have-for-professionals/"><u>Why Windows' Updated Outlook Is a Must-Have for Professionals</u></a></li>
</ul></div>

