---
title: Fix Windows 11 Drag-and-Drop Failures Now
date: 2024-07-13T10:00:21.812Z
updated: 2024-07-14T10:00:21.812Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-perfect-sync-blueprint-for-android-plus-microsoft-os/"><u>The Perfect Sync Blueprint for Android + Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-screen-snafus-with-sonic-frontiers-securing-smooth-play-on-w11/"><u>Navigating Screen Snafus with Sonic Frontiers - Securing Smooth Play on W11</u></a></li>
<li><a href="https://win11.techidaily.com/provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships.</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-premier-portals-to-retro-playstation-gaming-on-your-desktop-for-2024/"><u>[New] Premier Portals to Retro PlayStation Gaming on Your Desktop for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-system-performance-wins-top-diagnostic-list/"><u>Smooth System Performance: Win's Top Diagnostic List</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-realme-gt-5-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Realme GT 5 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-quest-for-content-videos-in-social-media-network-for-2024/"><u>[New] The Quest for Content  Videos in Social Media Network for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-13-mini-screen-lock-without-losing-data-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 13 mini screen lock without losing data</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-connection-error-restoring-mb-link-on-windows-11/"><u>Overcoming Connection Error: Restoring MB Link on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-access-control-personalized-windows-pin-creation/"><u>Revolutionize Access Control: Personalized Windows Pin Creation</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-robloxs-restrictive-error-403-on-pc/"><u>Unraveling Roblox's Restrictive Error 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-clarity-with-windows-11s-enhanced-photo-app/"><u>Maximizing Image Clarity with Windows 11'S Enhanced Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-top-picks-ultimate-tools-for-efficient-scheduling-screen-captures/"><u>In 2024, Top Picks  Ultimate Tools for Efficient Scheduling Screen Captures</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-rectify-slow-windows-app-connections-for-peak-performance/"><u>Swiftly Rectify Slow Windows App Connections for Peak Performance</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-enhance-image-edges-with-circular-smear-technique-ps-for-2024/"><u>[Updated] Enhance Image Edges with Circular Smear Technique PS for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-unleashing-creativity-capturing-and-editing-impressive-videos-in-adobe-connect/"><u>In 2024, Unleashing Creativity  Capturing & Editing Impressive Videos in Adobe Connect</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-generate-tones-with-ease-5-top-online-tools-no-cost/"><u>Updated In 2024, Generate Tones with Ease 5 Top Online Tools No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-mdm-from-iphone-14-pro-max-without-a-computer-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove MDM from iPhone 14 Pro Max without a computer?</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-past-the-steam-file-access-hurdle/"><u>Stepping Past the Steam “File Access” Hurdle</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-discover-the-power-of-youtube-audio-downloading-a-detailed-guide/"><u>Updated In 2024, Discover the Power of YouTube Audio Downloading A Detailed Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-snap-shooting-techniques-for-zoom-calls/"><u>In 2024, Snap Shooting Techniques for Zoom Calls</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-blemishes-to-beauty-a-step-by-step-fcpx-skin-smoothing-guide-for-2024/"><u>From Blemishes to Beauty A Step-by-Step FCPX Skin Smoothing Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-ultimate-twitreact-guidebook/"><u>[New] In 2024, The Ultimate TwitReact Guidebook</u></a></li>
</ul></div>
