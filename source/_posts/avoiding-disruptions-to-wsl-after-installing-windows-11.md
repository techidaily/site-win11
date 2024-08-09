---
title: Avoiding Disruptions to WSL After Installing Windows 11
date: 2024-08-08T13:13:32.799Z
updated: 2024-08-09T13:13:32.799Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-from-watcher-to-participant-tiktok-live-integration/"><u>[New] 2024 Approved  From Watcher to Participant  TikTok Live Integration</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-make-a-thumbnail-for-your-youtube-free-easily-for-2024/"><u>[New] How to Make a Thumbnail for Your YouTube Free Easily for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-beginners-obs-techniques-for-youtube-live-streaming/"><u>[New] In 2024, Beginner's OBS Techniques for YouTube Live Streaming</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-mastering-discord-message-pinning-essentials/"><u>[New] Mastering Discord  Message Pinning Essentials</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-optimal-video-sizing-for-an-instagram-standout/"><u>[New] Optimal Video Sizing for an Instagram Standout</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-essential-manual-to-fb-video-playback-settings-for-2024/"><u>[New] The Essential Manual to FB Video Playback Settings for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-free-to-use-tools-for-transcribing-digital-conferences/"><u>[Updated] 2024 Approved  Free-to-Use Tools for Transcribing Digital Conferences</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chill-and-thrills-highlighting-olympic-snowboard-cross-winners/"><u>[Updated] Chill & Thrills  Highlighting Olympic Snowboard Cross Winners</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-enabledisable-comments-a-youtube-instructional/"><u>[Updated] In 2024, Enable/Disable Comments  A YouTube Instructional</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-how-to-expertly-archive-your-favorite-streamed-shows-hulu/"><u>[Updated] In 2024, How To Expertly Archive Your Favorite Streamed Shows (Hulu)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-minecraft-shapes-magic-creating-perfect-circles-spheres-for-2024/"><u>[Updated] Minecraft Shapes Magic  Creating Perfect Circles, Spheres for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-convenient-youtube-viewing-activate-picture-in-picture-on-iphone/"><u>2024 Approved  Convenient YouTube Viewing  Activate Picture-in-Picture on iPhone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-essential-guide-to-documenting-macs-roblox-playthroughs/"><u>2024 Approved  Essential Guide to Documenting Mac's Roblox Playthroughs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-expressive-satire-kapwings-memetic-tool/"><u>2024 Approved  Expressive Satire  Kapwing’s Memetic Tool</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-no-fuss-filming-dell-laptop-screen-recordings/"><u>2024 Approved  No-Fuss Filming  Dell Laptop Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-11-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-slash-energy-drain-by-default-desktop-window-manager/"><u>7 Ways to Slash Energy Drain by Default Desktop Window Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-look-at-windows-11-efficiency-mastering-processes-and-customizing-themes/"><u>A Deeper Look at Windows 11 Efficiency: Mastering Processes and Customizing Themes</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-layer-of-simplicity-in-windows-photos-app-deletion/"><u>A New Layer of Simplicity in Windows Photos App Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-winning-website-conversion/"><u>A Step-by-Step for Winning Website Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-personalized-typing-mastering-keybinding-w11/"><u>A Window Into Personalized Typing: Mastering Keybinding W11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-windows-based-excel-tasks-a-guide/"><u>Accelerating Windows-Based Excel Tasks: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11-volume-mixer-shortcut/"><u>Accessing Windows 11 Volume Mixer Shortcut</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-personalize-your-pcs-audio-with-windows-11-mixer/"><u>Activate and Personalize Your PC's Audio with Windows 11 Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-failure-notifications-in-w10w11-pcs/"><u>Addressing 'Device Failure' Notifications in W10/W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-error-after-device-removal/"><u>Addressing DXGI Error After Device Removal</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-screen-driver-crash-in-windows-11/"><u>Addressing Screen Driver Crash in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-system-settings-for-outdated-app-packages/"><u>Adjusting System Settings for Outdated App Packages</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-system-interactions-a-step-bystep-guide/"><u>Advanced File System Interactions: A Step-Bystep Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-honor-magic-6-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-time-honored-directx-experiences-through-dxvk/"><u>Augmenting Time-Honored DirectX Experiences Through DXVK</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-blank-screens-windows-10-and-11-troubleshooting/"><u>Banishing Blank Screens: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-restore-visual-clarity-in-winos/"><u>Best Practices to Restore Visual Clarity in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/best-ways-to-restore-default-window-options-on-system-startup/"><u>Best Ways to Restore Default Window Options on System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/bigger-capacity-but-lagging-in-little-pcs-mp60/"><u>Bigger Capacity but Lagging in Little PCs (MP60)</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://win11.techidaily.com/boltgun-performance-tips-to-resolve-on-pc-interruptions/"><u>Boltgun Performance Tips to Resolve On-PC Interruptions</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-your-online-presence-with-innovative-cookiebot-solutions/"><u>Boost Your Online Presence with Innovative Cookiebot Solutions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boosting-efficiency-with-chatgpt-a-guide-to-4-timely-management-techniques/"><u>Boosting Efficiency with ChatGPT: A Guide to 4 Timely Management Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-functions-of-winservicesexe/"><u>Breaking Down the Functions of Winservices.exe</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-poco-x6-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Poco X6</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/crimson-codec-update/"><u>Crimson Codec Update</u></a></li>
<li><a href="https://program-issues.techidaily.com/enhance-gaming-experience-by-fixing-high-network-delay-in-back-4-bloods/"><u>Enhance Gaming Experience by Fixing High Network Delay in Back 4 Bloods</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-iphone-15-pro-max-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on iPhone 15 Pro Max</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oppo-a1-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Oppo A1 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-max-to-androidios-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS Max to Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-updating-your-skills-regularly/"><u>In 2024, Updating Your Skills Regularly</u></a></li>
<li><a href="https://win11.techidaily.com/1719367447353-multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719367274054-overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721202511211-professional-grade-file-destroyer-for-windows-users-setting-up-a-convenient-auto-schedule/"><u>Professional-Grade File Destroyer for Windows Users - Setting Up a Convenient Auto-Schedule</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-samsung-galaxy-a14-4g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Samsung Galaxy A14 4G Android SIM Unlock APK</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-persistent-crashes-in-darkest-dungeon-s-gt-mkii-on-your-gaming-rig/"><u>Troubleshooting Persistent Crashes in Darkest Dungeon ˈs Gt MkII on Your Gaming Rig</u></a></li>
</ul></div>
