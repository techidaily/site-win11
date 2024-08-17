---
title: Addressing Discreprancies in Power Usage Display for Win 11 Systems
date: 2024-08-15T23:14:22.145Z
updated: 2024-08-16T23:14:22.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Discreprancies in Power Usage Display for Win 11 Systems
excerpt: This Article Describes Addressing Discreprancies in Power Usage Display for Win 11 Systems
keywords: Power Usage WWin11,Win11 Energy Discrepancy,Energy Display Win11,Power Use Tracking Windows,Win11 Battery Efficiency,Windows Energy Monitoring,Power Metrics Win11 Systems
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Addressing Discreprancies in Power Usage Display for Win 11 Systems

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-bandicam-revisited-a-deep-dive-into-screen-recording/"><u>[New] In 2024, Bandicam Revisited  A Deep Dive Into Screen Recording</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mastering-live-recording-via-logitech-camera-guide-for-2024/"><u>[New] Mastering Live Recording via Logitech Camera Guide for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/treamlining-youtube-content-onto-insta-feed/"><u>[New] Streamlining YouTube Content Onto Insta Feed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-download-youtube-playlist-step-by-step/"><u>[Updated] 2024 Approved  How to Download YouTube Playlist-Step by Step</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boosting-your-gameplay-tips-for-increased-zoom-range/"><u>[Updated] Boosting Your Gameplay  Tips for Increased Zoom Range</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-close-up-power-in-videoleap-zooming-made-easy/"><u>[Updated] Close-Up Power in VideoLeap  Zooming Made Easy</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-key-methods-from-video-links-to-downloaded-audios/"><u>2024 Approved  Key Methods  From Video Links to Downloaded Audios</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-90-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor 90 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/clean-audio-clear-conscience-how-to-remove-background-noise-in-fcpx/"><u>Clean Audio, Clear Conscience How to Remove Background Noise in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-def5-error-code-in-onedrive-w11-style/"><u>Confronting the Def5 Error Code in OneDrive, W11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/contrasting-local-and-remote-protocols-for-upgrading-windows-operating-system/"><u>Contrasting Local and Remote Protocols for Upgrading Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-effective-power-indicators-in-windows/"><u>Crafting Effective Power Indicators in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/defrost-stuck-menus-top-fixes-to-try-today/"><u>Defrost Stuck Menus: Top Fixes to Try Today</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On OnePlus 11R? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-spotify-connectivity-fails/"><u>Eliminating Windows 11'S Spotify Connectivity Fails</u></a></li>
<li><a href="https://win11.techidaily.com/fixed-silent-outlook-alerts-in-windows-environment/"><u>Fixed Silent Outlook Alerts in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-smooth-audio-transmission-in-steam/"><u>Guaranteeing Smooth Audio Transmission in Steam</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/hangout-history-top-4-strategies-for-2024/"><u>Hangout History  Top 4 Strategies for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-skirt-sie-and-load-unsigned-drivers-in-windows-oses/"><u>How to Skirt SIE & Load Unsigned Drivers in Windows OSes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oppo-reno-11f-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Oppo Reno 11F 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-xiaomi-redmi-note-12r-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on Xiaomi Redmi Note 12R?</u></a></li>
<li><a href="https://win11.techidaily.com/hush-your-background-processes-in-win11/"><u>Hush Your Background Processes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-against-windows-11-search-failures/"><u>Immediate Actions Against Windows 11 Search Failures</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-apple-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>In 2024, Apple iPhone 12 Pro Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-oppo-reno-10-pro-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/increase-windows-storage-securely/"><u>Increase Windows Storage Securely</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-correct-drivers-for-your-brother-hl-l2380d-printer-on-a-pc-with-windows-os/"><u>Install the Correct Drivers for Your Brother HL-L2380D Printer on a PC with Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-android-pc-connection-step-by-step-guide/"><u>Mastering Android-PC Connection: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-activation-failures-in-office-suite/"><u>Navigating Activation Failures in Office Suite</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-system-recovery-how-sfc-and-dism-restore-windows-10-stability/"><u>Navigating System Recovery: How SFC and DISM Restore Windows 10 Stability</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-create-stunning-mac-slideshows-a-beginners-guide-to-ezvid/"><u>New In 2024, Create Stunning Mac Slideshows A Beginners Guide to Ezvid</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-pomodoro-strategies-best-windows-timer-selections/"><u>Optimal Pomodoro Strategies - Best Windows Timer Selections</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-inactive-session-limit/"><u>Personalizing Windows Inactive Session Limit</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-original-look-for-discoloured-extend-volume/"><u>Reclaim Original Look for Discoloured Extend Volume</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-preferred-file-layout-settings/"><u>Reclaiming Your Preferred File Layout Settings</u></a></li>
<li><a href="https://win11.techidaily.com/reconstructed-windows-log-a-guide-to-clearing-defender-data/"><u>Reconstructed Windows Log: A Guide to Clearing Defender Data</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-troubleshooting-tools-in-windows-1011/"><u>Resolving Faulty Troubleshooting Tools in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-ui-proposing-innovations-in-windows-11-widget-design/"><u>Revolutionizing UI: Proposing Innovations in Windows 11 Widget Design</u></a></li>
<li><a href="https://network-issues.techidaily.com/rtx-3080-troubleshooting-resurrect-your-gaming-experience/"><u>RTX 3080 Troubleshooting: Resurrect Your Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/security-alert-hacked-fingerprint-recognition-on-windows/"><u>Security Alert: Hacked Fingerprint Recognition on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/squashing-faulty-empty-directory-alert-with-0x80070091-on-windows-11/"><u>Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-for-astro-a10-microphone-malfunctions-expert-tips/"><u>Step-by-Step Fixes for Astro A10 Microphone Malfunctions - Expert Tips</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-the-application-was-unable-to-start-xc000003e-on-win11-and-11/"><u>Strategies to Address The Application Was Unable to Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/structure-your-thoughts-visual-notes-in-obsidian/"><u>Structure Your Thoughts: Visual Notes in Obsidian</u></a></li>
<li><a href="https://win11.techidaily.com/swift-systems-top-strategies-for-fixed-windows-11-wwe-games/"><u>Swift Systems: Top Strategies for Fixed Windows 11 WWE Games</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-transition-text-editor-from-light-to-dark-windows-11-style/"><u>Swiftly Transition Text Editor From Light to Dark, Windows 11 Style</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-guide-to-the-fujitsu-scansnap-ix1400-revolutionizing-document-management-in-home-and-small-business-settings/"><u>The Ultimate Guide to the Fujitsu ScanSnap iX1400: Revolutionizing Document Management in Home and Small Business Settings</u></a></li>
<li><a href="https://win11.techidaily.com/the-underrated-tools-comparing-windows-monitoring-systems/"><u>The Underrated Tools: Comparing Windows' Monitoring Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-ai-enhanced-platforms-for-personalized-book-suggestions/"><u>Top 5 AI-Enhanced Platforms for Personalized Book Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-fixes-to-unblock-firefox-page-load-blockage/"><u>Top Windows Fixes to Unblock Firefox Page Load Blockage</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-technological-timelines-using-a-windows-7-key-in-windows-11-setup/"><u>Traversing Technological Timelines: Using a Windows 7 Key in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-essential-tools-your-guide-to-zero-cost-win11-power/"><u>Unveiling Essential Tools: Your Guide to Zero-Cost Win11 Power</u></a></li>
<li><a href="https://win11.techidaily.com/windows-12x-steam-deck-step-by-step-guide/"><u>Windows 12X Steam Deck: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-magic-mastering-ctrl-combinations/"><u>Windows Photos Magic: Mastering Ctrl Combinations</u></a></li>
</ul></div>
