---
title: "Resolving Windows 11: Directory Emptiness Issue #0X80070091"
date: 2024-12-07T22:48:38.948Z
updated: 2024-12-13T06:56:42.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows 11: Directory Emptiness Issue #0X80070091"
excerpt: "This Article Describes Resolving Windows 11: Directory Emptiness Issue #0X80070091"
keywords: Win11 Error Code X,Clearing DIR Error W11,Fixing XP0091 in Windows,Solve Win11 Emptiness Issue,XError,Unblock Directory Error W11,Address XP0091 Problem W11
thumbnail: https://thmb.techidaily.com/0afe01c2e0f6b1c3ba9a8b87db7e0159921da64d28f55d619b92fd6d20b9c57c.jpg
---

## Resolving Windows 11: Directory Emptiness Issue #0X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-journey-to-the-heart-of-windows-11s-newest-gems/"><u>[New] 2024 Approved Journey to the Heart of Windows 11'S Newest Gems</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-premier-streamers-ultimate-concert-selection/"><u>[Updated] Premier Streamers Ultimate Concert Selection</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/aeiusys-compact-solar-generator-review-the-ideal-inverter-choice-for-essential-medical-equipment-care/"><u>Aeiusy's Compact Solar Generator Review: The Ideal Inverter Choice for Essential Medical Equipment Care</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/basic-screen-capture-windows-10-version-for-2024/"><u>Basic Screen Capture, Windows 10 Version for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-mastery-positioning-custom-shortcuts-by-power-button-in-windows-11/"><u>Command Mastery: Positioning Custom Shortcuts by Power Button in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-list-of-superior-screenshot-tools-excluding-windows/"><u>Comprehensive List of Superior Screenshot Tools Excluding Windows</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-crashes-winning-strategy-for-windows-11s-full-screen-in-sonic-games/"><u>Conquering Crashes: Winning Strategy for Windows 11'S Full-Screen in Sonic Games</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-chromes-file-upload-issues-a-windows-fix-guide/"><u>Eradicate Chrome's File Upload Issues: A Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-hardware-not-found-error-on-w11w10-system/"><u>Fixing 'Hardware Not Found' Error on W11/W10 System</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-logitech-g510-gamepad-drives-for-pcs-running-windows-7-to-10/"><u>Get Logitech G510 Gamepad Drives for PCs Running Windows 7 to 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/i-primissimi-6-convertitori-di-formato-mp4-gratis-e-piu-efficienti-scambio-video-con-facilita/"><u>I Primissimi 6 Convertitori Di Formato MP4 Gratis E Più Efficienti: Scambio Video Con Facilità!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-honor-magic-vs-2-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Honor Magic Vs 2 Phones with/without a PC</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-the-language-of-respectful-communication-in-japan/"><u>Learn the Language of Respectful Communication in Japan</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dual-monitor-configuration-a-compre-written-by-michael-nguyen-phd/"><u>Mastering Dual Monitor Configuration: A Compre Written by Michael Nguyen, PhD</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/precision-tech-selection-inside-scoop-by-toms-specialists/"><u>Precision Tech Selection - Inside Scoop by Tom's Specialists</u></a></li>
<li><a href="https://win11.techidaily.com/saving-the-day-reversing-blank-login-on-windows-11/"><u>Saving the Day: Reversing Blank Login on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smart-collaboration-at-your-fingertips-microsofts-ai-copilot-for-windows-11/"><u>Smart Collaboration at Your Fingertips: Microsoft's AI Copilot for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xc0f1103f-nvidia-software-glitches/"><u>Troubleshooting XC0F1103F Nvidia Software Glitches</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-skagen-falster-3-timeless-design-amidst-cutting-edge-smartwatch-innovations/"><u>Unveiling the Skagen Falster 3: Timeless Design Amidst Cutting-Edge Smartwatch Innovations</u></a></li>
</ul></div>

