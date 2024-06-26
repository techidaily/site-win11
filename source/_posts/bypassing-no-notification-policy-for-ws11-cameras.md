---
title: Bypassing No-Notification Policy for WS11 Cameras
date: 2024-06-25T10:21:09.345Z
updated: 2024-06-26T10:21:09.345Z
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
<li><a href="https://win11.techidaily.com/approaches-to-optimize-cpu-load-from-tiworkerexe/"><u>Approaches to Optimize CPU Load From TiWorker.exe</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-remedying-outlook-failures/"><u>Essential Steps for Remedying Outlook Failures</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-server-stumbled-errors-in-microsoft-store/"><u>Steps to Eliminate Server Stumbled Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-with-windows-11-changing-default-actions-smoothly/"><u>Syncing with Windows 11: Changing Default Actions Smoothly</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/eliciting-hidden-taskbar-recon-in-windows-11/"><u>Eliciting Hidden Taskbar Recon in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/wintime-discrepents-resolved/"><u>WinTime Discrepents Resolved</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-remote-work-fast-and-memory-friendly/"><u>Revitalizing Remote Work: Fast and Memory-Friendly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/send-smiles-wide-step-by-step-for-sharing-gifs-on-snapchat-for-2024/"><u>Send Smiles Wide  Step-by-Step for Sharing Gifs on Snapchat for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-instagram-videographers-manual-enhancing-quality-and-creativity/"><u>The Instagram Videographer's Manual  Enhancing Quality and Creativity</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-samsung-galaxy-f54-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Samsung Galaxy F54 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-ultimate-starters-manual-implementing-voicechanger-on-iphone-for-2024/"><u>New The Ultimate Starters Manual Implementing VoiceChanger on iPhone for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-nokia-c110-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Nokia C110 to Another | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/taxonomy-of-diverse-camera-systems-for-videos/"><u>Taxonomy of Diverse Camera Systems for Videos</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-bring-your-videos-to-life-top-5-iphone-video-editing-apps/"><u>Updated In 2024, Bring Your Videos to Life Top 5 iPhone Video Editing Apps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-guide-to-large-prop-integration-in-tiktok-productions/"><u>[New] In 2024, Guide to Large Prop Integration in TikTok Productions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-lava-blaze-2-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Lava Blaze 2 Phones? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-top-free-online-video-rotators-for-easy-flips/"><u>Updated 2024 Approved Top Free Online Video Rotators for Easy Flips</u></a></li>
</ul></div>
