---
title: Optimizing Memory & CPU for Streamers on W11
date: 2024-07-13T09:52:28.289Z
updated: 2024-07-14T09:52:28.289Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Memory & CPU for Streamers on W11
excerpt: This Article Describes Optimizing Memory & CPU for Streamers on W11
keywords: Streamer Optimization Tips,W11 Performance Boosting,Enhance CPU Efficiency,Improve RAM Usage,Memory Tuning for Streamers,CPU Optimization Guide,W11 Gaming Settings,Streamer Performance Tips,Boost W11 CPU Efficiency,Optimize RAM for Games,Memory Tuning Streamers,CPU Performance Guide,Enhance W11 Gaming
thumbnail: https://thmb.techidaily.com/634ac9f760c3e79a9b2c54edc99fe994b8053a847fb1d16c5b184059bb3a3f2f.png
---

## Optimizing Memory & CPU for Streamers on W11

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://youtube-videos.techidaily.com/boosting-views-top-14-gaming-video-ideas-that-work-for-2024/"><u>Boosting Views  Top 14 Gaming Video Ideas That Work for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-the-windows-firewall-with-precision/"><u>Resetting the Windows Firewall with Precision</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-essential-knowledge-for-instagram-success-a-guide-to-behind-the-scenes-metrics/"><u>[New] In 2024, Essential Knowledge for Instagram Success  A Guide to Behind-the-Scenes Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-windows-11s-help-interaction/"><u>How to Revive Windows 11'S Help Interaction</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/top-10-free-spanish-text-to-speech-converter-websites/"><u>Top 10 Free Spanish Text To Speech Converter Websites</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-professional-framing-adding-bb-and-letterbox-overlays-to-fb-videos/"><u>[Updated] Professional Framing  Adding BB and Letterbox Overlays to FB Videos</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-navigation-for-uwp-apps-with-windows-11-links/"><u>Rapid Navigation for UWP Apps with Windows 11 Links</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-data-handling-mastering-windows-11s-disk-access-methods/"><u>Streamline Data Handling: Mastering Windows 11'S Disk Access Methods</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-make-your-own-video-dvds-3-simple-methods-for-windows-and-mac/"><u>2024 Approved Make Your Own Video DVDs 3 Simple Methods for Windows and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-your-pcs-ram-landscape-on-windows/"><u>Navigate Your PC's RAM Landscape on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/no-plug-just-play-connect-dualshock-3-to-pc/"><u>No Plug, Just Play: Connect DualShock 3 to PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-pioneering-practices-in-multichannel-video-distribution-fbwhatsapp/"><u>In 2024, Pioneering Practices in Multichannel Video Distribution (FB/WhatsApp)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-11-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 11 & 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-uncovering-top-resources-for-authentic-bell-tones/"><u>Updated 2024 Approved Uncovering Top Resources for Authentic Bell Tones</u></a></li>
<li><a href="https://win11.techidaily.com/the-rise-of-ai-in-next-gen-windows/"><u>The Rise of AI in Next-Gen Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-refusal-to-execute-exe-files/"><u>Decoding Windows' Refusal to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-enable-widgets-on-windows-11-system/"><u>Harness the Power: Enable Widgets on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-pc-graphics-fix-in-windows-1011/"><u>Mastering PC Graphics Fix in Windows 10/11</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-huawei-p60-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/zip-file-disguise-for-windows-11-enthusiasts/"><u>Zip File Disguise for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-every-compositor-should-know-the-trick-of-color-match-in-after-effects/"><u>Updated Every Compositor Should Know The Trick of Color Match in After Effects</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-pinterests-treasure-trove-with-top-free-video-downloads/"><u>[New] Unlock Pinterest's Treasure Trove with Top Free Video Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-memory-shortage-error-in-windows-based-vms/"><u>Solutions for 'Memory Shortage' Error in Windows-Based VMs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-unlocking-wav-conversion-the-one-stop-solution/"><u>New 2024 Approved Unlocking Wav Conversion The One-Stop Solution</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-domain-users-biometric-use-on-w11/"><u>Strategizing Domain Users' Biometric Use on W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unauthorized-access-to-secure-devices-win/"><u>Addressing Unauthorized Access to Secure Devices Win</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-unsupported-devices-warning-when-upgrading-windows/"><u>How to Handle Unsupported Devices Warning When Upgrading Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-with-linuxs-sudo-feature/"><u>Navigating Windows with Linux's Sudo Feature</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-oppo-k11-5g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Oppo K11 5G Fingerprint Lock</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-econo-audio-amps-for-youtubers-with-limited-dough/"><u>[New] 2024 Approved  Econo Audio Amps for Youtubers with Limited Dough</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-lava-blaze-2-pro-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Lava Blaze 2 Pro FRP</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fast-tracking-yuzu-gameplay-on-windows/"><u>Fast-Tracking Yuzu Gameplay on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-cyberlink-screen-recorder-review/"><u>In 2024, Cyberlink Screen Recorder Review</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-premier-4k-recorder-apps-reviewed/"><u>[New] 2024 Approved  Premier 4K Recorder Apps Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-the-redundant-or-missing-windows-tools-and-add-ons/"><u>Reinstalling the Redundant or Missing Windows Tools & Add-Ons</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-leading-8-capture-tools-without-lag/"><u>In 2024, Leading 8 Capture Tools Without Lag</u></a></li>
<li><a href="https://win11.techidaily.com/bring-home-the-fun-smartphone-games-to-desktop-with-win-11-and-google-play/"><u>Bring Home the Fun: Smartphone Games to Desktop with Win 11 & Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-impact-with-auto-color-settings-in-windows-11/"><u>Maximize Visual Impact with Auto Color Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-stream-and-save-free-unmarked-tiktok-videos-online/"><u>[Updated] Stream and Save  Free, Unmarked TikTok Videos Online</u></a></li>
<li><a href="https://win11.techidaily.com/end-session-of-unknown-windows-users-effectively/"><u>End Session of Unknown Windows Users Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-reversing-rdp-monochrome/"><u>Strategies for Reversing RDP Monochrome</u></a></li>
<li><a href="https://win11.techidaily.com/openai-whisper-for-windows-voice-to-text-techniques-unveiled/"><u>OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-device-sticky-note-integration-on-win11/"><u>Seamless Multi-Device Sticky Note Integration on WIN11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/discovering-the-premium-free-plugins-the-top-10-list-sound-engineers/"><u>Discovering the Premium Free Plugins The Top 10 List Sound Engineers</u></a></li>
<li><a href="https://win11.techidaily.com/enable-system-sounds-despite-muted-status/"><u>Enable System Sounds Despite Muted Status</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-zero-30-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Zero 30 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-revolutionaries-building-virtual-realms/"><u>2024 Approved  Revolutionaries Building Virtual Realms</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-revolutionize-your-branding-strategy-with-access-to-a-vast-library-of-free-youtube-banners/"><u>[Updated] Revolutionize Your Branding Strategy with Access to a Vast Library of Free YouTube Banners</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-pro-animation-studio-top-8-software-picks-for-mac-and-windows-for-2024/"><u>New Pro Animation Studio Top 8 Software Picks for Mac and Windows for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/immersive-playgrounds-androids-top-15-simulations-for-2024/"><u>Immersive Playgrounds  Android's Top 15 Simulations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-purging-partitions-on-your-win-os/"><u>Mastering the Art of Purging Partitions on Your Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/best-web-browsing-practices-minimizing-resources-across-platforms/"><u>Best Web Browsing Practices: Minimizing Resources Across Platforms</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-your-route-to-youtube-entrepreneurship-top-10-easy-channels/"><u>In 2024, Your Route to YouTube Entrepreneurship  Top 10 Easy Channels</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-15-favorites-that-echoed-across-tiktoks-bookish-community/"><u>[New] 2024 Approved  15 Favorites That Echoed Across TikTok’s Bookish Community</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-essential-manual-to-fb-video-playback-settings/"><u>[New] The Essential Manual to FB Video Playback Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-smooth-directx-installation-on-pc/"><u>Step-by-Step Guide to Smooth DirectX Installation on PC</u></a></li>
<li><a href="https://win11.techidaily.com/erasing-email-on-windows-sign-in-a-guide/"><u>Erasing Email on Windows Sign-In: A Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-how-to-stitch-on-tiktok/"><u>[New] How to Stitch on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fix-kit-conquering-error-code-0x80-cookies/"><u>Microsoft Store Fix Kit: Conquering Error Code 0X80 Cookies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-advanced-greenscreen-techniques-a-complete-guide-to-chroma-key-kinemaster/"><u>[Updated] Unveiling Advanced Greenscreen Techniques  A Complete Guide to Chroma Key (KineMaster)</u></a></li>
</ul></div>
