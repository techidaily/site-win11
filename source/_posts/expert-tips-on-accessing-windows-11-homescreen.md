---
title: Expert Tips on Accessing Windows 11 Homescreen
date: 2024-07-13T09:54:15.850Z
updated: 2024-07-14T09:54:15.850Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips on Accessing Windows 11 Homescreen
excerpt: This Article Describes Expert Tips on Accessing Windows 11 Homescreen
keywords: Win11 Homescreen Tricks,Access Windows 11 Ease,Navigate Home Screen Quickly,Expert Window 11 Tips,Optimize Windows 11 Viewing,Master Windows 11 Interface,Speed Up Windows 11 Homescreen
thumbnail: https://thmb.techidaily.com/13322664753ec1bcb9b951122efdf005d8bc61a3a13c44fac0ae0c8584b8720e.jpg
---

## Expert Tips on Accessing Windows 11 Homescreen

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/rethinking-upgrades-windows-11s-improvement-focus/"><u>Rethinking Upgrades: Windows 11’S Improvement Focus</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-mp3-to-mp4-conversion-101-key-considerations-for-success/"><u>New In 2024, MP3 to MP4 Conversion 101 Key Considerations for Success</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-efficient-workflow-screen-recording-techniques-in-os-x-via-keyboard-shortcuts-for-2024/"><u>[New] Efficient Workflow  Screen Recording Techniques in OS X via Keyboard Shortcuts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-disable-microsoft-edge-tab-preloading-in-windows-11/"><u>4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Xiaomi Redmi 12 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-silencing-windows-11-operations/"><u>Ultimate Guide: Silencing Windows 11 Operations</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-wakeable-entities-on-dormant-windows/"><u>Controlling Wakeable Entities on Dormant Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-tales-that-echo-through-time-top-8-halls-for-storytellers/"><u>In 2024, Tales That Echo Through Time  Top 8 Halls for Storytellers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-unlocking-fb-top-8-free-downloader-tools/"><u>[New] In 2024, Unlocking FB  Top 8 Free Downloader Tools</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-harmonizing-snaps-integrating-tunes-seamlessly-for-2024/"><u>[Updated] Harmonizing Snaps  Integrating Tunes Seamlessly for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-video-cropping-101-a-beginners-guide-to-using-avidemux/"><u>Updated 2024 Approved Video Cropping 101 A Beginners Guide to Using Avidemux</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-v30-lite-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo V30 Lite 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-14-pro-max-drfone-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-g22-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Nokia G22 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/fx-artisan-suite-for-2024/"><u>[New] VFX Artisan Suite for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-y77t-by-fonelab-android-recover-music/"><u>The way to get back lost music from Y77t</u></a></li>
<li><a href="https://techidaily.com/tecno-video-recovery-recover-deleted-videos-from-tecno-by-fonelab-android-recover-video/"><u>Tecno Video Recovery - Recover Deleted Videos from Tecno</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-clutter-windows-generative-erasure/"><u>Say Goodbye to Clutter: Windows' Generative Erasure</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-mitigate-local-security-offline-issue/"><u>Essential Steps to Mitigate Local Security Offline Issue</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-best-alternatives-to-blockbuster-flicks/"><u>[New] Best Alternatives to Blockbuster Flicks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-your-video-sticker-take-down-tactics-on-tiktok/"><u>Unlock Your Video  Sticker Take-Down Tactics on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-fast-track-control-windows-taskbar-with-hotkeys/"><u>The Fast Track: Control Windows Taskbar with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/directly-to-dialer-windows-11-tutorial/"><u>Directly to Dialer: Windows 11 Tutorial</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-captivation-creator-for-articles/"><u>In 2024, Captivation Creator for Articles</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-functional-state-in-dead-usb-ports-win-edition/"><u>Enabling Functional State in Dead USB Ports, Win Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-day-wins-best-time-management-solutions/"><u>Streamline Your Day: Win's Best Time Management Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-crashes-sonic-frontiers-full-screen-fixes/"><u>Conquering Crashes: Sonic Frontiers Full-Screen Fixes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-converting-stored-content-into-real-time-livestreams-on-social-media/"><u>2024 Approved  Converting Stored Content Into Real-Time Livestreams on Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-compatible-fingerprint-in-windows/"><u>Troubleshooting No Compatible Fingerprint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-drive-letters-reasons-and-redeeming-solutions-explored/"><u>Windows Without Drive Letters: Reasons and Redeeming Solutions Explored</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-must-have-video-editing-software-for-macos-sierra/"><u>2024 Approved  Top 5 Must-Have Video Editing Software for macOS Sierra</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-system-backups-to-standard-configurations/"><u>Reverting System Backups to Standard Configurations</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-free-skype-recording-made-easy-mp3-edition/"><u>[New] Free Skype Recording Made Easy - MP3 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-github-desktop-adoption-in-windows-11/"><u>Best Practices for GitHub Desktop Adoption in Windows 11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-11-best-pokemon-go-spoofers-for-gps-spoofing-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Pokemon Go Spoofers for GPS Spoofing on Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-budget-efficiency-windows-11-pro-discounts/"><u>Boost Budget Efficiency: Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-1110s-required-privilege-error-code-0x80070522/"><u>Eradicating Windows 11/10'S “Required Privilege” Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-windows-temp-file-deletion-guide/"><u>Effortless Windows Temp File Deletion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win-volume-adjustment-reviving-dull-edges/"><u>Win Volume Adjustment: Reviving Dull Edges</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-obsudios-deep-dive-into-best-screencast-software-for-live-broadcasts/"><u>[New] In 2024, Obsudio's Deep Dive Into Best Screencast Software for Live Broadcasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-xiaomi-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Xiaomi Phone that is Locked?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-poco-x5-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Poco X5’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-4-applications-boosting-windows-audio-capacity/"><u>Sound Superchargers: 4 Applications Boosting Windows' Audio Capacity</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/skip-the-wait-amd-bugs-solved/"><u>Skip the Wait: AMD Bugs Solved</u></a></li>
<li><a href="https://win11.techidaily.com/stutter-no-more-essential-9-tips-to-ensure-fluid-video-on-pcs/"><u>Stutter No More: Essential 9 Tips to Ensure Fluid Video on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insights-into-os-upgrade-schedules-and-methods/"><u>Essential Insights Into OS Upgrade Schedules & Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-rdp-connection-issues-in-modern-oses/"><u>Unblocking RDP Connection Issues in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-computing-experience-best-windows-devices-2024/"><u>Ultimate Computing Experience - Best Windows Devices 2024</u></a></li>
<li><a href="https://win11.techidaily.com/critics-common-grumbles-windows-11-unveiled/"><u>Critics' Common Grumbles: Windows 11 Unveiled</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-xiaomi-redmi-note-12-4g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Xiaomi Redmi Note 12 4G Is Unlocked</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-samsung-galaxy-s24-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-ultimate-catcher-showdown/"><u>[New] 2024 Approved  Ultimate Catcher Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-elevate-presence-by-broadcasting-on-youtube-plus-twitch/"><u>[Updated] Elevate Presence by Broadcasting on YouTube + Twitch</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-windows-server-settings/"><u>Unlocking Secure Windows Server Settings</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-finest-zero-cost-windows-media-devices/"><u>Discover the Finest Zero-Cost Windows Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcoming-stuck-windows-update-fixer/"><u>Swiftly Overcoming Stuck Windows Update Fixer</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-unrecognized-disk-issue-a-comprehensive-guide-for-windows-11-users/"><u>Understanding 'Unrecognized Disk' Issue: A Comprehensive Guide for Windows 11 Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-ultimate-selection-top-10-vimeo-download-tools-unveiled-for-2024/"><u>The Ultimate Selection  Top 10 Vimeo Download Tools Unveiled for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-mobile-video-makers-with-a-beat-the-best-apps-for-android-and-iphone/"><u>2024 Approved Mobile Video Makers with a Beat The Best Apps for Android and iPhone</u></a></li>
</ul></div>
