---
title: Unraveling Nonexistent Device Alert in Windows 11
date: 2024-08-23T06:06:19.831Z
updated: 2024-08-24T06:06:19.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Nonexistent Device Alert in Windows 11
excerpt: This Article Describes Unraveling Nonexistent Device Alert in Windows 11
keywords: Windows 11 Alerts,Win11 Fake Devices,Unique WinAlert,NoExist Device Warning,False Win Device Notify,Resolve WinFake Alerter,Erroneous Win Notification
thumbnail: https://thmb.techidaily.com/e6d973791325054ad0d7f0fcd99fd3ff0a56a44316e750df20403e0686bc2309.jpg
---

## Unraveling Nonexistent Device Alert in Windows 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://vp-tips.techidaily.com/new-deciphering-variances-between-standard-and-immersive-video-tech/"><u>[New] Deciphering Variances Between Standard & Immersive Video Tech</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-explore-youtube-rankings-seo-tools-for-peak-performance/"><u>[New] Explore YouTube Rankings  SEO Tools for Peak Performance</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-freely-capture-perfection-the-leading-10-high-quality-recorders/"><u>[New] Freely Capture Perfection  The Leading 10 High-Quality Recorders</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-future-of-virtual-game-viewership-income-for-2024/"><u>[New] Future of Virtual Game Viewership Income for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-how-to-use-dslr-for-facebook-live-on-you-pc-or-mac/"><u>[New] How to Use DSLR for Facebook Live on You PC or Mac?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-strategic-planning-making-memorable-tiktok-videos/"><u>[New] In 2024, Strategic Planning  Making Memorable TikTok Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-crafting-captivating-edu-vids-on-youtube-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Crafting Captivating Edu-Vids on YouTube  A Step-by-Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-freenoweb-recorder-app-evaluation-insights/"><u>[Updated] 2024 Approved  FreenoWeb Recorder App Evaluation Insights</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-christian-hymnal-options-for-ringtone-customization/"><u>[Updated] Christian Hymnal Options for Ringtone Customization</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-how-to-screen-record-on-ipad-more-easily/"><u>[Updated] In 2024, How to Screen Record on iPad More Easily?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-pubg-effective-techniques-for-altering-your-vocal-presence/"><u>2024 Approved  Mastering PUBG  Effective Techniques for Altering Your Vocal Presence</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/a-new-era-of-capturing-screens-camstudio-2023-reviewed/"><u>A New Era of Capturing Screens? CamStudio 2023 Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-not-met-requirements-in-win11-os/"><u>Deciphering and Fixing ‘Not Met Requirements’ in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-audacitys-error-9999-on-win1011-systems/"><u>Decoding Audacity's Error 9999 on WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ease-upgrade-rejections-adobe-fix-guide/"><u>Ease Upgrade Rejections: Adobe Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/ensure-your-hardware-meets-new-windows-requirements/"><u>Ensure Your Hardware Meets New Windows Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-conquering-windows-11-display-preferences/"><u>Expert Guide: Conquering Windows 11 Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-noisy-recording-in-powerpoint-screen-casts-on-pc/"><u>Fixing Noisy Recording in PowerPoint Screen Casts on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-nubia-red-magic-8s-proplus-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Nubia Red Magic 8S Pro+? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-msresouce-and-apptext-on-w11-os/"><u>How to Fix Error: MsResouce and AppText on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-character-map-not-working-on-windows/"><u>How to Fix the Character Map Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-delete-key-not-working-on-windows/"><u>How to Fix the Delete Key Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-restore-file-explorers-classic-ribbon-interface-in-windows-11/"><u>How to Restore File Explorer’s Classic Ribbon Interface in Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-craft-your-own-visual-story-iphones-top-10-image-design-techniques/"><u>In 2024, Craft Your Own Visual Story  IPhone's Top 10 Image Design Techniques</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-itel-s23-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Itel S23 Without PUK Codes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unobstructed-movie-magic-erasing-youtube-borders/"><u>In 2024, Unobstructed Movie Magic  Erasing YouTube Borders</u></a></li>
<li><a href="https://win11.techidaily.com/increase-proficiency-with-these-6-expertly-designed-trackers/"><u>Increase Proficiency with These 6 Expertly Designed Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-top-4-windows-programs-for-webp-image-viewer/"><u>Introducing Top 4 Windows Programs for WebP Image Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-transfer-success-on-modern-windows-os/"><u>Mastering Data Transfer Success on Modern Windows OS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/optimize-your-social-media-with-autoplay-vids-on-fb-for-2024/"><u>Optimize Your Social Media with Autoplay Vids on FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permissions-obstacles-for-os-installation/"><u>Overcoming Permissions Obstacles for OS Installation</u></a></li>
<li><a href="https://win11.techidaily.com/redesigning-windows-removed-characteristics/"><u>Redesigning Windows: Removed Characteristics</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-windows-11-default-search-options/"><u>Reinstating Windows 11 Default Search Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-steam-connection-to-your-windows-system/"><u>Restoring Steam Connection to Your Window's System</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-recovering-a-disabled-delete-functionality/"><u>Solutions for Recovering a Disabled Delete Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-entry-to-your-fileshare-onedrive-troubleshooting-guide/"><u>Streamline Entry to Your Fileshare: OneDrive Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-quest-secrets-to-mac-address-on-windows-11/"><u>Streamlining Your Quest: Secrets to Mac Address on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-alias-names-for-application-launches/"><u>The Essence of Alias Names for Application Launches</u></a></li>
<li><a href="https://win11.techidaily.com/the-illusion-of-choice-confronting-microphone-and-camera-shackles/"><u>The Illusion of Choice: Confronting Microphone and Camera Shackles</u></a></li>
<li><a href="https://win11.techidaily.com/title-customize-icon-spacing-on-modern-and-classic-windows-oses/"><u>Title: Customize Icon Spacing on Modern & Classic Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-a-missing-msvcr110dll/"><u>Understanding & Correcting a Missing Msvcr110.dll</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-full-capability-of-windows-11s-problem-solvers/"><u>Unlocking Full Capability of Windows 11'S Problem Solvers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-powershell-tactics-to-reverse-error-message-about-disabled-scripts/"><u>Unlocking PowerShell: Tactics to Reverse Error Message About Disabled Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-cure-for-hyper-v-error-code-0x8009030e/"><u>Unlocking Windows: Cure for Hyper-V Error Code 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-next-gen-phone-integration/"><u>Unveiling Windows 11'S Next-Gen Phone Integration</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-the-ultimate-guide-for-the-10-leading-slow-motion-cameras/"><u>Updated 2024 Approved The Ultimate Guide for the 10 Leading Slow-Motion Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/windows-glitches-end-self-scrolling-panels-here/"><u>Windows Glitches? End Self-Scrolling Panels Here</u></a></li>
</ul></div>
