---
title: Getting Rid of Windows 11'S Official Store
date: 2024-11-22T00:55:09.972Z
updated: 2024-11-28T01:15:16.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Getting Rid of Windows 11'S Official Store
excerpt: This Article Describes Getting Rid of Windows 11'S Official Store
keywords: Drop Windows 11 Shop,Eliminate W11 Store,Remove Microsoft Store,Bypass Windows 11 Marketplace,Ditch Windows 11 Launcher,Unlink Windows 11 Apps,Escape Windows 11 Online Hub
thumbnail: https://thmb.techidaily.com/c7f6e1d56c05b1571f57a7f9b04e195b30e35f1ef9fbc6554b9991ddbdbae23c.png
---

## Getting Rid of Windows 11'S Official Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-pushing-up-conversions-with-high-roi-animated-advertisements-on-fb/"><u>[Updated] In 2024, Pushing Up Conversions with High-ROI Animated Advertisements on FB</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-motorola-defy-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-free-and-paid-canvas-creations-apps-for-pc-users/"><u>Best Free & Paid Canvas Creations Apps for PC Users</u></a></li>
<li><a href="https://common-error.techidaily.com/concept-of-karma/"><u>Concept of Karma</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-11s-audio-management-via-action-center-mixer/"><u>Decoding Windows 11'S Audio Management via Action Center Mixer</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/exploring-apples-smart-tech-integration-the-comprehensive-guide-to-ai-enhancements-on-iphone-mac-and-ipad/"><u>Exploring Apple's Smart Tech Integration: The Comprehensive Guide to AI Enhancements on iPhone, Mac, & iPad</u></a></li>
<li><a href="https://win11.techidaily.com/handling-failed-sound-device-opens-for-audacity-users/"><u>Handling Failed Sound Device Opens for Audacity Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-elevate-your-role-on-windows-computers/"><u>How to Elevate Your Role on Windows Computers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-poco-x5-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP from Poco X5 Pro?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-realme-12plus-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Realme 12+ 5G</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-keyboard-commands-near-power-icon-shortcut-placement-in-win11/"><u>Masterful Keyboard Commands: Near-Power Icon Shortcut Placement in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-precise-window-interactions-via-shorthand/"><u>Quick and Precise Window Interactions via Shorthand</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-fix-black-white-store-errors/"><u>Tactics to Fix Black, White Store Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-time-travelers-guide-to-windows-11-seven-enduring-elements/"><u>The Time Travelers' Guide to Windows 11: Seven Enduring Elements</u></a></li>
<li><a href="https://win11.techidaily.com/top-strategies-for-overcoming-windows-updater-failure-code-0x800f080a/"><u>Top Strategies for Overcoming Windows Updater Failure Code 0X800F080A</u></a></li>
<li><a href="https://fox-pages.techidaily.com/wat-doe-je-als-je-bestandjes-weggelost-zijn-bij-schijffreecleaning/"><u>Wat Doe Je Als Je Bestandjes Weggelost Zijn Bij Schijffreecleaning?</u></a></li>
</ul></div>

