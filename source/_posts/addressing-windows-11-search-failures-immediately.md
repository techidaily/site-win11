---
title: Addressing Windows 11 Search Failures Immediately
date: 2024-07-13T10:12:52.853Z
updated: 2024-07-14T10:12:52.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows 11 Search Failures Immediately
excerpt: This Article Describes Addressing Windows 11 Search Failures Immediately
keywords: Win11 Search Fix,Windows Fixes,Quick Search Cure,Resolve WS11 Issues,Addressing Search Errors,Immediate Search Repair,Windows Search Troubleshoot
thumbnail: https://thmb.techidaily.com/7e2e77f0d86cd559dbfa986d906ed8c2ea52210199eb42f08b362eadc3328953.jpg
---

## Addressing Windows 11 Search Failures Immediately

 Most users probably utilize the Windows 11/10 search tool to find apps and files. However, some users have reported their search tools don’t display any results. Some users see a “No results found” message whenever they search. Or the search tool displays nothing except a blank white screen in other instances.

 Either way, users can’t find things with the Windows search tool when it doesn’t display results right. Is your search tool not showing results either? If that’s the case, you can fix your search tool not displaying results in Windows 11/10 with these potential resolutions.

## 1\. Update Windows

 Microsoft releases a multitude of patch updates to fix Windows bugs and issues. So, it’s recommended to manually check for and download any available Windows updates for the sake of fixing the search tool. That also includes build updates for new Windows versions. Here’s how you can manually download and install Windows 11/10 updates.

1. Press the**Windows** key, and select the pinned Settings app shortcut on the Start menu that opens.
2. Select**Windows Update** along the left of Settings. In Windows 10, click**Update & Security** on Settings’ home screen.
3. Then press**Check for updates** to initiate a search. Most available updates will download and install automatically.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-check-for-updates-button.jpg)
4. If selecting**Check for updates** doesn’t automatically install everything available, click the**Download and Install** buttons for any other updates (including version 22H2).

## 2\. Run the Search Troubleshooting Tool

 Windows has troubleshooters that can fix all kinds of errors and issues. The Search and Indexing troubleshooter is the one for resolving search-related issues that occur in Windows. You may be able to fix the search tool not displaying results with that troubleshooter as follows:

1. Use one of the many ways to open Settings on Windows, then open the Setting's**System** tab.
2. Click**Troubleshoot** inside the Settings app’s**System** tab.
3. Select**Other trouble-shooters** to reach the Windows troubleshooters.
4. Press**Run** for the Search and Indexing troubleshooter.  
![The Run button for the Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-run-button-for-the-search-and-indexing-troubleshooter.jpg)
5. Click the**Can't start a search or see results** checkbox, and select the troubleshooter’s**Next** option. The **Files, folders, apps, or settings don't appear in results** checkbox is also a suitable option to select for troubleshooting this issue.  
![The Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-search-and-indexing-troubleshooter.jpg)

 The steps for opening the Search and Indexing troubleshooter in Windows 10’s Settings app aren’t exactly the same. Click**Update & Security** \>**Troubleshoot** in Windows 10’s Settings app. Selecting**Additional troubleshooters** will bring up the list. Then you can click**Run the troubleshooter** for Search and Indexing to open it from there.

## 3\. Select the Enhanced Search Option

 The Settings app has some search options that can affect the effectiveness of the search tool. You can set the search utility to fully search a PC by selecting an**Enhanced** option. Try selecting that option in the following steps:

1. Click**Settings** on the Start or Power User (**Win** +**X**) menu.
2. Select the**Privacy & security** tab to view navigation options for Windows permissions.
3. Click the**Searching Windows** navigation option.  
![The Search Windows navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-searching-windows-navigation-option.jpg)
4. Then select the**Enhanced** radio button.  
![The Enhanced radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-enhanced-radio-button.jpg)
5. Click the menu buttons for all excluded search folders listed below that option and select**Remove** .  
![The Remove option for excluded folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-remove-option.jpg)

## 4\. Start the Windows Search Service

 The search tool won’t display results if the Windows Search service it’s based on isn’t running. So, check the Windows Search is enabled and running:

1. To access Run, press**Win** +**R** . You can also use any method in our guide on [how to open Run on Windows](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Then type**services.msc** inside the**Open** box, and select Run’s**OK** option.
3. Double-click**Windows Search** within the Services app.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-services-window2.jpg)
4. Click the drop-down menu for the**Startup type** option to select the service’s**Automatic** option.  
![The Windows Search Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-windows-search-properties-window.jpg)
5. Press**Start** in the properties window if the search service isn’t running.
6. To save the changed settings, click the**Apply** option.
7. Select**OK** to close Windows Search Properties.

 If the Windows Search service is already running, try restarting it. Select the**Stop** option for Windows Search. Wait a few minutes, and click the**Start** button for the service to restart it.

## 5\. Run a Scan With the SFC Tool

 Microsoft recommends users run the System File Checker (SFC) tool when Windows functions aren’t working right. In this case, the search function isn’t displaying results, which could be because of corrupted Windows files on your PC. This is how you can start an SFC scan:

1. Launch the Run dialogue box as above, and enter**cmd** inside its**Open** box.
2. Press the**Ctrl** +**Shift** +**Enter** key combination to open Command Prompt with admin permissions.
3. First, run an image scan by entering this command text and pressing**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
4. Then start the SFC scan by executing the following command:  
`sfc /scannow`  
![The SFC scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-sfc-scan-command.jpg)
5. Wait for the SFC tool to show a Windows Resource Protection scan outcome.

## 6\. Rebuild the Search Tool’s Index

 A corrupted or outdated search index database is another potential cause for the search tool not displaying results. In this case, you may need to select to rebuild the search index. Doing so will wipe the current index’s content and restart the indexing. These are the steps for rebuilding the search index in Windows:

1. To open Control Panel, bring up Run first. Type**Control Panel** into Run and click**OK** . See [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/) for more methods.
2. Select**Large icons** on Control Panel’s**View by** menu.  
![The Large icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-large-icons-button.jpg)
3. Click**Indexing Options** to view that applet.
4. Select**Advanced** in the Indexing Options window.
5. Click**Rebuild** in the Index**Settings** tab.  
![The Rebuild button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-rebuild-option.jpg)
6. Wait for the rebuilding to finish.
7. Select**OK** \>**Close** to exit the indexing applet.

## 7\. Reinstall Cortana

 Cortana is an app that’s closely connected with the Windows search tool. Some users have been able to fix the search tool not displaying results by reinstalling that app. You can reinstall Cortana in PowerShell like this:

1. Press Task Manager’s**Ctrl** +**Shift** +**Esc** keyboard shortcut.
2. Click**File** and the**Run new task** option.
3. Type**PowerShell** inside the Create new task window’s**Open** box.
4. Select the checkbox for the**Create new task with administrative privileges** option.
5. Then select**OK** to access PowerShell.
6. Input the following command for reinstalling Cortana:  
`Get-AppXPackage -Name Microsoft.Windows.Cortana | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The command for reinstalling Cortana](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reinstall-cortana-command.jpg)
7. Press**Enter** to execute the PowerShell command.

## 8\. Reset Windows

 If nothing else fixes the search tool not showing results, this is the last-resort resolution to try. Resetting Windows reinstalls the platform by restoring it to a default configuration, which will most likely be enough to resolve this search issue. However, you’ll need to reinstall any software you previously installed after a reset.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-tool.jpg)

 You can perform a reset with the Reset this PC recovery tool. That utility includes an option for preserving user files. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this resolution with that tool.

## Find Apps and Files Again With the Windows Search Tool

 So, that’s how you can get your Windows search tool fixed when it’s not showing results. We recommend applying the suggested resolutions in the order specified above. There’s a reasonable chance one will sort your search utility out so that you can find the apps and files you’re looking for with it again.

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
<li><a href="https://win11.techidaily.com/decoding-the-windows-configuration-pathways/"><u>Decoding the Windows Configuration Pathways</u></a></li>
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-oneplus-ace-3-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of OnePlus Ace 3? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-0x800713f-error-on-the-windows-mail-service/"><u>How to Repair 0X800713f Error on the Windows Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-adjustment-overcoming-overscan/"><u>Mastering Windows Display Adjustment: Overcoming Overscan</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-oppo-a2-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Oppo A2 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-folder-navigation-in-win-11-movecopy-command-addition/"><u>Optimizing Folder Navigation in Win 11 - Move/Copy Command Addition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-to-dominate-kinemaster-and-identify-top-online-video-services/"><u>[Updated] Expert Tips to Dominate KineMaster & Identify Top Online Video Services</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-top-tricks-for-learning-photo-slideshow/"><u>New 2024 Approved Top Tricks for Learning Photo Slideshow</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-setting-up-your-youtube-studio-essential-equipment-list/"><u>[New] Setting Up Your YouTube Studio  Essential Equipment List</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-sluggish-outlook-on-your-computer/"><u>Sidestep Sluggish Outlook on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-by-wmi-service/"><u>Addressing High Cpu Usage by WMI Service</u></a></li>
<li><a href="https://win11.techidaily.com/winerror-solved-addressing-ms-store-0x80072f17/"><u>WinError Solved: Addressing MS Store 0X80072f17</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-uncover-hidden-system-startups/"><u>Tips to Uncover Hidden System Startups</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-overlays-for-windows-11/"><u>Adjusting Photo Overlays for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-saving-hurdles-with-steps-to-fix-pubg/"><u>Overcoming Saving Hurdles with Steps to Fix PUBG</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-trouble-with-updates-code-0x80246007/"><u>Tackling the Trouble with Update's Code 0X80246007</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-common-anydesk-errors-on-windows/"><u>Mastering the Art of Resolving Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-oculus-quest-2-for-windows-vr-use/"><u>Modifying Oculus Quest 2 for Windows VR Use</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-2023s-guide-to-android-nine-essential-digital-audio-workstations-for-creative-beats/"><u>In 2024, 2023S Guide to Android Nine Essential Digital Audio Workstations for Creative Beats</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-streamlined-processes-from-camera-roll-to-snapchat-posting/"><u>In 2024, Streamlined Processes  From Camera Roll to Snapchat Posting</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-audio-chop-and-split-in-a-flash-speeding-up-mp3-separation-processes/"><u>Updated Audio Chop & Split in a Flash Speeding up MP3 Separation Processes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-poco-f5-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Poco F5 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-transforming-instagram-vids-into-a-backup-solution-via-computers-and-macs/"><u>In 2024, Transforming Instagram Vids Into a Backup Solution via Computers & Macs</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-banish-coffee-stains-free-iphone-app-to-remove-red-eyes/"><u>[New] Banish Coffee Stains  Free iPhone App to Remove Red Eyes</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-x887a0006-dxgi-error-in-windows-11/"><u>Quick Fixes for X887A0006: DXGI Error in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-conquer-the-blackened-canvas-of-youtube/"><u>2024 Approved  Conquer the Blackened Canvas of YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-onedrive-files-offline-on-a-windows-pc/"><u>How to Access OneDrive Files Offline on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-absence-of-monitor-on-startup/"><u>Remedy for Absence of Monitor on Startup</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-blend-music-sequences-into-animated-file-format-on-win-os/"><u>New In 2024, Blend Music Sequences Into Animated File Format on WIN OS</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/fix-apple-iphone-15-plus-stuck-on-data-transfer-verified-solution-drfone-by-drfone-transfer-from-ios/"><u>Fix Apple iPhone 15 Plus Stuck on Data Transfer Verified Solution! | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unwanted-windows-start-up-in-bios-landing/"><u>Overcoming Unwanted Windows Start-Up in BIOS Landing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-deciphering-screens-a-comprehensive-review-of-recording-apps/"><u>[Updated] 2024 Approved  Deciphering Screens  A Comprehensive Review of Recording Apps</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-demystifying-ai-game-generators-from-definition-to-distinction-for-2024/"><u>New Demystifying AI Game Generators From Definition to Distinction for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-finding-the-ideal-game-voice-modifier-a-comprehensive-guide-for-2024/"><u>Updated Finding the Ideal Game Voice Modifier A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-greater-vram/"><u>Enhancing Your Visual Experience with Greater VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-your-outlook-calendar-on-windows/"><u>How to Customize Your Outlook Calendar on Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-top-30-original-pfp-suggestions-for-tiktok-success/"><u>[New] In 2024, Top 30 Original PFP Suggestions for TikTok Success</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-critical-assessment-the-core-elements-of-sound-forge/"><u>New 2024 Approved Critical Assessment The Core Elements of Sound Forge</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-tech-appbrowser-rule/"><u>Understanding Windows Tech: App/Browser Rule</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-error-0xfffffff-with-ease/"><u>Solving Windows' Error 0xFFFFFFF with Ease</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-oppo-a1x-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Oppo A1x 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unilateral-earbud-error-how-to-rectify/"><u>In 2024, Unilateral Earbud Error  How to Rectify</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-reclaim-lively-sounds-in-muted-video-tweets/"><u>[New] Reclaim Lively Sounds in Muted Video Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-understanding-and-turning-off-system-lockdown/"><u>Windows 11: Understanding & Turning Off System Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-hiding-or-revealing-windows-protection-sectors/"><u>Stealth Mode: Hiding or Revealing Windows Protection Sectors</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-is-now-microsofts-new-ai-enhanced-taskbar-for-windows-11-users/"><u>The Future Is Now: Microsoft’s New AI-Enhanced Taskbar for Windows 11 Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-zoom-webinar-basics-for-beginners-and-those-new-to-virtual-events/"><u>In 2024, Zoom Webinar Basics for Beginners & Those New to Virtual Events</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-asus-rog-phone-8-is-unlocked-by-drfone-android/"><u>How To Check if Your Asus ROG Phone 8 Is Unlocked</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-honor-90-lite-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Honor 90 Lite</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-cutting-edge-templates-unlocking-your-videos-potential/"><u>[New] 2024 Approved  Cutting-Edge Templates Unlocking Your Video's Potential</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-how-to-live-stream-to-facebook-from-dji-drone/"><u>[New] 2024 Approved  How to Live Stream to Facebook From DJI Drone?</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-guide-to-full-battery-indicators-in-win-oses/"><u>Advanced Guide to Full Battery Indicators in Win OSes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-essential-tiktok-emoji-encyclopedia/"><u>[Updated] Essential TikTok Emoji Encyclopedia</u></a></li>
<li><a href="https://win11.techidaily.com/debating-choco-and-wslm-top-pick-for-windows-software/"><u>Debating Choco and WSLM: Top Pick for Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-digital-life-with-exclusive-ms-choice/"><u>Elevate Your Digital Life with Exclusive MS Choice</u></a></li>
<li><a href="https://win11.techidaily.com/restarting-routine-efficiently-installing-windows-11/"><u>Restarting Routine: Efficiently Installing Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-rankings-top-budget-friendly-photo-editors-online/"><u>2024 Approved  The Ultimate Rankings  Top Budget-Friendly Photo Editors Online</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-unique-characteristics-of-ai-computers/"><u>Delving Into Unique Characteristics of AI Computers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-forget-youtube-here-are-the-best-10-mobile-video-sites/"><u>In 2024, Forget YouTube? Here Are the Best 10 Mobile Video Sites</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-0x0000004e-on-windows-11-systems/"><u>Conquering Error 0X0000004E on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unable-to-open-error-in-geforce-experience-windows/"><u>Resolving Unable to Open Error in GeForce Experience Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-screenshot-synopsis-study/"><u>In 2024, ScreenShot Synopsis Study</u></a></li>
</ul></div>
