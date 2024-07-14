---
title: Troubleshooting Admin-Blocked Application Issue
date: 2024-07-13T10:32:39.273Z
updated: 2024-07-14T10:32:39.273Z
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

 Check if the app launches ad administrator without the error. If yes, you can [set the app to always run as administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to fix the issue. That said, do this only if you trust the publisher for security reasons.

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

 You can [disable Microsoft SmartScreen Filter on Windows](https://www.makeuseof.com/windows-smartscreen-filter-enable-disable/) using the Windows Security app. Once disabled, relaunch the app and check if the error is resolved.

## 6\. Turn Off Your Antivirus Program

 False positives from Antivirus programs are not uncommon. Whether you are using Microsoft Windows Defender or another antivirus program, turn off the security program temporarily to determine if your antivirus blocking the app.

 You can [temporarily disable Microsoft Defender](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) using the Windows Security app. To turn off third-party antivirus, right-click the app icon in the system tray and select the appropriate options.

 If the error is resolved, add the app to your security program's allowed list. You can also [allowlist files and apps on Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) if you use it as the primary security application.

## 7\. Modify the Windows Registry to Remove Admin Block

 User Account Control settings are another common trigger for the This app has been blocked by your system administrator error. You can modify the User Account Control settings in Registry Editor to remove the admin block and resolve the error.

 Making incorrect modifications to the Windows Registry can cause your system to malfunction. Make sure to [create a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , and a [system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below.

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
<li><a href="https://win11.techidaily.com/from-sealed-boxes-to-digital-realm-unlocking-windows-11-with-a-window-7-key/"><u>From Sealed Boxes to Digital Realm: Unlocking Windows 11 With a Window 7 Key</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-the-blueprint-of-crafting-digital-collaboration-spheres/"><u>2024 Approved  The Blueprint of Crafting Digital Collaboration Spheres</u></a></li>
<li><a href="https://win11.techidaily.com/correction-procedure-for-windows-error-0xca00a009/"><u>Correction Procedure for Windows Error 0xCA00A009</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ignite-your-pc-bypassing-windows-11-lag-and-latency/"><u>Ignite Your PC: Bypassing Windows 11 Lag & Latency</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-jump-into-action-on-tiktok-live-easy-methods-revealed/"><u>2024 Approved  Jump Into Action on TikTok Live  Easy Methods Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-in-use-errors-unique-device-names-on-windows-pcs/"><u>Clearing Up In Use Errors: Unique Device Names on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/historical-code-to-contemporary-computing-windows-7-to-11-activation/"><u>Historical Code to Contemporary Computing: Windows 7 to 11 Activation</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-a-list-of-quick-access-techniques-for-credentials-in-win11/"><u>Break the Code: A List of Quick Access Techniques for Credentials in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-antivirus-conflicts-with-ms-defender/"><u>Navigating Through Antivirus Conflicts with MS Defender</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-file-properties-a-windowayers-manual/"><u>Fine-Tuning File Properties: A Window'ayer's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-battlenet-downloads-for-smooth-gaming/"><u>Turbo Charge Battle.net Downloads for Smooth Gaming</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-a-world-of-talent-with-the-top-10-low-cost-youtube-creators/"><u>[New] Unlocking a World of Talent with the Top 10 Low-Cost YouTube Creators</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-second-display-on-w11/"><u>Troubleshooting Missing Second Display on W11</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-mouse-experience/"><u>Customize Your Windows Mouse Experience</u></a></li>
<li><a href="https://win11.techidaily.com/winxpxo11-how-to-prevent-closed-folders-double-clicked/"><u>WinXP/XO11 - How to Prevent Closed Folders, Double-Clicked</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/in-place-upgrade-mastery-simplify-your-transition-to-windows-11/"><u>In-Place Upgrade Mastery: Simplify Your Transition to Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/ensuring-privacy-on-social-networking-sites-fb/"><u>Ensuring Privacy on Social Networking Sites (FB)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-free-to-download-movie-cast-releases/"><u>[New] In 2024, Free-to-Download Movie Cast Releases</u></a></li>
<li><a href="https://win11.techidaily.com/master-guide-winning-strategies-for-selecting-best-windows-emulators/"><u>Master Guide: Winning Strategies for Selecting Best Windows Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-detailed-settings-app-tour/"><u>Windows 11: A Detailed Settings App Tour</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-repair-access-with-windows-troubleshooting-hotkeys/"><u>Enhancing PC Repair Access with Windows Troubleshooting Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-bypassing-defender-firewall-in-win11/"><u>Mastering the Art of Bypassing Defender Firewall in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-without-mishap-avoiding-errors-in-windows-11/"><u>Navigating Without Mishap: Avoiding Errors in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-chromes-erroneous-virus-protection-alerts/"><u>How to Reset Chrome's Erroneous Virus Protection Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-space-on-windows-11-os/"><u>Customizing Taskbar Space on Windows 11 OS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-spark-go-2023-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Spark Go (2023) online without jailbreak</u></a></li>
<li><a href="https://win11.techidaily.com/grasping-group-policies-in-windows-environments/"><u>Grasping Group Policies in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-on-windows-folders-amidst-issues/"><u>Bypassing Read-Only on Windows Folders Amidst Issues</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-xiaomi-14-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Xiaomi 14</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-non-changeable-energy-modes-in-windows-11/"><u>Navigating Non-Changeable Energy Modes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-connectivity-the-5g-challenge/"><u>Addressing Windows 11 Connectivity: The 5G Challenge</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-vivo-v27e-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Vivo V27e Phones with/without a PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlock-the-secrets-to-lengthy-exposure-with-iphone/"><u>In 2024, Unlock the Secrets to Lengthy Exposure with iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-snipping-tool-in-windows-11/"><u>How to Open the Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/alert-systems-top-7-windows-processes-for-infection-scrutiny/"><u>Alert Systems: Top 7 Windows Processes for Infection Scrutiny</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-xs-drfone-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On Apple iPhone XS | Dr.fone</u></a></li>
</ul></div>
