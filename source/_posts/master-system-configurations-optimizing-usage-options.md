---
title: "Master System Configurations: Optimizing Usage Options"
date: 2024-07-13T10:32:07.793Z
updated: 2024-07-14T10:32:07.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master System Configurations: Optimizing Usage Options"
excerpt: "This Article Describes Master System Configurations: Optimizing Usage Options"
keywords: MS Optimize Configs,Master Sys Tuning,Gaming Console Setup,Control Panel Hacks,Game System Adjustments,Console Customization,Usage Options Enhance
thumbnail: https://thmb.techidaily.com/128936f1237a7dae7d947e202ae29738fcba18f1e1925b63e660146e08554eaf.jpg
---

## Master System Configurations: Optimizing Usage Options

 Windows 11 offers users the flexibility to change their device usage options to suit their own needs. If you skipped the initial Windows setup and want to change your Device Usage settings, read on. The article covers two methods for changing device usage options: using system settings and a reg file.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.

## What Are the Device Usage Options on Windows?

 Device Usage Options allow you to customize your Windows experience by setting preferences for how ads are displayed. Microsoft also provides tips & suggestions and personalizes recommendations for you. Depending on your choice, Windows presents you with different types of information and services.

 Here's how you to use your device to get tips, ads, and Microsoft suggestions.

* **Gaming:** Windows shows tips and suggestions about popular games and upcoming releases.
* **Family:** If you plan on using your device with family members, this feature allows each family member to have their profile. Also, customize safety settings and connect with family members.
* **Creativity:** This option gives tips on how to make videos and photographs that bring ideas to life.
* **School:** Choose this option for the best Windows experience as a student. Windows provides productivity tips, organization tools, and collaboration features for taking notes, writing essays, and collaborating on projects.
* **Entertainment:** This option provides tips about apps and services to watch videos, browse the web, connect on social media, and more.
* **Business:** Do you want to use your device for work? With this option, Windows offers tips on managing your business, tracking expenses, and providing customer service.

 Now that you know what Device Usage Options are, here's how to change them in Windows.

## 1\. Using Windows Settings

 Changing Device Usage Options on Windows is easy. There are two ways to do it - using System Settings or through a reg file. First, let's look at how to change Device Usage Options using Windows Settings.

 To get started, press **Win + I** on your keyboard. This will open the System Settings. From the left sidebar, click on the **Personalisation** tab. Scroll down in the right pane and click **Device usage**.

![Change Device Usage on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-device-usage-on-windows-11.jpg)

 On the next page, look for your preferred Device Usage option and toggle it on.

## 2\. Using a REG File

 If you're [unable to open the System Settings window or if it isn't working](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/), use a reg file instead. A reg file is a registry key file that helps you tweak Windows settings.

### Gaming Device Usage Options

 To create a reg file for your desired Device Usage Options, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and copy-paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Now click the **File** menu and select **Save as** from the options list. Choose **All files** from the **Save as type** drop-down menu and save it with a **.reg** extension to your desktop.

![Change Gaming Device Usage Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-gaming-device-usage-options.jpg)

 To apply the settings, double-click the reg file. This will turn on the Device usage options for Gaming.

 If you want to turn off this option, create a new reg file and paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000000`

 Now save it with the **.reg** extension as above and double-click to apply.

 To turn on Device usage options for other categories, create separate reg files with the corresponding code then apply them in the same way. Here's a list of each .reg file's contents:

### Family Device Usage Options

 For the Family option:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\family]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Creativity Device Usage Options

 For Creativity:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\creative]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### School Device Usage Options

 For School usage:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\schoolwork]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Entertainment Device Usage Options

 If you want the Entertainment options:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\entertainment]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Business Device Usage Options

 And finally, for the Business side of things:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\business]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Once you have created the reg file for the Device Usage Option, double-click to apply. Now when you open System **Settings** \> **Personalisation** \> **Device Usage**, you should see the option turned on.

## Configure Your Device’s Usage Options in a Flash

 With the right Device Usage Options, Microsoft will show you relevant tips, advertisements, and recommendations. If you're a student, entertainer, or business owner, you now know two methods to change your Device Usage options in Windows 11\.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-error-0x80070522-enhance-client-access-control/"><u>Eliminate Window's Error 0X80070522: Enhance Client Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-shutdown-the-guide-to-auto-mode-with-windows-1011/"><u>Efficient Shutdown: The Guide to Auto Mode with Windows 10/11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-rated-video-voice-over-software-for-pc-review-and-download/"><u>New Top-Rated Video Voice Over Software for PC - Review and Download</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-get-the-most-out-of-kinemaster-video-templates/"><u>In 2024, How to Get the Most Out of KineMaster Video Templates</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-modify-indexer-in-windows/"><u>Step-by-Step: Modify Indexer in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-funny-photos-for-iphones/"><u>In 2024, Funny Photos for IPhones</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-master-your-content-a-complete-list-of-essential-audio-visual-tools/"><u>[New] Master Your Content  A Complete List of Essential Audio-Visual Tools</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-advanced-desktop-tools-to-screen-capture-discord/"><u>[New] 2024 Approved  Advanced Desktop Tools to Screen-Capture Discord</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-elevate-your-video-production-adobe-premiere-pro-on-mac/"><u>Updated In 2024, Elevate Your Video Production Adobe Premiere Pro on Mac</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-every-voice-matters-the-ultimate-selection-of-cost-effective-vocal-cleanup-software/"><u>New 2024 Approved Every Voice Matters The Ultimate Selection of Cost-Effective Vocal Cleanup Software</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-comprehensive-guide-to-taking-part-in-twitresponses-for-2024/"><u>[New] Comprehensive Guide to Taking Part in TwitResponses for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installer-errors-in-windows-10-and-11/"><u>Overcoming Windows Installer Errors in Windows 10 & 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unveiling-secrets-sharing-restricted-youtube-content-via-email-for-2024/"><u>Unveiling Secrets  Sharing Restricted YouTube Content via Email for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dividing-top-4k-captures-best-gimbal-pairings/"><u>Dividing Top 4K Captures  Best Gimbal Pairings</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-a-quick-tutorial-on-how-to-convert-image-to-youtube-thumbnail/"><u>In 2024, A Quick Tutorial On How To Convert Image To YouTube Thumbnail</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-speech-to-text-magic-for-ms-word-users/"><u>2024 Approved  Speech-to-Text Magic for MS Word Users</u></a></li>
<li><a href="https://win11.techidaily.com/directives-for-disabling-errors-on-gaming-platform/"><u>Directives for Disabling Errors on Gaming Platform</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-unveiling-zooms-hidden-visual-treasures-with-filters-for-2024/"><u>[Updated] Unveiling Zoom's Hidden Visual Treasures with Filters for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-win-compatible-free-media-devices/"><u>Essential Guide: Win-Compatible Free Media Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unveiling-the-secrets-to-a-flawless-fb-live-session/"><u>[Updated] Unveiling the Secrets to a Flawless FB Live Session</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-how-to-seamlessly-convert-your-podcast-into-the-universal-mp3-format/"><u>In 2024, How to Seamlessly Convert Your Podcast Into the Universal MP3 Format</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/put-and-play-mkv-movies-on-redmi-13c-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Put and play MKV movies on Redmi 13C 5G</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pixels-designing-unique-displays-on-each-monitor-of-windows/"><u>Personalized Pixels: Designing Unique Displays on Each Monitor of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-renaissance-discovering-obsidians-visuality/"><u>Notetaking Renaissance: Discovering Obsidian's Visuality</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-efficient-windows-11-shortcuts-for-uwp-apps/"><u>Crafting Efficient Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-elevate-your-ar-creations-with-downloadable-color-lookup-tables/"><u>[Updated] In 2024, Elevate Your AR Creations with Downloadable Color Lookup Tables</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-leveraging-twitters-visual-content-on-snapchat/"><u>[Updated] 2024 Approved  Leveraging Twitter's Visual Content on Snapchat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-streamlining-your-approach-to-youtube-community-dialogue/"><u>[New] 2024 Approved  Streamlining Your Approach to YouTube Community Dialogue</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-dissonance-to-harmony-kinemasters-transition-magic-for-2024/"><u>From Dissonance to Harmony  Kinemaster’s Transition Magic for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-y100-5g-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/plating-perfection-30-unique-and-appealing-recipe-channels-for-2024/"><u>Plating Perfection  30 Unique and Appealing Recipe Channels for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/rhythms-unlocked-fb-downloads-galore/"><u>Rhythms Unlocked  FB Downloads Galore</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-initiating-efficient-conversations-on-snapchat-with-three-steps/"><u>[Updated] 2024 Approved  Initiating Efficient Conversations on Snapchat with Three Steps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-enhance-video-with-pre-made-tracks-in-premiere-pro/"><u>2024 Approved  Enhance Video With Pre-Made Tracks in Premiere Pro</u></a></li>
<li><a href="https://screen-capture.techidaily.com/industry-standards-the-top-5-online-video-devices/"><u>Industry Standards  The Top 5 Online Video Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-t2x-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo T2x 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-free-online-video-compression-made-easy-10-best-tools/"><u>Updated In 2024, Free Online Video Compression Made Easy 10 Best Tools</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-pre-use-disk-formatting-notice-on-windows/"><u>Eliminating Pre-Use Disk Formatting Notice on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-zte-nubia-z60-ultra-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of ZTE Nubia Z60 Ultra Phone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-enhance-your-photos-with-top-insta-editors/"><u>[Updated] 2024 Approved  Enhance Your Photos with Top Insta Editors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-a-perfect-replica-of-your-drive/"><u>How to Make a Perfect Replica of Your Drive</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-password-strength-in-windows-11-with-longer-pins/"><u>Enhancing Password Strength in Windows 11 with Longer Pins</u></a></li>
<li><a href="https://extra-skills.techidaily.com/iphones-visual-upgrades-in-ios-11-explored-for-2024/"><u>IPhone's Visual Upgrades in iOS 11 Explored for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-the-apple-m1-a-computing-revolution/"><u>[New] Unveiling the Apple M1  A Computing Revolution?</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
</ul></div>
