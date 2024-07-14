---
title: Avoiding Disruptions to WSL After Installing Windows 11
date: 2024-07-13T11:27:20.928Z
updated: 2024-07-14T11:27:20.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Disruptions to WSL After Installing Windows 11
excerpt: This Article Describes Avoiding Disruptions to WSL After Installing Windows 11
keywords: Win11 Stability,WSL Post-Upgrade,Noise Prevention in WSL,WSL Windows Compatibility,Smooth WSL Transition,WSL Installation Tips,Minimize WSL Disturbances
thumbnail: https://thmb.techidaily.com/172d2b5e16d3f59f8f3e9aeaa8db2d7a1dcd42c1282454326ca1c10c6fe01b75.jpg
---

## Avoiding Disruptions to WSL After Installing Windows 11

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a [full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://win11.techidaily.com/beat-the-sluggish-pace-of-win-based-outlook/"><u>Beat the Sluggish Pace of Win-Based Outlook</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-how-to-find-3d-animation-studio-meeting-all-your-inspiring-needs/"><u>New In 2024, How to Find 3D Animation Studio Meeting All Your Inspiring Needs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-macs-optimal-clipping-options-reviewed/"><u>[New] 2024 Approved  Mac's Optimal Clipping Options Reviewed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-a-simple-approach-to-youtube-statistics-review/"><u>[Updated] 2024 Approved  A Simple Approach to YouTube Statistics Review</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-energy-drain-auto-shutdown-at-idle-in-win11/"><u>Avoiding Energy Drain: Auto-Shutdown at Idle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-visual-quality-enable-win11s-color-adjustment/"><u>Boosting Visual Quality: Enable Win11's Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-to-boost-file-organization-with-multi-folder-setup-in-windows-1011/"><u>Advanced Tactics to Boost File Organization with Multi-Folder Setup in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/adopting-new-visual-elements-the-microsoft-store-experience/"><u>Adopting New Visual Elements: The Microsoft Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-remote-procedure-call-mishaps-in-windows/"><u>Avoiding Remote Procedure Call Mishaps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boost-brainpower-proven-techniques-to-master-studying-on-windows/"><u>Boost Brainpower: Proven Techniques to Master Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-fcpx-university-the-best-online-learning-platforms-and-websites/"><u>New In 2024, FCPX University The Best Online Learning Platforms and Websites</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-be-bold-on-igtv-the-10-cutting-edge-video-concepts-for-your-brand/"><u>[New] 2024 Approved  Be Bold on IGTV  The 10 Cutting-Edge Video Concepts for Your Brand</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-epicurean-explosion-tasty-international-dishes-for-2024/"><u>[Updated] Epicurean Explosion  Tasty International Dishes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bolster-window-app-interactions-via-efficient-internet-accessing-methods/"><u>Bolster Window App Interactions via Efficient Internet Accessing Methods</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-in-win-11-with-top-7-essential-widgets/"><u>Boost Productivity in Win 11 with Top 7 Essential Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-write-prohibited-steam-directories-in-win-11/"><u>Addressing Write-Prohibited Steam Directories in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-mastering-the-search-function-of-windows-11/"><u>Boost Productivity: Mastering the Search Function of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-pixelgrabber-w11-simplest-screen-to-video-converter-for-2024/"><u>[New] PixelGrabber W11  Simplest Screen to Video Converter for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-list-of-online-video-editors-with-music-integration/"><u>2024 Approved The Ultimate List of Online Video Editors with Music Integration</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-apple-iphone-14-plus-5-ways-to-get-into-a-locked-apple-iphone-14-plus-by-drfone-ios/"><u>Locked Out of Apple iPhone 14 Plus? 5 Ways to get into a Locked Apple iPhone 14 Plus</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/ipads-best-practices-for-clear-voice-recording/"><u>IPad's Best Practices for Clear Voice Recording</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-free-windows-movie-maker-download-your-one-stop-installation-resource/"><u>2024 Approved Free Windows Movie Maker Download Your One-Stop Installation Resource</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://extra-hints.techidaily.com/chinese-vr-headset-marketplace-wonders/"><u>Chinese VR Headset Marketplace Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnection-hurdles-in-nvidia-for-windows-users/"><u>Addressing Disconnection Hurdles in Nvidia for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breach-are-windows-fingerprint-scanners-safe/"><u>Biometric Breach: Are Windows Fingerprint Scanners Safe?</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-non-working-cut-and-paste-in-win-11/"><u>Ameliorating Non-Working Cut and Paste in Win 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovating-with-3d-text-effects-in-adobe-photoshop-for-2024/"><u>Innovating with 3D Text Effects in Adobe Photoshop for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-transform-how-you-talk-best-mobile-apps-to-alter-vocal-quality/"><u>2024 Approved  Transform How You Talk  Best Mobile Apps to Alter Vocal Quality</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-how-to-ensure-the-best-live-experience-with-top-networks/"><u>[Updated] How to Ensure the Best Live Experience with Top Networks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-commanding-attention-on-digital-platforms-via-custom-designs/"><u>[New] In 2024, Commanding Attention on Digital Platforms via Custom Designs</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-crashes-solving-0x80072f30-error/"><u>Avoiding Microsoft Store Crashes: Solving 0X80072F30 Error</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-exclusive-guide-save-high-res-fb-video-for-2024/"><u>[Updated] Exclusive Guide  Save High-Res FB Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-workload-of-ntoskrnlexe/"><u>Balancing the Workload of Ntoskrnl.exe</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-troubles-15-windows-fixes-to-consider/"><u>Arrow Troubles? 15 Windows Fixes to Consider</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/transforming-tiktok-videos-a-guide-to-audio-amplification-techniques-for-2024/"><u>Transforming TikTok Videos  A Guide to Audio Amplification Techniques for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-crafting-realities-on-android-the-premier-15-gaming-experienences/"><u>[New] In 2024, Crafting Realities on Android  The Premier 15 Gaming Experienences</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlocking-the-potential-of-snapchat-highlights/"><u>Unlocking the Potential of Snapchat Highlights</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-a-world-of-videos-made-easy-with-vidas-aid/"><u>[New] Navigating a World of Videos Made Easy with Vida's Aid</u></a></li>
<li><a href="https://win11.techidaily.com/boost-work-efficiency-select-6-best-pc-monitoring-apps/"><u>Boost Work Efficiency: Select 6 Best PC Monitoring Apps</u></a></li>
<li><a href="https://win11.techidaily.com/block-unwanted-startup-stop-snipping-tool-from-prtscan-on-win-11/"><u>Block Unwanted Startup: Stop Snipping Tool From PrtScan on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime</u></a></li>
</ul></div>
