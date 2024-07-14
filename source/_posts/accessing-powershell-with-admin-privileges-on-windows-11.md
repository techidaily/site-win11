---
title: Accessing PowerShell with Admin Privileges on Windows 11
date: 2024-07-13T11:23:06.829Z
updated: 2024-07-14T11:23:06.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing PowerShell with Admin Privileges on Windows 11
excerpt: This Article Describes Accessing PowerShell with Admin Privileges on Windows 11
keywords: Admin PowerShell Access,Windows 11 PowerShell,High-Privilege PS Execution,Windows 11 Admin Prep,Elevated Powershell Scripts,Secure PS Execution,Admin Rights in Windows PS
thumbnail: https://thmb.techidaily.com/4509b58b3a9a19b95f97977ea395ec0191792aea55bdaf18f72a70f3772092da.jpg
---

## Accessing PowerShell with Admin Privileges on Windows 11

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
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-vivo-v27-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Vivo V27 for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-forgotten-island-xbox-hiccup/"><u>Breaking Free From the Forgotten Island Xbox Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-user-engagement-with-context-menu-update-options/"><u>Bolstering User Engagement with Context Menu Update Options</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hidden-features-top-30-unknown-window-11-tips-for-2024/"><u>Hidden Features  Top 30 Unknown WINDOW 11 Tips for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-vivo-y200-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Vivo Y200 Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/assisting-users-with-erratic-swipes-on-windows-systems/"><u>Assisting Users with Erratic Swipes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-blank-screens-windows-10-and-11-troubleshooting/"><u>Banishing Blank Screens: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/step-by-step-guide-to-achieving-the-perfectly-loops-youtube-videos-for-2024/"><u>Step-By-Step Guide to Achieving the Perfectly Loops YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-approaches-for-removing-wifi-from-windows-11/"><u>Best Approaches for Removing Wifi From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-5-apps-to-increase-volume-on-windows-past-100/"><u>Breaking the Barrier: 5 Apps to Increase Volume on Windows Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-hot-zone-tips-to-prevent-pc-overheating-during-games/"><u>Avoiding the Hot Zone: Tips to Prevent PC Overheating During Games</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-display-driver-setbacks-amd-radeon-r9/"><u>Overcoming Display Driver Setbacks: AMD Radeon R9</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-odds-tackling-installer-errors-in-win11-successfully/"><u>Beating the Odds: Tackling Installer Errors in Win11 Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-xbox-game-pass-0x00000001-troubleshooting-for-windows-11/"><u>Avoiding Xbox Game Pass 0X00000001: Troubleshooting for Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-soothing-stories-in-video-form-insights-and-critiques/"><u>2024 Approved  Soothing Stories in Video Form  Insights and Critiques</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-exepe-file-formats/"><u>Breaking Down Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-license-ends-soon-issues-on-windows-1011/"><u>Avoiding “License Ends Soon” Issues on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-icon-alignment-on-pcs/"><u>Achieve Seamless Icon Alignment on PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>Methods to Change GPS Location On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-media-stream-efficiency-taming-vlc-lags/"><u>Boosting Media Stream Efficiency: Taming VLC Lags</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-black-battery-compatibility-with-gopro-hero5/"><u>[Updated] Ultimate Black Battery Compatibility with GoPro Hero5</u></a></li>
<li><a href="https://win11.techidaily.com/become-a-command-line-wizard-grasp-the-top-20-must-know-commands/"><u>Become a Command Line Wizard: Grasp the Top 20 Must-Know Commands</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/experts-choice-best-hdmi-21-display-models-evaluated-for-2024/"><u>Expert's Choice  Best HDMI 2.1 Display Models Evaluated for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-productivity-the-ultimate-toolkit-of-5plus-apps/"><u>Boost Your Windows Productivity: The Ultimate Toolkit of 5+ Apps</u></a></li>
<li><a href="https://win11.techidaily.com/airplane-mode-heres-your-guide-for-win11/"><u>Airplane Mode? Here's Your Guide for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-efficiently-updating-windows-solo/"><u>Blueprint for Efficiently Updating Windows Solo</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-10-and-11-climate-choices/"><u>Best Windows 10 & 11 Climate Choices</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-restore-search-box-to-win11-taskbar/"><u>Boosting Functionality: Restore Search Box to Win11 TaskBar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-sevenzeronine-in-windows/"><u>Addressing Error SevenZeroNine in Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/online-language-exchange-through-pearson/"><u>Online Language Exchange Through Pearson</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-pc-speed-post-media-downloads-on-w11/"><u>Boosting PC Speed Post Media Downloads on W11</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-glitches-a-guide-for-fixing-windows-office-issues/"><u>Addressing Failure Glitches: A Guide for Fixing Windows Office Issues</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-run-handbrake-in-windows/"><u>Breaking Barriers: Run HandBrake in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-defender-tracings-in-windows-1011-environments/"><u>Banishing Defender Tracings in Windows 10/11 Environments</u></a></li>
</ul></div>
