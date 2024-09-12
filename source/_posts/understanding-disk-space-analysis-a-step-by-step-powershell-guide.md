---
title: "Understanding Disk Space Analysis: A Step-by-Step PowerShell Guide"
date: 2024-09-11T09:40:07.378Z
updated: 2024-09-12T09:40:07.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Understanding Disk Space Analysis: A Step-by-Step PowerShell Guide"
excerpt: "This Article Describes Understanding Disk Space Analysis: A Step-by-Step PowerShell Guide"
keywords: DiskSpacePowerShellGuide,PowerShellDiskAnalysis,StorageManagementPS,DriveSpaceInsightPS,SpaceCheckScriptPS,DiskAnalyzeToolPS,StorageOptimizePS
thumbnail: https://thmb.techidaily.com/8eeffb0e6f2c9998156198f379aca60dcf8cc0a8121a8e9ad6701616d8eaae16.jpg
---

## Understanding Disk Space Analysis: A Step-by-Step PowerShell Guide

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Calculate a Folder's Size Using PowerShell on Windows

![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To calculate a folder's size, you'll need to use the two PowerShell cmdlets, Get-ChildItem and Measure-Object, followed by the Length property and Sum parameter.

 The cmdlet Get-ChildItem lets you retrieve information from a specified directory and its sub-directories. The Measure-Object cmdlet and the associated properties and parameters calculate the sum of the length property for the items returned by the Get-ChildItem (alias 'cgi') cmdlet.

 If you are new to PowerShell, you may want to read our explainer on [essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to understand the basics of PowerShell.

 Now that you are familiar with the PowerShell commands, here is how to use them to get any folder size.

1. Press the **Win** key and type **powershell**.
2. Next, right-click on **Windows PowerShell** and select **Run as administrator**. Click **Yes** if prompted by **User Account Control**.
3. In the PowerShell window, type the following command:  
`Get-ChildItem FolderPath | Measure-Object -Property Length -sum`
4. In the above command, replace **FolderPath** with the directory path where your folder is saved. For example, if you want to calculate the size of the Download folder located in the **E:\\** drive, then the full command will look like this:  
`Get-ChildItem E:\Download | Measure-Object -Property Length -sum`
5. The return will show the item count in the folder and its size in bytes. You'll need to divide the total sum by **1024** to get the size in **KBs** (Kilobytes). Divide it by **1024** again to get the size in **MBs** (Megabytes) and so on.

 Alternatively, you can use the .sum property to retrieve the total size and divide it by 1 million or billion to convert it into megabytes or gigabytes.

![powershell cmdlet to view folder size megabytes gigabytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-megabytes-gigabytes.jpg)

 For example, if you want to know the value in gigabytes (MBs), type the following command and press **Enter**:

`(gci E:\Download | measure Length -s).sum / 1Mb`

 Similarly, replace **1Mb** with **1Gb** to retrieve the folder size in gigabytes.

`(gci E:\Download | measure Length -s).sum / 1Gb`

 If you want to identify the size of specific types of files in a directory, you can use the wildcard character **\*** followed by the file extension type. It will only show the file size for the specified file type.

 For example, to find how much space is taken by the images in a folder, use the following command:

![powershell cmdlet to view folder by file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-by-file-type.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

## How to Get the Subfolder Size Using PowerShell

![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  
`$targetfolder = 'C:\'  
$dataColl = Get-ChildItem -Force $targetfolder -Directory -ErrorAction SilentlyContinue | ForEach-Object {  
   $len = Get-ChildItem -Recurse -Force $_.FullName -File -ErrorAction SilentlyContinue | Measure-Object -Property Length -Sum | Select-Object -ExpandProperty Sum  
   $foldername = $_.FullName  
   $foldersize = '{0:N2} GB' -f ($len / 1Gb)  
   [PSCustomObject]@{  
       foldername = $foldername  
       foldersizeGb = $foldersize  
   }  
}  
$dataColl | Out-GridView -Title "Size of Subdirectories in $targetfolder"`
3. Next, click **Run Script** or press **F5** and wait for the script to execute. Depending on the folder size, you'll see a "**Size Of Subdirectories**" dialog listing all the subdirectories with their size.

 In addition to this, you can make use of the PowerShell comparison operators to filter results. For example, to get file size for folders created between June 2023 and July 2023, you can use the following command:

`(gci -force E:\Download &ndash;Recurse -ErrorAction SilentlyContinue | ? {$_.CreationTime -gt '01/23/23' -AND $_.CreationTime -lt '02/23/23'}| measure Length -s).sum / 1Gb`

 In the above command, **"?"** is an alias for the **Where-Object** cmdlet, **\-gt, -AND, -It** are comparison operators, and **CreationTime** is a condition. The command checks if the CreationTime of files in the subdirectory falls within the specified date range and shows output only if the condition is satisfied. If you get an error, ensure your date and time format in the command matches the system's format and try again.

## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-how-to-embed-a-youtube-playlist-on-a-website/"><u>[New] In 2024, How to Embed A YouTube Playlist On a Website</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-leveraging-alternative-footage-in-filmmaking/"><u>[Updated] In 2024, Leveraging Alternative Footage in Filmmaking</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-quick-intro-to-instagram-video-chat-for-2024/"><u>[Updated] Quick Intro to Instagram Video Chat for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-affordable-storage-solutions-top-30-free-services-with-massive-1tbplus-space-capacity/"><u>2024 Approved Affordable Storage Solutions Top 30 Free Services with Massive (1TB+) Space Capacity</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-oppo-a79-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-nokia-c32-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Nokia C32 without App | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-in-class-steadicam-equipment-for-drone-cinematography-for-2024/"><u>Best-in-Class Steadicam Equipment for Drone Cinematography for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-hot-40-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Hot 40</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-overcoming-usb-not-recognized-error-in-virtualbox/"><u>Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-microsoft-store-issue-x80073d26-on-win11/"><u>Correcting Microsoft Store Issue X:80073d26 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-microsoft-store-error-code-0x80073d26/"><u>Deciphering and Fixing Microsoft Store Error Code 0X80073D26</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-top-tech-picks-and-reviews-a-look-into-toms-hardware-insights/"><u>Discover Top Tech Picks and Reviews: A Look Into Tom's Hardware Insights</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-workflow-on-windows-the-best-apps-for-maximum-output/"><u>Elevate Workflow on Windows: The Best Apps for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-printer-use-in-defender-smartscreen-on-edge-browser/"><u>Enabling Printer Use in Defender SmartScreen on Edge Browser</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-value-of-the-samsung-galaxy-tab-s3-in-todays-market/"><u>Exploring the Value of the Samsung Galaxy Tab S3 in Today's Market</u></a></li>
<li><a href="https://win11.techidaily.com/file-resurrection-made-simple-8-methods-for-windows-users/"><u>File Resurrection Made Simple: 8 Methods for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zerodxgierordevicehung-in-win11-systems/"><u>Fixing ZeroDXGIErorDeviceHung in Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-windows-index-adjustment-steps/"><u>Guide: Windows Index Adjustment Steps</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-high-speeds-across-devices/"><u>Harmonizing High Speeds Across Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-bluetooth-pin-related-connectivity-issues-in-win11win10/"><u>How To Bypass Bluetooth Pin-Related Connectivity Issues in Win11/Win10</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>How To Pause Life360 Location Sharing For Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-vivo-y27-5g-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Vivo Y27 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-no-drivers-error-during-installation/"><u>How to Resolve Windows No Drivers Error During Installation</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-oneplus-ace-2-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our OnePlus Ace 2 Phone Screen?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-oneplus-ace-2-by-drfone-android/"><u>In 2024, How to Bypass FRP from OnePlus Ace 2?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a79-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A79 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/madden-nfl-20-pc-version-stability-issues-solved-here/"><u>Madden NFL 20 PC Version Stability Issues Solved Here!</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-in-it-support-with-troubleshooters-shortcut-guide/"><u>Maximize Efficiency in IT Support with Troubleshooters Shortcut Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/microsoft-word-made-affordable-tips-for-finding-and-using-the-software-at-no-expense/"><u>Microsoft Word Made Affordable: Tips for Finding and Using the Software at No Expense</u></a></li>
<li><a href="https://win11.techidaily.com/missed-sd-card-display-how-to-locate-it-in-explorer/"><u>Missed SD Card Display: How to Locate It in Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-a-fresh-approach-to-admin-rights-on-windows-os/"><u>Pioneering a Fresh Approach to Admin Rights on Windows OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-connection-issues-making-itunes-and-finder-recognize-your-iphone/"><u>Solving Connection Issues: Making iTunes & Finder Recognize Your iPhone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-problem-of-unresponsive-headset-connections-on-a-windows-10-pc/"><u>Solving the Problem of Unresponsive Headset Connections on a Windows 10 PC</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-access-to-commands-setting-up-keybinds-effortlessly/"><u>Speedy Access to Commands: Setting up Keybinds Effortlessly</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-solution-overcoming-connection-dropped-issues-on-escape-from-tarkov-server/"><u>Step-by-Step Solution: Overcoming 'Connection Dropped' Issues on Escape From Tarkov Server</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-samsung-galaxy-m54-5g-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Samsung Galaxy M54 5G FRP</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-pc-name-error-in-win11/"><u>Steps to Resolve PC Name Error in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/synchronizing-qbittorrent-settings-between-multiple-windows-systems/"><u>Synchronizing qBittorrent Settings Between Multiple Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-utorrent-download-interruptions-on-pcs/"><u>Tackling uTorrent Download Interruptions on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-correctly-printing-from-microsoft-powerpoint-in-windows/"><u>The Ultimate Guide to Correctly Printing From Microsoft PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-stealthy-login-silencing-security-prompts-in-windows-11/"><u>Tricks for Stealthy Login: Silencing Security Prompts in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-fixing-rainbow-six-siege-launch-problems/"><u>Troubleshooting Guide: Fixing Rainbow Six Siege Launch Problems</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/ultimate-examination-unveiling-the-360-camera-wonders-for-2024/"><u>Ultimate Examination Unveiling the 360 Camera Wonders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-recent-activities-on-windows-os/"><u>Uncovering Recent Activities on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-should-prefer-windows-11-over-macos/"><u>Why You Should Prefer Windows 11 over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-disk-management-a-comprehensive-walkthrough/"><u>Win 10/11 Disk Management: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-inside-the-settings-experience/"><u>Windows 11: Inside the Settings Experience</u></a></li>
<li><a href="https://win11.techidaily.com/workaround-strategies-overcoming-banned-app-error-in-os/"><u>Workaround Strategies: Overcoming Banned App Error in OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    