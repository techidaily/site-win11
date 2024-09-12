---
title: Unlocking Disk Space Insights via PowerShell Scripts
date: 2024-09-11T09:30:05.295Z
updated: 2024-09-12T09:30:05.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Disk Space Insights via PowerShell Scripts
excerpt: This Article Describes Unlocking Disk Space Insights via PowerShell Scripts
keywords: PowerShell Disk Cleanup,Optimize Storage PowerShell,Extract Disk Usage Data,Automate Space Management PS,Efficient Drive Freeing Tools,Analyze System Storage Insight,Streamline SSD Space Handling
thumbnail: https://thmb.techidaily.com/52f8da45eabd9e84edabed13a325d84ff2b39dca8fb87ff4960ee8bff73c07e4.jpg
---

## Unlocking Disk Space Insights via PowerShell Scripts

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Calculate a Folder's Size Using PowerShell on Windows

![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
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

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get the Subfolder Size Using PowerShell

![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-navigating-zoom-chats-a-guide-to-effective-online-interactions/"><u>[New] In 2024, Navigating Zoom Chats  A Guide to Effective Online Interactions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-smooth-video-in-every-shot-prime-mobile-cameras-with-ois/"><u>[New] Smooth Video in Every Shot  Prime Mobile Cameras With OIS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-optimize-your-watch-time-on-instagram-videos/"><u>[Updated] 2024 Approved  Optimize Your Watch Time on Instagram Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-elevate-your-content-game-mastering-the-art-of-instagram-video-uploads-on-desktop/"><u>[Updated] Elevate Your Content Game  Mastering the Art of Instagram Video Uploads on Desktop</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-conclusion-to-your-youtube-journey/"><u>[Updated] The Ultimate Conclusion to Your YouTube Journey</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-unsung-heros-guide-to-tiktok-live-participation-for-2024/"><u>[Updated] The Unsung Hero's Guide to TikTok Live Participation for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-pro-level-strategies-for-saving-and-recording-movs-on-windows-pcs/"><u>2024 Approved  Pro-Level Strategies for Saving and Recording MOVs on Windows PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/all-about-apple-iphone-13-pro-unlock-chip-you-need-to-know-by-drfone-ios/"><u>All About Apple iPhone 13 Pro Unlock Chip You Need to Know</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-auto-tracking-cameras-for-2024/"><u>Best Auto Tracking Cameras for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/compatibility-crusade-four-key-windows-troubleshooters/"><u>Compatibility Crusade: Four Key Windows Troubleshooters</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-non-start-issue-for-windows-speech-recognition/"><u>Correcting the Non-Start Issue for Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-windows-11s-0x0000011b-operational-error/"><u>Decoding and Fixing Windows 11'S 0X0000011B Operational Error</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-battlenet-application-on-windows-pc/"><u>Fixing Unresponsive Battle.net Application on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11-anydesk-errors/"><u>Fixing Windows 11 AnyDesk Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-gateway-3-steps-to-direct-folder-entry-on-pc/"><u>Game Gateway: 3 Steps to Direct Folder Entry on PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-conceal-dim-display-feature-in-win-os-control-panel/"><u>Guide to Conceal Dim Display Feature in Win OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-parent-controls-on-microsoft-windows-11/"><u>Guide to Parent Controls on Microsoft Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-realme-12-pro-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Realme 12 Pro 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-random-console-window-flashes/"><u>How to Prevent Random Console Window Flashes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-ispoofer-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-motorola-g24-power-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Motorola G24 Power to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-crafting-seamless-tiktok-videos-through-stitching/"><u>In 2024, Crafting Seamless TikTok Videos Through Stitching</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-from-apple-iphone-15-pro-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code From Apple iPhone 15 Pro in the Best Ways</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-proven-winners-selecting-the-best-hdr-cameras/"><u>In 2024, Proven Winners  Selecting the Best HDR Cameras</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-secrets-revealed-a-detailed-look-at-google-podcasting/"><u>In 2024, Secrets Revealed  A Detailed Look at Google Podcasting</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-ultimate-guide-to-rapid-video-trimming-on-mac-updated-2023/"><u>In 2024, The Ultimate Guide to Rapid Video Trimming on Mac (Updated 2023)</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-5ghz-connection-not-appearing-in-windows-11-try-these-7-fixes/"><u>Is Your 5GHz Connection Not Appearing in Windows 11? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/is-yourphoneexe-a-threat-tips-for-windows-108-users/"><u>Is YourPhone.exe a Threat? Tips for Windows 10/8 Users</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-latest-features-for-taskbar-in-win11/"><u>Leveraging Latest Features for Taskbar in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-error-0x80070522-in-windows-privileges-restoration-guide/"><u>Navigating Error 0X80070522 in Windows: Privileges Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/photo-perfect-camouranage-integrating-files-into-images/"><u>Photo-Perfect Camouranage: Integrating Files Into Images</u></a></li>
<li><a href="https://win11.techidaily.com/premium-choices-top-windows-platforms-for-dsswitch-experience/"><u>Premium Choices: Top Windows Platforms for DS/Switch Experience</u></a></li>
<li><a href="https://win11.techidaily.com/quickly-fix-crashing-file-explorers-on-up-to-date-windows-11/"><u>Quickly Fix Crashing File Explorers on Up-to-Date Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rediscover-lost-control-panel-configurations-in-win11/"><u>Rediscover Lost Control Panel Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-non-existent-camera-issue-in-windows-device-hub/"><u>Resolve Non-Existent Camera Issue in Windows Device Hub</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-missing-links-to-shared-windows-sites/"><u>Resurrect Missing Links to Shared Windows Sites</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-11-shutdown-process/"><u>Strategies to Extend Windows 11 Shutdown Process</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-reveal-hidden-taskbar-icons/"><u>Strategies to Reveal Hidden Taskbar Icons</u></a></li>
<li><a href="https://win11.techidaily.com/superior-tools-replacing-windows-snipping-feature-in-various-oses/"><u>Superior Tools Replacing Windows' Snipping Feature in Various OSes</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-clock-and-dates-windows-1011-guide/"><u>Tailor Your Clock and Dates: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-mind-maps-organizing-notes-using-obsidian-canvas/"><u>The Art of Mind Maps: Organizing Notes Using Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-for-efficient-browsing-ram-friendly-windows-applications-ranked/"><u>The Quest for Efficient Browsing: RAM-Friendly Windows Applications Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-smooth-gameplay-better-frame-rates-in-roblox-win/"><u>Tips for Smooth Gameplay: Better Frame Rates in Roblox Win</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-no-cost-performance-boosters-to-enhance-windows-vehicles/"><u>Top 5 No-Cost Performance Boosters to Enhance Windows Vehicles</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-the-evolution-what-is-google-hangouts/"><u>Understanding the Evolution: What Is Google Hangouts?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-your-win11-status-key-indicators-and-checks-for-uptime/"><u>Understanding Your Win11 Status: Key Indicators and Checks for Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-fixed-recovering-non-functional-win-apps/"><u>Unleash the Power of Fixed: Recovering Non-Functional Win-Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-webcam-visibility-alerts-in-win11/"><u>Unlocking Webcam Visibility Alerts in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-win11s-five-privacy-snooping-techniques/"><u>Unveiling Win11's Five Privacy Snooping Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/windows-canary-explained-start-your-journey/"><u>Windows Canary Explained: Start Your Journey</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>