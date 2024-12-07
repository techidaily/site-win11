---
title: "OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows"
date: 2024-11-30T16:01:00.299Z
updated: 2024-12-06T16:38:20.046Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows"
excerpt: "This Article Describes OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows"
keywords: OneDrive Error Fixing,Reparse Pointer Repair,Invalid Point Resolution,Office Drive Recovery,Windows File Correction,Mend It Guide Windows,Invalid Spot Fix Windows
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

## 1\. Run a CHKDSK Scan

 For Windows users, CHKDSK is a go-to utility for scanning and fixing hard drive problems. Whenever users encounter a hard drive error or an issue with the data stored on their drive, the CHKDSK scan proves to be a godsend.

 This scan may be helpful to fix the issue under discussion since "the tag present in the reparse point buffer is invalid" is also associated with an inability to access a particular file correctly. Therefore, follow the steps below to run the CHKDSK scan before you attempt any other repair or fix:

1. In the Windows Search box, type**"Command Prompt** .**"**
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Enter the following command in the Command Prompt app:  
`Chkdsk C: /f /r`
4. Then press**Enter** .  
![Running Check Disk Scan in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-check-disk-scan-in-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Here,**C:** refers to the drive where your operating system is installed. If your operating system resides on a different drive, change the command accordingly. Also, don't forget to enter the**"/f"** and**"/r"** parameters since these are needed to fix errors, locate bad sectors, and recover corrupted information.

 The CHKDSK scan has the greatest chance of adequately fixing the error under discussion. However, if it doesn't resolve the problem, you can move on to the next solution.

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on[recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on[how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and[start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or[Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

## Keep Annoying OneDrive Errors at Bay

 It can be very frustrating to encounter the "The tag present in the reparse point buffer is invalid" error when making changes to our files. If you apply the fixes in the article, hopefully, you'll be able to fix the error and reaccess your files. If nothing works, you can move it elsewhere and delete it from your primary drive.

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-transformative-techniques-for-zipping-into-subtitle-files/"><u>[New] 2024 Approved Transformative Techniques for Zipping Into Subtitle Files</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-navigating-the-world-of-giant-file-movement-between-iphone-and-macos/"><u>[Updated] 2024 Approved Navigating the World of Giant File Movement Between iPhone and macOS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-perfecting-your-dialogue-a-google-meet-strategy/"><u>[Updated] 2024 Approved Perfecting Your Dialogue A Google Meet Strategy</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-best-microphone-for-youtubers/"><u>[Updated] In 2024, Best Microphone for YouTubers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-farming-secrets-stardew-on-ginger-isles/"><u>2024 Approved Farming Secrets Stardew on Ginger Isles</u></a></li>
<li><a href="https://win11.techidaily.com/custom-monitoring-features-for-the-taskbar-on-pc/"><u>Custom Monitoring Features for the Taskbar on PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-efficiently-delete-unwanted-video-feedback-for-2024/"><u>How to Efficiently Delete Unwanted Video Feedback for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-d3d11-compatible-gpu-error-in-windows-1110/"><u>How to Fix the “D3D11-Compatible GPU” Error in Windows 11/10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-iphone-13-mini-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the iPhone 13 mini Without Previous Owner?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/master-the-meter-elevate-your-instagram-metrics-by-1kmnth-for-2024/"><u>Master the Meter Elevate Your Instagram Metrics by 1K/Mnth for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-lost-signals-from-phone-link-app-to-windows-system/"><u>Reinstating Lost Signals From Phone Link App to Windows System</u></a></li>
<li><a href="https://blog-min.techidaily.com/seamless-video-format-change-discover-digiartys-specialized-dvd-and-video-converter-solutions/"><u>Seamless Video Format Change: Discover Digiarty’s Specialized DVD and Video Converter Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-dual-camera-usage-in-competing-software/"><u>Stopping Dual Camera Usage in Competing Software</u></a></li>
<li><a href="https://win11.techidaily.com/the-legacy-explore-interface-guidebook/"><u>The Legacy Explore Interface Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/tying-your-systems-together-winpc-galaxy-interconnection/"><u>Tying Your Systems Together - WinPC, Galaxy Interconnection</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-fixing-defender-error-0x80004004/"><u>Understanding and Fixing Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-flawless-gaming-experience-in-sonic-games-windows-11s-fullscreen/"><u>Unlocking Flawless Gaming Experience in Sonic Games (Windows 11'S Fullscreen)</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-printer-mysteries-on-microsofts-windows-11/"><u>Unraveling Printer Mysteries on Microsoft's Windows 11</u></a></li>
</ul></div>

