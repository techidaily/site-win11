---
title: Diminish Explore Tab Clamor in Windows 11
date: 2024-08-15T23:36:01.741Z
updated: 2024-08-16T23:36:01.741Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diminish Explore Tab Clamor in Windows 11
excerpt: This Article Describes Diminish Explore Tab Clamor in Windows 11
keywords: Windows 11 Noise Reduction,Minimize Taskbar Sound,Quiet System Tray,Silent Explorer View,Diminish Explore Tab Volume,Hush Windows App Bar,Mute Clamshell Notification
thumbnail: https://thmb.techidaily.com/e6c6b6e32249dbf76f20abd6c6055b57975d7da74a0ada4b319cc0a746113075.jpg
---

## Diminish Explore Tab Clamor in Windows 11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-comedic-content-concepts-7-hilarious-vlog-ideas-for-laughter-lovers/"><u>[New] 2024 Approved  Comedic Content Concepts  7 Hilarious Vlog Ideas for Laughter Lovers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-engaging-youtube-end-credits-for-2024/"><u>[New] Crafting Engaging YouTube End Credits for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-how-to-record-gameplay-and-webcam/"><u>[New] How to Record Gameplay and Webcam</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-immersive-experience-creating-rich-skype-recordings-using-obs-for-2024/"><u>[New] Immersive Experience  Creating Rich Skype Recordings Using OBS for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-from-chats-to-files-the-methodical-approach-to-downloading-fb-video/"><u>[New] In 2024, From Chats to Files  The Methodical Approach to Downloading FB Video</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/aster-the-art-of-subtitlecc-integration-in-youtube-with-this-guide/"><u>[New] Master the Art of Subtitle/CC Integration in YouTube with This Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-dive-into-the-world-of-self-expression-a-treasury-of-instagramcaptions/"><u>[Updated] Dive Into the World of Self-Expression - A Treasury of #InstagramCaptions</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-wiping-your-discord-servers-from-pc-and-android-devices-for-2024/"><u>[Updated] Wiping Your Discord Servers From PC and Android Devices for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-high-fidelity-mp4-streamer-to-facebook/"><u>2024 Approved  High-Fidelity MP4 Streamer to Facebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-humorous-vines-the-ultimate-10-list/"><u>2024 Approved  Humorous Vines  The Ultimate 10 List</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-professional-panoramic-vision-leading-360-cameras-of-2023/"><u>2024 Approved  Professional Panoramic Vision  Leading 360° Cameras of 2023</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-honor-90-lite-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Honor 90 Lite Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-for-broadcasting-is-obs-superior-to-twitch-studio-for-2024/"><u>Best for Broadcasting  Is OBS Superior to Twitch Studio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-torrent-lag-on-your-pc-with-qbittorrent/"><u>Breaking Through Torrent Lag on Your PC with qBittorrent</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-vintage-films-with-madvr-for-windows/"><u>Breathe New Life Into Vintage Films with MadVR for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-new-life-into-your-steam-games-milestones/"><u>Breathing New Life Into Your Steam Games' Milestones</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-up-your-cursor-windows-tips-and-tricks/"><u>Brightening Up Your Cursor: Windows Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-windows-11s-bluetooth-9-effective-fixes-at-hand/"><u>Bring Back Windows 11'S Bluetooth: 9 Effective Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/browsing-made-lighter-top-7-windows-apps-for-less-memory-use/"><u>Browsing Made Lighter: Top 7 Windows Apps for Less Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/budget-blues-identifying-the-risks-of-low-cost-windows-licensing/"><u>Budget Blues: Identifying the Risks of Low-Cost Windows Licensing</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-chromes-glitch-enabling-flawless-filesync-on-windows/"><u>Bypass Chrome’s Glitch: Enabling Flawless Filesync on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-non-responsive-power-switches-on-windows-11/"><u>Bypass Non-Responsive Power Switches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-stuck-screen-on-league-of-legends-bootup/"><u>Bypass Stuck Screen on League of Legends Bootup</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blurriness-9-ways-to-fine-tune-your-windows-display/"><u>Bypassing Blurriness: 9 Ways to Fine-Tune Your Windows Display</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-chrome-blackout-a-step-by-step-guide/"><u>Bypassing Chrome Blackout: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-support-issue-in-windows-the-essential-fixes-list/"><u>Bypassing Support Issue in Windows: The Essential Fixes List</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unknown-not-initialized-in-windows-operating-systems/"><u>Bypassing Unknown Not Initialized in Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-your-cortana-story-in-windows-files/"><u>Capturing Your Cortana Story in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/cautionary-tales-the-perils-of-affordable-windows-activation-codes/"><u>Cautionary Tales: The Perils of Affordable Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-edge-symbols-regular-occurrence/"><u>Ceasing Edge Symbols' Regular Occurrence</u></a></li>
<li><a href="https://win11.techidaily.com/change-your-visual-preference-in-winterm/"><u>Change Your Visual Preference in WinTerm</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-new-journey-away-from-lost-at-sea-xbox-errors/"><u>Charting a New Journey Away From Lost at Sea Xbox Errors</u></a></li>
<li><a href="https://win11.techidaily.com/chilly-warm-up-your-windows-11-with-holiday-hacks/"><u>Chilly Warm-Up Your Windows 11 with Holiday Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-your-preferred-package-manager-for-windows-devices/"><u>Choosing Your Preferred Package Manager for Window's Devices</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigate-power-management-to-prevent-usb-sleep/"><u>Circumnavigate Power Management to Prevent USB Sleep</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-and-resolving-the-mystery-of-error-0x8007251d-in-windows/"><u>Clarifying and Resolving the Mystery of Error 0X8007251d in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-ui-redesign-for-file-explorer-in-w11/"><u>Classic UI Redesign for File Explorer in W11</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-on-windows-11-a-synopsis-of-app-removal-techniques-107-chars/"><u>Clean Slate on Windows 11: A Synopsis of App Removal Techniques (107 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-reset-user-permissions-to-basics-in-windows-11/"><u>Clean Slate: Reset User Permissions to Basics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-concise-views-mastering-compact-explorer-layout/"><u>Clear and Concise Views: Mastering Compact Explorer Layout</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstacles-to-the-microsoft-store-on-windows-11/"><u>Clearing Obstacles to the Microsoft Store on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-to-smooth-ps-on-windows/"><u>Clearing the Path to Smooth PS on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-local-device-misnaming-on-windows-systems/"><u>Clearing Up Local Device Misnaming on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-windows-bluetooth-connectivity-issues/"><u>Clearing Up Windows Bluetooth Connectivity Issues</u></a></li>
<li><a href="https://extra-information.techidaily.com/editors-edge-the-power-of-video-tools-on-m1-technology/"><u>Editors' Edge  The Power of Video Tools on M1 Technology</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/expert-tips-for-online-korean-learning-the-ultimate-collection/"><u>Expert Tips for Online Korean Learning: The Ultimate Collection</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-poco-x5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Poco X5 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-smoothly-manipulate-video-speed-in-snapchat-for-2024/"><u>How to Smoothly Manipulate Video Speed in Snapchat for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nubia-red-magic-9-pro-bootloader-easily-by-drfone-android/"><u>How to Unlock Nubia Red Magic 9 Pro Bootloader Easily</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-cutting-edge-methods-backing-up-iphone-photos-to-snapchat/"><u>In 2024, Cutting-Edge Methods  Backing Up iPhone Photos to Snapchat</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ingenious-strategies-for-selecting-trailer-soundtracks/"><u>Ingenious Strategies for Selecting Trailer Soundtracks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/learning-the-ropes-of-lunapics-user-interface/"><u>Learning the Ropes of LunaPic's User Interface</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/locating-electric-vehicle-chargers-with-google-maps-a-comprehensive-guide/"><u>Locating Electric Vehicle Chargers with Google Maps: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/modulate-your-message-a-top-tier-list-of-voice-change-mobile-apps/"><u>Modulate Your Message  A Top-Tier List of Voice Change Mobile Apps</u></a></li>
<li><a href="https://data-wizards.techidaily.com/quick-acquisition-galactic-visual-revival/"><u>Quick Acquisition: Galactic Visual Revival</u></a></li>
<li><a href="https://hardware-help.techidaily.com/visit-the-manufacturers-official-website-to-find-the-most-recent-drivers-compatible-with-your-system-eg-dell-or-hp-download-all-essential-drivers-related-to121/"><u>Visit the Manufacturer's Official Website to Find the Most Recent Drivers Compatible with Your System, E.g., Dell or HP. Download All Essential Drivers Related to USB Ports and Chipset Firmware Updates if Available.</u></a></li>
</ul></div>
