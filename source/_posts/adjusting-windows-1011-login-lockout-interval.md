---
title: Adjusting Windows 10/11 Login Lockout Interval
date: 2024-08-16T00:33:09.202Z
updated: 2024-08-17T00:33:09.202Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows 10/11 Login Lockout Interval
excerpt: This Article Describes Adjusting Windows 10/11 Login Lockout Interval
keywords: Win10/11 Account Lock Time,Windows Login Cooldown,Adjusting Lockout Timers,Modify Window Logon Delay,Reset PC Login Intervals,Shorten Windows Lockouts,Tweak Windows Logon Timer
thumbnail: https://thmb.techidaily.com/1734faea8dc6fb99b0356fb7510aa58c46806122f440ead1dafd4f608890d169.png
---

## Adjusting Windows 10/11 Login Lockout Interval

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-11-free-youtube-playlist-downloaders-onlinepcandroidios/"><u>[New] 2024 Approved  11 FREE YouTube Playlist Downloaders [Online/PC/Android/iOS]</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-azure-profile-snapshot-analysis-resolution-codec-timeframe-for-2024/"><u>[New] AZURE Profile Snapshot Analysis  Resolution, Codec, Timeframe for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-expert-techniques-for-uploading-youtubes-on-dailymotion/"><u>[New] Expert Techniques for Uploading YouTubes on Dailymotion</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-snapchat-to-youtube-uploading-pics/"><u>[New] From Snapchat to YouTube  Uploading Pics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-curtail-unexpected-youtube-recommendations/"><u>[New] In 2024, Curtail Unexpected YouTube Recommendations</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-evasive-examiner-of-fb-narratives/"><u>[New] In 2024, Evasive Examiner of FB Narratives</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-insta-twist-magic-secrets-to-spinning-video-content-for-platform-perfection-for-2024/"><u>[New] Insta-Twist Magic  Secrets to Spinning Video Content for Platform Perfection for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-rapidly-create-facebook-collage-imagery-with-ease/"><u>[New] Rapidly Create Facebook Collage Imagery with Ease</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-for-ios-album-arrangement-and-icloud-cloud-syncing-mastery/"><u>[New] The Ultimate Guide for iOS Album Arrangement & iCloud Cloud Syncing Mastery</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-high-end-gamers-guide-to-switch-recordings/"><u>[Updated] 2024 Approved  High-End Gamers' Guide to Switch Recordings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-perfect-every-post-automated-mac-methods-for-instagram-video-sizing/"><u>[Updated] In 2024, Perfect Every Post  Automated Mac Methods for Instagram Video Sizing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-practical-tips-for-console-game-recordings/"><u>[Updated] Practical Tips for Console Game Recordings</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-streamline-editing-with-these-10-leading-software-tools/"><u>[Updated] Streamline Editing with These 10 Leading Software Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pocket-safari-androids-selection-of-best-simulators/"><u>2024 Approved  Pocket Safari  Android's Selection of Best Simulators</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-pivotal-points-for-reconnecting-your-obs-studio-link-win-compatible/"><u>7 Pivotal Points for Reconnecting Your OBS Studio Link (Win-Compatible)</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-sign-in-method-youre-trying-to-use-isnt-allowed-error-on-windows/"><u>8 Ways to Fix The Sign-In Method You're Trying to Use Isn't Allowed Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-fixes-for-troublesome-email-notifications-in-windows/"><u>9 Essential Fixes for Troublesome Email Notifications in Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-deep-dive-into-the-apple-macbook-air-13s-m1-202e-enhanced-capabilities-and-stunning-efficiency/"><u>A Deep Dive Into The Apple MacBook Air 13'S (M1, 202E) Enhanced Capabilities and Stunning Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/a-developers-journey-github-desktop-in-the-era-of-win-11/"><u>A Developer's Journey: GitHub Desktop in the Era of Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-keeping-your-tasks-visible-and-high-priority/"><u>A Guide to Keeping Your Tasks Visible and High-Priority</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-v27e-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo V27e</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-systemsettings-issue-on-windows-11/"><u>Addressing SystemSettings Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-lockout-interval-after-multiple-login-failures/"><u>Adjusting Lockout Interval After Multiple Login Failures</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-alchemy-how-to-seamlessly-change-windows-11-themes-and-enrich-your-workspace/"><u>Aesthetic Alchemy: How to Seamlessly Change Windows 11 Themes and Enrich Your Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-unlicensed-adobe-errors/"><u>Avoid Windows 'Unlicensed' Adobe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-folder-empty-warning-on-windows-pcs/"><u>Avoiding Folder Empty Warning on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-power-and-performance-in-windows-systems/"><u>Balancing Power and Performance in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-darkness-expert-tips-for-solving-obs-game-capturing-issues/"><u>Beat the Darkness: Expert Tips for Solving OBS Game Capturing Issues</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-poco-x5-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Poco X5 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-manual-inputs-embracing-ai-in-windows-operations/"><u>Beyond Manual Inputs: Embracing AI in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-capabilities-upgrading-to-virtualbox-70-in-win11/"><u>Boost Your VM Capabilities: Upgrading to VirtualBox 7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://windows11.techidaily.com/brightening-up-dull-desktop-windows-appearance/"><u>Brightening Up Dull Desktop Windows Appearance</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discovering-easy-music-arrangement-in-magix-maker/"><u>Discovering Easy Music Arrangement in Magix Maker</u></a></li>
<li><a href="https://extra-information.techidaily.com/elite-drone-recommendations-to-boost-gopro-video-impact/"><u>Elite Drone Recommendations to Boost GoPro Video Impact</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-system-issues-of-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System Issues of Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-apple-iphone-13-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile Apple iPhone 13 online without SIM Card?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-accumulating-prime-visuals-for-content-creation/"><u>In 2024, Accumulating Prime Visuals for Content Creation</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-channel-prodigy-skyrocketing-with-content-innovation/"><u>In 2024, Channel Prodigy  Skyrocketing with Content Innovation</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-time-saving-tricks-for-powerpoint-projections/"><u>In 2024, Time-Saving Tricks for PowerPoint Projections</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagram-edition-the-finest-picture-fixers/"><u>Instagram Edition  The Finest Picture Fixers</u></a></li>
<li><a href="https://extra-support.techidaily.com/lean-cloud-archive-efficient-low-cost-large-data-for-2024/"><u>Lean Cloud Archive  Efficient, Low-Cost Large Data for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/m3-macbook-pro-launch-details-pricing-info-and-specifications-unveiled/"><u>M3 MacBook Pro Launch Details: Pricing Info & Specifications Unveiled</u></a></li>
<li><a href="https://some-skills.techidaily.com/mac-users-check-your-hardware-for-big-sur-for-2024/"><u>Mac Users, Check Your Hardware for Big Sur for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-free-mp4-video-editing-software-with-cutting-capabilities-for-2024/"><u>New Free MP4 Video Editing Software with Cutting Capabilities for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ltimate-blueprint-for-your-mobile-youtube-businesspersonal-platform-for-2024/"><u>The Ultimate Blueprint for Your Mobile YouTube Business/Personal Platform for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719320103482-windows-xbox-not-working-fix-it-fast/"><u>Windows Xbox Not Working? Fix It Fast!</u></a></li>
</ul></div>
