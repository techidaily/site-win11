---
title: Leveraging the Potential of PowerShell for Storage Sizing
date: 2024-10-17T08:54:46.598Z
updated: 2024-10-21T00:52:46.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging the Potential of PowerShell for Storage Sizing
excerpt: This Article Describes Leveraging the Potential of PowerShell for Storage Sizing
keywords: PowerShell Storage Size Optimization,PS Sizing Strategy Guide,Efficient Storage with PowerShell,PowerShell Storage Management,Automating Server Capacity,Storage Planning Using PowerShell,Dynamic Storage Sizing with Powershell
thumbnail: https://thmb.techidaily.com/45a1f9697d2bdeb16116c56d8bb656d37d6c88757987caf5e6bad0d2243c55f0.jpg
---

## Leveraging the Potential of PowerShell for Storage Sizing

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get the Subfolder Size Using PowerShell

![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-perfecting-slow-motion-cinematography-for-social-media-engagement-on-instagram/"><u>[New] In 2024, Perfecting Slow Motion Cinematography for Social Media Engagement on Instagram</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-3d-lut-design-techniques/"><u>[New] Unveiling 3D LUT Design Techniques</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-whimseypixels-mememakerspace-for-2024/"><u>[New] WhimseyPixels MemeMakerSpace for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-advice-downloading-editing-and-personalizing-whatsapp-tones-for-both-platforms/"><u>[Updated] Expert Advice Downloading, Editing & Personalizing WhatsApp Tones for Both Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-access-10-fast-methods-to-control-center/"><u>Accelerate Access: 10 Fast Methods to Control Center</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-block-of-microsoft-store-in-windows-11/"><u>Disabling Block of Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-or-displaying-time-win-1011-tutorial/"><u>Disguising or Displaying Time: Win 10/11 Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-correct-file-or-device-path-unavailable-on-pc-with-windows/"><u>Easy Steps to Correct File or Device Path Unavailable on PC With Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/exclusive-collection-vimeo-video-clippers/"><u>Exclusive Collection Vimeo Video Clippers</u></a></li>
<li><a href="https://facebook.techidaily.com/instructions-wipe-your-facebook-activity-trail/"><u>Instructions: Wipe Your Facebook Activity Trail</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-cutting-down-cpu-load-on-windows-hosts/"><u>Mastery of Cutting Down CPU Load on Windows Hosts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-cinematic-soundscapes-techniques-for-retrieving-audio-from-videos-for-2024/"><u>New Cinematic Soundscapes Techniques for Retrieving Audio From Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-to-reality-efficiently-launching-windows-11-from-scratch/"><u>Rewind to Reality: Efficiently Launching Windows 11 From Scratch</u></a></li>
<li><a href="https://win11.techidaily.com/skimming-through-complex-windows-update-issues-with-error-0x800736cc/"><u>Skimming Through Complex Windows Update Issues with Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-disable-your-it-admin-limited-access-warning/"><u>Solutions to Disable 'Your IT Admin Limited Access' Warning</u></a></li>
<li><a href="https://change-location.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/transition-mastery-in-cinematic-productions-with-kinemaster-for-2024/"><u>Transition Mastery in Cinematic Productions with Kinemaster for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-mobility-settings-quick-guide-win-11/"><u>Turn Off Windows Mobility Settings Quick Guide (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-precision-ditch-delays-top-fixes-for-bf2-players/"><u>Unleash Precision, Ditch Delays: Top Fixes for BF2 Players</u></a></li>
</ul></div>

