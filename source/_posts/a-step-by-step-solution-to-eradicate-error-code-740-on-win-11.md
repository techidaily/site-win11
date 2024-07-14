---
title: A Step-by-Step Solution to Eradicate Error Code 740 on Win 11
date: 2024-07-13T11:11:14.294Z
updated: 2024-07-14T11:11:14.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Solution to Eradicate Error Code 740 on Win 11
excerpt: This Article Describes A Step-by-Step Solution to Eradicate Error Code 740 on Win 11
keywords: Win 11 Error Code 740 Fix,Error 740 Removal in Windows 11,Solve Win 11 Error 740,Unblocking Error 741 on PC,Troubleshoot Error 740, Win 11,Correcting Error Code,Eradicate 740 Error in Win 11 Update
thumbnail: https://thmb.techidaily.com/1b366750108562524d82d4ae59a489c50fa84a81f8bcbe092ec793162bb9610d.jpg
---

## A Step-by-Step Solution to Eradicate Error Code 740 on Win 11

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
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/tech-temporary-trouble-6-hours-of-no-internet/"><u>Tech Temporary Trouble: 6 Hours of No Internet</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-unlocking-a-new-sound-profile-free-guide-to-free-fire-voice-changes/"><u>[New] 2024 Approved  Unlocking a New Sound Profile  Free Guide to Free Fire Voice Changes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-creating-humor-making-funny-parody-videos/"><u>[New] 2024 Approved  Creating Humor  Making Funny Parody Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-mac-capture-techniques-overview-char-limit-156-for-2024/"><u>Top Mac Capture Techniques Overview (Char Limit  156) for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-vsco-image-enhancement/"><u>[Updated] Step-by-Step VSCO Image Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restricted-administrator-error-in-winsec/"><u>Overcoming Restricted Administrator Error in WinSec</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-cropping-like-a-pro-advanced-techniques-for-avidemux-users/"><u>Updated Cropping Like a Pro Advanced Techniques for Avidemux Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-12-mini-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 12 mini</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-your-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>How to identify missing your drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-drive-labels-the-candd-dynamics/"><u>Interpreting Drive Labels: The C&D Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-0x800704b3-on-windows-pcs/"><u>Addressing Error Code 0X800704B3 on Windows PCs</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-vivo-y78t-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-lan-play-fixes-for-no-connection-woes/"><u>Winning at LAN Play: Fixes for No Connection Woes</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/chronicle-custodians-circle-top-7-treasures-for-2024/"><u>Chronicle Custodians Circle - Top 7 Treasures for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>How to use Pokemon Go Joystick on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-worlds-best-short-videos-download-now-free/"><u>[Updated] World's Best Short Videos – Download Now! (Free)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-honor-magic-5-lite-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Honor Magic 5 Lite FRP Bypass</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-exciting-entertainment-top-10-ios-games-ready-for-no-wireless-connection/"><u>[Updated] In 2024, Exciting Entertainment - Top 10 iOS Games, Ready for No Wireless Connection</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-itel-s23-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Itel S23 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-a-comprehensive-manual-for-desktop-made-tiktok-hits/"><u>[New] In 2024, A Comprehensive Manual for Desktop-Made TikTok Hits</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-essential-pc-editing-skills-for-compelling-youtube-videos/"><u>In 2024, Essential PC Editing Skills for Compelling YouTube Videos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-leading-edge-in-natural-language-processing-voice-synthesis-technologies/"><u>In 2024, The Leading Edge in Natural Language Processing Voice Synthesis Technologies</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-installation-windows-cab-files-unpacked-and-utilized/"><u>Initiating Installation: Windows CAB Files Unpacked and Utilized</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-code-4-spotify-error-on-w10w11-systems/"><u>Overcoming the Code 4 Spotify Error on W10/W11 Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/getting-to-grips-with-apple-podcasts-installation-for-2024/"><u>Getting to Grips with Apple Podcasts Installation for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-amplify-youtube-visibility-crafting-effective-descriptions-and-tags-for-2024/"><u>[Updated] Amplify YouTube Visibility  Crafting Effective Descriptions & Tags for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-mastering-access-the-journey-through-free-visual-resources-for-2024/"><u>[New] Mastering Access  The Journey Through Free Visual Resources for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-guide-to-browser-paste-issues-on-windows/"><u>Corrective Guide to Browser Paste Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-threshold-post-failed-access-on-w10w11/"><u>Tweaking the Lockout Threshold Post-Failed Access on W10/W11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-realme-narzo-60-pro-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Realme Narzo 60 Pro 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-best-video-edits-and-scripting-tools-in-windows-11/"><u>The Ultimate List: Best Video Edits & Scripting Tools in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-earning-big-from-youtube-shorts-key-requirements-and-profit-prospects/"><u>2024 Approved  Earning Big From YouTube Shorts  Key Requirements and Profit Prospects</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-headphone-connection-errors-in-windows-1011/"><u>Resolving Headphone Connection Errors in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/critical-hardware-scan-tools/"><u>Critical Hardware Scan Tools</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-zipping-up-an-enthralling-tiktok-credit-sequence/"><u>[New] 2024 Approved  Zipping Up an Enthralling TikTok Credit Sequence</u></a></li>
<li><a href="https://win11.techidaily.com/instant-repair-tactics-for-windows-photo-app-malfunctions/"><u>Instant Repair Tactics for Windows Photo App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-dev-drive-setup-in-windows-11-development-space/"><u>Demystifying Dev Drive Setup in Windows 11 Development Space</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-descriptive-folders-in-windows-11/"><u>Boosting Productivity with Descriptive Folders in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-huawei-p60-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Huawei P60 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-a1x-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo A1x 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/accelerate-vimeo-videos-the-guide/"><u>Accelerate Vimeo Videos  The Guide</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-error-code-0xc0000001-on-windows/"><u>Decoding and Fixing Error Code 0XC0000001 on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-meme-masterpiece-wave/"><u>[Updated] In 2024, Meme Masterpiece Wave</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-ad-ds-strategies-for-printer-troubleshooting/"><u>Win11 & AD DS: Strategies for Printer Troubleshooting</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-lava-blaze-2-pro-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Lava Blaze 2 Pro Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-audio-excellence-with-5-free-windows-apps/"><u>Elevate Audio Excellence with 5 Free Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-way-you-use-windows-11s-search-feature/"><u>Transforming the Way You Use Windows 11'S Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-advanced-taskbar-attachments/"><u>Windows 11: Advanced Taskbar Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-alt-codes-in-windows/"><u>Troubleshooting Non-Responsive ALT Codes in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-audiovisual-synchronization-in-facebook-content-creation/"><u>[New] 2024 Approved  Audiovisual Synchronization in Facebook Content Creation</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-group-policy-settings-an-exploration-in-3-dimensions/"><u>Unraveling Windows Group Policy Settings: An Exploration in 3 Dimensions</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-disregard-must-have-components-issue-in-win10win11/"><u>Quick Guide to Disregard Must-Have Components Issue in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-credential-entry-attempts/"><u>Analyzing Windows Credential Entry Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pixel-power-streaming-strategies-in-the-software-vs-hardware-arena-for-2024/"><u>Pixel Power  Streaming Strategies in the Software vs Hardware Arena for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-x0001-with-nvidia-experience-w11/"><u>Remedying Error X0001 with Nvidia Experience, W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-photo-slideshows-and-spot-corrections-on-win11s-gallery/"><u>Mastering Photo Slideshows & Spot Corrections on Win11's Gallery</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-how-to-create-snapchat-lenses-easily-2-methods/"><u>[New] In 2024, How to Create Snapchat Lenses Easily  2 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/digital-fortifications-essential-tactics-for-access-control/"><u>Digital Fortifications: Essential Tactics for Access Control</u></a></li>
</ul></div>
