---
title: Halt Windows Push Notifications
date: 2024-12-17T16:02:05.504Z
updated: 2024-12-22T17:06:25.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Halt Windows Push Notifications
excerpt: This Article Describes Halt Windows Push Notifications
keywords: Stop WP Notifications,End Windows Alerts,Silence Windows Pop-Ups,Turn Off WIN Notifications,Disable PC Prompts,Mute Windows Push,Quiet System Alerts
thumbnail: https://thmb.techidaily.com/c06aefbb181f576852b2577ec9d3544ebd6635b5e4bff4964dd308c72eeba377.jpg
---

## Halt Windows Push Notifications

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-8-best-video-call-app-for-android-more-than-4-participants/"><u>[Updated] 2024 Approved 8 Best Video Call App for Android (More than 4 Participants)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-battlefield-geniuses-discovering-the-quintessential-7-total-war-experiences/"><u>[Updated] Battlefield Geniuses Discovering the Quintessential 7 Total War Experiences</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-how-to-record-gameplay-on-xbox-one-for-2024/"><u>[Updated] How to Record Gameplay on Xbox One for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-mastering-full-circle-clips-iphone-filming-tips/"><u>[Updated] Mastering Full-Circle Clips IPhone Filming Tips</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-enhance-show-planning-with-obs-timer-functions/"><u>2024 Approved Enhance Show Planning with OBS Timer Functions</u></a></li>
<li><a href="https://win11.techidaily.com/4-easy-ways-to-create-a-new-folder-in-windows-11/"><u>4 Easy Ways to Create a New Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-windows-11-pitfalls/"><u>Addressing Common Windows 11 Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-saturated-capacity-in-chatgpt/"><u>Alleviating Saturated Capacity in ChatGPT</u></a></li>
<li><a href="https://fox-access.techidaily.com/compile-of-premier-iphone-camera-apps-for-pro-photographers-for-2024/"><u>Compile of Premier iPhone Camera Apps for Pro Photographers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-windows-restoration-options/"><u>Dive Deep Into Windows Restoration Options</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-indefinite-deletion-settings-in-windows-desktop-bin/"><u>Initiating Indefinite Deletion Settings in Windows Desktop Bin</u></a></li>
<li><a href="https://driver-download.techidaily.com/latest-hp-officejet-4500-drivers-free-download-and-installation-guide/"><u>Latest HP OfficeJet 4500 Drivers: Free Download and Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719322242538-mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/reclaim-social-media-control-from-algorithms/"><u>Reclaim Social Media Control From Algorithms</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-normalcy-in-corporate-governed-chromium-and-microsoft-edge-browsing/"><u>Regaining Normalcy in Corporate-Governed Chromium & Microsoft Edge Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-w11s-0x8004def5-onedrive-malfunction/"><u>Unraveling the Mystery of W11's 0X8004def5 OneDrive Malfunction</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-mp4-video-trimming-made-easy-top-free-tools-for-2024/"><u>Updated MP4 Video Trimming Made Easy Top Free Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-difference-between-chkdsk-sfc-and-dism-in-windows/"><u>What Is the Difference Between CHKDSK, SFC, and DISM in Windows?</u></a></li>
<li><a href="https://win-trending.techidaily.com/1728465511519-windows-11/"><u>Windows 11におけるパーティションのデュアル化手順解説</u></a></li>
</ul></div>

