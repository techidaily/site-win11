---
title: "Admin Controls Simplified: Managing Users & Groups in Homes"
date: 2024-07-13T09:58:08.734Z
updated: 2024-07-14T09:58:08.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Admin Controls Simplified: Managing Users & Groups in Homes"
excerpt: "This Article Describes Admin Controls Simplified: Managing Users & Groups in Homes"
keywords: User Management at Home,Group Control Basics,Simplify Admin Access,Homesite User Guide,Easy Group Settings,Manage Users Efficiently,Simplified Admin Tools
thumbnail: https://thmb.techidaily.com/1382e80fe89cdc85e3f86df652866f8b806d3041c2bfdfcea85ed48c584b9f54.JPG
---

## Admin Controls Simplified: Managing Users & Groups in Homes

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-watch-dvds-on-windows-10-top-10-free-player-software/"><u>2024 Approved Watch DVDs on Windows 10 Top 10 Free Player Software</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-factory-unlock-your-telstra-iphone-8-plus-by-drfone-ios/"><u>In 2024, How To Factory Unlock Your Telstra iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-network-access-for-chrome-amidst-windows-security-barriers/"><u>Enabling Network Access for Chrome Amidst Windows Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-unwanted-files-from-your-c-drive/"><u>Banishing Unwanted Files From Your C: Drive</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-active-recorder-assessment-industry-standards-met/"><u>[Updated] In 2024, Active Recorder Assessment  Industry Standards Met?</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-and-correcting-the-msvcr110dll-deficit/"><u>Explaining & Correcting the msvcr110.dll Deficit</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-7-best-mp4-editors-for-mac-edit-mp4-in-mac/"><u>In 2024, 7 Best MP4 Editors for Mac Edit MP4 in Mac</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-display-order-easy-windows-method/"><u>Reversing Display Order: Easy Windows Method</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-update-problem-with-error-0xca00a009/"><u>Mitigating Update Problem with Error 0xCA00A009</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/concealed-video-streaming-background-youtube-watch-for-2024/"><u>Concealed Video Streaming  Background YouTube Watch for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-terminal-mastering-focus-mode-transitions/"><u>Navigating Windows Terminal: Mastering Focus Mode Transitions</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-essence-of-omegle-a-thorough-investigation-of-its-operations-and-user-protection-for-2024/"><u>Updated The Essence of Omegle A Thorough Investigation of Its Operations and User Protection for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-transformation-of-user-interaction-understanding-the-update/"><u>[New] In 2024, The Transformation of User Interaction  Understanding the Update</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-14-photo-video-montage-creators-with-music/"><u>Top 14 Photo Video Montage Creators with Music</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-samsung-galaxy-a14-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-lens-leaders-showcase-unveiling-the-best-6-4k-dslrs/"><u>[Updated] Lens Leaders Showcase  Unveiling the Best 6 4K DSLRs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/behind-the-screens-the-leading-bgm-audio-selections/"><u>Behind the Screens The Leading BGM Audio Selections</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-cutting-edge-strategies-for-flawless-custom-shorts-coverage/"><u>In 2024, Cutting-Edge Strategies for Flawless Custom Shorts Coverage</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-audio-purity-unleashed-advanced-noise-reduction-techniques-using-wondershare-filmora/"><u>New Audio Purity Unleashed Advanced Noise Reduction Techniques Using Wondershare Filmora</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/pinpointing-your-individual-playlist-hub-on-youtube-for-2024/"><u>Pinpointing Your Individual Playlist Hub on YouTube for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/king-the-impact-of-youtubes-shorts-programme/"><u>Unpacking the Impact of YouTube's Shorts Programme</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-crashes/"><u>Navigating Through Windows 10/11'S Recycle Bin Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-quality-over-novelties/"><u>Enhancing Windows 11: Quality over Novelties</u></a></li>
<li><a href="https://win11.techidaily.com/removing-default-homescreen-from-windows-11-setup/"><u>Removing Default Homescreen From Windows 11 Setup</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-easy-technique-storing-tweet-videos-and-images-on-cellphone/"><u>2024 Approved  Easy Technique  Storing Tweet Videos and Images on Cellphone</u></a></li>
<li><a href="https://win11.techidaily.com/removing-updater-code-0x8019-issue-on-xp/"><u>Removing Updater Code 0X8019 Issue on XP</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/discover-comedy-tear-fusion-in-these-highest-rated-memetic-accounts-for-2024/"><u>Discover Comedy-Tear Fusion in These Highest Rated Memetic Accounts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-diagnostics-timely-application-of-windows-ping/"><u>Navigating Network Diagnostics: Timely Application of Windows Ping</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-recordings-win-5-budget-friendly-filters/"><u>Enhance PC Recordings: Win 5 Budget-Friendly Filters</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-1011-installing-a-unique-lock-pattern/"><u>Guide to Windows 10/11: Installing a Unique Lock Pattern</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-behind-the-scenes-top-tactics-for-consistent-vlogging/"><u>In 2024, Behind the Scenes  Top Tactics for Consistent Vlogging</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-dism-failure-0x800f082f/"><u>Resolving Windows' DISM Failure 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/defeating-inaccessible-program-uninstall-in-microsofts-latest-os/"><u>Defeating Inaccessible Program Uninstall in Microsoft's Latest OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-exclusive-list-of-top-web-based-sound-capturers-2023/"><u>[Updated] In 2024, Exclusive List of Top Web-Based Sound Capturers 2023</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-surface-laptop-go-3-processor-boost-and-critique/"><u>Analyzing Surface Laptop Go 3: Processor Boost and Critique</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pc-what-to-do-when-windows-11-loses-a-tab/"><u>Enhance Your PC: What to Do When Windows 11 Loses a Tab?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-behind-the-scenes-with-viral-image-memes-and-stories/"><u>In 2024, Behind the Scenes with Viral Image Memes & Stories</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unleashing-creativity-in-youtube-banner-and-thumbnail-design/"><u>[New] Unleashing Creativity in YouTube Banner & Thumbnail Design</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-android-and-windows-gameplay-unification-with-google-play/"><u>Bridge Android and Windows: Gameplay Unification with Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/does-your-pc-tick-all-boxes-for-windows-11-upgrade/"><u>Does Your PC Tick All Boxes for Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-seamless-warhammer-gaming-on-windows-stop-stuttering/"><u>Achieving Seamless Warhammer Gaming on Windows: Stop Stuttering</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-pc-quick-steps-into-windows-11s-safe-mode/"><u>Jumpstart Your PC: Quick Steps Into Windows 11'S Safe Mode</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-harmony-in-transition-crafting-crossfade-effects/"><u>[Updated] Harmony in Transition  Crafting Crossfade Effects</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-screens-enhanced-brightness-controls/"><u>Mastering Windows Screens: Enhanced Brightness Controls</u></a></li>
<li><a href="https://win11.techidaily.com/combat-winerror-0x800f0831-with-ease/"><u>Combat WinError 0X800F0831 with Ease</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-art-of-video-marketing-11-tips-to-skyrocket-fb-traffic/"><u>2024 Approved  The Art of Video Marketing  11 Tips to Skyrocket FB Traffic</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-updater-error-0x80246007-in-windows-versions-1011/"><u>Fixing Updater Error 0X80246007 in Windows Versions 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-motorola-moto-g24-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Motorola Moto G24</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-ways-to-track-apple-iphone-8-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>3 Ways to Track Apple iPhone 8 Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-delete-dialogues-for-secure-computing/"><u>Controlling Delete Dialogues for Secure Computing</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-run-the-sfc-tool-successfully/"><u>Essential Tips to Run the SFC Tool Successfully</u></a></li>
</ul></div>
