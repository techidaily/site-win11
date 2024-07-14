---
title: Navigating Windows Hello Fingerprint Malfunctions Easily
date: 2024-07-13T11:03:09.050Z
updated: 2024-07-14T11:03:09.050Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows Hello Fingerprint Malfunctions Easily
excerpt: This Article Describes Navigating Windows Hello Fingerprint Malfunctions Easily
keywords: Windows Hello Fix Guide,Fingerprint Error Resolution,Sign-In Troubleshooting,Biometric Access Solutions,Easy Login Restart,Passwordless Sign-In Help,Fingerprint Recognition Support
thumbnail: https://thmb.techidaily.com/00e6694a6e8523368549c14f60a0299171aaa265941fbab1955d445021800a72.jpg
---

## Navigating Windows Hello Fingerprint Malfunctions Easily

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cant-find-copilot-on-windows-11-heres-what-to-do/"><u>Can't Find Copilot on Windows 11? Here's What To Do</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-split-a-clip-in-davinci-resolve-step-by-step/"><u>New How to Split a Clip in DaVinci Resolve Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-navigating-blank-login-page-fixes/"><u>Windows 11: Navigating Blank Login Page Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-windows-11-customization-techniques/"><u>A Detailed Guide to Windows 11 Customization Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-reviving-obs-sound-capture-steps/"><u>[Updated] In 2024, Reviving OBS Sound Capture Steps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-from-novice-to-pro-elevating-your-ps4-gameplay-screenshot-skills/"><u>[New] From Novice to Pro  Elevating Your PS4 Gameplay Screenshot Skills</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-funimate-masterclass-quick-video-access/"><u>2024 Approved  Funimate Masterclass  Quick Video Access</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-how-to-mute-audio-in-windows-movie-maker/"><u>New 2024 Approved How to Mute Audio in Windows Movie Maker?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-culinary-waves-tiktoks-most-shared-meals/"><u>[Updated] In 2024, Culinary Waves  TikTok's Most Shared Meals</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-desktop-opt-for-smart-window-arrangement/"><u>Revolutionize Your Desktop: Opt for Smart Window Arrangement</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-from-clash-to-harmony-mastering-color-matching-in-final-cut-pro/"><u>New 2024 Approved From Clash to Harmony Mastering Color Matching in Final Cut Pro</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-characters-that-convert-ideal-story-strategies/"><u>[Updated] In 2024, Characters That Convert  Ideal Story Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-strategies-to-overcome-access-barriers-on-win-pcs/"><u>Top 8 Strategies to Overcome Access Barriers on Win PCs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-capturing-your-hp-pcs-display/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Capturing Your HP PC's Display</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-boot-on-windows-sound-service-reboot-needs/"><u>Troubleshooting Boot-On Windows Sound Service Reboot Needs</u></a></li>
<li><a href="https://win11.techidaily.com/self-contained-strategies-for-hardware-duplication/"><u>Self-Contained Strategies for Hardware Duplication</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-oppo-f25-pro-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Oppo F25 Pro 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-controlling-windows-key-status/"><u>Understanding and Controlling Windows Key Status</u></a></li>
<li><a href="https://win11.techidaily.com/demonstrating-the-power-of-powershell-removing-restrictions-on-windows/"><u>Demonstrating the Power of PowerShell: Removing Restrictions on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://win11.techidaily.com/craft-your-own-secure-windows-pin-with-custom-patterns/"><u>Craft Your Own Secure Windows PIN with Custom Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-backup-mishaps/"><u>Troubleshooting Steam Backup Mishaps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-galaxy-of-play-ultimate-list-of-the-cheapest-rpgs-online/"><u>[New] In 2024, Galaxy of Play  Ultimate List of the Cheapest RPGs Online</u></a></li>
<li><a href="https://driver-install.techidaily.com/successful-samsung-ssd-driver-update-for-windows-pcs/"><u>Successful Samsung SSD Driver Update for Windows PCs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-a-journey-through-snapchats-creative-edit-features/"><u>[New] 2024 Approved  A Journey Through Snapchat's Creative Edit Features</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-top-facebook-video-mp4-downloaders/"><u>[Updated] Top Facebook Video MP4 Downloaders</u></a></li>
<li><a href="https://win11.techidaily.com/windows-warnings-identifying-critical-processes-for-malware-detection/"><u>Windows Warnings: Identifying Critical Processes for Malware Detection</u></a></li>
<li><a href="https://screen-recording.techidaily.com/full-screen-recovered-from-obs-errors/"><u>Full Screen Recovered From OBS Errors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tiktok-and-twittersphere-crossover-the-viral-vids/"><u>[New] TikTok and Twittersphere Crossover  The Viral Vids</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-vivo-y100t-is-unlocked-by-drfone-android/"><u>How To Check if Your Vivo Y100t Is Unlocked</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-8-popular-oculus-rift-games-you-should-try/"><u>In 2024, 8 Popular Oculus Rift Games You Should Try</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-eliminating-wsl-from-win-11-pcs/"><u>Comprehensive Guide: Eliminating WSL From Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-art-with-top-win-11-sketch-tools/"><u>Elevate Your Art with Top Win 11 Sketch Tools</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-recognize-non-appearing-hdd/"><u>Strategies to Recognize Non-Appearing HDD</u></a></li>
<li><a href="https://win11.techidaily.com/close-all-easy-as-1-2-3-windows-multi-app-command/"><u>Close All, Easy as 1-2-3: Windows Multi-App Command</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-steam-performance-overcoming-degraded-download-rates/"><u>Skyrocket Steam Performance: Overcoming Degraded Download Rates</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-empty-directory-faux-pas-in-windows-a-guide-to-error-x80070091/"><u>Demystifying the 'Empty Directory' Faux Pas in Windows - A Guide to Error X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-techniques-for-mac-address-discovery-in-windows-11/"><u>Top 4 Techniques for Mac Address Discovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-odbc-configuration-basics/"><u>Delving Into Windows ODBC Configuration Basics</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-windows-11-app-opening-secrets-revealed/"><u>Turbo Windows 11 App Opening Secrets Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/bios-tips-combatting-the-problem-of-grayed-out-secure-boot-on-windows/"><u>BIOS Tips: Combatting the Problem of Grayed-Out Secure Boot on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-step-by-step-shortcut-for-easy-mac-screen-recording/"><u>2024 Approved  Step-by-Step Shortcut for Easy Mac Screen Recording</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tips-simply-recognize-your-computers-ram-type/"><u>Tech Tips: Simply Recognize Your Computer's RAM Type</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How can I get more stardust in pokemon go On Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-a-productive-win-11-taskbar/"><u>The Ultimate Guide to a Productive Win 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/silent-restarts-a-windows-1011-guide-to-going-dark/"><u>Silent Restarts: A Windows 10/11 Guide to Going Dark</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-ensure-audible-feedback-in-screen-captures/"><u>Techniques to Ensure Audible Feedback in Screen Captures</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-premier-action-cameras-for-snow-adventures/"><u>[New] 2024 Approved  Premier Action Cameras for Snow Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-way-to-relaunch-printer-service/"><u>Efficient Way to Relaunch Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-transformation-through-38-years/"><u>Taskbar Transformation Through 38 Years</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-cultivate-creativity-best-video-concepts-for-viewers/"><u>2024 Approved  Cultivate Creativity  Best Video Concepts for Viewers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-free-software-strategies-for-efficient-educational-streaming/"><u>[Updated] Free Software Strategies for Efficient Educational Streaming</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-optimal-8-camera-stands-for-ultra-hd-shooting/"><u>2024 Approved  Optimal 8 Camera Stands for Ultra-HD Shooting</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/effortlessly-enhance-your-tiktok-aesthetic-guide-inside-for-2024/"><u>Effortlessly Enhance Your TikTok Aesthetic  Guide Inside for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-task-tracker-update-rate-in-windows-11/"><u>Enhancing Live Task Tracker Update Rate in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-save-location-glitch-quick-guide/"><u>Windows Save Location Glitch: Quick Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-xiaomi-14-ultra-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Xiaomi 14 Ultra Device</u></a></li>
</ul></div>
