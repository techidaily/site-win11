---
title: "Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091"
date: 2024-07-29T15:56:44.147Z
updated: 2024-07-30T15:56:44.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091"
excerpt: "This Article Describes Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091"
keywords: Directory Warning Bypass,Fix X80070091 Error,Empty Dir Warn Removal,X80070091 Solutions,Skip File Not Found,Override Folder Error,Handle DirectX Errors
thumbnail: https://thmb.techidaily.com/33c48593ec0173b68a8667f248e53142d39bc8c3611fadd3a7f85564f8ade76e.jpg
---

## Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
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
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-ultimate-fraps-experience-for-game-capture/"><u>[New] 2024 Approved  The Ultimate Fraps Experience for Game Capture</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harness-power-of-persuasion-with-these-tips-for-reddit/"><u>[New] Harness Power of Persuasion with These Tips for Reddit</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphone-techniques-for-seamless-image-to-pdf-conversion/"><u>[New] IPhone Techniques for Seamless Image-to-PDF Conversion</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-strategizing-live-broadcasts-turn-your-recordings-into-facebook-hits/"><u>[New] Strategizing Live Broadcasts  Turn Your Recordings Into Facebook Hits</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-smooth-iphone-screen-recording-made-simple/"><u>[Updated] 2024 Approved  Smooth iPhone Screen Recording Made Simple</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-boosting-social-media-presence-with-effective-fb-instream-ad-plans-for-2024/"><u>[Updated] Boosting Social Media Presence with Effective FB Instream Ad Plans for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-a-novel-approach-to-delivery-reinvented-box-revelations/"><u>2024 Approved  A Novel Approach to Delivery  Reinvented Box Revelations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-fidelity-videos-our-selection-of-the-three-finest-phones/"><u>2024 Approved  High Fidelity Videos  Our Selection of the Three Finest Phones</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-top-mp4-to-fb-transcoder/"><u>2024 Approved  Top MP4-to-FB Transcoder</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-gionee-f3-pro-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Gionee F3 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://driver-install.techidaily.com/gaomon-s620-setup-made-easy-download-now/"><u>Gaomon S620 Setup Made Easy - Download Now</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-tecno-camon-20-pro-5g-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Tecno Camon 20 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-oppo-a59-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Oppo A59 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-how-to-make-a-youtube-subscribe-link-easy/"><u>In 2024, How to Make a YouTube Subscribe Link - Easy!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-guide-to-creating-free-youtube-outros-1-6/"><u>In 2024, The Ultimate Guide to Creating FREE YouTube Outros #1-6</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-imessage-for-windows-expert-techniques-revealed/"><u>Leveraging iMessage for Windows: Expert Techniques Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-on-mending-windows-1011-corrupted-recycle-bin/"><u>Masterclass on Mending Windows 10/11 Corrupted Recycle Bin</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-free-video-trimming-software-10-online-options-reviewed/"><u>New In 2024, Free Video Trimming Software 10 Online Options Reviewed</u></a></li>
<li><a href="https://extra-support.techidaily.com/overcoming-virtual-reality-nausea-for-2024/"><u>Overcoming Virtual Reality Nausea for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-pc-saving-spotlight-pictures-as-wallpapers/"><u>Personalizing Your PC: Saving Spotlight Pictures as Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/power-buttons-ahead-crafting-shortcuts-on-windows-11/"><u>Power Buttons Ahead: Crafting Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-integration-into-win11-systems/"><u>PowerToys Integration Into Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-full-enter-key-capabilities-in-win-os/"><u>Regaining Full Enter Key Capabilities in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-setup-for-icloud-users-with-windows-pcs/"><u>Seamless Setup for iCloud Users with Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-telnet-enablement-in-win11/"><u>Step-by-Step: Telnet Enablement in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-savvy-in-the-world-of-windows-11/"><u>Sticky Note Savvy in the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-dolby-atmos-integration-in-windows-1011/"><u>The Ultimate Guide to Dolby Atmos Integration in Windows 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/top-10-causes-for-gaming-system-failures-solutions-guide/"><u>Top 10 Causes for Gaming System Failures: Solutions Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unleash-creativity-capturing-quality-videos-on-logitech-for-2024/"><u>Unleash Creativity  Capturing Quality Videos on Logitech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-of-your-computers-ram-type/"><u>Unlocking the Secret of Your Computer's RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-error-0x80300024-problems/"><u>Unraveling Windows' Error 0X80300024 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-lets-go-back-in-time-seventh-ranked-activision-titles/"><u>Xbox, Let's Go Back in Time: Seventh-Ranked Activision Titles</u></a></li>
</ul></div>
