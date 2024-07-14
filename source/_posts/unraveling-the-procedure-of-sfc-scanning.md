---
title: Unraveling the Procedure of SFC Scanning
date: 2024-07-13T10:37:57.930Z
updated: 2024-07-14T10:37:57.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Procedure of SFC Scanning
excerpt: This Article Describes Unraveling the Procedure of SFC Scanning
keywords: SFC Analysis Steps,FPC Scan Process,SFC Scanner Guide,SFC Testing Technique,Uncover SFC Protocol,SFC Examination Flow,Discovering SFC Methods
thumbnail: https://thmb.techidaily.com/53ddbe6924d2ddfb268e4678d76937abc181d4038a95a53ae70246e54e37c443.jpg
---

## Unraveling the Procedure of SFC Scanning

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.
4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on [what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our [beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by [creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.


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
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-enhancement-in-wt-with-personalized-schemes/"><u>Aesthetic Enhancement in WT with Personalized Schemes</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-control-set-active-hours-to-avoid-surprises-on-windows-11/"><u>Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-syncing-your-phone-with-windows-11-via-unison/"><u>Expert Tips: Syncing Your Phone with Windows 11 via Unison</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-user-sign-in-after-windows-authentication-issues/"><u>Enabling User Sign-In After Windows Authentication Issues</u></a></li>
<li><a href="https://win11.techidaily.com/flush-your-steam-dns-data-a-windows-user-guide/"><u>Flush Your Steam DNS Data - A Windows User Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-1011s-audacity-audio-connection-failures/"><u>Fixing Windows 10/11’S Audacity Audio Connection Failures</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-boosting-gaming-engagement-with-high-quality-steam-captures/"><u>[New] Boosting Gaming Engagement with High Quality Steam Captures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-all-encompassing-kinetic-review-2023/"><u>[New] 2024 Approved  All-Encompassing Kinetic Review 2023</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-firewall-options-for-blocking-software-to-windows-11s-context-menu/"><u>How to Add Firewall Options for Blocking Software to Windows 11’S Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-nullifying-windows-11s-eyes-on-you/"><u>Mastery in Nullifying Windows 11'S Eyes on You</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-oneplus-open-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your OnePlus Open Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-lava-yuva-2-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Lava Yuva 2 Pro Devices</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-easy-steps-to-securely-record-your-virtual-gatherings-with-google/"><u>2024 Approved  Easy Steps to Securely Record Your Virtual Gatherings with Google</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-apple-iphone-15-pro-by-drfone-ios/"><u>How Do You Remove Restricted Mode on Apple iPhone 15 Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-iphone-11-pro-when-phone-is-broken-by-drfone-ios/"><u>In 2024, How to Turn Off Find My iPhone 11 Pro when Phone is Broken?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/proven-strategies-for-selecting-elite-sound-engineers-in-modern-filmmaking-for-2024/"><u>Proven Strategies for Selecting Elite Sound Engineers in Modern Filmmaking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/easy-paths-back-to-success-in-steam-gaming/"><u>Easy Paths Back to Success in Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-restoring-erased-data-in-a-microsoft-world/"><u>Expertly Restoring Erased Data in a Microsoft World</u></a></li>
<li><a href="https://win11.techidaily.com/deactivating-mouse-speed-sensitivity-in-windows-1011/"><u>Deactivating Mouse Speed Sensitivity in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-this-article-we-talk-about-how-to-add-old-film-overlays-and-other-effects-to-turn-the-videos-or-photos-more-vintage-and-with-an-older-aspect-we-take-a-lo/"><u>In This Article, We Talk About How to Add Old Film Overlays and Other Effects to Turn the Videos or Photos More Vintage and with an Older Aspect. We Take a Look at Filmora in This Guide and Give Tips on How to Create Great Retro Videos</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-beyond-youtube-elite-video-sharing-hubs-revealed/"><u>[New] Beyond YouTube  Elite Video Sharing Hubs Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-code-0xa00f425d-in-windows-1e11-camera/"><u>Correcting Error Code: 0XA00F425D in Windows 1E11 Camera</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-make-a-splash-with-instagram-reels-using-tried-and-true-tiktok-hacks/"><u>In 2024, Make a Splash with Instagram Reels Using Tried-and-True TikTok Hacks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-earnings-breakdown-youtubes-adsense-payments-by-thousands-of-views/"><u>2024 Approved  Earnings Breakdown  Youtube's AdSense Payments by Thousands of Views</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-blue-windows-fails/"><u>Mastering the Art of Fixing Blue Windows Fails</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-methods-for-reducing-jello-like-video-stabilization-effects/"><u>[Updated] Methods for Reducing Jello-Like Video Stabilization Effects</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-critical-winerror-upgrade-fault-0xc004f050/"><u>Fixing Critical WinError: Upgrade Fault #0XC004F050</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-study-diversity-in-fb-video-shapes/"><u>[Updated] 2024 Approved  Study  Diversity in FB Video Shapes</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhancing-chats-adding-tunes-via-whatsapp-status/"><u>Enhancing Chats  Adding Tunes via WhatsApp Status</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-alternative-cinema-highlights-audiences/"><u>[New] 2024 Approved  Alternative Cinema Highlights Audiences</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/converting-from-pin-to-password-a-windows-11-users-guide-for-enhanced-security/"><u>Converting From PIN to Password: A Windows 11 User's Guide for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-root-user-access-in-the-windows-terminal/"><u>Ensuring Root User Access in the Windows Terminal</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-12-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 12</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-invalid-label-error-on-windows-11/"><u>Guide to Rectify 'Invalid Label' Error on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-zoom-voice-modifiers-6-expert-tips-to-make-every-meeting-unforgettable-and-entertaining/"><u>Updated In 2024, Zoom Voice Modifiers 6 Expert Tips to Make Every Meeting Unforgettable and Entertaining</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-photoshopping-in-windows-11-without-hurdles/"><u>Enabling Photoshopping in Windows 11 Without Hurdles</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/sticky-situations-solved-tiktok-video-cleanup/"><u>Sticky Situations Solved  TikTok Video Cleanup</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-windows-system-preferences-to-adjust-after-dark-mode/"><u>Mastery of Windows System Preferences to Adjust After Dark Mode</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-premier-12-single-user-screen-replay-apps/"><u>[Updated] In 2024, Premier 12 Single-User Screen Replay Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-open-avoid-lockout-feature/"><u>How To Keep Windows Open: Avoid Lockout Feature</u></a></li>
<li><a href="https://win11.techidaily.com/securing-off-screen-windows-6-methods-for-win11-users/"><u>Securing Off-Screen Windows: 6 Methods for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-on-space-spotlight-on-large-files-in-windows/"><u>Cutting Down on Space: Spotlight on Large Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-lost-connection-top-9-remedies-for-missing-bluetooth-on-win-11/"><u>Revive the Lost Connection: Top 9 Remedies for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-quintessential-toptiktok-tweets-in-popularity-for-2024/"><u>The Quintessential #TopTikTok Tweets in Popularity for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-s17-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo S17 Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-inbox-and-calendar-use-custom-images/"><u>Overhaul Your Inbox and Calendar: Use Custom Images</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wacatacbml-understanding-and-neutralizing-threats-on-windows/"><u>Breaking Down Wacatac.B!ml: Understanding and Neutralizing Threats on Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-essential-steps-for-starting-a-channel-on-discord/"><u>[New] Essential Steps for Starting a Channel on Discord</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-recommended-video-background-online-changers-for-2024/"><u>New Recommended Video Background Online Changers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719193162154-unlocking-the-secrets-to-fixing-non-working-win-plus-printer/"><u>Unlocking The Secrets to Fixing Non-Working Win + Printer.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/step-by-step-video-enhancement-tutorial-for-gopro-studio-users/"><u>Step-by-Step Video Enhancement Tutorial for GoPro Studio Users</u></a></li>
<li><a href="https://win11.techidaily.com/wrapping-windows-games-in-christmas-carols/"><u>Wrapping Windows Games in Christmas Carols</u></a></li>
</ul></div>
