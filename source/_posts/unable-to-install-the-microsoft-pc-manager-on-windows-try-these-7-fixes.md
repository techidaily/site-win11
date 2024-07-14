---
title: Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes
date: 2024-07-13T10:24:17.746Z
updated: 2024-07-14T10:24:17.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes
excerpt: This Article Describes Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes
keywords: Install PcManager Troubleshooting,Fix PC Manager Errors,Resolve Installer Issues,Uninstall & Reinstall PcManager,Update Windows for PcManager,Check Compatibility Windows,Validate System Requirements
thumbnail: https://thmb.techidaily.com/e92d1325fd1f2f901796fdd1123502e68b5122756c762090fd4b289d5054368b.jpg
---

## Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes

 Microsoft PC Manager is a maintenance app that lets you optimize your system performance. It offers superfast malware removal, a one-click speed boost, and a full computer security check. At the time of writing, the app is in open beta. Therefore, it's very common to face issues with it.

 One of the more common issues is that the app fails to install on a Windows computer. As such, if Microsoft PC Manager fails to install on your computer, here are some fixes you can try.

## 1\. Restart Your Computer

 This is a common troubleshooting method, but it's essential for a reason. The reason that Microsoft PC Manager won't install on your system could be due to a temporary bug. Before you dive into the more advanced troubleshooting fixes, consider restarting y [our computer](https://www.makeuseof.com/windows-restart-methods/) (see [how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) to put it back on a clean slate.

 If you still can't install the application after a system restart, try the next solution on the list.

## 2\. Temporarily Disable Your Antivirus

 Most antivirus programs come with a security feature that stops installing malicious applications onto the computer. Unfortunately, they can sometimes block trusted applications like the Microsoft PC Manager. If this is the case with you as well, consider disabling the antivirus program temporarily as a solution.

 If you're using the Windows Security app as the default security program on your computer, here's how to disable it:

1. Open the Settings menu by pressing the**Win + I** hotkeys.
2. Select**Privacy & security** from the left panel.
3. In the Security section, select the**Windows Security** option.
4. Click the**Open Windows Security** button.
5. In the Windows Security app, click the**Virus & threat protection** option in the left panel.
6. Click**Manage settings** under Virus & threat protection settings.
7. Disable the toggle next**Real-time protection.**  
![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/real-time-protection-option.jpg)

 If you're using a third-party antivirus program, you can disable it by right-clicking on its icon in the system tray and choosing the "Disable" option from the context menu. You can also go through the antivirus support pages to learn more about how to disable it.

 After disabling the security program, give a quick restart to your computer and check if the problem continues.

## 3\. Use the Program Troubleshooter

 Windows 10 and 11 offer different troubleshooting options that you can use to detect and fix common issues. They don't always eliminate the problem, but they're worth a try when you are unable to install Microsoft PC Manager on your computer.

 In Windows 10, you can access the program troubleshooter by following the below steps:

1. Open Settings, and then select**Update & Security** .
2. Choose the**Troubleshoot** option. Then, select**Additional troubleshooters.**
3. In the Additional troubleshooters window, highlight the**Program Compatibility Troubleshooter** option and click the**Run the troubleshooter** button.

 The troubleshooter window will appear and scan your computer for issues.

 If you've Windows 11, open the Settings menu, and navigate to**System** \>**Troubleshoot** \>**Other troubleshooters** . Click the**Run** button next to Program Compatibility Troubleshooter.

![Program Compatibility Troubleshooter in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatiblity-Troubleshooter.jpg)

 If running the built-in troubleshooter wasn't helpful, download and run the Program Install and Uninstall troubleshooter from [Windows Support](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d) .

## 4 . Clear the Temp Folder

![Delete content of the Temp folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Temp-folder.jpg)

 Programs and apps installed on your store temporary files in the Temp folder. But for various reasons, the Temp folder can get corrupted and cause the issue at hand.

 The solution, in this case, is to clear the Temp folder. Don't worry; deleting the Temp folder is not going to have any adverse effect on your computer's data.

To delete the Temp folder, follow the below instructions:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. In the Run dialog box, type**Temp** and click**OK.** It'll open the Temp folder.
3. Select everything inside the Temp folder by pressing the**Ctrl + A** hotkeys.
4. Press the**Shift + Delete** hotkeys to clear the Temp folder's content permanently.

## 5 . Download Any Available Windows Updates

 Windows regularly releases updates to add new features and fix bugs and glitches. And from what it looks like, Microsoft PC Manager can fail to install on your computer due to a temporary glitch.

 To download any available Windows update, follow the below instructions:

1. Open the Settings menu and select**Windows Update** from the left panel.
2. Click the**Check for updates** option.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option.jpg)

 Windows will now look for and download any available updates. Once the update is installed, restart your computer and check for the issue.

## 6\. Fix Any Corrupted Files on Your Computer

 Another reason behind this issue is corruption within the system files. Fortunately, you can detect and fix these files by running an SFC scan. However, before we run the SFC scan, it is best to do a preliminary scan to ensure that the SFC tool is working properly.

 The Deployment Image Servicing and Management tool (DISM) is an integrated Windows utility that offers a wide range of functionalities. In this case, the DISM Restorehealth command makes sure that our next fix will work properly. Work through the below steps:

1. Open the Start menu, type**Command** **Prompt** in the search bar, and select the**Run** **as administrator** option. It'll open Command Prompt with admin rights.
2. In the elevated Command Prompt window, type**DISM /online /cleanup-image /restorehealth** and press**Enter** .
3. Wait until the command is executed. Depending on your computer's health, the process can take up to 15 minutes. Sometimes the process will stick, but wait for it to complete.
4. After the process is complete, type**sfc /scannow** and press**Enter** .

## 7\. Reset Your Computer

![Reset PC button in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Reset-PC-.jpg)

 If you're still unable to install the Microsoft PC Manager, you can use the Windows Reset function. This will reinstall Windows, but it will keep all your personal files intact. Here's how to do it:

1. Navigate to Settings > System > Recovery.
2. Select the**Reset PC** button.

Next, follow the on-screen to complete the reset process.

## Optimize Your System With Microsoft PC Manager

 Microsoft PC Manager is the new way to optimize your system performance. The application is still in the beta phase; thus, it's common for it to run into issues now and then. If the Microsoft PC Manager fails to install on your computer, you now know what's causing the problem and how to fix it.

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
<li><a href="https://win11.techidaily.com/outsmart-windows-delete-temp-files-without-fuss/"><u>Outsmart Windows: Delete Temp Files Without Fuss</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-the-best-open-source-screen-recorders/"><u>[Updated] In 2024, The Best Open-Source Screen Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-fixes-for-stuck-game-resolutions-in-windows/"><u>Insightful Fixes for Stuck Game Resolutions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-non-loading-drivers-functional-on-windows-11/"><u>How to Make Non-Loading Drivers Functional on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/nine-keys-to-release-verification-holds-during-windows-update/"><u>Nine Keys to Release Verification Holds During Windows Update</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-optimal-free-screen-capture-suites-reviewed/"><u>[New] Optimal Free Screen Capture Suites Reviewed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-decoding-propeller-selection-for-optimal-fpv-drone-control/"><u>[New] 2024 Approved  Decoding Propeller Selection for Optimal FPV Drone Control</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hottest-online-hubs-for-metallic-3d-type-graphics-for-2024/"><u>Hottest Online Hubs for Metallic 3D Type Graphics for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-samsung-galaxy-m54-5g-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://win11.techidaily.com/hosting-multiple-oses-linux-vm-inside-hyper-v-on-a-windows-machine/"><u>Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine</u></a></li>
<li><a href="https://article-files.techidaily.com/new-prime-time-camera-selection-apexs-top-18-4k-camcorders-for-2024/"><u>[New] Prime-Time Camera Selection  Apex's Top 18 4K Camcorders for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigating-the-world-of-srt-with-ease-for-2024/"><u>Navigating the World of SRT with Ease for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-disappearances-in-system-navigator/"><u>Eradicating Disappearances in System Navigator</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-update-schedules-setting-active-periods-windows-11/"><u>Mastering Update Schedules: Setting Active Periods Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-voice-typing-failure-in-windows-11-error-code-0x80049dd3/"><u>Fixing Voice Typing Failure in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-commanding-the-crowd-on-igtv-5-tips-to-gain-traction/"><u>[Updated] 2024 Approved  Commanding the Crowd on IGTV  5 Tips to Gain Traction</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-monitor-settings-in-latest-os-version/"><u>Fine-Tune Monitor Settings in Latest OS Version</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-analyzing-channels-monetization-status-at-a-glance/"><u>[New] 2024 Approved  Analyzing Channels  Monetization Status at a Glance</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-break-through-boundaries-15plus-best-free-video-starters/"><u>[Updated] 2024 Approved  Break Through Boundaries  15+ Best Free Video Starters</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-5-ways-change-your-home-address-in-googleapple-map-on-apple-iphone-12ipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Ways Change Your Home Address in Google/Apple Map on Apple iPhone 12/iPad | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-tailored-titling-for-stellar-online-video-content/"><u>[New] Tailored Titling for Stellar Online Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-craft-impressive-images-with-photoshops-radial-distortion-features/"><u>[New] Craft Impressive Images with Photoshop's Radial Distortion Features</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-onedrive-error-def5-woes/"><u>Navigating Through Windows 11'S Onedrive Error DEF5 Woes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-11-best-free-youtube-name-generators-you-should-try/"><u>[Updated] In 2024, 11 Best Free YouTube Name Generators You Should Try</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win-rpc-failures-five-must-try-fixes/"><u>Navigating Win RPC Failures: Five Must-Try Fixes</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-enhancing-visibility-the-power-of-strategic-facebook-giveaways-for-2024/"><u>[New] Enhancing Visibility  The Power of Strategic Facebook Giveaways for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-alternatives-how-to-access-imessage-on-windows/"><u>Exploring Alternatives: How to Access iMessage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-windows-11-logins-restoration/"><u>Mastering Quick Windows 11 Logins Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-windows-11-efficiency-with-these-5-reliability-checks/"><u>Maximize Your Windows 11 Efficiency with These 5 Reliability Checks</u></a></li>
<li><a href="https://win11.techidaily.com/opera-stuck-swift-solutions-for-a-smooth-windows-patch/"><u>Opera Stuck? Swift Solutions for a Smooth Windows Patch</u></a></li>
<li><a href="https://win11.techidaily.com/non-light-no-problem-master-five-cures-for-backlit-keyboard-failure/"><u>Non-Light, No Problem: Master Five Cures for Backlit Keyboard Failure</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/cultivate-connections-top-10-agrigames-for-gathering-pals/"><u>Cultivate Connections  Top 10 AgriGames for Gathering Pals</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-iphone-8-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From iPhone 8 Online</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-silence-is-golden-a-step-by-step-guide-to-noise-reduction-in-fcpx/"><u>Updated Silence Is Golden A Step-by-Step Guide to Noise Reduction in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/make-ms-word-defaultly-use-reading-pane-for-email-attachments-no-editing/"><u>Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing</u></a></li>
</ul></div>
