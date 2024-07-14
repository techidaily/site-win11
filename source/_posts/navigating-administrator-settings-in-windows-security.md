---
title: Navigating Administrator Settings in Windows Security
date: 2024-07-13T11:01:16.965Z
updated: 2024-07-14T11:01:16.965Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Administrator Settings in Windows Security
excerpt: This Article Describes Navigating Administrator Settings in Windows Security
keywords: WinSecureConfig,AdminSettingsMSI,WindowsAdminControl,SecureWinSetting,SystemSecurityPrefs,AdminWindowsConfig,SecurityWinOptions
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## Navigating Administrator Settings in Windows Security

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our [how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on [how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
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

1. Open PowerShell with administrative rights. Our guide on [how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on [how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
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
<li><a href="https://win11.techidaily.com/5-best-file-sharing-apps-on-a-windows-pc/"><u>5 Best File Sharing Apps on a Windows PC</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-tecno-camon-20-pro-5g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Tecno Camon 20 Pro 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719364992381-unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1719322467309-troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes!</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-xiaomi-14-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Xiaomi 14</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-windows-11-shortcuts/"><u>A Step-by-Step Approach to Windows 11 Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/27-tips-for-personalizing-your-windows-11-experience/"><u>27 Tips for Personalizing Your Windows 11 Experience</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-yielding-income-a-streamers-guide-to-earning/"><u>2024 Approved  Yielding Income  A Streamer's Guide to Earning</u></a></li>
<li><a href="https://win11.techidaily.com/9-updated-w11-key-enhancements-unveiled-by-recent-patch/"><u>9 Updated W11: Key Enhancements Unveiled by Recent Patch</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-the-blueprint-for-creating-stellar-tiktok-promotional-content/"><u>[Updated] 2024 Approved  The Blueprint for Creating Stellar TikTok Promotional Content</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-pcs-are-better-than-macs/"><u>9 Reasons PCs Are Better Than Macs</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-expert-guide-to-pixlr-edits-top-15-tricks-for-perfection/"><u>[New] Expert Guide to Pixlr Edits  Top 15 Tricks for Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-vivo-t2x-5g-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Vivo T2x 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-vivo-y100i-power-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Vivo Y100i Power 5G FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-google-drive-not-syncing-on-windows/"><u>7 Ways to Fix Google Drive Not Syncing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-effective-methods-to-enhance-windows-ram-usage/"><u>3 Effective Methods to Enhance Windows' RAM Usage</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-entering-and-exiting-terminals-zen-space/"><u>A Step-by-Step Breakdown of Entering & Exiting Terminal's Zen Space</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-free-video-editing-on-ubuntu-top-10-picks/"><u>Updated In 2024, Free Video Editing on Ubuntu Top 10 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-change-taskbar-history-19852023/"><u>A Window Into Change: Taskbar History (1985–2023)</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-iscsi-initiator/"><u>A Comprehensive Look at Windows iSCSI Initiator</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-boosting-profile-videos-a-guide-to-allure/"><u>[New] In 2024, Boosting Profile Videos  A Guide to Allure</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-stop-the-background-from-automatically-changing-on-windows-11/"><u>6 Ways to Stop the Background From Automatically Changing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-winning-website-conversion/"><u>A Step-by-Step for Winning Website Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/1719351823246-fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719347188756-overcoming-chrome-hurdles-in-w11-effective-steps-herein/"><u>Overcoming Chrome Hurdles in W11 – Effective Steps Herein.</u></a></li>
<li><a href="https://win11.techidaily.com/1719334307866-skip-wsl-save-time/"><u>Skip WSL, Save Time</u></a></li>
<li><a href="https://win11.techidaily.com/1719368088856-troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here!</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-finding-out-what-model-you-run-on-windows/"><u>A Simple Guide to Finding Out What Model You Run on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-personalized-typing-mastering-keybinding-w11/"><u>A Window Into Personalized Typing: Mastering Keybinding W11</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-windows-processes-that-could-be-hiding-a-virus/"><u>7 Essential Windows Processes That Could Be Hiding a Virus</u></a></li>
<li><a href="https://win11.techidaily.com/1719325122258-overcome-your-win11-chrome-freeze-effective-fix-strategies/"><u>Overcome Your Win11 Chrome Freeze: Effective Fix Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-solving-directdraw-mistakes/"><u>A Step-by-Step Approach to Solving DirectDraw Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/achieve-hollywood-grade-video-a-step-by-step-fcpx-guide-for-2024/"><u>Achieve Hollywood-Grade Video A Step-by-Step FCPX Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-methods-to-mend-your-obs-studio-connection-on-windows-pcs/"><u>7 Methods to Mend Your OBS Studio Connection on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-discrepancies-in-to-do-app/"><u>A Comprehensive Guide to Fixing Discrepancies in To-Do App</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-keyboard-shortcuts-not-working-in-windows/"><u>9 Ways to Fix Keyboard Shortcuts Not Working in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-how-to-screen-record-instagram-story/"><u>[Updated] How to Screen Record Instagram Story</u></a></li>
<li><a href="https://win11.techidaily.com/22h2-windows-fixes-for-recurring-issues/"><u>22H2 Windows Fixes for Recurring Issues</u></a></li>
</ul></div>
