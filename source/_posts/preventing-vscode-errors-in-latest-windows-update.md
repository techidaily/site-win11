---
title: Preventing VSCode Errors in Latest Windows Update
date: 2024-07-13T10:55:28.142Z
updated: 2024-07-14T10:55:28.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing VSCode Errors in Latest Windows Update
excerpt: This Article Describes Preventing VSCode Errors in Latest Windows Update
keywords: Fix Vscode Errors Win,Stop Code Editor Crashes,Avoid Windows Update Issues,Prevent Update-Related Bugs,Maintain VSCode Stability,Windows Update VSCode Fix,Avoiding Errors in Latest Updates
thumbnail: https://thmb.techidaily.com/c614df743851cde902b9dc7b624e356646f565efb6b83602d7f5ffd347873428.jpg
---

## Preventing VSCode Errors in Latest Windows Update

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the [Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
2. Locate the Visual Studio Code process in the list of active processes.
3. Right-click on it and click on the**End Task** option from the context menu. It will close Visual Studio Code app and all its associated processes.  
![Terminate Visual Studio Code and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/terminate-visual-studio-code-and-restart.jpg)
4. Close the Task Manager window and open the Start menu.
5. Type Visual Studio Code and run the app with administrator privileges. Check if it encounters a crash now.

## 2\. Reboot your System

 Restarting the system is the oldest trick in the book. It might not sound effective but resolves most of the system issues. Restarting a system helps in closing all the active processes and services, clearing the system memory, and relaunching them. Due to this, any services or apps that aren't working will also restart afresh.

**Right-click** on the Start button and select the**Restart** option from the Power user menu. After the system restarts, run the Visual Studio Code with administrator permissions and check if it crashes.

## 3\. Disable Hardware Acceleration

 Hardware acceleration can cause problems on the low-spec system running the Visual Studio app. There isn’t an option for this feature in the app settings. So, you must modify the argv.json file to disable it. Here's how:

1. Launch Visual Studio Code and click on the**Settings** icon in the bottom left corner.
2. Select the**Command Palette** option from the settings menu and click on the**Preferences: Configure Runtime Arguments** option.
3. Now, enter the following command in the argv.json file:**"disable-hardware-acceleration": true**  
![Disable Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-hardware-acceleration.jpg)
4. Press**Ctrl+ S** to save the changes to the file.
5. Restart the app and check if it crashes now.

## 4\. Perform a Clean Boot

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a [clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

 If Visual Studio Code works fine after a clean boot, retry the clean boot while enabling some third-party service. Repeat this process until you find the problematic service or app.

## 5\. Disable Visual Studio Code Extensions

 Visual Studio Code needs extensions to extend language and debugger support for various programming languages. If you use extensions, you must find and remove the troublesome ones. Here's how to do it:

1. Launch Visual Studio Code and press**Ctrl+ Shift + X** to open the extensions settings.
2. Click on the**Installed** option to display all the extensions installed in the Visual Studio Code app.
3. Right-click on any extension and select the**Disable** option from the context menu.  
![Disable Visual Studio Code Extensions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-visual-studio-code-extensions.jpg)
4. Repeat this process for all extensions to disable them.
5. Now restart the Visual Studio Code app and run it for some time without any extensions. If it doesn't crash, an extension is probably the reason behind the crash.
6. To identify the extension, revisit the Extension settings in the app and right-click on a disabled extension. Select the**Enable** option.
7. Check if Visual Studio Code encounters a crash when this extension is active. Repeat the process to find the culprit extension and remove it from the app.

## 6\. Exclude Visual Studio Code in Windows Defender

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

## 7\. Update Visual Studio Code

 If you are using a very old version of Visual Studio Code and are facing abrupt crashes, then you must update the app. A new app update brings security improvements and bug fixes which could exist in the old version of the app. Here’s how to update the app:

1. Open Visual Studio Code and click on the**Settings** icon.
2. Select the**Check for updates** option from the context menu.  
![Update the Visual Studio Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/update-the-visual-studio-code.jpg)
3. If there is an update available, download and install it and restart your computer.
4. Launch the app again and use it for some time while keeping an eye out for crashes.

## 8\. Roll Back the Last Windows Update

 Windows updates can break system features or not sit well with third-party apps. If you encounter the app crash issue after a recent update,[manually uninstall the most recent Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) on your computer. It will revert all the new changes made to your system.

## 9\. Reinstall Visual Studio Code

 If the app installation is severely corrupt and unfixable, then a simple app reset won’t be effective. Instead, you must completely remove Visual Studio Code from your system and then reinstall it.

 Repeat the following steps to reinstall Visual Studio Code using Winget:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to launch the command prompt with administrator rights.
3. Accept the UAC prompt and click on the**Yes** button.
4. Type the following command and press enter key:**Winget list**
5. Copy the ID of the Visual Studio Code app and paste it after the following command:**winget uninstall \[App ID\]**  
winget uninstall Microsoft.VisualStudioCode
6. Wait for the uninstallation to complete. Restart your system.  
![Reinstall Visual Studio Code 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-1.jpg)
7. Launch the Command Prompt with admin privileges again.
8. Then type the following command and press the enter key:**winget install Microsoft.VisualStudioCode**  
![Reinstall Visual Studio Code 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-2.jpg)
9. It will take a while to download and install the app on your system. You won’t need to interact with the installer window or grant any permissions.
10. Run Visual Studio Code now and check if the app encounters any crashes now.

## 10\. Use the Web Version

 Microsoft even offers a [web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

## Visual Studio Code Won’t Crash Anymore on Windows 11

 Microsoft’s popular IDE is the go-to tool of programmers. If its crashes abruptly, the projects can get delayed by quite a bit. Start with basic troubleshooting and then disable hardware acceleration on your system. After that, disable extensions and perform a clean boot. Add an exclusion for the app in the antivirus program. Lastly, if nothing works, reinstall the Visual Studio Code app on your system.


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
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/storage-space-used-daily-extended-video-size-for-2024/"><u>Storage Space Used  Daily Extended Video Size for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-early-edge-tab-launches-on-windows-11/"><u>Prevent Early Edge Tab Launches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-whatsapp-room-assembly-guide/"><u>[New] WhatsApp Room Assembly Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-voice-alteration-devices-a-guide-to-introductions-assessments-and-substitutes/"><u>2024 Approved Voice Alteration Devices A Guide to Introductions, Assessments, and Substitutes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-nokia-c22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-conquering-low-light-shots-on-iphone/"><u>[New] Conquering Low-Light Shots on iPhone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-poco-m6-pro-4g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Poco M6 Pro 4G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/proper-methods-to-turn-windows-key-onoff/"><u>Proper Methods to Turn Windows Key On/Off</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitters-visuals-saving-and-downloading-on-smartphones-for-2024/"><u>Twitter's Visuals  Saving and Downloading on Smartphones for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-dormant-screen-saver-configurations-in-windows/"><u>Revitalizing Dormant Screen Saver Configurations in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfect-your-unboxing-game-8-tips-from-experts/"><u>Perfect Your Unboxing Game  8 Tips From Experts</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stepwise-guide-to-smoothing-out-audio-dynamics/"><u>In 2024, Stepwise Guide to Smoothing Out Audio Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-natural-windows-file-sorting-settings/"><u>Restoring Natural Windows File Sorting Settings</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-unveiling-dynamic-volume-control-mastering-audio-ducking-techniques/"><u>New Unveiling Dynamic Volume Control Mastering Audio Ducking Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unrivaled-tag-analyzers-your-key-to-hashtag-success-fbtwitterinsta-for-2024/"><u>[Updated] Unrivaled Tag Analyzers  Your Key to Hashtag Success (FB/Twitter/Insta) for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-105-classic-phone-without-password-by-drfone-android/"><u>How To Unlock Nokia 105 Classic Phone Without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-discover-the-leading-free-game-recording-tools-for-2024/"><u>[New] Discover the Leading Free Game Recording Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-device-interaction-with-windows-and-galaxy/"><u>Revolutionizing Device Interaction with Windows & Galaxy</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-breaking-barriers-next-level-strategies-for-fb-video-success/"><u>[Updated] In 2024, Breaking Barriers  Next-Level Strategies for FB Video Success</u></a></li>
</ul></div>
