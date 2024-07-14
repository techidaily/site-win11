---
title: Comprehensive Guide to Fixing Winget on W11
date: 2024-07-13T10:07:41.168Z
updated: 2024-07-14T10:07:41.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Guide to Fixing Winget on W11
excerpt: This Article Describes Comprehensive Guide to Fixing Winget on W11
keywords: Winget Troubleshooting,W11 Winget Repair,Fix Winget Errors,Winget Installation,Resolve Winget Issue,Windows 11 Winget FIX,Winget Setup Guide
thumbnail: https://thmb.techidaily.com/48b583faa31b393aa904516c2278bd0e1546bcda1fa4122648e108e1ee1f91de.jpg
---

## Comprehensive Guide to Fixing Winget on W11

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
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-curbing-virtual-disk-service-malfunction/"><u>Strategies: Curbing Virtual Disk Service Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-net-not-installed-app-warning/"><u>Solving Windows' .NET Not Installed App Warning</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-realme-narzo-n53-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Realme Narzo N53 Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-inaccessible-secure-boot-in-windows-bios/"><u>Solving the Puzzle of Inaccessible Secure Boot in Windows BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winmedia-server-error/"><u>Troubleshooting WinMedia Server Error</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-repairing-your-windows-headsets-microphone/"><u>Addressing and Repairing Your Windows Headset's Microphone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-crafting-breathtaking-time-lapses-with-gopro/"><u>2024 Approved  The Ultimate Guide to Crafting Breathtaking Time-Lapses with GoPro</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/tep-by-step-process-to-crafting-impressive-youtube-shorts-templates/"><u>[New] Step-By-Step Process to Crafting Impressive YouTube Shorts Templates</u></a></li>
<li><a href="https://extra-skills.techidaily.com/is-photoshops-image-smoothing-worth-the-hype-for-2024/"><u>Is Photoshop's Image Smoothing Worth the Hype for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-s-top-free-mkv-splitters-trim-and-edit-with-ease-for-2024/"><u>New S Top Free MKV Splitters Trim and Edit with Ease for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-step-by-step-screen-recording-for-snapchat-stories-on-mobile/"><u>[New] 2024 Approved  Step-by-Step Screen Recording for Snapchat Stories on Mobile</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-spotify-promos-your-comprehensive-guide/"><u>2024 Approved  Mastering Spotify Promos  Your Comprehensive Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-6s-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 6s</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-se-without-a-passcode-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone SE Without a Passcode</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-basic-to-brilliant-transforming-your-videos-with-cool-effects/"><u>From Basic to Brilliant Transforming Your Videos with Cool Effects</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-secrets-to-featuring-on-youtube-a-comprehensive-walkthrough/"><u>[Updated] Secrets to Featuring on YouTube  A Comprehensive Walkthrough</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-content-with-these-20-pro-video-shortcuts/"><u>Elevate Your Content With These 20 Pro Video Shortcuts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-behind-the-scenes-using-instagrams-virtual-backdrops/"><u>[New] Behind-the-Scenes  Using Instagram's Virtual Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtube-for-educators-maximizing-its-classroom-potential-for-2024/"><u>[Updated] YouTube for Educators  Maximizing Its Classroom Potential for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719363401331-win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again!</u></a></li>
<li><a href="https://win11.techidaily.com/windows-unseen-the-emergence-of-ai-futures/"><u>Windows Unseen: The Emergence of AI Futures</u></a></li>
<li><a href="https://win11.techidaily.com/boost-typing-prowess-changing-and-adding-keyboards-for-win-11/"><u>Boost Typing Prowess: Changing and Adding Keyboards for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-code-navigating-through-lost-windows-1110-patches/"><u>Unlock the Code: Navigating Through Lost Windows 11/10 Patches</u></a></li>
<li><a href="https://win11.techidaily.com/unique-visuals-for-your-window-terminal/"><u>Unique Visuals for Your Window Terminal</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-best-of-the-best-top-5-video-editing-apps-for-iphone-users-for-2024/"><u>New Best of the Best Top 5 Video Editing Apps for iPhone Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-elite-8-video-grabber-utilities/"><u>In 2024, Elite 8 Video Grabber Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pc-transferring-preferences-from-one-to-another/"><u>Securing Your PC: Transferring Preferences From One to Another</u></a></li>
<li><a href="https://win11.techidaily.com/the-final-countdown-for-windows-xp-7-and-81-lifeline-on-microsoft/"><u>The Final Countdown for Windows XP, 7 & 8.1 Lifeline on Microsoft</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-creating-a-safe-mc-habitat-plan-6/"><u>2024 Approved  Creating a Safe MC Habitat  Plan #6</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-realme-c55-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-keep-your-tweets-compliant-with-aspect-ratio-requirements/"><u>[New] Keep Your Tweets Compliant with Aspect Ratio Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-youtube-metrics-with-ease/"><u>2024 Approved  Navigating YouTube Metrics with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-10-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-desktop-menus-in-win-1011/"><u>Troubleshooting Non-Responsive Desktop Menus in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-the-dual-identity-approach-for-influential-tiktok-presence/"><u>[New] 2024 Approved  The Dual Identity Approach for Influential TikTok Presence</u></a></li>
<li><a href="https://win11.techidaily.com/tips-how-to-view-excel-files-in-notepad/"><u>Tips: How to View Excel Files in Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-photography-hacks-upside-down-and-sideways-shots/"><u>2024 Approved  IPhone Photography Hacks  Upside-Down & Sideways Shots</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ree-visual-templates-to-upgrade-your-profile-for-2024/"><u>[New] Free Visual Templates to Upgrade Your Profile for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-designing-with-dirt-incorporating-natural-elements-into-urban-areas/"><u>2024 Approved  Designing with Dirt  Incorporating Natural Elements Into Urban Areas</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-grant-write-access-for-steam-folders-in-win-11/"><u>Techniques to Grant Write Access for Steam Folders in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-scheduler-issues-restore-smoothness/"><u>Tackle Windows Scheduler Issues, Restore Smoothness</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/ultimate-guide-to-dynamic-ducking-the-five-must-have-audio-processors-for-clearer-stereo-separation/"><u>Ultimate Guide to Dynamic Ducking The Five Must-Have Audio Processors for Clearer Stereo Separation</u></a></li>
<li><a href="https://audio-editing.techidaily.com/digital-music-layering-and-editing-suite-for-2024/"><u>Digital Music Layering & Editing Suite for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cutting-edge-templates-unlocking-your-videos-potential-for-2024/"><u>[Updated] Cutting-Edge Templates Unlocking Your Video's Potential for 2024</u></a></li>
</ul></div>
