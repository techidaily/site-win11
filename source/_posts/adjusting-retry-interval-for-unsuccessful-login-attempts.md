---
title: Adjusting Retry Interval for Unsuccessful Login Attempts
date: 2024-08-16T00:41:11.308Z
updated: 2024-08-17T00:41:11.308Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
excerpt: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
keywords: Login Retry Adjustment,Unsuccessful Login Handling,Increase Login Retries,Manage Failed Logins,Login Attempt Limits,Optimize Login Intervals,Success Rate for Login Attempts
thumbnail: https://thmb.techidaily.com/4ac54b51c1cafa3a284440c31d27701c82afd968d6a73268fe3b019a529c7811.jpg
---

## Adjusting Retry Interval for Unsuccessful Login Attempts

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
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-make-a-youtube-subscribe-link-easy/"><u>[New] In 2024, How to Make a YouTube Subscribe Link - Easy</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-srt-power-play-transforming-macwindows-experience/"><u>[New] SRT Power Play  Transforming Mac/Windows Experience</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-thors-fury-legends-of-the-ragnarok/"><u>[New] Thor's Fury  Legends of the Ragnarök</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-craftsmanship-in-podcast-visuals-the-essentials/"><u>[Updated] Craftsmanship in Podcast Visuals  The Essentials</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-excellent-webcam-recorders-on-windows-10/"><u>[Updated] Excellent Webcam Recorders on Windows 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-maximize-your-impact-top-10-insta-tools-for-post-management/"><u>[Updated] In 2024, Maximize Your Impact  Top 10 Insta Tools for Post Management</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-natures-canvas-a-variety-of-downloads-to-enhance-cinematic-work/"><u>[Updated] Nature’s Canvas  A Variety of Downloads to Enhance Cinematic Work</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-pro-level-jump-cuts-in-final-cut-pro-x-tips-and-tricks/"><u>2024 Approved Pro-Level Jump Cuts in Final Cut Pro X Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/5-apps-that-elevate-your-desktop-writing-game/"><u>5 Apps That Elevate Your Desktop Writing Game</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-slash-energy-drain-by-default-desktop-window-manager/"><u>7 Ways to Slash Energy Drain by Default Desktop Window Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-look-at-windows-11-efficiency-mastering-processes-and-customizing-themes/"><u>A Deeper Look at Windows 11 Efficiency: Mastering Processes and Customizing Themes</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-layer-of-simplicity-in-windows-photos-app-deletion/"><u>A New Layer of Simplicity in Windows Photos App Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-winning-website-conversion/"><u>A Step-by-Step for Winning Website Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-personalized-typing-mastering-keybinding-w11/"><u>A Window Into Personalized Typing: Mastering Keybinding W11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-windows-based-excel-tasks-a-guide/"><u>Accelerating Windows-Based Excel Tasks: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11-volume-mixer-shortcut/"><u>Accessing Windows 11 Volume Mixer Shortcut</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-guide-transforming-heic-images-into-jpeg-format-with-w11-ease/"><u>Accurate Guide: Transforming HEIC Images Into JPEG Format with W11 Ease</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-media-player-for-a-streamlined-start/"><u>Activating Windows Media Player for a Streamlined Start</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-windows-11s-anti-phishing-filter/"><u>Activating/Deactivating Windows 11'S Anti-Phishing Filter</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-failure-notifications-in-w10w11-pcs/"><u>Addressing 'Device Failure' Notifications in W10/W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-error-after-device-removal/"><u>Addressing DXGI Error After Device Removal</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-system-settings-for-outdated-app-packages/"><u>Adjusting System Settings for Outdated App Packages</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-filters-enable-or-disable-safeguard/"><u>Adjusting Windows Filters: Enable or Disable SafeGuard</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-system-interactions-a-step-bystep-guide/"><u>Advanced File System Interactions: A Step-Bystep Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-imaging-separating-subjects-from-surroundings/"><u>Advanced Imaging: Separating Subjects From Surroundings</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-time-honored-directx-experiences-through-dxvk/"><u>Augmenting Time-Honored DirectX Experiences Through DXVK</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-not-working-mishaps-on-your-devices-windows-apps/"><u>Avoiding 'Not Working' Mishaps on Your Device’s Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-smart-note-management-for-windows/"><u>Avoiding Clutter: Smart Note Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-blank-screens-windows-10-and-11-troubleshooting/"><u>Banishing Blank Screens: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-restore-visual-clarity-in-winos/"><u>Best Practices to Restore Visual Clarity in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/best-ways-to-restore-default-window-options-on-system-startup/"><u>Best Ways to Restore Default Window Options on System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/bigger-capacity-but-lagging-in-little-pcs-mp60/"><u>Bigger Capacity but Lagging in Little PCs (MP60)</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://win11.techidaily.com/boltgun-performance-tips-to-resolve-on-pc-interruptions/"><u>Boltgun Performance Tips to Resolve On-PC Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-barriers-to-customizing-windows-11-apps/"><u>Breaking Down the Barriers to Customizing Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-functions-of-winservicesexe/"><u>Breaking Down the Functions of Winservices.exe</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/high-ranking-top-5-quick-screen-recorders-for-2024/"><u>High Ranking - Top 5 Quick Screen Recorders for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-data-retrieval-tool-restore-lost-data-from-honor-by-fonelab-android-recover-data/"><u>Honor Data Retrieval tool – restore lost data from Honor</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-infinix-gt-10-pro-is-unlocked-by-drfone-android/"><u>How To Check if Your Infinix GT 10 Pro Is Unlocked</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-and-install-new-drivers-for-your-canon-mp250-printer/"><u>How to Get & Install New Drivers for Your Canon MP250 Printer</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-stop-microsoft-edge-from-crashing-on-windows-11-proven-fixes/"><u>How to Stop Microsoft Edge From Crashing on Windows 11 - Proven Fixes!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-harness-the-power-of-video-editing-cropping-to-perfect-instagram-posts/"><u>In 2024, Harness the Power of Video Editing  Cropping to Perfect Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/1719367447353-multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-ultimate-guide-to-the-top-8-acoustic-themes-for-professional-video-enhancement-for-2024/"><u>New The Ultimate Guide to the Top 8 Acoustic Themes for Professional Video Enhancement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719367274054-overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/pros-and-cons-of-opting-for-a-local-llm-is-it-the-right-choice/"><u>Pros & Cons of Opting for a Local LLM: Is It the Right Choice?</u></a></li>
<li><a href="https://extra-support.techidaily.com/ranked-the-best-5-iphones-for-effortless-podcast-access-for-2024/"><u>Ranked  The Best 5 iPhones for Effortless Podcast Access for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-narzo-n55-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Narzo N55 has been deleted.</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-honor-magic-6-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Honor Magic 6</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/syncing-tiktok-content-with-twitter/"><u>Syncing TikTok Content with Twitter</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-essential-guide-to-youtube-edits-with-premiere-pro-for-2024/"><u>The Essential Guide to YouTube Edits with Premiere Pro for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-methodical-path-to-discovering-hidden-youtube-footage/"><u>The Methodical Path to Discovering Hidden YouTube Footage</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-14-pro-max-screen-lock-without-losing-data-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 14 Pro Max screen lock without losing data</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-best-9-french-video-translators-online-and-download-options-for-2024/"><u>Updated Best 9 French Video Translators Online and Download Options for 2024</u></a></li>
</ul></div>
