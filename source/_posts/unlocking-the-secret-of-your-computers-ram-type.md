---
title: Unlocking the Secret of Your Computer's RAM Type
date: 2024-06-25T10:23:33.615Z
updated: 2024-06-26T10:23:33.615Z
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
<li><a href="https://win11.techidaily.com/detailed-procedure-for-total-disabling-of-windows-subsystem/"><u>Detailed Procedure for Total Disabling of Windows Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-stability-solutions-for-recurring-crashes/"><u>Windows UI Stability: Solutions for Recurring Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-persistent-ps4-controller-connections-in-windows/"><u>Strategies for Persistent PS4 Controller Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-program-conflicts-the-four-step-fix/"><u>Decoding Program Conflicts: The Four-Step Fix</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-3-in-nvidia-opengl-win10-and-11/"><u>Eliminating Error Code 3 in NVIDIA OpenGL (Win10 & 11)</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-unveiling-hidden-gems-essential-tricks-for-win11/"><u>In 2024, Unveiling Hidden Gems  Essential Tricks for Win11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-critical-insight-into-recmeisters-video-capture-efficacy-for-2024/"><u>[New] Critical Insight Into Recmeister's Video Capture Efficacy for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-pixel-perfect-calculating-the-ideal-screen-ratio/"><u>Updated In 2024, Pixel Perfect Calculating the Ideal Screen Ratio</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-zoom-setup-ensuring-smooth-video-conferencing-for-2024/"><u>The Art of Zoom Setup  Ensuring Smooth Video Conferencing for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-the-ultimate-guide-to-avs-video-editor-review-and-tutorial/"><u>New In 2024, The Ultimate Guide to AVS Video Editor Review and Tutorial</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-step-by-step-process-to-shoot-with-a-fisheye-lens/"><u>[New] In 2024, Step-by-Step Process to Shoot with a Fisheye Lens</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-6-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-cutting-through-the-noise-final-cut-pro-vs-lumafusion-for-video-creators-for-2024/"><u>New Cutting Through the Noise Final Cut Pro vs LumaFusion for Video Creators for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-apple-iphone-8-could-not-be-activatedreached-issue-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 8 Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-disabling-push-notifications-for-commercial-content/"><u>[New] In 2024, Disabling Push Notifications for Commercial Content</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>