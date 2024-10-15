---
title: Three Steps for Disabling Windows Store on Win11
date: 2024-10-14T18:39:01.674Z
updated: 2024-10-15T18:36:57.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Steps for Disabling Windows Store on Win11
excerpt: This Article Describes Three Steps for Disabling Windows Store on Win11
keywords: Win11 Store Disable,Enable Windows Store,Win11 No Store Apps,Stop Windows Store,Deactivate WinStore,Removing WinStore,Turn Off Windows Store
thumbnail: https://thmb.techidaily.com/9c2b7ca2e1893d88d6bb8597241a29c970bfa10f3bf7e355bd7f5437be375738.jpg
---

## Three Steps for Disabling Windows Store on Win11

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
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-discover-top-asmr-for-iosandroid-devices/"><u>[New] 2024 Approved Discover Top ASMR for iOS/Android Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-flip-the-script-instagrams-video-trick-for-2024/"><u>[Updated] Flip the Script Instagram's Video Trick for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-direct-link-method-for-iphone-picture-sharing/"><u>2024 Approved Direct Link Method for iPhone Picture Sharing</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-steps-to-optimize-win11-network-preferences/"><u>Detailed Steps to Optimize Win11 Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/direct-effortless-gameplay-capture-using-windows-and-intel-graphics/"><u>Direct, Effortless Gameplay Capture Using Windows and Intel Graphics</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-oppo-a1x-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Oppo A1x 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-pova-6-pro-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Pova 6 Pro 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-aggregatorhostexe-functionalities-and-security/"><u>Insight Into Windows' AggregatorHost.exe: Functionalities and Security</u></a></li>
<li><a href="https://extra-support.techidaily.com/oceans-bounty-best-cameras-for-anglers-for-2024/"><u>Ocean's Bounty - Best Cameras for Anglers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reestablishing-memory-integrity-on-windows-11-amid-issues/"><u>Reestablishing Memory Integrity on Windows 11 Amid Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-windows-fbm-errors-seamless-chats-ahead/"><u>Resolve Windows FBM Errors, Seamless Chats Ahead</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-avoiding-password-entry-for-rdp-connections/"><u>Stealth Mode: Avoiding Password Entry for RDP Connections</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-switching-assistants-helping-you-ditch-your-mac-os/"><u>Top 5 Switching Assistants Helping You Ditch Your Mac OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-oneplus-nord-ce-3-lite-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for OnePlus Nord CE 3 Lite 5G Users</u></a></li>
</ul></div>

