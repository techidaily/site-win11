---
title: Bypassing Windows 11 Security Warning Glitches
date: 2025-01-31T21:42:04.436Z
updated: 2025-02-04T08:36:01.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows 11 Security Warning Glitches
excerpt: This Article Describes Bypassing Windows 11 Security Warning Glitches
keywords: Bypass WS11 Alerts,Win11 Warning Skip,SecPassFail Fix,Bypass MSWarn Glitch,Windows Security Evasion,Glitch Avoidance WS11,Elude WS11 Alert Error
thumbnail: https://thmb.techidaily.com/c7997379262ae837ce8b40d29f0069413aec90a361d23570f41841fc2273feb3.jpg
---

## Bypassing Windows 11 Security Warning Glitches

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our[guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on[utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about[resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the[Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this[Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out[our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to[performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the[Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-navigating-audio-imports-with-the-inshot-app/"><u>[Updated] 2024 Approved Navigating Audio Imports with the InShot App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-art-of-audio-mastery-with-iphones-voice-recording/"><u>[Updated] 2024 Approved The Art of Audio Mastery with iPhone's Voice Recording</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-discover-9-easy-no-cost-editing-software-options/"><u>2024 Approved Discover 9 Easy, No-Cost Editing Software Options</u></a></li>
<li><a href="https://win11.techidaily.com/all-inclusive-kodi-handbook-expert-strategies-for-optimizing-and-personalizing-your-viewing-pleasure/"><u>All-Inclusive Kodi Handbook: Expert Strategies for Optimizing and Personalizing Your Viewing Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/back-to-class-bash-enter-our-2014-wonderfox-contest-and-score-top-picks-at-no-cost/"><u>Back to Class Bash: Enter Our 2014 WonderFox Contest and Score Top Picks at No Cost!</u></a></li>
<li><a href="https://win11.techidaily.com/best-10-free-video-segmenters-how-to-easily-cut-and-slice-movies-without-cost/"><u>Best 10 FREE Video Segmenters: How to Easily Cut and Slice Movies Without Cost</u></a></li>
<li><a href="https://win11.techidaily.com/best-7-no-cost-audio-equalizers-and-levelers-for-windows-10-users/"><u>Best 7 No-Cost Audio Equalizers & Levelers for Windows 10 Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/build-high-impact-facebook-ad-videos-free-creation-kit-provides-tools/"><u>Build High-Impact Facebook Ad Videos - FREE Creation Kit Provides Tools</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-honor-70-lite-5g-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Honor 70 Lite 5G</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ultimate-selection-of-5-acapella-sites-for-free-tunes-perfect-for-dj-playlists/"><u>Discover the Ultimate Selection of 5 Acapella Sites for Free Tunes Perfect for DJ Playlists</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-to-setting-up-the-ultimate-loonatics/"><u>Easy Guide to Setting Up the Ultimate LooNatics</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-setting-up-your-vizio-tv-for-optimal-usb-movie-playback-performance/"><u>Easy Guide: Setting Up Your Vizio TV For Optimal USB Movie Playback Performance</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guide-discovering-the-specific-build-and-version-of-your-windows-10-system/"><u>Guide: Discovering the Specific Build & Version of Your Windows 10 System</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-contacts-from-apple-iphone-12-mini-to-iphone-quickly-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Contacts from Apple iPhone 12 mini to iPhone Quickly | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-complete-dynamics-review-2023/"><u>In 2024, Complete Dynamics Review 2023</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mega-discount-on-4tb-samsung-t5-usb-c-portable-ssd-up-to-50-off-shop-now-at-amazon/"><u>Mega Discount on 4TB Samsung T5 USB-C Portable SSD - Up to 50% Off - Shop Now at Amazon!</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-on-apple-iphone-12-pro-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes On Apple iPhone 12 Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/44ow44op44km44k444oz44kw5lit44gr44oh44oh44kj44ki44gm5yan55sf44gn44gn44gq44ge5ac05zci44cb44gp44gg5aplusplus5yem44gz44km44gw44ki44ge44gl77ya44ob44ol44o844oi4440/"><u>ブラウジング中にメディアが再生できない場合、どう対処すればよいか：チュートリアル</u></a></li>
<li><a href="https://win11.techidaily.com/and/"><u>プロの技術で任意のゲーム映像をキャプチャ&セーブするコツ</u></a></li>
</ul></div>

