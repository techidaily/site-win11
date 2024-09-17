---
title: Eliminating Microsoft's Windows 11 Store
date: 2024-09-10T21:39:52.807Z
updated: 2024-09-16T23:42:37.534Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Microsoft's Windows 11 Store
excerpt: This Article Describes Eliminating Microsoft's Windows 11 Store
keywords: Windows 11 Removal Guide,Bypassing Windows App Store,Uninstall Windows 11 Feature,Remove Windows Update Store,Eliminate Microsoft Store,Disable Windows 11 Shop,Bypass Windows 11 Purchase Center
thumbnail: https://thmb.techidaily.com/193370cfb5fd0062ad7927622f757d95e1534f19599b794b5d420052ed1a0476.jpg
---

## Eliminating Microsoft's Windows 11 Store

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

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-securing-high-quality-sound-from-anywhere/"><u>[New] 2024 Approved Securing High-Quality Sound From Anywhere</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premium-ios-photo-and-video-shows-from-ix-to-ios12/"><u>[Updated] Premium iOS Photo & Video Shows From IX to IOS12</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-tackling-inaudible-portions-in-partially-muted-fb-media/"><u>2024 Approved Tackling Inaudible Portions in Partially Muted FB Media</u></a></li>
<li><a href="https://location-social.techidaily.com/does-honor-play-8t-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Honor Play 8T Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-infinix-smart-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/game-on-securing-your-playthroughs-in-win10-for-2024/"><u>Game On Securing Your Playthroughs in Win10 for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-analyzing-aurora-hdr-quality/"><u>In 2024, Analyzing Aurora HDR Quality</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-boost-viewership-cost-effectively-with-subscriber-purchase/"><u>In 2024, Boost Viewership Cost-Effectively with Subscriber Purchase</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-c0000005-errors-in-windows/"><u>Mastering the Art of Fixing C0000005 Errors in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/premium-fb-videograbber-tools-secure-fast-file-grab/"><u>Premium FB Videograbber Tools Secure, Fast File Grab</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-onedrive-login-issues-in-windows-systems/"><u>Resolving OneDrive Login Issues in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-reset-softwaredistribution-on-windows-11/"><u>Simplified Steps to Reset SoftwareDistribution on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-resolving-mysterious-recording-issue-in-obs-on-windows-11/"><u>Strategies for Resolving Mysterious Recording Issue in OBS on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unique-windows-11-workarounds-for-inaccessible-folder-names/"><u>Unique Windows 11 Workarounds for Inaccessible Folder Names</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-update-error-x712-on-pcs/"><u>Unraveling Update Error X712 on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-threats-exposed-manual-checks-for-windows-pc-security/"><u>Unseen Threats Exposed: Manual Checks for Windows PC Security</u></a></li>
</ul></div>

