---
title: "Windows 11: How to Erase Microsoft Store"
date: 2024-09-13T23:15:55.090Z
updated: 2024-09-17T06:37:38.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: How to Erase Microsoft Store"
excerpt: "This Article Describes Windows 11: How to Erase Microsoft Store"
keywords: Win11 Uninstall MSStore,Delete Windows Store Apps,Removing Microsoft Store WS11,Eliminate Windows 11 Store,WS11 Microsoft Store Clear,Remove Store From Win11,Get Rid of WS11 Apps
thumbnail: https://thmb.techidaily.com/baabb0210a0e9d1dfef8f1a18fa201bad1a8f950b33fad191c1a3f8c1897f172.jpg
---

## Windows 11: How to Erase Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-why-are-facebook-recommended-videos-vanishing/"><u>[Updated] In 2024, Why Are Facebook Recommended Videos Vanishing?</u></a></li>
<li><a href="https://win11.techidaily.com/1-mastering-multimedia-a-comprehensive-guide-on-leveraging-the-power-of-video-to-audio-conversion-with-factory-pro/"><u>1. Mastering Multimedia: A Comprehensive Guide on Leveraging the Power of Video-to-Audio Conversion with Factory Pro</u></a></li>
<li><a href="https://win11.techidaily.com/windows-and-mac4/"><u>動画画角トリミング: Windows & Macで実行可能な4手法</u></a></li>
<li><a href="https://win11.techidaily.com/1726026337234-dvd/"><u>最適なレンタルDVDコピーツール選び - 使い勝手とセキュリティの両立!</u></a></li>
<li><a href="https://win11.techidaily.com/1726026382879-gif/"><u>GIFアニメ画質向上:高解像度への改良手順</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-seamless-and-permanent-tiktok-bio-linking-methods/"><u>In 2024, Seamless & Permanent TikTok Bio Linking Methods</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-apple-iphone-8-plus-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on Apple iPhone 8 Plus</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-vivo-y100-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo Y100 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/quick-and-simple-way-to-delete-programs-from-macos-devices/"><u>Quick & Simple Way to Delete Programs From macOS Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-guide-for-proficient-use-of-movie-maker-in-win11-for-2024/"><u>Step-by-Step Guide for Proficient Use of Movie Maker in Win11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-without-drive-letters-analyzing-problems-and-proposed-solutions/"><u>Windows Without Drive Letters: Analyzing Problems and Proposed Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/wmamp3-top3/"><u>WMAファイルからMP3への変換が簡単! ベストオンラインツールTOP3</u></a></li>
</ul></div>

