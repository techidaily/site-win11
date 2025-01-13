---
title: Methods to Uninstall Win11 Microsoft Store
date: 2025-01-09T05:43:19.133Z
updated: 2025-01-12T21:07:01.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Uninstall Win11 Microsoft Store
excerpt: This Article Describes Methods to Uninstall Win11 Microsoft Store
keywords: Win11 Removal Guide,Uninstalling Microsoft Store,Remove Windows 11 Store,Disable Windows Store Apps,Win11 Store Remover,OptOutWinStore,Stop Microsoft Store Installation
thumbnail: https://thmb.techidaily.com/76af2589a0e801a6b3434a05625504e9a24382860270c85ff4fd48c9e5e5afe1.png
---

## Methods to Uninstall Win11 Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-2023s-best-rated-ps3-virtual-players-for-pc/"><u>[New] 2024 Approved 2023'S Best-Rated PS3 Virtual Players for PC</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-high-definition-war-av1-vs-vp9-codecs-comparison-for-2024/"><u>[Updated] High-Definition War Av1 vs VP9 Codecs Comparison for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-top-10-online-video-editing-software-for-improved-content/"><u>2024 Approved Top 10 Online Video Editing Software for Improved Content</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/academic-engagement-lecture-capture-via-mac-computers/"><u>Academic Engagement Lecture Capture via Mac Computers</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/bend-ai-language-to-your-will/"><u>Bend AI Language to Your Will</u></a></li>
<li><a href="https://win11.techidaily.com/combining-windows-tech-for-superior-linux-use/"><u>Combining Windows Tech for Superior Linux Use</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-media-tool-code-0x90017/"><u>Correcting Windows' Media Tool: Code 0X90017</u></a></li>
<li><a href="https://extra-resources.techidaily.com/countdown-to-love-top-10-timing-tools-for-your-big-day-for-2024/"><u>Countdown to Love Top 10 Timing Tools for Your Big Day for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-ce-3-lite-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord CE 3 Lite 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://ai-video.techidaily.com/in-2024-how-to-auto-translate-youtube-videos-into-different-languages/"><u>In 2024, How To Auto Translate YouTube Videos Into Different Languages</u></a></li>
<li><a href="https://win11.techidaily.com/plain-programs-with-hidden-power-drain-in-windows-11-pcs/"><u>Plain Programs with Hidden Power Drain in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-error-code-0x90017-on-winmedia-tool/"><u>Reconciling Error Code: 0X90017 on WinMedia Tool</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-solo-opening-of-microsoft-marketplace/"><u>Remedying the Solo Opening of Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-window-sharing-rdp-tricks-for-win-11-users/"><u>Seamless Window Sharing: RDP Tricks for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-windows-11-security-issues/"><u>Understanding & Resolving Windows 11 Security Issues</u></a></li>
<li><a href="https://win11.techidaily.com/why-does-task-manager-show-extras-with-edge/"><u>Why Does Task Manager Show Extras with Edge?</u></a></li>
</ul></div>

