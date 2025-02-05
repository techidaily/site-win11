---
title: Steps to Overcome OBS Recording Glitch on Windows
date: 2025-01-28T04:55:12.443Z
updated: 2025-02-03T21:04:22.285Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Overcome OBS Recording Glitch on Windows
excerpt: This Article Describes Steps to Overcome OBS Recording Glitch on Windows
keywords: Fixing OBS Glitch,Overcoming OBS Crashes,Resolve OBS Errors,OBS Win Recovery Steps,Stop OBS Freeze on PC,Correcting Windows OBS Issue,Troubleshoot OBS Window Error
thumbnail: https://thmb.techidaily.com/b65c1700fc3be6103fe73469bcdff9ebd5593034f3622d27aea03408c9719ceb.jpg
---

## Steps to Overcome OBS Recording Glitch on Windows

 OBS Studio is a great program to record and stream online. However, some users can't utilize OBS Studio because of a recording error that occurs when they try to record their screens. Instead of recording, OBS Studio throws up this message: "An unspecified error occurred while recording."

 The error usually appears when an important DLL file is missing, or there's corruption in the OBS Studio installation directory. As such, if you also see the same error, then try the below solutions to eliminate the problem for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart OBS Studio

![Closing the OBS Studio Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/end-task.jpg)

 Whether you're[seeing a black screen](https://www.makeuseof.com/windows-11-obs-black-screen-fix/) or getting the "An unspecified error occurred while recording" error, the best way to fix any OBS Studio issue is to restart it. Restarting OBS Studio will clear the system resources and kill any temporary bugs or glitches that might be causing the error.

 To restart OBS Studio, open the**Task Manager** (see how to[open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on OBS Studio, and choose**End Task.** Then, search for OBS Studio in the**Start Menu** and choose**Open** from the right pane.

## 2\. Temporarily Disable Your Graphics Driver

 The error is likely to occur if there's corruption in the GPU log file that is used by the OBS Studio. To remove the corruption, you'll have to disable the graphics driver before launching the OBS Studio. Doing this will force the program to create a new GPU log.

Here's what you need to do:

1. Open the**Power User Menu** by pressing the**Win + X** hotkey and choose**Device Manager** from the context menu.
2. In the Device Manager, double-click on the**Display adapters** node to expand it.
3. Right-click on the dedicated graphics driver and choose**Disable device.**  
![Disable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-option-1.jpg)
4. Click**Yes** to the prompt that appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your screen might flicker after disabling the dedicated graphics driver. But worry not; it'll become normal after the generic driver is started.

 Now, launch the OBS Studio and open your project. Then, open the Device Manager again > access the Display adapters node > right-click on the dedicated graphics driver and choose**Enable device.**

![Enable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-device.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it! Return to OBS Studio and check if you are able to record.

## 3\. Allow OBS Studio Through Your Firewall

 OBS Studio might fail to record and throw the error at hand if it's blocked under Windows Firewall. To fix this, you'll have to whitelist OBS Studio from the Windows Firewall blocked app list. Here's how to do that:

1. Press the**Win** key to open the**Start Menu.**
2. Type**Windows Firewall** in the search bar and press Enter.
3. Choose **Allow an app or feature through Windows Defender Firewall** option from the left sidebar.  
![Allow an app or feature through Windows Defender Firewall option in Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/allow-an-app-or-feature-through-windows-defender-firewall-option.jpg)
4. Click the**Change settings** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click on**Allow another app** and then choose**Browse** from the**Add an app** prompt.  
![Add an app prompt in the Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-app.jpg)
6. Navigate to the location where you have installed the OBS Studio.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Select the**obs-ffmpeg-mux** executable file and click**Open.**  
![obs-ffmpeg-mux file in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/obs-ffmpeg-mux-file.jpg)
8. Click**Add.**

9. Check both the**Private** and**Public** boxes for**obs-ffmpeg-mux** and click**OK** to save the settings.  
![Private and Public boxes for OBS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/private-and-public-boxes.jpg)

Restart your computer and check if the problem continues.

## 4\. Fix the Missing DLL Files

[Dynamic Link Libraries](https://www.makeuseof.com/what-are-dll-files-on-windows/) , aka DLL files, are special implementations of system libraries that contain various functions and variables that programs use when needed. If an important DLL file required by OBS Studio goes missing, you will see the "An unspecified error occurred while recording" error.

 To fix that, you will have to re-acquire the required DLL file. Here's how:

1. Navigate to the place where you have installed the OBS Studio.
2. Double-click on the obs-ffmpeg-mux file, and note down which of the following DLL file is missing.  
`avcodec-57.dll  
avformat-57.dll  
avutil-55.dll  
swresample-2.dll`
3. Follow our guide on[how to fix DLL files missing on Windows](https://www.makeuseof.com/tag/dll-files-missing-errors/) to repair the missing file.

Restart your computer and check for the issue.

## 5\. Edit the OBS-Ffmpeg-Mux Installation Folder

 If you're still facing the issue even after downloading the missing DLL file, then it indicates that OBS Studio is unable to find the required DLL. The solution, in this case, is to edit the Path environment so that OBS Studio finds the required DLL files.

You can do that by following the below instructions:

1. Press the**Win + I** key to open the**Settings** **app.**
2. In the System tab, choose the**About** option in the left pane.
3. Click the**Advanced system settings** option.  
![Advanced system settings option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-system-settings.jpg)
4. Click the**Environment Variables** button.  

![Environment Variables option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enviroment-variables.jpg)
5. Select**Path** under the**System Variables** section, and click the**Edit** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Paste the following path in the**Variable value** text box and click**OK.**  
`C:\Program Files (x86)\obs-studio\bin\32bit;`  
![Edit Variable in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-variable.jpg)

 That's it! Now, start recording in OBS Studio and check if the problem persists.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check for Corrupted or Missing Files

 Sometimes, OBS Studio might fail to record due to corruption in its installation folder. The problem can also occur if an important file is missing.

 In either case, you can use the "Check File Integrity" feature to scan the OBS installation for corruption and redownload broken/ missing files. Here's how to use that feature:

1. Launch OBS Studio, click the**Help** option at the top, and choose the**Check File Integrity** option from the context menu.  
![Check File Integrity option in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-file-integrity-option.jpg)
2. Click**Yes** to confirm your selection.

 OBS Studio will compare the available files with those on its server and download any missing or broken files.

 While you're at the OBS Studio home screen, check for and download any available updates. To do that, click**Help** and choose**Check for Updates** .

## 7\. Reinstall OBS Studio

 If you're still getting the error message, you're left with no option other than reinstalling OBS Studio. To do that, first[uninstall OBS Studio from Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) .

 Then, visit the[OBS Studio official website](https://obsproject.com/) , and download and install the latest version on your computer.

## Enjoy Seamless Recording With OBS Studio

 OBS Studio makes it a cakewalk to record anything and upload it online. However, due to corruption in its installation folder or missing DLL files, it might throw the "An unspecified error occurred while recording" error. Fortunately, you can quickly get rid of this error by applying the above fixes.

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
<li><a href="https://youtube-help.techidaily.com/new-get-smart-with-your-youtube-thumbnails-using-a-mac/"><u>[New] Get Smart with Your YouTube Thumbnails, Using a Mac</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-virtual-quality-assurance-examining-apps-with-vll/"><u>[New] In 2024, Virtual Quality Assurance Examining Apps with VLL</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-cam-division-is-splitcam-the-1-choice-in-2024/"><u>[Updated] Cam Division Is SplitCam the #1 Choice, In 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-enhance-yt-experience-the-most-outstanding-reaction-ideas/"><u>[Updated] Enhance YT Experience The Most Outstanding Reaction Ideas</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-iphone-se-2020-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/command-mastery-embracing-sudo-on-windows-pcs/"><u>Command Mastery: Embracing Sudo on Windows PCs</u></a></li>
<li><a href="https://article-helps.techidaily.com/effortless-entry-to-entertainment-the-ifunny-app-experience/"><u>Effortless Entry to Entertainment The iFunny App Experience</u></a></li>
<li><a href="https://win11.techidaily.com/hide-time-show-dates-taskbar-settings-insight/"><u>Hide Time, Show Dates - Taskbar Settings Insight</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/how-to-fix-graphics-issues-on-your-windows-pc-a-step-by-step-guide/"><u>How to Fix Graphics Issues on Your Windows PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-discover-the-joy-of-real-time-broadcasting-with-fb-and-roku/"><u>In 2024, Discover the Joy of Real-Time Broadcasting with FB & Roku</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-computer-mechanics-creating-and-interpreting-reports/"><u>Mastering Computer Mechanics: Creating & Interpreting Reports</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-quickly-to-system-resolutions-in-windows-using-keys/"><u>Navigating Quickly to System Resolutions in WIndows Using Keys</u></a></li>
<li><a href="https://win11.techidaily.com/new-ui-features-in-enhanced-windows-11/"><u>New UI Features in Enhanced Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-11-altering-system-preferences/"><u>Personalizing Windows 11: Altering System Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functional-key-presses-for-snipshot/"><u>Restoring Functional Key Presses for Snipshot</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/scaricamento-rapido-e-facile-come-usare-il-dvd-di-movavi-con-solo-un-click/"><u>Scaricamento Rapido E Facile: Come Usare Il DVD Di Movavi Con Solo Un Click</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-resolving-system-call-failed-errors-in-windows/"><u>Step-by-Step: Resolving System Call Failed Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/synthesize-your-way-through-the-voice-driven-accessibility-of-win11/"><u>Synthesize Your Way Through the Voice-Driven Accessibility of Win11</u></a></li>
</ul></div>

