---
title: How to Make Non-Loading Drivers Functional on Windows 11
date: 2024-07-13T09:53:23.583Z
updated: 2024-07-14T09:53:23.583Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make Non-Loading Drivers Functional on Windows 11
excerpt: This Article Describes How to Make Non-Loading Drivers Functional on Windows 11
keywords: Fixing Loading Drivers in Win11,Driver Load Problems Windows 11,Boot Failure,Enabling Non-Loading Drivers,Troubleshoot Unloaded Drivers,Boot Issue,Activating Windows Drivers
thumbnail: https://thmb.techidaily.com/d8e6bf944e6c6a44077570ad300a1fab74b99e0c0b2c51be60c5944e75e29423.jpg
---

## How to Make Non-Loading Drivers Functional on Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-apple-iphone-11-pro-max-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and Apple iPhone 11 Pro Max without Apple Account</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-vanquish-xps-mysterious-printer-error-xfddddf/"><u>How to Vanquish XP's Mysterious Printer Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-clicks-avoid-accelerated-movement-in-win-1011/"><u>Stabilizing Clicks: Avoid Accelerated Movement in Win 10/11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-smart-way-to-choose-a-video-to-audio-converter-essential-features-to-consider/"><u>In 2024, The Smart Way to Choose a Video to Audio Converter Essential Features to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-boost-your-e-commerce-strategy-with-these-top-15-fb-analyzers/"><u>2024 Approved  Boost Your E-Commerce Strategy with These Top 15 FB Analyzers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-score-your-story-editing-and-enriching-videos-with-auditory-elements-via-filmora/"><u>In 2024, Score Your Story Editing and Enriching Videos with Auditory Elements via Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-screen-to-file-solutions-with-apowersoft-for-2024/"><u>[New] Screen-to-File Solutions with Apowersoft for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-clearing-microsoft-protection-archives/"><u>Mastering the Art of Clearing Microsoft Protection Archives</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-photo-management-winning-windows-applications/"><u>Efficient Photo Management: Winning Windows Applications</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/astering-youtube-views-secrets-for-a-million-followers-for-2024/"><u>[New] Mastering Youtube Views  Secrets for a Million Followers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-remote-desktop-troubleshoot-internal-errors/"><u>Resolving Windows 11 Remote Desktop: Troubleshoot Internal Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-on-your-apple-iphone-6-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud On your Apple iPhone 6</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-quick-tips-incorporating-video-from-youtube-into-google-presentations/"><u>In 2024, Quick Tips  Incorporating Video From YouTube Into Google Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-channel-success-metrics-subscriber-and-play-buttons/"><u>[New] In 2024, Channel Success Metrics  Subscriber & Play Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-for-fast-utorrent-downloads-on-windows/"><u>Expert Techniques for Fast uTorrent Downloads on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-no-uninstall-issue-on-windows-oses/"><u>How to Sidestep No Uninstall Issue on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-pause-bring-back-lost-sounds-to-tech-gadgets/"><u>Resetting Pause: Bring Back Lost Sounds to Tech Gadgets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-5-microphones-compatible-with-macos-for-2024/"><u>[New] Top 5 Microphones Compatible with MacOS for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ning-your-musical-journey-youtube-playlist-construction-tips-webapp-for-2024/"><u>Designing Your Musical Journey  YouTube Playlist Construction Tips Web/App for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-iphone-8-plus-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-iphone-7-plus-lock-screen-with-notifications-by-drfone-ios/"><u>In 2024, How to Make the Most of Your iPhone 7 Plus Lock Screen with Notifications?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-easy-video-editing-software-for-newbies/"><u>Updated 2024 Approved Easy Video Editing Software for Newbies</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-combine-multiple-videos-into-one-on-instagram/"><u>2024 Approved How to Combine Multiple Videos Into One on Instagram</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-8-recommended-free-srt-translation-websites-expert-selections/"><u>In 2024, Top 8 Recommended Free SRT Translation Websites  Expert Selections</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-endless-playback-top-free-video-loopers-for-windows-and-mac-for-2024/"><u>Updated Endless Playback Top Free Video Loopers for Windows and Mac for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-ultimate-software-for-mp4-recording/"><u>[Updated] In 2024, The Ultimate Software for MP4 Recording</u></a></li>
<li><a href="https://win11.techidaily.com/esd-files-demystified-creating-iso-versions-for-windows-systems/"><u>ESD Files Demystified: Creating ISO Versions for Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-bluescreenview-a-step-by-step-tutorial/"><u>Exploring BlueScreenView - A Step-By-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/handling-missing-component-in-windows-lsassexe/"><u>Handling Missing Component in Windows' lsass.exe</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avs-video-editor-2023-an-in-depth-analysis-and-review-for-2024/"><u>AVS Video Editor 2023 An In-Depth Analysis and Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-exploring-the-top-10-budget-friendly-youtube-spaces-for-artistry/"><u>[Updated] In 2024, Exploring the Top 10 Budget-Friendly YouTube Spaces for Artistry</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-becoming-a-top-youtuber-with-gaming-livestreams/"><u>[New] In 2024, Becoming a Top YouTuber with Gaming Livestreams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-ultimate-snapchat-checklist-for-engaging-content/"><u>In 2024, The Ultimate Snapchat Checklist for Engaging Content</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-mending-deskanywhere-on-windows-11/"><u>Methods for Mending DeskAnywhere on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-blueprint-for-captivating-and-professional-looking-live-video-thumbnails/"><u>The Ultimate Blueprint for Captivating and Professional-Looking Live Video Thumbnails</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-unraveling-the-secrets-to-soaring-podcast-rankings-with-seo-for-2024/"><u>[Updated] Unraveling the Secrets to Soaring Podcast Rankings with SEO for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-unlock-efficient-remote-streaming-via-vlc-media-player/"><u>[Updated] In 2024, Unlock Efficient Remote Streaming via VLC Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-your-cortana-data-on-windows/"><u>How to Download Your Cortana Data on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-setting-windows-filter-keys/"><u>Essential Knowledge: Setting Windows Filter Keys</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-complete-guide-to-macbook-webcam-recording/"><u>2024 Approved  The Complete Guide to MacBook Webcam Recording</u></a></li>
</ul></div>
