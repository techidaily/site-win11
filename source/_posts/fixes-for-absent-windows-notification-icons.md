---
title: Fixes for Absent Windows Notification Icons
date: 2024-07-13T10:16:15.682Z
updated: 2024-07-14T10:16:15.682Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixes for Absent Windows Notification Icons
excerpt: This Article Describes Fixes for Absent Windows Notification Icons
keywords: Fix Missing WinNotifyIcons,Restore Window Icons,Icon Recovery Tool,NotifyIcon Repair,Reinstall WinNotification,Clear Notification Icons,Icon Update Solution
thumbnail: https://thmb.techidaily.com/2151304b15358b5e0486365b1b4e0f5fc2185a4452deb2b08eaf2b9d1e47c0a1.jpg
---

## Fixes for Absent Windows Notification Icons

 Typically, apps that are pinned to the taskbar or running on your computer display notification badges on their icons to provide a visual cue for new or unread notifications. Occasionally, however, you might find that Windows won't show notification badges for some or all the taskbar icons on your computer.

 If you are troubled by this issue, don't fret. We have some quick and easy fixes that will get Windows to display notification badges once again.

## 1\. Modify the Taskbar Behavior

 To start, you need to ensure that the taskbar is configured to show notification badges on your computer. Here are the steps for doing the same.

1. Right-click on the**Start icon** and select**Settings** from the list.
2. Select**Personalization** from the left sidebar.
3. Click on**Taskbar** .
4. Click on**Taskbar behaviors** to expand it.
5. Tick the checkbox that reads**Show badges on taskbar apps** .  
![Enable Badges on Taskbar Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-badges-on-taskbar-apps-on-windows.jpg)

 Following this, apps should display notification badges on the taskbar.

## 2\. Make Sure App Notifications Are Enabled

 Another reason why badges may not appear on taskbar apps is if you have turned off notifications on Windows. If you are unsure, use these steps to check if notifications are enabled on your computer.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. In the**System** tab, click on**Notifications** .
3. Enable the toggle next to**Notifications** , if it isn’t already.
4. Scroll down to the**Notifications from apps and other senders** section and ensure that your favorite apps are allowed to display notifications on Windows.  
![Enable Notifications for Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-notifications-for-apps-on-windows.jpg)

## 3\. Allow Apps to Run in the Background

 If your apps do not have the necessary permission to run in the background, they will fail to fetch new data and display any notifications. This may lead you to believe that notification badges are not working for the taskbar apps. To avoid this, you should ensure that your apps are allowed to run in the background on Windows by following the steps below.

1. Right-click on the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll through the list or use the search bar at the top to locate the problematic app.
4. Click the**three-dot menu icon** next to the app and select**Advanced options** .
5. Use the drop-down menu under**Background apps permissions** to select**Always** .  
![Allow Xbox to Run in the Background on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/allow-xbox-to-run-in-the-background-on-windows.jpg)

 Unable to find the background app permissions option in the Settings app? Check our guide on [how to restore a missing background apps permission option in Windows](https://www.makeuseof.com/windows-11-restore-background-apps-permissions/) .

## 4\. Restart the Windows Explorer Process

 Temporary issues with the taskbar can also prevent apps from displaying notification badges on Windows. This usually happens when the Windows Explorer process, which is responsible for providing the Graphical User Interface (GUI) for the taskbar, experiences problems.

 If it’s just a minor glitch, restarting the Windows Explorer process should help fix it. If you need help with the same, check our guide on [different ways to restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) and follow the steps outlined there.

 Note that your taskbar will disappear for a brief moment when you restart the Windows Explorer process. After that, check if notification badges appear on the taskbar apps.

## 5\. Unpin the Apps From the Taskbar and Pin Them Again

 If Windows is failing to display notification badges for only one or two apps, you can try to unpin the affected apps from the taskbar and pin them back again. To do so, use these steps:

1. Right-click on the problematic app icon and select**Unpin from taskbar** .
2. Press**Win + S** to open the search menu.
3. Type the name of the app in the search box.
4. Select**Pin to taskbar** from the right pane.  
![Unpin App From Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/unpin-app-from-windows-taskbar.jpg)

 Repeat the above steps for all the apps that are not displaying badges on the taskbar.

## 6\. Repair the Problematic App

 If the issue remains even after you unpin and re-pin the app, you can try repairing it. This process will allow Windows to identify and resolve any issues with the app without affecting any of the app data. For more information on this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 7\. Enable Taskbar Badges Using the Registry Editor

 Windows may not show notification badges on taskbar apps if the feature has been disabled via the Registry Editor. In that case, you will need to modify the**TaskbarBadges** DWORD using the Registry Editor to bring back notification badges on Windows.

 As you may already know, editing registry files in Windows involves risk. Hence, it’s important to be cautious while using the Registry Editor. If you’re unfamiliar with it, we recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 Also, it’s a good idea to [back up all the Registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. Once you've done that, use these steps to enable taskbar badges on Windows via the Registry Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced** .
5. In the right pane, locate the**TaskbarBadges** entry. If you can’t find it, right-click on the**Advanced** key, and select**New > DWORD (32-bit) Value** . Rename the DWORD to**TaskbarBadges** .
6. Double-click on the**TaskbarBadges** DWORD to edit it.
7. In the**Value data** field, enter**1** .
8. Click**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-dword-in-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. After that, notification badges should appear on taskbar apps.

## Stay on Top of App Alerts With Notification Badges

 Taskbar notification badges are useful as they inform you about apps and programs awaiting your attention. Hopefully, one of the above fixes has helped you resolve the underlying issue and Windows is now showing notification badges for taskbar apps.

 Finding it hard to notice the taskbar notification badges because of their small size? You can always enlarge the Windows taskbar to make the notification badges more visible.


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
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-what-is-an-ai-editor-wondershare-virbo-glossary/"><u>2024 Approved What Is an AI Editor? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-risks-for-windows-bt-folder-expert-advice/"><u>Deletion Risks for Windows ~BT Folder: Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-13-pro-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 13 Pro You Should Try Out</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-navigating-updated-youtube-money-strategies/"><u>2024 Approved  Navigating Updated YouTube Money Strategies</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/save-instagram-music-a-simple-mp3-download-tutorial-for-2024/"><u>Save Instagram Music A Simple MP3 Download Tutorial for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-username-switch-on-windows-11/"><u>Streamlining the UserName Switch on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-a-distraction-free-start-with-win-11/"><u>Embrace a Distraction-Free Start with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-handshake-direct-pc-links-in-windows-11-rdp/"><u>The Invisible Handshake: Direct PC Links in Windows 11 RDP</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-optimal-windows-11-search-performance/"><u>Navigating to Optimal Window's 11 Search Performance</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/navigate-the-maze-of-mp4-cutters-for-mac-creators-for-2024/"><u>Navigate the Maze of MP4 Cutters for Mac Creators for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-everlasting-file-elimination-on-your-desktop-bin-with-windows-11/"><u>Simplifying Everlasting File Elimination on Your Desktop Bin with Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-final-cut-pro-x-debugging-secrets-unleash-your-editing-potential/"><u>New In 2024, Final Cut Pro X Debugging Secrets Unleash Your Editing Potential</u></a></li>
<li><a href="https://win11.techidaily.com/ditching-taskbar-chatting-in-windows-11-how-will-it-influence-your-experience/"><u>Ditching Taskbar Chatting in Windows 11: How Will It Influence Your Experience?</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-accessing-win-11s-call-center/"><u>Quick Guide: Accessing Win 11'S Call Center</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-vivo-v27-pro-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Vivo V27 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fix-missing-fb-watch-icon-quick-guide/"><u>[New] Fix Missing FB Watch Icon - Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-on-windows-11-desktop-ui/"><u>Increase Visible Pins on Windows 11 Desktop UI</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/androidmac-method-for-saving-snaps/"><u>Android/Mac Method for Saving Snaps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-the-year-2024-how-to-follow-sourav-joshi-on-youtube-income/"><u>In the Year 2024, How to Follow Sourav Joshi on YouTube Income</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-realme-12-pro-5gs-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Realme 12 Pro 5G’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-process-how-to-setup-google-maps-on-pc/"><u>A Step-by-Step Process: How to Setup Google Maps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-honor-90-gt-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Honor 90 GT Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-adding-gmaps-in-windows-os/"><u>The Ultimate Guide to Adding GMaps in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/essential-advice-to-supercharge-your-wsl-2-and-docker-use/"><u>Essential Advice to Supercharge Your WSL 2 and Docker Use</u></a></li>
</ul></div>
