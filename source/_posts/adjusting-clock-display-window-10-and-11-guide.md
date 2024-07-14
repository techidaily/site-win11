---
title: "Adjusting Clock Display: Window 10 & 11 Guide"
date: 2024-07-13T11:17:17.285Z
updated: 2024-07-14T11:17:17.285Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adjusting Clock Display: Window 10 & 11 Guide"
excerpt: "This Article Describes Adjusting Clock Display: Window 10 & 11 Guide"
keywords: Windows Clock Setup,Time Update PC,Win10 Clock Adjust,Win11 Timer Change,Display Clock PC,Update System Time,Setting Clock Windows
thumbnail: https://thmb.techidaily.com/f6b66ac253e72b1db3b7035e49bd4e3f144338d6a3b54451e87f8a05d4dd9575.jpg
---

## Adjusting Clock Display: Window 10 & 11 Guide

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-motorola-moto-g23-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-background-noise-begone-mastering-audio-editing-in-final-cut-pro-x/"><u>New 2024 Approved Background Noise Begone! Mastering Audio Editing in Final Cut Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-the-crossroads-of-full-time-work-and-youtube/"><u>2024 Approved  Navigating the Crossroads of Full-Time Work & YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-stay-concentrated-how-to-tame-the-chatter-of-google-video-calls/"><u>[New] In 2024, Stay Concentrated  How to Tame the Chatter of Google Video Calls</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-techniques-for-overcoming-media-app-issues-in-win11/"><u>Methodical Techniques for Overcoming Media App Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-restore-missing-app-icons/"><u>Methods to Restore Missing App Icons</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-motorola-edge-40-neo-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Motorola Edge 40 Neo Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-professional-strategies-for-drone-imagery-editing/"><u>2024 Approved  Professional Strategies for Drone Imagery Editing</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-cloud-connectivity-revive-google-drive-windows-links/"><u>Streamlining Cloud Connectivity: Revive Google Drive Windows Links</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-avoid-piracy-safe-youtube-to-mp4-conversion-tips/"><u>In 2024, Avoid Piracy  Safe YouTube to MP4 Conversion Tips</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlock-new-opportunities-in-croatia-why-learn-its-language-now/"><u>Unlock New Opportunities in Croatia: Why Learn Its Language Now?</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-the-course-of-creative-conquests-self-vs-competitors-on-youtube-for-2024/"><u>Charting the Course of Creative Conquests  Self Vs. Competitors on YouTube for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-tips-for-crafting-and-perfecting-multisnapping-snapchat-stories-for-2024/"><u>Quick Tips for Crafting and Perfecting Multisnapping Snapchat Stories for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-apple-tv-and-facebook-integration-watching-videos-easily/"><u>[Updated] 2024 Approved  Apple TV and Facebook Integration  Watching Videos Easily</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-high-impact-tweets-of-the-year-viewer-rankings/"><u>[Updated] In 2024, High-Impact Tweets of the Year  Viewer Rankings</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insights-for-placement-of-software-shortcuts-on-taskbar/"><u>Quick Insights for Placement of Software Shortcuts on Taskbar</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y200e-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y200e 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-digital-documentation-mobile-and-desktop-meeting-recordings/"><u>[Updated] In 2024, Digital Documentation  Mobile & Desktop Meeting Recordings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ending-static-audio-in-obs-streams/"><u>[Updated] Ending Static Audio in OBS Streams</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-vivo-y78-5g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Vivo Y78 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-maximizing-macs-potential-capturing-the-spirit-of-roblox-games/"><u>In 2024, Maximizing Mac's Potential  Capturing the Spirit of Roblox Games</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-expert-recommendations-leveraging-voxels-voice-manipulation-feature-to-boost-your-discord-experience/"><u>New 2024 Approved Expert Recommendations Leveraging Voxels Voice Manipulation Feature to Boost Your Discord Experience</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-it-all-the-top-7-ways-to-use-windows-11-effectively/"><u>Optimize It All: The Top 7 Ways to Use Windows 11 Effectively</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-how-to-be-a-good-interviewer/"><u>[New] How To Be A Good Interviewer</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-mastering-video-best-practices-in-game-recording-and-streaming/"><u>2024 Approved  Mastering Video  Best Practices in Game Recording & Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-novices-nexus-grasping-frame-rates-and-aspect-ratios/"><u>In 2024, Novice's Nexus  Grasping Frame Rates and Aspect Ratios</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-ranking-the-very-best-10-free-online-artists-on-youtube/"><u>In 2024, Ranking the Very Best 10 Free Online Artists on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-edit-like-a-pro-video-editing-on-mac-os-x-mavericks-for-2024/"><u>Updated Edit Like a Pro Video Editing on Mac OS X Mavericks for 2024</u></a></li>
</ul></div>
