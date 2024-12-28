---
title: Steps to Overcome OBS Recording Glitch on Windows
date: 2024-12-22T05:46:04.509Z
updated: 2024-12-27T16:35:37.197Z
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

## 1\. Restart OBS Studio

![Closing the OBS Studio Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/end-task.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Your screen might flicker after disabling the dedicated graphics driver. But worry not; it'll become normal after the generic driver is started.

 Now, launch the OBS Studio and open your project. Then, open the Device Manager again > access the Display adapters node > right-click on the dedicated graphics driver and choose**Enable device.**

![Enable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-device.jpg)

 That's it! Return to OBS Studio and check if you are able to record.

## 3\. Allow OBS Studio Through Your Firewall

 OBS Studio might fail to record and throw the error at hand if it's blocked under Windows Firewall. To fix this, you'll have to whitelist OBS Studio from the Windows Firewall blocked app list. Here's how to do that:

1. Press the**Win** key to open the**Start Menu.**
2. Type**Windows Firewall** in the search bar and press Enter.
3. Choose **Allow an app or feature through Windows Defender Firewall** option from the left sidebar.  
![Allow an app or feature through Windows Defender Firewall option in Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/allow-an-app-or-feature-through-windows-defender-firewall-option.jpg)
4. Click the**Change settings** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click on**Allow another app** and then choose**Browse** from the**Add an app** prompt.  
![Add an app prompt in the Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-app.jpg)
6. Navigate to the location where you have installed the OBS Studio.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Select the**obs-ffmpeg-mux** executable file and click**Open.**  
![obs-ffmpeg-mux file in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/obs-ffmpeg-mux-file.jpg)
8. Click**Add.**

9. Check both the**Private** and**Public** boxes for**obs-ffmpeg-mux** and click**OK** to save the settings.  
![Private and Public boxes for OBS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/private-and-public-boxes.jpg)

Restart your computer and check if the problem continues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
6. Paste the following path in the**Variable value** text box and click**OK.**  
`C:\Program Files (x86)\obs-studio\bin\32bit;`  
![Edit Variable in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-variable.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it! Now, start recording in OBS Studio and check if the problem persists.

## 6\. Check for Corrupted or Missing Files

 Sometimes, OBS Studio might fail to record due to corruption in its installation folder. The problem can also occur if an important file is missing.

 In either case, you can use the "Check File Integrity" feature to scan the OBS installation for corruption and redownload broken/ missing files. Here's how to use that feature:

1. Launch OBS Studio, click the**Help** option at the top, and choose the**Check File Integrity** option from the context menu.  
![Check File Integrity option in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-file-integrity-option.jpg)
2. Click**Yes** to confirm your selection.

 OBS Studio will compare the available files with those on its server and download any missing or broken files.

 While you're at the OBS Studio home screen, check for and download any available updates. To do that, click**Help** and choose**Check for Updates** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-expert-recommendations-top-15-no-cost-audiosite-collections/"><u>[New] In 2024, Expert Recommendations Top 15 No-Cost Audiosite Collections</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-from-novice-to-pro-a-comprehensive-guide-to-using-audacity-on-a-mac/"><u>[Updated] 2024 Approved From Novice to Pro A Comprehensive Guide to Using Audacity on a Mac</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-pioneers-panoramas-open-for-all/"><u>[Updated] 2024 Approved Pioneer's Panoramas Open for All</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-designing-impactful-social-media-fb-ads-for-2024/"><u>[Updated] Designing Impactful Social Media FB Ads for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-from-apple-iphone-xs-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out From Apple iPhone XS How to Bypass?</u></a></li>
<li><a href="https://win-able.techidaily.com/battlefield-fixes-for-the-frustrating-start-up-troubles/"><u>Battlefield ➔ Fixes for the Frustrating Start-Up Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/evaluate-your-needs-best-windows-11-choice-between-home-and-pro/"><u>Evaluate Your Needs: Best Windows 11 Choice Between Home and Pro</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unclog-printer-usage-jams-in-win11/"><u>Guide to Unclog Printer Usage Jams in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-oneplus-12-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On OnePlus 12 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-squashing-social-media-smears-with-grace/"><u>In 2024, Squashing Social Media Smears with Grace</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-a-swaying-cursor-in-windows-os/"><u>Resolving a Swaying Cursor in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-wsl-the-4294967295-error-explained/"><u>Resolving WSL: The 4294967295 Error Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-stealth-attacker-uncovered-defending-windows-against-wacatacbml/"><u>The Stealth Attacker Uncovered: Defending Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-system-call-failures-in-windows-11/"><u>Troubleshooting: Resolving System Call Failures in Windows 11</u></a></li>
</ul></div>

