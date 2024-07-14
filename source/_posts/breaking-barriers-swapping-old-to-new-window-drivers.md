---
title: "Breaking Barriers: Swapping Old to New Window Drivers"
date: 2024-07-13T11:30:03.894Z
updated: 2024-07-14T11:30:03.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breaking Barriers: Swapping Old to New Window Drivers"
excerpt: "This Article Describes Breaking Barriers: Swapping Old to New Window Drivers"
keywords: Driver Upgrade Guide,Windows Driver Update,Novelty Window Drivers,Driver Renewal Tips,Overhaul Driver Process,Old to New Driver Switch,Modernize System Drivers
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
---

## Breaking Barriers: Swapping Old to New Window Drivers

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

## How to Check Your Installed Drivers

 You will have drivers on your system, even if you didn't manually install them, but you may not know what they are or what version you have. There are various ways to check this.

 When you come across a date associated with a driver, this usually refers to when the driver was published, not necessarily when you installed it.

### 1\. Use Device Manager

 A user-friendly way to check drivers is through Device Manager. There are plenty of [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/); a simple method is to press **Windows key + X** and select **Device Manager**.

 This shows all your devices split by category (like **Disk drives**, **Monitors**, and **Printers**). To see a device's driver details:

1. **Double-click** a category to expand it and see the devices within.
2. **Right-click** a device and click **Properties**.
3. Click the **Driver** tab.
4. If you need more information and want to view the installed driver files, click **Driver Details**.

![device manager driver details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/device-manager-driver-details.jpg)

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

### 2\. Use the Manufacturer's Website

 You can also download drivers yourself through the hardware manufacturer's website. To ensure the driver is safe and the latest version, don't use any unofficial websites.

 Use one of the methods provided earlier to find out what drivers you have and which company produces them. Head to the manufacturer's website and look for the driver section (perhaps under "Downloads" or "Support"). Some providers, like AMD and NVIDIA, have tools that scan your system and detect what driver you need if you're unsure. Some also have proprietary software that keeps the driver updated and provides other functionality.

 Most drivers come as executables that update what's necessary when run. If not, use Device Manager to install them:

1. Press **Windows key + X** and select **Device Manager**.
2. **Double-click** a category to expand it and see the devices within.
3. **Right-click** a device and click **Update driver**.
4. Click **Browse my computer for drivers**.
5. Click **Browse** and navigate to the folder where you downloaded the driver.
6. Click **OK**.
7. Click **Next** and follow the wizard to completion.

![windows 10 browse for drivers on your computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-10-browse-for-drivers-on-your-computer.jpg)

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/avoiding-unwanted-chrome-notifications-windows/"><u>Avoiding Unwanted Chrome Notifications (Windows)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-diverse-vlogging-content-suggestions/"><u>[Updated] 2024 Approved  Diverse Vlogging Content Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-explore-4-innovative-microsoft-paint-additions/"><u>Breaking Boundaries: Explore 4 Innovative Microsoft Paint Additions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mini-drone-winners-market-analysis-guide/"><u>2024 Approved  Mini Drone Winners  Market Analysis Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-essential-iphoneside-by-side-guide-for-fb-sharing/"><u>[New] The Essential iPhoneside by Side Guide for FB Sharing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-who-skipped-my-story-unfollowers-scan/"><u>2024 Approved  Who Skipped My Story? Unfollowers Scan</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-masterclass-setting-up-countdowns-in-obs-studio/"><u>[New] 2024 Approved  Masterclass  Setting Up Countdowns in OBS Studio</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-social-media-to-monetary-success-the-roadmap-for-instagram-sponsorship/"><u>[Updated] In 2024, From Social Media to Monetary Success  The Roadmap for Instagram Sponsorship</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-pc-how-to-turn-on-hyper-v-in-win11/"><u>Boosting Your PC: How To Turn On Hyper-V in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-pinned-items-visibility-on-w11-start/"><u>Boosting Pinned Items Visibility on W11 Start</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-oppo-k11-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Oppo K11 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-vivo-y28-5g-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Vivo Y28 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unravel-time-the-art-of-snapchat-video-reverse/"><u>[Updated] Unravel Time  The Art of Snapchat Video Reverse</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-connectivity-hurdles-clearing-up-vague-instructions/"><u>Breaking Down Wi-Fi Connectivity Hurdles: Clearing Up Vague Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/boost-note-visibility-for-effective-productivity/"><u>Boost Note Visibility for Effective Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-with-dev-drive-on-the-latest-windows-11-release/"><u>Boosting Efficiency with Dev Drive on the Latest Windows 11 Release</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-top-10-tips-to-upgrade-your-obs-mobile-broadcasting/"><u>[Updated] Top 10 Tips to Upgrade Your OBS Mobile Broadcasting</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/freeze-frame-fantasy-expert-techniques-for-gameplay-preservation-pc-for-2024/"><u>Freeze Frame Fantasy  Expert Techniques for Gameplay Preservation (PC) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bound-windows-login-with-ms-account-essentials/"><u>Bound Windows Login with MS Account Essentials</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-key-steps-to-successfully-infiltrating-your-dream-discord-server/"><u>[Updated] Key Steps to Successfully Infiltrating Your Dream Discord Server</u></a></li>
<li><a href="https://extra-tips.techidaily.com/affinity-photos-power-crafting-focus-by-clearing-exteriors/"><u>Affinity Photo's Power  Crafting Focus by Clearing Exteriors</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-visual-keyboard-assistant/"><u>Accessing Windows 11'S Visual Keyboard Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-how-to-stop-apex-legends-freezes/"><u>Beat the Bug: How to Stop Apex Legends Freezes</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-competition-with-fc-managed-for-no-charge/"><u>Beat the Competition with FC Managed for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/boost-functionality-with-the-best-windows-powertoys-uses/"><u>Boost Functionality with the Best Windows PowerToys Uses</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-10-and-11s-vital-parts-missing-alert/"><u>Avoiding Windows 10 & 11'S Vital Parts Missing Alert</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-fixing-windows-file-download-failures/"><u>Approaches to Fixing Windows File Download Failures</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-the-best-video-metadata-editors-for-mac-users-easy-and-effective/"><u>Updated 2024 Approved The Best Video Metadata Editors for Mac Users (Easy and Effective)</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ultimate-guide-ten-most-affordable-screen-capture-software-for-2024/"><u>Ultimate Guide  Ten Most Affordable Screen Capture Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-folder-empty-warning-on-windows-pcs/"><u>Avoiding Folder Empty Warning on Windows PCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-beyond-inshot-essential-laptop-editing-tools/"><u>[New] Beyond Inshot  Essential Laptop Editing Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-capabilities-upgrading-to-virtualbox-70-in-win11/"><u>Boost Your VM Capabilities: Upgrading to VirtualBox 7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-blankness-3-straightforward-steps-for-win1011/"><u>Banish Blankness: 3 Straightforward Steps for Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-empty-recycle-bin-in-windows-step-by-step/"><u>Automatic Empty Recycle Bin in Windows Step by Step</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-explore-the-best-free-youtube-video-editor-apps-for-android/"><u>[New] Explore the Best Free YouTube Video Editor Apps for Android</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-the-downsides-of-economic-windows-licenses/"><u>Avoiding Pitfalls: The Downsides of Economic Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-wow-crash-code-132-from-windows-11/"><u>Banishing WoW Crash Code 132 From Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-premium-screenshot-and-video-options-for-linux-enthusiasts/"><u>[Updated] Premium Screenshot and Video Options for Linux Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-insight-into-fixing-directdraw-discrepancies-in-win1011/"><u>Advanced Insight Into Fixing DirectDraw Discrepancies in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-approaches-for-integrating-additional-av-software/"><u>Alternative Approaches for Integrating Additional AV Software</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-from-clash-to-cohesion-how-to-match-colors-in-your-video-footage-using-final-cut-pro/"><u>New 2024 Approved From Clash to Cohesion How to Match Colors in Your Video Footage Using Final Cut Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-apple-iphone-7-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock Apple iPhone 7 with iTunes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/bes-most-watched-wonders-the-ultimate-guide-for-2024/"><u>YouTube’s Most-Watched Wonders  The Ultimate Guide for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/livestreaming-leaderboards-which-software-tops-the-chartvmixwirecast/"><u>Livestreaming Leaderboards  Which Software Tops the Chart—VMix/Wirecast?</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-time-travelers-treasure-a-look-at-goofy-movie/"><u>[New] Time Traveler’s Treasure  A Look at 'Goofy Movie'</u></a></li>
<li><a href="https://extra-hints.techidaily.com/photoshop-stability-enhancement-essentiality/"><u>Photoshop Stability Enhancement - Essentiality</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combat-incorrect-video-cards-crashing-game/"><u>Combat Incorrect Video Cards Crashing Game</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/professional-zoom-settings-guide-for-google-meet-for-2024/"><u>Professional Zoom Settings Guide for Google Meet for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-your-pathway-to-audio-mastery-download-and-install-vrecorder-for-2024/"><u>[Updated] Your Pathway to Audio Mastery - Download & Install VRecorder for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-a-step-by-step-process-to-upgrade-and-update-video-covers-on-social-media-for-2024/"><u>[New] A Step-by-Step Process to Upgrade and Update Video Covers on Social Media for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-premium-free-ticking-companion/"><u>2024 Approved  Premium Free Ticking Companion</u></a></li>
<li><a href="https://win11.techidaily.com/averting-error-22-disable-situation-in-windows-11-settings/"><u>Averting Error 22 Disable Situation in Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-windows-programs-a-fixers-manual/"><u>Addressing Inoperative Windows Programs: A Fixer’s Manual</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-post-a-video-from-youtube-on-instagram/"><u>How to Post a Video From YouTube on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/behind-the-veil-of-user-interface-accessing-windows-hidden-personality-editor/"><u>Behind the Veil of User Interface: Accessing Windows’ Hidden Personality Editor</u></a></li>
<li><a href="https://win11.techidaily.com/awareness-on-7-key-windows-events-that-signal-infection/"><u>Awareness on 7 Key Windows Events That Signal Infection</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-the-power-of-final-cut-pro-creating-engaging-video-slideshows-for-2024/"><u>New Unleash the Power of Final Cut Pro Creating Engaging Video Slideshows for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-options-cheap-but-premium-4k-projector-systems/"><u>2024 Approved  Best Options  Cheap but Premium 4K Projector Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-runtime-exceptions-your-ultimate-guide-for-windows-users/"><u>Addressing Runtime Exceptions: Your Ultimate Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-utorrents-windows-download-speed/"><u>Boosting uTorrent's Windows Download Speed</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-valorant-speed-windows-performance-tips/"><u>Boosting Valorant Speed: Windows Performance Tips</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-x50iplus-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computer-skills-keyboard-shortcuts-for-success/"><u>Boost Your Computer Skills: Keyboard Shortcuts for Success</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-productivity-enlarge-or-minify-software-via-keyboard-in-win11/"><u>Boost Your Productivity: Enlarge or Minify Software via Keyboard in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>