---
title: Preventing VSCode Errors in Latest Windows Update
date: 2024-06-25T11:42:02.473Z
updated: 2024-06-26T11:42:02.473Z
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
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-remedies-to-address-instantaneous-failure-when-adding-a-folder-in-the-windows-onedrive-environment/"><u>Efficient Remedies to Address Instantaneous Failure when Adding a Folder in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://win11.techidaily.com/mending-disconnected-google-drive-windows-filesystem/"><u>Mending Disconnected Google Drive Windows Filesystem</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-fixes-for-windows-11-taskbar-loss/"><u>Guiding Fixes for Windows 11 Taskbar Loss</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-mouse-experience/"><u>Customize Your Windows Mouse Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-assistance-best-free-tools-for-a-win11-revamp/"><u>Unmatched Assistance: Best Free Tools for a Win11 Revamp</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-from-apple-iphone-15-by-drfone-ios/"><u>How To Create an Apple Developer Account From Apple iPhone 15</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-become-the-brand-you-want-with-our-exclusive-set-of-free-graphics/"><u>2024 Approved  Become the Brand You Want With Our Exclusive Set of FREE Graphics</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-magic5-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-shorts-revenue-sharing-explained-how-much-will-i-make/"><u>[Updated] YouTube Shorts Revenue Sharing Explained  How Much Will I Make?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/uploading-expansive-content-on-youtube-like-a-pro-for-2024/"><u>Uploading Expansive Content on YouTube Like a Pro for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-honor-90-pro-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Honor 90 Pro</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-trilltones-techniques-how-to-cut-and-download-tamil-songs/"><u>[Updated] TrillTones Techniques  How to Cut and Download Tamil Songs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-11-key-steps-for-perfect-color-grading-in-photography/"><u>[New] 11 Key Steps for Perfect Color Grading in Photography</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-xiaomi-redmi-note-12r-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Xiaomi Redmi Note 12R Phone When You Forget the Password</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigate-to-new-horizinas-top-win11-gaming-delights/"><u>[New] Navigate to New Horizinas  Top Win11 Gaming Delights</u></a></li>
</ul></div>
