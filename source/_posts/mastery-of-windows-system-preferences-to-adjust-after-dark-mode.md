---
title: Mastery of Windows System Preferences to Adjust After Dark Mode
date: 2024-07-13T09:51:26.094Z
updated: 2024-07-14T09:51:26.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Windows System Preferences to Adjust After Dark Mode
excerpt: This Article Describes Mastery of Windows System Preferences to Adjust After Dark Mode
keywords: Dark Mode Settings,Windows PC Configurations,Night Mode Systems,OS Preference Tweaks,Dusk Display Controls,System Bias Adjustment,Dark Interface Options
thumbnail: https://thmb.techidaily.com/6e815c1b64efb14276b71fc721777a9cc6b2edabdceffdbe6557dc25c31661ee.jpg
---

## Mastery of Windows System Preferences to Adjust After Dark Mode

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://win11.techidaily.com/guide-to-reactivating-stalled-windows-batch-processes/"><u>Guide to Reactivating Stalled Windows Batch Processes</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-through-edges-webview2-controls/"><u>Optimizing System Resources Through Edge's WebView2 Controls</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-iomap64-system-crashes-and-bsod-quickly-on-pcs/"><u>Resolve IOMap64 System Crashes and BSoD Quickly on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/taming-setting-turmoil-a-pubg-guide-for-pc-users/"><u>Taming Setting Turmoil: A PUBG Guide for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-sound-recording-on-windows-11/"><u>Streamline Your Sound Recording on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-essential-windows-shorthand/"><u>Streamline Your Workflow: Essential Windows Shorthand</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-motorola-edge-40-neo-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Motorola Edge 40 Neo Phone with Broken Screen</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-end-task-control-panel-in-windows-11-ui/"><u>Mastering the End Task Control Panel in Windows 11 UI</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-instagram-reels-production-process/"><u>2024 Approved  Step-by-Step Instagram Reels Production Process</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-strategies-for-finding-a-misplaced-pin/"><u>Unlock Windows 11 - Strategies for Finding a Misplaced PIN</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>How to Change Location On Facebook Dating for your Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-techniques-for-net-healing-in-windows-max-156/"><u>Top 5 Techniques for .NET Healing in Windows (Max 156)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-top-8-safe-online-collaboration-software-for-businesses/"><u>[Updated] In 2024, Top 8 Safe Online Collaboration Software for Businesses</u></a></li>
<li><a href="https://win11.techidaily.com/guide-recovering-invisible-bluetooth-in-device-manager/"><u>Guide: Recovering Invisible Bluetooth in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-go-no-net-with-your-new-os-win11/"><u>How to Go No Net With Your New OS, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/taming-erratic-errors-from-wins-protection-suite/"><u>Taming Erratic Errors From WINS Protection Suite</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-professional-tips-integrating-closed-captions-with-ease-on-youtube/"><u>[New] Professional Tips  Integrating Closed Captions with Ease on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/learn-how-to-turn-off-games-for-w11-suggestions/"><u>Learn How To Turn Off Games for W11 Suggestions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-creating-clip-sensations-tiktoks-viral-guide/"><u>[Updated] Creating Clip Sensations  TikTok's Viral Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-unresponsive-keyboard-issue-x80049dd3-in-windows-11/"><u>Overcoming the Unresponsive Keyboard Issue - X80049DD3 in Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-2023s-top-rated-facebook-live-viewing-software/"><u>[Updated] In 2024, 2023'S Top-Rated Facebook Live Viewing Software</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-overcoming-forbidden-errors/"><u>Mastering the Art of Overcoming Forbidden Errors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/innovative-naming-solutions-for-channels-for-2024/"><u>Innovative Naming Solutions for Channels for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-spectral-synergy-using-color-theories-effectively-for-2024/"><u>[Updated] Spectral Synergy  Using Color Theories Effectively for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-fast-techniques-to-restructure-your-youtube-sequence/"><u>In 2024, Fast Techniques to Restructure Your YouTube Sequence</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/androids-best-virtual-worlds-top-15-experiences-for-2024/"><u>Android's Best Virtual Worlds  Top 15 Experiences for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-image-conversion-in-windows-pc/"><u>Mastering the Art of CR2 Image Conversion in Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-transformation-mp3-files-to-windows-compatible-audio-cds-with-imgburn/"><u>Immediate Transformation: MP3 Files to Windows-Compatible Audio CDs with ImgBurn</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-recmaster-screen-recorder-review/"><u>[Updated] 2024 Approved  Recmaster Screen Recorder Review</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-from-facebook-to-the-friends-inbox-sharing-videos-through-whatsapp/"><u>[New] 2024 Approved  From Facebook to the Friend's Inbox  Sharing Videos Through WhatsApp</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-steam-sync-errors-in-windows/"><u>Remedying Steam Sync Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-no-hypervisor-detection-in-sandbox-mode/"><u>How to Address No Hypervisor Detection in Sandbox Mode</u></a></li>
<li><a href="https://win11.techidaily.com/opening-your-canvas-microsoft-paint-on-windows-11/"><u>Opening Your Canvas: Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-6-key-steps-to-discovering-the-identity-of-your-pc-window-edition/"><u>The 6 Key Steps to Discovering the Identity of Your PC, Window Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tailored-strategies-for-free-clock-usage-optimization/"><u>In 2024, Tailored Strategies for FREE Clock Usage Optimization</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-transitioning-tweets-into-facebook-visibility-for-2024/"><u>[New] Transitioning Tweets Into Facebook Visibility for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-dangers-hacked-fingerprints-on-windows-pcs/"><u>Unlocking Dangers: Hacked Fingerprints on Windows PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-realme-c55-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Realme C55 Through Google Earth?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-problem-zerosevennine/"><u>Overcoming System Problem ZeroSevenNine</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-captures-snip-tool-versus-prtsc/"><u>Mastering Windows Captures: Snip Tool versus PrtSc</u></a></li>
<li><a href="https://win11.techidaily.com/preempting-vagrant-start-issues-for-vms-on-win11os/"><u>Preempting Vagrant Start Issues for VMs on Win11OS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-studio-study-xvideo-studio-insights/"><u>[Updated] Comprehensive Studio Study  XVideo Studio Insights</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-pro-audio-refinement-on-windows-a-compendium-of-leading-tools-for-quieter-recording-environments-for-2024/"><u>Updated Pro Audio Refinement on Windows A Compendium of Leading Tools for Quieter Recording Environments for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11.</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-does-buying-youtube-likes-help-boost-your-channel/"><u>2024 Approved  Does Buying YouTube Likes Help Boost Your Channel?</u></a></li>
<li><a href="https://extra-information.techidaily.com/maximized-speed-the-prime-10-choices-of-srt-upgrades-for-pcs-and-macs/"><u>Maximized Speed  The Prime 10 Choices of SRT Upgrades for PCs & Macs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overwatch-2s-missing-graphics-driver-error/"><u>Fixing Overwatch 2'S Missing Graphics Driver Error</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-windows-11-mailcalendar/"><u>Quick Guide: Resetting Windows 11 Mail/Calendar</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-free-video-editing-options-10-windows-movie-maker-alternatives/"><u>Updated In 2024, Free Video Editing Options 10 Windows Movie Maker Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insight-navigating-newly-opened-window-folders/"><u>Quick Insight: Navigating Newly Opened Window Folders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-perfecting-your-recordings-using-nvidia-recorder/"><u>[Updated] In 2024, Perfecting Your Recordings  Using NVIDIA Recorder</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-realme-narzo-n55-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Realme Narzo N55 FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-volume-settings-after-hiccups-in-windows-10/"><u>Restoring Volume Settings After Hiccups in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-recovering-without-admin-creds/"><u>Mastering Windows 11: Recovering without Admin Creds</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-create-ai-videos-using-synthesia-avatar-and-voices/"><u>New In 2024, Create AI Videos Using Synthesia Avatar and Voices</u></a></li>
</ul></div>
