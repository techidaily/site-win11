---
title: Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
date: 2024-07-13T09:51:39.483Z
updated: 2024-07-14T09:51:39.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
excerpt: This Article Describes Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
keywords: Enable Clipboard Share,Activate Paste Functionality,Security Shield Startup,Edge Settings Access,Copy & Paste on Edge,Turn On Text Copy,Edge Shield Key Steps
thumbnail: https://thmb.techidaily.com/19760dde0975a0de0ce2cfe0db96677605f044bc91648bd3418188a2647d61d0.png
---

## Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


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
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-enhance-your-digital-footprint-upload-tiktoks-on-twitter/"><u>[Updated] In 2024, Enhance Your Digital Footprint  Upload TikToks on Twitter</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-honor-90-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Honor 90</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-digital-extension-fb-stories-archive/"><u>[New] 2024 Approved  Digital Extension  Fb Stories Archive</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/comedy-central-the-best-laughter-inducing-channels-online-for-2024/"><u>Comedy Central  The Best Laughter-Inducing Channels Online for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unraveling-instagrams-video-time-restrictions-for-2024/"><u>Unraveling Instagram's Video Time Restrictions for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-creativity-in-micro-videography-and-photography/"><u>[New] Unleashing Creativity in Micro Videography and Photography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-optimize-tasks-the-8-superior-facebook-schedulers/"><u>[Updated] In 2024, Optimize Tasks  The 8 Superior Facebook Schedulers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-professional-videographers-guide-to-efficient-color-keying/"><u>[Updated] Professional Videographer's Guide to Efficient Color-Keying</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-battlenet-downloads-for-smooth-gaming/"><u>Turbo Charge Battle.net Downloads for Smooth Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x100-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Vivo X100 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-channel-building-gear-a-quick-start-guide/"><u>[New] Channel-Building Gear  A Quick Start Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://fox-http.techidaily.com/unveiling-the-lesser-known-media-players-post-vlc/"><u>Unveiling the Lesser-Known Media Players Post-VLC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-unveiling-the-efficiency-of-screencastify-recorder/"><u>[New] 2024 Approved  Unveiling the Efficiency of Screencastify Recorder</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-influencing-instagram-step-by-step-tutorial-for-2024/"><u>[New] Influencing Instagram  Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-enhancing-youtube-thumbnails-neon-borders-top-3-methods/"><u>[New] In 2024, Enhancing YouTube Thumbnails  Neon Borders - Top 3 Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-choosing-youtube-premium-what-makes-it-worth-the-price/"><u>2024 Approved  Choosing YouTube Premium  What Makes It Worth the Price?</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-best-10-chinese-video-to-english-translator/"><u>In 2024, Best 10 Chinese Video to English Translator</u></a></li>
<li><a href="https://extra-hints.techidaily.com/incorporating-industry-standards-working-with-cg-centrals-luts-in-post-production/"><u>Incorporating Industry Standards  Working with CG Central's LUTs in Post-Production</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-techniques-for-overcoming-media-app-issues-in-win11/"><u>Methodical Techniques for Overcoming Media App Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-detailed-settings-app-tour/"><u>Windows 11: A Detailed Settings App Tour</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-restore-missing-app-icons/"><u>Methods to Restore Missing App Icons</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/weaving-wondrous-worlds-a-guide-to-the-best-storytelling-halls-1-8/"><u>Weaving Wondrous Worlds  A Guide to the Best Storytelling Halls (#1-#8)</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-14-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone 14?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-cloud-connectivity-revive-google-drive-windows-links/"><u>Streamlining Cloud Connectivity: Revive Google Drive Windows Links</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-enhance-engagement-with-effective-yt-summary-writing/"><u>[New] 2024 Approved  Enhance Engagement with Effective YT Summary Writing</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insights-for-placement-of-software-shortcuts-on-taskbar/"><u>Quick Insights for Placement of Software Shortcuts on Taskbar</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-leading-the-way-in-affordable-video-conferencing-technology/"><u>In 2024, Leading the Way in Affordable Video Conferencing Technology</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/reaper-unveiled-insights-into-advanced-recording-features-and-educational-content-for-2024/"><u>REAPER Unveiled Insights Into Advanced Recording Features & Educational Content for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-oppo-a78-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Oppo A78 5G</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-it-all-the-top-7-ways-to-use-windows-11-effectively/"><u>Optimize It All: The Top 7 Ways to Use Windows 11 Effectively</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-from-4-3-to-16-9-changing-aspect-ratio-in-final-cut-pro-made-easy-for-2024/"><u>New From 4 3 to 16 9 Changing Aspect Ratio in Final Cut Pro Made Easy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-capturequality-assessor-network-for-2024/"><u>[Updated] CaptureQuality Assessor Network for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-increase-your-videos-impact-essential-keyword-analysis-resources/"><u>In 2024, Increase Your Video's Impact  Essential Keyword Analysis Resources</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-no-cost-guide-to-capturing-your-favorite-shows-for-2024/"><u>The No-Cost Guide to Capturing Your Favorite Shows for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-update-audio-drivers-in-windows-1111/"><u>How to Update Audio Drivers in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-second-display-on-w11/"><u>Troubleshooting Missing Second Display on W11</u></a></li>
</ul></div>
