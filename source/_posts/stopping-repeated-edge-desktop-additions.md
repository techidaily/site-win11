---
title: Stopping Repeated Edge Desktop Additions
date: 2024-07-13T11:05:39.674Z
updated: 2024-07-14T11:05:39.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Repeated Edge Desktop Additions
excerpt: This Article Describes Stopping Repeated Edge Desktop Additions
keywords: Stop Duplicate Edges,End Redundant Edges,Prevent Multiple Edges,Avoid Repetitive Desktops,Cease Edge Repeats,Eliminate Excess Edges,Terminate Extra Edges
thumbnail: https://thmb.techidaily.com/d2538de48c05d03d5115f0d6f4197d40a4705facf7c78bd0835d847acacb8649.jpg
---

## Stopping Repeated Edge Desktop Additions

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
<li><a href="https://youtube-videos.techidaily.com/your-first-youtubian-venture-building-a-brand-bringing-in-bucks/"><u>Your First Youtubian Venture  Building a Brand, Bringing in Bucks</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-infinix-note-30-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Infinix Note 30 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/all-about-iphone-15-unlock-chip-you-need-to-know-by-drfone-ios/"><u>All About iPhone 15 Unlock Chip You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-boundless-treasure-tales-of-instagram-flair/"><u>[Updated] Boundless Treasure Tales of Instagram Flair</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-woes-a-script-error-cure-all-guide/"><u>Tackling Windows Woes: A Script Error Cure-All Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-15-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 15 Pro Max Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-quick-fix-getting-snapchat-installed-on-mac/"><u>[Updated] 2024 Approved  Quick Fix  Getting Snapchat Installed on Mac</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-light-and-shadow-with-iphone-xs-new-lens-technology/"><u>[Updated] Mastering Light & Shadow with iPhone X's New Lens Technology</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-outstanding-movies-overlooked-by-critics/"><u>[Updated] 2024 Approved  Outstanding Movies Overlooked by Critics</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-why-excel-opens-fail-in-notepad/"><u>Understanding Why Excel Opens Fail in Notepad</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-post-update-linux-subsystem-challenges-on-windows-11/"><u>Unraveling Post-Update Linux Subsystem Challenges on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-cut-edit-repeat-the-best-free-video-editing-tools-for-ubuntu/"><u>2024 Approved Cut, Edit, Repeat The Best Free Video Editing Tools for Ubuntu</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-15-pro-passcode-screen-drfone-by-drfone-ios/"><u>How to Unlock iPhone 15 Pro Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-store-issues-address-x80072f17/"><u>Streamlining Windows Store Issues: Address X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-vivo-v27-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Vivo V27 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-interactions-from-power-save-mode/"><u>Steering Device Interactions From Power Save Mode</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-speed-photography-showdown-gopro-hero-4-vs-ghost-s-drift/"><u>[Updated] Speed Photography Showdown  GoPro Hero 4 VS Ghost-S Drift</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-pixelpilot-review-the-years-leading-screen-capture-tech-for-2024/"><u>[New] PixelPilot Review  The Year's Leading Screen Capture Tech for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Vivo Y36i? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/whos-leading-in-screen-capture-tech-obs-studios-vs-bandicam-for-2024/"><u>Who's Leading in Screen Capture Tech  OBS Studios Vs. Bandicam for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-utilizing-apples-messaging-service-on-pc/"><u>Understanding and Utilizing Apple's Messaging Service on PC</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-convert-video-to-gif-28-top-rated-tools/"><u>Updated 2024 Approved Convert Video to GIF 28 Top-Rated Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
</ul></div>
