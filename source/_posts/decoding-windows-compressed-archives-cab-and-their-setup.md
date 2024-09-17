---
title: Decoding Windows Compressed Archives (CAB) & Their Setup
date: 2024-09-11T17:29:54.238Z
updated: 2024-09-16T19:00:48.889Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding Windows Compressed Archives (CAB) & Their Setup
excerpt: This Article Describes Decoding Windows Compressed Archives (CAB) & Their Setup
keywords: CAB Archive Decoding,Windows Compression Analysis,Cab Format Unpacking,Archiving on Windows,CAB File Extraction,Data Compression in Windows,Windows Decompressed Files
thumbnail: https://thmb.techidaily.com/cbd55a60b36d243580c486b7896cd6baf0fe5a1c6ab330fc24fdad62a19d7e96.jpeg
---

## Decoding Windows Compressed Archives (CAB) & Their Setup

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
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-best-of-the-best-8-cameras-for-top-streaming-experience/"><u>[New] Best of the Best 8 Cameras for Top Streaming Experience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-detailed-methodology-to-masterboard-use-in-desktopiosandroid-zoom-sessions/"><u>[New] Detailed Methodology to Masterboard Use in Desktop/iOS/Android Zoom Sessions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-strategic-tips-to-enhance-your-gmeet-ppt-presentations-on-mobilelaptop-for-2024/"><u>[Updated] Strategic Tips to Enhance Your GMeet PPT Presentations on Mobile/Laptop for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-solo-stream-smoothness-hacks-for-seamless-live-broadcasts/"><u>2024 Approved Solo Stream Smoothness Hacks for Seamless Live Broadcasts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/choosing-your-stage-obs-or-twitch-pro/"><u>Choosing Your Stage OBS or Twitch Pro</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-speech-failure-at-launch-point/"><u>Correcting Windows Speech Failure at Launch Point</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/face-forward-comparing-apple-and-samsungs-face-detection-capabilities-for-2024/"><u>Face Forward Comparing Apple and Samsung's Face-Detection Capabilities for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-facebook-video-downloader-application-for-mobilewinmac/"><u>In 2024, Facebook Video Downloader Application for Mobile/Win/Mac</u></a></li>
<li><a href="https://win11.techidaily.com/reconnecting-with-confidence-top-7-tactics-to-address-windows-errors/"><u>Reconnecting with Confidence: Top 7 Tactics to Address Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/solving-resource-occupied-message-on-windows-devices-153-chars/"><u>Solving Resource Occupied Message on Windows Devices (153 Chars)</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-issue-when-deathloop-game-crashes-or-stops-responding/"><u>Solving the Issue: When Deathloop Game Crashes or Stops Responding</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/straightforward-strategies-for-recording-games/"><u>Straightforward Strategies for Recording Games</u></a></li>
<li><a href="https://win11.techidaily.com/why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    