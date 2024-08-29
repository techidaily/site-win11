---
title: Deciphering Folder Dimensions with PowerShell Scripts
date: 2024-08-28T00:56:45.447Z
updated: 2024-08-29T00:56:45.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Folder Dimensions with PowerShell Scripts
excerpt: This Article Describes Deciphering Folder Dimensions with PowerShell Scripts
keywords: PowerShell Folder Size,Scripted Folder Analysis,Dimension Measurement PS,Folder Length Calculation,PowerShell Data Extraction,Internal Folder Sizes,Folder Metrics via Scripts
thumbnail: https://thmb.techidaily.com/157145562d322ac42b18debf7cc17b6e328143a79a361dfc0ab65e3b0afbaf26.jpg
---

## Deciphering Folder Dimensions with PowerShell Scripts

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

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

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-immediate-color-correction-with-canons-paired-luts/"><u>[New] Immediate Color Correction with Canon's Paired LUTs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-crafting-your-dream-minecraft-house-with-ease/"><u>[New] In 2024, Crafting Your Dream Minecraft House with Ease</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-proven-subtitle-editors-the-comprehensive-top-10-list-online/"><u>[Updated] Proven Subtitle Editors – The Comprehensive Top 10 List (Online)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-teaching-techniques-with-youtube-a-practical-approach/"><u>[Updated] Teaching Techniques with YouTube  A Practical Approach</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-access-to-the-top-soundscape-archives/"><u>2024 Approved  Exclusive Access to the Top Soundscape Archives</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-minimizing-moments-edit-longer-videos-for-youtube/"><u>2024 Approved  Minimizing Moments  Edit Longer Videos for YouTube</u></a></li>
<li><a href="https://buynow-info.techidaily.com/coolpix-b500-a-failed-wi-fi-journey/"><u>COOLPIX B500: A Failed Wi-Fi Journey?</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/crafting-tales-leveraging-chatgpt-for-epic-narratives/"><u>Crafting Tales: Leveraging ChatGPT for Epic Narratives</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhanced-digital-engagement-with-cookiebot-technology/"><u>Enhanced Digital Engagement with Cookiebot Technology</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-ide-speed-and-productivity-for-developers-on-windows/"><u>Enhancing IDE Speed & Productivity for Developers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enlightening-windows-users-on-camera-memory-issues/"><u>Enlightening Windows Users on Camera Memory Issues</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-top-8-win11-choices-for-professional-videoscripting/"><u>Explore the Top 8 Win11 Choices for Professional Videoscripting</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-the-silence-how-to-restore-audio-in-roblox-on-windows-11-and-10/"><u>Fixing the Silence: How to Restore Audio in Roblox on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zero-x-error-in-windows-11s-mail-application/"><u>Fixing Zero X Error in Windows 11'S Mail Application</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-merge-adjacent-and-non-adjacent-partitions-in-windows/"><u>How to Merge Adjacent and Non-Adjacent Partitions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reconnect-disconnected-file-apps-in-windows/"><u>How to Reconnect Disconnected File Apps in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-layers-of-cinematic-dialogue-design/"><u>In 2024, Layers of Cinematic Dialogue Design</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-bloatware-removal-in-windows-11/"><u>Mastering Bloatware Removal in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-microsofts-phone-link-app-explained/"><u>Mastering Connectivity: Microsoft’s Phone Link App Explained</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-download-rates-for-epic-launcher/"><u>Mastering Fast Download Rates for Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-restore-on-windows-for-past-fixes/"><u>Navigating System Restore on Windows for Past Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-discord-setup-in-windows-11/"><u>Navigating Through Failed Discord Setup in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-flawed-menu-navigation-in-windows-desktops/"><u>Overcoming Flawed Menu Navigation in Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-overcoming-xbox-game-pass-warzones-directx-issues/"><u>Quick Fixes for Overcoming Xbox Game Pass Warzone's DirectX Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solution-conquer-camera-fails-in-windows-os/"><u>Quick Solution: Conquer Camera Fails in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-reconnecting-distant-devices-in-windows/"><u>Regaining Control: Reconnecting Distant Devices in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rtx-3080-game-stability-tips/"><u>RTX 3080 Game Stability Tips</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-cyber-travel-mastering-connections-on-windows-pc/"><u>Seamless Cyber Travel: Mastering Connections on Windows PC</u></a></li>
<li><a href="https://fox-direct.techidaily.com/strategies-for-enthralling-vlog-content-flow/"><u>Strategies for Enthralling Vlog Content Flow</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-11-logon-from-pin-to-password-a-step-by-step-guide/"><u>Switching Windows 11 Logon From PIN to Password: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-operation-failed-problem-on-pcs/"><u>Tackling the Operation Failed Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-functionalities-of-fn-keys-on-windows-11-devices/"><u>Tailoring Functionalities of FN Keys on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-finest-alternatives-to-microsofts-core-applications/"><u>The Finest Alternatives to Microsoft's Core Applications</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-integrity-in-the-windows-registry/"><u>The Ultimate Guide to Restoring Integrity in the Windows Registry</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-stopping-windows-11-security-guard/"><u>Tutorial: Stopping Windows 11 Security Guard</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-breakdown-how-to-pre-emptive-access-updates/"><u>ViVeTool Breakdown: How to Pre-Emptive Access Updates</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>