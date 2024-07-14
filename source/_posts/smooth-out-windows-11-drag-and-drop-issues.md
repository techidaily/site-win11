---
title: Smooth Out Windows 11 Drag-and-Drop Issues
date: 2024-07-13T10:20:57.269Z
updated: 2024-07-14T10:20:57.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Smooth Out Windows 11 Drag-and-Drop Issues
excerpt: This Article Describes Smooth Out Windows 11 Drag-and-Drop Issues
keywords: Win11DragDropTips,ResolveWinDragIssue,FixWindows11DragError,SmoothWin11Upgrade,DragDropWin11Update,NoMoreWinDragProblems,11UpgradeSmoothProcess
thumbnail: https://thmb.techidaily.com/ef64597bda93820e24d8ab2d0a8cbf446e80301b9ceb1303c686c48229c6eca3.jpg
---

## Smooth Out Windows 11 Drag-and-Drop Issues

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
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-realme-c67-4g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Realme C67 4G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-system-health-improvement-via-updates/"><u>Understanding System Health Improvement via Updates</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-immersive-escapes-delving-into-jaunt-vr/"><u>2024 Approved  Immersive Escapes  Delving Into Jaunt VR</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-nubia-red-magic-9-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Nubia Red Magic 9 Pro Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-device-communication-via-google-sharing/"><u>Tips for Efficient Device Communication via Google Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-vivo-y100-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Vivo Y100? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-recurring-anydesk-errors-on-windows/"><u>Unraveling the Mysteries of Recurring AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-access-denied-on-nvidia-panel/"><u>Quick-Fix Tips for Access Denied on NVIDIA Panel</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-failed-zip-file-extractions-on-windows-11/"><u>How To Reverse Failed Zip File Extractions on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/highpoint-artist-toolkit-review-for-2024/"><u>Highpoint Artist Toolkit Review for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-unleash-creativity-with-these-5-windows-11-record-methods/"><u>2024 Approved  Unleash Creativity with These 5 Windows 11 Record Methods</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-speech-recognition-launch-failures-in-windows-os/"><u>Overcoming Speech Recognition Launch Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-frame-rate-conversion-20mb-video-specs/"><u>2024 Approved  Frame Rate Conversion  20MB Video Specs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-checklist-for-broadcasting-on-discord/"><u>[New] The Ultimate Checklist for Broadcasting on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-s17-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo S17 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winfixer-rectifying-the-network-not-reachable-error-in-windows-11/"><u>Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-endless-scrolls-on-large-datasheets-windows/"><u>Overcome Endless Scrolls on Large Datasheets, Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-best-of-the-best-10-animated-text-software-for-pro-results/"><u>2024 Approved The Best of the Best 10 Animated Text Software for Pro Results</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-convert-vimeo-hd-mp4-format-guide/"><u>[New] In 2024, Convert Vimeo HD  MP4 Format Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-savers-a-guide-to-win11/"><u>Tailoring Screen Savers: A Guide to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-top-5-cost-effective-video-editing-software-for-gamers/"><u>In 2024, Top 5 Cost-Effective Video Editing Software (For Gamers)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-approach-installing-and-using-outlook-preview-for-windows-11-users/"><u>Tailored Approach: Installing and Using Outlook Preview for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-microsoft-store-crash-error-0x800704cf-in-windows/"><u>Quick Fix for Microsoft Store Crash: Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-checks-when-windows-obs-studio-wont-launch/"><u>Essential Checks When Windows' OBS Studio Won't Launch</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-off-chrome-notifications-windows-version/"><u>Steps to Turn Off Chrome Notifications, Windows Version</u></a></li>
</ul></div>
