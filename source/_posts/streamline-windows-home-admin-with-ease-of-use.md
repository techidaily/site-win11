---
title: Streamline Windows Home Admin with Ease of Use
date: 2024-07-13T11:00:42.321Z
updated: 2024-07-14T11:00:42.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Windows Home Admin with Ease of Use
excerpt: This Article Describes Streamline Windows Home Admin with Ease of Use
keywords: Easy Window Administration,Simplified Windows Control,Streamlined PC Management,User-Friendly OS Tools,Convenient Window Settings,Quick Windows Configurations,Optimized Home System Access
thumbnail: https://thmb.techidaily.com/d72c9b0ad235ae2e33438a2833486adc17771826c6a96da1aa4105529dabc652.jpg
---

## Streamline Windows Home Admin with Ease of Use

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
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-essential-process-of-adding-sound-to-mkv-updated-videographies-for-2024/"><u>New The Essential Process of Adding Sound to MKV-Updated Videographies for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-word-by-digital-signature-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign Word by digital signature</u></a></li>
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/compelling-list-of-premium-free-phone-video-chat-applications-iosandroid/"><u>Compelling List of Premium-Free Phone Video Chat Applications (iOS/Android)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-revamp-chromebooks-soundscape-with-our-picks-for-web-extensions/"><u>[Updated] Revamp Chromebook's Soundscape with Our Picks for Web Extensions</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mastering-economy-in-gaming-top-business-sim-titles/"><u>[New] Mastering Economy in Gaming  Top Business Sim Titles</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-art-of-timely-and-effective-google-meet-planning/"><u>The Art of Timely and Effective Google Meet Planning</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-run-as-admin-errors-a-guide/"><u>Overcoming Run as Admin Errors: A Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-youtube-revenue-predictor-tools/"><u>[Updated] In 2024, Free YouTube Revenue Predictor Tools</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-connect-your-device-bluetooth-error-in-windows-11/"><u>Troubleshooting Connect Your Device Bluetooth Error in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-your-inner-comedian-9gag-meme-creation-guide/"><u>[Updated] Unleash Your Inner Comedian  9GAG Meme Creation Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-12-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 12 With 7 Methods</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-dynamic-visual-snapshot-providers/"><u>[New] In 2024, Dynamic Visual Snapshot Providers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-tecno-pova-5-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Tecno Pova 5 Without PUK Codes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-streamlining-your-profile-alter-name-in-google-meet-for-2024/"><u>[New] Streamlining Your Profile  Alter Name in Google Meet for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-streamline-screen-recording-processes-during-facetime-for-2024/"><u>[New] Streamline Screen-Recording Processes During FaceTime for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-weaving-wonders-a-tiktok-fabric-fundamentals-series/"><u>[New] 2024 Approved  Weaving Wonders  A TikTok Fabric Fundamentals Series</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-transforming-your-mobile-device-a-comprehensive-tone-customization-strategy/"><u>[New] In 2024, Transforming Your Mobile Device  A Comprehensive Tone Customization Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-joy-essential-list-of-free-media-players-for-windows/"><u>Unleash Joy: Essential List of Free Media Players for Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-worlds-best-5-streaming-videography-tools/"><u>[New] 2024 Approved  World's Best 5 Streaming Videography Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-building-successful-youtube-collaborations-step-by-step/"><u>[New] 2024 Approved  Building Successful YouTube Collaborations Step by Step</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Poco X6? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-the-art-of-choosing-high-impact-youtube-channels/"><u>[Updated] Unveiling the Art of Choosing High-Impact Youtube Channels</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-vloggers-selection-premium-camera-lenses-compared/"><u>[New] The Vlogger's Selection  Premium Camera Lenses Compared</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-master-video-editing-on-mac-with-mkvtoolnix-a-step-by-step-guide-2023/"><u>New In 2024, Master Video Editing on Mac with MKVtoolnix A Step-by-Step Guide 2023</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-access-essential-windows-10-tips/"><u>[Updated] Quick Access  Essential Windows 10 Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-essential-list-of-gratuitous-online-photo-enhancement-suites/"><u>[New] Essential List of Gratuitous Online Photo Enhancement Suites</u></a></li>
<li><a href="https://win11.techidaily.com/archive-your-cortana-trails-on-a-pc-operating-system/"><u>Archive Your Cortana Trails on a PC Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/interfacing-with-the-core-of-windows-print-system/"><u>Interfacing with the Core of Windows Print System</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-4-things-you-should-know-about-pinterest-gif-for-2024/"><u>New 4 Things You Should Know About Pinterest GIF for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-steam-friends-list-step-by-step-guide-windows-11/"><u>Reconnect Steam Friends List: Step-by-Step Guide, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-downfalls-of-modern-standby-in-windows-os/"><u>Dissecting the Downfalls of Modern Standby in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-fix-restoring-functionality-to-windows-charmap/"><u>Comprehensive Fix: Restoring Functionality to Windows CharMap</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comprehensive-guide-to-photo-to-video-conversion-via-pixiz/"><u>2024 Approved  Comprehensive Guide to Photo-to-Video Conversion via Pixiz</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-get-ultimate-premium-quality-discord-icons-at-no-charge/"><u>In 2024, Get Ultimate, Premium-Quality Discord Icons at NO Charge</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-affordable-cameras-for-effective-vloggers/"><u>In 2024, Affordable Cameras for Effective Vloggers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-ethernet-connection-fixes/"><u>Navigating Through Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-fall-guys-connection-errors-on-windows/"><u>How to Fix Fall Guys Connection Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-transformation-of-heic-files-into-jpeg/"><u>Uncomplicated Transformation of HEIC Files Into JPEG</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://win11.techidaily.com/altering-output-displays-in-window-based-os/"><u>Altering Output Displays in Window-Based OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-top-8-virtual-reality-vr-gaming-accessories/"><u>[Updated] Top 8 Virtual Reality (VR) Gaming Accessories</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-command-prompt-for-ultimate-control/"><u>Configuring Command Prompt for Ultimate Control</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-transition-from-stuck-in-windows-1011-s-mode/"><u>Tactics to Transition From Stuck in Windows 10/11 S Mode</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-infinix-hot-30-5g-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after Infinix Hot 30 5G has been deleted.</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-soundtracked-snapshots-instagram-videos-with-a-musical-theme/"><u>2024 Approved  Soundtracked Snapshots  Instagram Videos with a Musical Theme</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-spellbinding-spectacle-youtubes-finest-magic-tricks-edited/"><u>2024 Approved  Spellbinding Spectacle  YouTube's Finest Magic Tricks Edited</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-se-2020-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone SE (2020) without Data Loss? | Dr.fone</u></a></li>
</ul></div>
