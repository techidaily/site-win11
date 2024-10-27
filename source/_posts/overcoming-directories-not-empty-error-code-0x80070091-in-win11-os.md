---
title: "Overcoming Directories Not Empty Error (Code: 0X80070091) in Win11 OS"
date: 2024-10-23T22:31:48.680Z
updated: 2024-10-26T21:01:54.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Directories Not Empty Error (Code: 0X80070091) in Win11 OS"
excerpt: "This Article Describes Overcoming Directories Not Empty Error (Code: 0X80070091) in Win11 OS"
keywords: Win11 Directory Fix,Win11 No Space Error,Code 0X80070091 Solution,Overcome Empty Directories,Windows 11 OS Bug Fixed,Remove 0X80070091,Win11 Directory Not Full
thumbnail: https://thmb.techidaily.com/6eaa3e36b8ce62866baa3f0397f35b108aa431d0b37d363e9ff789051431b8db.jpg
---

## Overcoming Directories Not Empty Error (Code: 0X80070091) in Win11 OS

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
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-quick-guide-altering-screen-colors-on-google-meet/"><u>[New] Quick Guide Altering Screen Colors on Google Meet</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleashing-premium-soundtracks-in-your-mp4-files-the-2024-guide/"><u>[New] Unleashing Premium Soundtracks in Your MP4 Files – The 2024 Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-compre-written-guide-on-incorporating-markup-features-in-youtube/"><u>[Updated] In 2024, Compre Written Guide on Incorporating Markup Features in YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unlock-the-potential-of-your-fb-cover-image-with-these-top-11-websites/"><u>2024 Approved Unlock the Potential of Your FB Cover Image with These Top 11 Websites</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://data-wizards.techidaily.com/data-recovery-essentials-stellars-mac-guide/"><u>Data Recovery Essentials - Stellar's Mac Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/deciphering-tesla-robotaxi-news-expected-value-range-launch-date-forecasts-technical-details-plus-fresh-rumors/"><u>Deciphering Tesla Robotaxi News - Expected Value Range, Launch Date Forecasts, Technical Details, Plus Fresh Rumors</u></a></li>
<li><a href="https://win11.techidaily.com/directing-group-policy-modifications-a-guide-to-single-user-targeting/"><u>Directing Group Policy Modifications: A Guide to Single User Targeting</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-windows-11-as-your-home-network-hub/"><u>Establishing Windows 11 as Your Home Network Hub</u></a></li>
<li><a href="https://win11.techidaily.com/extensive-expansion-excellent-not-entailed-in-mp60/"><u>Extensive Expansion, Excellent Not Entailed in MP60</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/finding-the-perfect-screen-recorder-for-schooling/"><u>Finding the Perfect Screen Recorder for Schooling</u></a></li>
<li><a href="https://fox-making.techidaily.com/fix-your-windows-eboardsearch-bar-a-complete-walkthrough-for-non-responsive-keys-on-win10/"><u>Fix Your Windows eboardSearch Bar - A Complete Walkthrough for Non-Responsive Keys on Win10</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-quick-refresh-of-critical-directories-in-ws11/"><u>Guide to Quick Refresh of Critical Directories in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-authentication-in-windows-11-os-setup/"><u>Mastering the Authentication in Windows 11 OS Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-note-adhesion-in-windows-11-and-10/"><u>Mastering Window Note Adhesion in Windows 11 & 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/multiversus-hiccups-resolved-a-step-by-step-guide-for-pc-players-struggling-with-startup-issues/"><u>MultiVersus Hiccups Resolved? A Step-by-Step Guide for PC Players Struggling with Startup Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-err-87-in-winos-correcting-loadlib-malfunction/"><u>Overcoming Err 87 in WinOS: Correcting LoadLib Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/preventative-measures-for-windows-date-and-time-stability/"><u>Preventative Measures for Windows Date & Time Stability</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-preventing-permanent-changes-without-backup/"><u>Techniques for Preventing Permanent Changes without Backup</u></a></li>
</ul></div>

