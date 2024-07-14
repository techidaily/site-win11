---
title: Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
date: 2024-07-13T10:17:59.264Z
updated: 2024-07-14T10:17:59.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
excerpt: This Article Describes Updating Reset Limit After Unsuccessful Authentication in Windows 10/11
keywords: WinResetLimitUpdate,AuthFailWindowsUpdate,WindowsAuthenticationLimit,UpdateLoginLimitError,ResetLimitUnAuthW10x11,AuthenticationResetLimit,UnsuccessfulWinResetUpd
thumbnail: https://thmb.techidaily.com/9c54005e696cd2ed7b70760eb63ef402583a5567abcd354a24f074d4d0059be5.jpg
---

## Updating Reset Limit After Unsuccessful Authentication in Windows 10/11

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
<li><a href="https://win11.techidaily.com/clear-your-screen-clutter-advanced-window-organization-win11-and-10/"><u>Clear Your Screen Clutter: Advanced Window Organization (Win11 & 10)</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-rearranged-letters-in-windows-system/"><u>Eradicating Rearranged Letters in Windows System</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-forget-youtube-try-these-top-5-video-editor-options-for-2024/"><u>[New] Forget Youtube? Try These Top 5 Video Editor Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-window-11-apps-essential-tips/"><u>Fast-Track Window 11 Apps: Essential Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-anydesk-troubleshooting-in-windows/"><u>Essential Techniques: AnyDesk Troubleshooting in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-building-a-powerhouse-business-channel-in-under-5-minutes/"><u>[New] Building a Powerhouse Business Channel in Under 5 Minutes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-facebook-video-extravaganza-the-most-advanced-fire-browser-tools-updated-for-2024/"><u>[New] Facebook Video Extravaganza  The Most Advanced Fire-Browser Tools, Updated for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-restrictive-settings-from-steam-libraries-win-11/"><u>Eradicating Restrictive Settings From Steam Libraries Win 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-audiophiles-guide-techniques-to-elevate-sound-recording/"><u>[Updated] In 2024, Audiophile's Guide  Techniques to Elevate Sound Recording</u></a></li>
<li><a href="https://win11.techidaily.com/assigning-custom-codes-to-windows-software/"><u>Assigning Custom Codes to Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/digging-into-drive-labels-c-and-d-unpacked/"><u>Digging Into Drive Labels: C & D Unpacked</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://facebook.techidaily.com/why-your-digital-footprint-deserves-a-break-the-case-for-quitting-facebook/"><u>Why Your Digital Footprint Deserves a Break: The Case for Quitting Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-snapchat-marketing-playbook-boosting-sales/"><u>2024 Approved  The SnapChat Marketing Playbook  Boosting Sales</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-writable-html-in-email-settings/"><u>Addressing Windows 11' Writable HTML in Email Settings</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>How to Fake Snapchat Location without Jailbreak On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-precision-ditch-delays-top-fixes-for-bf2-players/"><u>Unleash Precision, Ditch Delays: Top Fixes for BF2 Players</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-funny-carousel-image-builder-for-2024/"><u>[Updated] Funny Carousel Image Builder for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-15-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 15</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-adobe-premiere-pro-tutorial-how-to-remove-camera-shake-and-stabilize-footage/"><u>Updated 2024 Approved Adobe Premiere Pro Tutorial How to Remove Camera Shake and Stabilize Footage</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-office-hours-the-top-5-task-boosting-tools-for-win-11/"><u>Elevate Your Office Hours: The Top 5 Task-Boosting Tools for Win 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mobilizing-money-a-complete-guide-to-youtubes-revenue-features/"><u>2024 Approved  Mobilizing Money  A Complete Guide to YouTube's Revenue Features</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-corrupted-filesystems-in-windows-11/"><u>Correcting Corrupted Filesystems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-limit-windows-sonic-amplification/"><u>How To Limit Windows Sonic Amplification</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-hashtag-mastery-enhancing-freefire-gameplay-videos/"><u>[Updated] 2024 Approved  Hashtag Mastery  Enhancing FreeFire Gameplay Videos</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-typing-speed-7-latency-fixes-revealed/"><u>Enhance Windows 11 Typing Speed: 7 Latency Fixes Revealed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-15-best-windows-pc-screen-recorders-for-2024/"><u>[New] 15 Best Windows PC Screen Recorders for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-shot-to-spectacle-pro-tips-for-transformative-photographic-edits/"><u>[New] From Shot to Spectacle  Pro Tips for Transformative Photographic Edits</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-novice-film-capture-scrutiny-report/"><u>In 2024, Novice Film Capture Scrutiny Report</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-powerful-tools-for-windows-users/"><u>Conjuring Powerful Tools for Windows Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-your-viewers-your-wealth-building-an-earning-strategy/"><u>In 2024, Your Viewers, Your Wealth  Building an Earning Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-peace-sleep-functions-in-windows/"><u>Bringing Peace: Sleep Functions in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/penning-powerful-stories-with-a-camera-lens-for-2024/"><u>Penning Powerful Stories with a Camera Lens for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-handle-installation-hiccups-win11/"><u>Clearing Up Confusion: How to Handle Installation Hiccups (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-hibernate-depression-in-windows/"><u>Combatting Hibernate Depression in Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-best-green-screen-recorders-how-to-use-them/"><u>[Updated] 2024 Approved  Best Green Screen Recorders  How to Use Them?</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-mobility-settings-quick-guide-win-11/"><u>Turn Off Windows Mobility Settings Quick Guide (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-beginners-guide-to-github-desktop-for-windows-users/"><u>A Compreenas Beginners Guide to GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/avoid-distraction-with-firm-footage-capture/"><u>Avoid Distraction with Firm Footage Capture</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-a-comprehensive-list-of-top-video-making-software-iphone-android/"><u>[Updated] 2024 Approved  A Comprehensive List of Top Video-Making Software (iPhone, Android)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-s17-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo S17</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/synchronous-capture-for-webcam-and-display-for-2024/"><u>Synchronous Capture for Webcam and Display for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-increase-windows-disk-size-securely/"><u>Strategies to Increase Windows Disk Size Securely</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/leading-win11-screen-recording-apps-ranked-top-15-for-2024/"><u>Leading Win11 Screen Recording Apps Ranked (Top 15) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/total-extraction-of-wsl-from-windows-11-screens/"><u>Total Extraction of WSL From Windows 11 Screens</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-from-novice-to-expert-a-comprehensive-guide-to-macscreencasting/"><u>[New] In 2024, From Novice to Expert  A Comprehensive Guide to MacScreencasting</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-chaos-to-clarity-picshot-transforms-photo-collages/"><u>From Chaos to Clarity - Picshot Transforms Photo Collages</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-webcam-creation-video-making-for-mac-users/"><u>[Updated] In 2024, Webcam Creation  Video Making for Mac Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-enter-virtual-realms-top-10-immersive-videos/"><u>[New] Enter Virtual Realms  Top 10 Immersive Videos</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-ip-command-prompt-guide-for-pcs/"><u>Discover Your IP: Command Prompt Guide for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-default-pdf-viewer/"><u>Switching Windows' Default PDF Viewer</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-nightmares-unleashed-8-must-play-zombie-games-explored/"><u>In 2024, Nightmares Unleashed  8 Must-Play Zombie Games Explored</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-speaking-in-code-learn-discords-text-to-speech/"><u>[Updated] In 2024, Speaking in Code  Learn Discord's Text-to-Speech</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-the-depths-of-firefox-pip-feature/"><u>[Updated] Exploring the Depths of Firefox PIP Feature</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-exploring-the-sound-emission-from-button-activation/"><u>New Exploring the Sound Emission From Button Activation</u></a></li>
<li><a href="https://win11.techidaily.com/instant-use-of-snipping-tool-on-modern-windows-os/"><u>Instant Use of Snipping Tool on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-file-access-failures-in-windows/"><u>Correcting File Access Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-iomap64-bsod-errors-in-windows-108/"><u>Strategies to Resolve IOMap64 BSOD Errors in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-vanished-panes-top-strategies-to-recover-off-screen-apps-on-win-10/"><u>Breathe Life Into Vanished Panes! Top Strategies to Recover Off-Screen Apps on Win 10</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-unveiling-the-essence-of-tiktoks-anime-culture-celebrating-movement-and-sound-expression/"><u>In 2024, Unveiling the Essence of TikTok's Anime Culture  Celebrating Movement & Sound Expression</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-upside-down-world-of-instagram-videos/"><u>2024 Approved  Exploring the Upside-Down World of Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-using-github-desktop-for-windows-11-dev-teams/"><u>Tailored Guide to Using GitHub Desktop for Windows 11 Dev Teams</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-everything-from-apple-iphone-11-pro-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Everything from Apple iPhone 11 Pro Max to iPhone 8/X/11 | Dr.fone</u></a></li>
</ul></div>
