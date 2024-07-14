---
title: Restoring Missing Thermal Policy in Windows Environment
date: 2024-07-13T09:49:32.121Z
updated: 2024-07-14T09:49:32.121Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Missing Thermal Policy in Windows Environment
excerpt: This Article Describes Restoring Missing Thermal Policy in Windows Environment
keywords: Thermal Policy Restore,Windows Heat Settings,Policy Policy Revival,Thermal Management Fix,Window Temperature Control,Policies Recovery Guide,System Temp Regulation
thumbnail: https://thmb.techidaily.com/29d02750ad0cb057d82cf1dca19da27d5429074e0ee73dae3abc4f97673bc3bc.jpg
---

## Restoring Missing Thermal Policy in Windows Environment

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://win11.techidaily.com/accelerate-typing-mastering-windows-powertoys/"><u>Accelerate Typing: Mastering Windows PowerToys</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-building-engagement-the-role-of-youtube-shorts-template-design/"><u>[Updated] Building Engagement  The Role of YouTube Shorts Template Design</u></a></li>
<li><a href="https://win11.techidaily.com/1719356384376-mastery-over-mute-shift-key-trouble/"><u>Mastery Over Mute Shift Key Trouble</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-hassle-free-techniques-for-igtv-on-stories/"><u>[Updated] Hassle-Free Techniques for IGTV on Stories</u></a></li>
<li><a href="https://win11.techidaily.com/1719359386759-overcoming-dim-windows-11-screens-tips-inside/"><u>Overcoming Dim Windows 11 Screens - Tips Inside</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-top-11-best-instagram-photo-editors/"><u>[New] Top 11 Best Instagram Photo Editors</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-the-cant-switch-out-of-s-mode-issue-in-windows-11-or-10/"><u>9 Ways to Fix the “Can’t Switch Out of S Mode” Issue in Windows 11 or 10</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-6-plus-without-a-passcode-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone 6 Plus Without a Passcode</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-fixes-for-troublesome-email-notifications-in-windows/"><u>9 Essential Fixes for Troublesome Email Notifications in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-convert-video-voice-to-text-online-for-free-fast-and-easy-ways/"><u>Updated In 2024, Convert Video Voice to Text Online for Free Fast and Easy Ways</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-focus-on-voice-not-background-with-skype/"><u>In 2024, Focus on Voice, Not Background with Skype</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win-utorrent-downloads-tips-and-tricks/"><u>Accelerate Win uTorrent Downloads: Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-0x800704b3-error-in-windows-11/"><u>A Quick Fix for 0X800704B3 Error in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-enhance-online-presence-master-facebook-video-autoplay/"><u>[New] 2024 Approved  Enhance Online Presence  Master Facebook Video Autoplay</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-tiktok-video-amplification/"><u>[New] The Ultimate Guide to TikTok Video Amplification</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
<li><a href="https://screen-recording.techidaily.com/economical-android-communication-tools-list/"><u>Economical Android Communication Tools List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-proven-strategies-to-amplify-zoomed-participants-in-google-meet/"><u>[Updated] Proven Strategies to Amplify Zoomed Participants in Google Meet</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/behind-the-scenes-insights-deciphering-what-unlisted-means-for-youtube-users/"><u>Behind-the-Scenes Insights  Deciphering What 'Unlisted' Means for YouTube Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-lava-agni-2-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Lava Agni 2 5G without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-telnet-in-windows-11-and-11/"><u>3 Ways to Enable Telnet in Windows 11 & 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-crafting-personalized-instagram-story-sections-for-2024/"><u>[New] Crafting Personalized Instagram Story Sections for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-elevate-your-shots-vloggers-guide-to-the-9-finest-camera-gadgets/"><u>[Updated] 2024 Approved  Elevate Your Shots  Vlogger's Guide to the 9 Finest Camera Gadgets</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/titans-of-tutorials-top-youtuber-earnings-for-2024/"><u>Titans of Tutorials  Top Youtuber Earnings for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-the-insiders-guide-to-creating-impressive-slow-motion-content-on-tiktok/"><u>[Updated] In 2024, The Insider's Guide to Creating Impressive Slow Motion Content on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-your-computer-writes-mouse-secrets-of-windows-11/"><u>A Deeper Dive Into Your Computer' Writes: Mouse Secrets of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-peak-auto-clickers-hotkeys-plus-high-performance/"><u>5 Peak Auto Clickers: Hotkeys + High Performance</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-unlocking-creative-power-in-logic-pro-x-with-these-top-8-plugins-for-2024/"><u>Updated Unlocking Creative Power in Logic Pro X with These Top 8 Plugins for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-triumph-in-football-fantasyland-at-no-cost/"><u>A Guide to Triumph in Football Fantasyland at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/a-tutorial-on-windows-media-player-launching/"><u>A Tutorial on Windows Media Player Launching</u></a></li>
<li><a href="https://win11.techidaily.com/1719349600813-troubleshoot-unlock-handbrake-on-widows/"><u>Troubleshoot: Unlock HandBrake on Widows!</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-realme-narzo-n53-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Realme Narzo N53 and Browser | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-personal-vlogs-that-resonate-deeply-with-viewers/"><u>[Updated] Personal Vlogs That Resonate Deeply With Viewers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-global-stage-excellent-live-soundscape/"><u>2024 Approved  Global Stage  Excellent Live Soundscape</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-streamlined-techniques-for-downloading-vimeo-files-for-2024/"><u>[Updated] Streamlined Techniques for Downloading Vimeo Files for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/1719362972502-enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today!</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hidden-whatsapp-gems-top-tricks-to-enhance-your-messaging-experience-for-2024/"><u>Hidden WhatsApp Gems  Top Tricks to Enhance Your Messaging Experience for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-seamless-online-media-dissemination-on-vimeo-for-2024/"><u>[New] Seamless Online Media Dissemination on Vimeo for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-for-optimizing-task-management-in-administrative-mode-on-windows-11/"><u>A Step-by-Step Guide for Optimizing Task Management in Administrative Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-mend-windows-1011-discord-errors/"><u>A Step-by-Step Approach to Mend Windows 10/11 Discord Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-to-top-windows-compatible-file-sharing-software/"><u>A Compreayer's Guide to Top Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/5-essential-time-saving-pc-apps-for-dynamic-desktop-screensavers/"><u>5 Essential Time-Saving PC Apps for Dynamic Desktop Screensavers</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-you-cant-enable-the-windows-firewall/"><u>4 Fixes to Try if You Can’t Enable the Windows Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/6-polarizing-windows-features-that-are-gone-for-good/"><u>6 Polarizing Windows Features That Are Gone for Good</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-entering-your-folder-of-apps-in-windows-11/"><u>A Step-by-Step Guide to Entering Your Folder of Apps in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-capture-and-save-windows-screen-shots-made-simple/"><u>[New] 2024 Approved  Capture and Save  Windows Screen Shots Made Simple</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-unveiling-effective-techniques-for-setting-up-and-gauging-fbs-instream-ads/"><u>[Updated] Unveiling Effective Techniques for Setting Up and Gauging FB's Instream Ads</u></a></li>
<li><a href="https://win11.techidaily.com/5-strategies-for-switching-out-of-unwanted-night-mode/"><u>5 Strategies for Switching Out of Unwanted Night Mode</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-missing-video-functionality-in-sony-a6400/"><u>2024 Approved  Missing Video Functionality in Sony A6400</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-overview-using-nearby-share-effectively/"><u>A Comprehensive Overview: Using Nearby Share Effectively</u></a></li>
</ul></div>
