---
title: "Win11 Storage Cleanup: Removing Microsoft App"
date: 2024-12-06T10:54:38.322Z
updated: 2024-12-06T22:20:46.827Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Storage Cleanup: Removing Microsoft App"
excerpt: "This Article Describes Win11 Storage Cleanup: Removing Microsoft App"
keywords: Win11 Space Clear,Win11 Disk Clean,Remove Win11 Apps,Free Win11 Memory,Optimize Win11 Storage,Delete Windows Apps,Streamline Win11 Files
thumbnail: https://thmb.techidaily.com/1b6976dc536a482a8440b6155a5c6ffdb602672c280e778006363b18d82c63d3.jpg
---

## Win11 Storage Cleanup: Removing Microsoft App

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/updated-expert-8-download-for-fb-movies-for-2024/"><u>[Updated] Expert 8 Download for FB Movies for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-leading-list-the-best-10-apps-for-live-racing-and-rugby-streaming/"><u>[Updated] In 2024, Leading List The Best 10 Apps for Live Racing & Rugby Streaming</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-syncopation-spotlight-hits-that-have-hit-the-high-note-on-tiktok/"><u>[Updated] Syncopation Spotlight Hits That Have Hit the High Note on TikTok</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/best-budget-gaming-accessories-keyboards-and-mice-under-99-for-2024/"><u>Best Budget Gaming Accessories Keyboards & Mice Under $99 for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/embrace-the-future-facebook-video-autoplay-for-2024/"><u>Embrace the Future Facebook Video Autoplay for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/enhance-game-performance-update-graphics-card-driver-for-forza-horizon-5/"><u>Enhance Game Performance: Update Graphics Card Driver for Forza Horizon 5</u></a></li>
<li><a href="https://win11.techidaily.com/forceful-deletion-of-windows-11-printers-explained/"><u>Forceful Deletion of Windows 11 Printers Explained</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-newest-hp-laptop-drivers-installed-on-windows-quickly-and-safely/"><u>Get the Newest HP Laptop Drivers Installed on Windows Quickly & Safely</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eradicate-the-0x80072af9-error-on-pc/"><u>How to Eradicate the 0X80072AF9 Error on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-oppo-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Oppo</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/how-to-use-a-whiteboard-in-google-meet-for-2024/"><u>How to Use a Whiteboard in Google Meet for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-in-efficiency-10-essential-windows-apps/"><u>Masterclass in Efficiency: 10 Essential Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-freeze-tips-for-resource-monitors-on-windows-11/"><u>Overcoming the Freeze: Tips for Resource Monitors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quake-mode-entry-with-windows-terminal/"><u>Quake Mode Entry with Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-operations-fixing-data-failure-on-usb-drives-windows/"><u>Restoring Operations: Fixing Data Failure on USB Drives (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unshielding-windows-deactivating-defender-firewall/"><u>Unshielding Windows: Deactivating Defender Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-veiled-viewer-steps-to-engage-with-windows-hidden-character-tracker/"><u>Unveiling the Veiled Viewer: Steps to Engage with Windows’ Hidden Character Tracker</u></a></li>
</ul></div>

