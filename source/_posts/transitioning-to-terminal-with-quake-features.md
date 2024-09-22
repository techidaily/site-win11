---
title: Transitioning to Terminal with Quake Features
date: 2024-09-16T00:00:56.784Z
updated: 2024-09-21T19:59:35.043Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transitioning to Terminal with Quake Features
excerpt: This Article Describes Transitioning to Terminal with Quake Features
keywords: Terminal QA Features,Quake Terminal Update,Terminal Enhancements,Advanced Terminal Tools,Quake Interface Upgrade,Modern Terminal Experience,Improved Terminal Functions
thumbnail: https://thmb.techidaily.com/4708f3ad86d66e7ad10dd3b75bdecccf20aa6cf32be5cc5adbe8d57734cb7714.jpg
---

## Transitioning to Terminal with Quake Features

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the[Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-master-iphone-timelapses-efficient-recording-tips-for-2024/"><u>[New] Master iPhone Timelapses Efficient Recording Tips for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exclusive-directory-free-visual-content-oasis-online/"><u>2024 Approved Exclusive Directory Free Visual Content Oasis Online</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-record-ruckus-samsung-phone-gaming-chronicles/"><u>2024 Approved Record Ruckus Samsung Phone Gaming Chronicles</u></a></li>
<li><a href="https://activate-lock.techidaily.com/4-things-you-must-know-about-apple-iphone-14-activation-lock-by-drfone-ios/"><u>4 Things You Must Know About Apple iPhone 14 Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ultimate-selection-of-5-acapella-sites-for-free-tunes-perfect-for-dj-playlists/"><u>Discover the Ultimate Selection of 5 Acapella Sites for Free Tunes Perfect for DJ Playlists</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-for-asus-webcam-display-glitches-on-windows-10-systems/"><u>DIY Fixes for ASUS Webcam Display Glitches on Windows 10 Systems</u></a></li>
<li><a href="https://network-issues.techidaily.com/dousing-display-disruptions-in-pro-7/"><u>Dousing Display Disruptions in Pro 7</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-to-setting-up-the-ultimate-loonatics/"><u>Easy Guide to Setting Up the Ultimate LooNatics</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-setting-up-your-vizio-tv-for-optimal-usb-movie-playback-performance/"><u>Easy Guide: Setting Up Your Vizio TV For Optimal USB Movie Playback Performance</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-dvd-viewing-a-step-by-step-guide-to-using-a-pc-dvd-player/"><u>Effortless DVD Viewing: A Step-by-Step Guide to Using a PC DVD Player</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-guide-solving-iphone-mov-file-playback-issues-and-troubleshooting-tips/"><u>Effortless Guide: Solving iPhone MOV File Playback Issues & Troubleshooting Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-poco-c55-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Poco C55 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-ultimate-method-to-seamless-integration-of-linktree-into-tiktok-profiles/"><u>In 2024, The Ultimate Method to Seamless Integration of Linktree Into TikTok Profiles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/magix-acid-pro-review-a-look-at-similar-programs/"><u>Magix ACID Pro Review A Look at Similar Programs</u></a></li>
</ul></div>

