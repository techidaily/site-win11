---
title: Sidestep Common VSCode Crash Causes on WinW11
date: 2024-06-25T11:35:27.286Z
updated: 2024-06-26T11:35:27.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sidestep Common VSCode Crash Causes on WinW11
excerpt: This Article Describes Sidestep Common VSCode Crash Causes on WinW11
keywords: WinW11 VSCode Troubleshoot,Fix VSCode W11 Crash,Avoid VSCode Errors Windows,Win11 VSCode Stability,Prevent Code Crash W11,Solve VSCode on Windows,VSCode No Freeze in W11
thumbnail: https://thmb.techidaily.com/fd283428cd4cb2c0907e2d15b8c7aa3306b361f3c11c9903f383663675146f0a.jpg
---

## Sidestep Common VSCode Crash Causes on WinW11

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
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

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a[clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

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

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even[temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

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

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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

 Microsoft even offers a[web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

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
<li><a href="https://win11.techidaily.com/solutions-to-silent-audio-during-powerpoint-presentations/"><u>Solutions to Silent Audio During PowerPoint Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-counteract-the-black-screen-on-steam/"><u>Strategies to Counteract the Black Screen on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-networking-with-python-servers-on-windows-os/"><u>Advanced Networking with Python Servers on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-importance-of-consistent-windows-data-saves/"><u>The Importance of Consistent Windows Data Saves</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-workspace-switching-themes-on-win11/"><u>Personalize Your Workspace: Switching Themes on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-max-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS Max to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-lava-yuva-3-pro-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Lava Yuva 3 Pro by Phone Number | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-tiktok-trends-in-reading-top-picks-with-a-viral-chop/"><u>[New] In 2024, TikTok Trends in Reading  Top Picks with a Viral Chop</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-inspiring-originality-in-tiktok-pfps-to-boost-profile-traction/"><u>2024 Approved  Inspiring Originality in TikTok PFPs to Boost Profile Traction</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-selecting-the-ideal-imagery-for-remote-meetings-for-2024/"><u>[New] Selecting the Ideal Imagery for Remote Meetings for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-hevc-h-265-content-on-samsung-galaxy-s23-ultra-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Can’t view HEVC H.265 content on Samsung Galaxy S23 Ultra</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-virtual-giggle-creator-for-2024/"><u>[New] Virtual Giggle Creator for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-mastering-the-art-of-measuring-igtv-video-quality/"><u>2024 Approved  Mastering the Art of Measuring IGTV Video Quality</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-snaptweet-transporter-swiftly-grab-social-media-vids/"><u>[New] In 2024, SnapTweet Transporter  Swiftly Grab Social Media Vids</u></a></li>
</ul></div>
