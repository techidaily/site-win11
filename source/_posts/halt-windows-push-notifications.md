---
title: Halt Windows Push Notifications
date: 2024-12-10T13:20:12.302Z
updated: 2024-12-12T17:26:39.864Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/tep-by-step-guide-to-youtube-video-enhancement-with-wmm-for-2024/"><u>[New] Step-by-Step Guide to YouTube Video Enhancement with WMM for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-elevate-your-streams-step-by-step-discord-tips/"><u>[Updated] Elevate Your Streams Step-by-Step Discord Tips</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-iphone-14-pro-max-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From iPhone 14 Pro Max</u></a></li>
<li><a href="https://fox-that.techidaily.com/bypass-siri-issues-on-ios-devices-addressing-the-top-7-setbacks/"><u>Bypass Siri Issues on iOS Devices: Addressing the Top 7 Setbacks</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210351826-comprehensive-troubleshoot-for-windows-11s-persistent-0xc190n0028-upgrade-hurdle-solutions-included/"><u>Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-installing-the-supercharged-run-tool/"><u>Elevate Your Windows Experience: Installing the Supercharged Run Tool</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-how-to-watch-facebook-live-on-roku/"><u>In 2024, How to Watch Facebook Live on Roku?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/iphotovidsyncer-seamless-imageplusvideo-playback/"><u>IPhotoVidSyncer Seamless Image+Video Playback</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-reliability-defragment-hard-drives-in-win11/"><u>Revamping Reliability: Defragment Hard Drives in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-sailing-overcoming-pc-issues-with-messenger/"><u>Smooth Sailing: Overcoming PC Issues with Messenger</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-automatic-open-of-search-bar-win11-edition/"><u>Stop the Automatic Open of Search Bar, Win11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-top-windows-to-do-apps/"><u>The Ultimate Guide to Top Windows To-Do Apps</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-realme-gt-3-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Realme GT 3 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/why-one-antivirus-works-best-for-windows-users/"><u>Why One Antivirus Works Best for Windows Users</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-note-12-4g-messages-recovery-recover-deleted-messages-from-xiaomi-redmi-note-12-4g-by-fonelab-android-recover-messages/"><u>Xiaomi Redmi Note 12 4G Messages Recovery - Recover Deleted Messages from Xiaomi Redmi Note 12 4G</u></a></li>
</ul></div>

