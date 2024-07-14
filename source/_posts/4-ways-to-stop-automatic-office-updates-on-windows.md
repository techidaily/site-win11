---
title: 4 Ways to Stop Automatic Office Updates on Windows
date: 2024-07-13T11:10:12.919Z
updated: 2024-07-14T11:10:12.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Stop Automatic Office Updates on Windows
excerpt: This Article Describes 4 Ways to Stop Automatic Office Updates on Windows
keywords: Stopping Auto-Updates,Office Update Halt,Disable Windows Updates,Windows Update Control,End PC Auto-Updates,Manage System Updates,Stop Windows Patches
thumbnail: https://thmb.techidaily.com/235c9a836def3af64d14d9406f5da36fac525d1a6b5286ab03fa2d909747fb1b.jpg
---

## 4 Ways to Stop Automatic Office Updates on Windows

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to [download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


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
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-from-photo-to-cartoon-the-ultimate-app-roundup/"><u>Updated In 2024, From Photo to Cartoon The Ultimate App Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/typography-transition-on-windows-multilingual-scripts/"><u>Typography Transition on Windows: Multilingual Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuity-with-powertoys-settings-transfer/"><u>Ensuring Continuity with PowerToys Settings Transfer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-navigate-motion-sickness-in-virtual-reality-with-ease/"><u>[Updated] In 2024, Navigate Motion Sickness in Virtual Reality with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-error-0x80070194-with-onedrive/"><u>Addressing the Error 0X80070194 with OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-space-hogs-on-your-windows-hard-drive/"><u>Unveiling Space Hogs on Your Windows Hard Drive</u></a></li>
<li><a href="https://win11.techidaily.com/ten-strategies-to-keep-windows-safe-without-bitlocker-support/"><u>Ten Strategies to Keep Windows Safe without Bitlocker Support</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-guide-to-making-engaging-youtube-video-thumbnails-with-phones/"><u>2024 Approved  The Ultimate Guide to Making Engaging YouTube Video Thumbnails with Phones</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/affordable-tutorial-on-professional-looking-youtube-introsends/"><u>Affordable Tutorial on Professional Looking YouTube Intros/Ends</u></a></li>
<li><a href="https://review-topics.techidaily.com/reinstall-your-drivers-with-device-manager-on-windows-1110-by-drivereasy-guide/"><u>Reinstall your drivers with Device Manager on Windows 11/10</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-high-res-sky-scenes-with-mi-drone-for-2024/"><u>Unveiling the High-Res Sky Scenes with Mi Drone for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-uncharted-territory-6-secrets-to-documenting-your-minecraft-journey/"><u>[Updated] In 2024, Uncharted Territory  6 Secrets to Documenting Your Minecraft Journey</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-potential-of-batch-files-via-exes/"><u>Unlock the Potential of Batch Files via EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-integrating-audible-elements-into-your-slides-a-comprehensive-guide-for-recording-sound-in-powerpoint-on-pcmac-systems/"><u>New In 2024, Integrating Audible Elements Into Your Slides A Comprehensive Guide for Recording Sound in PowerPoint on PC/Mac Systems</u></a></li>
<li><a href="https://win11.techidaily.com/winsecurely-solutions-for-windows-without-bitlocker/"><u>WinSecurely: Solutions for Windows Without Bitlocker</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-save-configuration-errors-in-pubg/"><u>Correcting Save Configuration Errors in PUBG</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-xperia-1-v-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Xperia 1 V.</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-geforce-error-x0001-on-windows-pcs/"><u>Fixing Common GeForce Error X0001 on Windows PCs</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-navigating-firefoxs-picture-in-picture-capabilities/"><u>[New] Navigating Firefox's Picture-in-Picture Capabilities</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-best-8-video-chat-apps-on-android-for-more-than-four/"><u>[New] 2024 Approved  Best 8 Video Chat Apps on Android for More Than Four</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-mozilla-revolutionized-screen-splitting-with-ffxp/"><u>2024 Approved  How Mozilla Revolutionized Screen Splitting with FFXP</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-valorant-gameplay-try-the-premium-no-cost-voice-modifier-now/"><u>Elevate Valorant Gameplay - Try the Premium, No-Cost Voice Modifier Now</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/decode-and-resolve-your-guide-to-instagram-video-problems-for-2024/"><u>Decode and Resolve  Your Guide to Instagram Video Problems for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wsl-2-streamline-docker-usage/"><u>Boosting WSL 2: Streamline Docker Usage</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tuning-into-emotion-background-melodies-in-film/"><u>In 2024, Tuning Into Emotion  Background Melodies in Film</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-asus-leads-the-charge-with-their-mg28uq-the-future-of-4k-monitors/"><u>In 2024, ASUS Leads the Charge with Their MG28UQ - The Future of 4K Monitors</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-did-your-iphone-14-pro-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>In 2024, Did Your iPhone 14 Pro Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-football-fortunes-for-free-with-old-championship-manager/"><u>Discover Football Fortunes for Free with Old Championship Manager</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-how-to-acquire-rare-bird-sound-samples-in-digital-audio-format/"><u>New How to Acquire Rare Bird Sound Samples in Digital Audio Format</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-crafting-stunning-slideshows-on-iphone-series-13/"><u>2024 Approved  Crafting Stunning Slideshows on iPhone Series 13</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-exploring-ghoulish-auditory-extras/"><u>New In 2024, Exploring Ghoulish Auditory Extras</u></a></li>
<li><a href="https://win11.techidaily.com/essential-sync-software-windows-and-android-unite/"><u>Essential Sync Software: Windows & Android Unite</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-epicentertainment-eyeview/"><u>[New] EpicEntertainment EyeView</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-3-step-structure-for-successful-subscriber-profit-analysis-a-guide-from-google/"><u>In 2024, The 3-Step Structure for Successful Subscriber Profit Analysis  A Guide From Google</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-viral-video-catalogue-highest-viewers/"><u>[Updated] Twitter’s Viral Video Catalogue  Highest Viewers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-virtualdub-limitations-why-you-need-to-consider-these-alternatives-for-2024/"><u>New Virtualdub Limitations Why You Need to Consider These Alternatives for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-boost-length-on-youtube-entry-filming/"><u>2024 Approved  Boost Length on YouTube Entry Filming</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-iis-8-key-steps/"><u>Unlocking IIS: 8 Key Steps</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-whisperer-guide-to-win11-menu-hiding/"><u>The Silent Whisperer Guide to Win11 Menu Hiding</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-restore-missing-app-icons/"><u>Methods to Restore Missing App Icons</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-unleashing-the-power-of-speech-in-your-tiktok-projects/"><u>2024 Approved  Unleashing the Power of Speech in Your TikTok Projects</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-techniques-for-overcoming-media-app-issues-in-win11/"><u>Methodical Techniques for Overcoming Media App Issues in Win11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-something-you-need-to-know-about-twistedwave-audio-editor/"><u>New 2024 Approved Something You Need to Know About TwistedWave Audio Editor</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-procedures-instilling-stopwatch-capabilities-in-broadcast-encoders-for-2024/"><u>Essential Procedures  Instilling Stopwatch Capabilities in Broadcast Encoders for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-htc-u23-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your HTC U23</u></a></li>
</ul></div>
