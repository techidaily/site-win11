---
title: Bypassing No-Notification Policy for WS11 Cameras
date: 2024-07-13T10:29:41.142Z
updated: 2024-07-14T10:29:41.142Z
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

 You need administrative rights to turn on camera notifications. So, if you’re using a local account, check out [how to switch to an account with administrative rights on Windows 11](https://www.makeuseof.com/windows-11-switch-user-accounts/) . Then, follow these steps to edit the Registry Editor:

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

 Also, it might be worth it to take a look at your Privacy settings and [check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

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
<li><a href="https://extra-support.techidaily.com/new-shine-strategy-top-tools-to-brighten-streams/"><u>[New] Shine Strategy  Top Tools to Brighten Streams</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-d3d11-compatible-gpu-faults-in-w11-and-w10/"><u>Addressing D3D11-Compatible GPU Faults in W11 & W10</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-reset-account-lockout-counter-after-failed-logins-win-11-edition/"><u>Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/unlock-professional-video-capturing-key-insights-for-2024/"><u>Unlock Professional Video Capturing  Key Insights for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-pinnacle-of-presence-a-strategic-approach-for-live-video-graphics/"><u>[Updated] In 2024, Pinnacle of Presence  A Strategic Approach for Live Video Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabling-directives-essential-4-fixes-to-windows-ps-load-issue/"><u>Bypassing Disabling Directives: Essential 4 Fixes to Windows PS Load Issue</u></a></li>
<li><a href="https://extra-tips.techidaily.com/total-expense-outline-the-economics-of-starting-a-podcast/"><u>Total Expense Outline  The Economics of Starting a Podcast</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-safety-turning-on-folder-controls-in-windows/"><u>Mastering File Safety: Turning On Folder Controls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-securely-without-screensaver/"><u>Unlock Windows 11 Securely Without Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/index-management-in-windows-1011/"><u>Index Management in Windows 10/11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/10-advanced-techniques-to-master-with-canva-designer/"><u>10 Advanced Techniques to Master with Canva Designer</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-windows-potential-with-new-widgets/"><u>Maximize Your Window's Potential with New Widgets</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-instagram-maximizing-post-engagement-for-2024/"><u>[New] Mastering Instagram  Maximizing Post Engagement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photo-perfection-troubleshooting-made-simple/"><u>Windows Photo Perfection: Troubleshooting Made Simple</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/discovering-the-fury-in-canine-vocalizations/"><u>Discovering the Fury in Canine Vocalizations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-restart-efficient-three-ways/"><u>Mastering Windows Restart: Efficient Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-emails-adding-gmail-accounts-to-outlook-windows-style/"><u>Uniting Emails: Adding Gmail Accounts to Outlook, Windows Style</u></a></li>
<li><a href="https://win11.techidaily.com/7-solutions-for-resolving-windows-11-naming-issues-in-directories/"><u>7 Solutions for Resolving Windows 11 Naming Issues in Directories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hero-11-vs-max-360-deciding-the-top-tier-gopro-video-camera/"><u>In 2024, Hero 11 vs Max 360 - Deciding the Top-Tier GoPro Video Camera</u></a></li>
<li><a href="https://win11.techidaily.com/improve-cs-global-offensive-speed-and-precision/"><u>Improve CS Global Offensive Speed and Precision</u></a></li>
<li><a href="https://win11.techidaily.com/keygen-virus-threat-assessment-causes-consequences-and-system-protection/"><u>Keygen Virus Threat Assessment: Causes, Consequences, & System Protection</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-oppo-reno-11-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Oppo Reno 11 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2023-updates-the-next-generation-of-samsung-k850u/"><u>2023 Updates - The Next Generation of Samsung K850U</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disconnects-resolving-fall-guys-errors-on-windows/"><u>Overcoming Disconnects: Resolving Fall Guys Errors on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/upgrading-your-videos-appeal-youtube-thumbnail-resizing-for-2024/"><u>Upgrading Your Video's Appeal  YouTube Thumbnail Resizing for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-oppo-f25-pro-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Oppo F25 Pro 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-nitro-free-a-guide-to-animated-gifs-and-emoji-use-in-discord-chat/"><u>[New] 2024 Approved  Nitro-Free  A Guide to Animated GIFs & Emoji Use in Discord Chat</u></a></li>
<li><a href="https://audio-editing.techidaily.com/streamlining-the-capture-of-podcast-archives-for-computer-devices-for-2024/"><u>Streamlining the Capture of Podcast Archives for Computer Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-windows-11s-time-and-date/"><u>Hiding or Showing Windows 11'S Time and Date</u></a></li>
<li><a href="https://win11.techidaily.com/unbeatable-black-friday-save-612-on-windows-10/"><u>Unbeatable Black Friday: Save $6.12 on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-note-apps-for-the-modern-windows-slates/"><u>Perfect Note Apps for the Modern Windows Slates</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-jumpstart-your-tiktok-presence-with-these-30-standout-nicknames-for-2024/"><u>[New] Jumpstart Your TikTok Presence with These 30 Standout Nicknames for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-of-0xc000003e-error-on-pcs/"><u>Mastering the Fix of 0xC000003E Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-11-task-managers-perfect-for-organizing-daily-chores/"><u>Top 6 Windows 11 Task Managers Perfect for Organizing Daily Chores</u></a></li>
<li><a href="https://win11.techidaily.com/error-handling-strategies/"><u>Error Handling Strategies:</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-backspace-abnormalities-in-modern-os/"><u>Overcoming Backspace Abnormalities in Modern OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-create-luts-with-luts-generator/"><u>Updated How to Create LUTs with LUTs Generator</u></a></li>
</ul></div>
