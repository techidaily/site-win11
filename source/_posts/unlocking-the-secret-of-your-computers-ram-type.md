---
title: Unlocking the Secret of Your Computer's RAM Type
date: 2024-06-25T11:35:29.511Z
updated: 2024-06-26T11:35:29.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking the Secret of Your Computer's RAM Type
excerpt: This Article Describes Unlocking the Secret of Your Computer's RAM Type
keywords: RAM Guide,RAM Types Explained,Memory Configuration,Understanding RAM,CPU RAM Relationship,RAM Speed Optimization,System RAM Usage
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Unlocking the Secret of Your Computer's RAM Type

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/overcoming-setback-preserving-saving-functionality-of-nvidia-cp/"><u>Overcoming Setback: Preserving Saving Functionality of Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-navigation-of-files-with-gallery-on-pc/"><u>Efficient Navigation of Files with Gallery on PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-app-migration-tips-to-fix-windows-task-manager-positions/"><u>Avoid App Migration: Tips to Fix Windows Task Manager Positions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-code-4-spotify-error-on-w10w11-systems/"><u>Overcoming the Code 4 Spotify Error on W10/W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-stabilize-windows-configuration-app/"><u>Quick Fixes to Stabilize Windows Configuration App</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-sticky-note-access/"><u>Unlocking Windows 11 Sticky Note Access</u></a></li>
<li><a href="https://win11.techidaily.com/windows-customizable-spotlight-picture-guide/"><u>Windows Customizable Spotlight Picture Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-group-policy-settings-an-exploration-in-3-dimensions/"><u>Unraveling Windows Group Policy Settings: An Exploration in 3 Dimensions</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-iphone-vs-android-best-video-editing-apps-compared-for-2024/"><u>Updated IPhone vs Android Best Video Editing Apps Compared for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-htc-u23-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from HTC U23.</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-savor-the-viral-tiktoks-culinary-hitslist/"><u>[New] In 2024, Savor the Viral  TikTok's Culinary Hitslist</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-the-best-7-tiktok-instruments-to-increase-your-view-count/"><u>[Updated] 2024 Approved  The Best 7 TikTok Instruments to Increase Your View Count</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-iphone-x-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock iPhone X</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-zte-blade-a73-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On ZTE Blade A73 5G</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/varied-and-eye-catching-vlog-discussion-points-for-2024/"><u>Varied and Eye-Catching Vlog Discussion Points for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-path-to-precision-audio-starting-with-an-adobe-auditions-fade-in/"><u>In 2024, The Path to Precision Audio  Starting with an Adobe Audition's Fade In</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-acoustic-architects-building-with-mac-studios-for-2024/"><u>[Updated] Acoustic Architects  Building with Mac Studios for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>