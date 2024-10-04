---
title: Effortless Exit Strategies for Windows' 'S Mode'
date: 2024-10-02T18:40:23.286Z
updated: 2024-10-04T01:42:36.056Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Exit Strategies for Windows' 'S Mode'
excerpt: This Article Describes Effortless Exit Strategies for Windows' 'S Mode'
keywords: Windows S Mode Ease,Quick S Mode Exit,Simple S Mode Out,Easily Leave S Mode,S Mode Exit Strategy,Swift S Mode Switch,Depart S Mode Simplicity
thumbnail: https://thmb.techidaily.com/dee28e41650480f8be267c870e6c35efe9b36fe181500be81f958d9b44354162.jpg
---

## Effortless Exit Strategies for Windows' 'S Mode'

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144288/7443" target="_top" id="2144288">
  <img src="//a.impactradius-go.com/display-ad/7443-2144288" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144288/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-expert-tips-for-creating-engaging-screencasts/"><u>[Updated] 2024 Approved Expert Tips for Creating Engaging Screencasts</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-bypass-tradition-innovative-techniques-to-boost-your-tiktok-photos/"><u>[Updated] In 2024, Bypass Tradition Innovative Techniques to Boost Your TikTok Photos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-soloists-journey-personal-growth-and-success-on-youtube-for-musicians-for-2024/"><u>[Updated] The Soloist's Journey Personal Growth and Success on YouTube for Musicians for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-honor-90-pro-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Honor 90 Pro to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-13-pro-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 13 Pro Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-cooldown-chart-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-fixing-frozen-windows-terminals-quickly/"><u>Regaining Access: Fixing Frozen Windows Terminals Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-hidden-taskbar-explorer-of-windows-11/"><u>Tapping Into Hidden Taskbar Explorer of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-app-execution-variants-and-usage/"><u>Understanding App Execution Variants & Usage</u></a></li>
</ul></div>

