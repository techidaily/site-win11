---
title: Thwarting Windows Users From Altering System Time
date: 2024-07-13T10:47:49.223Z
updated: 2024-07-14T10:47:49.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Thwarting Windows Users From Altering System Time
excerpt: This Article Describes Thwarting Windows Users From Altering System Time
keywords: Stop Time Change on Win PCs,Prevent Windows Clock Adjustment,Halt User Time Manipulation (Windows),Block System Time in Windows,Secure Windows Time Settings,Thwart Clock Changes Windows,Protect Windows Time Accuracy
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Thwarting Windows Users From Altering System Time

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
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-perfect-virtual-presentations-using-video-filters-on-zoom/"><u>2024 Approved  Perfect Virtual Presentations  Using Video Filters on Zoom</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-clutter-pro-tips-to-adhere-sticky-notes-on-w11w10/"><u>Avoid Clutter: Pro Tips to Adhere Sticky Notes on W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-best-performing-8-recording-software-picks/"><u>[New] 2024 Approved  Best Performing 8 Recording Software Picks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-step-by-step-guide-to-framing-youtube-content-for-free/"><u>[New] Step-By-Step Guide to Framing YouTube Content for Free</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-advanced-techniques-for-quality-audio-on-ipads/"><u>[New] 2024 Approved  Advanced Techniques for Quality Audio on iPads</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-top-mp4-to-fb-transcoder/"><u>[New] In 2024, Top MP4-to-FB Transcoder</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-malfunctions-in-windows-batch-file-systems/"><u>Addressing Malfunctions in Windows Batch File Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mobile-and-desktop-no-cost-magnifier-toolkit/"><u>In 2024, Mobile & Desktop  No-Cost Magnifier Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveil-windows-xp-professional-for-video-production/"><u>Unveil Windows XP Professional for Video Production</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-mouse-dynamics-for-a-more-natural-response-in-win-1011/"><u>Adjusting Mouse Dynamics for a More Natural Response in Win 10/11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-harmonyhack-expert-vocal-pitch-shifting-and-editing-program-of-the-year/"><u>New HarmonyHack Expert Vocal Pitch-Shifting and Editing Program of the Year</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-crafting-professional-gamers-content-with-obs-recordings/"><u>[New] In 2024, Crafting Professional Gamers' Content with OBS Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-window-settings-unseen-toolbar-configurations/"><u>Advanced Window Settings: Unseen Toolbar Configurations</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-crafting-the-perfect-soundtrack-for-your-vimeo-content/"><u>In 2024, Crafting the Perfect Soundtrack for Your Vimeo Content</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-locate-video-game-audio-cues/"><u>New Locate Video Game Audio Cues</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-tracing-gaps-in-your-instagram-circle/"><u>[New] In 2024, Tracing Gaps in Your Instagram Circle</u></a></li>
<li><a href="https://win11.techidaily.com/app-and-browser-domination-on-windows-os/"><u>App & Browser Domination on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-in-the-ms-store-a-step-by-step-guide/"><u>Accelerating Downloads in the MS Store - A Step-by-Step Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-sjcam-sj7-star-action-camera-complete-review/"><u>[Updated] SJCam SJ7 Star Action Camera Complete Review</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-apple-iphone-15-pro-max-in-lost-mode-drfone-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock Apple iPhone 15 Pro Max in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-ultimate-vote-players-best-political-game-reviews/"><u>[New] 2024 Approved  Ultimate Vote-Players  Best Political Game Reviews</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-voiceverse-review-audio-deep-dive/"><u>[Updated] VoiceVerse Review  Audio Deep Dive</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-portaudio-hiccup-on-windows-11-and-11/"><u>Addressing Audacity’s PortAudio Hiccup on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-new-in-youtube-money-regulations/"><u>What's New in YouTube Money Regulations</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-hd-disruptions-clear-screening-challenges-in-fir-safari-chrome/"><u>2024 Approved  Navigating HD Disruptions  Clear Screening Challenges in Fir, Safari, Chrome</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-lava-yuva-2-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Lava Yuva 2 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/leveraging-twitters-video-capabilities-for-instagram-audience-for-2024/"><u>Leveraging Twitter's Video Capabilities for Instagram Audience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-error-unauthorized-file-reading-in-win11/"><u>Addressing Steam Error: Unauthorized File Reading in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-navigating-instas-archive-maze-for-optimal-results/"><u>[New] 2024 Approved  Navigating Insta’s Archive Maze for Optimal Results</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-age-old-directx-experience-via-dxvk-compatibility/"><u>Amplifying Age-Old DirectX Experience via DXVK Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/smart-solutions-for-gathering-visual-assets/"><u>Smart Solutions for Gathering Visual Assets</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-are-you-looking-for-trustworthy-gif-converters-to-use-gif-images-across-various-platforms-find-out-about-reliable-and-authentic-gif-converters/"><u>2024 Approved Are You Looking for Trustworthy GIF Converters to Use GIF Images Across Various Platforms? Find Out About Reliable and Authentic GIF Converters that You Can Easily Use for WMV to GIF Conversion Anytime You Want</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/do-you-want-to-know-how-to-convert-youtube-sbv-subtitles-to-srt-format-here-is-an-ultimate-guide-about-it/"><u>Do You Want to Know How to Convert YouTube SBV Subtitles to SRT Format? Here Is an Ultimate Guide About It</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-premiere-pro-template-guide-no-cost/"><u>2024 Approved  Ultimate Premiere Pro Template Guide - No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-expert-review-of-ios-screenshot-software/"><u>[Updated] Expert Review of iOS Screenshot Software</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/activation-verification-methods-for-windows-11/"><u>Activation Verification Methods for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-media-error-your-input-not-opened-by-vlc/"><u>Addressing Media Error: Your Input Not Opened by VLC</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-concealment-for-windows-11-task-view-icon/"><u>Advanced Concealment for Windows 11 Task View Icon</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How can I get more stardust in pokemon go On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-complete-youtube-editors-toolkit-for-post-publish-adjustments/"><u>In 2024, The Complete YouTube Editor's Toolkit for Post-Publish Adjustments</u></a></li>
</ul></div>
