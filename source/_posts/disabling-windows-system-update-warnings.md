---
title: Disabling Windows System Update Warnings
date: 2024-07-13T10:58:01.006Z
updated: 2024-07-14T10:58:01.006Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows System Update Warnings
excerpt: This Article Describes Disabling Windows System Update Warnings
keywords: Disable Update Alerts,Stop Win Updates Notify,Silence OS Update Warnings,Halt Windows System Alerts,Prevent Windows Update Alarms,Mute Windows Update Issues,Cease Updates Notifications
thumbnail: https://thmb.techidaily.com/6e0cdf2b7038ec925488e32c1b0811331fe39479e79326e6be564a7361db8bbb.jpg
---

## Disabling Windows System Update Warnings

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-app-guard-features-with-graphical-upgrades-on-edge/"><u>Augmenting App Guard Features with Graphical Upgrades on Edge</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-run-a-giveaway-facebook-post/"><u>[New] How to Run a Giveaway Facebook Post</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-cadence-crossover-transferring-playlists-with-ease/"><u>[New] Cadence Crossover  Transferring Playlists with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/alter-display-angle-in-windows-settings/"><u>Alter Display Angle in Windows Settings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-audio-engineers-guide-switching-from-srt-to-ttml/"><u>2024 Approved  The Audio Engineer’s Guide  Switching From SRT to TTML</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-navigation-methods-without-ls-command/"><u>Advanced Windows Navigation Methods Without LS Command</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagrams-power-in-motion-crafting-a-comprehensive-video-plan/"><u>[New] In 2024, Instagram's Power in Motion  Crafting a Comprehensive Video Plan</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/1714138140154-updated-no-budget-no-problem-top-free-4k-video-editors/"><u>Updated No Budget? No Problem! Top Free 4K Video Editors</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-turntable-tunes-archive-stream-your-dj-favorites/"><u>New In 2024, Turntable Tunes Archive Stream Your DJ Favorites</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-software-removal-crafting-wins-context-menu-aids/"><u>Accelerating Software Removal: Crafting Win's Context Menu Aids</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-earning-power-leveraging-social-media-snaps/"><u>[Updated] Earning Power  Leveraging Social Media Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-task-mastery-initiating-task-manager-in-win11/"><u>Administrative Task Mastery: Initiating Task Manager in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-boosting-instagram-videos-online-strategies-for-faster-views/"><u>[New] 2024 Approved  Boosting Instagram Videos  Online Strategies for Faster Views</u></a></li>
<li><a href="https://win11.techidaily.com/art-software-showdown-windows-programs-vs-procreate/"><u>Art Software Showdown: Windows Programs Vs. Procreate</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-tecno-spark-20-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-0x0-failure-in-win11-setup-procedures/"><u>Avoid 0X0 Failure in Win11 Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-spatial-audio-setup-guide/"><u>Activating Windows 11: Spatial Audio Setup Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-key-to-viral-posts-on-instagram-unveiled/"><u>The Key to Viral Posts on Instagram Unveiled</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/top-video-speed-controllers-for-pc-and-mac-free-and-paid-options-for-2024/"><u>Top Video Speed Controllers for PC and Mac Free & Paid Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/android-extension-in-w11-workspace-enhancing-productivity/"><u>Android Extension in W11 Workspace: Enhancing Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/ascending-to-top-level-windows-management/"><u>Ascending to Top-Level Windows Management</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-optimal-efficiency-nircmd-tips-for-mastering-windows-11/"><u>Achieve Optimal Efficiency: NirCmd Tips for Mastering Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sync-failures-with-microsoft-to-do/"><u>Addressing Sync Failures with Microsoft To Do</u></a></li>
<li><a href="https://win11.techidaily.com/autonomous-windows-update-an-offline-methodology/"><u>Autonomous Windows Update: An Offline Methodology</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-comprehensive-tutorial-on-detaching-audible-elements-from-video-clips/"><u>The Comprehensive Tutorial on Detaching Audible Elements From Video Clips</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-key-components-to-a-smooth-watching-experience-facebook-livestream/"><u>[Updated] 2024 Approved  Key Components to a Smooth Watching Experience  Facebook Livestream</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-directories-to-your-windows-11-quick-access-menu/"><u>Adding Directories to Your Windows 11 Quick Access Menu</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-strategies-keeping-epic-launcher-non-freezing/"><u>Avoidance Strategies: Keeping Epic Launcher Non-Freezing</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-perfect-xbox-audio-with-windows-1011/"><u>Achieving Perfect Xbox Audio with Windows 10/11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-guide-to-converting-webm-to-mp4-10-best-options-for-2024/"><u>New The Ultimate Guide to Converting WebM to MP4 10 Best Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-creating-windows-shortcuts-for-uwp/"><u>Accelerating Workflow: Creating Windows Shortcuts for UWP</u></a></li>
<li><a href="https://ai-topics.techidaily.com/what-is-ai-marketing/"><u>What Is AI Marketing?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-seamless-media-exchange-posting-twitter-videos-on-instagram/"><u>In 2024, Seamless Media Exchange  Posting Twitter Videos on Instagram</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/how-to-set-up-and-use-xbox-screen-recording-tools/"><u>How to Set Up and Use Xbox Screen Recording Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-seamless-media-consumption-enable-automatic-playback-of-youtube-content-on-fb/"><u>[New] 2024 Approved  Seamless Media Consumption  Enable Automatic Playback of YouTube Content on FB</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/premium-techniques-for-secure-recording-of-computerized-tv-shows/"><u>Premium Techniques for Secure Recording of Computerized TV Shows</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-mobile-devices-for-windows-mic-input/"><u>Amplify Mobile Devices for Windows Mic Input</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-empty-folder-warning-windows/"><u>Addressing Empty Folder Warning Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>How to identify missing drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://win11.techidaily.com/address-windows-missing-camera-mystery-in-device-manager/"><u>Address Windows' Missing Camera Mystery in Device Manager</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-your-essential-guide-to-new-tiktok-acts-now/"><u>In 2024, Your Essential Guide to New TikTok Acts Now</u></a></li>
<li><a href="https://win11.techidaily.com/altering-monitors-order-in-windows/"><u>Altering Monitors' Order in Windows</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-unlock-the-potential-of-fb-chronicles-with-free-apps/"><u>[New] 2024 Approved  Unlock the Potential of FB Chronicles with Free Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-operating-software-via-network-drivers/"><u>Upgrade Operating Software via Network Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-email-checking-add-gmail-to-your-windows-side/"><u>Accelerated Email Checking: Add Gmail to Your Window's Side</u></a></li>
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/automation-bane-keep-your-windows-backdrop-steady/"><u>Automation Bane: Keep Your Windows Backdrop Steady</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-flawlesshd-webrecorder-software-for-2024/"><u>[Updated] FlawlessHD WebRecorder Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/assess-if-your-system-qualifies-for-new-windows-11/"><u>Assess if Your System Qualifies for New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-full-control-with-admin-cmd-role/"><u>Achieve Full Control with Admin CMD Role</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clock-display-window-10-and-11-guide/"><u>Adjusting Clock Display: Window 10 & 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-synchronized-data-across-your-multiple-windows-desktops-with-aoemi/"><u>Achieve Synchronized Data Across Your Multiple Windows Desktops With AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-zeroxc000003e-problem-in-pc-application-startup/"><u>Addressing ZeroXc000003e Problem in PC Application Startup</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-account-lockout-counter-following-unsuccessful-logins-in-w10w11/"><u>Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11</u></a></li>
</ul></div>
