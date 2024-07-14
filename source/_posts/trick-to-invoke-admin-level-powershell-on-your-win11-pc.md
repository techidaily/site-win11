---
title: Trick to Invoke Admin-Level PowerShell on Your Win11 PC
date: 2024-07-13T10:41:00.209Z
updated: 2024-07-14T10:41:00.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trick to Invoke Admin-Level PowerShell on Your Win11 PC
excerpt: This Article Describes Trick to Invoke Admin-Level PowerShell on Your Win11 PC
keywords: PowerShell Admin Access,Windows 11 Admin Commands,Gain PowerShell Privilege,Elevate PS Execution,Secure Windows Scripting,Admin-Level PowerShell,Win11 Command Prompt Authorization
thumbnail: https://thmb.techidaily.com/724743278e3cc8c3d6bd3e09a36a5228f2284123f9ba460d1a5d5ea60dfb5a94.jpg
---

## Trick to Invoke Admin-Level PowerShell on Your Win11 PC

 PowerShell is a task-based command-line shell and scripting language built on .NET technology. It's designed especially for system administrators and power users, so it has more features than the standard Command Prompt. If you want to use PowerShell to do anything more than basic tasks, you must run it as an administrator.

 In this guide, we'll show you ten simple ways to open an elevated PowerShell prompt on Windows 11.

## 1\. How to Open Windows PowerShell as an Administrator Using the Power User Menu

 The Power User Menu is a great way to quickly access important system tools and settings in Windows 11\. To open Windows PowerShell using the Power User Menu, do the following:

1. Right-click on**Start** to open the quick access menu. You can also access it by pressing**Win + X** on your keyboard.
2. From the menu list, select**Terminal (Admin)** .  
![Open Windows PowerShell Using Power User Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-power-user-menu.jpg)
3. If UAC appears on the screen, click**Yes** to grant permission.

## 2\. How to Open Windows PowerShell as an Administrator From the Windows Search Tool

 Alternatively, you can open Windows PowerShell as an administrator using the Windows Search tool. This process is relatively simple and only takes a few steps. Here is how to do it:

1. Press the**Win + S** keyboard shortcut to open Windows Search.
2. Type "PowerShell" into the search bar.
3. From the right pane, select**Run as administrator** .  
![Open Windows PowerShell Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-windows-search.jpg)
4. If User Account Control prompts you, click**Yes** to grant admin privileges.

 PowerShell will now open with administrative privileges. Here you can type any PowerShell command you want to execute. To exit PowerShell, type "Exit" and press**Enter** .

## 3\. How to Open Windows PowerShell as an Administrator Through the Run Command

 There is a powerful tool in Windows 11 called Run Command that lets you access files, launch programs, and adjust many system settings. You can also use it to launch Windows PowerShell as an administrator. Here's how:

1. Press**Win + R** on your keyboard. This will open the Run dialog box.
2. From here, type in "PowerShell" and press**Ctrl + Shift + Enter** key combination.  
![Open Windows PowerShell Using Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-run-command.jpg)
3. If a confirmation prompt pops up, click**Yes** to continue. This will launch PowerShell as an administrator.

## 4\. How to Open Windows PowerShell as an Administrator From Windows File Explorer

 Another method for opening Windows PowerShell as an administrator is through File Explorer's address bar. To do this, follow these steps:

1. Press**Win + E** on your keyboard to open Windows File Explorer.
2. In the File Explorer address bar, type the following command and press Enter.  
C:\Windows\System32\WindowsPowerShell\v1.0\
3. Next to the address bar, search for "PowerShell".
4. Right-click on the PowerShell executable file and select**Run as administrator** .  
![Open Windows PowerShell Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-file-explorer.jpg)
5. When UAC appears, click**Yes** to grant admin rights.

## 5\. How to Open Windows PowerShell as an Administrator Using Command Prompt

 A command prompt lets you run almost any program or application on your Windows device. To run Windows PowerShell using this tool, follow these steps:

1. Run Command Prompt as an Administrator (see [how to open the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).  
![Open Windows PowerShell Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-command-prompt.jpg)
2. In the elevated command prompt, copy and paste the given command line:  
`powershell Start-Process powershell -Verb runAs`

 As soon as you type the above command line in the elevated command prompt window, Windows PowerShell will start running as an administrator.

## 6\. How to Open Windows PowerShell as an Administrator From the Start Menu

 The Start Menu contains a wide range of software programs and files that provide a central place for launching applications and other tasks. Start Windows PowerShell with these steps:

1. Click the**Start** button at the bottom left of your screen.
2. Select**All apps** from the upper right corner.
3. Scroll down and click the**Windows Tools** option
4. Now right-click on**Windows PowerShell** and select**Run as administrator** .  
![Open Windows PowerShell Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-control-panel.jpg)
5. The UAC will appear on the screen. If it does, click**Yes** to grant administrative privileges.

## 7\. How to Open Windows PowerShell as an Administrator Through Task Manager

 Task Manager is a powerful tool that can help you troubleshoot and fix problems with your PC. Besides this, you can also use this tool to launch programs on your Windows device.

 Here's how to start Windows PowerShell as an administrator with this tool.

1. Press**Ctrl + Shift + Esc** on your keyboard to open Task Manager (see [how to open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) for more tips).
2. Select**Run new task** from the top of the page.
3. In the pop-up menu, type "PowerShell" and check the "Create this task with administrative privileges" box.  
![Open Windows PowerShell Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-task-manager.jpg)
4. Click**OK** and Windows PowerShell will start as an administrator.

## 8\. How to Open Windows PowerShell as an Administrator Using the Control Panel

 Windows Control Panel is a software program that contains many tools for managing settings on Windows. With this tool, you can launch almost any application installed on your computer. Follow these steps to open Windows PowerShell as an administrator:

1. Use one of the many [ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Click on**System and Security** .
3. Scroll down to the bottom and select**Windows Tools** .
4. Right-click on**Windows PowerShell** and select**Run as administrator** .  
![Open Windows PowerShell Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-control-panel.jpg)
5. A User Account Control pop-up window will appear asking if you want to allow this app to make changes to your PC; click**Yes** to continue.

 PowerShell will now launch as an administrator, and you can run commands with full privileges. If you need to exit PowerShell, type Exit and press Enter.

## 9\. How to Open Windows PowerShell as an Administrator With a Desktop Shortcut

 If you often run commands that require administrative privileges, consider creating a desktop shortcut. Here's how to do it with Windows PowerShell.

1. Right-click on your Desktop and select**New > Shortcut** .
2. Next, type the following command in the "Create Shortcut" window.  
C:\WINDOWS\System32\WindowsPowerShell\v1.0\powershell.exe
3. Then click**Next** to continue.  
![Open Windows PowerShell With Desktop Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-with-desktop-shortcut.jpg)
4. Type in a name for the shortcut and click Finish.

 Now, whenever you want to open PowerShell as an administrator, simply double-click on the shortcut.

## 10\. How to Open Windows PowerShell as an Administrator Using a Batch File

 This method involves creating a batch file to open Windows PowerShell as an administrator. Here's how to do it:

1. Press**Win + R** , type "Notepad", and hit**Enter** to open it (see [how to open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) for more ways).
2. In Notepad, copy and paste the following command line:  
Powershell.exe -Command "& {Start-Process Powershell.exe -Verb RunAs}"
3. Now click on**File** and select**Save as** from the menu list.
4. Put "PowerShell.bat" in the file name. You can name your file anything you like with the .bat extension.
5. Choose the location where you'd like to save it, and then click**Save** .  
![Open Windows PowerShell With a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-with-a-batch-file.jpg)

 This will create the Windows PowerShell batch file. To open Windows PowerShell with administrator access, double-click the batch file. When the UAC prompt appears, click**Yes** to continue.

## Get an Elevated Windows PowerShell Running

 When you are working with files or folders that need elevated permissions, you may need to open PowerShell as an administrator. This is because some tasks require elevation in order to complete them successfully. As shown above, there are several ways to open Windows PowerShell as an administrator.


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
<li><a href="https://win11.techidaily.com/accelerating-windows-based-excel-tasks-a-guide/"><u>Accelerating Windows-Based Excel Tasks: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-gameplay-recording-harnessing-intel-graphics-hub/"><u>Advanced Gameplay Recording: Harnessing Intel Graphics Hub</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-social-media-supremacy-amplifying-sales-via-tiktok-campaigns-for-2024/"><u>[Updated] Social Media Supremacy  Amplifying Sales via TikTok Campaigns for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-motorola-moto-g84-5g-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Motorola Moto G84 5G Device</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-beam-your-best-achieving-hd-quality-with-fb-live/"><u>[Updated] In 2024, Beam Your Best  Achieving HD Quality with FB Live</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-native-pdf-reader-setup-in-windows/"><u>Altering the Native PDF Reader Setup in Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/best-chromecast-audio-capture-solutions-top-picks/"><u>Best Chromecast Audio Capture Solutions - Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-effortless-ios-screen-recording-techniques-for-2024/"><u>[New] Effortless iOS Screen Recording Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-excessive-cpu-usage-by-tiworkerexe-software/"><u>Alleviating Excessive CPU Usage by TiWorker.exe Software</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-creativity-best-writing-software-for-windows/"><u>Amplify Creativity: Best Writing Software For Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-streamers-guide-to-best-free-options-across-every-system-for-2024/"><u>Ultimate Streamer's Guide to Best Free Options Across Every System for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-desktop-date-and-time-a-win-1011-guide/"><u>Adjusting Desktop Date & Time: A Win 10/11 Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-enhanced-productivity-learn-to-record-your-mac-screen-for-2024/"><u>[Updated] Enhanced Productivity  Learn to Record Your Mac Screen for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-audiophiles-ultimate-narrative-guides/"><u>[New] Audiophile's Ultimate Narrative Guides</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-iphone-8-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock iPhone 8 with iTunes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-soundless-shift-how-to-remove-audio-from-video-projects-today-for-2024/"><u>New The Soundless Shift How to Remove Audio From Video Projects Today for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-premium-surround-sound-with-dolby-atmos-in-windows-11/"><u>Achieving Premium Surround Sound with Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-realme-10t-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Realme 10T 5G</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-network-reachability-windows/"><u>Addressing No Network Reachability (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-insufficient-graphics-memory-in-hogwarts-educational-game/"><u>Addressing Insufficient Graphics Memory in Hogwarts Educational Game</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-muting-zoom-a-step-by-step-guide-for-quiet-calls-on-laptops-and-phones/"><u>Updated Muting Zoom A Step-by-Step Guide for Quiet Calls on Laptops & Phones</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-assessing-the-value-of-digital-image-anchor-points/"><u>2024 Approved  Assessing the Value of Digital Image Anchor Points</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-stop-motion-like-a-pro-expert-tips-and-techniques-for-instagram-success-for-2024/"><u>New Stop Motion Like a Pro Expert Tips and Techniques for Instagram Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-steam-data-flow-combatting-sudden-drops/"><u>Amplifying Steam Data Flow: Combatting Sudden Drops</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-ubuntu-video-editing-essentials-10-free-apps-you-need-to-know/"><u>New Ubuntu Video Editing Essentials 10 Free Apps You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
</ul></div>
