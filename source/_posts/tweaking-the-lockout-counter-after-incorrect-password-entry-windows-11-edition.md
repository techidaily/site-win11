---
title: Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
date: 2024-07-13T10:59:47.103Z
updated: 2024-07-14T10:59:47.103Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
excerpt: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
keywords: Win11 Password Error Fix,Lockout Counter Update Win11,Correct Pass Retry Options Win11,Preventing Incorrect Login Windows,Windows 11 Lockout Revision,Resetting Windows 11 Login Attempts,Adjusting Password Failures Win11
thumbnail: https://thmb.techidaily.com/a6de986a3fdb94c7142abb7e1738397c8994a30f493de897d20f957481bc1b83.jpg
---

## Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/faster-utorrent-file-sharing-a-guide-for-windows/"><u>Faster uTorrent File Sharing: A Guide for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-image-conversion-in-windows-pc/"><u>Mastering the Art of CR2 Image Conversion in Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-11s-limited-editions-feature-impact/"><u>Assessing Windows 11’S Limited Editions Feature Impact</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-go-no-net-with-your-new-os-win11/"><u>How to Go No Net With Your New OS, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/displaying-numeric-key-status-in-system-tray-for-win11-users/"><u>Displaying Numeric Key Status in System Tray for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-task-management-learn-filters-and-themes-customization-in-windows-11/"><u>Boost Productivity with Task Management: Learn Filters and Themes Customization in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/curing-frozen-windows-desktop-context-options/"><u>Curing Frozen Windows Desktop Context Options</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-repairing-your-windows-11-printer/"><u>Essential Tips for Repairing Your Windows 11 Printer</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-freely-stream-your-films-easy-to-use-mov-player-software/"><u>2024 Approved  Freely Stream Your Films  Easy-to-Use MOV PLAYER Software</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-stalled-windows-batch-processes/"><u>Guide to Reactivating Stalled Windows Batch Processes</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-upgrading-made-simple-a-compreomedmacsierra-guide-for-2024/"><u>[Updated] Upgrading Made Simple  A CompreomedmacSierra Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-pick-prime-photo-organizers-for-windows/"><u>Excellent Pick: Prime Photo Organizers For Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-foundation-of-a-great-facebook-presence-mastering-covers/"><u>[New] 2024 Approved  The Foundation of a Great Facebook Presence  Mastering Covers</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unresponsive-windows-service-error-error-1053/"><u>Eliminating the Unresponsive Windows Service Error (Error 1053)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/eliminating-blurry-visuals-from-streamed-youtube-content/"><u>Eliminating Blurry Visuals From Streamed YouTube Content</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-lyric-video-makers-online-top-picks-for-every-budget-for-2024/"><u>Updated Lyric Video Makers Online Top Picks for Every Budget for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-ultimate-list-of-lyric-video-makers-free-paid-and-everything-in-between/"><u>Updated 2024 Approved The Ultimate List of Lyric Video Makers Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-signs-youre-not-in-someones-contact-list/"><u>2024 Approved  Signs You're Not in Someone's Contact List</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-comprehensive-policies-reports-via-gpresult/"><u>Crafting Comprehensive Policies Reports via GPResult</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-your-unique-fashion-voice/"><u>2024 Approved  Mastering Your Unique Fashion Voice</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-v30-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fan-the-fire-essential-tips-for-cooler-gameplay-on-overheated-windows-laptops/"><u>Fan the Fire: Essential Tips for Cooler Gameplay on Overheated Windows Laptops</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-how-to-crop-a-video-with-avidemux/"><u>New 2024 Approved How to Crop a Video with Avidemux</u></a></li>
<li><a href="https://win11.techidaily.com/curating-a-personal-touch-for-windows-mouse-pointer/"><u>Curating a Personal Touch for Windows Mouse Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/easing-shared-printer-usage-conflict/"><u>Easing Shared Printer Usage Conflict</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-patchwork-pros-how-to-assemble-engaging-tiktoks/"><u>[Updated] Patchwork Pros  How to Assemble Engaging TikToks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-syncing-visuals-and-soundtracks-in-video-magic/"><u>[New] Syncing Visuals & Soundtracks in Video Magic</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-secure-social-scale-the-premier-app-selection-for-ios-and-android-users/"><u>[Updated] 2024 Approved  Secure Social Scale - The Premier App Selection for iOS & Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overwatch-2s-missing-graphics-driver-error/"><u>Fixing Overwatch 2'S Missing Graphics Driver Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-deciphering-digital-self-identity-the-insta-selfie-guide/"><u>2024 Approved  Deciphering Digital Self-Identity  The Insta Selfie Guide</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-a-spotless-system-restart-in-windows-11/"><u>Achieving a Spotless System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-how-to-turn-off-games-for-w11-suggestions/"><u>Learn How To Turn Off Games for W11 Suggestions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-fcp-mastery-top-5-editing-tips-and-tricks-from-the-experts/"><u>Updated FCP Mastery Top 5 Editing Tips and Tricks From the Experts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-augmented-reality-shading-exploiting-free-lut-resources-for-ar/"><u>[New] Augmented Reality Shading  Exploiting Free LUT Resources for AR</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-understanding-a-blue-icons-role-facebooks-communication-tool/"><u>[New] In 2024, Understanding a Blue Icon’s Role  Facebook's Communication Tool</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-no-notification-policy-for-ws11-cameras/"><u>Bypassing No-Notification Policy for WS11 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unsigned-files-error-for-windows-1110/"><u>Bypassing Unsigned Files Error for Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-no-hypervisor-detection-in-sandbox-mode/"><u>How to Address No Hypervisor Detection in Sandbox Mode</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-transformation-mp3-files-to-windows-compatible-audio-cds-with-imgburn/"><u>Immediate Transformation: MP3 Files to Windows-Compatible Audio CDs with ImgBurn</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-10-affordable-mobile-apps-to-boost-your-images-visual-impact/"><u>2024 Approved  10 Affordable Mobile Apps to Boost Your Image's Visual Impact</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-harmony-windows-app-compatible-with-apple-and-microsoft-pcsmacs/"><u>Cross-Platform Harmony: Windows App Compatible with Apple & Microsoft PCs/Macs</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11.</u></a></li>
<li><a href="https://win11.techidaily.com/guide-recovering-invisible-bluetooth-in-device-manager/"><u>Guide: Recovering Invisible Bluetooth in Device Manager</u></a></li>
</ul></div>
