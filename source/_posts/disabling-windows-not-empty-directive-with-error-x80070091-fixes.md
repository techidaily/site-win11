---
title: Disabling Windows' Not Empty Directive with Error X80070091 Fixes
date: 2024-08-08T13:17:33.873Z
updated: 2024-08-09T13:17:33.873Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows' Not Empty Directive with Error X80070091 Fixes
excerpt: This Article Describes Disabling Windows' Not Empty Directive with Error X80070091 Fixes
keywords: Windows Error X80070091,NotEmptyDirective Disable,Empty Property Fix,Directive Error Solve,Windows XP8007Error,System Update X8007,Resolve WindowsX8007
thumbnail: https://thmb.techidaily.com/56c9727e1647faa9df05a7ff87a2cebb670ed94ea60d5a674997e4383f15e6a2.jpg
---

## Disabling Windows' Not Empty Directive with Error X80070091 Fixes

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-essential-knowledge-for-capturing-stellar-tiktok-videos/"><u>[New] 2024 Approved  Essential Knowledge for Capturing Stellar TikTok Videos</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-5-best-snipping-tools-for-mac/"><u>[Updated] 5 Best Snipping Tools for Mac</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-potential-secrets-for-career-growth-in-designing/"><u>[Updated] Unleash Potential  Secrets for Career Growth in Designing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-innovative-methods-for-mac-screenshot-format-change/"><u>2024 Approved  Innovative Methods for Mac Screenshot Format Change</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-30-slept-on-speech-to-text-apps-for-macos-users/"><u>2024 Approved  Top 30 Slept-On Speech to Text Apps for macOS Users</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-gap-fixing-laptop-and-phone-connection-discrepancies/"><u>Bridge Gap: Fixing Laptop and Phone Connection Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-connecting-your-computer-again/"><u>Bridge the Gap: Connecting Your Computer Again</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-between-windows-and-wsl-with-post-update-strategies/"><u>Bridging Gaps Between Windows & WSL With Post-Update Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-local-libraries-and-online-oceans-dropbox-googledrive-on-c/"><u>Bridging Local Libraries & Online Oceans: Dropbox, GoogleDrive on C:/</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-windows-explorer-tab-lapses/"><u>Bridging Windows Explorer Tab Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/bring-order-to-your-notetaking-chaos-using-obsidian-palette/"><u>Bring Order to Your Notetaking Chaos Using Obsidian Palette</u></a></li>
<li><a href="https://win11.techidaily.com/bring-the-spirit-of-christmas-alive-with-these-wonderful-windows-themes/"><u>Bring the Spirit of Christmas Alive With These Wonderful Windows Themes</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-back-typical-window-explorer-options/"><u>Bringing Back Typical Window Explorer Options</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-winget-back-online-window-11-edition/"><u>Bringing Winget Back Online: Window 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-connections-ps3-dualshock-on-windows/"><u>Bypass Connections: PS3-DualShock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-oculus-setup-errors-with-proven-win11win10-methods/"><u>Bypass Oculus Setup Errors with Proven Win11/Win10 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-update-warnings-with-these-4-tips/"><u>Bypass Update Warnings with These 4 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blocked-onedrive-fixes-for-windows-users/"><u>Bypassing Blocked OneDrive: Fixes for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-internal-failure-for-smooth-rd-session/"><u>Bypassing Internal Failure for Smooth RD Session</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-secure-answers-for-win-11s-default-administrator/"><u>Bypassing Secure Answers for Win 11'S Default Administrator</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumble-errors-on-microsoft-store-win-1011/"><u>Bypassing Server Stumble Errors on Microsoft Store, Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-termination-error-a-guide-for-windows-users/"><u>Bypassing Termination Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-wsl-smart-choice/"><u>Bypassing WSL - Smart Choice</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fixing-outdated-windows-user-password-issue/"><u>Bypassing: Fixing Outdated Window's User Password Issue</u></a></li>
<li><a href="https://win11.techidaily.com/cease-unsolicited-search-menu-activation-win11-style/"><u>Cease Unsolicited Search Menu Activation, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/change-windows-11-taskbar-size/"><u>Change Windows 11 Taskbar Size</u></a></li>
<li><a href="https://win11.techidaily.com/chatgpt-deployment-for-windows-computers/"><u>ChatGPT Deployment for Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-constant-pc-startup-in-bios-mode/"><u>Circumventing Constant PC Startup in BIOS Mode</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-obstacles-with-amd-195-setup-on-pcs/"><u>Circumventing Obstacles with AMD 195 Setup on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/classic-game-connector-directing-past-fun-into-the-future/"><u>Classic Game Connector: Directing Past Fun Into the Future</u></a></li>
<li><a href="https://win11.techidaily.com/clear-out-clutter-personalize-your-w11-workspace/"><u>Clear Out Clutter: Personalize Your W11 Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-nine-tricks-to-dodge-steady-windows-update-stalls/"><u>Clear the Path: Nine Tricks to Dodge Steady Windows Update Stalls</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-from-the-recycle-bin-in-win-11-edition/"><u>Clearing Errors From the Recycle Bin in Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-successfully-downloading-from-the-ms-store/"><u>Clearing Errors: Successfully Downloading From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-for-startup-display-in-taskbar/"><u>Clearing the Path for Startup Display in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-disk-needs-format-warning-on-windows/"><u>Clearing Up 'Disk Needs Format' Warning on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusions-removing-read-only-from-folders/"><u>Clearing Up Confusions: Removing Read-Only From Folders</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dark-screen-with-windows-webcam/"><u>Clearing Up Dark Screen with Windows Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/cleverly-camouflaged-these-programs-slow-down-windows-users/"><u>Cleverly Camouflaged, These Programs Slow Down Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/code-28-error-woes-heres-your-ultimate-windows-hack-for-a-smooth-fix/"><u>Code 28 Error Woes? Here's Your Ultimate Windows Hack for a Smooth Fix</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/discover-the-top-9-free-online-tools-to-craft-your-logo/"><u>Discover the Top 9 Free Online Tools to Craft Your Logo</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-itel-s23-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Itel S23 Phone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-exploring-roku-watching-facebook-live-effortlessly/"><u>In 2024, Exploring Roku  Watching Facebook Live Effortlessly</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-insightful-guide-on-the-best-gopro-headsets-6-and-beyond/"><u>In 2024, Insightful Guide on The Best GoPro Headsets  #6 & Beyond</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-the-art-of-decreasing-decibents-a-guide-to-fading-out-sounds/"><u>In 2024, Mastering the Art of Decreasing Decibents  A Guide to Fading Out Sounds</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-6-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 6® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://extra-information.techidaily.com/poker-professional-panelisms/"><u>POKER PROFESSIONAL PANELISMS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-honor-x9a-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Honor X9a Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/screen-recording-innovations-a-comparative-look/"><u>Screen Recording Innovations  A Comparative Look</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-ultimate-guide-to-unlocking-your-iphone-se-2022-on-metropcs-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Your iPhone SE (2022) on MetroPCS</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-walkthrough-refreshing-cpu-driver-software-for-optimal-performance-in-windows/"><u>Ultimate Walkthrough: Refreshing CPU Driver Software for Optimal Performance in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivos-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Vivos Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://extra-resources.techidaily.com/wheres-the-community-twitch-and-youtube-side-by-side/"><u>Where's the Community? Twitch & YouTube Side by Side</u></a></li>
</ul></div>
