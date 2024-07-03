---
title: Utilizing Terminal in Quake Mode on Windows
date: 2024-06-25T11:24:12.213Z
updated: 2024-06-26T11:24:12.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Utilizing Terminal in Quake Mode on Windows
excerpt: This Article Describes Utilizing Terminal in Quake Mode on Windows
keywords: Win Terminal Quick Access,Quake Mode Usage,Terminal Command Line,Windows CLI Tooling,PowerShell Alternative,Script Execution Window,OSX Terminal Clone (Not Fitting, but for Context),Windows Terminal Quake,Quick Terminal Access,Command Line Interface,CLI PowerShell Tool,Terminal Batch Mode,OS X Terminal Equivalent (Adjusted for Context)
thumbnail: https://thmb.techidaily.com/1d7a3c5b577ddb7940a6a2457c0bee5c40f1807e21452ed2f6065cb51e5a9f16.jpg
---

## Utilizing Terminal in Quake Mode on Windows

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some[classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

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

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have[disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

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
<li><a href="https://win11.techidaily.com/fast-track-tips-for-discovering-computer-gpu-make/"><u>Fast-Track Tips for Discovering Computer GPU Make</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-trembling-cursor-a-guide-to-windows/"><u>Stop the Trembling Cursor: A Guide to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-no-fingerprint-detection-error-on-windows/"><u>Overcoming the No Fingerprint Detection Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xbox-live-games-access-failures-on-windows-os/"><u>Troubleshooting: Xbox Live Games Access Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-mending-deskanywhere-on-windows-11/"><u>Methods for Mending DeskAnywhere on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-enrich-video-narrative-with-slow-motion-on-iphone/"><u>[New] Enrich Video Narrative with Slow Motion on iPhone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-edit-mp4-videos-like-a-pro-top-10-free-tools/"><u>Updated In 2024, Edit MP4 Videos Like a Pro Top 10 Free Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/premium-list-10-budget-friendly-picture-storage-vaults-for-2024/"><u>Premium List  10 Budget-Friendly Picture Storage Vaults for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-v27e-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo V27e</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-apple-iphone-6-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 6 Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-breaking-down-8-common-blunders-in-early-stage-youtube-success/"><u>[Updated] In 2024, Breaking Down 8 Common Blunders in Early-Stage YouTube Success</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/subtitle-extraction-top-10-free-apps-rated-for-2024/"><u>Subtitle Extraction  Top 10 Free Apps Rated for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/examining-vidma-as-a-video-recorder-for-screens-for-2024/"><u>Examining Vidma as a Video Recorder for Screens for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/prime-list-best-free-video-transcript-harvesters/"><u>Prime List  Best Free Video Transcript Harvesters</u></a></li>
</ul></div>
