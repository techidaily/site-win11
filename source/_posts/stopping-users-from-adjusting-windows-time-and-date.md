---
title: Stopping Users From Adjusting Windows Time and Date
date: 2024-07-13T10:54:40.233Z
updated: 2024-07-14T10:54:40.233Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Users From Adjusting Windows Time and Date
excerpt: This Article Describes Stopping Users From Adjusting Windows Time and Date
keywords: Prevent Windows Clock Changes,Block Windows Date Alteration,Stop Time & Date on Windows,Halt Windows Time Update,Disable PC Date Change,Prohibit Windows Time Adjustment,Inhibit DST Time Shift in Windows
thumbnail: https://thmb.techidaily.com/f5eeb9ebfa2de64a3d4ee3942e718c9f14502e6b864cfccf1cdec1e982bafc3d.jpg
---

## Stopping Users From Adjusting Windows Time and Date

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
<li><a href="https://youtube-zero.techidaily.com/ed-grassroots-video-marketing-strategies/"><u>[Updated] Grassroots Video Marketing Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-extending-shutdown-duration-in-windows-10/"><u>Advanced Strategies for Extending Shutdown Duration in Windows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/quick-and-easy-image-trimming-techniques-for-websites/"><u>Quick & Easy Image Trimming Techniques for Websites</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-fluff-remove-windows-search-images/"><u>Avoid Visual Fluff: Remove Windows Search Images</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-prodigy-strategies-for-enthusiasts-in-seo/"><u>2024 Approved  Unveiling Prodigy Strategies for Enthusiasts in SEO</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sluggish-downloads-on-windows-pcs-a-guide/"><u>Addressing Sluggish Downloads on Windows PCs: A Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-dominating-desktops-the-ultimate-approach-for-viral-videos/"><u>[New] Dominating Desktops  The Ultimate Approach for Viral Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crucial-info-every-asmr-viewer-should-absorb/"><u>[New] 2024 Approved  Crucial Info Every ASMR Viewer Should Absorb</u></a></li>
<li><a href="https://win11.techidaily.com/activate-invisible-mode-quick-turnoff-of-windows-pcs/"><u>Activate Invisible Mode: Quick Turnoff of Windows PCs</u></a></li>
<li><a href="https://youtube-data.techidaily.com/k-the-power-of-persuasion-perfecting-your-shorts-visual-hook-for-2024/"><u>Unlock the Power of Persuasion  Perfecting Your Shorts' Visual Hook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-game-bar-issues-due-to-subpar-pcs/"><u>Addressing Game Bar Issues Due to Subpar PCs</u></a></li>
<li><a href="https://win11.techidaily.com/activating-wordpad-efficiently-in-windows-computers/"><u>Activating WordPad Efficiently in Windows Computers</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-make-your-own-invitation-videos-10-free-online-tools-for-2024/"><u>Updated Make Your Own Invitation Videos 10 Free Online Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/an-intuitive-roadmap-for-installing-java-development-kit-on-windows-11/"><u>An Intuitive Roadmap for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-nokia-130-music-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Nokia 130 Music Phone and Remove Locked Screen</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2023s-best-rated-ps3-virtual-players-for-pc/"><u>[Updated] 2023'S Best-Rated PS3 Virtual Players for PC</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-excessive-cpu-usage-by-tiworkerexe-software/"><u>Alleviating Excessive CPU Usage by TiWorker.exe Software</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-accelerated-troubleshooting-in-w11-interface/"><u>Accessing Accelerated Troubleshooting in W11 Interface</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/vr-adventures-that-will-captivate-you/"><u>VR Adventures That Will Captivate You</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-download-rates-in-windows-environment/"><u>Accelerating Steam Download Rates in Windows Environment</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-motorola-edge-2023-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Motorola Edge 2023 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/editmelodiespc-top-video-and-music-pairing-software-for-2024/"><u>EditMelodiesPC  Top Video & Music Pairing Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-pristine-windows-11-workspace/"><u>Achieve a Pristine Windows 11 Workspace</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-samsung-galaxy-a23-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-steam-data-flow-combatting-sudden-drops/"><u>Amplifying Steam Data Flow: Combatting Sudden Drops</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/beyond-basic-filters-elevating-your-snapchat-game/"><u>Beyond Basic Filters  Elevating Your Snapchat Game</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-spontaneous-store-openings-on-pc/"><u>Addressing Spontaneous Store Openings on PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/pixel-perfection-top-tools-for-preserving-tweets-videos-for-2024/"><u>Pixel Perfection  Top Tools for Preserving Tweets' Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-strategies-for-bulk-character-illusions-in-tiktok-content/"><u>[Updated] Strategies for Bulk Character Illusions in TikTok Content</u></a></li>
<li><a href="https://win11.techidaily.com/automating-success-windows-audio-at-system-startup/"><u>Automating Success: Windows Audio at System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-classic-games-in-hd-best-practices-with-scummvm-and-windows-os/"><u>Advancing Classic Games in HD: Best Practices with ScummVM and Windows OS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-srt-files-accessing-on-windowsmac/"><u>2024 Approved  Unlocking SRT Files  Accessing on Windows/Mac</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-performance-swapping-outdated-windows-drivers/"><u>Accelerating Performance: Swapping Outdated Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-time-honored-directx-experiences-through-dxvk/"><u>Augmenting Time-Honored DirectX Experiences Through DXVK</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revolutionizing-podcast-titles-leading-10-ai-generators/"><u>[New] Revolutionizing Podcast Titles  Leading 10 AI Generators</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-vivo-v30-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo V30 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/masterful-mac-capturing-techniques-explored/"><u>Masterful Mac Capturing Techniques Explored</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-top-30-unique-pfps-for-a-stellar-tiktok-presence/"><u>[Updated] Top 30 Unique PFPs for a Stellar TikTok Presence</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-steps-to-create-one-click-video-reverse-effect-in-filmora/"><u>New In 2024, Steps to Create One Click Video Reverse Effect in Filmora</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/your-essential-list-of-hot-tiktok-items-now-on-amazon/"><u>Your Essential List of Hot TikTok Items Now on Amazon</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-no1-video-recorders-with-personalized-view/"><u>2024 Approved  No.1 Video Recorders with Personalized View</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-of-breed-premium-4k-camera-mounts-for-pros/"><u>Best of Breed  Premium 4K Camera Mounts for Pros</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/activate-enhanced-browser-protection-with-microsofts-defender-on-windows-11s-edge/"><u>Activate Enhanced Browser Protection with Microsoft's Defender on Windows 11'S Edge</u></a></li>
</ul></div>
