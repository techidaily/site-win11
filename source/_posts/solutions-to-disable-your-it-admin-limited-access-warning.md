---
title: Solutions to Disable 'Your IT Admin Limited Access' Warning
date: 2024-07-13T10:09:22.687Z
updated: 2024-07-14T10:09:22.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions to Disable 'Your IT Admin Limited Access' Warning
excerpt: This Article Describes Solutions to Disable 'Your IT Admin Limited Access' Warning
keywords: IT Admin Restrictions,Disable IT Alert,Unlock IT Access,Override Access Limit,Remove IT Lockout,Bypass IT Warning,Clear IT Restriction
thumbnail: https://thmb.techidaily.com/59f91e855b8da924b2a0ba83734da21e4ed3929e8ad5bcae0b9a32715b7cc063.jpg
---

## Solutions to Disable 'Your IT Admin Limited Access' Warning

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to [changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to [open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article [about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on [creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-leading-mac-graphics-recorder/"><u>[New] 2024 Approved  Leading Mac Graphics Recorder</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-the-perfect-blend-of-sound-and-video-tips-to-capture-high-quality-zoom-recordings/"><u>2024 Approved  The Perfect Blend of Sound and Video  Tips to Capture High-Quality Zoom Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-overcoming-onedrive-errors-on-windows/"><u>Winning at Overcoming OneDrive Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-screen-captures-adding-sound-in-the-snipping-tool-max-156/"><u>Elevate Your Screen Captures: Adding Sound in the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nokia-c22-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Nokia C22 to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-tackling-windows-security-anomalies/"><u>Strategies for Tackling Windows Security Anomalies</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-system-failures-blue-screen-aftermath-in-windows/"><u>Delving Into System Failures: Blue Screen Aftermath in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-asus-rog-phone-8-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Asus ROG Phone 8 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-novices-introduction-to-video-coders/"><u>In 2024, A Novice's Introduction to Video Coders</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-honor-90-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Honor 90 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-make-every-instagram-story-a-visual-feast-multiply-your-images/"><u>2024 Approved  Make Every Instagram Story a Visual Feast  Multiply Your Images</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mend-media-player-server-faults/"><u>Steps to Mend Media Player Server Faults</u></a></li>
<li><a href="https://win11.techidaily.com/swift-pc-exploration-via-everythingapp/"><u>Swift PC Exploration via EverythingApp</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-realme-c55-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Realme C55 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-unlock-high-viewership-selecting-the-best-trackers-for-your-videos/"><u>[Updated] In 2024, Unlock High Viewership  Selecting the Best Trackers for Your Videos</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-quality-with-auto-hdr-in-w11/"><u>Maximizing Image Quality with Auto HDR in W11</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-outlook-error-0x80040610-on-windows-devices/"><u>Quick Fix for Outlook Error 0X80040610 on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-complications-with-java-installer/"><u>Steps to Fix Windows Complications with Java Installer</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-batch-renaming-made-simple/"><u>PowerToys' Batch Renaming Made Simple</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-get-laughter-in-minutes-install-and-revel-in-ifunnys-meme-world/"><u>[Updated] Get Laughter in Minutes  Install and Revel in iFunny's Meme World</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-bluetooth-headphones-playing-sound-without-volume-control/"><u>Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-proxy-perfection-the-top-8-video-editing-apps-for-4k/"><u>2024 Approved Proxy Perfection The Top 8 Video Editing Apps for 4K</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-high-end-audio-for-youtubes-best-gamers/"><u>[New] In 2024, High-End Audio for YouTube's Best Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-gpu-capabilities-the-6-best-testers-in-windows/"><u>Navigate Through GPU Capabilities: The 6 Best Testers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-over-windows-input-methods/"><u>Unlock Full Control over Windows' Input Methods</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-strategic-steps-for-pinpointing-a-list-film-creators/"><u>[New] Strategic Steps for Pinpointing A-List Film Creators</u></a></li>
<li><a href="https://extra-information.techidaily.com/digital-decor-best-platforms-and-software-for-photo-frameups/"><u>Digital Decor  Best Platforms & Software for Photo Frameups</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-11s-cam-access-silence-protocol/"><u>Altering Windows 11'S Cam Access Silence Protocol</u></a></li>
<li><a href="https://win11.techidaily.com/total-flush-out-of-windows-subsystem/"><u>Total Flush Out of Windows Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-how-to-block-facebook-video-ads/"><u>In 2024, How to Block Facebook Video Ads?</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-admin-control-in-windows-os-security/"><u>Redefining Admin Control in Windows OS Security</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-basics-top-10-windows-store-picks/"><u>Mastering the Basics: Top 10 Windows Store Picks</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-samsung-galaxy-a34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Samsung Galaxy A34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-non-ad-focused-start-menu-win-11/"><u>Exclusive, Non-Ad Focused Start Menu Win 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-premium-vimeo-file-extractors/"><u>[New] Premium Vimeo File Extractors</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-curious-case-of-inverted-images-on-social-media/"><u>2024 Approved  The Curious Case of Inverted Images on Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-unlocking-high-impact-content-masterful-strategies-for-more-views/"><u>[Updated] 2024 Approved  Unlocking High-Impact Content  Masterful Strategies for More Views</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-download-windows-movie-maker-a-comprehensive-guide-to-video-editing-for-2024/"><u>Updated Download Windows Movie Maker A Comprehensive Guide to Video Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-update-and-clean-the-cache-of-windows-symbols/"><u>Techniques to Update and Clean the Cache of Windows Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-tools-for-superior-macos-experience/"><u>Utilizing Windows Tools for Superior macOS Experience</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-your-samsung-galaxy-s24-ultra-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Samsung Galaxy S24 Ultra Lock Screen Password</u></a></li>
<li><a href="https://win11.techidaily.com/transform-spending-habits-with-premium-windows-11-pro-key/"><u>Transform Spending Habits with Premium Windows 11 Pro Key</u></a></li>
<li><a href="https://win11.techidaily.com/linking-legacy-and-modernity-initiating-windows-11-with-a-window-7-code/"><u>Linking Legacy and Modernity: Initiating Windows 11 with a Window 7 Code</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-10-top-inspirational-movies-for-personal-power-boosts/"><u>[Updated] 10 Top Inspirational Movies for Personal Power Boosts</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-admins-rights-issue-in-win-os/"><u>Bypassing Admins Rights Issue in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/1719361152872-lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-startup-in-windows-11/"><u>Mastering Fast Startup in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stalling-windows-auto-updates-four-methods/"><u>Stalling Windows Auto-Updates: Four Methods</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-blur-the-video-background-in-after-effects/"><u>Updated How To Blur The Video Background in After Effects</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-heic-pictures-to-jpeg-in-w10w11/"><u>Transitioning HEIC Pictures to JPEG in W10/W11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-the-secrets-of-high-conversion-rates-in-youtube-banner-designs-for-2024/"><u>Unlocking the Secrets of High Conversion Rates in YouTube Banner Designs for 2024</u></a></li>
</ul></div>
