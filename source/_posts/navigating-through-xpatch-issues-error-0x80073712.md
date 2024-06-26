---
title: "Navigating Through XPatch Issues: Error 0X80073712"
date: 2024-06-25T11:32:14.542Z
updated: 2024-06-26T11:32:14.542Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through XPatch Issues: Error 0X80073712"
excerpt: "This Article Describes Navigating Through XPatch Issues: Error 0X80073712"
keywords: XPatch Fix #0X80073712,XPatch Error Code 0X80073712,Overcoming XPatch Error 73712,Resolve XPatch 0X73712 Error,XPatch Issue #0X80073712,Fixing Xpatch Error 73712,XPatch Problem 0X80073712 Solution
thumbnail: https://thmb.techidaily.com/bd1f3164b21938808543fb77a181f9a976b01572cf9b49cfe1852edc61f82d53.jpg
---

## Navigating Through XPatch Issues: Error 0X80073712

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to[launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning[how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as[SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.


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
<li><a href="https://win11.techidaily.com/winning-fps-tools-the-top-6-counter-app-picks/"><u>Winning FPS Tools: The Top 6 Counter App Picks</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-service-failure-in-windows-11/"><u>Troubleshooting Steam Service Failure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-windows-update-failure-0x800f0845/"><u>Dealing with Windows Update Failure - 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-window-brighter-controls-the-ultimate-guide-for-multiscreen-enthusiasts/"><u>Top 6 Window Brighter Controls: The Ultimate Guide for Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/team-meeting-screens-not-showing-up/"><u>Team Meeting Screens Not Showing Up?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-decoding-the-impact-of-instagrams-algorithm-shifts/"><u>2024 Approved  Decoding the Impact of Instagram's Algorithm Shifts</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-tecno-spark-10c-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Tecno Spark 10C?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-prime-7-media-gatherers-on-fb/"><u>[Updated] Prime 7 Media Gatherers on FB</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-explore-the-best-kept-secret-7-premium-transition-sounds-available-for-download/"><u>New In 2024, Explore the Best-Kept Secret 7 Premium Transition Sounds Available for Download</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-from-simple-to-sophisticated-weaving-multiple-images-into-your-insta-story/"><u>In 2024, From Simple to Sophisticated  Weaving Multiple Images Into Your Insta Story</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-list-of-preferred-linux-audio-recorders-and-how-to-make-the-most-out-of-your-sessions/"><u>Updated The Ultimate List of Preferred Linux Audio Recorders and How to Make the Most Out of Your Sessions</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-tapping-into-built-in-screen-recording-features-of-huaweis-mate-and-p-lineup/"><u>[Updated] 2024 Approved  Tapping Into Built-In Screen Recording Features of Huawei's Mate & P Lineup</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-elevate-your-profile-picture-game-with-these-high-end-online-services/"><u>[New] In 2024, Elevate Your Profile Picture Game with These High-End Online Services</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-8-plus-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On iPhone 8 Plus?</u></a></li>
</ul></div>
