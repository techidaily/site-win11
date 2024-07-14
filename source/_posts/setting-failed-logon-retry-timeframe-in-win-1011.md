---
title: Setting Failed Logon Retry Timeframe in Win 10/11
date: 2024-07-13T09:43:35.854Z
updated: 2024-07-14T09:43:35.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
excerpt: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
keywords: Win 10 Login Recovery,Windows 10 Reset Attempts,Manage Logon Retries,Reconfigure Login Delays (Win10/11),Windows Timeout for Failed Logins,Setting Login Retry Interval (Win10),Adjusting Login Retries (Windows 10)
thumbnail: https://thmb.techidaily.com/128652f3635b5c02571aebd32ea42bdf5de3d8228fe08a4a4993ce8bcc5b8b84.png
---

## Setting Failed Logon Retry Timeframe in Win 10/11

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
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-stop-and-start-strategies-fb-livestream-recovery-methods/"><u>2024 Approved  Stop and Start Strategies  FB Livestream Recovery Methods</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-making-ai-images-with-paint-tool-sai/"><u>Transform Windows 11: Making AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-brief-but-bold-short-videos-on-fb/"><u>2024 Approved  Brief but Bold  Short Videos on FB</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>Life360 Circle Everything You Need to Know On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fixing-mistaken-face-id-in-facebook-chats-for-2024/"><u>[New] Fixing Mistaken Face ID in Facebook Chats for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-best-filmic-pro-luts-for-video-editing/"><u>Updated Best Filmic Pro LUTs For Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-managing-directories-without-renaming-feature-in-win-11/"><u>The Ultimate Guide to Managing Directories Without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-textual-form-from-vocal-input-in-windows-via-whisper/"><u>Unlock Textual Form From Vocal Input in Windows via Whisper</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-the-ultimate-guide-for-enthusiasts-on-screenshotting-with-zd-software/"><u>2024 Approved  The Ultimate Guide for Enthusiasts on Screenshotting with ZD Software</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-microsoft-store-crash-error-0x800704cf-in-windows/"><u>Quick Fix for Microsoft Store Crash: Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-past-security-checks-on-your-wins-system/"><u>How to Clear Past Security Checks on Your Wins System</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-creativity-personalizing-windows-1011-screens/"><u>Unleash Creativity: Personalizing Windows 10/11 Screens</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-effective-ways-to-archive-webcam-discussions-for-2024/"><u>[New] Effective Ways to Archive Webcam Discussions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-home-view-in-windows-11-settings/"><u>Unlock Home View in Windows 11 Settings</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-guide-to-separating-audio-tracks-in-adobe-premiere-pro/"><u>Updated The Ultimate Guide to Separating Audio Tracks in Adobe Premiere Pro</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-on-iphone-12-pro-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock on iPhone 12 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/ace-file-moves-with-advanced-auto-transfer-techniques-on-win-11/"><u>Ace File Moves with Advanced Auto-Transfer Techniques on Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-accessing-zoom-directly-from-google-mail-interface/"><u>2024 Approved  Accessing Zoom Directly From Google Mail Interface</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-enhancing-videos-with-camtasias-ken-burns-trick/"><u>[New] Enhancing Videos with Camtasia's Ken Burns Trick</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-decoding-youtubes-intricate-view-count-mechanics/"><u>[New] In 2024, Decoding YouTube's Intricate View Count Mechanics</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-approach-installing-and-using-outlook-preview-for-windows-11-users/"><u>Tailored Approach: Installing and Using Outlook Preview for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-struggles-lack-of-drive-letters-explained-and-cured/"><u>Windows Struggles: Lack of Drive Letters Explained & Cured</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-expert-recorder-choice-for-high-quality-youtube-content/"><u>[New] 2024 Approved  Expert Recorder Choice for High-Quality YouTube Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-electorate-engagement-experience-top-gaming-selections/"><u>2024 Approved  Electorate Engagement Experience  Top Gaming Selections</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tweet-transformation-techniques-for-free-gifs/"><u>[Updated] 2024 Approved  Tweet Transformation Techniques for Free GIFs</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-infographic-premier-fifa-videos-popularity-spotlight/"><u>[New] 2024 Approved  Infographic  Premier FIFA Videos Popularity Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-access-denied-on-nvidia-panel/"><u>Quick-Fix Tips for Access Denied on NVIDIA Panel</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-navigating-daily-life-on-facebook-a-step-by-step-guide/"><u>In 2024, Navigating Daily Life on Facebook  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-re-enable-your-windows-11-device-after-error-22/"><u>Expert Tips to Re-Enable Your Windows 11 Device After Error 22</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-updated-review-sonys-blu-ray-and-hd-masterpiece/"><u>2024 Approved  The Updated Review  Sony's Blu-Ray and HD Masterpiece</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-speech-recognition-launch-failures-in-windows-os/"><u>Overcoming Speech Recognition Launch Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-failed-zip-file-extractions-on-windows-11/"><u>How To Reverse Failed Zip File Extractions on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-endless-scrolls-on-large-datasheets-windows/"><u>Overcome Endless Scrolls on Large Datasheets, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/effective-communication-in-live-discovers-with-our-guide-for-2024/"><u>Effective Communication in Live Discovers with Our Guide for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mememolding-cutter-for-2024/"><u>MemeMolding Cutter for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719358014112-chrome-woes-on-windows-11-a-fixers-guide-to-reopening-it/"><u>Chrome Woes on Windows 11: A Fixer’s Guide to Reopening It.</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/flashback-fun-enjoying-oldschool-games-with-dosbox-x/"><u>Flashback Fun: Enjoying Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/conversing-with-confidence-mastering-japanese-salutations/"><u>Conversing with Confidence: Mastering Japanese Salutations</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-microsoft-store-error-x00000000-in-win-11/"><u>Addressing the Microsoft Store Error X00000000 in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/why-excel-fails-to-open-in-windows-notepad/"><u>Why Excel Fails to Open in Windows Notepad?</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-off-chrome-notifications-windows-version/"><u>Steps to Turn Off Chrome Notifications, Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/chronology-clash-wintime-harmony-guide/"><u>Chronology Clash? WinTime Harmony Guide</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-lock-screen-timeout-stops-working-on-windows/"><u>What to Do if the Lock Screen Timeout Stops Working on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-download-and-convert-youtube-twittersongs-videos-to-mp3/"><u>How to Download and Convert YouTube Twittersongs (Videos) to MP3</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-apple-iphone-se-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an Apple iPhone SE Without Apple ID Password?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-professionals-playbook-streaming-live-videos-on-tiktok-from-computer-for-2024/"><u>[New] The Professional’s Playbook  Streaming Live Videos on TikTok From Computer for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-screenplay-scribblers-hub/"><u>In 2024, Top Screenplay Scribblers Hub</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/blueprint-for-conquering-facebook-video-advertising-success/"><u>Blueprint for Conquering Facebook Video Advertising Success</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-xiaomi-redmi-note-13-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Xiaomi Redmi Note 13 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-bridging-platforms-uploading-from-twitch-to-youtube/"><u>In 2024, Bridging Platforms  Uploading From Twitch to YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-mastering-the-digital-persona-shift-ultimate-guide-to-changing-your-tiktok-handle/"><u>[Updated] 2024 Approved  Mastering the Digital Persona Shift  Ultimate Guide to Changing Your TikTok Handle</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10plus-users-unlocking-the-secrets-of-your-ram-type/"><u>Windows 10+ Users: Unlocking the Secrets of Your RAM Type</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-vivo-y100-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Vivo Y100</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
</ul></div>
