---
title: Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11
date: 2024-08-08T13:23:12.300Z
updated: 2024-08-09T13:23:12.300Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11
excerpt: This Article Describes Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11
keywords: Directory Error 0X80070091,Windows 11 Fault Alert,Empty Directory Fix Win11,Squashing #0XError,Directory Issue Resolution,Handle 0X70091 on Win11,Clear Empty Folder Error
thumbnail: https://thmb.techidaily.com/c8e68cffef41fc4061ac722c7019bbd23a7bd74185b074d0cf9fcbe34770c5fd.jpg
---

## Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
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
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-eastern-mini-homes-top-6-creative-concepts-in-mc/"><u>[New] 2024 Approved  Eastern Mini-Homes  Top 6 Creative Concepts in MC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-keyboard-warriors-guide-games-similar-to-gta-v/"><u>[New] In 2024, Keyboard Warriors' Guide  Games Similar to GTA V</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-cultivating-an-audience-naturally-youtubes-way/"><u>[Updated] In 2024, Cultivating an Audience Naturally - YouTube's Way</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-swift-snapshots-on-the-social-network/"><u>[Updated] Swift Snapshots on the Social Network</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-charting-the-course-to-earnings-with-youtube-videos/"><u>2024 Approved  Charting the Course to Earnings with YouTube Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-gigglegif-builder/"><u>2024 Approved  GiggleGif Builder</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-tecno-spark-20-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-pinpointing-hardware-identification-in-windows/"><u>Advanced Strategies for Pinpointing Hardware Identification in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/best-lighter-browsing-options-tested-for-memory-conservation/"><u>Best Lighter Browsing Options Tested For Memory Conservation</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/break-through-boundaries-15plus-best-free-video-starters/"><u>Break Through Boundaries  15+ Best Free Video Starters</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-window-systems-reliability-vs-performance/"><u>Bridging Gaps in Window Systems: Reliability Vs. Performance</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-x70-file-and-directory-recovery-on-windows-1011/"><u>Bypassing Error X70: File and Directory Recovery on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-edges-load-times-and-resource-use/"><u>Decreasing Edge's Load Times and Resource Use</u></a></li>
<li><a href="https://win11.techidaily.com/enliven-windows-11-desktop-a-step-by-step-guide-to-animated-walls/"><u>Enliven Windows 11 Desktop: A Step-by-Step Guide to Animated Walls</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tial-photo-and-film-capture-apps-iphone-and-android-edition-for-2024/"><u>Essential Photo & Film Capture Apps  IPhone & Android Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-win11-dns-client-service-adjustment/"><u>Essential Tips for Win11 DNS Client Service Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-lens-6-simple-steps-for-picture-spin-on-windows-11/"><u>Flip Your Lens: 6 Simple Steps for Picture Spin on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/gently-lowering-highs-a-guide-to-windowed-serenity/"><u>Gently Lowering Highs: A Guide to Windowed Serenity</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-the-required-apple-store-verification-for-apple-iphone-13-mini-drfone-by-drfone-ios/"><u>How To Bypass the Required Apple Store Verification For Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-13-mini-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 13 mini without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-6s-plus-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 6s Plus to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-closer-look-techniques-for-effective-collaboration-on-ms-teams/"><u>In 2024, Closer Look Techniques for Effective Collaboration on MS Teams</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-complete-dynamics-review-2023/"><u>In 2024, Complete Dynamics Review 2023</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-googles-augmented-reality-adornments/"><u>In 2024, Navigating Google's Augmented Reality Adornments</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-vivo-s17-pro-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Vivo S17 Pro</u></a></li>
<li><a href="https://extra-information.techidaily.com/layer-audio-onto-video-clips-in-premiere-pro/"><u>Layer Audio Onto Video Clips in Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-bsod-data-for-system-debugging/"><u>Leveraging BSOD Data for System Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-grans-old-computer-senior-friendly-and-simple/"><u>Make Your Gran’s Old Computer Senior-Friendly & Simple</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-youtube-channel-building-essentials-for-2024/"><u>Mastering YouTube  Channel-Building Essentials for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-characters-on-windows-11-screen/"><u>Navigating the Characters on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-isdonedll-isarcextract-failures/"><u>Overcoming Common ISDone.dll (ISArcExtract) Failures</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-your-guide-to-color-perfection-on-windows/"><u>Overcoming Obstacles: Your Guide to Color Perfection on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systemsettings-crashes-in-windows-11/"><u>Overcoming SystemSettings Crashes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-system-sounds-in-windows-11-by-activating-mixer-feature/"><u>Perfect System Sounds in Windows 11 by Activating Mixer Feature</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-window-11-dual-screen-usage/"><u>Perfecting Window 11 Dual Screen Usage</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-realme-12-pro-5g-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Realme 12 Pro 5G Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-default-heat-reduction-rules-in-winos/"><u>Reclaiming Default Heat Reduction Rules in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-copy-pasting-malfunctions-in-windows-11/"><u>Rectifying Copy-Pasting Malfunctions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-win-lol-initial-load-issue/"><u>Resolving Win: LOL Initial Load Issue</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unseen-second-monitor-problems/"><u>Solving Unseen Second Monitor Problems</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-notes-obsidian-canvas-approach/"><u>Streamline Your Notes: Obsidian Canvas Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/top-benefits-of-windows-11-overtaking-macos/"><u>Top Benefits of Windows 11 Overtaking macOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-to-resolve-battlenet-login-on-pcs/"><u>Troubleshooting Steps to Resolve Battle.net Login on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-access-navigating-localized-onedrive-files/"><u>Unplugged Access: Navigating Localized OneDrive Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>Unraveling Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-expect-from-microsofts-win11-feb-release/"><u>What to Expect From Microsoft's Win11 Feb Release</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
</ul></div>
