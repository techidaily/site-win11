---
title: Disable Dim Display Feature via Control Panel Quick Guide
date: 2024-07-13T10:53:17.410Z
updated: 2024-07-14T10:53:17.410Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
excerpt: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
keywords: Disable Screen Low Brightness,Control Panel Light Adjustment,Reduce Display Intensity,Simple Dark Mode Turn-Off,Quick Control Panel Guide,Dim Settings Deactivation,High Contrast Display Options
thumbnail: https://thmb.techidaily.com/481d06bf1b3256f57ab62815340fcc460dfe18ec5f4531d4ca28b88dc8e90d86.jpg
---

## Disable Dim Display Feature via Control Panel Quick Guide

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://extra-lessons.techidaily.com/capture-clarity-high-end-gyroscopic-tripod-gear-for-2024/"><u>Capture Clarity  High-End Gyroscopic Tripod Gear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-reviving-your-windows-system/"><u>The Blueprint for Reviving Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-tech-titans-android-and-microsoft-pc/"><u>Uniting Two Tech Titans: Android and Microsoft PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedy-restore-registry-management-functions/"><u>Quick Remedy: Restore Registry Management Functions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top-8-dictation-software-for-windows-mac-and-online-for-2024/"><u>New Top 8 Dictation Software for Windows, Mac, and Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/relish-in-unmatched-windows-software-sweepstakes/"><u>Relish In Unmatched Windows Software Sweepstakes</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-distractions-mastering-wins-on-windows-11/"><u>Avoiding Distractions: Mastering Wins on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-iphone-11-drfone-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-craft-compelling-fb-video-covers-from-scratch/"><u>[Updated] How to Craft Compelling FB Video Covers From Scratch</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-aurora-hdr-reviews-is-aurora-hdr-a-good-choice-in-2024/"><u>[Updated] Aurora HDR Reviews  Is Aurora HDR a Good Choice , In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-distant-devices-a-guide-for-windows-users/"><u>Reconciling Distant Devices: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-high-performance-navigate-valorant-lag-reduction/"><u>Unlock High Performance: Navigate Valorant Lag Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lag-on-extended-screens/"><u>Addressing Windows Lag on Extended Screens</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/revisionfx-reelsmart-motion-blur-plugin-for-premiere-pro-for-2024/"><u>ReVisionFX ReelSmart Motion Blur Plugin For Premiere Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turning-oculus-quest-into-a-windows-based-vr-device/"><u>Turning Oculus Quest Into a Windows-Based VR Device</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-digest-your-facebook-memories/"><u>[New] In 2024, Digest Your Facebook Memories</u></a></li>
<li><a href="https://win11.techidaily.com/solving-failed-volume-shadow-copy-in-windows-os/"><u>Solving Failed Volume Shadow Copy in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-phone-link-microsofts-bluetooth-connectivity-app/"><u>Unveiling 'Phone Link': Microsoft’s Bluetooth Connectivity App</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-poco-c55-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Poco C55 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-compre-written-by-john-doe-phd-in-psychology-specializing-in-human-behavior-and-motivation-motivational-interviewing-for-2024/"><u>The Compre Written By  John Doe, PhD in Psychology, Specializing in Human Behavior and Motivation (Motivational Interviewing) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-avoiding-endless-xbox-app-cycle/"><u>Quick Cure: Avoiding Endless Xbox App Cycle</u></a></li>
<li><a href="https://extra-resources.techidaily.com/blur-free-photography-ranked-10-best-web-editing-tools-for-2024/"><u>Blur-Free Photography  Ranked 10 Best Web Editing Tools for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/solved-dead-obs-camera-for-2024/"><u>Solved  Dead OBS Camera for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-link-ups-phones-and-windows-11-synergy/"><u>Innovative Link-Ups: Phones and Windows 11 Synergy</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-detailed-protocols-for-filming-films-across-multiplatform-systems/"><u>[New] 2024 Approved  Detailed Protocols for Filming Films Across Multiplatform Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-expert-reviews-best-game-capture-apps/"><u>[Updated] In 2024, Expert Reviews  Best Game Capture Apps</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/no-cost-youtube-channels-essential-artistic-templates-for-2024/"><u>No-Cost YouTube Channels  Essential Artistic Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revive-muted-slack-on-windows-easy-steps-to-resuscitate-alerts/"><u>Revive Muted Slack on Windows: Easy Steps to Resuscitate Alerts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/exclusive-insight-free-access-to-1-6-video-clips-for-2024/"><u>Exclusive Insight  Free Access to #1-#6 Video Clips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-the-electrical-footprint-of-your-personal-windows-pc/"><u>Analyzing the Electrical Footprint of Your Personal Windows PC</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-stepping-into-a-new-digital-era-mastering-your-tiktok-handle-change-process/"><u>In 2024, Stepping Into a New Digital Era  Mastering Your TikTok Handle Change Process</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-world-google-map-powerhouse/"><u>Microsoft World, Google Map Powerhouse</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-superior-mp4-integrator-with-fb/"><u>[Updated] In 2024, Superior MP4 Integrator with FB</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-editing-excellence-the-ultimate-guide-to-top-notebooks/"><u>[New] In 2024, Editing Excellence  The Ultimate Guide to Top Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/verifying-your-version-three-ways-for-windows-11/"><u>Verifying Your Version: Three Ways for Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-understanding-the-impact-of-youtubes-creative-commons-on-videos/"><u>[Updated] Understanding the Impact of YouTube's Creative Commons on Videos</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-innovation-new-pcs-best-tools-from-msistore/"><u>Accelerated Innovation: New PC's Best Tools From MSIStore</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-increasing-onscreen-detail-in-virtual-spaces/"><u>[Updated] Increasing Onscreen Detail in Virtual Spaces</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-step-into-fame-crafting-an-authentic-tiktok-duplicate/"><u>[New] Step Into Fame  Crafting an Authentic TikTok Duplicate</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-performance-with-vm-cache-clear/"><u>Boost PC Performance with VM Cache Clear</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-touchscreen-experience-on-a-windows-11-machine/"><u>Maximize Your Touchscreen Experience on a Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-guide-to-brightening-images-post-capture/"><u>Step-by-Step Guide to Brightening Images Post-Capture</u></a></li>
<li><a href="https://youtube-help.techidaily.com/laughter-loops-scouring-the-best-chuckles-in-youtube-worlds-for-2024/"><u>Laughter Loops  Scouring the Best Chuckles in YouTube Worlds for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-utilizing-zero-cost-clocks/"><u>2024 Approved  The Ultimate Guide to Utilizing Zero-Cost Clocks</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-unlock-easy-audio-modification-with-these-7-free-online-apps/"><u>2024 Approved Unlock Easy Audio Modification with These 7 Free Online Apps</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-learn-to-activate-picture-in-picture-viewing-on-iphones-youtube-app/"><u>[Updated] Learn to Activate Picture-in-Picture Viewing on iPhone's Youtube App</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unable-to-access-your-windows-start-icon/"><u>Troubleshooting: Unable to Access Your Windows Start Icon</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-samsung-galaxy-a05-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Samsung Galaxy A05</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-things-about-youtube-tv-you-should-know/"><u>2024 Approved  Things About YouTube TV You Should Know</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-essential-topic-choosing-the-right-kids-quadcopter/"><u>[Updated] 2024 Approved  Essential Topic  Choosing the Right Kid's Quadcopter</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-update-notifier-into-the-windows-ui-context-of-win11/"><u>Integrating Update Notifier Into the Windows UI Context of Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-lava-blaze-curve-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Lava Blaze Curve 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-procedure-to-independently-update-windows/"><u>Stepwise Procedure to Independently Update Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-live-speech-to-text-whisper-desktop-tips/"><u>Mastering Live Speech-to-Text: Whisper Desktop Tips</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-overlooked-window-11-styles/"><u>In-Depth Look at Overlooked Window 11 Styles</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-picturesaveerror-in-windows-11/"><u>Resolving PictureSaveError in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-in-use-device-names-on-your-windows-system/"><u>Overcoming In-Use Device Names on Your Windows System</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-quick-tips-screen-recording-made-simple-for-mac-users/"><u>In 2024, Quick Tips  Screen Recording Made Simple for Mac Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-tecno-spark-20c-frp-by-drfone-android/"><u>How Can We Bypass Tecno Spark 20C FRP?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/stop-auto-changing-visuals-on-win11-pcs/"><u>Stop Auto-Changing Visuals on Win11 PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-xs-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone XS i Do? Get Answers here</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-underrated-realm-of-windows-monitoring-systems/"><u>Navigating the Underrated Realm of Windows Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-apple-maps-on-windows/"><u>Navigating the World: Apple Maps on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-unleash-potential-making-your-vids-go-viral/"><u>[New] 2024 Approved  Unleash Potential  Making Your Vids Go Viral</u></a></li>
</ul></div>
