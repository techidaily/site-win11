---
title: Method to Release Administrator-Restricted Apps
date: 2024-07-13T11:06:48.504Z
updated: 2024-07-14T11:06:48.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method to Release Administrator-Restricted Apps
excerpt: This Article Describes Method to Release Administrator-Restricted Apps
keywords: Admin App Release Guide,Unrestricting App Access,App Permissions Removal,Disable Restrictions (App),Freeing Restricted Apps,Revoking App Limits,Easing Admin-Limited Apps
thumbnail: https://thmb.techidaily.com/b97d0ebad54511b61b45570cc2aa70ceb4b57e4382ef455cbbee6f6a39f5f377.jpg
---

## Method to Release Administrator-Restricted Apps

 User Account Control on Windows prevents unauthorized changes to your computer. This, however, can cause issues with genuine apps and block them from running.

 This app has been blocked by your system administrator error is triggered if your account doesn't have admin rights. Other reasons include issues with User Account Control and Microsoft Defender SmartScreen blocking the app.

 To fix the problem, perform a quick restart of your computer. If the issue persists after the restart, follow these steps to fix the This app has been blocked by your system administrator error on Windows.

## 1\. Unblock the App Executable

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 Windows can automatically block apps downloaded from the internet from running your computer. This is a safety measure intended to protect your system against apps from unknown publishers.

 If you trust the publisher, you can manually unblock the file and run it without the error.

To unblock an app on Windows:

1. Locate and right-click on the app's executable and select**Properties** .
2. In the**Properties** dialog, open the**General** tab.
3. In the**Secure** section, check the**Unblock** option.
4. Click**Apply** and**OK** to save the changes.
5. Launch the app again to see if the error is resolved.

## 2\. Run the App Using the Command Prompt

 You can run and launch apps using Command Prompt on Windows. All you need is a file path followed by the file name. Command Prompt offers a faster way to open apps on Windows; however, you can also use it if you can't open an app from File Explorer.

To open Windows apps using Command Prompt:

1. Right-click on the app shortcut and select**Open File Location** .
2. Next, right-click on the**app.exe** file and select**Properties** .  
![Windows file properties file path location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-file-properties-file-path-location.jpg)
3. In the Properties dialog, open the**Genera** l tab.
4. Copy the file path shown as**Location** .
5. On Windows 11, right-click on the .exe file and select**Copy as File Path** .  
![run program using command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-program-using-command-prompt.jpg)
6. Next, press the**Win** key and type**cmd** .
7. Right-click on**Command Prompt** , and select**Run as administrator.**
8. Next, press**Ctrl + V** to paste the copied file path in Command Prompt. Make sure to add the .exe file name at the end of the file path.
9. Press**Enter** to launch the app.

## 3\. Run the Apps as an Administrator

![run minecraft as administrator windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-minecraft-as-administrator-windows-11.jpg)

 Some Windows apps may need administrator privileges to work correctly. To fix the error, run the app as an administrator. If it works, you can configure the app properties to always run as administrator.

To run an app as an administrator:

1. Right-click on the app icon and select**Run as administrator** .
2. Click**Yes** if prompted by User Account Control.

 Check if the app launches ad administrator without the error. If yes, you can [set the app to always run as administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to fix the issue. That said, do this only if you trust the publisher for security reasons.

## 4\. Repair or Reset the Microsoft Store Apps

 If the error is triggered when opening a Microsoft Store app, try to perform a repair. You can repair Microsoft Store apps from the Settings panel. This should fix temporary glitches with the app and resolve the error.

To repair a Microsoft Store app:

![repair photos app windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/repair-photos-app-windows-11.png)

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Search and locate the app you want to repair.
4. Click the**three-dots menu** next to the app name and select**Advanced Options** .
5. Scroll down and click on the**Repair** button. Wait as Windows repairs the app; you will see a green check mark indicating the repair is complete.

 Once done, launch the app and check if the error is resolved. If you see the error again, try to reset the app.

Reset the Microsoft Store app:

![reset-microsoft-teams-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-microsoft-teams-windows-11.jpg)

 Resetting an app will delete its data, including sign-in details and preferences.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Click the**three-dots menu** near the app name and select**Advanced options** .
4. Scroll down and click the**Reset** button. Click**Reset** again to confirm the action. Similar to Repair, you'll see a checkmark when the reset process is complete.

## 5\. Disable Microsoft Defender SmartScreen

 Microsoft Defender's SmartScreen scans programs and files during the launch for potential threats and can block them from running. You can disable the SmartScreen feature temporarily to determine if your app is blocked by it.

 You can [disable Microsoft SmartScreen Filter on Windows](https://www.makeuseof.com/windows-smartscreen-filter-enable-disable/) using the Windows Security app. Once disabled, relaunch the app and check if the error is resolved.

## 6\. Turn Off Your Antivirus Program

 False positives from Antivirus programs are not uncommon. Whether you are using Microsoft Windows Defender or another antivirus program, turn off the security program temporarily to determine if your antivirus blocking the app.

 You can [temporarily disable Microsoft Defender](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) using the Windows Security app. To turn off third-party antivirus, right-click the app icon in the system tray and select the appropriate options.

 If the error is resolved, add the app to your security program's allowed list. You can also [allowlist files and apps on Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) if you use it as the primary security application.

## 7\. Modify the Windows Registry to Remove Admin Block

 User Account Control settings are another common trigger for the This app has been blocked by your system administrator error. You can modify the User Account Control settings in Registry Editor to remove the admin block and resolve the error.

 Making incorrect modifications to the Windows Registry can cause your system to malfunction. Make sure to [create a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , and a [system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below.

To remove the admin block using Registry Editor:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** , if prompted by User Account Control.
3. In Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies`
4. Select the**System** subkey under**Policies** .
5. In the right pane, locate**EnableLUA** .  
![enable lua modify registry editor windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-windows.jpg)
6. Right-click on the**EnableLUA** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![enable lua modify registry editor value 0 windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-value-0-windows.jpg)
8. Close Registry Editor and restart your computer to apply the changes. After the restart, launch the app to see if the error is resolved.
9. If you are using a school or work computer, your organization may put some restrictions on its use. If you can't find the UAC settings, contact your IT administrator to resolve the issue.

## Unblock the Apps Blocked by Your System Administrator

 Security settings on your Windows computer can often block suspicious apps and trigger the This app has been blocked by your system administrator message. To resolve the issue, check and unblock the app in file properties. Also, turn off the SmartScreen filter and your antivirus solution.

 Reconfiguring your UAC settings in Registry Editor is another way to resolve the problem. If all else fails, the restrictions may have been put in place by guardians or the school or work administration.


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
<li><a href="https://snapchat-videos.techidaily.com/rapid-retrieval-for-missed-snaps-for-2024/"><u>Rapid Retrieval for Missed Snaps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-app-install-failures-on-microsoft-store/"><u>Correcting App Install Failures on Microsoft Store</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-behind-stock-image-memes-stories-that-stood-the-test/"><u>2024 Approved  Behind Stock Image Memes  Stories That Stood the Test</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-expert-tips-for-seamless-iphone-screen-recordings/"><u>2024 Approved  Expert Tips for Seamless iPhone Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-11-installation-with-these-essential-tweaks/"><u>Streamline Your Windows 11 Installation with These Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/visual-clarity-in-note-taking-with-obsidian-design/"><u>Visual Clarity in Note-Taking with Obsidian Design</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-analysis-of-windows-11-settings/"><u>In-Depth Analysis of Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-why-windows-fails-to-execute-exe-files/"><u>Decoding Why Windows Fails to Execute .exe Files</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-filing-mastery-key-principles-max-156/"><u>Windows Filing Mastery: Key Principles (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/from-ios-to-desktop-seamless-sync-with-windows-os/"><u>From iOS to Desktop: Seamless Sync with Windows OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-conquering-snapchat-send-gifs-with-ease/"><u>[Updated] In 2024, Conquering Snapchat  Send Gifs with Ease</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-honor-x50i-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Honor X50i Phone</u></a></li>
<li><a href="https://win11.techidaily.com/cease-auditory-gain-on-windows-operating-system/"><u>Cease Auditory Gain on Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-beast-boosting-fps-in-cs-go/"><u>Unleash the Beast - Boosting FPS in CS Go</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-redesigned-windows-11-widget-pickers/"><u>Enabling Redesigned Windows 11 Widget Pickers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unraveling-free-filter-treasures-through-instagrams-advanced-searches-for-2024/"><u>[Updated] Unraveling Free Filter Treasures Through Instagram’s Advanced Searches for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-infinix-note-30-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Infinix Note 30? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-hidden-login-screens-in-windows-11/"><u>Eradicating Hidden Login Screens in Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-internet-companion-fb-story-backup-tool/"><u>[Updated] In 2024, Internet Companion  FB Story Backup Tool</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pinnacle-plots-and-dialogues-for-radios/"><u>Pinnacle Plots & Dialogues for Radios</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-zero-empty-directories-issue-in-windows-11-and-11/"><u>Tackling the Zero-Empty Directories Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pathways-to-windows-performance-details/"><u>Efficient Pathways to Windows Performance Details</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-fix-rpc-fails-on-your-pc/"><u>Master Plan to Fix RPC Fails on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-role-and-usage-of-windows-component-services/"><u>Deciphering the Role & Usage of Windows Component Services</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-spark-creativity-with-costless-auditory-extras/"><u>[Updated] Spark Creativity with Costless Auditory Extras</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-transform-your-social-media-experience-livestream-fb-flawlessly/"><u>[New] Transform Your Social Media Experience  Livestream FB Flawlessly</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-intensive-resource-usage-managing-dropboxs-cpu-in-windows/"><u>Lowering Intensive Resource Usage: Managing Dropbox's CPU in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-ultimate-guide-using-vlc-for-videos/"><u>2024 Approved  Ultimate Guide  Using VLC for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-a-strategy-to-resolve-locked-windows-update/"><u>Unveiling a Strategy to Resolve Locked Windows Update</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-hit-the-floor-with-optimal-posting-hours/"><u>[New] Hit the Floor with Optimal Posting Hours</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-alter-windows-dashboard-imagery-effortlessly/"><u>How to Alter Windows Dashboard Imagery Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-setting-windows-backups-against-original-standards/"><u>Instructions for Setting Windows Backups Against Original Standards</u></a></li>
<li><a href="https://win11.techidaily.com/the-unmatched-features-in-windows-10-why-its-superior-to-win11/"><u>The Unmatched Features in Windows 10: Why It's Superior to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/clipit-woes-uncover-top-fixes-for-swift-recovery/"><u>ClipIt Woes? Uncover Top Fixes for Swift Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-motorola-moto-g14-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Motorola Moto G14 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-channel-identity-made-simple-discover-the-10-best-banner-maker-apps/"><u>[Updated] In 2024, Channel Identity Made Simple  Discover the 10 Best Banner Maker Apps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-dissecting-digital-communication-discord-versus-skype-for-2024/"><u>[Updated] Dissecting Digital Communication  Discord Versus Skype for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/improving-the-effectiveness-of-win-based-discord-queries/"><u>Improving the Effectiveness of Win-Based Discord Queries</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-gain-momentum-with-these-strategies-for-trending-youtubers/"><u>[Updated] In 2024, Gain Momentum with These Strategies for Trending YouTubers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-eliminating-an-obsolete-linkedin-identity-stepwise-guide/"><u>[New] Eliminating an Obsolete LinkedIn Identity  Stepwise Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-understanding-audience-favorites-for-successful-hauls/"><u>In 2024, Understanding Audience Favorites for Successful Hauls</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-parsing-hiccup-code-0xc00ce556/"><u>Correcting Windows Parsing Hiccup Code 0xC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-usage-options-on-windows-11-devices-and-systems/"><u>Streamlining Usage Options on Windows 11 Devices and Systems</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-effortless-pathways-to-scour-for-mass-video-downloads-on-tiktok/"><u>2024 Approved  Effortless Pathways to Scour for Mass Video Downloads on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-out-of-place-window-elements/"><u>Correcting Out-of-Place Window Elements</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-old-ribbon-revival-in-new-windows/"><u>Guide for Old Ribbon Revival in New Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-server-errors-a-windows-guide-to-apex-success-(156-chars/"><u>Eliminating No-Server Errors: A Windows Guide to Apex Success (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttered-windows-desktop-at-a-glance/"><u>Uncluttered Windows Desktop at a Glance</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-java-vm-error-on-windows/"><u>Unraveling the Mystery of Java VM Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-operation-failed-error-code-0x0000011b/"><u>Tackling Operation Failed Error: Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-audio-access-failures-in-audacity/"><u>Troubleshooting Audio Access Failures in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-skip-recurring-enter-credentials-messages/"><u>Techniques to Skip Recurring 'Enter Credentials' Messages</u></a></li>
</ul></div>
