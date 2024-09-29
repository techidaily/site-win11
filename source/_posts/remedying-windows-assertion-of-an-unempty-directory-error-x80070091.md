---
title: Remedying Windows' Assertion of an Unempty Directory (Error X80070091)
date: 2024-09-21T17:18:06.753Z
updated: 2024-09-28T19:28:52.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying Windows' Assertion of an Unempty Directory (Error X80070091)
excerpt: This Article Describes Remedying Windows' Assertion of an Unempty Directory (Error X80070091)
keywords: Fix Windows EmptyDirError,Resolve Windows Dir Error X80070091,EmptyDirError Solution,Handle Unempty Directory Error,Clearing Windows Error X80070091,Troubleshoot Windows EmptyDir,Stop Windows Assertion Error
thumbnail: https://thmb.techidaily.com/176a1a151aeb9ebfdcfd4bd623625c32ca353b5d86117d513193a67649a60b72.jpg
---

## Remedying Windows' Assertion of an Unempty Directory (Error X80070091)

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
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
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
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
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
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/2024-approved-seamless-audio-integration-in-instagram-visuals-and-stories/"><u>2024 Approved Seamless Audio Integration in Instagram Visuals & Stories</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-streamline-your-social-experience-with-mobile-music-files/"><u>2024 Approved Streamline Your Social Experience with Mobile Music Files</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/9-innovative-applications-of-chatgpt-for-wellness/"><u>9 Innovative Applications of ChatGPT for Wellness</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-delete-dialogues-for-secure-computing/"><u>Controlling Delete Dialogues for Secure Computing</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/craft-your-contents-voyage-from-camera-to-instagram-tv/"><u>Craft Your Content's Voyage From Camera to Instagram TV</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-recordings-win-5-budget-friendly-filters/"><u>Enhance PC Recordings: Win 5 Budget-Friendly Filters</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-motorola-moto-g14-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Motorola Moto G14 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/legendary-lens-showdown-sj6-vs-the-four-k-visionaries-of-xiaomi-for-2024/"><u>Legendary Lens Showdown SJ6 Vs. The Four-K Visionaries of Xiaomi for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-diagnostics-timely-application-of-windows-ping/"><u>Navigating Network Diagnostics: Timely Application of Windows Ping</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-display-order-easy-windows-method/"><u>Reversing Display Order: Easy Windows Method</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-desktop-opt-for-smart-window-arrangement/"><u>Revolutionize Your Desktop: Opt for Smart Window Arrangement</u></a></li>
<li><a href="https://driver-download.techidaily.com/seamless-printing-downloading-and-installing-the-newest-drivers-for-brother-mfc-7360n-across-multiple-windows-versions/"><u>Seamless Printing: Downloading and Installing the Newest Drivers for Brother MFC-7360N Across Multiple Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/silent-restarts-a-windows-1011-guide-to-going-dark/"><u>Silent Restarts: A Windows 10/11 Guide to Going Dark</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-steam-performance-overcoming-degraded-download-rates/"><u>Skyrocket Steam Performance: Overcoming Degraded Download Rates</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-gopro-footage-made-easy-top-alternatives-to-gopro-studio-this-year-for-2024/"><u>Updated GoPro Footage Made Easy Top Alternatives to GoPro Studio This Year for 2024</u></a></li>
</ul></div>

