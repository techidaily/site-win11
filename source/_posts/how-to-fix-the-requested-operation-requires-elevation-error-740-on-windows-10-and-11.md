---
title: How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11
date: 2024-07-13T10:42:30.793Z
updated: 2024-07-14T10:42:30.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11
excerpt: This Article Describes How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11
keywords: Windows 10 Elevate Error,10+11 Fix Err740,Solve WinError740,Resolve OS Elevation Issue,Overcome Windows Elevation,Fix Elevate Req on PC,Eradicate WinErr740 Error
thumbnail: https://thmb.techidaily.com/84fef5f35988a89f310851ba69e27f36f222e4900085b075caa3fb4e05a962a8.jpg
---

## How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-top-30-free-mac-speech-to-text-software-youve-missed/"><u>In 2024, Top 30 Free Mac Speech-to-Text Software You've Missed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-boosting-your-content-a-guide-to-instagram-video-fame/"><u>[New] Boosting Your Content  A Guide to Instagram Video Fame</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/free-youtube-money-calculators-calculate-youtube-money/"><u>Free YouTube Money Calculators-Calculate YouTube Money</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-exploring-differences-between-igtv-and-youtube-for-effective-posts/"><u>[New] 2024 Approved  Exploring Differences Between IGTV and YouTube for Effective Posts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-ultimate-guide-to-video-call-capturing-on-devices/"><u>2024 Approved  The Ultimate Guide to Video Call Capturing on Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-from-iphone-6-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock From iPhone 6 Online</u></a></li>
<li><a href="https://win11.techidaily.com/dispel-limitations-escalating-internet-speed-past-100mbps-in-windows/"><u>Dispel Limitations: Escalating Internet Speed Past 100Mbps in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-vivo-y36-easily-by-drfone-android/"><u>In 2024, How To Unlock a Vivo Y36 Easily?</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolving-inbox-notifications-on-pcs/"><u>Comprehensive Guide to Resolving Inbox Notifications on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-elevate-online-engagement-unlocking-the-potential-of-voicemod-on-discord/"><u>In 2024, Elevate Online Engagement  Unlocking the Potential of VoiceMod on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-clear-obstacles-no-access-allowed-windows-errors/"><u>Methods to Clear Obstacles: No Access Allowed Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-abcs-of-facebook-cover-video-production/"><u>[New] In 2024, The ABCs of Facebook Cover Video Production</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-huawei-p60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-error-0x800700e1-in-windows-11-os/"><u>Essential Fixes for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-video-memory-crashes-in-hogwarts-legacy-windows-edition/"><u>Remedying Video Memory Crashes in 'Hogwarts: Legacy' Windows Edition</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-tecno-spark-10-pro-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/mastering-the-art-of-flawless-podcast-production-your-comprehensive-tutorial-for-2024/"><u>Mastering the Art of Flawless Podcast Production Your Comprehensive Tutorial for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-x90s-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo X90S Phones</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-universal-video-editing-solutions-35-options-for-every-device-and-os/"><u>Updated Universal Video Editing Solutions 35 Options for Every Device and OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-navigating-digital-dialogues-insider-secrets-to-proficient-zoom-conversations-for-2024/"><u>[Updated] Navigating Digital Dialogues  Insider Secrets to Proficient Zoom Conversations for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-guidelines-for-authoritative-life-lesson-videos-for-2024/"><u>[Updated] Guidelines for Authoritative Life Lesson Videos for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pioneering-excellence-leading-vr-creators/"><u>[Updated] Pioneering Excellence  Leading VR Creators</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-expressive-commentary-utilizing-emojis-on-youtube/"><u>[New] In 2024, Expressive Commentary  Utilizing Emojis on YouTube</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>How to get the dragon scale and evolution-enabled pokemon On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-apple-iphone-12-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On Apple iPhone 12? Heres the Best Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-content-gold-youtube-studios-path-to-perfection/"><u>[New] 2024 Approved  Crafting Content Gold  YouTube Studio's Path to Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-strategies-your-file-explorer-fixes/"><u>Rebooting Strategies: Your File Explorer Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elite-screen-grabbers-5-non-windows-counterparts-to-snipping-tool/"><u>Elite Screen Grabbers: 5 Non-Windows Counterparts to Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/reorient-your-windows-a-guide-to-90-degree-display-adjustment/"><u>Reorient Your Windows: A Guide to 90-Degree Display Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-civ-5-crashing-issues-on-pc/"><u>Fix CIV 5 Crashing Issues On PC</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today!</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-oppo-reno-10-proplus-5g-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Oppo Reno 10 Pro+ 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unlocking-creativity-free-animation-techniques/"><u>2024 Approved  Unlocking Creativity  Free Animation Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/from-simple-logon-to-strong-authentication-changing-your-windows-11-login-habit/"><u>From Simple Logon to Strong Authentication: Changing Your Windows 11 Login Habit</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vanished-hardware-on-windows/"><u>Resolving Vanished Hardware on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-contemporary-voiceover-practices-for-dynamic-video-creation-an-updated-guide/"><u>Updated Contemporary Voiceover Practices for Dynamic Video Creation - An Updated Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-lava-storm-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Lava Storm 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-windows-essence-crafting-and-evaluating-system-data/"><u>Peering Into Windows Essence: Crafting & Evaluating System Data</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-a-simple-yet-effective-guide-for-starting-a-skype-group-discussion-across-different-os-platforms/"><u>[Updated] In 2024, A Simple yet Effective Guide for Starting a Skype Group Discussion Across Different OS Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-delaying-windows-10-shutdown-processes/"><u>Mastering the Art of Delaying Windows 10 Shutdown Processes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-motorola-defy-2-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Motorola Defy 2 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
</ul></div>
