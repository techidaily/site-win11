---
title: "Unveiling the Art of Size Calculation: PowerShell Ways"
date: 2024-08-08T13:21:47.921Z
updated: 2024-08-09T13:21:47.921Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Art of Size Calculation: PowerShell Ways"
excerpt: "This Article Describes Unveiling the Art of Size Calculation: PowerShell Ways"
keywords: PS Size Calc Tips,PowerShell Dimensions,PSSize Compute Guide,Windows Shell Measure,Scripted Size Estimation,PWCalculate Volume,Advanced Size Math
thumbnail: https://thmb.techidaily.com/7d60bd83471ce3aad62f7e36543b04c731bcd80b3b2e4d4cbbcd899202078565.jpg
---

## Unveiling the Art of Size Calculation: PowerShell Ways

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## How to Calculate a Folder's Size Using PowerShell on Windows

![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

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

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Get the Subfolder Size Using PowerShell

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-affordable-minecraft-video-graphics/"><u>[New] 2024 Approved  Affordable Minecraft Video Graphics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-your-channels-aesthetics-free-banners-available/"><u>[Updated] 2024 Approved  Elevate Your Channel's Aesthetics - Free Banners Available</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-double-your-watch-time-on-youtube-with-these-tips-for-2024/"><u>[Updated] Double Your Watch Time on YouTube with These Tips for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-maximizing-mobile-video-quality-in-tweets/"><u>[Updated] In 2024, Maximizing Mobile Video Quality in Tweets</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-instagram-video-sharing-tips/"><u>[Updated] Instagram Video Sharing Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-lost-video-steps-to-fix-sony-a6400-problem/"><u>[Updated] Lost Video  Steps to Fix Sony A6400 Problem</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-mario-vs-donkey-kong-the-ultimate-switch-fighting-series-for-2024/"><u>[Updated] Mario Vs. Donkey Kong  The Ultimate Switch Fighting Series for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-master-the-art-of-sound-alteration-on-sony-games-for-2024/"><u>[Updated] Master the Art of Sound Alteration on Sony Games for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-efficient-video-marketing-incorporating-timestamps-effectively/"><u>2024 Approved  Efficient Video Marketing  Incorporating Timestamps Effectively</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-still-to-dynamic-the-xs-action-camera-unboxed/"><u>2024 Approved  From Still to Dynamic  The XS Action Camera Unboxed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-nows-vr-tech-landscape/"><u>2024 Approved  Now’s VR Tech Landscape</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streamlining-your-youtube-editing-with-imovie-tools/"><u>2024 Approved  Streamlining Your YouTube Editing with iMovie Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-hues-handbook-theory-meets-technique/"><u>2024 Approved  Ultimate Hues Handbook  Theory Meets Technique</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-selection-of-economical-4k-projection-screens/"><u>2024 Approved  Ultimate Selection of Economical 4K Projection Screens</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unravel-the-mystery-perfect-your-green-screen-skills-using-kinemaster/"><u>2024 Approved  Unravel the Mystery  Perfect Your Green Screen Skills Using Kinemaster</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/decoding-the-secrets-of-youtubes-content-hub-for-2024/"><u>Decoding the Secrets of YouTube's Content Hub for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-hdr-visualization-with-windows-11/"><u>Dive Deep Into HDR Visualization with Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-corsair-keyboard-software-and-drivers-for-windows-free-and-secure/"><u>Download Corsair Keyboard Software & Drivers for Windows - Free and Secure</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-steps-for-resolving-audio-glitches-in-presentation-software/"><u>Easy Steps for Resolving Audio Glitches in Presentation Software</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhancing-obs-on-a-thrifty-computer-for-2024/"><u>Enhancing OBS on a Thrifty Computer for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-connection-issue-on-windows-os/"><u>Fixing No Connection Issue on Windows OS</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-nokia-c22-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Nokia C22 FRP Bypass Instantly</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-discover-the-potential-of-screencastify-recorder/"><u>In 2024, Discover the Potential of Screencastify Recorder</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-infinix-smart-7-hd-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Infinix Smart 7 HD Location Settings | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-xiaomi-13t-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unveiling-2023s-most-efficient-tools-for-fb-lite-videos-download/"><u>In 2024, Unveiling 2023'S Most Efficient Tools for FB Lite Videos Download</u></a></li>
<li><a href="https://win11.techidaily.com/installation-triumph-fixed-mspm-in-windows-10/"><u>Installation Triumph: Fixed MSPM in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winservicesexe-a-comprehensive-guide/"><u>Mastering Winservices.exe: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/masterpieces-in-film-script-writing-by-genre-for-2024/"><u>Masterpieces in Film Script Writing, By Genre for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-5ghz-connection-in-windows-11-effective-fixes-here/"><u>Reintroduce Missing 5GHz Connection in Windows 11: Effective Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-prepare-win11-in-vmware-17-player/"><u>Step-by-Step Guide to Prepare Win11 in VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/superior-non-zoom-virtual-collaboration-options-for-2024/"><u>Superior Non-Zoom Virtual Collaboration Options for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/syncing-visuals-and-soundtracks-in-video-magic/"><u>Syncing Visuals & Soundtracks in Video Magic</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-process-of-android-video-u-turns-for-2024/"><u>The Process of Android Video U-Turns for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-concept-of-online-streaming-television-sets/"><u>Unraveling the Concept of Online Streaming Television Sets</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-free-software-optimal-and-safe-options/"><u>Win-Friendly Free Software: Optimal and Safe Options</u></a></li>
<li><a href="https://win11.techidaily.com/windows-a-deep-dive-into-data-consumption-patterns/"><u>Windows: A Deep Dive Into Data Consumption Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-contribution-to-linux-user-growth/"><u>WSL Contribution to Linux User Growth</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>