---
title: How to Turn Off Windows Update Interruptions
date: 2025-01-01T20:41:34.479Z
updated: 2025-01-06T18:19:49.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Off Windows Update Interruptions
excerpt: This Article Describes How to Turn Off Windows Update Interruptions
keywords: WinUpdateStop,EndWindowsUpdates,DisableAutoUpdates,StopUpdaterInterrupts,CeaseWindowsUpdate,ShutOffWindowsUpdates,InterruptionFreeUpdate
thumbnail: https://thmb.techidaily.com/4d7dde3a99efac5f6bdb879d88148e0d5b48fb1025ad045c8786c79687920a30.jpg
---

## How to Turn Off Windows Update Interruptions

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-quickly-amplify-your-tiktok-audience-essential-techniques/"><u>[New] 2024 Approved Quickly Amplify Your TikTok Audience - Essential Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-all-encompassing-razer-camera-report-for-2024/"><u>[New] All-Encompassing Razer Camera Report for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-bridging-communication-gaps-utilizing-zoom-with-gmail-mail/"><u>[New] Bridging Communication Gaps Utilizing Zoom with Gmail Mail</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-convenience-and-efficiency-with-task-scheduler/"><u>Command Line Convenience & Efficiency with Task Scheduler</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/cenes-unlocked-tutorials-to-enhance-viewing-experience-for-2024/"><u>End Scenes Unlocked Tutorials to Enhance Viewing Experience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-future-to-past-windows-11-reskinned-as-98-version/"><u>From Future to Past: Windows 11 Reskinned as '98 Version</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-honor-x50-gt-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ifas-big-unveil-top-laptop-selections-of-2023/"><u>IFA's Big Unveil - Top Laptop Selections of 2023</u></a></li>
<li><a href="https://win-blog.techidaily.com/navigating-the-enigma-comprehensive-analysis-of-beyond-the-wire-incidents/"><u>Navigating the Enigma: Comprehensive Analysis of 'Beyond The Wire' Incidents</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-virtual-machine-start-issues-in-wm11plusvmware/"><u>Overcoming Virtual Machine Start Issues in WM11+VMware</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-display-expert-tips-on-adjusting-themes-in-windows-11/"><u>Revamp Your Display: Expert Tips on Adjusting Themes In Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-future-of-video-capturing-embracing-vimeo-record/"><u>The Future of Video Capturing Embracing Vimeo Record</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-youtubes-power-for-free-educational-sessions-for-2024/"><u>Unlock YouTube's Power for FREE Educational Sessions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-operational-status-of-googles-windowed-nearby-share/"><u>Unlocking Operational Status of Google's Windowed Nearby Share</u></a></li>
</ul></div>

