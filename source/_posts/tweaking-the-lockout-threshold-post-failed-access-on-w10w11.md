---
title: Tweaking the Lockout Threshold Post-Failed Access on W10/W11
date: 2024-07-13T11:04:29.243Z
updated: 2024-07-14T11:04:29.243Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Lockout Threshold Post-Failed Access on W10/W11
excerpt: This Article Describes Tweaking the Lockout Threshold Post-Failed Access on W10/W11
keywords: Failed Access Prevention,Windows 10 Security,Access Control Settings,W10 Lockout Adjustment,W11 Post-Access Threshold,Update Account Lockouts,Access Failure Management
thumbnail: https://thmb.techidaily.com/88b9d1a1839e87bc852a7b88397e12987972348fa38a161adde19f109b06aa2c.jpg
---

## Tweaking the Lockout Threshold Post-Failed Access on W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-for-superior-4k-visual-quality-with-gear/"><u>2024 Approved  Expert Tips for Superior 4K Visual Quality with Gear</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-nokia-c12-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Nokia C12 FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-detection-of-razer-devices-by-synapse-software/"><u>Reinstating Detection of Razer Devices by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-code-0xc00ce556/"><u>Navigating Windows Error Code: 0XC00CE556</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-no-expense-yes-watch-one-frame-at-a-time-on-youtube/"><u>[New] No Expense? Yes! Watch One Frame at a Time on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-prevent-unauthorized-access-on-windows/"><u>7 Ways to Prevent Unauthorized Access on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-pc-windows-11-device-options-revised/"><u>Customize Your PC: Windows 11 Device Options Revised</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-driving-engagement-on-instagram-strategy-for-successful-video-content-for-2024/"><u>[Updated] Driving Engagement on Instagram  Strategy for Successful Video Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-fixing-audacitys-failed-sound-device-openings-on-win-os/"><u>Methods for Fixing Audacity's Failed Sound Device Openings on Win OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-charting-a-course-through-creative-professions/"><u>In 2024, Charting a Course Through Creative Professions</u></a></li>
<li><a href="https://win11.techidaily.com/1719347376759-efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7.</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-microsoft-edges-heavy-background-tasks/"><u>Curbing Microsoft Edge's Heavy Background Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-apowersoft-screen-recorder-review-and-alternative/"><u>[Updated] In 2024, Apowersoft Screen Recorder Review and Alternative</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-process-termination-errors-effortlessly/"><u>Bypassing Process Termination Errors Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-the-ink-flow-pc-pen-and-touch-adjustments/"><u>Perfecting the Ink Flow: PC Pen and Touch Adjustments</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-video-appeal-crafting-unforgettable-thumbnail-images-for-2024/"><u>[New] Elevate Video Appeal  Crafting Unforgettable Thumbnail Images for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-swift-solutions-for-adding-a-folder-to-onedrive-successfully/"><u>Troubleshooting Guide: Swift Solutions for Adding a Folder to OneDrive Successfully</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/quit-quickly-leave-facebook-lives-on-pc-and-pads/"><u>Quit Quickly  Leave Facebook Lives on PC & Pads</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-everything-you-want-to-know-about-kapwing-video-translation/"><u>Updated In 2024, Everything You Want To Know About Kapwing Video Translation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-path-to-efficient-workflow-learning-voice-to-text-conversion-in-ms-word/"><u>2024 Approved  The Path to Efficient Workflow  Learning Voice-to-Text Conversion in MS Word</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-by-step-guide-to-adding-your-own-video-images/"><u>[Updated] Step-by-Step Guide to Adding Your Own Video Images</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/get-started-with-video-editing-best-free-resources-desktoponlinemobile-for-2024/"><u>Get Started with Video Editing Best Free Resources Desktop/Online/Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ace-your-laughs-kinemaster-for-top-memes-for-2024/"><u>Ace Your Laughs  KineMaster for Top Memes for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-methods-for-rolling-macos-sierra-back-to-el-capitan/"><u>In 2024, Methods for Rolling MacOS Sierra Back to El Capitan</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-capturing-sound-in-presentations-a-step-by-step-windows-and-mac-tutorial/"><u>In 2024, Capturing Sound in Presentations A Step-by-Step Windows & Mac Tutorial</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-realme-c67-5g-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Realme C67 5G</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-10-mobile-and-desktop-video-chat-apps-for-2024/"><u>Top 10 Mobile & Desktop Video Chat Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/nine-best-window-timers-enhancing-pomodoro-productivity/"><u>Nine Best Window Timers Enhancing Pomodoro Productivity</u></a></li>
<li><a href="https://article-files.techidaily.com/new-the-ultimate-directory-top-10-sources-for-free-graphics/"><u>[New] The Ultimate Directory  Top 10 Sources for Free Graphics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-substitutes-for-winmovie-new-windows-editors/"><u>[Updated] Substitutes for WinMovie  New Windows Editors</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-a-runtime-broker-unpacking-its-importance-for-pcs/"><u>What Is a Runtime Broker? Unpacking Its Importance for PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/digital-dome-streamlining-your-song-posts-on-youtube/"><u>Digital Dome  Streamlining Your Song Posts on YouTube</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-iphone-xs-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass iPhone XS Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-elevate-engagement-the-hottest-tiktok-hashtags-for-now/"><u>[New] In 2024, Elevate Engagement  The Hottest TikTok Hashtags for Now</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-activating-windows-recovery-software/"><u>Key Steps for Activating Windows Recovery Software</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-the-power-of-multiple-directories-windows-11-edition/"><u>Harnessing the Power of Multiple Directories: Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-ultimate-guide-to-in-frame-multimedia-experience-on-mac/"><u>[Updated] The Ultimate Guide to In-Frame Multimedia Experience on Mac</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-top-10-most-watched-music-videos-on-fb-for-2024/"><u>[Updated] Top 10 Most Watched Music Videos on FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/digital-retrofit-modernizing-windows-11-with-a-98-twist/"><u>Digital Retrofit: Modernizing Windows 11 with a '98 Twist</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-cloud-file-retrieval-methods/"><u>Cross-Platform Cloud File Retrieval Methods</u></a></li>
<li><a href="https://win11.techidaily.com/winning-cars-mouse-keys-and-acceleration-mastery/"><u>Winning Cars: Mouse, Keys, and Acceleration Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-flickering-screens-windows-11-edition/"><u>Banishing Flickering Screens: Windows 11 Edition</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ng-into-payment-structures-for-maker-profit-in-video-shorts/"><u>Peering Into Payment Structures for Maker Profit in Video Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-microsoft-store-color-glitches/"><u>Resolving Microsoft Store Color Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-lenovo-thinkphone-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Lenovo ThinkPhone without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://win11.techidaily.com/winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them.</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-what-are-youtube-tags-and-how-can-you-find-great-tags-for-your-videos/"><u>[New] 2024 Approved  What Are YouTube Tags and How Can You Find Great Tags For Your Videos?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-vivo-g2-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Vivo G2 Device SIM</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-from-your-iphone-12-mini-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID From your iPhone 12 mini?</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>How to Check Distance and Radius on Google Maps For your Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-resize-flv-videos-efficiently-windows-macandroid-iphone-and-online/"><u>New How to Resize FLV Videos Efficiently Windows, Mac，Android, iPhone & Online</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-original-icon-placement/"><u>Winning Back Original Icon Placement</u></a></li>
</ul></div>
