---
title: Fixing Unchecked Cpu Usage by WMI Worker
date: 2024-07-13T09:59:26.528Z
updated: 2024-07-14T09:59:26.528Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unchecked Cpu Usage by WMI Worker
excerpt: This Article Describes Fixing Unchecked Cpu Usage by WMI Worker
keywords: High CPU Usage Fix,WMI Worker Optimization,Reduce System Overload,Manage Task Prioritization,Control WMI Consumption,Decrease Cpu Load,Enhance System Efficiency
thumbnail: https://thmb.techidaily.com/5c8db21fb7e97eed2eddd025f3f66d3a9e58c7bc74fde8e765814f3eec97fd83.jpg
---

## Fixing Unchecked Cpu Usage by WMI Worker

 If your computer is heating up and the CPU fan is running loudly, it could mean there is an issue with the Windows Modules Installer Worker process. This process is part of the operating system and handles Windows updates. In some cases, it leads to slow speeds and even system crashes due to high CPU usage.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

## 1\. Give It Some Time

 If your computer's "Windows Modules Installer Worker" process is using a lot of CPU power, it means that Windows is busy installing updates or doing system maintenance in the background. These tasks may take a few minutes to complete, and the CPU usage should go back to normal afterward.

 So if you're not in a hurry, give it some time and let it finishes before trying anything else.

## 2\. Restart Your Computer

 If there is no ongoing update process or system maintenance, and CPU usage is still abnormally high, restart your computer. This will kill all running programs, including "Windows Modules Installer Worker" and any other process that might be causing the issue.

 To restart your computer, open the **Start** menu or hit the **Windows** key. Select the **Power** icon and click **Restart** from the menu. Once your computer restarts, see if CPU usage is back to normal.

## 3\. Run the Windows Update Troubleshooter

 If restarting doesn't work, run the Windows Update troubleshooter. This tool scans for any issues with Windows Update and automatically fixes them, which might solve the "Windows Modules Installer Worker" high CPU usage issue.

 To run the troubleshooter, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **Control Panel** in the dialog box and hit Enter. This will open the Control Panel.
3. Change the Control Panel view to **Large icons** or **Small icons**.
4. Locate and click on the **Troubleshooting** option.  
![Troubleshooting in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooting-in-control-panel.jpg)
5. On the right side, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
6. Click **Run** next to **Windows Update**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

## 4\. Restart the Windows Update Service

 Another solution is to restart Windows Update. This will reset the Windows Update settings and possibly fix any issues causing the high CPU usage. Here's how to do it:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **services.msc** in the dialog box and hit Enter. This will open the Services console.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Restart** from the menu.  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-update-service.jpg)

 Once the service has been restarted, check if the "Windows Modules Installer Worker" process is still using a lot of CPU power.

## 5\. Set Windows Update to Manual Mode

 The Windows Modules Installer Worker process sometimes remains active even when there are no updates to install. This usually happens when the Windows Update service is set to Automatic.

 To fix this issue, you can change the Windows Update service to manual mode. This will prevent Windows from running the process all the time and reduce CPU usage.

 To change Windows Update into manual mode, do the following:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Scroll down and right-click on **Windows Update**.
3. From the context menu, select the **Properties** option. You can also double-click on the service to open its Properties window
4. On the **General** tab, set the **Startup type** to **Manual** and click **OK**.  
![Set Windows Update to Manual](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/set-windows-update-to-manual.jpg)
5. Next, locate **Windows Modules Installer** in the list of services and repeat the same steps.

 Once done, restart your computer and see if CPU usage has reduced. If not, try the next solution.

## 6\. Disable Windows Update

 If high CPU usage persists, you can disable Windows Update completely. This is not a recommended long-term solution since updates are crucial for security and performance. But if needed, you can disable it for now and check CPU usage.

 To disable Windows Update, do the following.

1. Click on Start and type **Services** in the search box.
2. Select Services from the results list. This will open the Services window.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Stop** from the context menu.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
5. Upon stopping the Windows Update service, double-click on it to open its Properties window.
6. On the **General** tab, click **Startup type** and select **Disabled** from the dropdown.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
7. Click **Apply** \> **OK** to save your changes.

 After performing the above steps, close the Services window and restart your computer. Check if the "Windows Modules Installer Worker" process is still using CPU resources. Don't forget to enable Windows Update once you're done troubleshooting.

## 7\. Clear the SoftwareDistribution Folder

 Another thing you can do is delete the Software Distribution folder. This folder holds temporary files used during Windows updates. However, if there are any corrupt or outdated files in this folder, it might cause high CPU usage.

 In that case, delete the folder and let Windows recreate it. To clear the SoftwareDistribution folder, follow these steps:

1. [Run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In the Command Prompt window, type the following commands and hit Enter after each one:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Upon executing the above commands, open Windows File Explorer and browse to the following location:  
C:\Windows\SoftwareDistribution\
4. In the SoftwareDistribution folder, use **Ctrl + A** to select all contents then delete them.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
5. If a pop-up menu asks for permission, click **Continue**.
6. After deleting the Software Distribution folder, you will need to restart the services you stopped previously. For this, launch the elevated command prompt again and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now close the Command Prompt window and restart your computer. Now check if the Windows Modules Installer Worker process still consumes CPU power.

## 8\. Try Some Generic Windows Fixes

 Aside from the solutions above, there are some generic fixes you can try to reduce high CPU usage. This includes [disabling unnecessary startup programs](https://www.makeuseof.com/windows-11-disable-startup-programs/) and [repairing corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/). If you have downloaded any third-party programs, uninstall them and check if that helps.

 In addition, check if you have installed any updates recently. Corrupted or incompatible updates can cause high CPU usage issues. If the problem persists after performing these steps, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/).

## Optimizing High CPU Usage on Windows

 If Windows Modules Installer Worker is using too much CPU power, you now have solutions to try. Although this process usually utilizes computer resources while installing updates and shouldn't create issues, if you observe that it is using excessive CPU power for an extended period, you can try deactivating services, deleting files from the SoftwareDistribution folder, and implementing common fixes.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://activate-lock.techidaily.com/latest-guide-on-ipad-23-and-apple-iphone-13-pro-max-icloud-activation-lock-bypass-by-drfone-ios/"><u>Latest Guide on iPad 2/3 and Apple iPhone 13 Pro Max iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-optimize-accessibility-top-free-speech-conversion-tools-for-macos/"><u>2024 Approved  Optimize Accessibility  Top Free Speech Conversion Tools for MacOS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-overestimated-cpu-usage-in-windows-performance-tool/"><u>Addressing Overestimated CPU Usage in Windows Performance Tool</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-a-comprehensive-review-the-premier-audio-changers-for-smartphones-for-2024/"><u>New A Comprehensive Review The Premier Audio Changers for Smartphones for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-6-windows-usage-analysis-programs/"><u>Explore the Finest 6 Windows Usage Analysis Programs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-temporary-path-errors-quick-fix-guide-for-windows-error-1152/"><u>Tackling Temporary Path Errors - Quick Fix Guide for Windows Error 1152</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-top-20-tiktok-captions-for-captivating-viewers/"><u>[Updated] In 2024, Top 20 TikTok Captions for Captivating Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launchers-secure-login-failures-on-windows-os/"><u>Overcoming Launcher's Secure Login Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-workstation-access-the-hidden-side-of-rdp-in-win-11/"><u>Zero-Entry Workstation Access: The Hidden Side of RDP in Win 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-premier-collection-of-popular-mobile-alert-melodies/"><u>Updated Premier Collection of Popular Mobile Alert Melodies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unlock-your-potential-one-thousand-new-likesmonth/"><u>[Updated] Unlock Your Potential  One Thousand New Likes/Month</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/virtual-worlds-on-screen-new-era-films/"><u>Virtual Worlds on Screen  New Era Films</u></a></li>
<li><a href="https://win11.techidaily.com/dynamic-walls-for-windows-11-setting-lively-desktop-backdrops/"><u>Dynamic Walls for Windows 11: Setting Lively Desktop Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-potential-7-efficient-practices-for-windows-11-users/"><u>Unleash Peak Potential: 7 Efficient Practices for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-puzzle-of-non-opening-apps-in-w11/"><u>Unlocking the Puzzle of Non-Opening Apps in W11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-on-the-fly-quick-tips-for-cropping-photos-online/"><u>2024 Approved  On-the-Fly  Quick Tips for Cropping Photos Online</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-key-to-professional-filming-without-spending-free-lessons-from-the-best-in-green-screen-artistry/"><u>[Updated] The Key to Professional Filming Without Spending  Free Lessons From the Best in Green Screen Artistry</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-soundquality-assessment/"><u>[New] In 2024, SoundQuality Assessment</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-illuminating-the-sensor-rich-world-of-iphone-x-photos/"><u>In 2024, Illuminating the Sensor-Rich World of iPhone X Photos</u></a></li>
<li><a href="https://win11.techidaily.com/check-it-out-quick-fixes-for-your-webcam-and-mic-test/"><u>Check It Out: Quick Fixes for Your Webcam & Mic Test</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-transforming-lyrics-into-visual-masterpieces-using-adobe-ae/"><u>New Transforming Lyrics Into Visual Masterpieces Using Adobe AE</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-verification-loading-unsigned-drivers-in-windows-2000xp/"><u>Bypassing Verification: Loading Unsigned Drivers in Windows 2000/XP</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-direct-links-sharing-twitch-content-with-friends-on-fb/"><u>[Updated] Direct Links  Sharing Twitch Content with Friends on FB</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-windowsmac-recording-skype-chats-and-calls/"><u>[Updated] In 2024, Windows/Mac  Recording Skype Chats & Calls</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-deactivated-speech-recognition-microsofts-windows-11-guide/"><u>Addressing Deactivated Speech Recognition: Microsoft's Windows 11 Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-how-to-record-films-seamlessly-across-tech-devices/"><u>In 2024, How to Record Films Seamlessly Across Tech Devices</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-the-delayed-folder-upload-issue-onedrive-errors/"><u>Swift Remedies for the Delayed Folder Upload Issue: OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-visibility-to-system-startups-on-win-os/"><u>Restoring Visibility to System Startups on Win OS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/tap-into-tagging-techniques-for-6kplus-youtube-vistas-for-2024/"><u>Tap Into #Tagging Techniques for $6K+ YouTube Vistas for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-the-art-of-screen-enhancement-in-teams-for-2024/"><u>Mastering the Art of Screen Enhancement in Teams for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-exclusive-no-watermark-downloads-from-tiktok/"><u>[New] 2024 Approved  Exclusive  No Watermark Downloads From TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-prevent-vscode-failures-w11/"><u>Essential Steps to Prevent VSCode Failures W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unverified-session-error-by-steams-vac/"><u>Fixing Unverified Session Error by Steam's VAC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-windows-11-to-notify-you-when-someone-accesses-your-camera/"><u>How to Force Windows 11 to Notify You When Someone Accesses Your Camera</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-for-battery-life-extension-on-notebooks/"><u>Effective Techniques for Battery Life Extension on Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-quick-and-accurate-screenshot-of-uac-prompts/"><u>Techniques for Quick and Accurate Screenshot of UAC Prompts</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-complete-tutorial-on-using-autotune-with-audacity-users/"><u>2024 Approved The Complete Tutorial on Using Autotune with Audacity Users</u></a></li>
<li><a href="https://facebook.techidaily.com/next-update-brings-no-surprises-no-oculus-quest-3/"><u>Next Update Brings No Surprises, No Oculus Quest 3</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-yuva-2-pro-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Yuva 2 Pro.</u></a></li>
<li><a href="https://facebook.techidaily.com/mastering-the-matrix-of-multiple-social-media-connections-on-xbox/"><u>Mastering the Matrix of Multiple Social Media Connections on Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nvidias-opengl-failure-no-3-in-windows-11/"><u>Eliminating NVIDIA's OpenGL Failure No. 3 in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-best-multiplayer-game-communities/"><u>[New] Best Multiplayer Game Communities</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-zero-to-hero-integrating-roles-in-discord-for-2024/"><u>From Zero to Hero  Integrating Roles in Discord for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-no-cost-high-quality-srt-editors/"><u>2024 Approved  The Ultimate Guide to No-Cost, High-Quality Srt Editors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fps-in-csgo-essential-insights/"><u>Mastering FPS in CS:GO - Essential Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/streamline-your-gameplay-win10-screen-record-tech-for-2024/"><u>Streamline Your Gameplay  Win10 Screen Record Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-editing-with-these-win11-videoscripts/"><u>Streamline Editing with These Win11 Videoscripts</u></a></li>
<li><a href="https://win11.techidaily.com/four-practical-alternatives-to-bitlocker-in-winoss/"><u>Four Practical Alternatives to BitLocker in WinOSs</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-abrupt-device-removal-errors-dxgi/"><u>Fixing Abrupt Device Removal Errors (DXGI)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-how-to-elevate-your-tiktok-footage-with-enhanced-heads-a-guide-3-steps/"><u>[New] How To Elevate Your TikTok Footage with Enhanced Heads  A Guide (3 Steps)</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-driver-verification-on-windows-enforcement-off-unsigned-loaded/"><u>Bypass Driver Verification on Windows: Enforcement Off, Unsigned Loaded</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-discords-inadequate-search-mechanism/"><u>Reviving Windows Discord's Inadequate Search Mechanism</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-from-free-to-paid-subscriber-count-surpasses-500/"><u>[New] From Free to Paid  Subscriber Count Surpasses 500</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-secrets-5-entertaining-hacks/"><u>Command Prompt Secrets: 5 Entertaining Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-feature-flashback-the-surviving-anniversary-of-7-elements/"><u>Windows 11 Feature Flashback: The Surviving Anniversary of 7 Elements</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-tactics-to-accelerate-vimeo-video-viewership/"><u>[Updated] 2024 Approved  Tactics to Accelerate Vimeo Video Viewership</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/steer-clear-from-cheap-windows-codes-a-cautionary-tale/"><u>Steer Clear From Cheap Windows Codes: A Cautionary Tale</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/step-by-step-guide-to-record-google-meet-on-smartphones-for-2024/"><u>Step-by-Step Guide to Record Google Meet on Smartphones for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-from-script-to-screen-a-production-perspective-on-voice-over-artistry/"><u>[New] 2024 Approved  From Script to Screen  A Production Perspective on Voice Over Artistry</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/top-rated-free-mov-video-splitters-for-easy-editing-for-2024/"><u>Top-Rated Free MOV Video Splitters for Easy Editing for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-revolutionize-your-animation-workflow-7-must-try-drawing-software/"><u>Updated 2024 Approved Revolutionize Your Animation Workflow 7 Must-Try Drawing Software</u></a></li>
</ul></div>
