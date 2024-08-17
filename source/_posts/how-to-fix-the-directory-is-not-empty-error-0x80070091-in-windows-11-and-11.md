---
title: How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11
date: 2024-08-15T23:52:25.203Z
updated: 2024-08-16T23:52:25.203Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11
excerpt: This Article Describes How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11
keywords: Fixing Windows Error 0X80070091,Empty Directory Fix,Windows 11 Error Code 0X80070091,Resolve Directories Not Empty,0X80070091 in Windows Fix,Windows 11 Empty Folder Issue,Correction Directory Full Error
thumbnail: https://thmb.techidaily.com/80e9505289538424f43d5ba12eaf938497fe9485f8cac83a0e7062f472435b7f.jpg
---

## How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
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

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-becoming-a-lyric-video-pro-a-lyric-video-makers-journey/"><u>[New] 2024 Approved  Becoming a Lyric Video Pro  A Lyric Video Maker's Journey</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-correcting-obs-darkness-during-live-streams/"><u>[New] 2024 Approved  Correcting OBS Darkness During Live Streams</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-earnings-breakdown-one-million-glances-at-youtube/"><u>[New] 2024 Approved  Earnings Breakdown  One Million Glances at Youtube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-how-to-download-part-of-youtube-video/"><u>[New] 2024 Approved  How to Download Part of YouTube Video?</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-mastering-tweeted-videos-on-facebooks-networks/"><u>[New] 2024 Approved  Mastering Tweeted Videos on Facebooks Networks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-flip-the-script-unique-approaches-to-retracing-yt-content-for-2024/"><u>[New] Flip the Script  Unique Approaches to Retracing YT Content for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-how-to-enhance-clarity-of-online-video-content/"><u>[New] How to Enhance Clarity of Online Video Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-unified-iptv-streaming-framework/"><u>[New] In 2024, Unified IPTV Streaming Framework</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-metaverse-comedy-crafting-top-tips-for-diy-memetic-mastery/"><u>[Updated] 2024 Approved  Metaverse Comedy Crafting  Top Tips for DIY Memetic Mastery</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-no-cash-all-fun-turning-twitter-vids-into-gifs/"><u>[Updated] In 2024, No Cash, All Fun  Turning Twitter Vids Into GIFs</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-core-elements-of-virtual-tale-transmission/"><u>2024 Approved  Core Elements of Virtual Tale Transmission</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-from-two-dimensions-to-three-making-text-pop-in-photoshop/"><u>2024 Approved  From Two-Dimensions to Three  Making Text Pop in Photoshop</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-beat-drops-highlighting-this-years-best-music-vids/"><u>2024 Approved  The Beat Drops  Highlighting This Year's Best Music Vids</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-the-power-of-android-time-lapses/"><u>2024 Approved  Unlocking the Power of Android Time-Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-breakdown-rehabilitating-win11s-ccleaner/"><u>Breaking the Breakdown: Rehabilitating Win11's CCleaner</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-torrent-lag-on-your-pc-with-qbittorrent/"><u>Breaking Through Torrent Lag on Your PC with qBittorrent</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-vintage-films-with-madvr-for-windows/"><u>Breathe New Life Into Vintage Films with MadVR for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-new-life-into-your-steam-games-milestones/"><u>Breathing New Life Into Your Steam Games' Milestones</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-windows-11s-bluetooth-9-effective-fixes-at-hand/"><u>Bring Back Windows 11'S Bluetooth: 9 Effective Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/browsing-made-lighter-top-7-windows-apps-for-less-memory-use/"><u>Browsing Made Lighter: Top 7 Windows Apps for Less Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/budget-blues-identifying-the-risks-of-low-cost-windows-licensing/"><u>Budget Blues: Identifying the Risks of Low-Cost Windows Licensing</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-chromes-glitch-enabling-flawless-filesync-on-windows/"><u>Bypass Chrome’s Glitch: Enabling Flawless Filesync on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-non-responsive-power-switches-on-windows-11/"><u>Bypass Non-Responsive Power Switches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blurriness-9-ways-to-fine-tune-your-windows-display/"><u>Bypassing Blurriness: 9 Ways to Fine-Tune Your Windows Display</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-chrome-blackout-a-step-by-step-guide/"><u>Bypassing Chrome Blackout: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unknown-not-initialized-in-windows-operating-systems/"><u>Bypassing Unknown Not Initialized in Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-your-cortana-story-in-windows-files/"><u>Capturing Your Cortana Story in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-edge-symbols-regular-occurrence/"><u>Ceasing Edge Symbols' Regular Occurrence</u></a></li>
<li><a href="https://win11.techidaily.com/change-your-visual-preference-in-winterm/"><u>Change Your Visual Preference in WinTerm</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-new-journey-away-from-lost-at-sea-xbox-errors/"><u>Charting a New Journey Away From Lost at Sea Xbox Errors</u></a></li>
<li><a href="https://win11.techidaily.com/chilly-warm-up-your-windows-11-with-holiday-hacks/"><u>Chilly Warm-Up Your Windows 11 with Holiday Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-your-preferred-package-manager-for-windows-devices/"><u>Choosing Your Preferred Package Manager for Window's Devices</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-and-resolving-the-mystery-of-error-0x8007251d-in-windows/"><u>Clarifying and Resolving the Mystery of Error 0X8007251d in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-ui-redesign-for-file-explorer-in-w11/"><u>Classic UI Redesign for File Explorer in W11</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-on-windows-11-a-synopsis-of-app-removal-techniques-107-chars/"><u>Clean Slate on Windows 11: A Synopsis of App Removal Techniques (107 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-reset-user-permissions-to-basics-in-windows-11/"><u>Clean Slate: Reset User Permissions to Basics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-concise-views-mastering-compact-explorer-layout/"><u>Clear and Concise Views: Mastering Compact Explorer Layout</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstacles-to-the-microsoft-store-on-windows-11/"><u>Clearing Obstacles to the Microsoft Store on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-temporary-files-and-cache-from-spotify-app/"><u>Clearing Temporary Files and Cache From Spotify App</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-obstacles-winning-against-xps-print-error-xfddddf/"><u>Clearing the Obstacles: Winning Against XP's Print Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-local-device-misnaming-on-windows-systems/"><u>Clearing Up Local Device Misnaming on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-windows-bluetooth-connectivity-issues/"><u>Clearing Up Windows Bluetooth Connectivity Issues</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-vanishing-disk-space-paradox-on-windows/"><u>Combat the Vanishing Disk Space Paradox on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-scrutiny-gear-360s-virtual-reality-capability-for-2024/"><u>Comprehensive Scrutiny  Gear 360'S Virtual Reality Capability for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/elevate-your-snap-game-with-pro-level-boomerang-expertise-for-2024/"><u>Elevate Your Snap Game with Pro-Level Boomerang Expertise for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/how-can-i-post-a-video-between-twitter-and-tumblr-for-2024/"><u>How Can I Post a Video Between Twitter and Tumblr for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-itel-p40-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Itel P40</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-iphone-15-pro-max-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>In 2024, How to Make the Most of Your iPhone 15 Pro Max Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-13-ultra-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi 13 Ultra Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-loom-lens-view-unveiling-screen-record-magic/"><u>In 2024, Loom Lens View  Unveiling Screen Record Magic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-methods-for-computer-based-vhs-artistic-touches/"><u>In 2024, Perfect Methods for Computer-Based VHS Artistic Touches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/nourishing-recipes-and-plans-the-chatgpt-approach-to-dietary-wellness/"><u>Nourishing Recipes and Plans: The ChatGPT Approach to Dietary Wellness</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-oppo-k11x-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Oppo K11x Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-erratic-windows-7-dell-input-device/"><u>Resolve Erratic Windows 7 Dell Input Device</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719577021074-top-ranked-non-native-language-classes-us/"><u>Top Ranked Non-Native Language Classes U.S.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/years-premier-picks-top-15-youtube-channels-revolutionizing-product-reviews-2024/"><u>Year's Premier Picks  Top 15 YouTube Channels Revolutionizing Product Reviews, 2024</u></a></li>
</ul></div>
