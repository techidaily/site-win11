---
title: Resurrecting the Core of Windows 11'S Problem-Solving Tools
date: 2024-07-13T10:37:41.846Z
updated: 2024-07-14T10:37:41.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resurrecting the Core of Windows 11'S Problem-Solving Tools
excerpt: This Article Describes Resurrecting the Core of Windows 11'S Problem-Solving Tools
keywords: Win11 Debugging Tools,OS Diagnostics Solutions,PC Repair Essentials,System Troubleshooting Guide,Windows 11 Fixes List,Error Resolution in Win11,Performance Optimization Tools
thumbnail: https://thmb.techidaily.com/276d97c36ad2008d7cfbd98152b79e1acd5c5f1c2ed18f1585db86304b623852.jpg
---

## Resurrecting the Core of Windows 11'S Problem-Solving Tools

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

## 5\. Rename the Catroot2 and SoftwareDistribution Folders

 If you’re having issues with the Windows Update troubleshooter, try applying this potential solution. Users confirm renaming the catroot2 and SoftwareDistribution folders can fix the Windows Update troubleshooter not working. Those are folders that store data for Windows updates. Rename the catroot2 and SoftwareDistribution folders as follows:

1. Launch the Windows Command Prompt app with administrative rights.
2. Input these four separate commands, pressing **Enter** after each, to stop update services:  
`net stop cryptsvc  

net stop wuauserv  

net stop bits  

net stop msiserver`
3. Next, input this command and hit **Return** to rename the SoftwareDistribution folder:  
`ren c:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren command for the SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-softwaredistribution-folder.jpg)
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-network-shield-controls-on-windows/"><u>Mastering Network Shield Controls on Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-taming-audio-chaos-advanced-tips-and-tricks-for-reducing-room-noise-in-microphones/"><u>2024 Approved Taming Audio Chaos Advanced Tips and Tricks for Reducing Room Noise in Microphones</u></a></li>
<li><a href="https://games-able.techidaily.com/next-gen-superior-hdi-display-mouse-lineup/"><u>Next-Gen, Superior HDI Display Mouse Lineup</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-computers-small-smart-and-windows/"><u>Innovative Computers: Small, Smart, and Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-your-pcs-games-on-steam-deck-with-ease/"><u>Unlocking Your PC's Games on Steam Deck with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-cannot-open-file-problems-in-win1110/"><u>Mastering the Art of Fixing 'Cannot Open File' Problems in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-windows-model-chronology/"><u>Pinpointing Windows Model Chronology</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weather-software-for-w10w11-pcs/"><u>Prime Weather Software for W10/W11 PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-trim-3gp-videos-a-step-by-step-guide/"><u>2024 Approved Trim 3GP Videos A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-typing-efficiency-with-w11-bespo-points/"><u>Elevate Typing Efficiency with W11, Bespo Points</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-missing-battery-time-estimate-in-windows-11/"><u>How to Fix a Missing Battery Time Estimate in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cease-alerts-for-unrequested-system-recommendations/"><u>Cease Alerts for Unrequested System Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-two-networks-a-window-guide-to-dual-connectivity/"><u>Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-editorial-powerhouses-free-for-web-enthusiasts/"><u>[Updated] Editorial Powerhouses Free for Web Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-sneak-peeks-into-instagrams-latest-hacks/"><u>[Updated] In 2024, Sneak Peeks Into Instagram's Latest Hacks</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-iphone-images-problem-in-windows-environments/"><u>How to Rectify iPhone Images Problem in Windows Environments</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-motorola-g24-power-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Motorola G24 Power phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-opengl-error-3-from-nvidia/"><u>Correcting OpenGL Error 3 From NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/managing-disk-space-wisely-recognizing-huge-file-and-folder-use/"><u>Managing Disk Space Wisely: Recognizing Huge File & Folder Use</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-enhancing-your-fb-video-experience-with-1080p-quality/"><u>[Updated] 2024 Approved  Enhancing Your FB Video Experience with 1080P Quality</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-install-failed-messages-on-discord/"><u>Navigating Through Install Failed Messages on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-null-associated-app-error-on-windows-systems/"><u>Fixing Null Associated App Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://win11.techidaily.com/max-1-antivirus-for-windows-optimize-system-performance/"><u>Max 1 Antivirus for WIndows: Optimize System Performance</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-see-what-is-taking-up-too-much-disk-space-on-your-windows-pc/"><u>How to See What Is Taking Up Too Much Disk Space on Your Windows PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-xiaomi-mix-fold-3-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Xiaomi Mix Fold 3? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-windows-speech-to-text-app-using-whisper-and-ahk/"><u>Creating a Personalized Windows Speech-to-Text App Using Whisper & AHK</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-the-2024-cloud-cost-landscape/"><u>[New] Navigating the 2024 Cloud Cost Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-inability-to-link-with-nvidia-experience-on-pcs/"><u>Overcoming the Inability to Link with NVIDIA Experience on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-your-windows-stylus-device/"><u>Mastering the Art of Fixing Your Windows Stylus Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-flow-optimize-your-windows-11-hdd/"><u>Mastering Data Flow: Optimize Your Windows 11 HDD</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xbox-play-network-errors-on-windows-1011-systems/"><u>Fixing Xbox Play Network Errors on Windows 10/11 Systems</u></a></li>
</ul></div>
