---
title: Demystifying Windows Compressed Archive (CAB) Installation
date: 2024-10-09T18:22:10.088Z
updated: 2024-10-15T20:01:08.308Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Windows Compressed Archive (CAB) Installation
excerpt: This Article Describes Demystifying Windows Compressed Archive (CAB) Installation
keywords: CAB Installs Clarity,WinZip Extract Basics,Cabfile Decompression,CAB File Unpacking,Windows Compress Files,Archive Install Guide,CAB Format Understanding
thumbnail: https://thmb.techidaily.com/7ec641d0887205acbcfc6836f03618d0eee863811c5fb186d0f0c958e752d87a.jpg
---

## Demystifying Windows Compressed Archive (CAB) Installation

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is a Windows CAB File?

 A CAB file or Cabinet file is a common archive file format used by Microsoft. It contains the compressed version of different files, folders, and even other cabinet files. Microsoft uses these files to distribute Windows, drivers, and UWP app updates. However, you can also use it to store other forms of data, such as images, videos, and documents.

 A CAB file is compressed using the Microsoft Cabinets Compression Format (MCF), which ensures that you can easily decompress it without losing the data stored in it. It can also be signed with digital certificates, allowing to maintain the authenticity and integrity of the file.

 CAB files are recognized by their first four bytes, which are the [ASCII characters](https://www.makeuseof.com/what-is-ascii-text/) MSCF. You can store up to 65,535 folders in a CAB file, with each folder having a storage capacity of 65,535 files.

 Now that you have a brief understanding of CAB files, let's check out how you can install it on Windows 11\.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043596/7443" target="_top" id="2043596">
  <img src="//a.impactradius-go.com/display-ad/7443-2043596" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043596/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Install a CAB File on Windows 11

 You can easily install a CAB file on Windows 11 using Command Prompt and Windows PowerShell. In the Command Prompt method, you'll have to use the [DISM command](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/). Whereas, in the PowerShell method, you'll use the Add-WindowsPackage command.

 Here's how to install a CAB file using Command Prompt.

1. Navigate to the CAB file location on your computer.
2. Right-click the CAB file, and choose **Copy as path**.  
![Copy as path option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/copy-as-path-option.jpg)
3. Press **Win** key to open the **Start Menu**, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
4. In the elevated Command Prompt window, type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`dism /Online /Add-Package /PackagePath:"CAB location"`  
![CMD window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cmd-window.jpg)

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)

 That's it. PowerShell will install the content of the CAB file on your computer.

## How to Install Driver Updates From a CAB File

 If you have downloaded a driver update, which is a CAB file, you can install it using the following instructions:

1. Double-click the CAB file to view its contents.
2. Press **Ctrl + A** to select all the files, right-click, and choose **Extract**.  
![Extract option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/extract-option.jpg)
3. Choose the location where you want to extract the contents of the CAB file and click **Extract**.
4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
6. Click **Browse my computer for drivers**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-the-ultra-30-action-cameras-by-garmin-in-depth-analysis/"><u>[New] In 2024, The Ultra 30 Action Cameras by Garmin - In Depth Analysis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-step-by-step-saving-tweet-vids-on-androids/"><u>[Updated] 2024 Approved Step-By-Step Saving Tweet Vids on Androids</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-samsung-galaxy-a34-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Samsung Galaxy A34 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/beginners-manual-activating-your-new-meta-oculus-quest-or-quest-2-gear/"><u>Beginner's Manual: Activating Your New Meta (Oculus) Quest or Quest 2 Gear</u></a></li>
<li><a href="https://win-amazing.techidaily.com/epson-wf-3620-driver-download-and-update-for-windows-1087/"><u>Epson WF-3620 Driver Download & Update for Windows 10/8/7</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-repairing-windows-11s-erroneous-camera-app/"><u>Guide to Repairing Windows 11'S Erroneous Camera App</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-master-privacy-unveil-faces-less-clearly/"><u>In 2024, Master Privacy Unveil Faces Less Clearly</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-mouse-top-10-ways-for-win11-users/"><u>Master Your Mouse: Top 10 Ways for Win11 Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-hdr-photography-your-essential-list/"><u>Mastering HDR Photography Your Essential List</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-delayed-iphone-text-message-issues-a-guide-with-9-effective-solutions/"><u>Solving Delayed iPhone Text Message Issues: A Guide with 9 Effective Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-compatibility-issues-of-your-windows-tablet-stylus/"><u>Streamlining Compatibility Issues of Your Windows Tablet Stylus</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-maintain-program-order-in-taskbar-list/"><u>Tips to Maintain Program Order in TaskBar List</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-potentials-windows-reliability-and-performance-metrics/"><u>Unseen Potentials: Windows' Reliability & Performance Metrics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    