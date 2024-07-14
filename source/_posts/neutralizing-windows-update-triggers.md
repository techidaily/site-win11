---
title: Neutralizing Windows Update Triggers
date: 2024-07-13T10:02:49.707Z
updated: 2024-07-14T10:02:49.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Neutralizing Windows Update Triggers
excerpt: This Article Describes Neutralizing Windows Update Triggers
keywords: Stop Win Updates,Disable Windows Updates,Preventing OS Updates,Windows Update Fixes,Blocking Win Update Signs,Halting Windows Patch,Avoid Windows Auto-Upgrade
thumbnail: https://thmb.techidaily.com/14df3d85d8466ef631a5707d30d5e14919d53addb84823d2a2bfe4ff558c0940.png
---

## Neutralizing Windows Update Triggers

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-device-issue-on-windows-os/"><u>Troubleshooting Missing Device Issue on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-approaches-to-cure-the-ailing-windows-service-control-panel/"><u>7 Key Approaches to Cure the Ailing Windows Service Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://win11.techidaily.com/no-snip-from-prtscan-how-to-prevent-launch-of-snipping-tool-in-windows-11/"><u>No Snip From PrtScan: How to Prevent Launch of Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/finding-lost-windows-proven-strategies-for-win11-users/"><u>Finding Lost Windows: Proven Strategies for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-syncs-a-guide-to-onedrive-operations-on-windows/"><u>Fixing Failed Syncs: A Guide to OneDrive Operations on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-pick-your-favorite-top-ios-apps-for-facebook-video-loading/"><u>[New] Pick Your Favorite  Top iOS Apps for Facebook Video Loading</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-1011s-share-issue-with-nvidia/"><u>Addressing Windows 10/11'S Share Issue with NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-moving-programs-from-older-win-pcs-to-windows-11/"><u>Essential Steps for Moving Programs From Older Win PCs to Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/swift-signature-bg-cleansing-secrets-revealed/"><u>Swift Signature BG Cleansing Secrets Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-a-cohesive-file-landscape-in-win1011/"><u>Conjuring a Cohesive File Landscape in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-accessing-your-iis-management-center/"><u>Quick Fixes for Accessing Your IIS Management Center</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-0x80041015-problem-from-windows-ms-office/"><u>Eradicating 0X80041015 Problem From Windows MS Office</u></a></li>
<li><a href="https://win11.techidaily.com/unzipping-complex-archives-a-windows-cli-experts-manual/"><u>Unzipping Complex Archives: A Windows CLI Expert's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/examining-the-role-and-relevance-of-wasd-in-windows/"><u>Examining the Role and Relevance of WASD in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-hunt-for-terrifying-acoustic-phenomena/"><u>In 2024, Hunt for Terrifying Acoustic Phenomena</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-windows-build-numbers/"><u>Interpreting Windows Build Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-setback-preserving-saving-functionality-of-nvidia-cp/"><u>Overcoming Setback: Preserving Saving Functionality of Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-regain-basic-windows-settings-after-restart/"><u>Guide to Regain Basic Windows Settings After Restart</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-visual-harmony-with-windows-desktop-wallpapers/"><u>Perfecting Visual Harmony with Windows Desktop Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/w11s-moment-update-a-glimpse-at-the-next-gen-features/"><u>W11's Moment Update: A Glimpse at the Next-Gen Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-pathway-restrictions-in-windows/"><u>Overcoming Device Pathway Restrictions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mending-usb30-device-failure-in-windows-1011-systems/"><u>Mending USB3.0 Device Failure in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-interruptnothandled-error-on-win11/"><u>Eliminating the INTERRUPT_NOT_HANDLED Error on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/one-os-multiple-worlds-windows-across-mobile-tablet-mac-and-desktop-realized/"><u>One OS, Multiple Worlds: Windows Across Mobile, Tablet, Mac & Desktop Realized</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-iphones-panoramic-videos-explained-for-fb-sharing-for-2024/"><u>[New] IPhone's Panoramic Videos Explained for FB Sharing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-system-fixes-through-keyboard-shortcuts-on-windows/"><u>Uncomplicated System Fixes Through Keyboard Shortcuts on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-gems-of-windows-world-windows-11s-stealth-menu-secrets/"><u>Hidden Gems of Window's World: Windows 11’S Stealth Menu Secrets</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-superior-sound-capture-insiders-list-of-the-best-9-microphones-online/"><u>[Updated] Superior Sound Capture  Insider's List of the Best 9 Microphones Online</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-ms-teams-hurdle-error-80080300-in-win11/"><u>Overcoming MS Teams Hurdle Error 80080300 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-clearing-out-microsoft-edge/"><u>Easy Guide: Clearing Out Microsoft Edge</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-the-blocked-fixing-windows-access-issues/"><u>Unblocking the Blocked: Fixing Windows Access Issues</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-discord-text-formatting-how-to-change-text-style-in-discord/"><u>[Updated] In 2024, Discord Text Formatting  How to Change Text Style in Discord?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-maximize-impact-with-professional-grade-fb-cover-videos/"><u>[New] Maximize Impact with Professional-Grade FB Cover Videos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-infinix-note-30-vip-racing-edition-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Infinix Note 30 VIP Racing Edition Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-microsoft-outlook-problems-effectively/"><u>How to Repair Microsoft Outlook Problems Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/windows-secure-access-tips-for-stuck-pins/"><u>Windows Secure Access: Tips for Stuck Pins</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outdated-boot-options-gray/"><u>Overcoming Outdated BOOT Options Gray</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-lighting-top-brightness-managers-for-windows-monitors/"><u>Optimal Lighting: Top Brightness Managers for Windows Monitors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-9-top-notch-free-online-movie-creators/"><u>In 2024, 9 Top-Notch Free Online Movie Creators</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-visual-vibrancy-of-a-frozen-windows-device/"><u>Reviving the Visual Vibrancy of a Frozen Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-virtual-machine-performance-with-six-windows-tricks/"><u>Jumpstart Your Virtual Machine Performance with Six Windows Tricks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-lightning-fast-fileshare-on-windows-os/"><u>[New] 2024 Approved  Lightning-Fast Fileshare on Windows OS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-speeding-up-on-the-go-vimeo-videos-for-2024/"><u>[New] Speeding Up On-the-Go Vimeo Videos for 2024</u></a></li>
</ul></div>
