---
title: Fix Windows 11 Drag-and-Drop Failures Now
date: 2024-06-25T11:26:41.879Z
updated: 2024-06-26T11:26:41.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Windows 11 Drag-and-Drop Failures Now
excerpt: This Article Describes Fix Windows 11 Drag-and-Drop Failures Now
keywords: Fix Windows 11 Issues,Drop Errors in Win11,Resolve Win11 DragFail,Win11 Drag-Drop Fix,Correct Win11 D&D Failures,Windows 11 Drag-and-Drop Solve,Stop Win11 DragFail Issues,Windows 11 Drag-Drop Fixes,Resolve Win11 D&D Errors,Quick Fix for Win11 DragFail,Win11 Drop Fail Repair,Stop Win11 Dropping Issue,Address Win11 D&D Fails,End Win11 Drag Fail
thumbnail: https://thmb.techidaily.com/4f252061500e08e9c2f2521977c5b0253a500625454298afd84e9855ed4fbb6b.jpg
---

## Fix Windows 11 Drag-and-Drop Failures Now

 Drag and drop is a simple yet useful feature that makes it easy to move items around on your screen. With it, you can quickly relocate your files and folders without having to switch between windows or use keyboard shortcuts.

 While that’s convenient, there can be times when the drag and drop feature stops working on your Windows 11 computer. If you are facing the same problem, here are some solutions that will help.

## 1\. Start With Some Generic Fixes

 It's a good idea to try some generic Windows fixes before spending time on any advanced solutions.

* **Restart Windows Explorer:** An unresponsive Windows Explorer process can cause features like drag and drop to stop working in Windows 11\. Most of the time, you can fix such problems by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Install Windows Updates:** Running an outdated Windows build can also lead to such issues. Hence, it’s a good idea to [install pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) if you haven’t already.
* **Run the SFC Scan:** If some of the system files on your PC are corrupted or missing, Windows 11 may not respond to the drag and drop gesture. Try [running the SFC (or System File Checker) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to repair any damaged system files and see if that helps.
* **Scan for Malware:** A malware infection is another possible cause of this issue. To rule this out, try [scanning your PC for malware with PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or an antivirus program.
* **Try Clean Boot:** It’s possible that a rouge third-party app or program on your PC is causing the drag and drop feature to malfunction. If that’s the case, [booting your PC in a clean boot state](https://www.makeuseof.com/clean-boot-windows-11/) will help you verify that.

## 2\. Use the Esc Key

 At times, Windows may freeze on the last drag and drop operation and stop responding to new actions. If it's just a one-off glitch, simply resetting the drag and drop gesture should do the trick.

 Left-click and hold the file or folder you want to drag and click the **Esc** key. Then, release the left click on your mouse, and check if you can drag and drop items after that.

## 3\. Restart the Problematic App

 If the drag and drop feature is not working only in a specific app, such as Chrome or Outlook, there may be an issue with that app. You can try restarting the problematic app or program to fix the problem.

 Press **Ctrl + Shift + Esc** to open the Task Manager. In the **Processes** tab, locate and select the faulty app or program, and click the **End task** option at the top.

![Close Programs Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/close-programs-using-task-manager.jpg)

 Reopen your app and check if the issue still occurs.

## 4\. Run the Hardware and Devices Troubleshooter

 Running the Hardware and devices troubleshooter is an effective way to fix issues with your peripherals. This tool can scan all the hardware devices connected to the system, including your mouse or touchpad, and resolve any issues with them.

 Since this troubleshooter is not accessible through the Settings app, you will need to use the Run command to start it. Here are the steps you can follow:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Advanced** and tick the **Apply repairs automatically** checkbox.
4. Click **Next** to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hardware-and-devices-troubleshooter-on-windows.jpg)

## 5\. Update or Reinstall Mouse Drivers

 Outdated or damaged mouse or touchpad drivers can also cause drag and drop to stop working in Windows 11\. If that’s the case, updating the relevant drivers should help solve the problem.

 Here are the steps to do the same:

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Mice and other pointing devices** to expand it.
4. Right-click on your mouse or touchpad device and select **Update driver**.  
![Update Mouse Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-mouse-driver.jpg)

 Follow the on-screen prompts to finish updating the driver.

 If the issue remains even after this, you can try uninstalling the mouse driver from your PC. If you need help with that, check our guide on [how to uninstall drivers in Windows 11](https://www.makeuseof.com/windows-11-uninstall-drivers/). After removing the driver, restart your PC, and Windows will automatically reinstall the missing driver during the boot process.

## 6\. Check Your Mouse for Issues

 Issues with your mouse can also make it seem like the drag and drop feature is not working on Windows 11\. Try disconnecting your mouse and reconnecting it to see if that works. If you’re using a wireless mouse, swap the old batteries or charge it.

 For more help, refer to our guide on [fixing the left-click mouse button not working issue on Windows](https://www.makeuseof.com/tag/fix-left-mouse-button/) and follow the tips mentioned there.

## 7\. Edit Registry Files

 Incorrect registry entries can also cause such anomalies. You need to review the registry values related to the drag and drop feature and ensure they are configured correctly.

 Making incorrect modifications to registry files can lead to serious problems. Hence, you should consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Once you’ve done that, use these steps to fix the drag and drop registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **Desktop** key.  
`HKEY_CURRENT_USER\Control Panel\Desktop`
5. In the right pane, double-click the **DragHeight** entry and change its value data to **4**. Then, click **OK**.
6. Similarly, set the value of the **DragWidth** entry value to **4**.  
![Drag and Drop Registry Entries on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/drag-and-drop-registry-entries-on-windows.jpg)

 Restart your PC after making the above changes and see if the drag and drop feature works after that.

## Effortlessly Move Your Files With Drag and Drop Functionality on Windows

 Drag and drop is one of those Windows 11 features that once you start using it, you can’t go back. Hence, it can be inconvenient when the feature stops working on your PC. We hope that going through the above tips has helped you fix the problem and put you at ease.

 While the default drag and drop action can help you move items quickly, you can also modify it to copy or create shortcuts for files and folders on Windows.

## FAQ

### Q: How Do You Drag Maximized Windows in Windows 11?

 You drag maximized Windows in Windows 11 by pressing and holding down the Windows key and pressing an arrow key (right, left, up, or down arrow key). This changes your current window's position on your screen.

### Q: How Do You Change Drag and Drop From Copy to Move in Windows 11?

 You can change drag-and-drops's action from copy to move by holding down the Shift key while dragging and dropping your files. This makes Windows move your files instead of copying them to a folder.

### Q: How Do You Drag and Drop From One Computer to Another?

 You can drag and drop files from one computer to another by opening your target computer's shared folder on your main computer and dragging your files and folders onto that folder window. This copies your computer's files to your chosen computer.

 While that’s convenient, there can be times when the drag and drop feature stops working on your Windows 11 computer. If you are facing the same problem, here are some solutions that will help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-vms-with-virtualbox-70-now-for-windows-11-users/"><u>Boosting Your VMs with VirtualBox 7.0, Now for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-screen-dream-realized-android-plus-windows-11-collaboration/"><u>A Dual-Screen Dream Realized: Android + Windows 11 Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-challenge-of-preview-failures-in-microsoft-mail/"><u>Tackling the Challenge of Preview Failures in Microsoft Mail</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-the-hidden-treasure-troves-of-snapchat-tones/"><u>In 2024, Unveiling the Hidden Treasure Troves of Snapchat Tones</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-maximizing-view-count-for-facebook-videos/"><u>[New] In 2024, Maximizing View Count for Facebook Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-through-mixed-reality-an-overview/"><u>[Updated] Navigating Through Mixed Reality  An Overview</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-enrich-meeting-experience-a-compilation-of-the-top-10-free-apps/"><u>[New] In 2024, Enrich Meeting Experience  A Compilation of the Top 10 Free Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-detailed-guide-securely-recording-on-vimeo/"><u>2024 Approved  Detailed Guide  Securely Recording on Vimeo</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-improving-chromebook-tone-with-top-voice-extensions/"><u>[New] The Ultimate Guide to Improving Chromebook Tone with Top Voice Extensions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>