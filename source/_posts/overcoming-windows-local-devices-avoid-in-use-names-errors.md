---
title: "Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
date: 2024-07-13T09:52:33.748Z
updated: 2024-07-14T09:52:33.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
excerpt: "This Article Describes Overcoming Windows' Local Devices: Avoid In-Use Names Errors"
keywords: AVOID Device Error Windows,Overcome In-Use Name Issue,Resolve Local Devices Error,Stop Windows In-Use Error,Fix In-Used Names on PC,Avoid Local Devices Errors,Correct Windows Usage Error
thumbnail: https://thmb.techidaily.com/57a07625ab9c873f1b8816cfe4ef02cf1a6f9bda4b7acdd0899c793b0d810b70.jpg
---

## Overcoming Windows' Local Devices: Avoid In-Use Names Errors

 The Local device name is already in use error is not particularly unusual. If you work with any type of network, even a local network, you are quite likely to encounter it at some point. Luckily, it is also usually easy to resolve.

 Here are the most common causes of this error, along with the most likely solutions.

## What Causes the Local Device Name Error?

 There can be a couple of possible causes of this error, but pinpointing the exact cause can be difficult. The most common are unassigned drive letters and incorrect file and printer sharing settings.

 It is also possible that a lack of space on the network server can result in this error appearing. You should check this possibility first. If lack of storage is the cause, none of the following solutions will make a difference.

 If the network server has ample space, you can move on to trying the methods below to solve the problem on your local device.

## 1 Enable File and Printer Sharing

[You should always keep your firewall enabled](https://www.makeuseof.com/tag/5-reasons-use-firewall/) , but it can sometimes interfere with file and printer sharing. This can lead to seeing the Local device name is already in use error. Luckily you can enable file and printer sharing easily in the firewall settings.

 If you're using a third-party firewall, refer to the documentation to find the setting. Here's how to enable file and printer sharing in the Microsoft Firewall.

1. Search for Control Panel using Windows Search, and click the search result to open it.
2. Click**System and Security > Windows Defender Firewall** to see the firewall settings.
3. In the left menu, click**Allow an app or feature through the firewall** and then click the**Change settings** button.  
![Windows firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-printer-sharing.jpg)
4. Scroll down to find**File and Printer Sharing** in the list, and click the**Public** checkbox.
5. Click**Ok** and restart your computer to apply the change.

 Occasionally, the file and printer sharing settings for the firewall can get reset after a major update. Just because you know you have enabled it in the past, it is worth checking again.

## 2 Remap the Network Drive With Command Prompt

 Windows will automatically assign a letter to your network drive. During network mapping, the assigned letters can become mixed and even be missing altogether. Remapping the network drive can fix this and prevent the error.

1. The best way to remap the network drive is through the Command Prompt. Search for**cmd** in Windows Search and select**Run as Administrator** .
2. At the cursor, type:**net use D /delete** . Replace**D** with the drive letter you want to delete. Then press**Enter** .  
![the remap network drive command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remap-network-drive.jpg)
3. Now remap the drive by typing:**net use D: \\\\server\\share /user:username password** . Replace the drive letter and user and username password with the relevant details.

 If this doesn't help, you may need to try reassigning the drive letters manually. The end result is similar, but sometimes remapping won't work when manually reassigning the drive path will work.

## 3 Re-assign Drive Letters

 Another common cause of this error is an incorrectly assigned drive letter. Reassigning a drive letter is easy, as long as you don't run into the Drive letter not available error.

1. Search for**Disk Management** using Windows Search, or right-click the Start Menu and select it from the hidden menu.
2. In Disk Management, find the partition or drive you want to change and right-click on it.
3. Select**Change Drive Letter and Paths** , and then click the**Add** button.  
![reassigning drive letter in disk management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reassign-drive-letter.jpg)
4. Click**Assign the following drive letter** and use the drop-down menu to choose a new letter for the partition or drive.

 If the drive letter you require is not available, it may already be being used on another drive or partition. It could also be associated with a removable drive that is not currently connected. If the A and B drive letters are available, and they often aren't, it is best not to use them. These letters are traditionally reserved for floppy drives and for use with old OS versions.

 Learn more about [why drive letters usually start with C on Windows](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

## 4 Reinitialize the Computer Browser

 A less likely solution to this error, but one that does sometimes help, is reinitializing the browser. Browser settings can, in some cases, interfere with network drive settings. By stopping the browser and reinitializing it, those settings should be reverted.

1. Open Windows Search and type**cmd** . In the result, select**Command Prompt** and click**Run as Administrator** .
2. At the Command Prompt cursor, type:**net stop "Computer Browser"** and then press**Enter** .  
![reinitialize the browser on command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinitialize-browser.jpg)
3. When the command finishes executing, type:**net start "Computer Browser"** and press**Enter** .
4. You can now close the Registry Editor and check to see if the error persists.

 Reinitializing the browser is different from simply closing and reopening the browser window. It is a much more forceful solution to clearing any browser settings that may be in conflict.

 Learn how to optimize and get the most from your computer with these [essential Windows performance tips](https://www.makeuseof.com/tag/windows-10-faster-performance/) .

## 5 Delete the MountPoints Registry Key

 If none of the above solutions have fixed the problem, you can try deleting the MountPoints registry key as a last resort. This key stores data about USB and other removable drives. Deleting the key can sometimes resolve conflicts in drive letter assignments.

1. Deleting the MountPoints key shouldn't cause problems, but it is best to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case. Do this before you continue.
2. Open the Registry Editor by searching for it in Windows Search.
3. Navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer** .  
![delete mountpoints in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-mountpoints.jpg)
4. Look for the**MountPoints2** key in the right-hand panel, right-click on it and select**Delete** .
5. Close the Registry Editor and restart your computer.

 The MountPoint registry key will be regenerated after deleting and restarting. You can then check to see if this fixed the Local Device name is already in use error.

## Fixing Local Device Name Errors on Windows

 The Local device name is already in use error is not uncommon, and it can be frustrating. But by working through the solutions here, you will normally be able to fix it within a few minutes. Just be sure to check the remaining storage on the network server before you start digging deeper.


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
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-se-2022-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone SE (2022) Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-approaches-to-cure-the-ailing-windows-service-control-panel/"><u>7 Key Approaches to Cure the Ailing Windows Service Control Panel</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-zte-axon-40-lite-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your ZTE Axon 40 Lite Phone</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-visual-harmony-with-windows-desktop-wallpapers/"><u>Perfecting Visual Harmony with Windows Desktop Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/one-os-multiple-worlds-windows-across-mobile-tablet-mac-and-desktop-realized/"><u>One OS, Multiple Worlds: Windows Across Mobile, Tablet, Mac & Desktop Realized</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-temporary-path-errors-quick-fix-guide-for-windows-error-1152/"><u>Tackling Temporary Path Errors - Quick Fix Guide for Windows Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-lighting-top-brightness-managers-for-windows-monitors/"><u>Optimal Lighting: Top Brightness Managers for Windows Monitors</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-capture-the-essence-your-free-screen-recording-solution-on-mac-and-pc/"><u>[Updated] In 2024, Capture the Essence - Your FREE Screen Recording Solution on Mac & PC</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-premier-mixers-transforming-your-home-streaming-setup/"><u>In 2024, Premier Mixers Transforming Your Home Streaming Setup</u></a></li>
<li><a href="https://win11.techidaily.com/windows-secure-access-tips-for-stuck-pins/"><u>Windows Secure Access: Tips for Stuck Pins</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launchers-secure-login-failures-on-windows-os/"><u>Overcoming Launcher's Secure Login Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-the-blocked-fixing-windows-access-issues/"><u>Unblocking the Blocked: Fixing Windows Access Issues</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-prevent-vscode-failures-w11/"><u>Essential Steps to Prevent VSCode Failures W11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-windows-build-numbers/"><u>Interpreting Windows Build Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/steer-clear-from-cheap-windows-codes-a-cautionary-tale/"><u>Steer Clear From Cheap Windows Codes: A Cautionary Tale</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-clearing-out-microsoft-edge/"><u>Easy Guide: Clearing Out Microsoft Edge</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-indoor-games-galore-top-9-screen-less-titles-for-android-gamers/"><u>[New] In 2024, Indoor Games Galore  Top 9 Screen-Less Titles for Android Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-windows-11-to-notify-you-when-someone-accesses-your-camera/"><u>How to Force Windows 11 to Notify You When Someone Accesses Your Camera</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-price-estimation-guide-for-music-video-production/"><u>[New] Price Estimation Guide for Music Video Production</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-beyond-vlc-uncovering-hidden-streaming-gems/"><u>[New] 2024 Approved  Beyond VLC  Uncovering Hidden Streaming Gems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-top-6-android-and-ios-apps-for-enhancing-call-conversation-volume/"><u>2024 Approved Top 6 Android & iOS Apps for Enhancing Call Conversation Volume</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paperless-pages-winning-window-based-notepad-substitutes/"><u>Paperless Pages: Winning Window-Based Notepad Substitutes</u></a></li>
<li><a href="https://win11.techidaily.com/mending-usb30-device-failure-in-windows-1011-systems/"><u>Mending USB3.0 Device Failure in Windows 10/11 Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-vivo-y100a-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-editors-playbook-for-drone-imagery/"><u>[Updated] The Editor's Playbook for Drone Imagery</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-potential-7-efficient-practices-for-windows-11-users/"><u>Unleash Peak Potential: 7 Efficient Practices for Windows 11 Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-advanced-frameworks-for-documenting-e-learning-sessions/"><u>[Updated] 2024 Approved  Advanced Frameworks for Documenting E-Learning Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outdated-boot-options-gray/"><u>Overcoming Outdated BOOT Options Gray</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fps-in-csgo-essential-insights/"><u>Mastering FPS in CS:GO - Essential Insights</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-virtual-machine-performance-with-six-windows-tricks/"><u>Jumpstart Your Virtual Machine Performance with Six Windows Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-device-issue-on-windows-os/"><u>Troubleshooting Missing Device Issue on Windows OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-score-the-biggest-bargains-on-mystery-boxes-websites/"><u>[New] Score the Biggest Bargains on Mystery Boxes Websites</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-pathway-restrictions-in-windows/"><u>Overcoming Device Pathway Restrictions in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-expert-video-extractor-and-downloader-enhanced-firefox-support/"><u>[Updated] In 2024, Expert Video Extractor & Downloader  Enhanced FireFox Support</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-the-delayed-folder-upload-issue-onedrive-errors/"><u>Swift Remedies for the Delayed Folder Upload Issue: OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-moving-programs-from-older-win-pcs-to-windows-11/"><u>Essential Steps for Moving Programs From Older Win PCs to Windows 11</u></a></li>
</ul></div>
