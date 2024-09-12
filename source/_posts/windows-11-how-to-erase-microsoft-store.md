---
title: "Windows 11: How to Erase Microsoft Store"
date: 2024-09-11T09:37:33.107Z
updated: 2024-09-12T09:37:33.107Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115919/19272" target="_top" id="2115919">
  <img src="//a.impactradius-go.com/display-ad/19272-2115919" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115919/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-mastering-stardews-core-principles-and-secrets-with-special-emphasis-on-ginger-island/"><u>[New] In 2024, Mastering Stardew's Core Principles and Secrets, With Special Emphasis on Ginger Island</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-video-capture-app-for-fb-messenger-for-2024/"><u>[New] Video Capture App for FB Messenger for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-secrets-to-selecting-the-best-online-game-coverage/"><u>[Updated] 2024 Approved Secrets to Selecting the Best Online Game Coverage</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-how-to-share-screen-on-google-meet-desktop-and-mobile/"><u>[Updated] In 2024, How to Share Screen on Google Meet [Desktop and Mobile]</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-obs-and-youtube-a-beginners-live-stream-blueprint/"><u>[Updated] In 2024, OBS and Youtube A Beginner's Live Stream Blueprint</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-affordable-screen-recorders-with-extra-features/"><u>2024 Approved Affordable Screen Recorders with Extra Features</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-conversion-wizardry-zip-to-subrip-transformation/"><u>2024 Approved Conversion Wizardry ZIP to SubRip Transformation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-from-individualist-to-institutional-influence-in-the-youtube-universe/"><u>2024 Approved From Individualist to Institutional Influence in the YouTube Universe</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-essential-guide-to-youtube-edits-with-premiere-pro/"><u>2024 Approved The Essential Guide to YouTube Edits with Premiere Pro</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-windows-snap-shotting-simplified/"><u>2024 Approved Windows Snap Shotting Simplified</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-file-properties-on-windows-platforms/"><u>Customizing File Properties on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-lunar-client-not-functional-message-in-os/"><u>Dealing with the Lunar Client Not Functional Message in OS</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-unwanted-edge-desktop-buttons/"><u>Disabling Unwanted Edge Desktop Buttons</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-leading-tv-streaming-services-ranked-and-reviewed/"><u>Discover the Leading TV Streaming Services - Ranked and Reviewed!</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-boot-up-windows-startup-with-notebooks-available/"><u>Efficient Boot-Up: Windows Startup with Notebooks Available</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-this-file-has-no-app-windows-issue/"><u>Eliminating 'This File Has No App' Windows Issue</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-xbox-service-interruptions-in-windows-os/"><u>Eliminating Xbox Service Interruptions in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-edge-safety-integrate-microsofts-defender-aguard/"><u>Enhance Edge Safety: Integrate Microsoft's Defender Aguard</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhancing-images-through-automated-dynamic-range-adjustments/"><u>Enhancing Images Through Automated Dynamic Range Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-consistent-reading-pane-openness-setup-for-email-attachments-in-ms-word/"><u>Ensuring Consistent Reading Pane Openness: Setup for Email Attachments In MS Word</u></a></li>
<li><a href="https://win11.techidaily.com/five-strategies-to-rejuvenate-file-explorer/"><u>Five Strategies to Rejuvenate File Explorer</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-logitech-g510-mouse-drivers-here-optimized-for-win7-win8-and-win10-systems/"><u>Get Your Logitech G510 Mouse Drivers Here: Optimized for Win7, Win8 and Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-finding-the-storage-for-your-desktop-pics/"><u>Guide: Finding the Storage for Your Desktop Pics</u></a></li>
<li><a href="https://win11.techidaily.com/how-and-when-to-use-the-ping-command-in-windows/"><u>How (and When) to Use the Ping Command in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-samsung-galaxy-s23-ultra-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Samsung Galaxy S23 Ultra To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-excel-2016-files-on-mac-complete-guide-by-stellar-guide/"><u>How to Recover Deleted Excel 2016 Files on Mac Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-hidden-results-from-your-windows-1011-search-tool/"><u>Identifying Hidden Results From Your Windows 10/11 Search Tool</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-techs-leap-into-the-win11-era-a-roadmap/"><u>Legacy Tech's Leap Into the Win11 Era: A Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-compatibility-issues-in-windows-11/"><u>Mastering Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-solutions-for-create-failed-issue-windows-error-30005/"><u>Mastering Solutions for Create Failed Issue - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-error-code-0x80070570-fixes-for-broken-files-on-windows-11/"><u>Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-intricate-boot-configuration-landscape/"><u>Navigating Through Windows' Intricate Boot Configuration Landscape</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-elevate-your-visuals-advanced-slideshow-techniques-in-final-cut-pro/"><u>New 2024 Approved Elevate Your Visuals Advanced Slideshow Techniques in Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-screen-quality-resetting-graphics-in-windows-11/"><u>Optimize Screen Quality: Resetting Graphics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-self-triggered-terminal-displays-in-windows/"><u>Preventing Self-Triggered Terminal Displays in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weekend-sale-buy-now-at-612yr-with-windows-10/"><u>Prime Weekend Sale: Buy Now at $6.12/Yr with Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/realignment-of-data-win11-hdd-optimization-techniques/"><u>Realignment of Data: Win11 HDD Optimization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-the-start-page-for-windows-task-manager/"><u>Redefining the Start Page for Windows Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functionality-to-windows-photos-with-registering-packages/"><u>Reinstating Functionality to Windows Photos with Registering Packages</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-gaps-between-windows-explorer-folders/"><u>Resolving Gaps Between Windows Explorer Folders</u></a></li>
<li><a href="https://fox-that.techidaily.com/revitalize-your-iphones-power-unit-a-step-by-step-calibration-process/"><u>Revitalize Your iPhone's Power Unit: A Step-by-Step Calibration Process</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-retro-games-achievement-integration-with-retroarch-tips/"><u>Revitalizing Retro Games: Achievement Integration with Retroarch Tips</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-and-solving-winerror-0x80071a90-in-windows/"><u>Simplifying & Solving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sixfold-solution-to-off-screen-woes-a-roadmap-for-rejuvenating-your-windows-desktop/"><u>Sixfold Solution to Off-Screen Woes: A Roadmap for Rejuvenating Your Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/solving-stranded-status-on-xbox-for-pc-a-practical-approach/"><u>Solving ‘Stranded’ Status on Xbox for PC: A Practical Approach</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-error-403-in-robloxwindows/"><u>Strategies to Resolve Error 403 in Roblox/Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-to-the-not-supported-interface-error/"><u>Swift Solutions to the Not-Supported Interface Error</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-dodging-enter-credentials-message-in-windows/"><u>Tactics for Dodging 'Enter Credentials' Message in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-apps-to-help-you-write-better-on-a-windows-pc/"><u>The 5 Best Apps to Help You Write Better on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-managing-deletion-alerts-in-windows-os/"><u>Tips for Managing Deletion Alerts in Windows OS</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/ultimate-guide-choosing-the-best-stabilizing-accessories/"><u>Ultimate Guide Choosing the Best Stabilizing Accessories</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-full-potential-with-microsofts-copilot-key/"><u>Unlocking Windows 11'S Full Potential with Microsoft's Copilot Key</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-code-4-spotify-connection-problem-in-w10w11/"><u>Unraveling the Code 4 Spotify Connection Problem in W10/W11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-techniques-for-embedding-images-into-music-tracks-for-2024/"><u>Updated Techniques for Embedding Images Into Music Tracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/whats-win32keygen-an-analysis-of-its-threats-and-remediation-processes-for-pcs/"><u>What's Win32/Keygen? An Analysis of Its Threats & Remediation Processes for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-taskbar-chat-discontinuation-what-does-this-mean-for-us/"><u>Windows 11 Taskbar Chat Discontinuation: What Does This Mean for Us?</u></a></li>
<li><a href="https://win11.techidaily.com/winning-task-managers-for-windows-10-and-11-users/"><u>Winning Task Managers for Windows 10 & 11 Users</u></a></li>
</ul></div>

