---
title: Tactics to Transition From Stuck in Windows 10/11 S Mode
date: 2024-07-13T10:53:53.144Z
updated: 2024-07-14T10:53:53.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics to Transition From Stuck in Windows 10/11 S Mode
excerpt: This Article Describes Tactics to Transition From Stuck in Windows 10/11 S Mode
keywords: Escape WS Mode,Switch WS Modes,Exit WS Limitation,Unlock WS Version,Free WS Mode Trapped Users,Bypass Windows S Mode,Overcome WS Lockdown
thumbnail: https://thmb.techidaily.com/1155b908ebc8fe078487b3227b97ba044636fc4713be9d07ea00e7f8a9937936.jpeg
---

## Tactics to Transition From Stuck in Windows 10/11 S Mode

### Key Takeaways

* If you cannot switch out of Windows S Mode, it may be due to issues with Microsoft servers.
* Restart the wauserv service in the Task Manager to fix any glitches with the Microsoft Update service, which handles update-related tasks on your PC.
* Try signing out of the Microsoft Store and signing back in before attempting to exit Windows S Mode again.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

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
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-the-best-peter-mckinnon-luts-for-perfect-video-editing/"><u>Updated In 2024, The Best Peter McKinnon LUTs for Perfect Video Editing</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/best-green-screen-apps-for-mac-a-comprehensive-guide-for-2024/"><u>Best Green Screen Apps for Mac A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-cutting-edge-the-6-leading-video-apps-for-macos-big-sur/"><u>2024 Approved  Cutting Edge  The 6 Leading Video Apps for macOS Big Sur</u></a></li>
<li><a href="https://win11.techidaily.com/restarting-routine-efficiently-installing-windows-11/"><u>Restarting Routine: Efficiently Installing Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-adventures-at-a-tap-androids-elite-15-game-choices/"><u>[Updated] In 2024, Adventures at a Tap  Android's Elite 15 Game Choices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-your-ultimate-selfie-validation-handbook/"><u>In 2024, Your Ultimate Selfie Validation Handbook</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unwanted-windows-start-up-in-bios-landing/"><u>Overcoming Unwanted Windows Start-Up in BIOS Landing</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-unique-characteristics-of-ai-computers/"><u>Delving Into Unique Characteristics of AI Computers</u></a></li>
<li><a href="https://win11.techidaily.com/crack-the-ms-pc-manager-install-issue-on-windows-xp/"><u>Crack the MS PC Manager Install Issue on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-common-anydesk-errors-on-windows/"><u>Mastering the Art of Resolving Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-by-wmi-service/"><u>Addressing High Cpu Usage by WMI Service</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-x9a-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Honor X9a | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/master-quick-video-cuts-on-windows-11-photos/"><u>Master Quick Video Cuts on Windows 11 Photos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transformative-youtube-title-genesis-tools/"><u>In 2024, Transformative YouTube Title Genesis Tools</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-overlays-for-windows-11/"><u>Adjusting Photo Overlays for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-is-now-microsofts-new-ai-enhanced-taskbar-for-windows-11-users/"><u>The Future Is Now: Microsoft’s New AI-Enhanced Taskbar for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-guide-to-full-battery-indicators-in-win-oses/"><u>Advanced Guide to Full Battery Indicators in Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/debating-choco-and-wslm-top-pick-for-windows-software/"><u>Debating Choco and WSLM: Top Pick for Windows Software</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-top-30-trending-tiktok-anime-inspirations/"><u>[New] In 2024, Top 30 Trending TikTok Anime Inspirations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-a-volume-on-windows-without-erasing-personal-data/"><u>How to Extend a Volume on Windows Without Erasing Personal Data</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-your-outlook-calendar-on-windows/"><u>How to Customize Your Outlook Calendar on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-mastering-the-art-of-audio-separation-a-step-by-step-premiere-pro-approach/"><u>Updated 2024 Approved Mastering the Art of Audio Separation A Step-by-Step Premiere Pro Approach</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-trouble-with-updates-code-0x80246007/"><u>Tackling the Trouble with Update's Code 0X80246007</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-infinix-note-30-vip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-approaches-to-compress-media-files-effectively-without-loss-of-quality/"><u>New Approaches to Compress Media Files Effectively Without Loss of Quality</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-windows-configuration-pathways/"><u>Decoding the Windows Configuration Pathways</u></a></li>
<li><a href="https://win11.techidaily.com/essential-reasons-why-pcs-outshine-macs-9/"><u>Essential Reasons Why PCs Outshine Macs (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-file-format-alterations-on-your-pc/"><u>Streamline File Format Alterations on Your PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-the-moment-best-drone-footage-editing-tools-ranked-for-2024/"><u>[Updated] Mastering the Moment  Best Drone Footage Editing Tools Ranked for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-chuckles-churner-visual-composer/"><u>2024 Approved  Chuckles Churner  Visual Composer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-onedrive-files-offline-on-a-windows-pc/"><u>How to Access OneDrive Files Offline on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-error-code-0x80070570-repair-corrupted-filesdirectories/"><u>Reversing Error Code 0X80070570: Repair Corrupted Files/Directories</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-reviving-your-reliable-tiktok-videos/"><u>In 2024, Reviving Your Reliable TikTok Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-time-lapse-video-editing-top-picks-for-free-and-paid-tools/"><u>New 2024 Approved Time-Lapse Video Editing Top Picks for Free and Paid Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-video-lessons-to-vivid-engaging-gifs-no-download-needed/"><u>In 2024, From Video Lessons to Vivid, Engaging GIFs – No Download Needed</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-y77t-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Y77t Phone Forgot Password</u></a></li>
<li><a href="https://win11.techidaily.com/decrypting-wacatacbml-trojan-a-step-by-step-windows-cleanup/"><u>Decrypting Wacatac.B!ml Trojan: A Step-by-Step Windows Cleanup</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumbled-glitches-win-1111-store-correction-guide/"><u>Bypassing 'Server Stumbled' Glitches: Win 11/11 Store Correction Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-capturing-mac-screen-images-top-5-techniques/"><u>[New] In 2024, Capturing Mac Screen Images  Top 5 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-display-panel-configurations/"><u>Rearranging Display Panel Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-notification-interface-in-win-11/"><u>Tailoring Your Notification Interface in Win 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-14-pro-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For Apple iPhone 14 Pro?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-top-5-best-3d-intro-makers-for-youtube/"><u>[Updated] In 2024, Top 5 Best 3D Intro Makers for YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-detailed-insights-for-optimal-screenrec-techniques/"><u>2024 Approved  Detailed Insights for Optimal ScreenRec Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/risks-and-precautions-deleting-windows-bt-folder/"><u>Risks & Precautions: Deleting Windows ~BT Folder</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-plant-and-play-best-friends-games-in-the-agricultural-world/"><u>[New] Plant & Play  Best Friends Games in the Agricultural World</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pro-3-in-perspective-the-latest-from-ion-air-reviewed/"><u>[Updated] Pro 3 in Perspective  The Latest From ION Air Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-x887a0006-dxgi-error-in-windows-11/"><u>Quick Fixes for X887A0006: DXGI Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-uncover-hidden-system-startups/"><u>Tips to Uncover Hidden System Startups</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-folder-navigation-in-win-11-movecopy-command-addition/"><u>Optimizing Folder Navigation in Win 11 - Move/Copy Command Addition</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-error-0xfffffff-with-ease/"><u>Solving Windows' Error 0xFFFFFFF with Ease</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-speedy-steps-for-assembling-image-collections-on-mac/"><u>In 2024, Speedy Steps for Assembling Image Collections on Mac</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-0x800713f-error-on-the-windows-mail-service/"><u>How to Repair 0X800713f Error on the Windows Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-0x0000004e-on-windows-11-systems/"><u>Conquering Error 0X0000004E on Windows 11 Systems</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-linking-your-apple-earphones-to-your-personal-computer-for-2024/"><u>New Linking Your Apple Earphones to Your Personal Computer for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-guide-to-promoting-music-videos-on-youtube-for-2024/"><u>Updated Guide to Promoting Music Videos on YouTube for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-dusk-to-dawn-strategies-for-exceptional-night-portraits-for-2024/"><u>[New] Dusk to Dawn  Strategies for Exceptional Night Portraits for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/androids-screen-capture-4-easy-techniques/"><u>Android's Screen Capture  4 Easy Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-saving-hurdles-with-steps-to-fix-pubg/"><u>Overcoming Saving Hurdles with Steps to Fix PUBG</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-understanding-and-turning-off-system-lockdown/"><u>Windows 11: Understanding & Turning Off System Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-adjustment-overcoming-overscan/"><u>Mastering Windows Display Adjustment: Overcoming Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/silence-non-pertinent-windows-advisory-messages/"><u>Silence Non-Pertinent Windows Advisory Messages</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-how-to-use-morphvox-voice-changer-for-online-games-for-2024/"><u>Updated How to Use Morphvox Voice Changer for Online Games for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ultimate-yt-shorts-companion-for-2024/"><u>Your Ultimate YT Shorts Companion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-onedrive-and-microsoft-id-for-pc-users/"><u>Bridging the Gap: OneDrive & Microsoft ID for PC Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-tecno-camon-20-pro-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Tecno Camon 20 Pro 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/most-popular-image-stickering-apps-iosandroid-edition-for-2024/"><u>Most Popular Image Stickering Apps – iOS/Android Edition for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/convert-any-instagram-video-in-minutes-best-free-tools-windowsmac-for-2024/"><u>Convert Any Instagram Video in Minutes  Best Free Tools (Windows/Mac) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unable-to-open-error-in-geforce-experience-windows/"><u>Resolving Unable to Open Error in GeForce Experience Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-tech-appbrowser-rule/"><u>Understanding Windows Tech: App/Browser Rule</u></a></li>
</ul></div>
