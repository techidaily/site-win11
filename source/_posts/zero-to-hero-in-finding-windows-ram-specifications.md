---
title: Zero to Hero in Finding Windows RAM Specifications
date: 2024-09-11T09:40:22.413Z
updated: 2024-09-12T09:40:22.413Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Zero to Hero in Finding Windows RAM Specifications
excerpt: This Article Describes Zero to Hero in Finding Windows RAM Specifications
keywords: Windows RAM Specs,RAM Identification Guide,RAM Details Window,Identify Windows Memory,Memory Specification Windows,Windows RAM Configuration,Find Windows RAM Model
thumbnail: https://thmb.techidaily.com/2a48b2247fe4fccf62c26b321b73686dd63d342e88315635def6454749492ddb.jpg
---

## Zero to Hero in Finding Windows RAM Specifications

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
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

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115929/19272" target="_top" id="2115929">
  <img src="//a.impactradius-go.com/display-ad/19272-2115929" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115929/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-crafting-seamless-visuals-with-instagrams-chroma-key-for-2024/"><u>[New] Crafting Seamless Visuals with Instagram's Chroma Key for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-becoming-a-wise-trader-top-video-tutorials/"><u>[Updated] Becoming a Wise Trader Top Video Tutorials</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-avoid-piracy-safe-youtube-to-mp4-conversion-tips/"><u>[Updated] In 2024, Avoid Piracy Safe YouTube to MP4 Conversion Tips</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-visionarys-list-the-finest-26-video-to-text-converters-available/"><u>[Updated] The Visionary’s List The Finest 26 Video-to-Text Converters Available</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-tips-for-a-secure-youtube-identity-check/"><u>2024 Approved Tips for a Secure YouTube Identity Check</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-simplified-your-companion-for-w11-transitioning/"><u>DevHome Simplified: Your Companion for W11 Transitioning</u></a></li>
<li><a href="https://win11.techidaily.com/direct-guide-square-windows-interface/"><u>Direct Guide: Square Windows' Interface</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-guide-to-downloading-and-installing-hp-laserjet-1320-printer-driver-for-windows/"><u>Easy Guide to Downloading & Installing HP LaserJet 1320 Printer Driver for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-how-to-make-uwp-app-shortcuts/"><u>Enhancing Windows 11: How to Make UWP App Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-operation-failed-code-0x0000011b-on-win11/"><u>Eradicating Operation Failed Code 0X0000011B on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-converter-software-list/"><u>Essential Windows Converter Software List</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-photovideo-loss-in-windows-camera-app/"><u>Fixing Photo/Video Loss in Windows Camera App</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-realme-c67-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-check-for-updates-context-menu-option-in-windows-10-and-11/"><u>How to Add a Check for Updates Context Menu Option in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-if-your-storage-disk-is-hdd-or-ssd-on-windows/"><u>How to Check if Your Storage Disk Is HDD or SSD on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-grant-read-permission-on-hidden-outlook-directories-and-files/"><u>How to Grant Read Permission on Hidden Outlook Directories & Files</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pro-techniques-for-professional-iphone-shots/"><u>In 2024, Pro Techniques for Professional Iphone Shots</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-increasing-indoor-ambiance-via-sunlight/"><u>In 2024, The Art of Increasing Indoor Ambiance via Sunlight</u></a></li>
<li><a href="https://win11.techidaily.com/innovating-cleanup-generative-erase-revolutionizes-windows/"><u>Innovating Cleanup: Generative Erase Revolutionizes Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-chrome-notification-suppression-windows/"><u>Mastering Chrome Notification Suppression, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-imessage-for-windows-a-step-by-step-guide/"><u>Mastering iMessage for Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fixes-for-unsuccessful-windows-upgrades/"><u>Mastering the Fixes for Unsuccessful Windows Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-with-microsofts-copilot-key-insights/"><u>Mastering Windows 11 with Microsoft's Copilot Key Insights</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-without-microsofts-core-tools-for-win-11/"><u>Mastery Without Microsoft's Core Tools for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-file-system-failures-a-guide-to-fixes-in-win11/"><u>Navigating File System Failures: A Guide to Fixes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-settings-hyper-v-onoff-tutorial/"><u>Navigating Windows 11'S Settings: Hyper-V On/Off Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-gear-usage-a-guide-to-windows-widgets/"><u>Navigating Your Gear Usage: A Guide to Windows Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/preservation-of-windows-safescreensaver-integrity/"><u>Preservation of Windows SafeScreensaver Integrity</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-7-cameras-elevating-virtual-event-coverage-and-vlogging/"><u>Prime 7 Cameras Elevating Virtual Event Coverage and Vlogging</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-overcoming-windows-10-bsod-issues/"><u>Quick Guide: Overcoming Windows 10 BSOD Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unresponsive-snip-tools-shortcuts/"><u>Resolving Unresponsive Snip Tools Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-windows-11-defender-trail-easy-steps-to-take/"><u>Revamp Your Windows 11 Defender Trail: Easy Steps to Take</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-microsoft-meeting-screen/"><u>Reviving Your Microsoft Meeting Screen</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-win11-screensaver-exceptions-easily/"><u>Sidestep WIN11 Screensaver Exceptions Easily</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-lost-network-access-on-windows-pc/"><u>Steps to Regain Lost Network Access on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-re-associate-file-applications-in-win108/"><u>Strategies to Re-Associate File Applications in Win10/8</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-samsung-galaxy-a14-4g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Samsung Galaxy A14 4G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand!</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-solving-defenders-0x80004004-problem/"><u>Unraveling and Solving Defender's 0X80004004 Problem</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-of-geforce-error-x0001-in-windows-os/"><u>Unraveling the Cause of GeForce Error X0001 in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unsafe-synthetic-methods-for-windows-11-key-creation/"><u>Unsafe Synthetic Methods for Windows 11 Key Creation</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-hidden-controls-for-taskbar-time/"><u>Unveiling the Hidden Controls for Taskbar Time</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-security-tool-canary-channel/"><u>Unveiling Windows' Security Tool: Canary Channel</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-surface-devices-firmware-edition-explained/"><u>Upgrading Surface Devices: Firmware Edition Explained</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    