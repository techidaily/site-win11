---
title: How to Fix the Vanishing Battery Time Indicator in Windows 11
date: 2024-07-13T10:45:28.275Z
updated: 2024-07-14T10:45:28.275Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
excerpt: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
keywords: Windows Battery Life,Save Power Mode,Low Battery Alerts,Battery Health Check,Optimize Battery Use,Fix Time Indicator,Manage Battery Settings
thumbnail: https://thmb.techidaily.com/4d82cc5d4830160f77be1be23b3b0d5c8cbc630ac82437e197dd592c77a4c46e.jpg
---

## How to Fix the Vanishing Battery Time Indicator in Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://win11.techidaily.com/no-drive-letters-investigating-the-causes-and-remedies-for-windows-users/"><u>No Drive Letters: Investigating the Causes & Remedies for Windows Users</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/snapchat-recovery-quickly-recover-photosvideos-for-2024/"><u>Snapchat Recovery  Quickly Recover Photos/Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-power-management-tools-for-windows-devices/"><u>Unlocking Power Management Tools for Windows Devices</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-billion-views-video-hall-youtubes-top-ever-watches/"><u>[Updated] Billion-Views Video Hall  YouTube's Top Ever Watches</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-motorola-moto-g13-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Motorola Moto G13 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-counteract-the-black-screen-on-steam/"><u>Strategies to Counteract the Black Screen on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-overcoming-windows-11-screensaver/"><u>The Ultimate Guide: Overcoming Windows 11 Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/turn-the-tide-solving-chrome-file-upload-issues-on-windows-pcs/"><u>Turn the Tide: Solving Chrome File Upload Issues on Windows PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-iphone-15-plus-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Plus When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-comparing-videography-power-in-prohero-and-keymission-for-2024/"><u>[Updated] Comparing Videography Power in ProHero and Keymission for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rog-ally-in-question-how-does-asus-stack-up/"><u>ROG Ally in Question: How Does ASUS Stack Up?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-master-lightrooms-artistic-control-creating-and-merging-hdr-images/"><u>2024 Approved  Master Lightroom's Artistic Control  Creating & Merging HDR Images</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-huawei-nova-y91-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Huawei Nova Y91 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-chromatic-coherence-helper/"><u>[New] Chromatic Coherence Helper</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-navigation-in-windows-11/"><u>Sticky Note Navigation in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-oneplus-12-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-computers-without-the-windows-lockdown/"><u>Rejuvenating Computers Without the Windows Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/pixelated-paths-walking-through-oldschool-pc-world-in-dosbox-x/"><u>Pixelated Paths: Walking Through Oldschool PC World in DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-the-lost-startup-window-in-windows/"><u>Reclaiming the Lost Startup Window in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-playbook-9-proven-fixes-for-smooth-windows-videos/"><u>The Ultimate Playbook: 9 Proven Fixes for Smooth Windows Videos</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-spatial-capability-with-windows-11-settings/"><u>Unleash Full Spatial Capability with Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/strategize-for-smooth-operations-manage-windows-11s-activities-and-updates/"><u>Strategize for Smooth Operations: Manage Windows 11'S Activities & Updates</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-samsung-galaxy-s23-by-drfone-android/"><u>How to Bypass FRP on Samsung Galaxy S23?</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-the-load-on-your-pc-with-efficient-wlanextexe/"><u>Lowering the Load on Your PC with Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-apples-messaging-protocol-in-windows-os/"><u>Leveraging the Power of Apple's Messaging Protocol in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/solving-projector-offline-error-in-microsoft-operating-system/"><u>Solving 'Projector Offline' Error in Microsoft Operating System</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-unveiling-the-secrets-of-enhancing-video-sessions-in-google-meet/"><u>2024 Approved  Unveiling the Secrets of Enhancing Video Sessions in Google Meet</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/the-top-rated-free-video-stabilization-software-a-comprehensive-guide-for-2024/"><u>The Top-Rated Free Video Stabilization Software A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/standby-struggles-dissecting-modern-standby-issues/"><u>Standby Struggles: Dissecting Modern Standby Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mending-missing-window-steam-play-integration/"><u>Mending Missing Window-Steam Play Integration</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-finest-unboxing-content-15-top-ranked-youtube-vids/"><u>The Finest Unboxing Content  15 Top-Ranked YouTube Vids</u></a></li>
<li><a href="https://win11.techidaily.com/replacing-default-pdf-handler-in-windows-os/"><u>Replacing Default PDF Handler in Windows OS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-samsung-galaxy-f14-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Samsung Galaxy F14 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-conflicting-camera-requests-windows-error-0xa00f4243/"><u>Mitigating Conflicting Camera Requests (Windows, Error 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-0x800704cf-error-from-microsoft-store/"><u>Overcoming the 0X800704CF Error From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-large-archiving-tasks-with-windows-powershell-tips/"><u>Simplifying Large Archiving Tasks with Windows PowerShell Tips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/troubleshoot-and-mend-your-instagram-video-issues/"><u>Troubleshoot & Mend Your Instagram Video Issues</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-onedrive-lockout-windows-user-guide-needed/"><u>Reverse OneDrive Lockout: Windows User Guide Needed</u></a></li>
<li><a href="https://win11.techidaily.com/unlinked-file-program-resolution-for-windows-pc-users/"><u>Unlinked File Program Resolution for Windows PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-flashing-screens-on-win1011-quick-fixes/"><u>Tackling Flashing Screens on WIN10/11: Quick Fixes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-video-spin-perfecting-instagram-posts/"><u>[Updated] Mastering Video Spin  Perfecting Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-user-errors-fixing-invalid-profiles-in-w1111/"><u>Unraveling User Errors: Fixing Invalid Profiles in W11/11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-10-viral-culinary-phenomena-on-tiktok/"><u>[New] In 2024, 10 Viral Culinary Phenomena on TikTok</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/download-windows-movie-maker-a-comprehensive-guide-to-video-editing/"><u>Download Windows Movie Maker A Comprehensive Guide to Video Editing</u></a></li>
</ul></div>
