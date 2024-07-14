---
title: Crafting Secure Network Shadows in Windows
date: 2024-07-13T11:02:51.996Z
updated: 2024-07-14T11:02:51.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting Secure Network Shadows in Windows
excerpt: This Article Describes Crafting Secure Network Shadows in Windows
keywords: Secure Networks,Windows Security,Cybersecurity,Network Protection,Privacy Safeguards,Safe Shadows,Encrypted Connections
thumbnail: https://thmb.techidaily.com/eea9086dc7bf337d2bb499bc698c2b462f09146348f5ebcda0ff8ce585d15359.jpg
---

## Crafting Secure Network Shadows in Windows

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-setup-utilize-windows-11s-troubleshooting/"><u>Streamline Your Setup: Utilize Windows 11'S Troubleshooting</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-mastering-video-cropping-and-export-for-instagram-posts/"><u>In 2024, Mastering Video Cropping & Export for Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-recently-accessed-windows-documents/"><u>Deciphering Recently Accessed Windows Documents</u></a></li>
<li><a href="https://win11.techidaily.com/studio-2-unleashed-microsofts-near-perfect-creator-tool/"><u>Studio 2 Unleashed: Microsoft's Near-Perfect Creator Tool</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-mend-failed-jvm-initialization-in-windows/"><u>Techniques to Mend Failed JVM Initialization in WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-procedure-for-restoring-original-windows-11-search-settings/"><u>Simplified Procedure for Restoring Original Windows 11 Search Settings</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-installation-sites-for-pc-apps-on-windows/"><u>Tracing Installation Sites for PC Apps on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crack-your-smile-with-these-laughing-and-tearful-ig-meme-pages/"><u>Crack Your Smile with These Laughing & Tearful IG Meme Pages</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-cpu-and-ram-overuse-caused-by-unrealcefsubprocess-on-pcs/"><u>Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-automatic-shutdown-for-w10w11/"><u>Setting Up Automatic Shutdown for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-a-non-functional-spotify-client-in-windows-10/"><u>Troubleshooting a Non-Functional Spotify Client in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-11-calendar-into-daily-life/"><u>Integrating Windows 11 Calendar Into Daily Life</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-device-health-check-up-the-ultimate-guide-for-windows-11s-uptime/"><u>Dive Into Device Health Check-Up: The Ultimate Guide for Windows 11'S Uptime</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-realme-c51-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Realme C51 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-methods-to-autoplay-youtube-videos-on-facebook-in-2024/"><u>[New] Methods to Autoplay Youtube Videos on Facebook, In 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-you-play-mp4-on-htc-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can you play MP4 on HTC ?</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-mitigate-winerror-0x80780119/"><u>Strategies to Mitigate WinError 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-to-status-bar-windows-taskbar-chronology/"><u>From Start to Status Bar: Windows Taskbar Chronology</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-labyrinth-of-identities-finding-sids-on-win11/"><u>Navigating the Labyrinth of Identities: Finding SIDs on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-overcoming-frozen-dark-mode-on-pcs/"><u>Essential Tips: Overcoming Frozen Dark Mode on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-pc-resources-by-unrealcefsubprocess-in-windows/"><u>Tackling Excessive PC Resources by UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-workflows-via-custom-task-integration-into-explorer-menus/"><u>Enhanced Workflows via Custom Task Integration Into Explorer Menus</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-non-interactive-components-on-windows-11/"><u>How to Resolve Non-Interactive Components on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-photo-error-unregistered-package-fix/"><u>Remedying Windows Photo Error: Unregistered Package Fix</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-6-typical-windows-display-issues/"><u>Troubleshooting 6 Typical Windows Display Issues</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-ultimate-guide-to-the-best-10-video-saving-devices/"><u>[New] Ultimate Guide to the Best 10 Video Saving Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-ultimate-photo-frame-tools/"><u>[Updated] Unveiling the Ultimate Photo Frame Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-guides-to-3d-type-exploration/"><u>In 2024, Ultimate Guides to 3D Type Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-with-windows-11-changing-default-actions-smoothly/"><u>Syncing with Windows 11: Changing Default Actions Smoothly</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-file-explorer-experience-with-onedrive-connection/"><u>Enhance File Explorer Experience with OneDrive Connection</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-how-to-enhance-video-rankings-on-youtube-through-seo/"><u>[New] 2024 Approved  How to Enhance Video Rankings on YouTube Through SEO</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-swapping-screen-orientation-by-90-degrees/"><u>The Ultimate Guide to Swapping Screen Orientation by 90 Degrees</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-iphone-14-plus-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and iPhone 14 Plus The Right Way</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-androidiphones-ultimate-guide-top-10-free-photo-overlay-hacks/"><u>2024 Approved  Android/iPhone's Ultimate Guide  Top 10 Free Photo Overlay Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-low-memory-error-on-fantasy-school-of-magical-art/"><u>Remedying Low-Memory Error on Fantasy School of Magical Art</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cleanup-close-multiple-windows-with-one-click/"><u>Quick Cleanup: Close Multiple Windows with One Click</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-application-size-modification-with-keys-on-win11/"><u>Streamlining Application Size Modification with Keys on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-0x80073cf3-in-windows-microsoft-shop/"><u>Resolving Error 0X80073CF3 in Windows' Microsoft Shop</u></a></li>
<li><a href="https://win11.techidaily.com/reliability-monitor-vs-performance-monitor-comparing-two-underutilized-windows-tools/"><u>Reliability Monitor Vs. Performance Monitor: Comparing Two Underutilized Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-controlled-chromeedge-configurations-for-work-computers/"><u>Steps to Tweak Controlled Chrome/Edge Configurations for Work Computers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-scaling-issues-for-high-dpi-screens/"><u>How to Fix Windows Scaling Issues for High DPI Screens</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-speakers-not-detected-issue/"><u>Resolving Windows: Speakers Not Detected Issue</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/0-top-editing-apps-at-no-cost-online-for-2024/"><u>[New] 10 Top Editing Apps at No Cost Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-move-your-qbittorrent-installation-to-a-different-windows-pc/"><u>How to Move Your qBittorrent Installation to a Different Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-attaching-notes-to-windows-apps/"><u>The Art of Attaching Notes to Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/pivotal-security-titans-winning-passwords-in-windows-11/"><u>Pivotal Security Titans: Winning Passwords in Windows 11</u></a></li>
</ul></div>
