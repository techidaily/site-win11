---
title: Avoid Disruption - Bypass Game Glitches Immediately
date: 2024-07-13T11:28:13.747Z
updated: 2024-07-14T11:28:13.747Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Disruption - Bypass Game Glitches Immediately
excerpt: This Article Describes Avoid Disruption - Bypass Game Glitches Immediately
keywords: Avoiding Game Glitches,Quick Glitch Fixing,Halt Disruptions,Gameplay Stability,Skip Glitches,Immediate Fix,Smooth Gaming Experience
thumbnail: https://thmb.techidaily.com/74722f9cb9d89019ce2bd2f1c80c266bfc2adc6c2152da5539a4a5d5cb3e57e3.jpg
---

## Avoid Disruption - Bypass Game Glitches Immediately

 When Minecraft fails to launch correctly, it will sometimes crash with the "exit code: 1" error. While the error message indicates issues with Java runtime configuration, there can also be other reasons. An outdated graphics driver, incorrect in-game settings, incompatible mods, buggy game files, and an invalid launcher file path can also trigger the "exit code:1" error on Windows.

 Here we show you a few quick troubleshooting steps to fix the "exit code: 1" and get back to playing Minecraft on your Windows computer.

## 1\. Delete or Disable Outdated Mods

 The "exit code: 1" error can occur due to outdated mods. To resolve the error, check the Minecraft mods folder and delete it. Removing mods can break your worlds. So make sure to create a backup before attempting to remove any mods. Here’s how to do it.

1. Press**Win + R** and type the following in the**Run** dialog:  
`%appdata%\`
2. Click**OK** to open the**AppData\\Roaming** folder in**File Explorer** .  
![appdata run dialog windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/appdata-run-dialog-windows-11.jpg)
3. Next, open the**.minecraft** folder.  
![minecraft mods folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-mods-folder-windows-file-explorer.jpg)
4. Open the**mods** folder inside the**.minecraft** folder.
5. Select and right-click on all the**mods** one by one and select**Delete** .

 Once all the mods are removed, close File Explorer and relaunch Minecraft to see if the error is resolved. On the flip side, you may find some Minecraft levels (worlds) broken upon launch. You may also want to re-download mods to make further modifications.

## 2\. Repair Minecraft Launcher

 You can fix common problems with the Minecraft Launcher using the [built-in repair option on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) . During repair, Windows will look for common issues and try to fix them automatically. It will also delete the app’s data.

To repair Minecraft Launcher:

1. Press**Win + I** to open**Windows** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed Apps** and search**Minecraft Launcher** .  
![minecrafft launcher advanced options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecrafft-launcher-advanced-options-windows-11.jpg)
4. Next, click the**three-dots menu** beside the app name and select**Advanced Options** .  
![repair minecraft launcher windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/repair-minecraft-launcher-windows-11.jpg)
5. Scroll down to the**Reset** section and click**Repair** . Windows will perform a quick repair and show a checkmark once the repair is complete.
6. Relaunch Minecraft Launcher and check for any improvements.

 Similarly, you can also repair your Minecraft game. Open Minecraft’s**Advanced Options** and perform a repair in the**Settings** app.

## 3\. Modify the Minecraft Launcher File Path

![modify minecraft launcher file path working directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-minecraft-launcher-file-path-working-directory.jpg)

 Issues with the Minecraft Launcher file path can cause the "exit code: 1" on Windows. If your user name has a special character, the Minecraft Launcher file path may not respond to a user account with a special character.

 To fix the issue, you’ll need to modify the Minecraft Launcher file path to allow the launcher to access the launcher without special characters.

To change the Minecraft Launcher file path:

1. Right-click on the**Minecraft Launcher** shortcut and select**Properties** .
2. In the**Properties** dialog, open the Shortcut pat.
3. In the**Target** field, add the following line to change the working directory for Minecraft Launcher. You need to add the below lines after the existing file path:  
`&ndash;workDir %ProgramData%.minecraft`
4. After modifications, the target field will look something like this:  
`"C:\Program Files (x86)\Minecraft Launcher\MinecraftLauncher.exe" &ndash;workDir %ProgramData%.minecraft`
5. Click**Apply** and**OK** to save the changes.
6. Relaunch Minecraft and check for any improvements.

## 4\. Change the Java Executable Path

 Your Minecraft installation can run into issues if the launcher fails to detect the correct Java file. While Minecraft Launcher automatically installs the required JRE version, at times, you may need to manually change the executable to run the modified version of the game.

To change the Java executable for Minecraft:

1. Open the**Minecraft Launcher** .
2. Next, select the**Minecraft Java Edition** tab in the left pane.
3. Open the**Installations** tab in the toolbar.
4. Hover your mouse over**Latest Release** and click the**three-dots menu.**
5. Select**Edit** from the menu.  
![minecraft launcher latest release edit windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-launcher-latest-release-edit-windows.jpg)

1. Click**More Options** to view additional options.
2. Click**Browse** to add a**Java Executable** .  
![java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-executable-browse-minecraft-launcher-windows.jpg)
3. Navigate to your Java installation. By default, the JRE file path is:  
`C:\Program Files (x86)\Java\jre1.8.0_361\bin`
4. Select the**Java.exe** file and click**Open** .  
![select JRE java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/select-jre-java-executable-browse-minecraft-launcher-windows.jpg)
5. Click**Save** to apply the changes and relaunch Minecraft Launcher.
6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

## 5\. Reinstall Minecraft Without Deleting Saves

 You can reinstall Minecraft to fix issues with the game. Depending on how you installed the game, you can uninstall Minecraft from the Settings app or delete the .minecraft Appdata folder. If you prefer, you can also choose to keep your Minecraft saves.

To backup Minecraft saves and uninstall the game:

1. Press**Win + R** to open the**Run** dialog.
2. Paste the following in the**Run** field and click**OK** :  
`%appdata%\`
3. Open the**.minecraft** folder.  
![delete minecraft data folder uninstall windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-minecraft-data-folder-uninstall-windows.jpg)
4. Right-click on the saves folder and select**Copy (Ctrl +C)** .
5. Paste the**saves** folder outside the**.minecraft** folder.  
![minecraft saves folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-savess-folder-windows-file-explorer.jpg)
6. Next, return to the**Roaming** folder and delete the**.minecraft** folder to uninstall the game.
7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to [install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)

 The "exit code: 1" error often hints at invalid Java runtime configuration issues. You can reinstall Java to fix configuration issues fixed in the latest release.

To reinstall Java Runtime Environment:

1. Go to the [Java download page](https://www.java.com/en/download/manual.jsp) .
2. Select the correct version for your Windows computer. You can opt for the Windows Online or Offline version. Also, download the 64-bit version if applicable.
3. Run the installer and follow the on-screen instructions to complete installations.
4. Once installed, restart your computer and check for any improvements.

## Fixing the Minecraft Exit Code: 1 Error

 Many things can go wrong and trigger the "exit Code: 1 error" in Minecraft. To resolve the issue, try to disable mods and change the Minecraft Launcher path. If the issue persists, check your graphics driver for the problem.

 If all else fails, perform a reinstall. You can reinstall Minecraft while keeping saves. If you are using the latest Microsoft Store version of the game, you can also uninstall it from the settings app.


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
<li><a href="https://win11.techidaily.com/breached-bytebandit-ponder-the-path-for-a-possible-pivot/"><u>Breached ByteBandit: Ponder the Path for a Possible Pivot</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/gaming-transformed-by-tech/"><u>Gaming Transformed by Tech</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-reimagining-administrative-protocols-on-windows/"><u>Breaking Barriers: Reimagining Administrative Protocols on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/transferring-twitter-videos-to-whatsapp-effortlessly/"><u>Transferring Twitter Videos to WhatsApp Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-10-safe-free-software-download-sites/"><u>Best Practices: 10 Safe Free Software Download Sites</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-perfect-hover-over-experience-win11-mouse-guide/"><u>Achieve a Perfect Hover Over Experience: Win11 Mouse Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-does-immediate-subscribing-affect-content-recommendations/"><u>[Updated] 2024 Approved  Does Immediate Subscribing Affect Content Recommendations?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-motorola-by-fonelab-android-recover-data/"><u>How to recover lost data from Motorola ?</u></a></li>
<li><a href="https://win11.techidaily.com/boost-input-speed-learn-from-typingaid/"><u>Boost Input Speed: Learn From TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-to-accessing-steam-files/"><u>Breaking Down Barriers to Accessing Steam Files</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://win11.techidaily.com/basking-in-low-light-the-art-of-dark-modes-in-paint/"><u>Basking in Low Light: The Art of Dark Modes in Paint</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windows-passwords-the-11-easiest-ways-to-open-credential-manager/"><u>Breaking Into Windows Passwords: The 11 Easiest Ways to Open Credential Manager</u></a></li>
<li><a href="https://extra-hints.techidaily.com/8-popular-oculus-rift-games-you-should-try-for-2024/"><u>8 Popular Oculus Rift Games You Should Try for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-human-interface-ai-in-windows-tomorrow/"><u>Beyond Human Interface: AI in Windows Tomorrow</u></a></li>
<li><a href="https://win11.techidaily.com/boost-playnites-capabilities-with-windows-compatible-emulators/"><u>Boost Playnite's Capabilities with Windows-Compatible Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-system-interactions-a-step-bystep-guide/"><u>Advanced File System Interactions: A Step-Bystep Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-pioneering-profit-navigating-the-path-to-money-making-on-vimeo/"><u>[Updated] In 2024, Pioneering Profit  Navigating the Path to Money-Making on Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-challenges-of-windows-steam-content-blocks/"><u>Avoiding the Challenges of Windows Steam Content Blocks</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-retrospective-on-the-goofy-movie-a-comprehensive-review/"><u>[New] Retrospective on 'The Goofy Movie'  A Comprehensive Review</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-top-10-budget-friendly-mmorpg-experiences/"><u>[Updated] Top 10 Budget-Friendly MMORPG Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-benefits-of-16gb-windows-memory/"><u>Breaking Down the Benefits of 16GB Windows Memory</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-10-gaming-youtubers-you-may-want-to-subscribe/"><u>Top 10 Gaming YouTubers You May Want to Subscribe</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-humor-hub-creator/"><u>[Updated] In 2024, Humor Hub Creator</u></a></li>
<li><a href="https://win11.techidaily.com/averting-the-def5-blunder-in-onedrive-w11-issues/"><u>Averting the Def5 Blunder in OneDrive W11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/beating-down-error-code-31-in-the-windows-landscape/"><u>Beating Down Error Code 31 in the Windows Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-in-remote-steam-functionality/"><u>Breaking Barriers in Remote Steam Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-using-github-desktop-on-windows-1011/"><u>Boost Productivity: Using GitHub Desktop on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-through-strategic-task-management-in-windows-11/"><u>Boosting Productivity Through Strategic Task Management in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-v20-document-with-digital-signature-software-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a PDF v2.0 document with digital signature software</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-black-backdrops-on-windows/"><u>Breaking Free From Black Backdrops on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-gionee-f3-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Gionee F3 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-realme-c67-4g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Realme C67 4G Phone Screen?</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-boost-your-photo-workflow-in-windows-11-for-2024/"><u>[Updated] Boost Your Photo Workflow in Windows 11 for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-oppo-find-x6-pro-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Oppo Find X6 Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-not-working-mishaps-on-your-devices-windows-apps/"><u>Avoiding 'Not Working' Mishaps on Your Device’s Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/best-browsing-on-three-oses-minimal-resource-browser-choices/"><u>Best Browsing on Three OSes: Minimal Resource Browser Choices</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-android-performance-with-optimized-resources-on-wsl/"><u>Boosting Android Performance with Optimized Resources on WSL</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-easy-ways-to-change-aspect-ratio-in-imovie/"><u>Updated Easy Ways to Change Aspect Ratio in iMovie?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-samsung-galaxy-a23-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Samsung Galaxy A23 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-ntfs-compression-in-win11-systems/"><u>Advanced Tips for NTFS Compression in Win11 Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Nokia 105 Classic? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-tiktok-bugs-what-if-my-tiktok-not-working/"><u>[Updated] In 2024, Tiktok Bugs  What If My Tiktok Not Working?</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-converting-heic-images-to-jpeg-in-windows-11/"><u>Advanced Tips for Converting HEIC Images to JPEG in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-dive-into-makers-earnings-exploring-youtube-shorts-revenue-structure/"><u>[Updated] 2024 Approved  Dive Into Maker's Earnings  Exploring YouTube Shorts Revenue Structure</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-using-keyboard-shortcuts-for-windows-taskbar-management/"><u>Boosting Efficiency: Using Keyboard Shortcuts for Windows Taskbar Management</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-instagram-engage-obs-live-streaming/"><u>[New] 2024 Approved  Instagram Engage  OBS Live Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windowsstore-app-folder-secrets/"><u>Breaking Into WindowsStore App Folder Secrets</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-samsung-galaxy-a14-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/boost-keyboard-efficiency-top-strategies-for-speed-on-windows-devices/"><u>Boost Keyboard Efficiency: Top Strategies for Speed on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-obs-full-screen-nightmare-ended/"><u>[Updated] 2024 Approved  Obs Full-Screen Nightmare Ended</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-login-failure-threshold-step-by-step-for-windows-11-users/"><u>Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-innovative-techniques-for-ppts-and-webcams-2023-edition/"><u>2024 Approved  Innovative Techniques for PPTs and Webcams, 2023 Edition</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-xbox-expansion-top-5-external-hard-drives-ranked/"><u>[Updated] Xbox Expansion  Top 5 External Hard Drives Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/beating-full-screen-freezes-and-crashes-in-sonic-games-on-w11-os/"><u>Beating Full-Screen Freezes and Crashes in Sonic Games on W11 OS</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-poco-x6-pro-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-honor-magic-5-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Honor Magic 5 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-the-required-apple-store-verification-for-iphone-12-pro-max-by-drfone-ios/"><u>How To Bypass the Required Apple Store Verification For iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-verified-app-alerts-for-windows-users/"><u>Addressing Non-Verified App Alerts for Windows Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-oneplus-ace-2-pro-unlock-without-password-by-drfone-android/"><u>5 Solutions For OnePlus Ace 2 Pro Unlock Without Password</u></a></li>
</ul></div>
