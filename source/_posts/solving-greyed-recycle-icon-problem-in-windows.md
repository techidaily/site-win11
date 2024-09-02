---
title: Solving Greyed Recycle Icon Problem in Windows
date: 2024-09-01T04:37:06.279Z
updated: 2024-09-02T04:37:06.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Greyed Recycle Icon Problem in Windows
excerpt: This Article Describes Solving Greyed Recycle Icon Problem in Windows
keywords: Fix Grey Recycle Bin,Clear Icon Issue WIndows,Resolve WIdnows Recycling Error,Unstuck Grey Recycle Icon,Rectify Windows Trash Icon,Address Faded Recycling Symbol,Eliminate Dull Recycling Icon
thumbnail: https://thmb.techidaily.com/b47fd0e753c3df7e85d7c99e9dd6f25592469353c9ed51bdab027cc3c0e36d8f.jpg
---

## Solving Greyed Recycle Icon Problem in Windows

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevating-the-end-scene-in-youtube-productions-for-2024/"><u>[New] Elevating the End Scene in YouTube Productions for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-creating-breathtaking-slow-motion-photo-editing-techniques-explored/"><u>[New] In 2024, Creating Breathtaking Slow Motion  Photo Editing Techniques Explored</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-science-behind-the-best-sized-videos-for-your-instagram-story/"><u>[Updated] 2024 Approved  The Science Behind the Best-Sized Videos for Your Instagram Story</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-managing-moments-in-live-streams-an-obs-timer-guide/"><u>[Updated] In 2024, Managing Moments in Live Streams  An OBS Timer Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-optimizing-audio-and-visuals-in-mobile-broadcasting-via-obs/"><u>[Updated] In 2024, Optimizing Audio & Visuals in Mobile Broadcasting via OBS</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-mastering-the-basics-of-telegram-advertising-as-a-novice/"><u>[Updated] Mastering the Basics of Telegram Advertising as a Novice</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unleash-the-power-of-stories-free-online-and-mobile-solutions-for-2024/"><u>[Updated] Unleash the Power of Stories – Free, Online & Mobile Solutions for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-nokia-xr21-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Nokia XR21 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-oppo-k11x-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Oppo K11x Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-compatibility-androidpc-connectivity-guide/"><u>Cross-Platform Compatibility: Android/PC Connectivity Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-wu-and-orchestrator-integration/"><u>Deciphering WU & Orchestrator Integration</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visibility-a-cursor-guide-for-win10-and-11/"><u>Enhancing Visibility: A Cursor Guide for Win10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/excel-data-consolidation-essentials-uniting-various-tables-with-ease/"><u>Excel Data Consolidation Essentials: Uniting Various Tables with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tips-how-to-embed-current-page-number-and-total-pages-into-document-headers/"><u>Excel Tips: How To Embed Current Page Number and Total Pages Into Document Headers</u></a></li>
<li><a href="https://win11.techidaily.com/expert-shortcuts-swiftly-sculpting-windows-11-directories/"><u>Expert Shortcuts: Swiftly Sculpting Windows 11 Directories</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixes-for-nonfunctional-microphone-in-microsoft-teams-on-windows-11-and-10/"><u>Fixes for Nonfunctional Microphone in Microsoft Teams on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-internet-connection-on-windows-systems/"><u>Fixing No Internet Connection on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-control-win11-rgb-settings/"><u>How to Control Win11 RGB Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eradicate-the-error-xc0f1103f-from-your-win11-and-geforce/"><u>How to Eradicate the Error Xc0f1103f From Your Win11 & GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-blackout-phenomenon-while-winning-games/"><u>How to Prevent Blackout Phenomenon While Winning Games</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-excel-2003-document-online-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to sign Excel 2003 document online</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-find-x7-ultra-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo Find X7 Ultra</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enhance-video-production-7-best-free-sounds-for-editors/"><u>In 2024, Enhance Video Production - 7 Best Free Sounds for Editors</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Xiaomi Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-11-update-problems-non-existent/"><u>Making Windows 11 Update Problems Non-Existent</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-installer-needs-more-access-rights-in-windows/"><u>Overcoming Installer Needs More Access Rights in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/refresh-virtual-memory-on-new-windows-11/"><u>Refresh Virtual Memory on New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-windows-11-without-admin-authorization/"><u>Resetting Windows 11 Without Admin Authorization</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lack-of-system-temperature-regulation/"><u>Restoring Lack of System Temperature Regulation</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-turning-off-autofill-feature-in-microsoft-excel/"><u>Step-by-Step Guide: Turning Off AutoFill Feature in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-locate-external-workbook-links-within-microsoft-excel/"><u>Steps to Locate External Workbook Links Within Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-effective-household-budget-planning-using-microsoft-excel/"><u>Strategies for Effective Household Budget Planning Using Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-iscsi-initiator-an-overview-for-network-enthusiasts/"><u>The Windows iSCSI Initiator: An Overview for Network Enthusiasts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/time-warp-in-media-youtube-content-upside-down-for-2024/"><u>Time Warp in Media  YouTube Content Upside Down for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-solutions-for-non-functional-redragon-pc-mic/"><u>Troubleshooting and Solutions for Non-Functional Redragon PC Mic</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-and-solving-the-problem-of-arrow-button-navigation-in-microsoft-excel/"><u>Troubleshooting and Solving the Problem of Arrow Button Navigation in Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/tuning-irqs-to-perfect-your-sound-card-experience/"><u>Tuning IRQs to Perfect Your Sound Card Experience</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-on-utilizing-the-length-formula-len-in-ms-excel-spreadsheets/"><u>Ultimate Tutorial on Utilizing the Length Formula (LEN) in MS Excel Spreadsheets</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-gionee-by-fonelab-android-recover-music/"><u>Undelete lost music from Gionee</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-insights-with-microsoft-excel-understanding-and-utilizing-the-analyze-data-functionality/"><u>Unlock Insights with Microsoft Excel: Understanding and Utilizing the 'Analyze Data' Functionality</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-poco-m6-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Poco M6 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/your-guide-to-safest-free-software-for-windows-devices/"><u>Your Guide to Safest Free Software for Windows Devices</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>