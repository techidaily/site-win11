---
title: Cutting Ties with Windows 11 Store
date: 2024-06-25T11:38:13.306Z
updated: 2024-06-26T11:38:13.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting Ties with Windows 11 Store
excerpt: This Article Describes Cutting Ties with Windows 11 Store
keywords: Forego Windows Shop,Ditch WinStore,Reject Microsoft Apps,Escape WinShop,Bypass Windows Updates,Liberate From WinOS,Break Free From Store
thumbnail: https://thmb.techidaily.com/bbf8b4ac709b45ef5944f09a459d244c293de523e01954b86b12ee5efc9e9834.jpg
---

## Cutting Ties with Windows 11 Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://win11.techidaily.com/easing-the-fatal-javascript-issue-on-windows-11s-discord-app/"><u>Easing the Fatal Javascript Issue on Windows 11'S Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-chrome-for-smooth-youtube-streaming/"><u>Optimizing Chrome for Smooth YouTube Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-java-failure-in-windows-installation/"><u>Troubleshooting Java Failure in Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-frozen-discord-overlay-on-your-windows-system/"><u>Combat the Frozen Discord Overlay on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-system-call-failed-error-on-windows-10-and-11/"><u>How to Fix the “System Call Failed” Error on Windows 10 & 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-pixelsnapper-professional-edition/"><u>[New] PixelSnapper  Professional Edition</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-samsung-galaxy-m34-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Samsung Galaxy M34 5G Phones</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-undercover-guide-to-enhancing-your-window-11-experience/"><u>[New] The Undercover Guide to Enhancing Your WINDOW 11 Experience</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-free-avi-video-concatenators-top-10-tools-for-smooth-joining/"><u>2024 Approved Free AVI Video Concatenators Top 10 Tools for Smooth Joining</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-make-excel-2023-hyperlinks-working-stellar-by-stellar-guide/"><u>Easy Steps to Make Excel 2023 Hyperlinks Working | Stellar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-nubia-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Nubia? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-the-art-of-storytelling-on-ig-for-higher-engagement/"><u>[Updated] In 2024, Mastering the Art of Storytelling on IG for Higher Engagement</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-critical-analysis-of-vsdc-highlighting-best-software/"><u>[Updated] Critical Analysis of VSDC, Highlighting Best Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/seamless-timelapse-footage-with-ios-technology/"><u>Seamless Timelapse Footage with iOS Technology</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-heritage-on-display-post-copyright-masterpieces/"><u>[New] 2024 Approved  Heritage on Display  Post-Copyright Masterpieces</u></a></li>
</ul></div>
