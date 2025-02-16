---
title: Initiating PowerShell as Admin in Windows 11 Operating System
date: 2025-02-10T04:52:34.942Z
updated: 2025-02-15T18:36:07.876Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Initiating PowerShell as Admin in Windows 11 Operating System
excerpt: This Article Describes Initiating PowerShell as Admin in Windows 11 Operating System
keywords: Admin PowerShell Windows 11,Windows 11 PowerShell Run,Elevate Powershell Command,Execute Script As Admin Win11,Gain Admin Privileges PS,Superuser Powershell Setup,PowerShell Accesso Administrazione Windows11
thumbnail: https://thmb.techidaily.com/bb7a936483f9ef78d27c435fd60e8eb11646b876bcc8f6574b11c1b4a0b3d5df.jpg
---

## Initiating PowerShell as Admin in Windows 11 Operating System

 PowerShell is a task-based command-line shell and scripting language built on .NET technology. It's designed especially for system administrators and power users, so it has more features than the standard Command Prompt. If you want to use PowerShell to do anything more than basic tasks, you must run it as an administrator.

 In this guide, we'll show you ten simple ways to open an elevated PowerShell prompt on Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Open Windows PowerShell as an Administrator Using the Power User Menu

 The Power User Menu is a great way to quickly access important system tools and settings in Windows 11\. To open Windows PowerShell using the Power User Menu, do the following:

1. Right-click on**Start** to open the quick access menu. You can also access it by pressing**Win + X** on your keyboard.
2. From the menu list, select**Terminal (Admin)** .  
![Open Windows PowerShell Using Power User Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-power-user-menu.jpg)
3. If UAC appears on the screen, click**Yes** to grant permission.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. How to Open Windows PowerShell as an Administrator Using Command Prompt

 A command prompt lets you run almost any program or application on your Windows device. To run Windows PowerShell using this tool, follow these steps:

1. Run Command Prompt as an Administrator (see[how to open the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).  
![Open Windows PowerShell Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-command-prompt.jpg)
2. In the elevated command prompt, copy and paste the given command line:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. How to Open Windows PowerShell as an Administrator Through Task Manager

 Task Manager is a powerful tool that can help you troubleshoot and fix problems with your PC. Besides this, you can also use this tool to launch programs on your Windows device.

 Here's how to start Windows PowerShell as an administrator with this tool.

1. Press**Ctrl + Shift + Esc** on your keyboard to open Task Manager (see[how to open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) for more tips).
2. Select**Run new task** from the top of the page.
3. In the pop-up menu, type "PowerShell" and check the "Create this task with administrative privileges" box.  
![Open Windows PowerShell Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/open-windows-powershell-using-task-manager.jpg)
4. Click**OK** and Windows PowerShell will start as an administrator.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. How to Open Windows PowerShell as an Administrator Using the Control Panel

 Windows Control Panel is a software program that contains many tools for managing settings on Windows. With this tool, you can launch almost any application installed on your computer. Follow these steps to open Windows PowerShell as an administrator:

1. Use one of the many[ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 10\. How to Open Windows PowerShell as an Administrator Using a Batch File

 This method involves creating a batch file to open Windows PowerShell as an administrator. Here's how to do it:

1. Press**Win + R** , type "Notepad", and hit**Enter** to open it (see[how to open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) for more ways).
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
<li><a href="https://facebook-videos.techidaily.com/new-determining-the-perfect-orientation-for-fb-videos/"><u>[New] Determining the Perfect Orientation for FB Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-exploring-the-depths-of-adobe-cloud-storages-plus-top-non-adobe-choices/"><u>[New] In 2024, Exploring the Depths of Adobe Cloud Storages, Plus Top Non-Adobe Choices</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-innovative-frame-tools-and-websites-image-editors-for-2024/"><u>[New] Innovative Frame Tools and Websites Image Editors for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unveiling-figmas-bg-elimination-mastery/"><u>[Updated] In 2024, Unveiling Figma's BG Elimination Mastery</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-turbo-speed-photo-browser-for-windows-10/"><u>[Updated] Turbo Speed Photo Browser for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-mobile-hotspot-on-the-go/"><u>Configuring Windows 11 Mobile Hotspot on the Go</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/easy-techniques-to-download-gif-images-from-social-media-for-2024/"><u>Easy Techniques to Download GIF Images From Social Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-mouse-indicators-in-modern-windows-environments/"><u>Elevating Mouse Indicators in Modern Windows Environments</u></a></li>
<li><a href="https://facebook.techidaily.com/fix-for-inaccessible-verification-codes-on-social-media-platforms-fb/"><u>Fix for Inaccessible Verification Codes on Social Media Platforms (FB)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-apple-iphone-13-pro-max-with-or-without-password-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on Apple iPhone 13 Pro Max With or Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-rift-of-war-boost-fps-on-windows-pcs/"><u>Master the Rift of War: Boost FPS on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-lunar-client-launch-failure-on-desktops/"><u>Quick-Fix Tips for Lunar Client Launch Failure on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disconnection-issues-from-nvidia-to-os-1011/"><u>Resolving Disconnection Issues From Nvidia to OS 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/top-8-compact-android-emulators-windows-and-macos/"><u>Top 8 Compact Android Emulators, Windows & MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-why-is-my-nvidia-cp-closed/"><u>Troubleshooting: Why Is My Nvidia CP Closed?</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-speed-potential-with-premium-keyboard-cars/"><u>Unleash Speed Potential with Premium Keyboard Cars</u></a></li>
</ul></div>

