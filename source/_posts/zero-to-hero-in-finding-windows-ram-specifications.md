---
title: Zero to Hero in Finding Windows RAM Specifications
date: 2024-09-15T05:58:37.664Z
updated: 2024-09-17T06:17:44.477Z
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

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/ed-effortless-income-estimations-for-youtubers/"><u>[Updated] Effortless Income Estimations for YouTubers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-conquer-the-crowd-reach-your-goal-of-1k-insta-admirers-monthly/"><u>[Updated] In 2024, Conquer the Crowd Reach Your Goal of 1K Insta Admirers Monthly</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-peeling-the-onion-understanding-instagram-story-audiences-for-2024/"><u>[Updated] Peeling the Onion Understanding Instagram Story Audiences for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-game-on-in-reality-the-ultimate-vr-headset-comparison/"><u>2024 Approved Game On in Reality The Ultimate VR Headset Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/complete-guide-downloading-entire-albums-from-youtube-successfully/"><u>Complete Guide: Downloading Entire Albums From YouTube Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-premier-video-editing-tools-top-5-pc-compatible-video-mergers-unveiled/"><u>Discover the Premier Video Editing Tools: Top 5 PC-Compatible Video Mergers Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/easy-tutorial-capturing-conversations-from-slack-for-windowsmac-and-iosandroid-devices/"><u>Easy Tutorial: Capturing Conversations From Slack for Windows/Mac and iOS/Android Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-methods-to-modify-text-casing-in-microsoft-excel-2013-with-built-in-formulae/"><u>Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-add-a-pcmcia-adapter-to-your-computer-using-windows-quick-and-effective-tutorials/"><u>Effortlessly Add a PCMCIA Adapter to Your Computer Using Windows – Quick & Effective Tutorials!</u></a></li>
<li><a href="https://win11.techidaily.com/flacitunesmp3/"><u>FLAC形式からiTunes対応のMP3への完全ガイド変換</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-take-off-or-change-a-cell-phones-protective-glass-screen/"><u>How to Take Off or Change a Cell Phone's Protective Glass Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-canva-10-best-practices-unveiled/"><u>Mastering Canva 10 Best Practices Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/optimizing-windows-11-expert-techniques-for-seamless-device-driver-updates-via-revouninstaller-software/"><u>Optimizing Windows 11: Expert Techniques for Seamless Device Driver Updates via RevoUninstaller Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/what-is-instagram-story-highlight-for-2024/"><u>What Is Instagram Story Highlight for 2024</u></a></li>
</ul></div>

