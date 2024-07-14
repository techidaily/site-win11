---
title: Activate/Deactivate Window 11 Search Lights
date: 2024-07-13T11:28:48.370Z
updated: 2024-07-14T11:28:48.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate/Deactivate Window 11 Search Lights
excerpt: This Article Describes Activate/Deactivate Window 11 Search Lights
keywords: Windows 11 Light Switch On/Off,Activate Window L11 Search Beam,Deactivate Windows L11 Scope,Enable/Disable Win11 Scope Light,Manage Windows 11 Search Illumination,Toggle Windows 11 Search Radiance,Control Win11 L11 Search Glow
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## Activate/Deactivate Window 11 Search Lights

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/beyond-manual-inputs-embracing-ai-in-windows-operations/"><u>Beyond Manual Inputs: Embracing AI in Windows Operations</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-discover-the-top-rated-youtube-to-mp3-converters-features-pros-and-cons/"><u>New 2024 Approved Discover the Top-Rated YouTube to MP3 Converters Features, Pros, and Cons</u></a></li>
<li><a href="https://win11.techidaily.com/blending-email-services-adding-gmail-to-the-outlook-app-in-windows/"><u>Blending Email Services: Adding Gmail to the Outlook App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-offer-best-price-keys-fan-unlocked-for-all-year-lifetime-windows-11/"><u>Black Friday Offer: Best Price Keys Fan Unlocked for All-Year Lifetime Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bare-bones-pc-boasts-bulky-but-lackluster-loops/"><u>Bare-Bones PC Boasts Bulky, but Lackluster Loops</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocker-less-protection-4-effective-methods-for-win-users/"><u>BitLocker-Less Protection: 4 Effective Methods for Win Users</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-15-pro-max-using-icloud-website-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 15 Pro Max using icloud website</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakdown-is-windows-hello-still-reliable/"><u>Biometric Breakdown: Is Windows Hello Still Reliable?</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-frozen-mouse-menu-stasis-on-pc/"><u>Break Free From Frozen Mouse Menu Stasis on PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-photo-pinnacle-insta-coverage-excellence-on-ios-and-android/"><u>[New] Photo Pinnacle  Insta Coverage Excellence on iOS & Android</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-windows-11-login-blunders/"><u>Avoiding Common Windows 11 Login Blunders</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-unleash-the-chaos-the-best-free-online-glitch-effect-makers/"><u>New 2024 Approved Unleash the Chaos The Best Free Online Glitch Effect Makers</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-media-player-for-a-streamlined-start/"><u>Activating Windows Media Player for a Streamlined Start</u></a></li>
<li><a href="https://win11.techidaily.com/best-way-to-wrap-windows-store-games-for-yule/"><u>Best Way to Wrap Windows Store Games for Yule</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-discover-the-best-free-and-paid-3d-animation-programs-for-artists/"><u>In 2024, Discover the Best Free and Paid 3D Animation Programs for Artists</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/best-6-to-do-list-programs-tailored-for-windows-11-enthusiasts/"><u>Best 6 To-Do List Programs Tailored for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://driver-install.techidaily.com/beat-the-blues-troubleshoot-m-track-issues/"><u>Beat the Blues: Troubleshoot M-Track Issues</u></a></li>
<li><a href="https://win11.techidaily.com/boost-notability-of-your-scribbles-with-strategic-sticky-note-placement-in-win-os/"><u>Boost Notability of Your Scribbles with Strategic Sticky Note Placement in Win OS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-effortless-mp4-conversion-from-facebook-hd-content-all-for-free/"><u>In 2024, Effortless MP4 Conversion From Facebook HD Content – All For Free</u></a></li>
<li><a href="https://win11.techidaily.com/boost-display-output-clarity-with-high-dpi-adjustments/"><u>Boost Display Output Clarity with High-DPI Adjustments</u></a></li>
<li><a href="https://extra-information.techidaily.com/solving-iphone-xs-identity-crisis-fixing-face-id-failures/"><u>Solving iPhone X's Identity Crisis  Fixing Face ID Failures</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-graphics-techniques-in-edge-app-guard/"><u>Advanced Graphics Techniques in Edge App Guard</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-media-integration-adding-online-yt-videos-to-ppts-for-2024/"><u>Mastering Media Integration  Adding Online YT Videos to PPTs for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-complete-analysis-triangulating-life-with-samsung-vr-for-2024/"><u>[New] Complete Analysis  Triangulating Life with Samsung VR for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-smart-note-management-for-windows/"><u>Avoiding Clutter: Smart Note Management for Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-enhance-your-footage-best-video-brightening-apps/"><u>2024 Approved Enhance Your Footage Best Video Brightening Apps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-advanced-tips-for-blending-modes-in-vfx/"><u>[New] In 2024, Advanced Tips for Blending Modes in VFX</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-system-uncrashing-win1011s-corrupt-bin-error/"><u>Beating the System: Uncrashing Win10/11's Corrupt Bin Error</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-cut-to-the-chase-convert-fb-vids-into-mp3s/"><u>[Updated] In 2024, Cut-to-the-Chase  Convert FB Vids Into MP3s</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-barriers-to-customizing-windows-11-apps/"><u>Breaking Down the Barriers to Customizing Windows 11 Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/first-steps-in-av1-coders-for-2024/"><u>First Steps in AV1 Coders for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-zen-of-zoom-talk-top-strategies-for-smooth-virtual-dialogue/"><u>2024 Approved  The Zen of Zoom Talk  Top Strategies for Smooth Virtual Dialogue</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-game-access-blocks-fixing-unreachable-errors/"><u>Avoiding Game Access Blocks: Fixing Unreachable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win1011-graphics-power-the-ultimate-guide-to-vram/"><u>Boosting Win10/11 Graphics Power: The Ultimate Guide to VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-stability-fixing-high-memory-usage-of-services/"><u>Boosting System Stability: Fixing High Memory Usage of Services</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/3-ways-to-export-contacts-from-apple-iphone-8-plus-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>3 Ways to Export Contacts from Apple iPhone 8 Plus to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-depth-analysis-of-green-screen-technology-in-kinemaster/"><u>In 2024, In-Depth Analysis of Green Screen Technology in Kinemaster</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-unveiling-androids-7-best-rated-voice-transformation-software/"><u>New 2024 Approved Unveiling Androids 7 Best-Rated Voice Transformation Software</u></a></li>
<li><a href="https://win11.techidaily.com/bigger-capacity-but-lagging-in-little-pcs-mp60/"><u>Bigger Capacity but Lagging in Little PCs (MP60)</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-utilities-convert-any-media-file/"><u>Best Windows Utilities Convert Any Media File</u></a></li>
<li><a href="https://win11.techidaily.com/bargain-bonanza-black-friday-612-for-lifelong-win10-life/"><u>Bargain Bonanza: Black Friday - $6.12 for Lifelong Win10 Life</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Infinix GT 10 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-exploring-instagrams-hidden-gems-accessing-no-cost-filters/"><u>[Updated] Exploring Instagram's Hidden Gems  Accessing No-Cost Filters</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-mobile-sound-for-windows-pc-use-case/"><u>Boosting Mobile Sound for Windows PC Use Case</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-of-windows-modern-standby-problems/"><u>Beneath the Surface of Windows Modern Standby Problems</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>