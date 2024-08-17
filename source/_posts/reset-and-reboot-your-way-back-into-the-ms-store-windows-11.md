---
title: Reset & Reboot Your Way Back Into the MS Store (Windows 11)
date: 2024-08-16T00:18:23.134Z
updated: 2024-08-17T00:18:23.134Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reset & Reboot Your Way Back Into the MS Store (Windows 11)
excerpt: This Article Describes Reset & Reboot Your Way Back Into the MS Store (Windows 11)
keywords: Reset MS Store,Reboot Windows 11,MS Store Access,Boot PC for MS,Restore Windows,Reinstall MS Store,Startup Repair MS
thumbnail: https://thmb.techidaily.com/07f3d5f057a0a1f3c1d2492add732e27fc47138ba4a1808a078297c558520a47.png
---

## Reset & Reboot Your Way Back Into the MS Store (Windows 11)

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-your-guide-to-affordable-android-recording-with-top-8-free-apps-for-2024/"><u>[New] Your Guide to Affordable Android Recording with Top 8 Free Apps for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-enabling-instant-access-to-youtube-videos-in-your-facebook-browsing/"><u>[Updated] 2024 Approved  Enabling Instant Access to YouTube Videos in Your Facebook Browsing</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-iphoneandroid-sharing-videos-on-twitter-without-retweeting/"><u>[Updated] 2024 Approved  IPhone/Android  Sharing Videos On Twitter Without Retweeting</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-google-meet-mastery-for-free-hostparticipants-ultimate-handbook-for-2024/"><u>[Updated] Google Meet Mastery for Free  Host/Participant's Ultimate Handbook for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-discovering-youtubes-finest-storyweavers/"><u>[Updated] In 2024, Discovering YouTube's Finest Storyweavers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-requesting-for-unrestricted-access-to-shared-visual-and-audio-content/"><u>[Updated] In 2024, Requesting for Unrestricted Access to Shared Visual & Audio Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-key-steps-to-accurate-and-effective-market-research-analysis/"><u>[Updated] Key Steps to Accurate and Effective Market Research Analysis</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-rising-stars-will-likes-surpass-tiktoks-mass-appeal-for-2024/"><u>[Updated] Rising Stars  Will Likes Surpass TikTok's Mass Appeal for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-zoom-calls-with-flair-filters-application-101-for-2024/"><u>[Updated] Zoom Calls with Flair  Filters Application 101 for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-facebooks-vision-for-video-unpacking-the-short-form-movement/"><u>2024 Approved  Facebook's Vision for Video   Unpacking the Short Form Movement</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-history-in-action-top-7-engaging-civilization-wars/"><u>2024 Approved  History in Action  Top 7 Engaging Civilization Wars</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-memory-integrity-feature-grayed-out-on-windows-11/"><u>7 Ways to Fix the Memory Integrity Feature Grayed Out on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/busted-byteguardian-wait-weigh-your-worthiness/"><u>Busted ByteGuardian? Wait, Weigh Your Worthiness</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-infinix-hot-40-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Infinix Hot 40 is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://article-helps.techidaily.com/compendium-of-different-photographic-gadgets-for-2024/"><u>Compendium of Different Photographic Gadgets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://win11.techidaily.com/ease-system-load-cutting-back-on-malware-scanning-power/"><u>Ease System Load: Cutting Back on Malware Scanning Power</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-for-common-win-printer-issues/"><u>Easy Fixes for Common Win-Printer Issues</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-hp-15-inch-budget-laptop-powered-by-amd-can-it-meet-daily-task-demands/"><u>Evaluating HP 15 Inch Budget Laptop Powered by AMD: Can It Meet Daily Task Demands?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-brother-hl-l2360dw-printer-drivers-for-a-hassle-free-setup/"><u>Get the Latest Brother HL-L2360DW Printer Drivers for a Hassle-Free Setup</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-shortcut-creation-on-windows-11/"><u>Harness the Power of Shortcut Creation on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-superior-control-over-windows-11-task-management/"><u>How to Activate Superior Control Over Windows 11 Task Management</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-your-emulated-games-into-playnite-on-windows/"><u>How to Add Your Emulated Games Into Playnite on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-infinix-note-30-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Infinix Note 30 Phone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamlined-strategy-to-create-your-custom-youtube-queue/"><u>In 2024, Streamlined Strategy to Create Your Custom YouTube Queue</u></a></li>
<li><a href="https://win11.techidaily.com/key-considerations-when-shopping-for-a-windows-device/"><u>Key Considerations When Shopping for a Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-correction-of-writing-permissions-issue-on-pcs/"><u>Mastering Correction of Writing Permissions Issue on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-aural-outputs-with-win-compatible-audacity/"><u>Overhauling Windows' Aural Outputs with Win-Compatible Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-secrets-for-restoring-hidden-panes-on-win-1011-with-ease/"><u>Reclaim Your Lost Windows! Secrets for Restoring Hidden Panes on Win 10/11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-sign-out-problem-due-to-malware-intrusion/"><u>Remedying Windows Sign-Out Problem Due to Malware Intrusion</u></a></li>
<li><a href="https://win11.techidaily.com/setting-updeactivating-wi-fi-data-tracking-on-windows-11/"><u>Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smashing-through-disconnection-issues-during-wins-discord-setup/"><u>Smashing Through Disconnection Issues During Win's Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-restoring-secure-file-connections-on-win/"><u>Strategies for Restoring Secure File Connections on Win</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-code-0x0001-glitches-in-ge-and-windows-os/"><u>Strategies to Address Code 0X0001 Glitches in GE & Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-easy-guide-to-opening-iis-explorer/"><u>The Easy Guide to Opening IIS Explorer</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-noobs-manual-to-saving-streaming-radio-lines-for-2024/"><u>The Noob's Manual to Saving Streaming Radio Lines for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-rankings-expert-review-of-2024s-most-efficient-mesh-network-devices/"><u>The Ultimate Rankings: Expert Review of 2024'S Most Efficient Mesh Network Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-troubleshooting-freezing-spotify-app-on-windows-11/"><u>Tips for Troubleshooting Freezing Spotify App on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-nokia-c22-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Nokia C22 Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-if-vac-isnt-verifying-your-online-gaming-session/"><u>Troubleshooting Tips If VAC Isn't Verifying Your Online Gaming Session</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-oppo-reno-10-pro-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Oppo Reno 10 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-fixing-search-service-disruptions/"><u>Understanding and Fixing Search Service Disruptions</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-samsung-galaxy-s23-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Samsung Galaxy S23 password or pattern lock</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-composite-device-is-an-older-usb-device-solved/"><u>USB Composite Device Is an Older USB Device [SOLVED]</u></a></li>
<li><a href="https://win11.techidaily.com/win11-audit-steps-for-default-user-permission-reset/"><u>Win11 Audit: Steps for Default User Permission Reset</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-audio-configuration-for-spatiality/"><u>Windows 11 Audio Configuration for Spatiality</u></a></li>
</ul></div>
