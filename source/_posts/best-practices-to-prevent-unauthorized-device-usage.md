---
title: Best Practices to Prevent Unauthorized Device Usage
date: 2024-07-13T11:28:52.835Z
updated: 2024-07-14T11:28:52.835Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Best Practices to Prevent Unauthorized Device Usage
excerpt: This Article Describes Best Practices to Prevent Unauthorized Device Usage
keywords: UNAUTHORIZED DEVICE HACK,PREVENTING UNLICENSED OPERATION,DATA SECURITY CONTROL,INTEGRITY MAINTENANCE,AUTHORIZED USAGE REGULATE,PROACTIVE RISK MANAGEMENT,SAFE DEVICE PRACTICES
thumbnail: https://thmb.techidaily.com/7ac9924553405319fc34adce73b50933080c4e0b7ab947e877cf6636c606146d.jpg
---

## Best Practices to Prevent Unauthorized Device Usage

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://extra-tips.techidaily.com/beginning-with-adobe-audition-the-fading-start/"><u>Beginning with Adobe Audition  The Fading Start</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-is-the-best-mp4-cutter-for-youtuber-on-mac-for-2024/"><u>What Is the Best MP4 Cutter for YouTuber on Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bluetooth-woes-try-these-9-fixes-for-a-seamless-link-in-windows-11/"><u>Bluetooth Woes? Try These 9 Fixes for a Seamless Link in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-lava-storm-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win1011-graphics-power-the-ultimate-guide-to-vram/"><u>Boosting Win10/11 Graphics Power: The Ultimate Guide to VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-barriers-to-customizing-windows-11-apps/"><u>Breaking Down the Barriers to Customizing Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-unleash-your-creativity-best-mobile-video-editing-apps-for-ios-and-android/"><u>2024 Approved Unleash Your Creativity Best Mobile Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-graphics-techniques-in-edge-app-guard/"><u>Advanced Graphics Techniques in Edge App Guard</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-windows-overload-7-ways-to-fix-too-many-requests-error/"><u>Beating Back Window's Overload: 7 Ways to Fix Too Many Requests Error</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-essential-enhancements-for-a-superstar-stardew-fan/"><u>[New] 2024 Approved  The Essential Enhancements for a Superstar Stardew Fan</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-experts-guide-to-effective-webinars-for-2024/"><u>[New] Expert's Guide to Effective Webinars for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-utilities-convert-any-media-file/"><u>Best Windows Utilities Convert Any Media File</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-offer-best-price-keys-fan-unlocked-for-all-year-lifetime-windows-11/"><u>Black Friday Offer: Best Price Keys Fan Unlocked for All-Year Lifetime Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-high-definition-screenshots-best-apps-for-w11w10-users/"><u>[Updated] 2024 Approved  High-Definition Screenshots  Best Apps for W11/W10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/blending-email-services-adding-gmail-to-the-outlook-app-in-windows/"><u>Blending Email Services: Adding Gmail to the Outlook App in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-poco-m6-5g-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Poco M6 5G Phone Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/best-way-to-wrap-windows-store-games-for-yule/"><u>Best Way to Wrap Windows Store Games for Yule</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unravel-the-power-of-live-streaming-with-obs-on-youtube-and-twitch/"><u>Unravel the Power of Live Streaming with OBS on YouTube & Twitch</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-resolve-chromes-video-playback-woes/"><u>[New] In 2024, Resolve  Chrome's Video Playback Woes</u></a></li>
<li><a href="https://win11.techidaily.com/boost-notability-of-your-scribbles-with-strategic-sticky-note-placement-in-win-os/"><u>Boost Notability of Your Scribbles with Strategic Sticky Note Placement in Win OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-quick-guide-merging-igtv-with-instagram-stories/"><u>In 2024, Quick Guide  Merging IGTV with Instagram Stories</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-elevating-the-end-scene-in-youtube-productions/"><u>[New] Elevating the End Scene in YouTube Productions</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-captioning-videos-efficiently-on-vimeo-platform/"><u>[Updated] Captioning Videos Efficiently on Vimeo Platform</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reformatting-large-win11-screen/"><u>Reformatting Large Win11 Screen</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-by-step-wirecast-livestream-on-youtube/"><u>In 2024, Step-by-Step  WireCast Livestream on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-playchoice-pondering-over-dacast/"><u>[New] PlayChoice  Pondering Over DaCast</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-of-windows-modern-standby-problems/"><u>Beneath the Surface of Windows Modern Standby Problems</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-smart-note-management-for-windows/"><u>Avoiding Clutter: Smart Note Management for Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-media-extractor-mp3-focus-for-2024/"><u>[Updated] Facebook Media Extractor – MP3 Focus for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-stability-fixing-high-memory-usage-of-services/"><u>Boosting System Stability: Fixing High Memory Usage of Services</u></a></li>
<li><a href="https://win11.techidaily.com/activatedeactivate-window-11-search-lights/"><u>Activate/Deactivate Window 11 Search Lights</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocker-less-protection-4-effective-methods-for-win-users/"><u>BitLocker-Less Protection: 4 Effective Methods for Win Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-cinema-scores-in-imovie/"><u>Crafting Cinema Scores in iMovie</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unlock-creative-potential-in-filmmaking-with-filmora-answers/"><u>[New] Unlock Creative Potential in Filmmaking with Filmora Answers</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-7-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-game-access-blocks-fixing-unreachable-errors/"><u>Avoiding Game Access Blocks: Fixing Unreachable Errors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-mastering-youtube-to-mp3-conversion-essential-tool-reviews/"><u>New Mastering YouTube to MP3 Conversion Essential Tool Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/boost-display-output-clarity-with-high-dpi-adjustments/"><u>Boost Display Output Clarity with High-DPI Adjustments</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-6-websites-to-free-download-motivational-video-footage/"><u>In 2024, 6 Websites to Free Download Motivational Video Footage</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakdown-is-windows-hello-still-reliable/"><u>Biometric Breakdown: Is Windows Hello Still Reliable?</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-system-uncrashing-win1011s-corrupt-bin-error/"><u>Beating the System: Uncrashing Win10/11's Corrupt Bin Error</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-frozen-mouse-menu-stasis-on-pc/"><u>Break Free From Frozen Mouse Menu Stasis on PC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-capture-and-record-a-new-era-of-iphoneipad-recording/"><u>[Updated] Capture & Record  A New Era of iPhone/iPad Recording</u></a></li>
<li><a href="https://win11.techidaily.com/bigger-capacity-but-lagging-in-little-pcs-mp60/"><u>Bigger Capacity but Lagging in Little PCs (MP60)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-understanding-and-implementing-discord-text-styles/"><u>[New] Understanding & Implementing Discord Text Styles</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-captivatescreen-scrutiny-platform/"><u>[Updated] In 2024, CaptivateScreen Scrutiny Platform</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-huawei-p60-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Huawei P60 to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/best-6-to-do-list-programs-tailored-for-windows-11-enthusiasts/"><u>Best 6 To-Do List Programs Tailored for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-accessibility-of-grandparents-pre-ultimate-pcs/"><u>Boosting Accessibility of Grandparents' Pre-Ultimate PCs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-the-secret-of-highest-quality-youtube-mp3s/"><u>[Updated] In 2024, Decoding the Secret of Highest Quality YouTube MP3s</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-windows-11-login-blunders/"><u>Avoiding Common Windows 11 Login Blunders</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-mastering-the-art-of-volume-control-a-guide-to-seamless-audio-transitions-in-adobe-after-effects-for-2024/"><u>Updated Mastering the Art of Volume Control A Guide to Seamless Audio Transitions in Adobe After Effects for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bare-bones-pc-boasts-bulky-but-lackluster-loops/"><u>Bare-Bones PC Boasts Bulky, but Lackluster Loops</u></a></li>
</ul></div>
