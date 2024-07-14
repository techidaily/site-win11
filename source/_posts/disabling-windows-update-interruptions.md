---
title: Disabling Windows Update Interruptions
date: 2024-07-13T09:46:08.509Z
updated: 2024-07-14T09:46:08.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows Update Interruptions
excerpt: This Article Describes Disabling Windows Update Interruptions
keywords: Stop Update Pauses,End Windows Updates,Disable UWP Stoppage,Cease OS Update Halt,Quiet Update Restarts,Silence System Checks,Suspend Update Interruptions
thumbnail: https://thmb.techidaily.com/1a06e5fd0d5cec8ff438d2d94c98e453ecdfe96f957771d6cb6ed139269884f8.jpg
---

## Disabling Windows Update Interruptions

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
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-xiaomi-13-ultra-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Xiaomi 13 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-old-school-gaming-with-retroarcs-tools/"><u>A Step-by-Step Guide to Old-School Gaming with RetroArc's Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-asserting-ownership-on-social-platforms-instagrams-watermarking-secrets/"><u>[New] 2024 Approved  Asserting Ownership on Social Platforms  Instagram's Watermarking Secrets</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-essential-video-to-audio-converters-top-picks-for-professional-and-amateur-use/"><u>Updated In 2024, Essential Video to Audio Converters Top Picks for Professional and Amateur Use</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719358882925-solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-adding-secure-websites-in-windows-11/"><u>A Step-by-Step Guide to Adding Secure Websites in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-quietude-craft-isolating-vocal-frequencies-in-audacity/"><u>In 2024, Quietude Craft  Isolating Vocal Frequencies in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-deleting-files-without-a-click-in-windows/"><u>A Step-by-Step Guide to Deleting Files Without a Click in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/1719347815778-resolve-dormant-shift-key-issue-on-windows/"><u>Resolve Dormant Shift Key Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-linux-vms-within-windows-via-hyper-v/"><u>A Step-by-Step Guide to Linux VMs Within Windows via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/1719369512280-ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-open-the-file-or-folder-properties-in-windows/"><u>6 Ways to Open the File or Folder Properties in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlined-approach-transforming-your-audio-impression-in-pubg/"><u>In 2024, Streamlined Approach  Transforming Your Audio Impression in PUBG</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-authoritative-sourcebook-no-cost-limitless-pictures/"><u>2024 Approved  Authoritative Sourcebook  No Cost, Limitless Pictures</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-6-best-audio-mixers-for-enhancing-your-streaming/"><u>2024 Approved 6 Best Audio Mixers For Enhancing Your Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/1719350686194-unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-fix-the-windows-terminal-not-opening/"><u>6 Ways to Fix the Windows Terminal Not Opening</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-step-by-step-volume-regulation-in-vlc-ensuring-consistent-sound-quality-for-2024/"><u>New Step-by-Step Volume Regulation in VLC Ensuring Consistent Sound Quality for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/high-quality-webcam-capture-made-easy-review/"><u>High-Quality WebCam Capture Made Easy Review</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-reset-the-windows-11-settings-app/"><u>3 Ways to Reset the Windows 11 Settings App</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-keygen-malware-and-its-destructive-path-in-windows/"><u>A Deep Dive Into Keygen Malware & Its Destructive Path in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-boost-iphone-cinematic-experience-essential-film-gear/"><u>2024 Approved  Boost iPhone Cinematic Experience  Essential Film Gear</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-cant-change-resolution-solved/"><u>Windows 11 Can't Change Resolution [SOLVED]</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-compreehsive-review-of-the-ultra-hd-actioncamera/"><u>[Updated] A Compreehsive Review of the Ultra-HD ActionCamera</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-understanding-group-policies-windows-via-3-views/"><u>A Detailed Guide to Understanding Group Policies (Windows) via 3 Views</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/1719361199591-navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-early-warnings-to-consider-windows-restart/"><u>5 Early Warnings to Consider Windows Restart</u></a></li>
<li><a href="https://win11.techidaily.com/1719382051492-exclusive-deal-for-tech-lovers-612-windows-11-lifetime-thanks-to-keys-fans/"><u>Exclusive Deal for Tech Lovers: $6.12 Windows 11 Lifetime, Thanks to Keys Fans</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-most-engaging-tiktok-stars-for-your-drive/"><u>[New] The Most Engaging TikTok Stars for Your Drive</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-palette-perfection-a-guide-to-grading-filmmaking/"><u>2024 Approved  Palette Perfection  A Guide to Grading Filmmaking</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-how-to-report-someone-on-discord/"><u>[Updated] How to Report Someone on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/1719320743244-windows-users-run-a-cost-free-locally-operated-gpt-model/"><u>Windows Users: Run a Cost-Free, Locally Operated GPT Model</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-is-virtualdub-still-the-best-choice-a-review-and-comparison-of-top-alternatives/"><u>New In 2024, Is Virtualdub Still the Best Choice? A Review and Comparison of Top Alternatives</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-best-of-the-best-free-avi-video-rotation-software/"><u>New Best of the Best Free AVI Video Rotation Software</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-group-policies-with-the-gpresult-command/"><u>A Deeper Dive Into Group Policies with the GPResult Command</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-6-best-movie-editor-for-windows/"><u>In 2024, 6 Best Movie Editor for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-mistakes-you-should-avoid-making-as-a-beginner-to-windows-11/"><u>8 Mistakes You Should Avoid Making as a Beginner to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719336940768-cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-asus-rog-phone-8-pro-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719380925919-keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-sound-shift-secrets-revealed-uncover-the-best-voice-recorder-changer-apps-for-2024/"><u>[Updated] Sound Shift Secrets Revealed  Uncover the Best Voice Recorder Changer Apps for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-samsung-galaxy-a14-4g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Samsung Galaxy A14 4G Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-stopping-blued-in-windows-10/"><u>A Step-by-Step Guide to Stopping Blued in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-windows-11-the-essentials-of-its-registry-data/"><u>A Window Into Windows 11: The Essentials of Its Registry Data</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-what-is-ai-api-wondershare-virbo-glossary/"><u>In 2024, What Is AI API? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-honor-80-pro-straight-screen-edition-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Honor 80 Pro Straight Screen Edition to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-steps-overcome-windows-update-setbacks/"><u>7 Essential Steps: Overcome Windows Update Setbacks</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-layer-of-simplicity-in-windows-photos-app-deletion/"><u>A New Layer of Simplicity in Windows Photos App Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-workflow-fine-tuning-mouse-clicks/"><u>Accelerate Your Workflow: Fine-Tuning Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/7-fixes-to-try-when-waterfox-is-not-loading-webpages-on-windows/"><u>7 Fixes to Try When Waterfox Is Not Loading Webpages on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
</ul></div>
