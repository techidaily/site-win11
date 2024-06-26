---
title: "The Essentials of Windows CAB Files: Purpose & Installation Tactics"
date: 2024-06-25T10:01:09.109Z
updated: 2024-06-26T10:01:09.109Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Essentials of Windows CAB Files: Purpose & Installation Tactics"
excerpt: "This Article Describes The Essentials of Windows CAB Files: Purpose & Installation Tactics"
keywords: Windows Cab Files Basics,Windows Extracts Guide,CAB File Functionality,Installing Windows CAB,CAB Install Strategies,Windows Compression Tools,System CAB Utilities
thumbnail: https://thmb.techidaily.com/a399a44beb5899ba48cdf59ba448623d828236f52b18cfdee70ac40508a6e091.jpg
---

## The Essentials of Windows CAB Files: Purpose & Installation Tactics

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/achieving-a-spotless-system-restart-in-windows-11/"><u>Achieving a Spotless System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-failed-volume-shadow-copy-in-windows-os/"><u>Solving Failed Volume Shadow Copy in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-windows-os-issues/"><u>Quick Guide to Resolving Common Windows OS Issues</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/from-easy-access-to-higher-security-transitioning-your-logon-method-on-windows-11/"><u>From Easy Access to Higher Security: Transitioning Your Logon Method on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clashing-cybersecurity-the-case-against-multiple-antiviruses-on-windows/"><u>Clashing Cybersecurity: The Case Against Multiple Antiviruses on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/6-risks-of-using-cheap-windows-activation-keys/"><u>6 Risks of Using Cheap Windows Activation Keys</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-captivating-crafts-trending-instagram-filters/"><u>[Updated] Captivating Crafts  Trending Instagram Filters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-your-go-to-for-epic-virtual-escapades/"><u>In 2024, Your Go-To for Epic Virtual Escapades</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-sifting-commentary-on-youtube/"><u>2024 Approved  Sifting Commentary on YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-unveiling-instagrams-videography-timeframe/"><u>[Updated] In 2024, Unveiling Instagram's Videography Timeframe</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-the-most-effective-pc-screen-capture-apps/"><u>[New] In 2024, The Ultimate Guide to the Most Effective PC Screen Capture Apps</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-max-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS Max With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-battlefield-geniuses-discovering-the-quintessential-7-total-war-experiences/"><u>2024 Approved  Battlefield Geniuses  Discovering the Quintessential 7 Total War Experiences</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pinnacle-photo-narrative-assembly-platform/"><u>[Updated] Pinnacle Photo Narrative Assembly Platform</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unlock-social-media-success-hashtag-utilization-on-instagram/"><u>In 2024, Unlock Social Media Success  Hashtag Utilization on Instagram</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>