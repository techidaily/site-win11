---
title: Addressing 'MsResource/AppName Text' Glitch in W11
date: 2024-07-13T09:58:06.610Z
updated: 2024-07-14T09:58:06.610Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'MsResource/AppName Text' Glitch in W11
excerpt: This Article Describes Addressing 'MsResource/AppName Text' Glitch in W11
keywords: W11 Text Fix,App Name Error,Resource Glitch,MsResource Issue,App Name Resolve,W11 Bug Address,Text Processing Flaw
thumbnail: https://thmb.techidaily.com/f68ad44dfce4596bff961c8c73128e503881dbfbd95e5f1787a78426eec3f375.jpg
---

## Addressing 'MsResource/AppName Text' Glitch in W11

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter

![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

## 5\. Repair the Microsoft Store App

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/innovating-with-technology-advanced-gopro-4k-editing-techniques-for-2024/"><u>Innovating with Technology  Advanced GoPro 4K Editing Techniques for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/securing-your-social-snapshot-instagram-edition-for-2024/"><u>Securing Your Social Snapshot  Instagram Edition for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-nubia-z50-ultra-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Nubia Z50 Ultra Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-or-enable-smartfilter-on-modern-windows-os/"><u>Turn Off or Enable SmartFilter on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-overheating-prevention-on-windows-pcs/"><u>Adjusting Overheating Prevention on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-completely-get-rid-of-wsl-on-windows-11-pcs/"><u>How To Completely Get Rid of WSL on Windows 11 PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unwanted-comments-made-easy-an-overview/"><u>Unwanted Comments Made Easy  An Overview</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-work-and-play-in-windows-11-schedules/"><u>Balancing Work and Play in Windows 11 Schedules</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-desk-customization-displaying-this-pc-image/"><u>Aesthetic Desk Customization: Displaying 'This PC' Image</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-v27-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo V27 to iPod | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/express-screen-snag-aural-elements/"><u>Express Screen Snag  Aural Elements</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-remove-functionality-on-windows-11-os/"><u>Fixing Inaccessible Remove Functionality on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-windows-11-zoom-failure-1132/"><u>Unblocking Windows 11 Zoom Failure #1132</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-stranded-status-from-xbox-console-experience-on-pc/"><u>Eradicate ‘Stranded’ Status From Xbox Console Experience on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-top-free-must-have-for-win11/"><u>Unleash Potential: Top Free Must-Have for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/executing-chatgpt-on-windows-systems/"><u>Executing ChatGPT on Windows Systems</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-discovering-and-demystifying-tiktoks-pfp-symbol/"><u>2024 Approved  Discovering and Demystifying TikTok's PFP Symbol</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-tutorial-to-bypass-your-tecno-spark-20-pro-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Tecno Spark 20 Pro Face Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-native-pdf-displayer/"><u>Adjusting Windows' Native PDF Displayer</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-winuac-new-techniques-for-administrators/"><u>Enhancing WinUAC: New Techniques for Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-common-onedrive-issues-on-pc/"><u>Conquering Common OneDrive Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-settings-app-overview/"><u>Windows 11 Settings App Overview</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-defenders-error-code-0x80004004/"><u>Unveiling Fixes for Defender’s Error Code: 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-windows-memory-management-via-pagefilesys-files/"><u>Clarifying Windows' Memory Management via Pagefile.sys Files</u></a></li>
<li><a href="https://win11.techidaily.com/underrated-windows-11-themes-worth-appreciating/"><u>Underrated Windows 11 Themes Worth Appreciating</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-the-windows-ecosystem-a-dive-into-memory-shields/"><u>Ftdibus.sys in the Windows Ecosystem: A Dive Into Memory Shields</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/precision-techniques-for-high-quality-console-recordings-on-pcs/"><u>Precision Techniques for High-Quality Console Recordings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/yourphone-in-windows-98-should-you-exercranize-it/"><u>YourPhone in Windows 9/8: Should You Exercranize It?</u></a></li>
<li><a href="https://win11.techidaily.com/winupgrade-hurdles-overcoming-error-code-xc004f050/"><u>WinUpgrade Hurdles: Overcoming Error Code Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/discuss-the-limits-of-cultural-relativism-when-might-it-be-challenging-or-problematic-to-apply/"><u>Discuss the Limits of Cultural Relativism: When Might It Be Challenging or Problematic to Apply?</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-tray-ui-show-number-keys-scroll-lock-windows-11/"><u>Customizing Tray UI: Show Number Keys, Scroll Lock Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-voice-harmonizing-tools-to-enhance-live-performances-online-for-2024/"><u>Updated Top Voice Harmonizing Tools to Enhance Live Performances Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/coding-a-deity-command-into-system-menu/"><u>Coding a Deity Command Into System Menu</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-mastering-the-most-effective-7-tiktok-techniques-for-fame/"><u>[New] 2024 Approved  Mastering the Most Effective 7 TikTok Techniques for Fame</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-quick-access-tools-into-the-win11-taskbar-easily/"><u>Incorporating Quick Access Tools Into the Win11 Taskbar Easily</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/top-picks-of-firefox-tools-to-streamline-your-facebook-video-experience-2023/"><u>Top Picks of Firefox Tools to Streamline Your Facebook Video Experience, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-previewable-files-issue-in-outlook-for-personal-computers/"><u>Fixing Non-Previewable Files Issue in Outlook for Personal Computers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/savory-sensations-top-youtube-food-influencers-for-2024/"><u>Savory Sensations  Top YouTube Food Influencers for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-oppo-a58-4g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Oppo A58 4G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-random-shutdown-phenomenon/"><u>Fix Windows 11'S Random Shutdown Phenomenon</u></a></li>
</ul></div>
