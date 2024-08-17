---
title: Unlocking the Secret of Your Computer's RAM Type
date: 2024-08-16T00:03:23.155Z
updated: 2024-08-17T00:03:23.155Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-crafting-facebook-videos-a-step-by-step-guide/"><u>[New] 2024 Approved  Crafting Facebook Videos  A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unleashing-creative-potential-with-instas-bokeh-effects/"><u>[New] 2024 Approved  Unleashing Creative Potential with Insta's Bokeh Effects</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-digital-recorder-snap-your-screen-upload-to-youtube-onlinepcmac/"><u>[Updated] 2024 Approved  Digital Recorder  Snap Your Screen, Upload to YouTube Online/PC/Mac</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-enhance-visibility-the-most-effective-30-freefire-tags-for-video-marketing/"><u>[Updated] 2024 Approved  Enhance Visibility  The Most Effective 30 FreeFire Tags for Video Marketing</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-9-key-approaches-to-free-webinar-archiving/"><u>[Updated] 9 Key Approaches to Free Webinar Archiving</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-apex-1-written-by-assistant/"><u>[Updated] Apex 1 Written by Assistant</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-activatedeactivate-pip-in-ios-web-experience/"><u>[Updated] How to Activate/Deactivate PIP in iOS Web Experience</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-process-how-to-setup-google-maps-on-pc/"><u>A Step-by-Step Process: How to Setup Google Maps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-lockout-duration-post-failed-logon/"><u>Altering Windows Lockout Duration Post-Failed Logon</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-user-interface-incorrante-windows-with-portables/"><u>Augmenting User Interface: Incorrante Windows with Portables</u></a></li>
<li><a href="https://win11.techidaily.com/boost-performance-and-efficiency-top-10-powertoys-applications/"><u>Boost Performance and Efficiency: Top 10 PowerToys Applications</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-your-computerenas-dark-background-issue/"><u>Brightening Your Computer'enas Dark Background Issue</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-conflicting-apps-in-windows-10/"><u>Dealing with 'Conflicting Apps' In Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/decode-widows-code-to-unfreeze-handbrake/"><u>Decode Widows' Code to Unfreeze HandBrake</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discover-11-secrets-of-windows-11/"><u>Discover 11 Secrets of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/drive-success-on-windows-1011-top-5-productivity-boosting-tools/"><u>Drive Success on Windows 10/11: Top 5 Productivity-Boosting Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-ralink-driver-download-and-update-tutorial-for-windows-users-resolved/"><u>Easy Ralink Driver Download & Update Tutorial for Windows Users - Resolved</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-icon-visibility-windows-11s-hidden-menus/"><u>Elevate Icon Visibility: Windows 11'S Hidden Menus</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-a-distraction-free-start-with-win-11/"><u>Embrace a Distraction-Free Start with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-key-collectors-deal-wintry-windows-11-priced-at-612-per-year/"><u>Exclusive Key Collector's Deal - Wintry Windows 11 Priced at $6.12 Per Year</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-connect-airpods-to-windows/"><u>Expert Tips to Connect AirPods to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-basic-to-winning-converting-batch-to-executable/"><u>From Basic to Winning: Converting Batch to Executable</u></a></li>
<li><a href="https://win11.techidaily.com/improve-performance-cutting-down-memory-demand-by-media-apps/"><u>Improve Performance: Cutting Down Memory Demand by Media Apps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-nokia-c22-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-playbox-app-user-testimonials/"><u>In 2024, PlayBox App User Testimonials</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-samsung-galaxy-f15-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Samsung Galaxy F15 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-on-screen-labels-and-descriptions-for-video-files-windows-11-for-2024/"><u>Mastering On-Screen Labels and Descriptions for Video Files (Windows 11) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mending-disconnected-google-drive-windows-filesystem/"><u>Mending Disconnected Google Drive Windows Filesystem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-recognition-failure-in-windows-installation/"><u>Overcoming Device Recognition Failure in Windows Installation</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-infinix-smart-7-hd-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Infinix Smart 7 HD</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-teamsters-crashes-on-windows-11-and-10-pcs/"><u>Preventing Teamsters Crashes on Windows 11 & 10 PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/sony-s6700-latest-features-reviewed-for-2024/"><u>Sony S6700  Latest Features Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/spruce-up-system-tray-with-custom-weather-icons-in-windows-11-desktop-bar/"><u>Spruce Up System Tray with Custom Weather Icons in Windows 11 Desktop Bar</u></a></li>
<li><a href="https://win11.techidaily.com/1719255130164-tackle-non-working-shift-with-simple-tweaks/"><u>Tackle Non-Working Shift with Simple Tweaks.</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-how-to-enhance-your-workflow-via-menus/"><u>The Blueprint: How to Enhance Your Workflow via Menus</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-compression-via-cli/"><u>The Essential Guide to File Compression via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-assembling-a-taskbar-on-windows-11-slate/"><u>The Ultimate Guide to Assembling a Taskbar on Windows 11 Slate</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-ultra-hd-marvel-on-apple-tv-4k-a-comprehensive-review-with-siri-integration-for-2prise/"><u>Unveiling the Ultra HD Marvel on Apple TV 4K - A Comprehensive Review with Siri Integration for 2Prise !</u></a></li>
<li><a href="https://win11.techidaily.com/window-terminal-design-your-own-palette/"><u>Window Terminal: Design Your Own Palette</u></a></li>
<li><a href="https://win11.techidaily.com/windows-edge-utility-sticking-email-alerts-on-the-taskbar/"><u>Windows Edge Utility: Sticking Email Alerts on the Taskbar</u></a></li>
</ul></div>
