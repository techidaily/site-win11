---
title: "Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091"
date: 2024-08-15T23:17:37.998Z
updated: 2024-08-16T23:17:37.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091"
excerpt: "This Article Describes Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091"
keywords: Win11 EmptyDirError,Windows 11 DirIssue,X070091 FileError,NonEmptyDirWin11,ErrorCode0X80070091,FixWindows11Err,DirectoryNotEmptyW11
thumbnail: https://thmb.techidaily.com/6490fa2e8c158c917a608e37e654c53e5a410f7e37ed3b9237ae0e8dd67dcf2f.jpg
---

## Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-enhancing-narrative-flow-integrating-chapters-into-your-youtube-content/"><u>[New] 2024 Approved  Enhancing Narrative Flow  Integrating Chapters Into Your YouTube Content</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-change-snapchat-voice-in-minutes-using-twin-methods/"><u>[New] In 2024, Change Snapchat Voice in Minutes Using Twin Methods</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-vs-gopro-hero-session-and-polaroid-cube-top-pick-for-filmmakers-for-2024/"><u>[New] Vs. GoPro Hero Session & Polaroid Cube  Top Pick for Filmmakers for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-convert-srt-with-ease-the-finest-free-converters-ranked/"><u>[Updated] 2024 Approved  Convert SRT with Ease - The Finest FREE Converters Ranked</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimal-voice-processing-software-solutions/"><u>2024 Approved  Optimal Voice Processing Software Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/close-all-easy-as-1-2-3-windows-multi-app-command/"><u>Close All, Easy as 1-2-3: Windows Multi-App Command</u></a></li>
<li><a href="https://win11.techidaily.com/demonstrating-the-power-of-powershell-removing-restrictions-on-windows/"><u>Demonstrating the Power of PowerShell: Removing Restrictions on Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-vivo-y27-4g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Vivo Y27 4G Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-for-captivating-images-and-memorable-slideshows-in-win11s-photography-platform/"><u>Expert Insights for Captivating Images and Memorable Slideshows in Win11's Photography Platform</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-system-audio-windows-11-mixer-configuration-steps/"><u>Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-solve-the-persistent-problem-of-vray-crashes-in-windows-or-mac-systems/"><u>How to Solve the Persistent Problem of Vray Crashes in Windows or Mac Systems</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-file-fixation-powerpoint-saves-crisis-solutions-win11/"><u>Immediate File Fixation: PowerPoint Saves Crisis, Solutions WIN11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-realme-gt-5-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Realme GT 5</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-what-lies-beneath-an-exploration-into-youtubes-unlisted-video-space/"><u>In 2024, What Lies Beneath  An Exploration Into YouTube's Unlisted Video Space</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-essential-steps-for-using-dev-drive/"><u>Navigating Windows 11: Essential Steps for Using Dev Drive</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-credential-vault-access-blocks/"><u>Overcome Credential Vault Access Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/phoenix-rise-revive-gaming-pcs-with-atlasos/"><u>Phoenix Rise: Revive Gaming PCs with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-hacked-no-more-winning-encryption-tools-ranked-149-chars/"><u>Privacy Hacked No More: Winning Encryption Tools Ranked (149 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-the-heart-of-windows-11-system32/"><u>Probing Into the Heart of Windows 11: System32</u></a></li>
<li><a href="https://win11.techidaily.com/recording-games-simply-mastering-screen-captures-with-intel-tools/"><u>Recording Games Simply: Mastering Screen Captures with Intel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hibernation-a-windows-users-guide/"><u>Resurrecting Hibernation: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pc-display-interactive-and-lively-windows-11-walls/"><u>Revitalize Your PC Display: Interactive and Lively Windows 11 Walls</u></a></li>
<li><a href="https://driver-install.techidaily.com/setup-netgear-1200-mbps-wi-fi-pcie-adapter-drivers/"><u>Setup NETGEAR 1200 Mbps Wi-Fi PCIe Adapter Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-trembling-cursor-a-guide-to-windows/"><u>Stop the Trembling Cursor: A Guide to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-increase-win11-icons-size/"><u>Techniques to Increase Win11 Icons Size</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-windows-photo-management-tools-an-essential-guide/"><u>Top 7 Windows Photo Management Tools: An Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-glitches-solutions-guide/"><u>Unraveling WINDOWS 11 Glitches: Solutions Guide</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-powerpoint-wont-record-audio-while-recording-the-screen-on-windows/"><u>What to Do if PowerPoint Won’t Record Audio While Recording the Screen on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
</ul></div>
