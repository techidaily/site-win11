---
title: Fixing No Logging in Run Commands on PCs
date: 2024-06-25T11:41:20.204Z
updated: 2024-06-26T11:41:20.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing No Logging in Run Commands on PCs
excerpt: This Article Describes Fixing No Logging in Run Commands on PCs
keywords: Stop PC No-Log Commands,Disable Command Line Logout,Prevent Run Command Logouts,Halt Console No-Record Feature,Cease Ignored Terminal Events,Block Unlogged Command Execution,Quell Non-Logging Commands
thumbnail: https://thmb.techidaily.com/acc4624304fa10f6661dcbd0f5aeeaf72266dc48176909da6153f980695e7df6.png
---

## Fixing No Logging in Run Commands on PCs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-to-reset-and-redo-store-registrations-in-win-11/"><u>How to Reset and Redo Store Registrations in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-yuzu-experience-on-windows/"><u>Supercharge Your Yuzu Experience on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-upgrades-techniques-for-ensuring-optional-components-on-windows-os/"><u>Optimal Upgrades: Techniques for Ensuring Optional Components on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-installed-windows-11-on-mac-through-parallels/"><u>Breaking the Barrier: Installed Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-browsing-post-windows-installation/"><u>Effortless Browsing Post-Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-windows-11-cc-issues/"><u>Quick-Fix Strategies for Windows 11 CC Issues</u></a></li>
<li><a href="https://win11.techidaily.com/auto-shutdown-hacks-for-idle-pcs-running-w10w11/"><u>Auto Shutdown Hacks for Idle PCs Running W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-windows-1011-camera-app-error-a00f429f/"><u>Steps to Eliminate Windows 10/11 Camera App Error A00F429F</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-efficient-scratching-tool-for-chromeos/"><u>[New] Efficient Scratching Tool for ChromeOS</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-realme-c67-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-integrating-mixer-with-macos-for-smooth-streaming/"><u>[New] 2024 Approved  Integrating Mixer with macOS for Smooth Streaming</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-from-zero-to-hero-beginner-friendly-video-editors/"><u>New 2024 Approved From Zero to Hero Beginner-Friendly Video Editors</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-gain-more-traction-on-tiktok-a-compendium-of-unique-username-concepts/"><u>2024 Approved  Gain More Traction on TikTok  A Compendium of Unique Username Concepts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-enhanced-viewing-fb-videos-on-large-displays/"><u>[New] 2024 Approved  Enhanced Viewing  FB Videos On Large Displays</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-huawei-p60-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Huawei P60 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-prime-video-game-editors-simplified-top-picks-for-newbies-for-2024/"><u>[Updated] Prime Video Game Editors Simplified  Top Picks for Newbies for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>