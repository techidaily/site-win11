---
title: 3 Ways to Remove the Microsoft Store App From Windows 11
date: 2024-07-02T13:09:21.374Z
updated: 2024-07-03T13:09:21.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Remove the Microsoft Store App From Windows 11
excerpt: This Article Describes 3 Ways to Remove the Microsoft Store App From Windows 11
keywords: Removing MS Store,Uninstalling Windows 11 Store,Eliminate Windows 11 App,Disable Microsoft Apps,Delete OS Store Icon,MS Store Uninstall Guide,Remove Windows 11 Apps
thumbnail: https://thmb.techidaily.com/549ca928829525c9c386345bc34f0e1c4ffcbb4613654a88c4a76774162c73c8.jpg
---

## 3 Ways to Remove the Microsoft Store App From Windows 11

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

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
<li><a href="https://win11.techidaily.com/quick-tutorial-opening-the-windows-info-panel/"><u>Quick Tutorial: Opening the Windows Info Panel</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-reliable-windows-photo-organizer-list/"><u>The Most Reliable Windows Photo Organizer List</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-windows-11-pin-more-secure-and-elongated/"><u>Making Your Windows 11 PIN More Secure & Elongated</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-web-with-ease-using-ms-edge-gestures-windows-11/"><u>Navigate the Web with Ease Using MS Edge Gestures (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-run-as-admin-errors-a-guide/"><u>Overcoming Run as Admin Errors: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-missing-file-updates-error-on-windows-error-code-0x80070003/"><u>Navigating Through Missing File Updates Error on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-setting-windows-backups-against-original-standards/"><u>Instructions for Setting Windows Backups Against Original Standards</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimizing-your-podcasts-itunes-placement/"><u>2024 Approved  Optimizing Your Podcast's iTunes Placement</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-xiaomi-14-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Xiaomi 14 Location | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-best-10-pc-cameras-and-recording-software-on-win-10/"><u>[New] 2024 Approved  The Best 10 PC Cameras & Recording Software on Win 10</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-correct-lens-distortion-in-videos/"><u>In 2024, How to Correct Lens Distortion in Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-use-google-trends-to-come-up-with-video-ideas-in-2024/"><u>[New] How to Use Google Trends to Come up with Video Ideas, In 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713961686156-updated-are-you-thinking-of-learning-video-editing-in-the-final-cut-pro-software-in-this-article-you-will-learn-different-ways-of-splitting-and-merging-mult/"><u>Updated Are You Thinking of Learning Video Editing in the Final Cut Pro Software? In This Article, You Will Learn Different Ways of Splitting and Merging Multiple Videos at Once as a New Skill to Get Your Business to a New Level for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-pre-converting-prep-essential-information-for-m4r-newbies/"><u>Updated In 2024, Pre-Converting Prep Essential Information for M4R Newbies</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-iphone-13-pro-max-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass iPhone 13 Pro Max Activation Lock</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-realme-c53-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Realme C53? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
</ul></div>
