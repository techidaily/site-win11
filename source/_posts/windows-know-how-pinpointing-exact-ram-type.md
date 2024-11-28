---
title: "Windows Know-How: Pinpointing Exact RAM Type"
date: 2024-11-22T21:38:52.610Z
updated: 2024-11-28T04:04:34.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Know-How: Pinpointing Exact RAM Type"
excerpt: "This Article Describes Windows Know-How: Pinpointing Exact RAM Type"
keywords: Windows RAM Guide,RAM Identification Tips,RAM Types for Windows,Finding Right RAM,Optimal Windows Memory,Pinpointing RAM Type,Exact Window RAM
thumbnail: https://thmb.techidaily.com/c62b5284641027dfddd7dff7e86c9bcc06523e51b87668f0c388f2d39f0ecdca.jpg
---

## Windows Know-How: Pinpointing Exact RAM Type

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-conquered-by-creatives-from-wmm-to-a-stellar-vimeo-presence-for-2024/"><u>[New] Conquered By Creatives From WMM to a Stellar Vimeo Presence for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-latest-evolution-2023s-samsung-bd-j5900-review/"><u>2024 Approved The Latest Evolution 2023'S Samsung BD-J5900 Review</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/dark-souls-evocative-sibling-a-detailed-look-at-bloodborne/"><u>Dark Souls' Evocative Sibling - A Detailed Look at Bloodborne</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-correcting-windows-0x80072af9-mistake/"><u>Decoding and Correcting Windows' 0X80072AF9 Mistake</u></a></li>
<li><a href="https://media-tips.techidaily.com/easy-methods-for-converting-flv-files-into-wav-format/"><u>Easy Methods for Converting FLV Files Into WAV Format</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-buyers-with-ai-at-microsofts-digital-marketplace/"><u>Empowering Buyers with AI at Microsoft's Digital Marketplace</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-nokia-g22-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Nokia G22? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-with-widget-features-in-win11-os/"><u>How to Engage With Widget Features in Win11 OS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-pixel-powerhouse-expert-review-on-top-8k-tv-models/"><u>In 2024, Pixel Powerhouse Expert Review on Top 8K TV Models</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-protocol-for-spotting-system-intrusions/"><u>Personalized Protocol for Spotting System Intrusions</u></a></li>
<li><a href="https://fox-http.techidaily.com/real-time-broadcast-at-your-fingertips-12-channels/"><u>Real-Time Broadcast at Your Fingertips - 12 Channels</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/refining-your-digital-footprint-editing-the-look-back-feature-for-2024/"><u>Refining Your Digital Footprint Editing the Look Back Feature for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/secure-graphics-integrity-win-11s-dxgi-solutions/"><u>Secure Graphics Integrity: Win 11'S DXGI Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-bypassing-windows-11-lock-in-minutes/"><u>Tricks for Bypassing Windows 11 Lock in Minutes</u></a></li>
</ul></div>

