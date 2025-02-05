---
title: What to Do When the Run Command Won’t Save History on Windows
date: 2025-02-03T07:19:57.208Z
updated: 2025-02-04T02:42:47.354Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What to Do When the Run Command Won’t Save History on Windows
excerpt: This Article Describes What to Do When the Run Command Won’t Save History on Windows
keywords: Run Command Save Issue Windows,Windows Run Failure Logging,Restore Window's Run Command,Fixing No History Record in Run,Resetting Run Command Cache,Tackle Windows Run Non-Saving,Recover Lost Run Command Data
thumbnail: https://thmb.techidaily.com/3c65f68799b4050edde66f042974df77982abdb35ad2689534997125a364839c.jpg
---

## What to Do When the Run Command Won’t Save History on Windows

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-10-top-must-have-gear-items-for-youtubers/"><u>[New] 2024 Approved 10 Top Must-Have Gear Items for YouTubers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-top-8-android-multi-user-video-chat-tools/"><u>[New] 2024 Approved Top 8 Android Multi-User Video Chat Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-exclusive-iphone-filming-software-list/"><u>[Updated] In 2024, Exclusive iPhone Filming Software List</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-mastering-cross-platform-tweeting-twitterfacebook/"><u>2024 Approved Mastering Cross-Platform Tweeting (Twitter/Facebook)</u></a></li>
<li><a href="https://solve-hot.techidaily.com/easy-instructions-to-refresh-scanner-driver-software-in-windows-by-yl-software/"><u>Easy Instructions to Refresh Scanner Driver Software in Windows by YL Software</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-workflow-on-windows-the-best-apps-for-maximum-output/"><u>Elevate Workflow on Windows: The Best Apps for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-printer-use-in-defender-smartscreen-on-edge-browser/"><u>Enabling Printer Use in Defender SmartScreen on Edge Browser</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/fix-samsung-device-transfer-freezing-at-99-100-or-0-complete-guide/"><u>Fix Samsung Device Transfer Freezing at 99%, 100%, or 0% - Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-high-speeds-across-devices/"><u>Harmonizing High Speeds Across Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-bluetooth-pin-related-connectivity-issues-in-win11win10/"><u>How To Bypass Bluetooth Pin-Related Connectivity Issues in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-access-to-commands-setting-up-keybinds-effortlessly/"><u>Speedy Access to Commands: Setting up Keybinds Effortlessly</u></a></li>
</ul></div>

