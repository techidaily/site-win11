---
title: Resolving Windows' Extract Error 1152
date: 2024-10-09T22:59:13.250Z
updated: 2024-10-15T19:19:44.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows' Extract Error 1152
excerpt: This Article Describes Resolving Windows' Extract Error 1152
keywords: Fix Windows Extract Error,Resolve WinError 1152,Overcome Windows Unpack Failure,Stop WinExtract Problems,Address Windows File Extraction Issue,Correct WinZip Error 1152,Avoid Windows Extract Error 1152
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Resolving Windows' Extract Error 1152

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.

4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  
![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.
6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install the Windows Software You Need Again

 There aren’t that many confirmed resolutions for error 1152\. However, the ones covered here have worked for many users who’ve needed to fix that Windows software installation issue.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-expert-setup-guide-to-capture-high-quality-video-using-logitech-camera/"><u>[New] In 2024, Expert Setup Guide to Capture High-Quality Video Using Logitech Camera</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-how-to-ensure-accurate-game-saves-with-fbx-recorder/"><u>[New] In 2024, How to Ensure Accurate Game Saves with FBX Recorder</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-optimal-choices-for-endless-data-preservation/"><u>[Updated] 2024 Approved Optimal Choices for Endless Data Preservation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-beginners-tutorial-on-nintendo-switch-screenshotting-and-sharing-techniques/"><u>A Beginner's Tutorial on Nintendo Switch Screenshotting & Sharing Techniques</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-review-of-hp-chromebook-11-blending-academics-workloads-and-leisure-seamlessly/"><u>Comprehensive Review of HP Chromebook 11: Blending Academics, Workloads, and Leisure Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-audio-error-xc00d36b4-in-win10-and-11/"><u>Eliminating Audio Error XC00D36B4 in Win10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-user-experience-optimizing-windows-pins/"><u>Enhance User Experience: Optimizing Windows PINs</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-efficiently-undoing-changes-with-system-restore/"><u>Expert Tips for Efficiently Undoing Changes with System Restore</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mp4-movies-with-samsung-galaxy-xcover-7-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Failed to play MP4 movies with Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Samsung Galaxy S23 Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-google-maps-a-windows-users-manual/"><u>Integrating Google Maps: A Windows User's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-iomap64sys-blue-screen-in-win108/"><u>Mastering Fixes for IOMap64.sys Blue Screen in Win10/8</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-graphics-driver-updates-for-amd-windows-11/"><u>Navigating the Maze of Graphics Driver Updates for AMD, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-microsoft-teams-experience-navigating-through-windows-error-80080300/"><u>Seamless Microsoft Teams Experience: Navigating Through Windows Error 80080300</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-ui-module-failure-in-steam-client/"><u>Tackling Steam UI Module Failure in Steam Client</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-web-control-panel/"><u>Unlocking Windows 11'S Web Control Panel</u></a></li>
</ul></div>

