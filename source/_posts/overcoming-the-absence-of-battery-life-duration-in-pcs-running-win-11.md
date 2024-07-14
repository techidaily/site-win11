---
title: Overcoming the Absence of Battery Life Duration in PCs Running Win 11
date: 2024-07-13T09:53:35.414Z
updated: 2024-07-14T09:53:35.414Z
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
<li><a href="https://win11.techidaily.com/eradicating-disappearances-in-system-navigator/"><u>Eradicating Disappearances in System Navigator</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-team-chats-on-windows-1110/"><u>Ensuring Smooth Team Chats on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-edition-enhance-windows-11/"><u>Christmas Edition: Enhance Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-to-add-srt-to-mp4-is-not-as-hard-as-you-might-think-all-you-just-need-is-the-right-tool-to-help-you-get-the-job-done-read-this-article/"><u>Updated 2024 Approved To Add SRT to MP4 Is Not as Hard as You Might Think. All You Just Need Is the Right Tool to Help You Get the Job Done. Read This Article and Learn the 8 Latest Methods to Merge SRT with MP4 Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-correcting-unresponsive-video-files/"><u>Tips for Correcting Unresponsive Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-your-marketing-mettle-on-youtube/"><u>[New] Maximizing Your Marketing Mettle on Youtube</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-realme-gt-3-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Realme GT 3 Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-nokia-150-2023-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Nokia 150 (2023) to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/5-solutions-for-itel-s23plus-unlock-without-password-by-drfone-android/"><u>5 Solutions For Itel S23+ Unlock Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsoft-family-safetys-core-functions/"><u>Decoding Microsoft Family Safety's Core Functions</u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-image-navigation-using-file-explorer-windows/"><u>Effortless Image Navigation Using File Explorer Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-effortless-mac-screenshots-exploring-five-simple-methods-for-2024/"><u>[Updated] Effortless Mac Screenshots  Exploring Five Simple Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-360-degree-retail-exploration-tech/"><u>[Updated] 360-Degree Retail Exploration Tech</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/streaming-success-optimizing-your-logitech-cam-for-2024/"><u>Streaming Success  Optimizing Your Logitech Cam for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wonders-enhance-windows-11-explorer-visibility/"><u>Windowed Wonders: Enhance Windows 11 Explorer Visibility</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/mastermind-your-marketing-surge-to-1000-insta-supporters-each-month-for-2024/"><u>Mastermind Your Marketing  Surge to 1,000 Insta Supporters Each Month for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-the-cutting-edge-trends-shaping-tiktok/"><u>2024 Approved  The Cutting-Edge Trends Shaping TikTok</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-latest-trend-get-8plus-free-tools-for-cutting-and-sharing-video-content/"><u>Instagram's Latest Trend  Get 8+ Free Tools for Cutting & Sharing Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-voice-and-music-from-bluetooth-headset/"><u>Troubleshooting Windows: Voice & Music From Bluetooth Headset</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-digital-dynasty-ranking-the-top-10-youtube-videos-for-2024/"><u>Daily Digital Dynasty  Ranking the Top 10 YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-how-to-execute-system-file-checker-sfc/"><u>Command Line: How to Execute System File Checker (SFC)</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-blank-display-of-startup-items/"><u>Eradicating Blank Display of Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-why-your-windows-11-icons-are-diminishing/"><u>Discover Why Your Windows 11 Icons Are Diminishing</u></a></li>
<li><a href="https://win11.techidaily.com/toolbox-tutorial-windows-core-components-management/"><u>Toolbox Tutorial: Windows' Core Components Management</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windowsstore-directory-secrets-for-users/"><u>Unveiling WindowsStore Directory Secrets for Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-vivo-y36-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Vivo Y36 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/1719293621682-mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
</ul></div>
