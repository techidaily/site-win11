---
title: How to Fix Empty Folder Problems in Win11 & 11 Error #0X80070091
date: 2024-10-13T20:46:18.655Z
updated: 2024-10-15T21:06:49.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Empty Folder Problems in Win11 & 11 Error #0X80070091
excerpt: This Article Describes How to Fix Empty Folder Problems in Win11 & 11 Error #0X80070091
keywords: Win11 Empty Folder Fix,110X80070091 Resolution,Win11 #0XError Solution,Windows 11 Empty Issue,File System Error Win11,Fixing 11 Empty Directory,Win11 Folder Not Found Error
thumbnail: https://thmb.techidaily.com/f00def1c04cb418f21da5c60f199b078da943127e970aa7acf9eb30479f71c91.jpg
---

## How to Fix Empty Folder Problems in Win11 & 11 Error #0X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-review-of-freewatch-webcam-recorder-app/"><u>[New] 2024 Approved Review of Freewatch Webcam Recorder App</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-comprehensive-guide-to-obtaining-visual-assets/"><u>[Updated] In 2024, Comprehensive Guide to Obtaining Visual Assets</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-final-step-delete-your-youtube-shorts-link/"><u>[Updated] The Final Step Delete Your YouTube Shorts Link</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/discover-the-leading-photo-restoration-services-of-202-comparing-the-advantages-and-disadvantages-a-comprehensive-list-of-the-best-options/"><u>Discover the Leading Photo Restoration Services of 202# Comparing the Advantages and Disadvantages: A Comprehensive List of the Best Options</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-n-versions-usage-insights/"><u>Exploring Windows N Versions: Usage Insights</u></a></li>
<li><a href="https://win11.techidaily.com/fix-freezing-vlc-swift-solution/"><u>Fix Freezing VLC - Swift Solution</u></a></li>
<li><a href="https://facebook.techidaily.com/guard-your-digital-world-identifying-fb-breaches/"><u>Guard Your Digital World: Identifying FB Breaches</u></a></li>
<li><a href="https://win11.techidaily.com/halt-discord-auto-launch-and-update-checks-on-windows-10/"><u>Halt Discord Auto-Launch & Update Checks on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-windows-11-secure-your-digital-assets/"><u>How Does Windows 11 Secure Your Digital Assets?</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-feast-on-a-gallery-ios-top-10-free-stunning-photo-collage-apps/"><u>In 2024, Feast on a Gallery IOS’ Top 10 FREE, Stunning Photo Collage Apps</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-pagefilesys-usage-and-importance-in-winos/"><u>Navigating Through Pagefile.sys Usage & Importance in WinOS</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-solution-reactivating-windows-support-for-logitech-control-software/"><u>Step-by-Step Solution: Reactivating Windows Support for Logitech Control Software</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-correcting-directx-install-errors/"><u>Steps for Correcting DirectX Install Errors</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-hackers-handbook-advanced-win11-tactics-for-2024/"><u>The Hacker's Handbook Advanced Win11 Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanism-behind-windows-reserve-memory-system/"><u>The Mechanism Behind Windows' Reserve Memory System</u></a></li>
</ul></div>

