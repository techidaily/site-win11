---
title: 4 Keys to Reviving a Device Stuck in Night Setting
date: 2024-07-13T11:11:00.269Z
updated: 2024-07-14T11:11:00.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Keys to Reviving a Device Stuck in Night Setting
excerpt: This Article Describes 4 Keys to Reviving a Device Stuck in Night Setting
keywords: Night Mode Recovery,Fixing Device Dusk Halt,Unstick Devices at Nite,Restart Locked Settings,Revive Night Display,Reverse Dark Screen,Reactivate Nocturnal Mode
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## 4 Keys to Reviving a Device Stuck in Night Setting

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://extra-tips.techidaily.com/new-boxing-brilliance-versus-broadband-bonanza/"><u>[New] Boxing Brilliance versus Broadband Bonanza</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-motorola-moto-g13-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Motorola Moto G13 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-ways-to-track-apple-iphone-6s-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>3 Ways to Track Apple iPhone 6s without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://extra-information.techidaily.com/illustrate-instantly-image-to-illustration-on-any-device/"><u>Illustrate Instantly  Image to Illustration on Any Device</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps/"><u>[New] Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/quickening-boot-process-windows-11-timeout-reduction-guide/"><u>Quickening Boot Process: Windows 11 Timeout Reduction Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-samsung-galaxy-a24-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Samsung Galaxy A24 Phone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/a-closer-look-at-tiktoks-hot-reaction-videos/"><u>A Closer Look at TikTok's Hot Reaction Videos</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-new-world-of-windows-11-avoidance-guide-top-8/"><u>Navigating the New World of Windows 11: Avoidance Guide (Top 8)</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-removing-windows-defender-error-0x80004004/"><u>Understanding & Removing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-instagrams-secrets-for-creating-must-watch-unboxings/"><u>2024 Approved  Instagram's Secrets for Creating Must-Watch Unboxings</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-context-menu-choices-with-automatic-patch-information/"><u>Enriching Context Menu Choices with Automatic Patch Information</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-window-preview-failures-in-win-810/"><u>Addressing Window Preview Failures in Win 8/10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/elite-watchlist-top-10-advanced-video-capture-programs/"><u>Elite Watchlist  Top 10 Advanced Video Capture Programs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-secure-growth-of-your-tiktok-fanbase/"><u>2024 Approved  Secure Growth of Your TikTok Fanbase</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719368082467-switch-off-windows-11-defender-firewall-now/"><u>Switch Off Windows 11 Defender Firewall Now</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-bestiary-of-top-ps2-emulators-running-on-iphones/"><u>[Updated] In 2024, Bestiary of Top PS2 Emulators Running on iPhones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dji-aerial-palette-changes-get-20-free-with-pay-options-available/"><u>DJI Aerial Palette Changes - Get 20 FREE with Pay Options Available</u></a></li>
<li><a href="https://win11.techidaily.com/fast-setupuninstall-bings-ai-on-win-11-taskbar/"><u>Fast Setup/Uninstall: Bing's AI on Win 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-tpm-deactivation-for-modern-windows-users/"><u>Triumph in TPM Deactivation for Modern Windows Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-unleash-cinematic-quality-top-rated-1080p-video-editing-tools/"><u>In 2024, Unleash Cinematic Quality Top-Rated 1080P Video Editing Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-optimizing-your-facebook-budget-high-roi-animated-ad-best-practices/"><u>2024 Approved  Optimizing Your Facebook Budget  High-ROI Animated Ad Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-precision-editing-on-inshot-mastering-the-art-of-transitioning/"><u>2024 Approved  Precision Editing on Inshot  Mastering the Art of Transitioning</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-unlock-tiktok-potential-the-best-analytic-tools-of-the-year/"><u>[New] Unlock TikTok Potential  The Best Analytic Tools of the Year</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/managing-your-digital-life-restarting-apps-in-windows-11/"><u>Managing Your Digital Life: Restarting Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-no-support-errors-5-effective-steps/"><u>Navigating Windows No-Support Errors: 5 Effective Steps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-writable-registry-for-hidden-themes/"><u>Mastering Windows 11' Writable Registry for Hidden Themes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-cutting-edge-computers-optimal-machines-for-media-creation/"><u>2024 Approved  Cutting-Edge Computers  Optimal Machines for Media Creation</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-for-managing-users-in-command-prompt/"><u>Essential Tools for Managing Users in Command Prompt</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-retrace-mechanic-setup/"><u>2024 Approved  Retrace Mechanic Setup</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-infusing-new-life-into-old-images-with-instagram-magic/"><u>[Updated] Infusing New Life Into Old Images with Instagram Magic</u></a></li>
<li><a href="https://win11.techidaily.com/five-methods-for-protecting-your-pc-avoiding-bitlocker/"><u>Five Methods for Protecting Your PC: Avoiding BitLocker</u></a></li>
<li><a href="https://audio-editing.techidaily.com/step-by-step-guide-to-audio-keyframing-with-adobe-premiere-pro-on-apple-devices-2023-edition/"><u>Step-by-Step Guide to Audio Keyframing with Adobe Premiere Pro on Apple Devices, 2023 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-precision-crafting-win11-self-extractables/"><u>The Path to Precision: Crafting Win11 Self-Extractables</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-errors-in-windows-update-xc004f050/"><u>Bypassing Common Errors in Windows Update Xc004f050</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-the-ultimate-mac-video-editor-how-to-produce-a-pro-quality-movie/"><u>New In 2024, The Ultimate Mac Video Editor How to Produce a Pro-Quality Movie</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-discovering-the-optimal-ways-to-enrich-your-environment-with-muted-melodies-for-2024/"><u>New Discovering the Optimal Ways to Enrich Your Environment with Muted Melodies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-extracting-audio-from-vimeo-content-easily/"><u>2024 Approved  Extracting Audio From Vimeo Content Easily</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-dominate-your-digital-space-with-these-10-follower-boosting-hacks/"><u>[New] In 2024, Dominate Your Digital Space with These 10 Follower-Boosting Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-enable-startup-diagnostics/"><u>A Step-by-Step Guide to Enable Startup Diagnostics</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-the-authorization-interface-in-windows-11/"><u>Pathways to the Authorization Interface in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uninstall-simplified-top-methods-for-windows-11-users-111-chars/"><u>Uninstall Simplified: Top Methods for Windows 11 Users (111 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Huawei Nova Y71? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-infinix-hot-40i-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Infinix Hot 40i Location Settings | Dr.fone</u></a></li>
</ul></div>
