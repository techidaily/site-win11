---
title: Solutions for Non-Disappearing Edge Shortcuts
date: 2024-07-13T10:10:25.039Z
updated: 2024-07-14T10:10:25.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Non-Disappearing Edge Shortcuts
excerpt: This Article Describes Solutions for Non-Disappearing Edge Shortcuts
keywords: Edge Shortcut Fixes,No Disappear Edges,Stable Edge Access,Shutdown Edge Issues,Unhide Shortcuts Tips,Persistent Edge Shortcuts,Solutions for Edge Loss
thumbnail: https://thmb.techidaily.com/270945824bfc208da598210ea9d10172c37fe105e9954ed76f47e6f487357fc6.jpg
---

## Solutions for Non-Disappearing Edge Shortcuts

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/addressing-discreprancies-in-power-usage-display-for-win-11-systems/"><u>Addressing Discreprancies in Power Usage Display for Win 11 Systems</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-s23-ultra-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adopt-wsl-the-easy-way-to-run-linux-commands/"><u>Adopt WSL: The Easy Way to Run Linux Commands</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/is-there-a-perfect-fps-for-everyone-comparing-30-and-60/"><u>Is There a 'Perfect' FPS for Everyone? Comparing 30 and 60</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-samsung-galaxy-m34-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Samsung Galaxy M34?</u></a></li>
<li><a href="https://win11.techidaily.com/android-ios-direct-pc-file-access/"><u>Android-iOS: Direct PC File Access</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-what-should-be-considered-to-choose-a-nice-gopro-for-vlogging/"><u>New What Should Be Considered to Choose A Nice GoPro for Vlogging?</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-internal-portaudio-errors-in-audacity-windows-11/"><u>Addressing Internal PortAudio Errors in Audacity (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/audioscape-refresh-on-windows-the-driver-upgrade-path/"><u>Audioscape Refresh on Windows: The Driver Upgrade Path</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-vivo-y02t-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Vivo Y02T Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-cost-monitor-functionality-of-your-wifi-network/"><u>Adjusting the Cost Monitor Functionality of Your Wifi Network</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-your-download-experience-with-epic-launcher/"><u>Accelerating Your Download Experience with Epic Launcher</u></a></li>
<li><a href="https://youtube-data.techidaily.com/outubers-toolkit-essential-setup-guidelines/"><u>[New] Youtubers' Toolkit  Essential Setup Guidelines</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-loading-lag-quick-fix-for-lol-on-win/"><u>Avoid Loading Lag: Quick Fix for LOL on Win</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-in-recent-windows-discord-upgrades/"><u>Addressing Failure in Recent Windows Discord Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ctrl-lock-up-in-windows-11-environments/"><u>Addressing Ctrl Lock-Up in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/augment-win11-notebook-with-smart-companion/"><u>Augment Win11 Notebook with Smart Companion</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-solutions-starting-your-software-on-windows-effortlessly/"><u>Alternative Solutions: Starting Your Software on Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-management-application-hiccups/"><u>Avoid Windows Management Application Hiccups</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-uncharted-territory-of-jazz-music-fundamentals-for-2024/"><u>The Uncharted Territory of Jazz Music Fundamentals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-mixer-for-clear-windows-sounds/"><u>Activating the Action Center Mixer for Clear Windows Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/android-as-a-w11-secondary-display-step-by-step-guide/"><u>Android as a W11 Secondary Display: Step by Step Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-the-art-of-buying-cutting-edge-360cams/"><u>Mastering the Art of Buying Cutting-Edge 360Cams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/transform-your-stories-6-premier-apps-for-snapchat-filters/"><u>Transform Your Stories  6 Premier Apps for Snapchat Filters</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-premier-voice-command-conversion-apps-for-windows-users/"><u>New 2024 Approved Premier Voice Command Conversion Apps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011s-error-0x8007045d/"><u>Addressing Win 10/11'S Error 0X8007045D</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-ps2-replay-on-android-devices-top-picks-for-2024/"><u>[Updated] Mastering PS2 Replay on Android Devices - Top Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/aspire-to-win-11s-trials-joining-the-insider-brigade/"><u>Aspire to Win 11'S Trials: Joining the Insider Brigade</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-getting-involved-in-the-global-village-facebook/"><u>[Updated] In 2024, Getting Involved in the Global Village (Facebook)</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-partition-management-tactics/"><u>Advanced Windows Partition Management Tactics</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-top-applications-that-can-help-apply-the-best-vhs-camera-effect/"><u>In 2024, Top Applications That Can Help Apply The Best VHS Camera Effect</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/cultivate-calmness-and-flexibility-with-top-10-yoga-streams-for-2024/"><u>Cultivate Calmness & Flexibility with Top 10 Yoga Streams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-how-windows-11-manages-your-files-a-look-at-its-recovery-system/"><u>Analyzing How Windows 11 Manages Your Files: A Look at Its Recovery System</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-live-streaming-made-simple-mastering-ps4-captures-using-obs/"><u>[New] In 2024, Live Streaming Made Simple  Mastering PS4 Captures Using OBS</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-mastering-mac-lecture-recording-techniques/"><u>[New] 2024 Approved  Mastering Mac  Lecture Recording Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-memory-shortage-in-the-magical-school-of-hogwarts-game/"><u>Addressing Memory Shortage in The Magical School of Hogwarts Game</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-blurring-faces-with-best-video-editing-software/"><u>New In 2024, Blurring Faces with Best Video Editing Software</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-call-failed-problems-in-windows-devices/"><u>Addressing 'Call Failed' Problems in Windows Devices</u></a></li>
</ul></div>
