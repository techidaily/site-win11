---
title: "Rectifying Directory Not Empty Issue with Error Code: 0X80070091 in Windows 11"
date: 2024-11-30T21:27:25.843Z
updated: 2024-12-06T23:01:13.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Rectifying Directory Not Empty Issue with Error Code: 0X80070091 in Windows 11"
excerpt: "This Article Describes Rectifying Directory Not Empty Issue with Error Code: 0X80070091 in Windows 11"
keywords: Windows 11 Error 0X80070091,Directory Empty Fix 0X80070091,0X80070091 in Windows,0X80070091 Directory Issue,Win11 Error Code,Emptying Directories, Error 0X80070091,Fix Windows Error 0X80070091
thumbnail: https://thmb.techidaily.com/e274a732c7d0d3f61527d48aecc65a65fbbf84ca45a89dafe19b065f7716c31c.jpg
---

## Rectifying Directory Not Empty Issue with Error Code: 0X80070091 in Windows 11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/1718144126937-new-2024-approved-how-many-seconds-is-a-20mb-video/"><u>[New] 2024 Approved How Many Seconds Is a 20Mb Video</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-crafting-masterpieces-top-meme-templates/"><u>[Updated] In 2024, Crafting Masterpieces Top Meme Templates</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/1-comprehensive-guide-step-by-step-instructions-on-downloading-videos-from-anon-v-platform/"><u>1. Comprehensive Guide: Step-by-Step Instructions on Downloading Videos From Anon-V Platform</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-command-center-hide-and-seek-guide-for-win/"><u>Elusive Command Center Hide-and-Seek Guide for Win</u></a></li>
<li><a href="https://games-able.techidaily.com/ghosting-your-digital-presence/"><u>Ghosting Your Digital Presence</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/lockdown-windows-7-ways-to-secure-your-system/"><u>Lockdown Windows: 7 Ways to Secure Your System</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-productivity-paste-and-jump-tutorials/"><u>Maximizing Productivity: Paste & Jump Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/muting-chromium-browser-sounds-on-windows-pc/"><u>Muting Chromium Browser Sounds on Windows PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/one-step-fix-for-your-magic-mouse-tracking-glitches/"><u>One-Step Fix For Your Magic Mouse Tracking Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-into-your-windows-11-apps-vault-explored/"><u>Pathways Into Your Windows 11 Apps Vault Explored</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cmd-setups-with-windows-shortcuts-a-practical-guide/"><u>Quick Cmd Setups with Windows Shortcuts: A Practical Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-obs-error-in-windows-11-during-streaming/"><u>Resolving OBS Error in Windows 11 During Streaming</u></a></li>
<li><a href="https://fox-tips.techidaily.com/seamlessly-shift-snaps-transferring-photos-from-ios-to-macos-catalina/"><u>Seamlessly Shift Snaps: Transferring Photos From iOS to macOS Catalina</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-resource-for-critical-hardware-and-software-analysis-by-tom/"><u>The Ultimate Resource for Critical Hardware and Software Analysis by Tom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-frozen-windows-run-logs/"><u>Unfreezing Frozen Windows Run Logs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-essential-pct-paths/"><u>Unlocking Windows: Essential PCT Paths</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-insert-song-into-imovie-media-library-for-2024/"><u>Updated Insert Song Into iMovie Media Library for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-change-your-onedrive-folders-address/"><u>Win 11: Change Your OneDrive Folder's Address</u></a></li>
</ul></div>

