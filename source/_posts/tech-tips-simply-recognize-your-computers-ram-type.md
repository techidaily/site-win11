---
title: "Tech Tips: Simply Recognize Your Computer's RAM Type"
date: 2024-06-25T11:34:04.884Z
updated: 2024-06-26T11:34:04.884Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Tips: Simply Recognize Your Computer's RAM Type"
excerpt: "This Article Describes Tech Tips: Simply Recognize Your Computer's RAM Type"
keywords: RAM Basics,Identify RAM,RAM Types,Tech Tricks,Understand RAM,Memory Know-How,PC Specs Guide
thumbnail: https://thmb.techidaily.com/6612d7a6b7e8b44ce845a24c9c71af5e69ea9f37b5bedb688c03953f127445f3.jpg
---

## Tech Tips: Simply Recognize Your Computer's RAM Type

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
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-offline-setup-path-of-win11/"><u>Navigating the Offline Setup Path of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-dilemma-is-removing-pagefilesys-advisable/"><u>Deletion Dilemma: Is Removing Pagefile.sys Advisable?</u></a></li>
<li><a href="https://win11.techidaily.com/facing-browser-blockades-top-tactics-to-reach-sites-on-your-system/"><u>Facing Browser Blockades: Top Tactics to Reach Sites on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-how-inauthentic-affection-impacts-your-feeds-credibility/"><u>[New] In 2024, How Inauthentic Affection Impacts Your Feed's Credibility</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-face-flaunting-visual-guidebook/"><u>[New] Face Flaunting Visual Guidebook</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-desktop-video-capture-best-practices-and-tools/"><u>[Updated] Desktop Video Capture  Best Practices & Tools</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/strategies-to-optimize-time-and-quality-in-thumbnail-design-for-2024/"><u>Strategies to Optimize Time and Quality in Thumbnail Design for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-oneplus-open-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your OnePlus Open to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-engagement-youtube-insights-for-timing/"><u>[New] In 2024, Elevate Engagement  Youtube Insights for Timing</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-iphone-se-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The iPhone SE SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-tips-for-higher-youtube-traction-with-persistent-creative-commons-usage/"><u>2024 Approved  Tips for Higher YouTube Traction with Persistent Creative Commons Usage</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-innovation-in-visuals-a-guide-to-the-leading-5-monitors-for-2024/"><u>[Updated] Innovation in Visuals  A Guide to the Leading 5 Monitors for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>