---
title: Blocking User Interference with Windows Clocks
date: 2024-07-13T11:24:25.427Z
updated: 2024-07-14T11:24:25.427Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Blocking User Interference with Windows Clocks
excerpt: This Article Describes Blocking User Interference with Windows Clocks
keywords: Block Time Changes,Secure Windows Hours,Prevent Clock Tampering,Lock Windows Calendar,Nocturnal Clock Control,Anti-Interference Windows,Untampered System Clocks
thumbnail: https://thmb.techidaily.com/bc22e110eacd1143aa0bdeeb05b2f88960a893ae5ff7866bf9fbfc4c2eddab7b.jpg
---

## Blocking User Interference with Windows Clocks

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/aster-screen-time-find-your-must-have-7-android-blockers-for-2024/"><u>[New] Master Screen Time  Find Your Must-Have 7 Android Blockers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-pitfalls-of-error-xffffff-in-print-tasks/"><u>Avoiding the Pitfalls of Error XFFFFFF in Print Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-functions-of-winservicesexe/"><u>Breaking Down the Functions of Winservices.exe</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-leading-applications-to-create-fast-motion-in-iphone/"><u>Updated In 2024, Leading Applications to Create Fast Motion in iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-winapp-and-web-browser-mastery/"><u>Blueprint for WinApp and Web Browser Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beating-blue-screens-a-guide-to-system-recovery/"><u>Beating Blue Screens: A Guide to System Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-backup-a-self-reliant-approach/"><u>Bootable Backup: A Self-Reliant Approach</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-accessing-windowsstore-folder/"><u>Breaking Down Barriers: Accessing WindowsStore Folder</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-excel-pace-on-a-windows-system/"><u>Boosting Your Excel Pace on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/banish-temp-files-quick-windows-fixes/"><u>Banish Temp Files: Quick Windows Fixes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-the-world-of-podcast-rss-formatting/"><u>2024 Approved  Navigating the World of Podcast RSS Formatting</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-art-of-drone-video-recording/"><u>The Art of Drone Video Recording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-solo-creators-path-to-dynamic-animation-art/"><u>[New] The Solo Creator’s Path to Dynamic Animation Art</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-craft-your-own-podcast-success-with-writing-tips-and-sample-templates/"><u>[Updated] In 2024, Craft Your Own Podcast Success with Writing Tips and Sample Templates</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-understanding-youtubes-content-crafting-environment/"><u>2024 Approved  Understanding YouTube's Content Crafting Environment</u></a></li>
<li><a href="https://win11.techidaily.com/banish-stubborn-epic-launcher-guide-for-win-11-users/"><u>Banish Stubborn Epic Launcher: Guide for Win 11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/efficiently-setting-up-mixer-on-macos/"><u>Efficiently Setting Up Mixer on MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-error-xc0f1103f-in-windows-11-nvidias-geforce-now/"><u>Banishing Error Xc0f1103f in Windows 11, NVIDIA's GeForce Now</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-vivo-v29e-by-fonelab-android-recover-data/"><u>Recover lost data from Vivo V29e</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-obscured-windows-11-query-engine/"><u>Awakening Obscured Windows 11 Query Engine</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-vivo-g2-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Vivo G2 to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-innovation-unleashed-exploring-s15-oled-and-bape-edition/"><u>Asus's Innovation Unleashed: Exploring S15 OLED and BAPE Edition</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-best-mac-audio-conversion-tools-expert-recommendations/"><u>New 2024 Approved Best Mac Audio Conversion Tools Expert Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-roadblocks-reinstating-access-on-windows-11-system/"><u>Avoiding Roadblocks: Reinstating Access on Windows 11 System</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-concurrent-display-registration/"><u>In 2024, Concurrent Display Registration</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://article-helps.techidaily.com/chucklebox-build-memes-free-of-charge/"><u>ChuckleBox  Build Memes Free of Charge</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-top-10-video-editing-online-makers-is-worth-your-attention/"><u>In 2024, Top 10 Video Editing Online Makers Is Worth Your Attention</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-collective-wisdom-on-easeus-products/"><u>In 2024, Collective Wisdom on EaseUS Products</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-displaying-notifications-of-phone-link-app-on-pc/"><u>Addressing Non-Displaying Notifications of Phone Link App on PC</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-ai-assistant-via-vivetool/"><u>Activating Windows AI Assistant via ViveTool</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-top-10-free-animated-logo-creators-boost-your-brand/"><u>New In 2024, Top 10 Free Animated Logo Creators Boost Your Brand</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-animated-title-makers/"><u>Top Animated Title Makers</u></a></li>
<li><a href="https://win11.techidaily.com/boltgun-performance-tips-to-resolve-on-pc-interruptions/"><u>Boltgun Performance Tips to Resolve On-PC Interruptions</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-perfecting-your-live-stream-our-picks-from-the-top-6-microphones/"><u>2024 Approved  Perfecting Your Live Stream  Our Picks From the Top 6 Microphones</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-real-time-performance-on-windows-11-task-monitor/"><u>Boosting Real-Time Performance on Windows 11 Task Monitor</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-sierra-sovereign-dvd-and-media-cutting-tools/"><u>[Updated] In 2024, Sierra Sovereign Dvd & Media Cutting Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-12-live-video-streaming-app-for-watching-and-streaming-videos/"><u>2024 Approved  12 Live Video Streaming App for Watching and Streaming Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-itel-p40-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Itel P40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-dominance-in-windows-appbrowser-arena/"><u>Blueprint for Dominance in Windows' App/Browser Arena</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-edit-podcasts-in-garageband/"><u>[New] How To Edit Podcasts in GarageBand</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-complications-with-an-efficient-in-place-windows-11-update/"><u>Avoiding Complications with an Efficient, In-Place Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-unsolicited-activation-of-windows-marketplace/"><u>Blocking Unsolicited Activation of Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-transfer-speed-averting-sudden-stops/"><u>Boosting Windows Steam Transfer Speed: Averting Sudden Stops</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-digital-discourse-with-windows-11/"><u>Begin Your Digital Discourse with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/boost-user-experience-add-portable-menus-on-win11plus/"><u>Boost User Experience: Add Portable Menus on Win11+</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-is-insta-snap-verification-worth-it-for-2024/"><u>[Updated] Is Insta-Snap Verification Worth It for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/top-10-talking-photo-online-tools-you-have-to-try-for-2024/"><u>Top 10 Talking Photo Online Tools You Have To Try for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-lava-storm-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Lava Storm 5G</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>