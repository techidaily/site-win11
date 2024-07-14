---
title: Adjusting Windows 10/11 Login Lockout Interval
date: 2024-07-13T10:00:12.187Z
updated: 2024-07-14T10:00:12.187Z
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

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

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
<li><a href="https://sound-optimizing.techidaily.com/updated-ranking-the-ultimate-selection-the-9-superior-podcast-microphones/"><u>Updated Ranking the Ultimate Selection The 9 Superior Podcast Microphones</u></a></li>
<li><a href="https://win11.techidaily.com/digging-deep-into-digital-details-step-by-step/"><u>Digging Deep Into Digital Details, Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-mp3s-to-audio-cds-using-imgburn/"><u>Windows Guide: Converting MP3s to Audio CDs Using ImgBurn</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-mastering-effective-social-media-video-promos/"><u>In 2024, Mastering Effective Social Media Video Promos</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-guide-to-online-image-aspect-ratio-changers-for-2024/"><u>New The Ultimate Guide to Online Image Aspect Ratio Changers for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-experience-the-pinnacle-of-free-fb-image-and-vfx-crafting/"><u>[New] Experience the Pinnacle of Free FB Image and VFX Crafting</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-reactivating-a-greyed-out-secure-boot-in-bios/"><u>Steps for Reactivating a Greyed Out Secure Boot in BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-windows-file-explorer-efficiently/"><u>Reactivate Windows File Explorer Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/configure-windows-apps-with-personalized-keys/"><u>Configure Windows Apps with Personalized Keys</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-chaos-of-mbr-errors-with-data-interpretation/"><u>Taming the Chaos of MBR Errors with Data Interpretation</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-blue-screen-error/"><u>Strategies for Overcoming Blue Screen Error</u></a></li>
<li><a href="https://win11.techidaily.com/remedial-actions-for-incorrect-app-configuration/"><u>Remedial Actions for Incorrect App Configuration</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-partner-up-strategies-optimal-selection-for-youtube-teams/"><u>2024 Approved  Partner Up Strategies  Optimal Selection for YouTube Teams</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unleash-creativity-premium-editors-for-mobile-and-desktop-oses/"><u>In 2024, Unleash Creativity  Premium Editors for Mobile & Desktop OSes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-infinix-hot-40-lock-screen-password-by-drfone-android/"><u>How To Change Infinix Hot 40 Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-fixing-broken-internet-connections-6-strategies-for-windows-users/"><u>The Art of Fixing Broken Internet Connections - 6 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-the-default-windows-clock-configuration/"><u>Protecting the Default Windows Clock Configuration</u></a></li>
<li><a href="https://youtube-data.techidaily.com/culpting-waterway-content-with-flair/"><u>[New] Sculpting Waterway Content with Flair</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keyboard-mastery-with-typingaid/"><u>Swift Keyboard Mastery with TypingAid</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-understanding-snapchats-emojis-more-than-just-fun-for-2024/"><u>[New] Understanding Snapchat's Emojis  More Than Just Fun for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-audio-alchemy-transforming-your-windows-11-projects-with-sound/"><u>[Updated] Audio Alchemy  Transforming Your Windows 11 Projects with Sound</u></a></li>
<li><a href="https://win11.techidaily.com/regain-access-to-microsoft-store-features-on-pcs/"><u>Regain Access to Microsoft Store Features on PCs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/customizing-your-pixels-melodic-identity/"><u>Customizing Your Pixel's Melodic Identity</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sea-to-sea-recording-best-action-cameras-for-anglers-for-2024/"><u>Sea-to-Sea Recording  Best Action Cameras for Anglers for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-a-comprehensive-list-of-frames-to-upgrade-your-photos-on-instagram/"><u>[New] A Comprehensive List of Frames to Upgrade Your Photos on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-app-support-issues-on-newer-windows/"><u>Techniques to Address App Support Issues on Newer Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-the-power-of-java-sdk-on-windows-11/"><u>Unleashing the Power of Java SDK on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tactics-for-using-windows-explorer-not-ls/"><u>Powerful Tactics for Using Windows Explorer, Not LS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-mac-video-trimming-made-easy-fast-and-efficient-methods/"><u>New In 2024, Mac Video Trimming Made Easy Fast and Efficient Methods</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-hardware-alerts-in-windows/"><u>Troubleshooting Steps for Hardware Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-using-windows-11-toolbars-effectively/"><u>The Pathway to Using Window's 11 Toolbars Effectively</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-find-the-perfect-free-video-editor-app-for-iphones-and-ipads/"><u>[Updated] In 2024, Find the Perfect Free Video Editor App for iPhones & iPads</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-free-10-websites-to-watch-cartoon-online-in-hd-for-2024/"><u>New FREE 10 Websites to Watch Cartoon Online in HD for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unidentified-component-in-windows-lsass/"><u>Quick Fixes for Unidentified Component in Windows Lsass</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-inquiry-speed-using-everythingapp/"><u>Boost PC Inquiry Speed Using EverythingApp</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-honor-90-lite-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Honor 90 Lite? Look No Further | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-engaging-consumer-openings/"><u>2024 Approved  Engaging Consumer Openings</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-list-of-3d-video-makers-free-paid-and-in-between/"><u>The Ultimate List of 3D Video Makers Free, Paid, and In-Between</u></a></li>
<li><a href="https://win11.techidaily.com/best-vm-options-compatible-with-windows-11-pcs/"><u>Best VM Options Compatible With Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-getting-past-windows-update-hitches/"><u>Quick Fixes: Getting Past Windows Update Hitches</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-amplification-of-combined-enthusiasm-trend/"><u>2024 Approved Amplification of Combined Enthusiasm Trend</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-master-the-art-of-video-editing-with-top-7-sounds-selections/"><u>[Updated] 2024 Approved  Master the Art of Video Editing with Top 7 Sounds Selections</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-spread-laughter-with-simple-steps-in-kinemaster/"><u>[New] Spread Laughter with Simple Steps in KineMaster</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-frostbound-feats-olympic-ice-innovations/"><u>2024 Approved  Frostbound Feats  Olympic Ice Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-firewall-4-methods-explored/"><u>Bypassing Disabled Windows Firewall: 4 Methods Explored</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-9-methods-for-altering-windows-sound-settings/"><u>Unlock 9 Methods for Altering Windows Sound Settings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-seamlessly-engage-fb-live-on-your-roku-screen/"><u>[New] In 2024, Seamlessly Engage  FB Live on Your Roku Screen</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-unleashing-your-creative-potential-the-comprehensive-guide-to-volume-automation-and-ducking-with-adobe-premiere-pro-mac-edition/"><u>Updated Unleashing Your Creative Potential The Comprehensive Guide to Volume Automation and Ducking with Adobe Premiere Pro (Mac Edition)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/weekly-hits-cant-skip-these-tiktok-tests-for-2024/"><u>Weekly Hits  Can't Skip These TikTok Tests for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-startup-options-your-ultimate-guidebook/"><u>Decoding Windows Startup Options: Your Ultimate Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-delay-in-windows-11-keys-7-proven-methods/"><u>Reduce Delay in Windows 11 Keys: 7 Proven Methods</u></a></li>
<li><a href="https://win11.techidaily.com/choco-vs-wslm-optimal-windows-software-downloader/"><u>Choco vs WSLM: Optimal Windows Software Downloader</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-security-six-pathways-for-safe-mode/"><u>Accessing Windows 11'S Security: Six Pathways for Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigating-the-challenges-of-itunes-on-windows-pcs/"><u>Circumnavigating the Challenges of iTunes On Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/win11-control-panel-lost-find-unlisted-system-configurations/"><u>Win11 Control Panel Lost, Find Unlisted System Configurations</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-solve-invisible-frames-in-video-capture-software/"><u>[Updated] In 2024, Solve Invisible Frames in Video Capture Software</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-way-to-windows-11-group-policies/"><u>Streamline Your Way to Windows 11 Group Policies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-color-coding-mastery-the-most-essential-lightroom-luts-you-need-to-know/"><u>2024 Approved  Color Coding Mastery  The Most Essential Lightroom LUTs You Need to Know</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-samsung-galaxy-f54-5g-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Samsung Galaxy F54 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-how-to-recover-lost-x-configuration/"><u>Unraveling the Mystery: How to Recover Lost X Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/14-ways-to-make-irresistible-gourmet-vids-for-2024/"><u>14 Ways to Make Irresistible Gourmet Vids for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-pro-tools-for-pc-gamers-screen-record-windows-10/"><u>[New] In 2024, Pro Tools for PC Gamers  Screen Record Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/altering-network-addresses-on-win11/"><u>Altering Network Addresses on Win11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-some-must-know-useful-lego-animation-ideas-for-you/"><u>2024 Approved Some Must-Know Useful Lego Animation Ideas for You</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-chatcam-video-saver-app/"><u>[Updated] In 2024, ChatCam Video Saver App</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-evasive-moves-for-a-shadowbanned-tiktoker-for-2024/"><u>[New] Evasive Moves for a Shadowbanned TikToker for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-amplify-volume-for-twitters-silent-videos/"><u>[New] In 2024, Amplify Volume for Twitter's Silent Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/full-utilization-of-final-cut-pro-an-in-depth-guide/"><u>Full Utilization of Final Cut Pro  An In-Depth Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-robot-generated-passwords-for-win-11-access/"><u>Bypassing Robot-Generated Passwords for Win 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-n-series-what-you-need-to-know/"><u>Delving Into Windows N Series: What You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/correct-the-dimmed-extend-option-on-windows-explorer/"><u>Correct the Dimmed Extend Option on Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/cortanas-farewell-windows-future-awaits/"><u>Cortana's Farewell, Windows' Future Awaits</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-diverse-iptv-platforms-integration/"><u>In 2024, Diverse IPTV Platforms Integration</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-cpuram-drain-from-consuming-video-content/"><u>Reducing CPU/RAM Drain From Consuming Video Content</u></a></li>
</ul></div>
