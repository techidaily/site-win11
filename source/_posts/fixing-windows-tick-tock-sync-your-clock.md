---
title: "Fixing Windows' Tick-Tock: Sync Your Clock"
date: 2024-07-13T10:19:21.574Z
updated: 2024-07-14T10:19:21.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Windows' Tick-Tock: Sync Your Clock"
excerpt: "This Article Describes Fixing Windows' Tick-Tock: Sync Your Clock"
keywords: Sync Windows Time,Set WinTime,Fix Windows Clock,Adjust WinClock,Align Windows Date,Reset WinTimer,TickWinSync
thumbnail: https://thmb.techidaily.com/29b1b2904297da87da55ea288cd0a44b14a4d2e985940c7f874a6ef2e9aec11a.jpg
---

## Fixing Windows' Tick-Tock: Sync Your Clock

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/tips-to-secure-windows-sound-level-adjustments/"><u>Tips to Secure Windows Sound Level Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-downloads-not-working-on-win-devices/"><u>How to Resolve Downloads Not Working on Win Devices</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-fn-keys-functionality-on-windows-1011/"><u>Optimizing FN Keys' Functionality on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-3d-paint-efficiency-with-these-tricks/"><u>Boost Your 3D Paint Efficiency With These Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-missing-system-cooling-policy-on-windows/"><u>How to Fix a Missing System Cooling Policy on Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-transform-your-discord-chat-emojis-at-the-forefront-of-statuses/"><u>[New] Transform Your Discord Chat  Emojis at the Forefront of Statuses</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-a15-4g-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy A15 4G Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-safety-turning-on-folder-controls-in-windows/"><u>Mastering File Safety: Turning On Folder Controls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-solutions-for-resolving-windows-11-naming-issues-in-directories/"><u>7 Solutions for Resolving Windows 11 Naming Issues in Directories</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-vivo-y02t-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Vivo Y02T Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-your-guide-to-favorite-tiktok-backgrounds/"><u>In 2024, Your Guide to Favorite TikTok Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-to-do-app-when-its-not-syncing/"><u>How to Fix the Microsoft To Do App When It’s Not Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-windows-11-vm-reset/"><u>Guidelines for Windows 11 VM Reset</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disconnects-resolving-fall-guys-errors-on-windows/"><u>Overcoming Disconnects: Resolving Fall Guys Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-of-0xc000003e-error-on-pcs/"><u>Mastering the Fix of 0xC000003E Error on PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-compressed-to-captioned-zip-to-srt-effortlessly/"><u>[Updated] From Compressed To Captioned  Zip to .Srt Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/revive-volume-control-preferences-in-your-windows-pc/"><u>Revive Volume Control Preferences in Your Windows PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-10-best-asmr-recorders-for-exceptional-audio-quality/"><u>[New] In 2024, 10 Best ASMR Recorders for Exceptional Audio Quality</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-organizing-the-art-of-customizing-windows-outlook-calendars/"><u>Winning at Organizing: The Art of Customizing Window's Outlook Calendars</u></a></li>
<li><a href="https://win11.techidaily.com/access-advanced-control-panel-to-change-screen-after-dark-mode/"><u>Access Advanced Control Panel to Change Screen After Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-note-apps-for-the-modern-windows-slates/"><u>Perfect Note Apps for the Modern Windows Slates</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-not-responsive-spotify-error-in-windows-oses/"><u>Resolving Not Responsive Spotify Error in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mail-apps-0x800713f-error-in-windows-11-and-11/"><u>How to Fix the Mail App’s 0X800713f Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/unbeatable-black-friday-save-612-on-windows-10/"><u>Unbeatable Black Friday: Save $6.12 on Windows 10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/inside-window-11s-power-saving-secrets/"><u>Inside Window 11'S Power-Saving Secrets</u></a></li>
<li><a href="https://apple-account.techidaily.com/detailed-guide-on-removing-apple-iphone-se-2020-activation-lock-without-previous-owner-by-drfone-ios/"><u>Detailed Guide on Removing Apple iPhone SE (2020) Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-plugged-inspection-failure-for-pc-sound-devices/"><u>Addressing Plugged Inspection Failure for PC Sound Devices</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-hidden-cameras-fix-their-absence-in-dm/"><u>Uncover Hidden Cameras: Fix Their Absence in DM</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-hide-search-icon-from-taskbar-in-win-11/"><u>Easy Steps: Hide Search Icon From Taskbar in Win 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-get-free-youtube-music-anytime-with-these-high-performing-splitters/"><u>[Updated] 2024 Approved  Get Free YouTube Music Anytime With These High-Performing Splitters</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-silent-snaptaking-the-art-of-concealed-picture-recording/"><u>[New] Silent SnapTaking  The Art of Concealed Picture Recording</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-a-faulty-esc-key-in-windows-10-and-beyond/"><u>Troubleshoot a Faulty Esc Key in Windows 10 and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-missing-windows-phone-link-notifications/"><u>Steps to Reactivate Missing Windows Phone Link Notifications</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-building-an-mc-village-housing-essentials/"><u>[Updated] 2024 Approved  Building an MC Village  Housing Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabling-directives-essential-4-fixes-to-windows-ps-load-issue/"><u>Bypassing Disabling Directives: Essential 4 Fixes to Windows PS Load Issue</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-on-iphone-7-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes On iPhone 7?</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-11-task-managers-perfect-for-organizing-daily-chores/"><u>Top 6 Windows 11 Task Managers Perfect for Organizing Daily Chores</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-innovative-snapchat-strategies-the-ultimate-list/"><u>[New] Innovative Snapchat Strategies  The Ultimate List</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-xiaomi-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Xiaomi Device</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-motorola-razr-40-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Motorola Razr 40 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/enhancing-interactivity-tips-for-hosting-splitting-screen-events-on-facebook/"><u>Enhancing Interactivity  Tips for Hosting Splitting-Screen Events on Facebook</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-cut-to-impress-top-tier-online-photo-editing-skills/"><u>2024 Approved  Cut to Impress  Top-Tier Online Photo Editing Skills</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/detailed-guide-securely-recording-on-vimeo/"><u>Detailed Guide  Securely Recording on Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-to-enable-touch-typing-on-windows-laptops/"><u>Tricks to Enable Touch Typing on Windows Laptops</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-marketing-game-free-50-youtube-adornments-here/"><u>Elevate Your Marketing Game - Free 50 YouTube Adornments Here</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-icebound-duelists-celebrating-the-best-of-winter-olympics-snowboard-x-for-2024/"><u>[Updated] Icebound Duelists  Celebrating the Best of Winter Olympics Snowboard X for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/thwarting-windows-users-from-altering-system-time/"><u>Thwarting Windows Users From Altering System Time</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-securely-without-screensaver/"><u>Unlock Windows 11 Securely Without Screensaver</u></a></li>
<li><a href="https://extra-tips.techidaily.com/15-top-free-slow-motion-video-recording-apps-for-iphoneandroid-for-2024/"><u>15 Top Free Slow Motion Video Recording Apps for iPhone/Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-a-non-responsive-windows-notepad-application/"><u>How to Revive a Non-Responsive Windows Notepad Application</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transforming-business-with-metaverse-ideas/"><u>2024 Approved  Transforming Business with Metaverse Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-installed-windows-11-on-mac-through-parallels/"><u>Breaking the Barrier: Installed Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-complete-stop-motion-toolkit-studio-and-beyond/"><u>The Complete Stop Motion Toolkit Studio and Beyond</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-gripping-phrase-generator-device/"><u>[Updated] In 2024, Gripping Phrase Generator Device</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-quality-freely-accessible-music-websites-listed-here/"><u>[New] 2024 Approved  High-Quality, Freely Accessible Music Websites Listed Here</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-switch-apps-using-snap-feature-in-windows-11/"><u>Swiftly Switch Apps Using Snap Feature in Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-video-color-correction-for-youtube-beauty/"><u>In 2024, Video Color Correction for YouTube Beauty</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-fine-tuning-your-amd-settings-in-windows-gaming/"><u>Winning Strategy: Fine-Tuning Your AMD Settings in Windows Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-vs-powershell-pinpointing-the-distinguishing-aspects/"><u>Terminal Vs. PowerShell: Pinpointing the Distinguishing Aspects</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-windows-11-installation-essential-settings-guide/"><u>Personalize Your Windows 11 Installation: Essential Settings Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigating-through-hands-free-technological-advances-for-2024/"><u>Navigating Through Hands-Free Technological Advances for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/handling-unable-to-open-file-for-writing-error-in-win-11/"><u>Handling Unable to Open File for Writing Error in Win 11</u></a></li>
</ul></div>
