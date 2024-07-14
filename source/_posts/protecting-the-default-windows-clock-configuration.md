---
title: Protecting the Default Windows Clock Configuration
date: 2024-07-13T09:45:21.153Z
updated: 2024-07-14T09:45:21.153Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Protecting the Default Windows Clock Configuration
excerpt: This Article Describes Protecting the Default Windows Clock Configuration
keywords: Win Clock Security,Safe Time Settings,Default Time Protection,OS Clock Safeguard,Preventing Time Changes,Secure Windows Time,Preserve Windows Hours
thumbnail: https://thmb.techidaily.com/48b583faa31b393aa904516c2278bd0e1546bcda1fa4122648e108e1ee1f91de.jpg
---

## Protecting the Default Windows Clock Configuration

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/updated-integrated-activity-evaluation-guide/"><u>[Updated] Integrated Activity Evaluation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-uninstalling-apps-on-windows-11/"><u>Efficiently Uninstalling Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/sound-sculpture-shaping-your-youtube-audio-experience-for-2024/"><u>Sound Sculpture  Shaping Your YouTube Audio Experience for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-humor-potential-with-kapwings-designer/"><u>2024 Approved  Unlock Humor Potential with Kapwing’s Designer</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://extra-hints.techidaily.com/effortless-background-erasure-in-digital-photography/"><u>Effortless Background Erasure in Digital Photography</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-moto-g24-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Motorola Moto G24 won’t play MKV movies</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigating-netflixs-pace-adjustments-for-2024/"><u>Navigating Netflix's Pace Adjustments for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionizing-the-music-creation-process-through-magix-mentor-x/"><u>[New] Revolutionizing the Music Creation Process Through Magix Mentor X</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-assembling-impactful-insta-colleagues/"><u>[Updated] Step-by-Step  Assembling Impactful Insta Colleagues</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-zipping-with-command-prompt-step-by-step/"><u>Advanced Zipping with Command Prompt, Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-realme-c53-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Realme C53 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-k11x-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo K11x to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/capturing-every-detail-best-practices-for-hp-laptop-recording/"><u>Capturing Every Detail  Best Practices for HP Laptop Recording</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows.</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-pathway-to-preserving-instagram-content-via-desktop-platforms/"><u>In 2024, The Pathway to Preserving Instagram Content via Desktop Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-maintenance-tips-for-setting-active-windows-11-times/"><u>Navigating System Maintenance: Tips for Setting Active Windows 11 Times</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-insiders-look-at-sharing-links-on-ig-platform-for-2024/"><u>The Insider's Look at Sharing Links on IG Platform for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-rated-switch-capture-cards-revealed/"><u>Top-Rated Switch Capture Cards Revealed</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-harmonious-guidelines-instagram-and-intellectual-property/"><u>2024 Approved  Harmonious Guidelines  Instagram & Intellectual Property</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-open-world-originals-titles-similar-to-gta-v/"><u>[Updated] 2024 Approved  Open World Originals  Titles Similar To GTA V</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-sewn-sequences-learning-loom-screen-casting-for-2024/"><u>[Updated] Sewn Sequences  Learning Loom Screen Casting for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-subtitles-the-ultimate-guide-to-free-tools/"><u>Mastering Subtitles  The Ultimate Guide to FREE Tools</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-seamless-techniques-to-share-your-screen-on-google-meet/"><u>[New] In 2024, Seamless Techniques to Share Your Screen on Google Meet</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-learn-to-prevent-persistent-commercials-in-digital-platforms/"><u>[New] 2024 Approved  Learn to Prevent Persistent Commercials in Digital Platforms</u></a></li>
</ul></div>
