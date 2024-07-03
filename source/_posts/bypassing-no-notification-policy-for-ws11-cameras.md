---
title: Bypassing No-Notification Policy for WS11 Cameras
date: 2024-06-25T11:34:57.853Z
updated: 2024-06-26T11:34:57.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing No-Notification Policy for WS11 Cameras
excerpt: This Article Describes Bypassing No-Notification Policy for WS11 Cameras
keywords: Bypass Notification,Camera Alert Skip,Disable Notify Feature,Cam Privacy Control,WS11 No-Alert,Security Camera Silence,Unnotified WS11 Cameras
thumbnail: https://thmb.techidaily.com/70cafb81e97d380bf1f55403cf595cebfeb242757ff19f24408692f694faf166.jpg
---

## Bypassing No-Notification Policy for WS11 Cameras

 Have you noticed your camera LED randomly lighting up? Are you worried that malicious software can access your camera at any time?

 By default, Windows turns on the LED next to your webcam every time your camera is accessed. But if you’re in a well-lit environment or something is covering the LED, you might miss it. Also, the LED might be broken, so there’s no way of telling if your camera is on.

 The good news is that you can have Windows 11 display a desktop notification to let you know whether your camera is turned on or off.

## How to Turn On Camera On and Off Notifications

 You need administrative rights to turn on camera notifications. So, if you’re using a local account, check out[how to switch to an account with administrative rights on Windows 11](https://www.makeuseof.com/windows-11-switch-user-accounts/) . Then, follow these steps to edit the Registry Editor:

1. Press**Winy + R** to bring up a Run dialog.
2. Type**regedit** and press**Enter** .
3. In the Registry Editor, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > OEM > Device > Capture** .
4. Locate and open**NoPhysicalCameraLED** .
5. Set**Value data** to**1** to enable the notifications.
6. Click**OK** and restart your computer.

![Enable camera notifications in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/notify-camera-1.jpg)

 If the**NoPhysicalCameraLED** value is missing, you can create it. Right-click on the empty space in the right pane, and click**New > Dword(32-bit) value** . Set its name and**Value data** to**1** . Then, save the new changes and restart your computer for the changes to take place.

 Changing the value to**1** doesn’t impact your camera LED. It will still light up every time you access the camera. If you want to revert the change, go through the above instructions again and set**Value data** to**0** .

 Once your computer boots up access the camera and test if Windows is showing the camera notification.

## How to Check Camera History

 If you missed the notification, Windows 11 allows you to check which apps have accessed your camera. Launch Windows Settings and go to**Privacy & security > Camera** . There, check the**Recent activity** section.

 Also, it might be worth it to take a look at your Privacy settings and[check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

## Know When Your Camera Starts on Windows

 Now, every time an app accesses your camera, Windows 11 will let you know. But if you want to add an extra layer to your privacy, you should consider placing tape over the camera.


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
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-disabling-laptops-hardware-keys-on-windows-pc/"><u>Guide: Disabling Laptop's Hardware Keys on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/standby-struggles-dissecting-modern-standby-issues/"><u>Standby Struggles: Dissecting Modern Standby Issues</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-refusal-to-execute-exe-files/"><u>Decoding Windows' Refusal to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-procedure-of-sfc-scanning/"><u>Unraveling the Procedure of SFC Scanning</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-solid-state-drive-harnessing-power-of-windows-and-fresh/"><u>Elevate Your Solid State Drive - Harnessing Power of Windows & Fresh</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-silent-tab-disabling-in-windows-11/"><u>Navigating to Silent Tab Disabling in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-vivo-s17-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Vivo S17 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-bridge-the-gap-transferring-files-from-pc-to-ios/"><u>In 2024, Bridge the Gap  Transferring Files From PC to iOS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oneplus-nord-ce-3-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track OnePlus Nord CE 3 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/1716169136059-2024-approved-how-to-reverse-image-search-instagram/"><u>2024 Approved  How to Reverse Image Search Instagram</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-advanced-techniques-in-itunes-video-saving/"><u>2024 Approved  Advanced Techniques in iTunes Video Saving</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-15-pro-max-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 15 Pro Max without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-elevate-group-video-sessions-with-discords-share-functionality/"><u>[New] Elevate Group Video Sessions with Discord's Share Functionality</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-gathered-group-glances/"><u>2024 Approved  Gathered Group Glances</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-elevate-your-online-presence-with-these-top-30-username-ideas/"><u>[New] In 2024, Elevate Your Online Presence with These Top 30 Username Ideas</u></a></li>
</ul></div>
