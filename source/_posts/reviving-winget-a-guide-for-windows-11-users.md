---
title: "Reviving Winget: A Guide for Windows 11 Users"
date: 2024-07-13T09:52:42.878Z
updated: 2024-07-14T09:52:42.878Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Winget: A Guide for Windows 11 Users"
excerpt: "This Article Describes Reviving Winget: A Guide for Windows 11 Users"
keywords: Windows 11 Winget,Reviving Winget,Winget Tips,Update Winget,Windows 11 Tooling,New Winget Guide,Enhance Winget Usage
thumbnail: https://thmb.techidaily.com/93116893fd34c4239c7adfcfb1ed2eb9afdd0b3ec4eb0ecc53392c491facd138.png
---

## Reviving Winget: A Guide for Windows 11 Users

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-clash-for-dominance-leading-royale-games/"><u>[New] Clash for Dominance  Leading Royale Games</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-step-by-step-to-maximizing-adobe-storages-and-exploring-more/"><u>[Updated] In 2024, Step-by-Step to Maximizing Adobe Storages and Exploring More</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-microsoft-store-error-0x80073cf3/"><u>Steps to Resolve Microsoft Store Error 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-resuming-windows-shared-space-visit/"><u>Unshackle: Resuming Windows Shared Space Visit</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/vivid-visions-enhancing-youtubes-aesthentic-content-for-2024/"><u>Vivid Visions  Enhancing YouTube's Aesthentic Content for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-realme-c33-2023-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Realme C33 2023 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-compression-and-decompression-tactics-in-windows-cli/"><u>Quick Compression & Decompression Tactics in Windows CLI</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-ntoskrnlexe-process/"><u>Tackling Excessive Ntoskrnl.exe Process</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-90-pro-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from 90 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-window-11-potential-7-tips/"><u>Unleash Your Window 11 Potential: 7 Tips</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-a-streamers-dream-unifying-obs-and-zoom-with-steps/"><u>In 2024, A Streamer's Dream  Unifying OBS & Zoom with Steps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premium-selection-of-budget-friendly-4k-projectors/"><u>[Updated] Premium Selection of Budget-Friendly 4K Projectors</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-journey-from-content-creator-to-money-maker-on-youtube/"><u>[Updated] The Journey From Content Creator to Money-Maker on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-variances-a-comparison-between-microsoft-and-standard-windows-accounts/"><u>Exploring Variances: A Comparison Between Microsoft and Standard Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-editing-the-win11-list-of-premier-video-scripts/"><u>Elevate Editing: The Win11 List of Premier Video Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-the-missing-search-back-into-win11s-task-manager/"><u>Bringing the Missing Search Back Into Win11's Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-process-unterminate-obstacles-in-windows/"><u>Overcoming 'Process Unterminate' Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pcs-login-trail-a-win-flip-guide/"><u>Securing Your PC's Login Trail: A Win-Flip Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winning-every-game-with-smart-amd-radeon-configurations/"><u>Winning Every Game with Smart AMD Radeon Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-mystery-of-infinite-c-drive-usage/"><u>Combatting the Mystery of Infinite C: Drive Usage</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-on-windows-11-easily/"><u>Enabling Hyper-V on Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-write-failure-in-windows/"><u>Overcoming Memory Write Failure in Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-syncing-scores-three-unique-techniques-for-embedding-audio-in-visual-media/"><u>Updated 2024 Approved Syncing Scores Three Unique Techniques for Embedding Audio in Visual Media</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-blueprints-for-making-youtube-intro-videos-that-stick/"><u>2024 Approved  Blueprints for Making YouTube Intro Videos that Stick</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimized-storage-analysis-how-many-videos-on-a-64128gb-drive/"><u>Optimized Storage Analysis  How Many Videos on a 64/128GB Drive?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-ideas-that-help-you-out-in-converting-avi-to-gif/"><u>New In 2024, Ideas That Help You Out in Converting AVI to GIF</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-pretending-playfulness-making-mocks-and-laughs/"><u>In 2024, Pretending Playfulness  Making Mocks and Laughs</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-mastering-iphone-capturing-time-stretched-movies/"><u>[Updated] Mastering iPhone  Capturing Time-Stretched Movies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winupdate-error-x8019/"><u>Troubleshooting WinUpdate Error X8019</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-show-more-pins-on-win-11-startscreen/"><u>Techniques to Show More Pins on Win 11 Startscreen</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-office-activation-setbacks/"><u>Navigating Through Failed Office Activation Setbacks</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-surge-troubleshoot-for-a-swift-windows-11/"><u>Speedy Surge: Troubleshoot for a Swift Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-grayed-out-extend-volume-option-in-disk-management-for-windows/"><u>How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-uninstall-issues-in-windows-11/"><u>Solving Uninstall Issues in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-speedy-techniques-for-converting-whatsapp-voice-recordings-to-mp3/"><u>In 2024, Speedy Techniques for Converting WhatsApp Voice Recordings to Mp3</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11s-camera-app-glitch-afc-error/"><u>Resolving Windows 11'S Camera App Glitch: AFC Error</u></a></li>
<li><a href="https://driver-install.techidaily.com/configure-printer-canon-mx870-to-work-with-win-versions/"><u>Configure Printer: Canon MX870 to Work with Win Versions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-false-virus-detection-issue/"><u>Overcoming Chrome’s False Virus Detection Issue</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-fixing-black-screens-and-blank-cursors-on-win11/"><u>Master the Art of Fixing Black Screens & Blank Cursors on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-access-denied-error-on-windows-11/"><u>5 Ways to Fix the “Access Denied” Error on Windows 11</u></a></li>
</ul></div>
