---
title: Quiet Down Windows' Update Reminders and Alerts
date: 2024-09-12T07:06:57.991Z
updated: 2024-09-16T21:23:47.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quiet Down Windows' Update Reminders and Alerts
excerpt: This Article Describes Quiet Down Windows' Update Reminders and Alerts
keywords: Quiet Window Updates,Silent Notifications,Hush Updates,Muted Alerts,Calm Update Reminders,Soft Windows Notification,Gentle Patching Prompts
thumbnail: https://thmb.techidaily.com/021a636e7cb8e3ab80d8561e5ce2e4b597fd93ffb1b210b719494f43e8dc1394.jpg
---

## Quiet Down Windows' Update Reminders and Alerts

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

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-audio-recording-101-from-youtube-playback-to-files/"><u>[New] 2024 Approved Audio Recording 101 From YouTube Playback To Files</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-transform-instagram-videos-into-mp4-with-top-free-online-tools-windowsosx/"><u>[Updated] In 2024, Transform Instagram Videos Into MP4 with Top Free Online Tools [Windows/OSX]</u></a></li>
<li><a href="https://win11.techidaily.com/7-top-free-tools-like-jibjab-make-custom-e-cards-using-just-your-image/"><u>7 Top Free Tools Like JibJab: Make Custom E-Cards Using Just Your Image</u></a></li>
<li><a href="https://win11.techidaily.com/adobe-media-encoder-mp4/"><u>Adobe Media Encoderで動画変換＆圧縮 - MP4形式への完全ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/best-free-and-premium-pc-based-flv-video-editing-tools-top-picks/"><u>Best Free and Premium PC-Based FLV Video Editing Tools: Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/best-video-conversion-tools-from-dvd-to-mp4-on-windows-11-2024-edition/"><u>Best Video Conversion Tools From DVD to MP4 on Windows 11 - 2024 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/convert-aiff-audio-files-to-free-and-open-source-ogg-format-with-ease/"><u>Convert AIFF Audio Files to Free and Open-Source Ogg Format with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/convert-videos-seamlessly-for-psp-top-tools-that-transform-media-into-optimal-ps-portable-size-and-resolution/"><u>Convert Videos Seamlessly for PSP - Top Tools That Transform Media Into Optimal PS Portable Size and Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-digital-conversion-how-to-upgrade-doobie-brothers-dvds-to-modern-mp4-and-mp3-formats/"><u>Effortless Digital Conversion: How to Upgrade Doobie Brothers DVDs to Modern MP4 and MP3 Formats</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-apple-iphone-12-to-chromecast-drfone-by-drfone-ios/"><u>In 2024, How to Cast Apple iPhone 12 to Chromecast? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-top-7-stardew-valley-enhancements-for-ultimate-farming-bliss/"><u>In 2024, Top 7 Stardew Valley Enhancements for Ultimate Farming Bliss</u></a></li>
<li><a href="https://discover-guides.techidaily.com/itunes-dvdand-windowsmac-os/"><u>ITunes DVD取り込み&再生ガイド | WindowsとMac OS対応</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-control-of-svchostexes-high-cpu-drainage-on-windows-10-machines-proven-fixes/"><u>Mastering the Control of svchost.exe's High CPU Drainage on Windows 10 Machines - Proven Fixes</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-the-common-problem-why-does-my-blender-keep-crashing-and-how-to-fix-it/"><u>Solving the Common Problem: Why Does My Blender Keep Crashing and How To Fix It?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-create-jaw-dropping-slow-mo-videos-with-these-top-10-editors/"><u>Updated Create Jaw-Dropping Slow Mo Videos with These Top 10 Editors</u></a></li>
</ul></div>

