---
title: Easing Windows Safety Blocks Set By High-Ranking Admins
date: 2024-06-25T11:35:07.400Z
updated: 2024-06-26T11:35:07.400Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easing Windows Safety Blocks Set By High-Ranking Admins
excerpt: This Article Describes Easing Windows Safety Blocks Set By High-Ranking Admins
keywords: Safeguard Windows Protocols,Admin Security Updates,Eliminating Window Restrictions,High-Ranking Policy Enforcement,Admin Block Management,Windows Access Control,Elevated Privilege Moderation
thumbnail: https://thmb.techidaily.com/1040d06f8d0aa10730551351f9cb44d3bcea699d80952a8774c562402ba30c3b.jpg
---

## Easing Windows Safety Blocks Set By High-Ranking Admins

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit[how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our[how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on[how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our[how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on[how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on[how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://win11.techidaily.com/discover-the-win11-lineups-finest-videomodding-software/"><u>Discover the Win11 Lineup's Finest Videomodding Software</u></a></li>
<li><a href="https://win11.techidaily.com/ten-strategies-to-keep-windows-safe-without-bitlocker-support/"><u>Ten Strategies to Keep Windows Safe without Bitlocker Support</u></a></li>
<li><a href="https://win11.techidaily.com/ace-at-tech-how-to-revitalize-your-pcs-apps/"><u>Ace at Tech: How to Revitalize Your PC's Apps</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-accelerate-your-pcs-warmup-with-win11-tips/"><u>Ready, Set, Go! Accelerate Your PC's Warmup with Win11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-xc0000142-in-microsoft-oses/"><u>Remedying Error XC0000142 in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-natural-windows-file-sorting-settings/"><u>Restoring Natural Windows File Sorting Settings</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-how-to-locate-and-utilize-hidden-windows-11-enhancements/"><u>Fix the Gap: How to Locate & Utilize Hidden Windows 11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/end-session-of-unknown-windows-users-effectively/"><u>End Session of Unknown Windows Users Effectively</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, Methods to Change GPS Location On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-abyss-underwater-video-tips-using-a-gopro-camera/"><u>[New] Exploring Abyss  Underwater Video Tips Using a GoPro Camera</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-optimal-chrome-plugins-top-5-for-vimeo-downloaders/"><u>[New] Optimal Chrome Plugins  Top 5 for Vimeo Downloaders</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-ultimate-list-of-windows-audio-equalization-software/"><u>Updated 2024 Approved The Ultimate List of Windows Audio Equalization Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/diving-deep-into-valheims-vital-vegetation/"><u>Diving Deep Into Valheim's Vital Vegetation</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-most-reliable-voice-recorders-suited-for-macos-users/"><u>[New] 2024 Approved  The Most Reliable Voice Recorders Suited for MacOS Users</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-perfecting-ephemeral-fades-in-digital-recording-software-audacity/"><u>In 2024, Perfecting Ephemeral Fades in Digital Recording Software Audacity</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-from-ideas-to-influence-an-insider-look-at-strategic-instagram-videos/"><u>In 2024, From Ideas to Influence  An Insider Look at Strategic Instagram Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-tecno-pop-8-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Tecno Pop 8 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-maximizing-twitter-budget-efficiency-in-ad-spends/"><u>[Updated] 2024 Approved  Maximizing Twitter Budget Efficiency in Ad Spends</u></a></li>
</ul></div>
