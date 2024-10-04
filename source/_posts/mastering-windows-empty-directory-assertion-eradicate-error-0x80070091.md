---
title: Mastering Windows' Empty Directory Assertion - Eradicate Error 0X80070091
date: 2024-10-03T03:31:18.530Z
updated: 2024-10-03T23:07:29.808Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows' Empty Directory Assertion - Eradicate Error 0X80070091
excerpt: This Article Describes Mastering Windows' Empty Directory Assertion - Eradicate Error 0X80070091
keywords: WinEmptyDirErrorHandling,DefeatErrorCode0X80070091,EmptyDirectoryAssertionWin,WindowsError0X80070091Resolution,EradicateWindowsError0X80070091,FixEmptyDirWindowsIssue,Overcome0X80070091Windows
thumbnail: https://thmb.techidaily.com/81c104f653fc6628652d6140a521e94570f22aa2499ea9263be6a00f18fb658c.jpg
---

## Mastering Windows' Empty Directory Assertion - Eradicate Error 0X80070091

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
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148637/16836" target="_top" id="2148637">
  <img src="//a.impactradius-go.com/display-ad/16836-2148637" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148637/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-capturing-instagram-content-on-computers-techniques-and-tools-for-2024/"><u>[New] Capturing Instagram Content on Computers Techniques and Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transformative-approaches-to-engaging-with-online-video-reviews/"><u>[New] Transformative Approaches to Engaging with Online Video Reviews</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-5-best-360-degree-action-cameras-you-should-use/"><u>[Updated] 5 Best 360-Degree Action Cameras You Should Use</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-bold-transitions-a-beginners-guide-to-fades/"><u>[Updated] Bold Transitions A Beginner's Guide to Fades</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-direct-download-vs-alternative-store-instagram-reels-efficiently-for-2024/"><u>[Updated] Direct Download vs Alternative Store Instagram Reels Efficiently for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-measures-for-disk-read-failure-windows/"><u>Corrective Measures for Disk Read Failure Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-best-note-taking-solutions-our-expert-picks/"><u>Discover the Best Note Taking Solutions : Our Expert Picks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-yellowed-lcd-on-computer-screens/"><u>How to Fix Yellowed LCD on Computer Screens</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-samsung-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Samsung Pictures An Easy Method Explained.</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-motorola-moto-g23-phone-without-pin-by-drfone-android/"><u>How to Unlock Motorola Moto G23 Phone without PIN</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-issues-with-5ghz-wireless-networks/"><u>Navigating Windows 11 Issues with 5GHz Wireless Networks</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wi-fi-prompt-shortcomings-completing-missing-steps-in-windows/"><u>Overcoming Wi-Fi Prompt Shortcomings: Completing Missing Steps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pro-win-efficiency-selecting-the-best-apps-for-window-11-users/"><u>Pro-Win Efficiency: Selecting the Best Apps for Window 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-the-basics-of-windows-backup-configurations/"><u>Regaining the Basics of Windows Backup Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/self-sufficient-windows-patch-application/"><u>Self-Sufficient Windows Patch Application</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggling-to-connect-your-iphone-to-a-vpn-explore-these-7-resolution-steps/"><u>Struggling to Connect Your IPhone to a VPN? Explore These 7 Resolution Steps</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-cpu-state-showcase-at-peak-levels/"><u>Windows Guide: CPU State Showcase at Peak Levels</u></a></li>
</ul></div>

