---
title: "Windows 11: How to Erase Microsoft Store"
date: 2024-10-24T04:30:00.905Z
updated: 2024-10-27T03:08:30.605Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
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

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-step-by-step-guide-to-obs-streaming-success/"><u>[New] 2024 Approved The Step-by-Step Guide to OBS Streaming Success</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-efficient-tweet-strategy-embrace-aspect-ratio-specifications-for-2024/"><u>[New] Efficient Tweet Strategy Embrace Aspect Ratio Specifications for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-game-on-essential-samsung-gear-vr-experiences/"><u>[New] Game On Essential Samsung Gear VR Experiences</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-search-of-alternatives-to-vlc-media-player/"><u>[Updated] In Search of Alternatives to VLC Media Player</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-top-10-vr-apps-for-iphoneandroid/"><u>2024 Approved Top 10 VR Apps for iPhone/Android</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/avoid-developer-headaches-with-these-8-techniques-for-handling-parsing-issues-in-android/"><u>Avoid Developer Headaches with These 8 Techniques for Handling Parsing Issues in Android</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-boot-blockers-top-windows-troubleshooting-steps/"><u>Breaking Through Boot Blockers: Top Windows Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-the-seven-timeless-windows-features-of-11/"><u>Bridging Generations: The Seven Timeless Windows Features of 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-worlds-windows-meets-kali-linux/"><u>Bridging Worlds: Windows Meets Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-steam-game-icons-quickly/"><u>Bring Back Missing Steam Game Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-frozen-startup-screen-in-win-lol/"><u>Bypassing Frozen Startup Screen in Win: LOL</u></a></li>
<li><a href="https://win11.techidaily.com/changing-the-time-before-next-login-attempt-on-failure/"><u>Changing the Time Before Next Login Attempt on Failure</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-experience-unadorned-windows-11/"><u>Clear the Clutter: Experience Unadorned Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-session-verification-failure-on-your-steam-pc/"><u>Clearing Up Session Verification Failure on Your Steam PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-error-31-restoring-seamless-internet-access/"><u>Clearing Up WIN Error 31: Restoring Seamless Internet Access</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-narzo-60-pro-5g-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Realme Narzo 60 Pro 5G Phone with Broken Screen</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-itel-a70-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Itel A70 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/two-ways-to-sync-contacts-from-honor-x50-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Two Ways to Sync Contacts from Honor X50 to Gmail | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-gpt-4s-potential-accessible-ai-for-all-discover-the-workflow/"><u>Unlocking GPT-4's Potential: Accessible AI for All - Discover The Workflow</u></a></li>
</ul></div>

