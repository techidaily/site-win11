---
title: Break Free From Stagnant Windows Update Status
date: 2024-07-13T11:25:31.755Z
updated: 2024-07-14T11:25:31.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Break Free From Stagnant Windows Update Status
excerpt: This Article Describes Break Free From Stagnant Windows Update Status
keywords: Upgrade Windows Update,Clearing Update Errors,Resolve Update Failure,Fast Windows Update Fix,Stop Update Halt,Reactivate Window Update,Unlock Update Progress
thumbnail: https://thmb.techidaily.com/55d1895b35f08f3d82ecb412a2b84639eef0d00ef22964bfc70576f31a7b8bbc.jpg
---

## Break Free From Stagnant Windows Update Status

 Update errors are nothing new for Windows users. In some cases, the updates simply do not start, while in others, they start fine, but become stuck at some point.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

## 1\. Wait for the Process to Complete

 It may take longer for some Windows updates to install, so before you begin troubleshooting, ensure that the update is stuck and not in between operations.

 The best way to do this is by waiting for the process to complete on its own. You should give the update process at least 3-4 hours before proceeding with the troubleshooting methods if you can. Some users left their computers overnight for the updates to be installed.

 We understand that waiting this long might not be possible for everyone and if it does not suit you as well, go ahead with the methods below. It is also important to note that before proceeding with the methods in this guide that require you to access your system, you will need to break the update loop that is causing the issue. To do this, reboot your PC to perform the steps listed.

## 2\. Remove Any USB Peripherals and Restart Your PC

 Start by removing any USB peripherals that may be connected to your PC. When you have extra external devices connected, your PC thinks of it as a change in the default hardware settings, leading to issues like the one at hand.

 Once you have removed all peripherals, wait for a few minutes and see if it makes any difference. If not, you can try force restarting the PC. However, this method involves removing the battery from your laptop, so we recommend you only proceed if you have some experience doing so.

 Here is how you can force restart your PC:

1. Press and hold the power button of your PC to shut it down.
2. Once it shuts down, remove the power supply and battery.
3. Then, wait for a few minutes before inserting it back.
4. Now, boot your PC and see if the issue is resolved.

## 3\. Restart the Windows Update Service

 The Windows Update service handles the download, installation, and removal of updates on your system. If this service is disabled or not working as it is supposed to, you are likely to encounter issues while updating your operating system and its applications.

 If removing the external peripherals did not help, then you can try restarting the Windows Update service.

 Here is how you can make sure that the update service is running properly:

1. Press **Win** \+ **R** to open Run.
2. Type "services.msc" in Run and press **Enter**.
3. In the following window, look for the Windows Update service and right-click on it.
4. Choose **Properties** from the context menu.  
![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, click on the **Stop** button.  
![Stop button in Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/win10-windows-update-properties-stop.jpg)
6. Wait for a few seconds before hitting the **Start** button again.
7. Expand the dropdown for Startup type and choose **Automatic** from the list.  
![Startup type of service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-automatic-startup-type.jpg)
8. Click **Apply** \> **OK** to save the changes.

## 4\. Scan for Viruses

 Your operating system might also be infected with a virus or corruption error that is preventing you from installing the latest updates.

 To check if this is the case, try running a system scan using the security program you have installed on your PC. If you do not have a third-party security program, you can [run built-in troubleshooting utilities like SFC, DISM, and CHKDSK](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) via Command Prompt.

 However, if you are unable to use the basic Windows features and applications installed, then you must first [boot into Repair Mode](https://www.makeuseof.com/fix-windows-11-stuck-preparing-windows/). Once you are in the Repair Mode, head over to **Troubleshoot** \> **Advanced options**. Then, choose **Command Prompt** from the list of options and run the scans.

![Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-command-prompt.jpg)

 If these utilities find any issues, they will attempt to resolve them without requiring your input. After the scans, check if the issue is resolved.

## 5\. Run the Windows Update Troubleshooter

 Another troubleshooting method that has helped users fix the issue is running the Windows Update troubleshooter. This is a built-in utility that is specifically designed by Microsoft to fix issues regarding Windows updates.

 Here is how you can run it:

1. Press **Win** \+ **I** to open Windows Settings.
2. Choose **Troubleshoot** from the left pane and click on **Other troubleshooters** on the right side of the window.  
![other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/other-troubleshooters-1.jpg)
3. In the following window, look for Windows Update troubleshooter and click on the **Run** button associated with it.  
![Run button for Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-troubleshooter.jpg)
4. The troubleshooter will now begin scanning the system for potential errors. If it finds issues, it will recommend fixes. In that case, click on **Apply this fix**.
5. If not, click **Close the troubleshooter** and move to the next method below.

## 6\. Boot Into Safe Mode

 Safe Mode is a Windows mode that launches Windows with only the basic drivers and programs. This troubleshooting mode helps users determine if a background process is causing issues within the system.

 In this method, we will first boot into Safe Mode using the Repair Mode and then restart the PC normally. Hopefully, this will fix the problem at hand.

 Here is what you need to do:

1. Boot Windows and during the process, press the F11 key repeatedly till Windows displays the Advanced Startup screen.
2. Head over to navigate to **Troubleshoot** \> **Advanced options** \> **Startup settings**.  
![Startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings.jpg)
3. Click on the **Restart** button in the following window.  
![Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings-restart.jpg)
4. Hit the F5 key on the keyboard to proceed. This will launch the Safe Mode successfully.
5. In Safe Mode, restart your PC the normal way (**Start menu** \> **Sign out** \> **Restart**).  
![Restart Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-safe-mode-restart.jpg)

 Upon reboot, the issue should no longer appear. You can now check if the updates are successfully installed. If not, you can try any one of [the different methods to update Windows manually](https://www.makeuseof.com/update-windows-manually/).

## Resume the Update Process on Windows 11

 We hope that at least one of the methods listed above was able to help you. Nevertheless, if you have come this far without finding a solution, you should consider performing a complete system reset since the issue is likely caused by a component that conventional troubleshooting methods cannot fix.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/blending-elegance-with-utility-the-asus-vivobook-s-15-edition/"><u>Blending Elegance with Utility: The ASUS Vivobook S 15 Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-in-depth-look-at-vsdc-plus-top-competitors/"><u>[New] In 2024, In-Depth Look at VSDC, Plus Top Competitors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-performance-in-plain-sight-a-guide-to-windows-11s-in-place-upgrade/"><u>Boosting Performance in Plain Sight: A Guide to Windows 11'S In-Place Upgrade</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-in-this-article-you-will-find-8-best-animation-maker-they-are-suitable-for-various-users-check-it-out/"><u>New 2024 Approved In This Article, You Will Find 8 Best Animation Maker. They Are Suitable for Various Users. Check It Out</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-defaults-20-ways-to-personalize-windows-11/"><u>Beyond Defaults: 20 Ways to Personalize Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-evolution-reimagining-control-in-a-windows-world/"><u>Administrative Evolution: Reimagining Control in a Windows World</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-notepad-system-disruptions/"><u>Avoiding Windows Notepad System Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-nikon-d500-a-revolution-in-4k-uhd-photography/"><u>[New] Nikon D500  A Revolution in 4K UHD Photography</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-picks-ultimate-portable-devices-for-cutting-edge-editing/"><u>2024 Approved  Top Picks  Ultimate Portable Devices for Cutting-Edge Editing</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-how-to-disable-the-pesky-epic-games-hub/"><u>Break Free: How to Disable the Pesky Epic Games Hub</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-limits-why-16gb-ram-is-key-for-modern-pcs/"><u>Beyond Limits: Why 16GB RAM Is Key for Modern PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win11-crucial-complimentary-software-selection/"><u>Boosting Win11: Crucial, Complimentary Software Selection</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-ultimate-guide-to-choosing-windows-friendly-speech-recognition-apps-for-2024/"><u>The Ultimate Guide to Choosing Windows-Friendly Speech Recognition Apps for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-12-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi 12 Phone without Google Account?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snap-your-way-unique-discover-over-120-private-story-creation-tips-and-tricks/"><u>[New] Snap Your Way Unique  Discover over 120 Private Story Creation Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/banish-flickering-screens-a-windows-11-guide/"><u>Banish Flickering Screens: A Windows 11 Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/improving-viewer-experience-with-clearer-web-content/"><u>Improving Viewer Experience with Clearer Web Content</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-apple-iphone-14-plus-backup-password-heres-what-to-do-by-drfone-ios/"><u>Forgot Apple iPhone 14 Plus Backup Password? Heres What to Do</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/battle-the-bake-off-effective-tactics-to-reduce-gaming-laptops-temperature/"><u>Battle the Bake-Off: Effective Tactics to Reduce Gaming Laptop’s Temperature</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-utorrents-non-functionality-on-pc-systems/"><u>Addressing uTorrent's Non-Functionality on PC Systems</u></a></li>
<li><a href="https://win11.techidaily.com/action-plan-if-powershell-isnt-displayed-by-windows/"><u>Action Plan if PowerShell Isn’t Displayed by Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-exclusive-access-to-the-ultimate-no-cost-design-suite-for-2024/"><u>[Updated] Exclusive Access to the Ultimate No-Cost Design Suite for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-earn-on-the-go-snapchats-money-tips/"><u>In 2024, Earn on the Go  Snapchat's Money Tips</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-self-shutting-windows-11-units/"><u>Addressing Self-Shutting Windows 11 Units</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/create-epic-trailers-best-software-for-mac-and-pc-2023-review-for-2024/"><u>Create Epic Trailers Best Software for Mac and PC (2023 Review) for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/beginners-overview-of-animation-trends/"><u>Beginner's Overview of Animation Trends</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-message-impact-with-emoji-15-on-win11/"><u>Boost Your Message Impact with Emoji 15 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-win-11-context-menu-to-omit-additional-entry/"><u>Adjusting Win 11 Context Menu to Omit Additional Entry</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-love-in-action-top-9-premium-wedding-films-on-youtube-and-vimeo/"><u>[Updated] Love in Action  Top 9 Premium Wedding Films on YouTube and Vimeo</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-from-apple-iphone-12-by-drfone-ios/"><u>How To Remove the Two Factor Authentication From Apple iPhone 12</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wake-up-alerts-win-1011-full-charge-ding/"><u>Boosting Wake-Up Alerts: Win 10/11 FULL CHARGE DING</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-application-launch-descriptors/"><u>Breaking Down Application Launch Descriptors</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-guide-to-enabling-high-dynamic-range-auto-hdr-on-windows-11/"><u>[Updated] Step-by-Step Guide to Enabling High Dynamic Range (Auto HDR) on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-guide-for-older-tech/"><u>AtlasOS Resurgence Guide for Older Tech</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-use-your-recordings-for-a-seamless-live-experience-on-fb-for-2024/"><u>[Updated] How to Use Your Recordings for a Seamless Live Experience on FB for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-configuration-backup-by-nvidia-cp/"><u>Addressing Missing Configuration Backup by Nvidia CP</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-script-crafting-basics/"><u>2024 Approved  Script Crafting Basics</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-get-spoken-up-on-discord-using-tts/"><u>[Updated] 2024 Approved  Get Spoken Up on Discord Using TTS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-foster-conversations-via-thoughtful-instagram-quiz-style-lives/"><u>[New] Foster Conversations via Thoughtful Instagram Quiz-Style Lives</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-add-software-icons-to-windows-desktop/"><u>Boost Productivity: Add Software Icons to Windows Desktop</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-top-10-screenrecord-tips-and-tricks-on-a-laptop/"><u>In 2024, Top 10 ScreenRecord Tips and Tricks on a Laptop</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>