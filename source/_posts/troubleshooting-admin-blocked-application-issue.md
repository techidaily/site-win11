---
title: Troubleshooting Admin-Blocked Application Issue
date: 2024-06-25T10:24:22.041Z
updated: 2024-06-26T10:24:22.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Admin-Blocked Application Issue
excerpt: This Article Describes Troubleshooting Admin-Blocked Application Issue
keywords: App Block Fix,Admin Access Denied,Unblock App Error,Admin Portal Trouble,Resolve App Lock,Override Admin Block,Restore App Functionality
thumbnail: https://thmb.techidaily.com/c2bd6ba622504fadfbcb07e0ff1b2943eed89d4f17cad9fcf863c9fe9218bf46.jpg
---

## Troubleshooting Admin-Blocked Application Issue

 User Account Control on Windows prevents unauthorized changes to your computer. This, however, can cause issues with genuine apps and block them from running.

 This app has been blocked by your system administrator error is triggered if your account doesn't have admin rights. Other reasons include issues with User Account Control and Microsoft Defender SmartScreen blocking the app.

 To fix the problem, perform a quick restart of your computer. If the issue persists after the restart, follow these steps to fix the This app has been blocked by your system administrator error on Windows.

## 1\. Unblock the App Executable

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 Windows can automatically block apps downloaded from the internet from running your computer. This is a safety measure intended to protect your system against apps from unknown publishers.

 If you trust the publisher, you can manually unblock the file and run it without the error.

To unblock an app on Windows:

1. Locate and right-click on the app's executable and select**Properties** .
2. In the**Properties** dialog, open the**General** tab.
3. In the**Secure** section, check the**Unblock** option.
4. Click**Apply** and**OK** to save the changes.
5. Launch the app again to see if the error is resolved.

## 2\. Run the App Using the Command Prompt

 You can run and launch apps using Command Prompt on Windows. All you need is a file path followed by the file name. Command Prompt offers a faster way to open apps on Windows; however, you can also use it if you can't open an app from File Explorer.

To open Windows apps using Command Prompt:

1. Right-click on the app shortcut and select**Open File Location** .
2. Next, right-click on the**app.exe** file and select**Properties** .  
![Windows file properties file path location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-file-properties-file-path-location.jpg)
3. In the Properties dialog, open the**Genera** l tab.
4. Copy the file path shown as**Location** .
5. On Windows 11, right-click on the .exe file and select**Copy as File Path** .  
![run program using command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-program-using-command-prompt.jpg)
6. Next, press the**Win** key and type**cmd** .
7. Right-click on**Command Prompt** , and select**Run as administrator.**
8. Next, press**Ctrl + V** to paste the copied file path in Command Prompt. Make sure to add the .exe file name at the end of the file path.
9. Press**Enter** to launch the app.

## 3\. Run the Apps as an Administrator

![run minecraft as administrator windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-minecraft-as-administrator-windows-11.jpg)

 Some Windows apps may need administrator privileges to work correctly. To fix the error, run the app as an administrator. If it works, you can configure the app properties to always run as administrator.

To run an app as an administrator:

1. Right-click on the app icon and select**Run as administrator** .
2. Click**Yes** if prompted by User Account Control.

 Check if the app launches ad administrator without the error. If yes, you can[set the app to always run as administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to fix the issue. That said, do this only if you trust the publisher for security reasons.

## 4\. Repair or Reset the Microsoft Store Apps

 If the error is triggered when opening a Microsoft Store app, try to perform a repair. You can repair Microsoft Store apps from the Settings panel. This should fix temporary glitches with the app and resolve the error.

To repair a Microsoft Store app:

![repair photos app windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/repair-photos-app-windows-11.png)

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Search and locate the app you want to repair.
4. Click the**three-dots menu** next to the app name and select**Advanced Options** .
5. Scroll down and click on the**Repair** button. Wait as Windows repairs the app; you will see a green check mark indicating the repair is complete.

 Once done, launch the app and check if the error is resolved. If you see the error again, try to reset the app.

Reset the Microsoft Store app:

![reset-microsoft-teams-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-microsoft-teams-windows-11.jpg)

 Resetting an app will delete its data, including sign-in details and preferences.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Click the**three-dots menu** near the app name and select**Advanced options** .
4. Scroll down and click the**Reset** button. Click**Reset** again to confirm the action. Similar to Repair, you'll see a checkmark when the reset process is complete.

## 5\. Disable Microsoft Defender SmartScreen

 Microsoft Defender's SmartScreen scans programs and files during the launch for potential threats and can block them from running. You can disable the SmartScreen feature temporarily to determine if your app is blocked by it.

 You can[disable Microsoft SmartScreen Filter on Windows](https://www.makeuseof.com/windows-smartscreen-filter-enable-disable/) using the Windows Security app. Once disabled, relaunch the app and check if the error is resolved.

## 6\. Turn Off Your Antivirus Program

 False positives from Antivirus programs are not uncommon. Whether you are using Microsoft Windows Defender or another antivirus program, turn off the security program temporarily to determine if your antivirus blocking the app.

 You can[temporarily disable Microsoft Defender](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) using the Windows Security app. To turn off third-party antivirus, right-click the app icon in the system tray and select the appropriate options.

 If the error is resolved, add the app to your security program's allowed list. You can also[allowlist files and apps on Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) if you use it as the primary security application.

## 7\. Modify the Windows Registry to Remove Admin Block

 User Account Control settings are another common trigger for the This app has been blocked by your system administrator error. You can modify the User Account Control settings in Registry Editor to remove the admin block and resolve the error.

 Making incorrect modifications to the Windows Registry can cause your system to malfunction. Make sure to[create a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , and a[system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below.

To remove the admin block using Registry Editor:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** , if prompted by User Account Control.
3. In Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies`
4. Select the**System** subkey under**Policies** .
5. In the right pane, locate**EnableLUA** .  
![enable lua modify registry editor windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-windows.jpg)
6. Right-click on the**EnableLUA** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![enable lua modify registry editor value 0 windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-value-0-windows.jpg)
8. Close Registry Editor and restart your computer to apply the changes. After the restart, launch the app to see if the error is resolved.
9. If you are using a school or work computer, your organization may put some restrictions on its use. If you can't find the UAC settings, contact your IT administrator to resolve the issue.

## Unblock the Apps Blocked by Your System Administrator

 Security settings on your Windows computer can often block suspicious apps and trigger the This app has been blocked by your system administrator message. To resolve the issue, check and unblock the app in file properties. Also, turn off the SmartScreen filter and your antivirus solution.

 Reconfiguring your UAC settings in Registry Editor is another way to resolve the problem. If all else fails, the restrictions may have been put in place by guardians or the school or work administration.


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
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-locate-powershell-console/"><u>What to Do When Windows Can't Locate PowerShell Console</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-changing-picture-preview-size/"><u>Windows 11: Changing Picture Preview Size</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-clutter-eliminate-onedrive-symbol-from-explorer/"><u>Confronting Clutter: Eliminate OneDrive Symbol From Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/windows-a-deep-dive-into-data-consumption-patterns/"><u>Windows: A Deep Dive Into Data Consumption Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-a-sleeker-system-auto-delete-files-on-windows/"><u>The Key to a Sleeker System: Auto-Delete Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-effective-windows-storage-visualization/"><u>Unleashing Potential: Effective Windows Storage Visualization</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-windows-experience-adding-contextual-items/"><u>Upgrading Your Windows Experience: Adding Contextual Items</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-effortless-steps-for-switching-user-statuses-on-discord/"><u>[New] 2024 Approved  Effortless Steps for Switching User Statuses on Discord</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-easy-techniques-for-archiving-group-discussions/"><u>[New] Easy Techniques for Archiving Group Discussions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-approaches-to-modify-user-numbers-in-tiktok-for-2024/"><u>Innovative Approaches to Modify User Numbers in TikTok for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-vivo-y36i-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-secure-methods-for-youtube-to-mp4-conversion/"><u>[Updated] 2024 Approved  Secure Methods for Youtube-to-MP4 Conversion</u></a></li>
<li><a href="https://extra-skills.techidaily.com/stepwise-process-enhancing-document-editing-via-googles-speech-to-text-for-2024/"><u>Stepwise Process  Enhancing Document Editing via Google's Speech-to-Text for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-tecno-spark-10-4g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Tecno Spark 10 4G</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-seamless-social-streams-link-instagram-and-facebook/"><u>2024 Approved  Seamless Social Streams  Link Instagram & Facebook</u></a></li>
</ul></div>
