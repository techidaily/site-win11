---
title: "Syncing with Windows 11: Changing Default Actions Smoothly"
date: 2024-07-13T10:18:55.260Z
updated: 2024-07-14T10:18:55.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Syncing with Windows 11: Changing Default Actions Smoothly"
excerpt: "This Article Describes Syncing with Windows 11: Changing Default Actions Smoothly"
keywords: Win11 Default Actions,Sync Windows Settings,Change PC Defaults,Action Panel Adjustment,Smooth Setup W11,Easy System Customize,New OS Configuration
thumbnail: https://thmb.techidaily.com/c3ecdd732aca091f9e06be3caec567f3fcd17c056bf2dd14982465e8c7b5b6a1.jpg
---

## Syncing with Windows 11: Changing Default Actions Smoothly

 If you are not satisfied with any of the default apps assigned by Windows, you can change them to your preferred options. This process was quite simple in Windows 10, but Microsoft has made it a bit complicated for Windows 11 users.

 In this guide, we will discuss the method of changing the default apps in Windows 11 in detail. We have also discussed several troubleshooting methods later in this guide that you can try if the default apps fail to change.

## How to Change the Default Apps in Windows 11

[Changing the default apps in Windows 10](https://www.makeuseof.com/tag/change-default-settings-windows-10/) is quite simple. You can access the**Default Apps** section of the Settings app and replace the current default app with your preferred option.

 In Windows 11, this method is slightly different. You must set a program default for all the registered file types and links relevant to it since there isn’t a**Set default for all** option available.

 Below, we have listed different ways of changing the default apps in Windows 11:

### 1\. Choose the Open With Option

 The easiest method of changing the default apps option is by using the Open with option in the context menu for files.

Here is how you can do that:

1. Right-click on the targeted file. For instance, an image file that you want to open with an app other than the default Photos app.
2. Choose**Open with** \>**Choose another app** from the context menu.  
![Choose another app to open the targeted file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-open-with-choose-another-app.jpg)
3. Now, in the following dialog, choose the app you want to set as the default option. If you cannot find the targeted app in the list, choose**Look for another app on this PC** and then select the app.
4. Click on**Always use this app to open files** and click**OK** . This should set the selected app as the default preference.  
![Set a default app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/set-the-default-app.jpg)

### 2\. Use the Settings App

 The next thing that you can do is access the Default Apps option and choose the preferred app from there.

Follow these steps to proceed:

1. Press the Win + I keys together to open the Windows Settings.
2. Choose**Apps** from the left pane.
3. Click on**Default apps** .  
![Click on the Default apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-settings-apps-default-apps.jpg)
4. Next, choose the app that you want to set as default. You should now see all the file types and link types the app is registered with.
5. If you want to choose a program as the default for all its registered file types and links, you'd need to click each type and choose the desired application in the following dialog.  
![Pick a default file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pick-a-default-file-type.jpg)

 This should set the app as the default option for the selected file and link types. However, if you [reset Windows 11 to its default state](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) ever, you will lose all these settings.

### 3\. Use File Properties

 You can also change the file properties of the targeted file to open it with a new default app.

To proceed, follow these steps:

1. Right-click on the targeted file and choose**Properties** from the context menu.  
![Access the properties of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties.jpg)
2. Head over to the General tab and click on the**Change** button associated with**Opens with** .  
![Click on the Change button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties-general-change.jpg)
3. Now, choose the desired app and click**OK** .

## What to Do If You Cannot Change the Default Apps in Windows 11?

 If you are unable to change the default apps in Windows 11 despite trying the different methods mentioned above, it could be due to the following reasons:

* The app that you are trying to set as the default option is dealing with a corruption error or is not installed correctly.
* A group policy setting in the system is preventing you from changing these configurations.
* You do not have sufficient permissions to make changes of this level in the system.
* The app is not compatible with your system.

 In this case,[ensure that your user account has administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/) and that the app you are trying to set as default is compatible with the system. Here are some more steps you can follow to resolve the problem.

### 1\. Update Windows 11

 If you're running an outdated version of Windows, you may be experiencing problems due to incompatibility issues. Windows 11 needs to be updated to the latest version in this case.

Here is how you can do that:

1. Press the Win + I keys together to open Windows Settings.
2. Choose**Windows Update** from the left pane.
3. Now, click on the**Check for updates** button on the right side.
4. Install all the pending updates one by one by clicking on the**Download & install** button and then restart your PC.  
![Click on the Download & install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-windows-update-download-and-install.jpg)

 Once this is done, follow one of the steps above to change the default app.

### 2\. Reset the Targeted App

 If the problem is within the app that you are trying to change, you can reset the program to solve the problem.

Follow these steps to proceed:

1. Press Win + S keys together to open Windows Search.
2. Type Powershell and choose**Run as administrator** .
3. Click**Yes** in the User Account Control prompt.
4. In the Powershell window, type the command mentioned below and click Enter. Replace packagename with the name package name of the app that you want to set as default.  
Get-AppxPackage packagename -AllUsers | Reset-AppxPackage
5. For instance, if you want to change the Photos app, execute the following command:  
Get-AppxPackage Microsoft.Windows.Photos -AllUsers | Reset-AppxPackage  
![Reset the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-appxpackage-packagename.jpg)
6. Once the command is executed, check if you can change the default app.

### 3\. Reinstall the App

 Lastly, you can try reinstalling the app that you want to set as default. This will eliminate any corruption errors are bugs within the app that are preventing you from setting it as the default option.

Here is how you can proceed:

1. Press the Win + R keys together to open a Run dialog.
2. Type control in Run and click Enter.
3. In the following window, navigate to**Uninstall a program** .  
![Uninstall a program](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/uninstall-a-program.jpg)
4. Locate the targeted app and right-click on it.
5. Choose**Uninstall** and follow the on-screen instructions to proceed.  
![Uninstall the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-uninstall-program.jpg)

 Once the uninstallation is completed, restart the computer and reinstall the app. Hopefully, this time, you will be able to set it as the default option without any problems.

## Make Your Preferred Apps Default

 The apps set as the default options on Windows are quite user-friendly and efficient. It is possible, however, to change the default preference to a better option if you have found one that suits your system better.

 With the methods listed above, you should be able to change the default apps on your Windows 11 system in no time. Nevertheless, keep in mind that in the event that Windows is reinstalled or reset, these options will return to the default configuration.

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
<li><a href="https://fox-boxes.techidaily.com/updated-high-end-drones-expert-buyers-choices-top-5-for-2024/"><u>[Updated] High-End Drones - Expert Buyers' Choices, Top 5 for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-starting-with-telegram-advertising-essential-steps-for-newbies/"><u>[Updated] Starting with Telegram Advertising  Essential Steps for Newbies</u></a></li>
<li><a href="https://audio-editing.techidaily.com/silencing-sounds-five-techniques-for-deleting-audio-in-digital-footage/"><u>Silencing Sounds Five Techniques for Deleting Audio in Digital Footage</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-earn-while-playing-games-online/"><u>[New] In 2024, Earn While Playing Games Online</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-essential-guide-to-playstation-45-audio-tweaks/"><u>The Essential Guide to PlayStation 4/5 Audio Tweaks</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-simplify-complex-designs-by-mastering-figmas-backdrop-cleansing/"><u>2024 Approved  Simplify Complex Designs by Mastering Figma's Backdrop Cleansing</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-ctrl-keys-in-windows-11/"><u>Fixing Non-Operational Ctrl Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-it-all-the-top-7-ways-to-use-windows-11-effectively/"><u>Optimize It All: The Top 7 Ways to Use Windows 11 Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-xiaomi-redmi-note-12r-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuity-with-powertoys-settings-transfer/"><u>Ensuring Continuity with PowerToys Settings Transfer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://extra-information.techidaily.com/smartphones-meet-virtual-reality-best-10-models/"><u>Smartphones Meet Virtual Reality  Best 10 Models</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-best-free-video-editing-programs-for-old-windows-pcs/"><u>2024 Approved The Best Free Video Editing Programs for Old Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-cloud-connectivity-revive-google-drive-windows-links/"><u>Streamlining Cloud Connectivity: Revive Google Drive Windows Links</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/illusions-realized-what-is-augmented-reality-for-2024/"><u>Illusions Realized  What Is Augmented Reality for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-preserving-pixels-in-the-sky-selecting-best-photo-cloud-storages/"><u>2024 Approved  Preserving Pixels in the Sky  Selecting Best Photo Cloud Storages</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-creative-freedom-in-videos-the-art-of-audio-integration/"><u>In 2024, Unlock Creative Freedom in Videos  The Art of Audio Integration</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-refine-content-creation-high-end-watermark-erasers/"><u>2024 Approved  Refine Content Creation  High-End Watermark Erasers</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-realme-12plus-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Realme 12+ 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-techniques-for-overcoming-media-app-issues-in-win11/"><u>Methodical Techniques for Overcoming Media App Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insights-for-placement-of-software-shortcuts-on-taskbar/"><u>Quick Insights for Placement of Software Shortcuts on Taskbar</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-exploring-streaming-options-vimeo-vs-youtubes-popularity/"><u>[New] In 2024, Exploring Streaming Options  Vimeo vs YouTube's Popularity</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-geforce-error-x0001-on-windows-pcs/"><u>Fixing Common GeForce Error X0001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/essential-sync-software-windows-and-android-unite/"><u>Essential Sync Software: Windows & Android Unite</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-hevc-files-on-sony-xperia-10-v-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Failed to play HEVC files on Sony Xperia 10 V</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-list-for-seeking-no-cost-high-quality-vector-imagery/"><u>[Updated] The Ultimate List for Seeking No-Cost High-Quality Vector Imagery</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-demystifying-facebooks-blue-image-symbol/"><u>[Updated] In 2024, Demystifying Facebook's Blue Image Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/discover-football-fortunes-for-free-with-old-championship-manager/"><u>Discover Football Fortunes for Free with Old Championship Manager</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dark-theme-for-notepad-win-11/"><u>Mastering Dark Theme for Notepad (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-restore-missing-app-icons/"><u>Methods to Restore Missing App Icons</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-realme-c67-5g-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Realme C67 5G Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-premium-selection-of-webinar-technologies/"><u>2024 Approved  Premium Selection of Webinar Technologies</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-past-connections-discovering-friends-timelines/"><u>Unveiling Past Connections: Discovering Friends' Timelines</u></a></li>
</ul></div>
