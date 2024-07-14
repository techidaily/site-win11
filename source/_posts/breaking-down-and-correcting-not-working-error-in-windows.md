---
title: Breaking Down and Correcting 'Not Working' Error in Windows
date: 2024-07-13T10:55:03.347Z
updated: 2024-07-14T10:55:03.347Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down and Correcting 'Not Working' Error in Windows
excerpt: This Article Describes Breaking Down and Correcting 'Not Working' Error in Windows
keywords: Fixing Win Errors,Windows Troubleshooting,Resolve Operating System Fails,Stop Non-Functional Windows,Correct Computer Crashes,Solving PC Errors,Tackling System Failures
thumbnail: https://thmb.techidaily.com/1df433206ff11dec7faaaf54cae7b4a5f98f51a6cf19d2906c605406cb94fb11.jpg
---

## Breaking Down and Correcting 'Not Working' Error in Windows

 While the Microsoft Store offers a great selection of apps for Windows systems, you may sometimes encounter installation errors. One such error is “this app will not work on your device” which usually occurs when installing apps from the Store app. This error message appears with a yellow circle around an exclamation mark, even if the app is compatible.

 There could be various reasons for this issue depending on the app, such as a corrupted cache file or system problems. Read this guide to learn more about this error and how to fix it.

## 1\. Restart Your Computer

 Restarting your PC is the simplest solution to many Windows issues, including this one. It refreshes the system and resets the Microsoft Store service. So, if you are experiencing the “This app will not work on your device” error, restart your computer first and see if it works.

 To restart your device, open the Start menu. Then select the Power icon and click **Restart**. You can also use the keyboard shortcut **Ctrl + Alt + Del** to open the same window. After restarting, try installing the app again and see if it works.

## 2\. Clear the Microsoft Store Cache

 If restarting your device does not help, the next step is to clear the Microsoft Store cache. This process removes any temporary files that might cause this issue. Clearing the cache removes unnecessary files and speeds up the browsing experience. Here’s how to clear the Microsoft Store cache.

1. Press **Win + R** on your keyboard to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **WSReset.exe** in the dialog box and press Enter.  
![Clear Microsoft Store Cache File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-microsoft-store-cache-file.jpg)

 A command prompt appears on the screen confirming that the Windows Store cache is cleared. Once you've completed these steps, check if it solves the error.

## 3\. Check for Microsoft Store Updates

 Another potential reason for this error is the outdated Windows Store version. Microsoft regularly releases updates to fix bugs and improve Store performance. So, make sure that you are using the latest version. To check for Windows Store updates, follow these steps.

1. Go to Start, search for Microsoft Store, and click on it.
2. Click the **Library** icon. This will be on the left side of the Store app.  
![Check for Microsoft Store Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-microsoft-store-updates.jpg)
3. Next, click the **Get updates** button to check for available updates.
4. If updates are available, click **Update all** to download and install them.

 After following the steps above, restart your computer and see if it resolves the issue.

## 4\. Run the Windows Store Apps Troubleshooter

 Windows comes with a built-in troubleshooter that diagnoses and resolves various problems. You can use it to fix the “This app will not work on your device” error as well. To run the troubleshooter, follow these steps:

1. Right-click on Start and select **Settings** from the menu list.
2. From the left pane, click **System > Troubleshoot > Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
3. Scroll down to **Windows Store Apps** and click the **Run** button.  
![Run Windows Store Apps Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-store-apps-troubleshooter.jpg)
4. Wait for the troubleshooter to detect any problem and fix it if necessary.

 After performing the instructions, try launching the app again and see if it works. If not, you can try the next solution below.

## 5\. Restart the Application Identity Service

 Application Identity service determines and verifies the identity of Windows Store apps. So, if it’s not running correctly, you may run into this error. To restart this service, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services window.
3. Scroll down to find the **Application Identity** service and double-click on it.  
![Restart the Application Identity Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restart-the-application-identity-service.jpg)
4. In the Properties window, set the **Startup type** to **Automatic**.
5. Also, click on the **Start** button under Service status.
6. Finally, click **Apply > OK** to save the changes.

 Now, restart your computer and check if the error has been resolved. If not, proceed to the next solution.

## 6\. Temporarily Disable Your Antivirus Program

 If you have an antivirus program installed on your computer, it could block the app from running. To check if this is the case, temporarily disable your antivirus and see if it works. Here's how to do it:

1. Press **Win + I** on your keyboard to [open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Select **Privacy & security** in the left sidebar.
3. Go to the right pane and click **Open Windows Security**.
4. Once you're in Windows Security, select **Virus & threat protection** from the left pane.
5. Next, scroll down to **Virus & threat protection settings** and click **Manage settings**.  
![Manage settings in Windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/manage-settings-in-windows-security.jpg)
6. Turn off the **Real-time protection** toggle.  
![Turn off the Real-time protection toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-off-the-real-time-protection-toggle.jpg)

 Now restart your computer and try launching the app again. If the error still persists, turn on Real-time protection and try the next one.

## 7\. Enable Hyper-V in Windows Features

 Hyper-V is a Microsoft virtualization technology that lets some Microsoft Store apps run. If it isn't enabled on your device, you may encounter the “This app will not work on your device” error when installing certain programs.

1. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and view it in **Category** mode.
2. Go to **Programs > Programs and Features > Turn Windows features on or off**.
3. In the Windows Features dialog, scroll down to **Hyper-V** and check the box next to it.  
![Enable Hyper-V in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-hyper-v-in-windows-features.jpg)
4. Similarly, search for **Virtual Machine Platform** and **Windows Hypervisor Platform** and enable them as well.
5. Once done, click **OK > Apply** to save the changes.

 Finally, restart your computer and check if the problem is resolved.

## 8\. Perform Several Generic Windows Fixes

 If none of the above solutions managed to fix the error, you can try performing several generic fixes. This includes [running the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to scan for missing or corrupted files and the Deployment Image Servicing and Management tool to repair any corrupt system image.

 You can also [reset the Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) app to its default settings. This will reset the Store to its original configuration and potentially fix the error you're experiencing.

 If there are still problems, you can try [performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). It will launch the device with a minimal set of drivers and programs, allowing you to identify any 3rd-party applications that may be causing the error. Once done, restart your computer normally and check if the error has been fixed.

## Keep Your Apps Up and Running on Windows

 It's okay if you receive a "this app will not work on your device" message; it just means that your system doesn't meet an app's requirements or there is a corrupted Microsoft Store cache. Thankfully, our guide offers solutions to resolve this issue quickly.

 There could be various reasons for this issue depending on the app, such as a corrupted cache file or system problems. Read this guide to learn more about this error and how to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unleash-your-inner-gamer-strategic-play-and-success-at-zero-cost/"><u>Unleash Your Inner Gamer: Strategic Play & Success at Zero-Cost</u></a></li>
<li><a href="https://win11.techidaily.com/digital-detox-for-pcs-a-collection-of-13-revival-methods/"><u>Digital Detox for PCs: A Collection of 13 Revival Methods</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winrars-summation-oversights-a-6-step-approach/"><u>Correcting WinRAR's Summation Oversights: A 6-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocks-lost-luster-await-wise-wisdom-before-shift/"><u>BitLocks Lost Luster: Await Wise Wisdom Before Shift</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-inside-the-core-of-xstream-studios-an-exhaustive-studio-guide/"><u>2024 Approved  Inside the Core of XStream Studios – An Exhaustive Studio Guide</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-heart-of-windows-11-registry-explained/"><u>Delving Into the Heart of Windows 11: Registry Explained</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-professional-obs-edits-the-ultimate-top-5-guide/"><u>[Updated] In 2024, Professional OBS Edits  The Ultimate Top 5 Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Infinix Hot 40i? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-complete-resource-for-selecting-the-best-aiff-conversion-software/"><u>New The Complete Resource for Selecting the Best Aiff Conversion Software</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-pristine-windows-display-perfection/"><u>Crafting Pristine Windows Display Perfection</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-20-best-video-editors-compatible-with-dji-videos/"><u>2024 Approved  20 Best Video Editors Compatible with DJi Videos</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-accounts-after-fails/"><u>Bypassing Disabled Windows Accounts After Fails</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-galaxy-s23-fes-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Samsung Galaxy S23 FEs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11.techidaily.com/unrestricted-windows-dialogue-embrace-freedomgpt/"><u>Unrestricted Windows Dialogue: Embrace FreedomGPT</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-image-editing-efficiently-removing-backdrops/"><u>The Art of Image Editing: Efficiently Removing Backdrops</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-youtube-success-by-uploading-from-twitch-streams/"><u>Crafting YouTube Success by Uploading From Twitch Streams</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/expert-tiktok-editing-simplified-methods-for-bold-video-makeovers-for-2024/"><u>Expert TikTok Editing  Simplified Methods for Bold Video Makeovers for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-dimming-on-lenovo-laptop-displays/"><u>Overcoming Dimming on Lenovo Laptop Displays</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-access-the-key-to-your-windows-11-folder/"><u>Conquering Access: The Key to Your Windows 11 Folder</u></a></li>
</ul></div>
