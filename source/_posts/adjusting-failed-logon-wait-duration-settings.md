---
title: Adjusting Failed Logon Wait Duration Settings
date: 2024-08-15T23:19:35.234Z
updated: 2024-08-16T23:19:35.234Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Failed Logon Wait Duration Settings
excerpt: This Article Describes Adjusting Failed Logon Wait Duration Settings
keywords: Login Failure Time Adjustment,Increase Logon Wait Time,Extend Lockout Periods,Reduce Logon Denial Rate,Delay Failed Login Attempts,Lengthen Unsuccessful Login Countdown,Elevate Retry Intervals
thumbnail: https://thmb.techidaily.com/860b3898b4af7e1c1dc6c593b5d2eb5997c8c8e6aad583a53288672db7b6ce02.jpg
---

## Adjusting Failed Logon Wait Duration Settings

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-a-comprehensive-guide-to-hp-laptops-screen-recording-features/"><u>[New] A Comprehensive Guide to HP Laptop's Screen Recording Features</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-best-laptops-for-video-editing/"><u>[New] The Best Laptops for Video Editing</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-immaculate-game-recordings-with-obs-studio-pro/"><u>[Updated] 2024 Approved  Immaculate Game Recordings with OBS Studio Pro</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-insta-wealth-tactics-for-transforming-passion-projects-into-paid-opportunities/"><u>[Updated] 2024 Approved  Insta-Wealth  Tactics for Transforming Passion Projects Into Paid Opportunities</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-androidiphone-instruction-adding-music-files-to-fb-profile/"><u>[Updated] Android/iPhone Instruction  Adding Music Files to FB Profile</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-exclusive-screen-time-delight-with-these-top-offline-games-for-2024/"><u>[Updated] Exclusive Screen Time Delight with These Top Offline Games for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-complete-breakdown-of-game-capture-in-overwatch/"><u>[Updated] In 2024, The Complete Breakdown of Game Capture in Overwatch</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-crafting-your-own-android-ringtones-and-sounds/"><u>[Updated] Step-By-Step  Crafting Your Own Android Ringtones and Sounds</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-routine-for-large-files-journey-from-iphones-to-macs/"><u>[Updated] The Ultimate Routine for Large Files' Journey From iPhones to Macs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-overcoming-connectivity-issues-in-your-live-feed/"><u>2024 Approved  Overcoming Connectivity Issues in Your Live Feed</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-the-windows-snip-and-sketch-tool-wont-screenshot-the-entire-screen/"><u>4 Fixes to Try if the Windows Snip & Sketch Tool Won’t Screenshot the Entire Screen</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/8-strategies-to-solve-vmware-booting-woes-on-win11/"><u>8 Strategies to Solve VMware Booting Woes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-to-install-and-configure-microsoft-pc-manager/"><u>A Compreran Guide to Install and Configure Microsoft PC Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-permanently-vanish-language-sign-on-win11-ui/"><u>A Guide to Permanently Vanish Language Sign on Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-performance-swapping-outdated-windows-drivers/"><u>Accelerating Performance: Swapping Outdated Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-transfers-avoiding-sudden-speed-slumps/"><u>Accelerating Steam Transfers: Avoiding Sudden Speed Slumps</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-removable-storage-via-explore-navigation-menu/"><u>Adding Removable Storage via Explore Navigation Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-timed-lock-screen-issue-windows/"><u>Addressing Faulty Timed Lock Screen Issue Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functioning-windows-conditional-filters/"><u>Addressing Non-Functioning Windows Conditional Filters</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-troubleshooting-locating-and-fixing-system-error-messages-using-commands/"><u>Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-volume-control-on-windows-bluetooth/"><u>Amplifying Volume Control on Windows-Bluetooth</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/apple-iphone-xs-max-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>Apple iPhone XS Max Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-steam-deck-challenger-the-rog-ally/"><u>ASUS's Steam Deck Challenger: The ROG Ally?</u></a></li>
<li><a href="https://win11.techidaily.com/auto-displaying-images-craft-your-windows-11-slide-show-7-ways/"><u>Auto-Displaying Images: Craft Your Windows 11 Slide Show (7 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-sonic-full-screen-pitfalls-on-windows-11-os/"><u>Avoiding Sonic Full-Screen Pitfalls on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blues-effective-methods-for-hybrid-os-errors-in-winxose/"><u>Beat the Blues: Effective Methods for Hybrid OS Errors in WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-overturning-monochrome-windows-display/"><u>Breaking Free: Overturning Monochrome Windows Display</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-x-fold-2-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo X Fold 2</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/essential-tips-for-a-novice-using-facebook-analytics-for-2024/"><u>Essential Tips for a Novice Using Facebook Analytics for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-purchasing-digital-ebooks-via-apples-books-app-on-your-ios-device/"><u>Guide: Purchasing Digital eBooks via Apple's Books App on Your iOS Device</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-90-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor 90 Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-realme-narzo-60x-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Realme Narzo 60x 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-14-pro-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 14 Pro Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-installation-errors-with-windows-1ns-version-1607-upgrade/"><u>How to Resolve Installation Errors with Windows 1N's Version 1607 Upgrade</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-12-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even On iPhone 12 If Youve Tried Everything</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-lava-blaze-curve-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Lava Blaze Curve 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-14-ultra-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi 14 Ultra Device</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-the-ultimate-list-5-best-video-editing-apps-for-ipad/"><u>In 2024, The Ultimate List 5 Best Video Editing Apps for iPad</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/smb-social-media-strategies-infographic-guide-for-2024/"><u>SMB Social Media Strategies  Infographic Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719231160491-streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/taking-pc-performance-to-the-next-level-with-crucials-pro-overclocking-ddr5-c36-ram-2x16gb-detailed-insights-and-benchmarks/"><u>Taking PC Performance to the Next Level with Crucial's Pro Overclocking DDR5 C36 RAM (2X16GB) - Detailed Insights & Benchmarks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-redmi-note-12t-pro-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi Redmi Note 12T Pro Location | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-the-secrets-to-earning-from-viral-snippets-for-2024/"><u>Unlocking the Secrets to Earning From Viral Snippets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
</ul></div>
