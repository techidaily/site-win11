---
title: "Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
date: 2024-07-13T09:50:00.378Z
updated: 2024-07-14T09:50:00.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
excerpt: "This Article Describes Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
keywords: Active Windows Hours,Time Blocking W11,Surprise Prevention Windows,Control Active Times,Schedule W11 Settings,Avoid Alerts W11,Windows 11 Activity Period
thumbnail: https://thmb.techidaily.com/f05049a163390a10effd56fd7872beac0cf9789080e0cebdf0db85a2c18febb4.jpg
---

## Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11

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
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-hd-hunting-cameras-unveiled/"><u>2024 Approved  Top 5 HD Hunting Cameras Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-vanquish-xps-mysterious-printer-error-xfddddf/"><u>How to Vanquish XP's Mysterious Printer Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-remote-desktop-troubleshoot-internal-errors/"><u>Resolving Windows 11 Remote Desktop: Troubleshoot Internal Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-light-on-shadows-techniques-for-depth-in-illustrator/"><u>2024 Approved  Light on Shadows  Techniques for Depth in Illustrator</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-digital-persona-username-overhaul-guide/"><u>Upgrading Your Digital Persona: UserName Overhaul Guide</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-quick-and-easy-tone-generation-5-top-tools-for-2024/"><u>New Quick and Easy Tone Generation 5 Top Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-your-journey-to-instagram-dominance-started-here/"><u>[Updated] Your Journey to Instagram Dominance, Started Here</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-detailed-breakdown-bublcam-360-reviewed/"><u>2024 Approved  Detailed Breakdown  Bublcam 360 Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-pause-bring-back-lost-sounds-to-tech-gadgets/"><u>Resetting Pause: Bring Back Lost Sounds to Tech Gadgets</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-windows-11-video-editor-roundup-best-free-and-paid-choices-for-2024/"><u>New Windows 11 Video Editor Roundup Best Free and Paid Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-exploring-premium-9-digital-mic-capture-tools/"><u>[New] 2024 Approved  Exploring Premium 9 Digital Mic Capture Tools</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/a-beginners-guide-to-indonesian-social-etiquette/"><u>A Beginner's Guide to Indonesian Social Etiquette</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-lcv-video-monitoring-analysis/"><u>[New] LCV Video Monitoring Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-clearing-microsoft-protection-archives/"><u>Mastering the Art of Clearing Microsoft Protection Archives</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-clicks-avoid-accelerated-movement-in-win-1011/"><u>Stabilizing Clicks: Avoid Accelerated Movement in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/twinkling-tokens-gifting-windows-games-via-mstore/"><u>Twinkling Tokens: Gifting Windows Games via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-with-our-top-5-budget-drivers-for-pcs/"><u>Unleash Potential with Our Top 5 Budget Drivers for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-windows-chrome-problems/"><u>Unclogging Windows Chrome Problems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-explore-the-world-of-custom-thumbnails-top-6-tools-reviewed/"><u>[Updated] Explore the World of Custom Thumbnails - Top 6 Tools Reviewed</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-google-pixel-fold-by-drfone-android/"><u>How to Show Wi-Fi Password on Google Pixel Fold</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-printer-force-delete-on-windows-11/"><u>Step-by-Step Printer Force Delete on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-missing-component-in-windows-lsassexe/"><u>Handling Missing Component in Windows' lsass.exe</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-tecno-pova-6-pro-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Tecno Pova 6 Pro 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-blue-screen-essential-fixes-for-win10/"><u>Troubleshoot Blue Screen: Essential Fixes for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://games-able.techidaily.com/meet-the-new-nvidia-application-amplifying-games/"><u>Meet the New Nvidia Application Amplifying Games</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-avs-video-editor-a-review-of-its-performance-and-capabilities/"><u>Updated In 2024, AVS Video Editor A Review of Its Performance and Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-your-cortana-data-on-windows/"><u>How to Download Your Cortana Data on Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-visualrecorder-your-yearly-guide-to-screen-captures/"><u>[New] 2024 Approved  VisualRecorder  Your Yearly Guide to Screen Captures</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-e1-in-w10w11-devices/"><u>Tackling Error Code: E1 in W10/W11 Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/maximizing-vimeo-presence-with-movies-from-wmm/"><u>Maximizing Vimeo Presence with Movies From WMM</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/understanding-a-blue-icons-role-facebooks-communication-tool/"><u>Understanding a Blue Icon’s Role  Facebook's Communication Tool</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-from-flat-to-fabulous-adding-3d-effects-to-your-windows-videos-for-2024/"><u>New From Flat to Fabulous Adding 3D Effects to Your Windows Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-exception-breaking-point-on-microsoft-os/"><u>Steps to Eliminate Exception Breaking Point on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-mending-deskanywhere-on-windows-11/"><u>Methods for Mending DeskAnywhere on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-30-pro-tiktok-edits-techniques/"><u>In 2024, Top 30 Pro TikTok Edits Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-unified-platforms-for-sharing-videos/"><u>[Updated] In 2024, Unified Platforms for Sharing Videos</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-store-access-on-windows-11/"><u>Troubleshooting Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-no-uninstall-issue-on-windows-oses/"><u>How to Sidestep No Uninstall Issue on Windows OSes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/elite-nintendo-switch-fighters-showdown-max-156-for-2024/"><u>Elite Nintendo Switch Fighters Showdown (Max 156) for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-blueprint-for-influential-video-arrangements/"><u>2024 Approved  The Blueprint for Influential Video Arrangements</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-now-you-can-also-apply-the-stranger-things-upside-down-effect-to-your-video-this-effect-combines-camera-tricks-and-video-editing-within-filmor/"><u>2024 Approved Now, You Can Also Apply the Stranger Things Upside Down Effect to Your Video! This Effect Combines Camera Tricks and Video Editing Within Filmora to Transition From the Normal World Into the Upside Down</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-erroneous-temporary-folders-in-windows-11/"><u>Troubleshooting Erroneous Temporary Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://extra-support.techidaily.com/introductory-handbook-on-video-quality-and-size-for-2024/"><u>Introductory Handbook on Video Quality and Size for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-inactive-windows-lock-screen-timer/"><u>Troubleshooting Inactive Windows Lock Screen Timer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-mastering-fb-video-marketing-with-top-20-free-editors/"><u>[Updated] In 2024, Mastering FB Video Marketing with Top 20 Free Editors</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-bluescreenview-a-step-by-step-tutorial/"><u>Exploring BlueScreenView - A Step-By-Step Tutorial</u></a></li>
</ul></div>
