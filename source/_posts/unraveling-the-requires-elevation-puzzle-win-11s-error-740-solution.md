---
title: "Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution"
date: 2024-07-13T10:06:27.345Z
updated: 2024-07-14T10:06:27.345Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution"
excerpt: "This Article Describes Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution"
keywords: Win 11 Error Fix,Resolve Windows Error 740,Elevate Error Fixing,Solve Win Error 740,Easy Win 11 Error,Eliminate Error 740 Win,Overcoming Windows Error 740
thumbnail: https://thmb.techidaily.com/7a3bff4e2eede5438bb2fccedcb9095f7ad51baa5a8f2d8fdc6330db34850673.jpg
---

## Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution

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
<li><a href="https://techidaily.com/turn-off-screen-lock-nokia-c300-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Nokia C300</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-swift-solutions-for-adding-a-folder-to-onedrive-successfully/"><u>Troubleshooting Guide: Swift Solutions for Adding a Folder to OneDrive Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-the-ink-flow-pc-pen-and-touch-adjustments/"><u>Perfecting the Ink Flow: PC Pen and Touch Adjustments</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-building-your-brands-buzz-on-youtube-with-fresh-insights/"><u>In 2024, Building Your Brand's Buzz on Youtube with Fresh Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/bridge-ppt-content-with-video-channeling/"><u>Bridge PPT Content with Video Channeling</u></a></li>
<li><a href="https://facebook.techidaily.com/a-complete-archive-of-your-facebook-journey/"><u>A Complete Archive of Your Facebook Journey</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pcs-login-trail-a-win-flip-guide/"><u>Securing Your PC's Login Trail: A Win-Flip Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-free-logo-blueprints-to-refine-and-personalize-your-symbol/"><u>2024 Approved  Free Logo Blueprints to Refine and Personalize Your Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/nine-best-window-timers-enhancing-pomodoro-productivity/"><u>Nine Best Window Timers Enhancing Pomodoro Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winupdate-error-x8019/"><u>Troubleshooting WinUpdate Error X8019</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-filesystem-woes-a-win10win11-fixers-manual/"><u>Unpacking Filesystem Woes: A Win10/Win11 Fixer's Manual</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-securely-extract-and-convert-youtube-audios-as-mp3-for-2024/"><u>[New] How To Securely Extract and Convert YouTube Audios as MP3 for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-direct-to-device-converting-youtube-tracks-for-idevices/"><u>[New] In 2024, Direct to Device  Converting YouTube Tracks for iDevices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-app-management-with-winget-on-w11/"><u>Mastering App Management with Winget on W11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-top-video-lighting-adjustment-software/"><u>New 2024 Approved Top Video Lighting Adjustment Software</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-vivo-y200-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Vivo Y200</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-flickering-screens-windows-11-edition/"><u>Banishing Flickering Screens: Windows 11 Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-y55s-5g-2023-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo Y55s 5G (2023) Phones? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-instagram-mastery-easy-steps-to-great-collages/"><u>In 2024, Instagram Mastery  Easy Steps to Great Collages</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-resuming-windows-shared-space-visit/"><u>Unshackle: Resuming Windows Shared Space Visit</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/key-steps-to-screen-record-on-your-phone/"><u>Key Steps to Screen Record on Your Phone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-a-guide-to-excellence-with-zd-soft-screen-capture/"><u>[New] In 2024, A Guide to Excellence with ZD Soft Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-editing-the-win11-list-of-premier-video-scripts/"><u>Elevate Editing: The Win11 List of Premier Video Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11s-camera-app-glitch-afc-error/"><u>Resolving Windows 11'S Camera App Glitch: AFC Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-microsoft-store-error-0x80073cf3/"><u>Steps to Resolve Microsoft Store Error 0X80073CF3</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-swift-skim-windows-file-compilation/"><u>2024 Approved  Swift Skim Windows File Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-pc-windows-11-device-options-revised/"><u>Customize Your PC: Windows 11 Device Options Revised</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-show-more-pins-on-win-11-startscreen/"><u>Techniques to Show More Pins on Win 11 Startscreen</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-ultimate-blueprint-adopting-mobizen-screen-recording-skills/"><u>[New] 2024 Approved  The Ultimate Blueprint  Adopting Mobizen Screen Recording Skills</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-vivo-y100a-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Vivo Y100A Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-microsoft-store-color-glitches/"><u>Resolving Microsoft Store Color Glitches</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-professional-results-for-free-top-4k-video-editing-software-choices-for-2024/"><u>Updated Professional Results for Free Top 4K Video Editing Software Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them.</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-inside-the-world-of-discord-nitro-highlights-and-acquisition-strategies/"><u>2024 Approved  Inside the World of Discord Nitro  Highlights and Acquisition Strategies</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-iphone-x-after-ios-update-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Lost Data from iPhone X After iOS Update? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-office-activation-setbacks/"><u>Navigating Through Failed Office Activation Setbacks</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-top-choices-for-unconventional-peer-to-peer-dialogue-platforms-safety-efficiency-pleasure/"><u>New 2024 Approved Top Choices for Unconventional Peer-to-Peer Dialogue Platforms Safety, Efficiency, Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/digital-retrofit-modernizing-windows-11-with-a-98-twist/"><u>Digital Retrofit: Modernizing Windows 11 with a '98 Twist</u></a></li>
<li><a href="https://facebook.techidaily.com/claiming-a-portion-of-the-mega-settlement-from-facebook/"><u>Claiming a Portion of the Mega-Settlement From Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-the-missing-search-back-into-win11s-task-manager/"><u>Bringing the Missing Search Back Into Win11's Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-detection-of-razer-devices-by-synapse-software/"><u>Reinstating Detection of Razer Devices by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-ntoskrnlexe-process/"><u>Tackling Excessive Ntoskrnl.exe Process</u></a></li>
<li><a href="https://win11.techidaily.com/solving-uninstall-issues-in-windows-11/"><u>Solving Uninstall Issues in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-most-effective-tactics-to-set-whatsapp-status/"><u>Updated 2024 Approved Most Effective Tactics to Set WhatsApp Status</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
<li><a href="https://extra-tips.techidaily.com/20-gratis-plus-purchasable-luts-enhance-canon-cams-for-2024/"><u>20 Gratis + Purchasable LUTs  Enhance Canon Cams for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Where Is the Best Place to Catch Dratini On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premium-free-graphic-havens-a-comprehensive-guide-to-top-art-portals-for-2024/"><u>Premium-Free Graphic Havens  A Comprehensive Guide to Top Art Portals for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/spectacular-racing-thrills-the-quintet/"><u>Spectacular Racing Thrills  The Quintet</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-prevent-unauthorized-access-on-windows/"><u>7 Ways to Prevent Unauthorized Access on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unexpected-token-call-issues-on-windows-devices/"><u>How To Resolve “Unexpected Token Call” Issues on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-process-unterminate-obstacles-in-windows/"><u>Overcoming 'Process Unterminate' Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-the-power-of-multiple-directories-windows-11-edition/"><u>Harnessing the Power of Multiple Directories: Windows 11 Edition</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-cars-mouse-keys-and-acceleration-mastery/"><u>Winning Cars: Mouse, Keys, and Acceleration Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-surge-troubleshoot-for-a-swift-windows-11/"><u>Speedy Surge: Troubleshoot for a Swift Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-variances-a-comparison-between-microsoft-and-standard-windows-accounts/"><u>Exploring Variances: A Comparison Between Microsoft and Standard Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-on-windows-11-easily/"><u>Enabling Hyper-V on Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-write-failure-in-windows/"><u>Overcoming Memory Write Failure in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-is-higher-frame-rate-better-weighing-30-vs-60fps-in-video/"><u>[New] 2024 Approved  Is Higher Frame Rate Better? Weighing 30 Vs. 60Fps in Video</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-grayed-out-extend-volume-option-in-disk-management-for-windows/"><u>How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-window-11-potential-7-tips/"><u>Unleash Your Window 11 Potential: 7 Tips</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-10-no-cost-video-conference-platforms-worklearn-edition/"><u>[Updated] Essential 10 No-Cost Video Conference Platforms  Work/Learn Edition</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-fixing-black-screens-and-blank-cursors-on-win11/"><u>Master the Art of Fixing Black Screens & Blank Cursors on Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-when-worlds-crumble-premium-guide-to-top-zombie-games/"><u>[New] When Worlds Crumble  Premium Guide to Top Zombie Games</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-iphone-15-pro-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T iPhone 15 Pro with 3 Methods</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-secrets-the-best-dronescopic-stabilizers-reviewed-for-2024/"><u>Unveiling Secrets  The Best Dronescopic Stabilizers Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/winning-every-game-with-smart-amd-radeon-configurations/"><u>Winning Every Game with Smart AMD Radeon Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps-on-windows-10-and-11/"><u>Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-y55s-5g-2023-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Vivo Y55s 5G (2023)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-package-revelation/"><u>The Art of Package Revelation</u></a></li>
</ul></div>
