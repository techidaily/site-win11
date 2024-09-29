---
title: Mastering the Art of Calculating Storage Space via Windows Powershell
date: 2024-09-24T19:38:52.288Z
updated: 2024-09-28T21:51:40.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Calculating Storage Space via Windows Powershell
excerpt: This Article Describes Mastering the Art of Calculating Storage Space via Windows Powershell
keywords: WinPowershellStorageCalc,StorageSpaceWindows,WindowsStoragePS,SpaceCalculationWin,PowerShellStorageTech,EfficientSpaceWin,WindowsOptimizeSpace
thumbnail: https://thmb.techidaily.com/7190f701d24b2bca2702a5bcd803eaeb74415822adafed338c6c5049f6c7aefb.jpg
---

## Mastering the Art of Calculating Storage Space via Windows Powershell

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## How to Get the Subfolder Size Using PowerShell

![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-srs-mastery-innovative-conversion-techniques/"><u>[New] 2024 Approved SRS Mastery Innovative Conversion Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionizing-the-music-creation-process-through-magix-mentor-x/"><u>[New] Revolutionizing the Music Creation Process Through Magix Mentor X</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-nokia-130-music-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-blueprint-for-effortless-youtube-video-posting-on-fb/"><u>2024'S Blueprint for Effortless YouTube Video Posting on FB</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-activate-windows-calculator/"><u>A Step-by-Step Walkthrough: Activate Window's Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-profile-alerts-on-windows-1011/"><u>Addressing Invalid Profile Alerts on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-obscured-windows-11-query-engine/"><u>Awakening Obscured Windows 11 Query Engine</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-mastering-the-search-function-of-windows-11/"><u>Boost Productivity: Mastering the Search Function of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-administration-local-groups-and-users/"><u>Boosting Windows Administration: Local Groups and Users</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-update-autopilot-hurdles/"><u>Breaking Down Windows Update Autopilot Hurdles</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 On Apple iPhone 15 Pro</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-realme-11-proplus-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Realme 11 Pro+ to Mac? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prime-filters-for-smooth-streaming-sessions/"><u>In 2024, Prime Filters for Smooth Streaming Sessions</u></a></li>
<li><a href="https://extra-support.techidaily.com/inside-the-studio-how-magix-video-pro-x-simplifies-production-for-2024/"><u>Inside the Studio How Magix Video Pro X Simplifies Production for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719290483430-quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-techniques-building-animation-with-movie-maker-for-2024/"><u>Step-by-Step Techniques Building Animation with Movie Maker for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    