---
title: How to Overcome Zero-Empty Directory Error in Windows 11 & 11
date: 2024-08-28T00:53:01.726Z
updated: 2024-08-29T00:53:01.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Overcome Zero-Empty Directory Error in Windows 11 & 11
excerpt: This Article Describes How to Overcome Zero-Empty Directory Error in Windows 11 & 11
keywords: WinErrorZeroEmptyDir,FixWindows11011Fault,Solve11ErrorDirEmpty,RemovingDirErrorWin11,WindowsErrorNoFileFound,ClearingDirectoryWindows,ZeroErrorHandlerWin11
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## How to Overcome Zero-Empty Directory Error in Windows 11 & 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
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
<li><a href="https://article-files.techidaily.com/new-in-depth-analysis-the-essence-of-the-google-podcast-application-for-2024/"><u>[New] In-Depth Analysis  The Essence of the Google Podcast Application for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-shortform-video-tweets-as-webm-sounds/"><u>[New] Shortform Video Tweets as WebM Sounds</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-advanced-3d-viewing-on-your-android-device-for-2024/"><u>[Updated] Advanced 3D Viewing on Your Android Device for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-craft-of-loom-seamless-screen-recording-guide/"><u>2024 Approved  The Craft of Loom  Seamless Screen Recording Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/achieving-financial-independence-on-youtube-via-views-for-2024/"><u>Achieving Financial Independence on YouTube via Views for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/curing-windows-error-elusive-startup-items/"><u>Curing Windows Error: Elusive Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-discarding-your-windows-11-trail/"><u>Deciphering and Discarding Your Windows 11 Trail</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-to-enhance-laptop-response-time-post-extended-setup/"><u>Effective Methods to Enhance Laptop Response Time Post-Extended Setup</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-airflow-for-windows-11-gadgets/"><u>Enhancing Airflow for Windows 11 Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/essential-to-do-list-software-for-windows-users/"><u>Essential To-Do List Software for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/formulating-enduring-file-disposal-strategies-on-windows-systems/"><u>Formulating Enduring File Disposal Strategies on Windows Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-lava-yuva-2-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Lava Yuva 2 Face Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-video-driver-crashed-and-was-reset-error-in-windows-1110/"><u>How to Fix the “Video Driver Crashed and Was Reset” Error in Windows 11/10</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-from-apple-iphone-13-mini-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data from Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-quick-settings-on-windows-11/"><u>How to Use Quick Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-your-operational-window-11-state/"><u>Identifying Your Operational Window 11 State</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-vivo-y55s-5g-2023-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Vivo Y55s 5G (2023) Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-y27s-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo Y27s FRP Android 10/11/12/13</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-apple-iphone-6s-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Your Apple iPhone 6s Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-final-cut-pro-x-the-art-of-freeze-frames-and-slow-motion-storytelling/"><u>New Final Cut Pro X The Art of Freeze Frames and Slow Motion Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workflow-with-windows-and-sudo-integration/"><u>Optimize Your Workflow with Windows & Sudo Integration</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-denial-on-windows-11/"><u>Overcoming File Access Denial on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-unlocking-your-os-control-panel/"><u>Quick Access: Unlocking Your OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/quick-method-to-shut-off-windows-11-alerts/"><u>Quick Method to Shut Off Windows 11 Alerts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Google Pixel 7a? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-color-from-chrome-on-pcs/"><u>Recovering Color From Chrome on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/remedies-for-low-memory-indicators-in-windows-based-vmware/"><u>Remedies for Low Memory Indicators in Windows-Based VmWare</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-iphone-12-pro-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of iPhone 12 Pro Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unselectable-text-in-windows-pdf-viewers/"><u>Resolve Unselectable Text in Windows' PDF Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-0x800700e9-on-xbox-game-pass-in-windows-11/"><u>Resolving 0X800700E9 on Xbox Game Pass in Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/seamless-gaming-effortlessly-fixing-recurring-outriders-crashes/"><u>Seamless Gaming: Effortlessly Fixing Recurring Outriders Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-power-management-hitch-with-third-party-software/"><u>Steps to Overcome Windows Power Management Hitch with Third-Party Software</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-no-data-usb-devices-in-microsoft-systems/"><u>Strategies for Fixing No-Data USB Devices in Microsoft Systems</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-stuck-easy-fixes-for-w11w10-users/"><u>Synapse Stuck? Easy Fixes for W11/W10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-xpatch-problem-error-code-0x80073712/"><u>Tackling XPatch Problem: Error Code 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-through-the-years-in-windows-os/"><u>Taskbar Through the Years in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peaceful-application-management-in-window-11/"><u>The Path to Peaceful Application Management in Window 11</u></a></li>
<li><a href="https://win11.techidaily.com/unite-pilot-and-ai-on-windows-11-after-disconnection/"><u>Unite Pilot & AI on Windows 11 After Disconnection</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-list-the-premier-pc-vr-headsets-of-2023-for-2024/"><u>Updated List  The Premier PC VR Headsets of 2023 for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-intel-stream-assist-and-how-does-it-make-game-streaming-better/"><u>What Is Intel Stream Assist and How Does It Make Game Streaming Better?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-iphone-11-pro-max-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud From your iPhone 11 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-influence-on-desktop-linux-landscape-shift/"><u>WSL Influence on Desktop Linux Landscape Shift</u></a></li>
</ul></div>
