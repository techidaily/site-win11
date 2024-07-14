---
title: How to Enable the Volume Mixer in the Action Center in Windows 11
date: 2024-07-13T10:20:31.662Z
updated: 2024-07-14T10:20:31.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable the Volume Mixer in the Action Center in Windows 11
excerpt: This Article Describes How to Enable the Volume Mixer in the Action Center in Windows 11
keywords: Windows 11 Volume Control,Action Center Sound Mixer,Enable Volume Mixer Guide,Windows 11 Audio Settings,Mixer in Action Center Access,Volume Adjustment for Win11,Turning on Mixer in Win11
thumbnail: https://thmb.techidaily.com/72ad6224a96d1332d870ccac31eeed89a25da9895e91d61d746d246092f66e50.png
---

## How to Enable the Volume Mixer in the Action Center in Windows 11

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.


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
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/conducting-harmonious-auditory-performance-in-windows/"><u>Conducting Harmonious Auditory Performance in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exclusive-free-player-list-for-windowsmac-users/"><u>In 2024, Exclusive Free Player List for Windows/Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-an-inactive-firewall-a-step-by-step-guide/"><u>Bypassing an Inactive Firewall: A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-evaluating-the-impact-of-true-to-self-imagery-on-instagram/"><u>[Updated] In 2024, Evaluating the Impact of True-to-Self Imagery on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-online-tools-discovering-the-top-10-dynamic-image-changers/"><u>[Updated] Best Online Tools  Discovering the Top 10 Dynamic Image Changers</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://extra-information.techidaily.com/tips-for-reducing-vr-induced-symptoms/"><u>Tips for Reducing VR-Induced Symptoms</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-installation-of-arm-based-windows-11-from-iso/"><u>Mastering the Installation of ARM-Based Windows 11 From ISO</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-a-professionals-playbook-to-profitable-youtube-ventures/"><u>In 2024, A Professional's Playbook to Profitable YouTube Ventures</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-launch-windows-11-access-control-panel/"><u>Locate and Launch Windows 11 Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-and-optimizing-windows-11-service-usage-wisely/"><u>Prioritizing and Optimizing Windows 11 Service Usage Wisely</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-experience-in-roblox-addressing-account-restrictions/"><u>Fixing Blocked Experience in Roblox: Addressing Account Restrictions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-premium-macpc-video-recording-software/"><u>[New] 2024 Approved  Premium Mac/PC Video Recording Software</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-master-psd-color-dynamics/"><u>[Updated] Master PSD Color Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-the-failed-file-synchronization-on-steam/"><u>Remedy for the Failed File Synchronization on Steam</u></a></li>
<li><a href="https://extra-hints.techidaily.com/film-fanatics-unite-ioss-best-free-and-paid-filmmaking-tools/"><u>Film-Fanatics Unite! IOS's Best Free & Paid Filmmaking Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-vivo-y200e-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Vivo Y200e 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-video-layouts-vertical-or-horizontal/"><u>[Updated] Facebook Video Layouts  Vertical or Horizontal?</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-win-os-cease-df-glitching-issues/"><u>Stabilizing Win OS: Cease DF Glitching Issues</u></a></li>
<li><a href="https://win11.techidaily.com/dual-screen-delight-personalized-pixels-per-monitor-of-windows-1011/"><u>Dual Screen Delight: Personalized Pixels per Monitor of Windows 10/11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-honor-x9a-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Honor X9a Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-reading-qr-codes-on-windows-devices/"><u>Essential Tips for Reading QR Codes on Windows Devices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-get-steady-the-best-free-video-stabilization-websites/"><u>Updated In 2024, Get Steady The Best Free Video Stabilization Websites</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-pcs-wi-fi-woes-six-effective-steps-from-fixing-adapter-failure/"><u>Reviving Your PC's Wi-Fi Woes - Six Effective Steps From Fixing Adapter Failure</u></a></li>
<li><a href="https://win11.techidaily.com/best-7-free-players-for-your-pcs-viewing-pleasure-win/"><u>Best 7 Free Players for Your PC's Viewing Pleasure (Win)</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-best-linux-screenshot-and-video-solutions/"><u>[New] In 2024, Best Linux Screenshot and Video Solutions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-iphone-se-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>Unlock Your iPhone SE in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-best-practices-for-measuring-igtv-video-effectiveness/"><u>[New] Best Practices for Measuring IGTV Video Effectiveness</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-ribbon-to-windows-explorer/"><u>Restoring Legacy Ribbon to Windows Explorer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-assessing-enterprise-chat-apps-for-unmatched-collaboration-which-holds-the-high-ground-slack-or-discord-for-2024/"><u>[Updated] Assessing Enterprise Chat Apps for Unmatched Collaboration  Which Holds the High Ground, Slack or Discord for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/an-effective-guide-to-fix-error-0xc0000001-on-windows-pcs/"><u>An Effective Guide to Fix Error 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/alter-viewer-angle-in-windows-setup/"><u>Alter Viewer Angle in Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-crashes-during-xbox-app-update-process/"><u>Resolving Crashes During Xbox App Update Process</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-win-over-product-sponsors-in-the-youtube-arena/"><u>How to Win Over Product Sponsors in the YouTube Arena</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-apowersoft-examined-a-full-review-of-its-capabilities/"><u>[Updated] Apowersoft Examined  A Full Review of Its Capabilities</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-x6-pro-bootloader-easily-by-drfone-android/"><u>How to Unlock Poco X6 Pro Bootloader Easily</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-itel-a05s-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Itel A05s</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-file-management-crafting-multitudes-of-subfolders-instantly/"><u>Conquer File Management: Crafting Multitudes of Subfolders Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-yuzu-gameplay-speed/"><u>Amplify Your Yuzu Gameplay Speed</u></a></li>
<li><a href="https://win11.techidaily.com/go-pure-with-linux-avoid-wsl/"><u>Go Pure with Linux - Avoid WSL</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-advanced-tips-for-zooms-video-filters/"><u>2024 Approved  Advanced Tips for Zoom's Video Filters</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-nokia-c300-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Nokia C300 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/switch-calculator-color-scheme-to-dark/"><u>Switch Calculator Color Scheme to Dark</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-harmonizing-technology-with-taste-your-guide-to-mastering-audio-format-selection/"><u>Updated Harmonizing Technology with Taste Your Guide to Mastering Audio Format Selection</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-a1x-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo A1x 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/top-5-strategies-for-implementing-tiktok-video-descriptions/"><u>Top 5 Strategies for Implementing TikTok Video Descriptions</u></a></li>
<li><a href="https://win11.techidaily.com/processors-and-windows-discovering-your-cpus-generation-in-8-steps/"><u>Processors & Windows: Discovering Your CPU's Generation in 8 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/speak-up-troubleshooting-and-fixing-microphone-errors-on-microsoft-powered-google-meet/"><u>Speak Up! Troubleshooting and Fixing Microphone Errors on Microsoft-Powered Google Meet</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-unlocking-desktop-recording-the-ezvide-approach/"><u>[New] In 2024, Unlocking Desktop Recording - The EZvide Approach</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-s18-pro-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo S18 Pro</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-on-apple-iphone-11-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock On Apple iPhone 11? How to Fix it?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-top-picks-best-free-cross-platform-video-communication-tools/"><u>[New] 2024 Approved  Top Picks  Best Free Cross-Platform Video Communication Tools</u></a></li>
<li><a href="https://win11.techidaily.com/successful-virtualbox-setup-in-winscape/"><u>Successful VirtualBox Setup in Winscape</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-take-your-edits-to-the-next-level-10-free-fcpx-plugins/"><u>In 2024, Take Your Edits to the Next Level 10 Free FCPX Plugins</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-quick-recording-keyboard-shortcut-tips-for-win-11/"><u>Mastering the Art of Quick Recording: Keyboard Shortcut Tips for Win 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unlock-vertical-video-potential-top-editing-apps-for-ios-and-android/"><u>New Unlock Vertical Video Potential Top Editing Apps for iOS and Android</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-imovie-trimming-query-the-reason-behind-video-cropping/"><u>[Updated] IMovie Trimming Query  The Reason Behind Video Cropping</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-yuzu-experience-on-windows/"><u>Supercharge Your Yuzu Experience on Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-pushing-boundaries-with-dells-revolutionary-p2715q-monitor-review/"><u>2024 Approved  Pushing Boundaries with Dell's Revolutionary P2715Q Monitor Review</u></a></li>
</ul></div>
