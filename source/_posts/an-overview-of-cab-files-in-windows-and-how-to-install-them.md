---
title: An Overview of CAB Files in Windows and How to Install Them
date: 2024-07-13T11:21:56.360Z
updated: 2024-07-14T11:21:56.360Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes An Overview of CAB Files in Windows and How to Install Them
excerpt: This Article Describes An Overview of CAB Files in Windows and How to Install Them
keywords: WinCAB Files Guide,CAB File Basics,CAB Installation Steps,CAB Utility Tools,Managing CAB Archives,Extracting WinCAB Content,Windows Diagnostic Toolkit
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## An Overview of CAB Files in Windows and How to Install Them

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

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

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-creator-to-critic-evaluating-video-value-across-platforms/"><u>[New] In 2024, From Creator to Critic  Evaluating Video Value Across Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-vmwares-failed-to-start-the-virtual-machine-error-in-windows-11/"><u>9 Ways to Fix VMware's Failed to Start the Virtual Machine Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-gaming-setup-with-fast-valorant-loading/"><u>Accelerate Your Gaming Setup with Fast Valorant Loading</u></a></li>
<li><a href="https://win11.techidaily.com/1719369975560-break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now</u></a></li>
<li><a href="https://win11.techidaily.com/7-innovative-uses-for-windows-11-god-mode/"><u>7 Innovative Uses for Windows 11 God Mode</u></a></li>
<li><a href="https://win11.techidaily.com/7-annoying-wins-windows-11s-design-dissonance/"><u>7 Annoying Wins: Windows 11'S Design Dissonance</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-master-your-most-watched-videos-on-fb-today-and-beyond-2023/"><u>[New] Master Your Most-Watched Videos on FB Today & Beyond 2023</u></a></li>
<li><a href="https://win11.techidaily.com/1719345925022-the-forgotten-tools-of-windows-11-dont-miss-them/"><u>The Forgotten Tools of Windows 11 - Don’t Miss Them</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-overcoming-wwe-2k23-freezes-in-windows/"><u>Accelerated Action: Overcoming WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/storystitcher-compelling-collage-for-instagram-users-for-2024/"><u>StoryStitcher  Compelling Collage for Instagram Users for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-unleash-your-creativity-top-14-video-editing-software-for-vloggers/"><u>New Unleash Your Creativity Top 14 Video Editing Software for Vloggers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-clean-audio-clear-conscience-how-to-remove-background-noise-in-fcpx/"><u>New 2024 Approved Clean Audio, Clear Conscience How to Remove Background Noise in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-on-using-w11s-automated-hdr-feature/"><u>A Complete Guide on Using W11's Automated HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/5-ingenious-cmd-puzzles-to-perplex-and-pleasure/"><u>5 Ingenious CMD Puzzles to Perplex and Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tasks-high-speed-windows-autoclickers/"><u>Accelerate Tasks: High-Speed Windows Autoclickers</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-chloe-miller/"><u>A Compre Written by Chloe Miller</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-outlook-performance-in-windows/"><u>Accelerate Outlook Performance in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-top-android-video-editing-apps-for-cinematic-creations/"><u>Updated In 2024, Top Android Video Editing Apps for Cinematic Creations</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-repair-the-net-framework-on-windows/"><u>5 Ways to Repair the .NET Framework on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-steam-download-rates-overcoming-sluggish-pace/"><u>Accelerate Steam Download Rates: Overcoming Sluggish Pace</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hdr-on-your-desk-a-windows-guide-to-color-mastery/"><u>[Updated] HDR on Your Desk  A Windows Guide to Color Mastery</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokémon Go Cooldown Chart On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/"><u>A Guide to Quickly Opens Sticky Notes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-twelve-days-of-windows-11-christmas-guide/"><u>A Twelve Days of Windows 11 Christmas Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-audience-augmentation-made-simple-5-solutions-available/"><u>[Updated] 2024 Approved  Audience Augmentation Made Simple - $5 Solutions Available</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719382719080-optimal-start-menu-no-commercials-here/"><u>Optimal Start Menu: No Commercials Here</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-at-dxvks-impact-on-windows-gaming/"><u>A Closer Look at DXVK's Impact on Windows Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-users-guide-for-web-site-app-conversion/"><u>A Windows User's Guide for Web Site App Conversion</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-step-by-step-reposting-on-instagram/"><u>2024 Approved  Step-by-Step Reposting on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/1719362597425-navigating-networked-notebooks-effortless-file-sharing-with-c/"><u>Navigating Networked Notebooks: Effortless File Sharing with C:</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-hdr-on-windows-11/"><u>A Complete Guide to HDR on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-buyers-blueprint-essential-steps-for-your-win-pc-purchase/"><u>A Buyer’s Blueprint: Essential Steps for Your Win PC Purchase</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-steps-for-windows-hello-fingerprint-woes/"><u>9 Essential Steps for Windows Hello Fingerprint Woes</u></a></li>
<li><a href="https://win11.techidaily.com/8-easy-ways-to-unlock-windows-screen-setup-problems/"><u>8 Easy Ways to Unlock Windows Screen Setup Problems</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-reading-qr-codes-with-windows-os/"><u>A Deeper Dive Into Reading QR Codes with Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/a-developers-journey-github-desktop-in-the-era-of-win-11/"><u>A Developer's Journey: GitHub Desktop in the Era of Win 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-unlock-iphone-13-mini-without-passcode-or-face-id-by-drfone-ios/"><u>3 Ways to Unlock iPhone 13 mini without Passcode or Face ID</u></a></li>
</ul></div>
