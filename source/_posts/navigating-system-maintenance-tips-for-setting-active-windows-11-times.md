---
title: "Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
date: 2024-07-13T10:48:32.450Z
updated: 2024-07-14T10:48:32.450Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
excerpt: "This Article Describes Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
keywords: Win11 Setup Guide,Timesync Windows 11,Optimal Win11 Time,Win11 Maintenance Tips,Active Windows 11 Schedule,Setting Win11 Clock,Timing Windows 11 Properly
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Navigating System Maintenance: Tips for Setting Active Windows 11 Times

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-professional-noise-reduction-software-for-video-editing-for-2024/"><u>[New] Professional Noise-Reduction Software for Video Editing for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-glimpses-identifying-who-sees-your-pics-for-2024/"><u>[Updated] Instagram Glimpses  Identifying Who Sees Your Pics for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-great-free-screen-capture-devices-ranking-for-2024/"><u>[New] Great Free Screen Capture Devices Ranking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-free-from-marks-acquiring-unmarked-stock-photography/"><u>In 2024, Free From Marks  Acquiring Unmarked Stock Photography</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-intovas-action-realm/"><u>The Ultimate Guide to Intova's Action Realm</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-where-can-i-find-glass-breaking-sound-effect/"><u>Updated 2024 Approved Where Can I Find Glass Breaking Sound Effect?</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-unveiling-the-ideal-aspect-ratio-for-video-content/"><u>[Updated] Unveiling the Ideal Aspect Ratio for Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-walkthrough-restoring-default-search-features-in-windows-11/"><u>Detailed Walkthrough: Restoring Default Search Features in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-understanding-the-difference-in-30-and-60-fps-videography/"><u>In 2024, Understanding the Difference in 30 and 60 FPS Videography</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-reimagining-stills-as-continuous-motion-sessions/"><u>2024 Approved  Reimagining Stills as Continuous Motion Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-enhance-post-impact-auto-adjusting-videos-for-instagram-on-mac/"><u>[New] In 2024, Enhance Post Impact  Auto-Adjusting Videos for Instagram on Mac</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-balanced-mounts-capture-clear-shots-every-time/"><u>In 2024, Best Balanced Mounts  Capture Clear Shots Every Time</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-caption-solutions-photo-text-integration-guide/"><u>In 2024, Ideal Caption Solutions  Photo-Text Integration Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/effortlessly-record-high-quality-mac-audio-using-audacity-for-2024/"><u>Effortlessly Record High-Quality Mac Audio Using Audacity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-pro-level-video-conferencing-picking-the-best-5-recorders/"><u>[Updated] Pro-Level Video Conferencing  Picking the Best 5 Recorders</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-honor-x8b-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Honor X8b Phone? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-15-pro-max-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your Apple iPhone 15 Pro Max?</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-vivo-y27s-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Vivo Y27s Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-oppo-f23-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Oppo F23 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prepping-for-the-latest-macos-big-sur-update/"><u>[New] Prepping for the Latest MacOS Big Sur Update</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/no-budget-no-problem-top-free-flv-video-editors/"><u>No Budget? No Problem! Top Free FLV Video Editors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/overcoming-printer-paper-jams-and-errors/"><u>Overcoming Printer Paper Jams and Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-typing-experience-speed-up-windows-keyboard-delay/"><u>Enhance Your Typing Experience: Speed Up Windows Keyboard Delay</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-optimize-your-views-youtube-thumbnail-dimensions-and-pro-tips/"><u>2024 Approved Optimize Your Views YouTube Thumbnail Dimensions and Pro Tips</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-graphics-new-vega-3-firmware-update/"><u>Boost Graphics - New Vega 3 Firmware Update</u></a></li>
</ul></div>
