---
title: Five Solutions for Windows Defender Virus Shield Malfunction
date: 2024-07-13T10:03:35.494Z
updated: 2024-07-14T10:03:35.494Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Five Solutions for Windows Defender Virus Shield Malfunction
excerpt: This Article Describes Five Solutions for Windows Defender Virus Shield Malfunction
keywords: Windows Virus Fix,Defender Troubleshoot,Anti-Virus Repair,Security Shield Help,Malware Guard Fixes,VirusShield Resolve,System Defender Cure
thumbnail: https://thmb.techidaily.com/ccf5800f87dc975bfa3f97e17abaade8c733e4db5fe1a72f092700ec2559e9fd.jpg
---

## Five Solutions for Windows Defender Virus Shield Malfunction

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the [Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the [different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses [how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some [best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.


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
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-asus-rog-phone-8-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Asus ROG Phone 8</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-pixelperfect-pro-focus-on-mac-and-windows-snaps-for-2024/"><u>[New] PixelPerfect Pro  Focus on Mac & Windows Snaps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-camera-error-a00f4289-in-windows-environments/"><u>Eradicating Camera Error A00F4289 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/wu-and-orchestrator-the-pillars-of-update-routine/"><u>WU & Orchestrator: The Pillars of Update Routine</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhance-your-cameras-outputs-10-free-paid-upgrade-lut-sets-available-for-2024/"><u>Enhance Your Cameras' Outputs  10 FREE, Paid-Upgrade LUT Sets Available for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-an-overheating-windows-laptop-when-gaming/"><u>How to Fix an Overheating Windows Laptop When Gaming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-easy-recording-setups-for-lol-enthusiasts-3-ways/"><u>[New] In 2024, Easy Recording Setups for LOL Enthusiasts (3 Ways)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-quintessential-5-filters-for-depth-video/"><u>In 2024, Quintessential 5 Filters for Depth Video</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-lsa-protection-error-on-windows/"><u>How to Fix the LSA Protection Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-system-information-tool-on-windows/"><u>10 Ways to Open the System Information Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-spontaneous-search-menu-open-in-win11/"><u>Fixing Spontaneous Search Menu Open in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-sandbox-a-win-11-guide/"><u>Configure Your Sandbox: A Win 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1715860796573-new-capture-and-share-your-mac-life-free/"><u>[New] Capture & Share Your Mac Life, FREE!</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-itel-a70-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Itel A70 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-microsofts-phone-link-on-mobile-devices/"><u>How to Utilize Microsoft's Phone Link on Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/winfreedomgpt-guide-launching-unrestricted-chatbots/"><u>WinFreedomGPT Guide: Launching Unrestricted ChatBots</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-rewind-game-pc-redemption/"><u>AtlasOS Rewind: Game PC Redemption</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-docker-setup-tips-for-optimized-wsl-2-use/"><u>Elevate Your Docker Setup: Tips for Optimized WSL 2 Use</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-cleaner-windows-11-desktop-layout/"><u>Designing a Cleaner Windows 11 Desktop Layout</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-essential-steps-to-record-your-hp-laptop-screen-efficiently/"><u>In 2024, Essential Steps to Record Your HP Laptop Screen Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-google-nearby-to-link-devices-easily/"><u>Leveraging Google Nearby to Link Devices Easily</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-windows-selection-of-best-nintendo-switch-imitators/"><u>Exclusive Windows Selection of Best Nintendo Switch Imitators</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-save-locations-on-windows-devices/"><u>How to Resolve Save Locations on Windows Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-can-life360-track-you-when-your-xiaomi-redmi-13c-5g-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Xiaomi Redmi 13C 5G is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-organize-your-pcenas-7-prime-windows-photos-tools/"><u>Effortlessly Organize Your PC'enas: 7 Prime Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-policies-an-in-depth-analysis-using-3-different-views/"><u>Exploring Windows Policies: An In-Depth Analysis Using 3 Different Views</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-use-and-maintenance-of-m1-max-clips-for-2024/"><u>Mastering the Use and Maintenance of M1 Max Clips for 2024</u></a></li>
</ul></div>
