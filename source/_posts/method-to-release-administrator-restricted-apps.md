---
title: Method to Release Administrator-Restricted Apps
date: 2024-06-25T11:45:23.465Z
updated: 2024-06-26T11:45:23.465Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method to Release Administrator-Restricted Apps
excerpt: This Article Describes Method to Release Administrator-Restricted Apps
keywords: Admin App Release Guide,Unrestricting App Access,App Permissions Removal,Disable Restrictions (App),Freeing Restricted Apps,Revoking App Limits,Easing Admin-Limited Apps
thumbnail: https://thmb.techidaily.com/b97d0ebad54511b61b45570cc2aa70ceb4b57e4382ef455cbbee6f6a39f5f377.jpg
---

## Method to Release Administrator-Restricted Apps

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
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/which-window-suits-you-best-home-versus-pro-in-windows-11/"><u>Which Window Suits You Best? Home Versus Pro in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-ui-instability-issues/"><u>Overcoming Windows UI Instability Issues</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-counter-after-incorrect-password-entry-windows-11-edition/"><u>Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-system-fixes-through-keyboard-shortcuts-on-windows/"><u>Uncomplicated System Fixes Through Keyboard Shortcuts on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-iphone-se-2022-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with iPhone SE (2022) Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-cost-effective-strategies-to-combine-videos-with-text/"><u>2024 Approved  Cost-Effective Strategies to Combine Videos with Text</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/explore-the-premier-video-grabbing-tools-on-windows-10/"><u>Explore the Premier Video Grabbing Tools on Windows 10</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/maximizing-tiktok-income-8-must-try-strategies-for-2024/"><u>Maximizing TikTok Income  8 Must-Try Strategies for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-mastering-video-to-gif-conversion-with-tiktok-apps/"><u>[New] In 2024, Mastering Video-to-GIF Conversion with TikTok Apps</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-perfecting-volume-control-strategies-for-seamless-audio-transitions-for-2024/"><u>New Perfecting Volume Control Strategies for Seamless Audio Transitions for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-download-lumafusion-for-mac-top-alternatives-included-for-2024/"><u>New Download Lumafusion for Mac Top Alternatives Included for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-flavor-forge-30-epicurean-titles-that-resonate-for-2024/"><u>[New] Flavor Forge  30 Epicurean Titles That Resonate for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/pinnacle-partnership-portrayal-picking-an-ideal-mcn-for-2024/"><u>Pinnacle Partnership Portrayal  Picking an Ideal MCN for 2024</u></a></li>
</ul></div>
