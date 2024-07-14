---
title: Addressing Discreprancies in Power Usage Display for Win 11 Systems
date: 2024-07-13T11:21:53.039Z
updated: 2024-07-14T11:21:53.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Discreprancies in Power Usage Display for Win 11 Systems
excerpt: This Article Describes Addressing Discreprancies in Power Usage Display for Win 11 Systems
keywords: Power Usage WWin11,Win11 Energy Discrepancy,Energy Display Win11,Power Use Tracking Windows,Win11 Battery Efficiency,Windows Energy Monitoring,Power Metrics Win11 Systems
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Addressing Discreprancies in Power Usage Display for Win 11 Systems

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
<li><a href="https://win11.techidaily.com/1719368088856-troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-immaculate-window-display-on-w11/"><u>A Guide to Immaculate Window Display on W11</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enhance-audio-visual-fidelity-use-av1-on-youtube/"><u>Enhance Audio-Visual Fidelity  Use AV1 on YouTube</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-vivo-y100-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Vivo Y100 5G Fingerprint Lock</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-vivo-v29-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Vivo V29 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-apps-that-elevate-your-desktop-writing-game/"><u>5 Apps That Elevate Your Desktop Writing Game</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-windows-processes-that-could-be-hiding-a-virus/"><u>7 Essential Windows Processes That Could Be Hiding a Virus</u></a></li>
<li><a href="https://win11.techidaily.com/1719348018496-skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oppo-find-x7-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Oppo Find X7? Fixed | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo Y100A? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-11-software-removal-primer-top-11-approaches-114-chars/"><u>A Windows 11 Software Removal Primer: Top 11 Approaches (114 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/5-must-have-windows-software-for-mac-refugees/"><u>5 Must-Have Windows Software for Mac Refugees</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-iphone-exposed-the-art-of-prolonged-photography/"><u>2024 Approved  IPhone Exposed  The Art of Prolonged Photography</u></a></li>
<li><a href="https://win11.techidaily.com/a-comparative-study-of-cloud-and-physical-methods-for-windows-setup/"><u>A Comparative Study of Cloud & Physical Methods for Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/1719339382074-unlock-frozen-shift-on-windows-pcs/"><u>Unlock Frozen Shift on Windows PCs.</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-to-revamping-group-policy-settings/"><u>A Practical Approach to Revamping Group Policy Settings</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-nokia-c110-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-the-critical-selection-top-5-most-cutting-edge-voice-transformation-services-online-for-2024/"><u>Updated The Critical Selection Top 5 Most Cutting-Edge Voice Transformation Services Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-clear-the-tpm-on-windows-11/"><u>4 Ways to Clear the TPM on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/vlog-with-verve-following-in-the-footsteps-of-video-experts-for-2024/"><u>Vlog with Verve  Following in the Footsteps of Video Experts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-stop-automatic-office-updates-on-windows/"><u>4 Ways to Stop Automatic Office Updates on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-inconsistent-monitor-flashes-in-laptops/"><u>Resolved Inconsistent Monitor Flashes in Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
</ul></div>
