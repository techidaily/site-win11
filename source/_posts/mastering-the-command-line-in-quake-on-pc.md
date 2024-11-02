---
title: Mastering the Command Line in Quake on PC
date: 2024-10-26T21:36:58.899Z
updated: 2024-11-01T16:52:58.310Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Command Line in Quake on PC
excerpt: This Article Describes Mastering the Command Line in Quake on PC
keywords: Command Line Mastery,Quake Game Console,PC Gaming Techniques,Linux Terminal Skills,Console Coding Basics,PC Game Development,Text-Based Gaming Guide
thumbnail: https://thmb.techidaily.com/d375bcd96d435c14a3e9a48edfb86d3a2995018c383247bac69b40f31de6e4df.jpg
---

## Mastering the Command Line in Quake on PC

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some[classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open[Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the[Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have[disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using the Windows Terminal's Quake Mode

 The Windows Terminal is a great way to work in command-line apps such as PowerShell and Windows Subsystem for Linux. Being able to run it in Quake mode means that you always have access to the terminal you need, no matter what you do on your PC.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-in-2024-the-screen-readers-digest-recorder-evaluation/"><u>[New] In 2024, The Screen Reader's Digest Recorder Evaluation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-enjoy-high-quality-pc-audio-recording-install-x-recorder/"><u>[Updated] 2024 Approved Enjoy High-Quality PC Audio Recording - Install X-Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-strategies-expert-methods-for-decoding-qr-codes-on-pcs/"><u>Breakthrough Strategies: Expert Methods for Decoding QR Codes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-onedrive-to-windows-microsoft-services/"><u>Bridging OneDrive to Windows Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-obstacles-fixing-microsoft-office-activation-issues/"><u>Bypassing Obstacles: Fixing Microsoft Office Activation Issues</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-camera-app-glitches-on-windows-11s-f429f-issue/"><u>Clearing Up Camera App Glitches on Windows 11'S F429F Issue</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-apple-watch-or-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How To Bypass Activation Lock On Apple Watch Or iPhone 15 Pro Max?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-toms-hardware-informed-reviews-for-savvy-gadget-enthusiasts/"><u>Navigating Tom's Hardware: Informed Reviews for Savvy Gadget Enthusiasts</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-5-best-mp4-video-editors-totally-free-for-2024/"><u>New Top 5 Best MP4 Video Editors Totally Free for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/rectifying-discrepancies-unexplained-websites-showing-up-in-iphones-screen-time-logs/"><u>Rectifying Discrepancies: Unexplained Websites Showing Up in iPhone's Screen Time Logs</u></a></li>
</ul></div>

