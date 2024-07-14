---
title: Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
date: 2024-07-13T10:14:19.334Z
updated: 2024-07-14T10:14:19.334Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
excerpt: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
keywords: WIN10/11 Account Lock,Unsuccessful Login Limit,Windows Lockout Settings,Preventing Bruteforce Attacks,Adjust Lockout Policy,Access Control in Win10/11,Manage Failed Logins
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
---

## Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11

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
<li><a href="https://instagram-videos.techidaily.com/enhance-your-content-utilizing-the-green-screen-on-instagram-for-2024/"><u>Enhance Your Content  Utilizing the Green Screen on Instagram for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-aesthetic-alchemy-transforming-youtube-videos/"><u>[Updated] Aesthetic Alchemy  Transforming YouTube Videos</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-windows-default-settings-on-reboot/"><u>Quick Tips for Windows Default Settings on Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-mass-unzipping-on-your-pc/"><u>Navigating the Maze of Mass Unzipping on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-high-space-consumers-on-your-windows-machine/"><u>Identifying High-Space Consumers on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-for-reviving-freeze-ups-on-resource-monitor-win11/"><u>Immediate Actions for Reviving Freeze-Ups on Resource Monitor, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-9-methods-for-accessing-windows-11s-audio-control-panel/"><u>Navigate 9 Methods for Accessing Windows 11'S Audio Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/seven-keys-to-unlocking-the-full-potential-of-windows-software/"><u>Seven Keys to Unlocking the Full Potential of Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-11-and-11/"><u>How to Fix a Blank Login Screen in Windows 11 & 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-express-yourself-accessibility-available-for-free/"><u>2024 Approved  Express Yourself, Accessibility Available for Free</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-10-prime-yoga-videos-to-transform-your-body-and-mind/"><u>In 2024, 10 Prime Yoga Videos to Transform Your Body & Mind</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-mastering-mp4-music-a-collection-of-streamlined-audio-extraction-procedures-set-for-2024/"><u>New Mastering MP4 Music A Collection of Streamlined Audio Extraction Procedures Set for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-a-guide-to-mastering-window-11s-taskbar-search-function/"><u>Quick Start: A Guide to Mastering Window 11’S Taskbar Search Function</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-unveiling-top-editors-perfect-entries-any-device/"><u>[New] In 2024, Unveiling Top Editors  Perfect Entries, Any Device</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-add-magic-to-your-phone-videos-best-animated-text-apps/"><u>Updated 2024 Approved Add Magic to Your Phone Videos Best Animated Text Apps</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-unblocking-steam-when-playing-games/"><u>Essential Tips for Unblocking Steam When Playing Games</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ical-integration-on-windows-11-systems/"><u>Mastering iCal Integration on Windows 11 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/master-your-chromebooks-pitch-and-tone-with-our-top-5-web-tools/"><u>Master Your Chromebook's Pitch and Tone with Our Top 5 Web Tools</u></a></li>
<li><a href="https://win11.techidaily.com/new-wave-windows-leap-from-the-legacy-of-11/"><u>New Wave Windows: Leap From the Legacy of 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/making-the-most-of-virtual-reality-space-for-2024/"><u>Making the Most of Virtual Reality Space for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-segmentviewpoint-report/"><u>[Updated] 2024 Approved  SegmentViewpoint Report</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-traditional-windows-explorer-look/"><u>Reclaiming Traditional Windows Explorer Look</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-how-to-send-and-add-snapchat-gifs-100-the-easy-way/"><u>2024 Approved How to Send and Add Snapchat GIFs 100 The Easy Way</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-combine-several-xvid-files-into-one-windows-macandroid-iphone-and-online/"><u>How to Combine Several Xvid Files Into One Windows, Mac，Android, iPhone & Online</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unchecked-cpu-usage-by-wmi-worker/"><u>Fixing Unchecked Cpu Usage by WMI Worker</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-resolve-microphone-problems-on-pc-and-xbox/"><u>Guidelines to Resolve Microphone Problems on PC & Xbox</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-twitch-broadcast-excellence-the-ultimate-5-guide-for-2024/"><u>[Updated] Twitch Broadcast Excellence  The Ultimate 5 Guide for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-top-rated-free-mp4-video-editors-for-cutting-and-trimming/"><u>Updated 2024 Approved Top-Rated Free MP4 Video Editors for Cutting and Trimming</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-office-setup-on-windows-10-and-11-systems/"><u>Mastering Office Setup on WIndows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11-drag-and-drop-failures-now/"><u>Fix Windows 11 Drag-and-Drop Failures Now</u></a></li>
<li><a href="https://win11.techidaily.com/realign-google-chrome-clock-with-windows-time/"><u>Realign Google Chrome Clock with Windows Time</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unveiling-the-powerhouse-techniques-in-facebooks-360-streaming/"><u>2024 Approved  Unveiling the Powerhouse Techniques in Facebook's 360 Streaming</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-amplifying-the-listener-experience-where-to-obtain-professional-podcast-sound-effects/"><u>In 2024, Amplifying the Listener Experience Where to Obtain Professional Podcast Sound Effects</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-elevate-your-call-quality-mastering-facetime-recording-for-2024/"><u>[New] Elevate Your Call Quality  Mastering FaceTime Recording for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pushing-boundaries-a-roundup-of-the-best-nft-generators-available/"><u>[New] Pushing Boundaries  A Roundup of the Best NFT Generators Available</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-pc-with-the-top-10-must-try-powertoy-applications/"><u>Reimagine Your PC with the Top 10 Must-Try PowerToy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-bypassing-non-active-window-firewall/"><u>Methods for Bypassing Non-Active Window Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-absence-of-printmanagement-on-your-system/"><u>Remedying the Absence of 'Printmanagement' On Your System</u></a></li>
<li><a href="https://win11.techidaily.com/is-it-necessary-to-keep-pagefilesys-reasons-explored/"><u>Is It Necessary to Keep Pagefile.sys? Reasons Explored</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-exclusive-nintendo-switch-fighter-lineups-max-156/"><u>2024 Approved  Exclusive Nintendo Switch Fighter Lineups (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-photos-app-background-blur-feature-on-windows-11/"><u>How to Use the Photos App Background Blur Feature on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-windows-uac-prompt-pictures/"><u>Securely Storing Windows UAC Prompt Pictures</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-creating-mp3-files-from-textual-content-on-multiple-operating-systems/"><u>New 2024 Approved Creating MP3 Files From Textual Content on Multiple Operating Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-excessive-windows-contrast-effects/"><u>Disabling Excessive Windows Contrast Effects</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-finding-the-right-mic-a-guide-for-multifaceted-yt-channels/"><u>[New] 2024 Approved  Finding the Right Mic  A Guide for Multifaceted YT Channels</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-motorola-moto-e13-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Motorola Moto E13</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-beginnings-executing-a-clean-windows-11-reinstall/"><u>Fresh Beginnings: Executing a Clean Windows 11 Reinstall</u></a></li>
<li><a href="https://win11.techidaily.com/masked-commands-the-win-1011-trickery-guide/"><u>Masked Commands: The Win 10/11 Trickery Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/stage-talent-video-download-permission-form-for-2024/"><u>Stage Talent  Video Download Permission Form for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-discords-critical-js-error-on-windows-1011-systems/"><u>Resolving Discord's Critical JS Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/immersive-education-experience-windows-11-tutorials/"><u>Immersive Education Experience: Windows 11 Tutorials</u></a></li>
</ul></div>
