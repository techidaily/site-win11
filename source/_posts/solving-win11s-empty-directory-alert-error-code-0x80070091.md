---
title: "Solving Win11's Empty Directory Alert (Error Code: 0X80070091)"
date: 2024-10-08T19:43:50.696Z
updated: 2024-10-15T22:55:09.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving Win11's Empty Directory Alert (Error Code: 0X80070091)"
excerpt: "This Article Describes Solving Win11's Empty Directory Alert (Error Code: 0X80070091)"
keywords: Win11 Error 0X80070091,Win11 Dir Alert Fix,Win11 Empty Directory,Win11 0X80070091 Solution,Fixing WinError 7,Win11 No Files Error,Resolving WinDir Issue
thumbnail: https://thmb.techidaily.com/05054cfe506491b99a35f8cf834debaebdbdb9bad3863dd1f8be14d01cc17569.jpg
---

## Solving Win11's Empty Directory Alert (Error Code: 0X80070091)

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  

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

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-20-gratis-plus-purchasable-luts-enhance-canon-cams/"><u>[New] 2024 Approved 20 Gratis + Purchasable LUTs Enhance Canon Cams</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/roubleshooting-techniques-for-optimized-video-shorts-for-2024/"><u>[New] Troubleshooting Techniques for Optimized Video Shorts for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-switching-spotify-playlists-transferring-to-youtube-music-format/"><u>2024 Approved Switching Spotify Playlists Transferring to YouTube Music Format</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-zte-nubia-flip-5g-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your ZTE Nubia Flip 5G Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/breaking-down-solution-strategies-for-troubleshooting-error-0xc19001e1-on-windows-10-machines/"><u>Breaking Down Solution Strategies for Troubleshooting Error 0Xc19001e1 on Windows 10 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-operational-failures-in-windows-os/"><u>Correcting Operational Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-resolving-d3d11-issues-for-w11w10-systems/"><u>Decoding and Resolving D3D11 Issues for W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-differences-exe-vs-msi-installation/"><u>Decoding the Differences: Exe vs Msi Installation</u></a></li>
<li><a href="https://win11.techidaily.com/discover-best-free-desktop-password-makers-on-windows/"><u>Discover Best Free Desktop Password Makers on Windows</u></a></li>
<li><a href="https://win-ratings.techidaily.com/free-online-conversion-changing-wav-files-into-swf-format-with-movavi/"><u>Free Online Conversion: Changing WAV Files Into SWF Format with Movavi</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-xiaomi-redmi-a2-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Xiaomi Redmi A2 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/launching-windows-11-mastering-the-taskbars-quick-search/"><u>Launching Windows 11: Mastering the Taskbar's Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-for-windows-msc-not-found-error/"><u>Mastering Troubleshooting for Windows MSC Not Found Error</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/int-pioneering-podium-places/"><u>Pinpoint Pioneering Podium Places</u></a></li>
<li><a href="https://win11.techidaily.com/realign-prime-video-subtitles-with-windows-11-settings/"><u>Realign Prime Video Subtitles with Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11s-5ghz-wi-fi-connection-problems/"><u>Resolving Windows 11'S 5GHz Wi-Fi Connection Problems</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-cybersecurity-why-more-than-one-antivirus-is-unnecessary-for-windows-pcs/"><u>Simplify Cybersecurity: Why More Than One Antivirus Is Unnecessary for Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-google-pixel-8-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Google Pixel 8? Here is How | Dr.fone</u></a></li>
</ul></div>

