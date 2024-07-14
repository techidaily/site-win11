---
title: Offline Process for Extra Users in Windows 11
date: 2024-07-13T10:49:41.988Z
updated: 2024-07-14T10:49:41.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Offline Process for Extra Users in Windows 11
excerpt: This Article Describes Offline Process for Extra Users in Windows 11
keywords: Win11 Offline Mode,Extra User Guide,Windows Update Separate,Remote Login Windows,Non-Internet PC Setup,User Access Windows,Offline Computer Support
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## Offline Process for Extra Users in Windows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://graphic-issues.techidaily.com/fixed-issue-fluctuating-display-on-dell-notebook/"><u>Fixed Issue: Fluctuating Display on Dell Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80246007-in-windows-11s-update-process/"><u>Tackling Error 0X80246007 in Windows 11'S Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-fix-rpc-fails-on-your-pc/"><u>Master Plan to Fix RPC Fails on Your PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-lift-mood-and-performance-20-fitness-playlists-ranked-right/"><u>[New] Lift Mood & Performance  20 Fitness Playlists Ranked Right</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-setting-windows-backups-against-original-standards/"><u>Instructions for Setting Windows Backups Against Original Standards</u></a></li>
<li><a href="https://fix-guide.techidaily.com/nokia-xr21-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia XR21 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-seamless-experience-with-best-rated-android-devices-for-playstation-2-games/"><u>2024 Approved  Seamless Experience with Best-Rated Android Devices for PlayStation 2 Games</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-seamless-edits-await-best-freeware-on-android/"><u>2024 Approved  Seamless Edits Await  Best Freeware on Android</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-wirecast-strategies-for-successful-social-media-livestreams/"><u>[New] 2024 Approved  Wirecast Strategies for Successful Social Media Livestreams</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-how-to-remove-audio-from-mov-files-on-windowsmac/"><u>Updated 2024 Approved How to Remove Audio From MOV Files on Windows/Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategy-become-system-admin-now/"><u>Swift Strategy: Become System Admin Now</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-craft-intense-conversations-on-discord-learn-effective-message-pinning/"><u>[Updated] In 2024, Craft Intense Conversations on Discord  Learn Effective Message Pinning</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-detection-issues-with-razer-on-windows-11/"><u>Overcoming Device Detection Issues with Razer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-freezing-windows-netflix-interface/"><u>Reviving Freezing Windows Netflix Interface</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/perfect-spectrum-balancer-for-2024/"><u>Perfect Spectrum Balancer for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-capture-hearts-on-tiktok-designed-templates-for-visual-impact-for-2024/"><u>[New] Capture Hearts on TikTok  Designed Templates for Visual Impact for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-closed-caption-fixes-the-win11-way/"><u>Mastering Closed Caption Fixes: The Win11 Way</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-path-to-perfect-streams-streamlabs-plus-obs-for-mac-users/"><u>2024 Approved  The Path to Perfect Streams  Streamlabs + OBS for Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rectifying-windows-alt-key-problems-46-characters/"><u>Strategies for Rectifying Windows ALT Key Problems (46 Characters)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-tips-for-crafting-effective-igtv-titles-and-summaries-for-2024/"><u>[New] Tips for Crafting Effective IGTV Titles & Summaries for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-samsung-galaxy-f14-5g-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Samsung Galaxy F14 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-thx-audio-functionality-in-windows/"><u>Restoring Lost THX Audio Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-analysis-of-windows-11-settings/"><u>In-Depth Analysis of Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-intensive-resource-usage-managing-dropboxs-cpu-in-windows/"><u>Lowering Intensive Resource Usage: Managing Dropbox's CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-alter-windows-dashboard-imagery-effortlessly/"><u>How to Alter Windows Dashboard Imagery Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-address-error-0x800700e1-issues-on-windows-11-pcs/"><u>Essential Steps to Address Error 0X800700E1 Issues on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-defenses-adding-firewall-to-the-context-menu/"><u>Streamlining Windows 11 Defenses: Adding Firewall to the Context Menu</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-discover-the-leading-online-havens-for-free-premium-hd-video-backdrops/"><u>Updated In 2024, Discover the Leading Online Havens for Free, Premium HD Video Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/from-ios-to-desktop-seamless-sync-with-windows-os/"><u>From iOS to Desktop: Seamless Sync with Windows OS</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-blueprint-for-youtube-educational-video-success-stories-for-2024/"><u>[New] The Blueprint for YouTube Educational Video Success Stories for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-modify-twitter-clip-visuals/"><u>[Updated] Modify Twitter Clip Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/superior-pc-weather-apps-selection/"><u>Superior PC Weather Apps Selection</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-experience-beyond-reality-with-these-immersive-titles/"><u>2024 Approved  Experience Beyond Reality with These Immersive Titles</u></a></li>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/quick-reference-guide-to-mastering-mobizens-screen-recording-tech/"><u>Quick Reference Guide to Mastering Mobizen's Screen Recording Tech</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-navigating-new-media-the-marketers-top-10-ig-editing-platforms/"><u>[New] Navigating New Media  The Marketer's Top 10 IG Editing Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/max-out-your-games-on-windows-the-amd-optimization-guide/"><u>Max Out Your Games on Windows: The AMD Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-connection-problem-with-mb-services-in-win11/"><u>Overcoming the Connection Problem with MB Services in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-hidden-login-screens-in-windows-11/"><u>Eradicating Hidden Login Screens in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/improving-the-effectiveness-of-win-based-discord-queries/"><u>Improving the Effectiveness of Win-Based Discord Queries</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-intel-network-adapters-on-pcs/"><u>Step-by-Step: Setting Up Intel Network Adapters on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cortana-integration-vivetool-approach/"><u>Optimizing Cortana Integration: ViveTool Approach</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-infinix-hot-40-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Infinix Hot 40 in Minutes | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unwind-and-capture-your-games-in-peace/"><u>[New] Unwind and Capture Your Games in Peace</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revolutionizing-workouts-the-best-vr-treadmill-choices/"><u>In 2024, Revolutionizing Workouts  The Best VR Treadmill Choices</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-innovating-in-the-snapchat-space-trendsetting-ad-design-principles/"><u>[New] In 2024, Innovating in the Snapchat Space  Trendsetting Ad Design Principles</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-old-ribbon-revival-in-new-windows/"><u>Guide for Old Ribbon Revival in New Windows</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/2024-approved-how-to-make-a-triggered-meme/"><u>2024 Approved How to Make a Triggered Meme?</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-views-tabbing-in-windows-explorer/"><u>Streamlining Data Views: Tabbing in Windows Explorer</u></a></li>
</ul></div>
