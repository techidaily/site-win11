---
title: Steps to Overcome Not Empty Directory Problem in Windows OS
date: 2024-08-15T23:46:12.424Z
updated: 2024-08-16T23:46:12.424Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Overcome Not Empty Directory Problem in Windows OS
excerpt: This Article Describes Steps to Overcome Not Empty Directory Problem in Windows OS
keywords: Win Directory Clearance Guide,Fixing Empty Folder Errors,Windows Empty Directories Tips,Stop Empty Drive Warning,Solve Empty Directory OSX,Windows Folder Emptiness Fix,Empty Space Issue Resolution,Win Clear Empty Folder Tips,Fixing Empty Dir Errors Windows,Empty Drives in Windows Fix,Stop OS Error NotEmptyDir,Windows Directories Space Solve,Unblock Window Directory,Resolving Empty Space Issue Windows
thumbnail: https://thmb.techidaily.com/b366957cb2f5f0bbc845d34641faf6413a6383aa8049e6555ff0f80bdf97ed47.jpg
---

## Steps to Overcome Not Empty Directory Problem in Windows OS

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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
<li><a href="https://extra-approaches.techidaily.com/new-30plus-metaverse-quotes-to-inspire-you-ar-and-vr-included/"><u>[New] 30+ Metaverse Quotes to Inspire You [AR & VR Included]</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-from-jokes-to-laughter-waves-how-to-craft-memes-on-9gag/"><u>[New] In 2024, From Jokes to Laughter Waves  How to Craft Memes on 9GAG</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-reviving-relics-seamless-access-to-old-fb-narratives-on-tech/"><u>[New] In 2024, Reviving Relics  Seamless Access to Old FB Narratives on Tech</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-ultra-clear-gameplay-best-hdmi-21-monitors-for-ps5-gamers/"><u>[New] In 2024, Ultra-Clear Gameplay  Best HDMI 2.1 Monitors For PS5 Gamers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-master-the-art-of-video-editing-with-top-7-sounds-selections/"><u>[Updated] 2024 Approved  Master the Art of Video Editing with Top 7 Sounds Selections</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-eyecapture-facebook-content-saves/"><u>[Updated] EyeCapture  Facebook Content Saves</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-spotlight-on-10-youtube-channels-with-swift-popularity-boosts-for-2024/"><u>[Updated] Spotlight on 10 YouTube Channels With Swift Popularity Boosts for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-the-youtube-numbers-views-and-earnings-unpacked/"><u>2024 Approved  Navigating the Youtube Numbers  Views & Earnings Unpacked</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pioneering-color-correction-with-adobes-top-luts/"><u>2024 Approved  Pioneering Color Correction with Adobe’s Top LUTs</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-path-to-professional-gopro-time-lapse-cinematography/"><u>2024 Approved  The Path to Professional GoPro Time-Lapse Cinematography</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-uncover-the-best-online-church-streaming-options/"><u>2024 Approved  Uncover The Best Online Church Streaming Options</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-unlocking-the-world-of-premium-banners-for-media/"><u>2024 Approved  Unlocking the World of Premium Banners for Media</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-windows-startup-setup-options/"><u>A Step-by-Step Breakdown of Windows Startup Setup Options</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://win11.techidaily.com/curing-store-failures-the-quick-fix-for-error-code-x00000000-in-windows-11/"><u>Curing Store Failures: The Quick Fix for Error Code X00000000 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/decorate-your-screen-space-saving-spotlight-images-as-walls/"><u>Decorate Your Screen Space: Saving Spotlight Images as Walls</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-canon-pixma-mg7810-series-drivers-on-windows/"><u>Download Canon PIXMA MG7810 Series Drivers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-launch-windows-11-on-mac-through-parallels/"><u>Essential Steps to Launch Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/explore-and-manage-windows-11-writable-components/"><u>Explore and Manage Windows 11' Writable Components</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-success-elevating-winning-frames/"><u>Fast-Track to Success: Elevating Winning Frames</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-unused-disk-space-in-windows-efficiently/"><u>Harnessing Unused Disk Space in Windows Efficiently</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Xiaomi Redmi Note 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-a-disabled-app-in-windows/"><u>How to Unblock a Disabled App in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-oneplus-ace-2-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from OnePlus Ace 2 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-on-apple-iphone-13-mini-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled On Apple iPhone 13 mini? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-samsung-galaxy-xcover-7-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Samsung Galaxy XCover 7 Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://win11.techidaily.com/leap-ahead-your-in-store-purchase-speed-on-ms-platform/"><u>Leap Ahead Your In-Store Purchase Speed on MS Platform</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/logitech-g533-vocalization-headset-or-audio-revolution/"><u>Logitech G533 Vocalization - Headset or Audio Revolution?</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-cybersecurity-essential-windows-protection-tips/"><u>Mastery in Cybersecurity: Essential Windows Protection Tips</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-nonstop-teams-sign-ins-on-pc/"><u>Overcoming the Hurdle of Nonstop Teams Sign-Ins on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-utorrent-download-halt-on-windows-os/"><u>Overcoming uTorrent Download Halt on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-glance-windows-11-expert-guide-to-image-access/"><u>Quick Glance: Windows 11 Expert Guide to Image Access</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-accelerate-your-pcs-warmup-with-win11-tips/"><u>Ready, Set, Go! Accelerate Your PC's Warmup with Win11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-the-antique-ribbon-interface-of-explorer/"><u>Restoring the Antique Ribbon Interface of Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/reward-system-reboot-for-your-favorite-titles/"><u>Reward System Reboot for Your Favorite Titles</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-your-microphone-usage-with-keyboard-techniques-for-win-11/"><u>Speeding Up Your Microphone Usage with Keyboard Techniques for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/stay-on-top-of-your-windows-11-devices-with-our-5-crucial-uptime-methods/"><u>Stay on Top of Your Windows 11 Devices with Our 5 Crucial Uptime Methods</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/streamlined-process-altering-video-direction-in-vlc/"><u>Streamlined Process  Altering Video Direction in VLC</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-windows-embracing-ai-dominance/"><u>Tomorrow's Windows: Embracing AI Dominance</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-steps-before-factory-clearing-a-pc/"><u>Top 7 Steps Before Factory Clearing a PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-dll-file-disappearance-on-windows/"><u>Troubleshooting DLL File Disappearance on Windows</u></a></li>
<li><a href="https://fox-http.techidaily.com/ultimate-20-pubg-photo-mashups-without-copyrights/"><u>Ultimate 20 PUBG Photo Mashups, Without Copyrights</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-read-only-folders-a-step-by-step-guide/"><u>Unlocking Read-Only Folders: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-files-preventing-read-only-in-win11/"><u>Unlocking Your Files: Preventing Read-Only in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-blues-troubleshooting-rare-system-crashes/"><u>Windows Blues: Troubleshooting Rare System Crashes</u></a></li>
</ul></div>
