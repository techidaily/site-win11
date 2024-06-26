---
title: Overcoming the Absence of Battery Life Duration in PCs Running Win 11
date: 2024-06-25T09:49:55.892Z
updated: 2024-06-26T09:49:55.892Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Absence of Battery Life Duration in PCs Running Win 11
excerpt: This Article Describes Overcoming the Absence of Battery Life Duration in PCs Running Win 11
keywords: Win 11 Power Efficiency,PC Battery Endurance,Extend Windows PC Life,Optimal Win 11 Battery,Minimize Win 11 Drainage,Enhance Win 11 Usability,Prolong Win 11 Runtime
thumbnail: https://thmb.techidaily.com/3616fb63d3712b98cc05f9583f4211869f6e4c453eb6e04c1cfde40ef70bbce3.jpg
---

## Overcoming the Absence of Battery Life Duration in PCs Running Win 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

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
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-enable-razer-recognition-by-synapse/"><u>How to Re-Enable Razer Recognition by Synapse</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-for-enabling-win11-on-5ghz-networks-effortlessly/"><u>Essentials for Enabling Win11 on 5GHz Networks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-windows-11-when-you-cant-rename-folders/"><u>8 Ways to Fix Windows 11 When You Can’t Rename Folders</u></a></li>
<li><a href="https://win11.techidaily.com/how-runtime-broker-enhances-system-efficiency-and-security/"><u>How Runtime Broker Enhances System Efficiency & Security</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-revealing-youtubes-showcase-of-notable-user-comments/"><u>[New] Revealing YouTube's Showcase of Notable User Comments</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unseen-strategies-how-to-tap-into-your-facebook-message-library/"><u>In 2024, Unseen Strategies  How to Tap Into Your Facebook Message Library</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-reno-11f-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Oppo Reno 11F 5G</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-the-2023-assessment-of-apeaksofts-pioneering-screens-recording/"><u>In 2024, The 2023 Assessment of Apeaksoft's Pioneering Screens Recording</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/reaper-decoded-in-depth-analysis-of-its-professional-recording-suite-and-educational-materials-for-2024/"><u>REAPER Decoded In-Depth Analysis of Its Professional Recording Suite and Educational Materials for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-expert-tips-for-capturing-and-saving-igtv-on-handhrani/"><u>[New] 2024 Approved  Expert Tips for Capturing and Saving IGTV on Handhrani</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-adding-drama-to-videos-strikethrough-for-emphasis-and-clarity-for-2024/"><u>[New] Adding Drama to Videos  Strikethrough for Emphasis and Clarity for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-samsung-galaxy-f04-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Samsung Galaxy F04 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-craft-channels-with-flair-unveiling-10-innovative-design-platforms-for-2024/"><u>[Updated] Craft Channels with Flair  Unveiling 10 Innovative Design Platforms for 2024</u></a></li>
</ul></div>
