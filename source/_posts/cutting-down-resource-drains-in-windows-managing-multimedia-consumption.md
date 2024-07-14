---
title: "Cutting Down Resource Drains in Windows: Managing Multimedia Consumption"
date: 2024-07-13T10:00:17.598Z
updated: 2024-07-14T10:00:17.598Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cutting Down Resource Drains in Windows: Managing Multimedia Consumption"
excerpt: "This Article Describes Cutting Down Resource Drains in Windows: Managing Multimedia Consumption"
keywords: Multimedia Management,Save Resources Win,Reduce Media Usage,Efficient Windows Use,Streamline System Load,Optimize Resource Spend,Cut Unnecessary Consumption
thumbnail: https://thmb.techidaily.com/02857e9a5729a034df5799d80242303ce172ee6947ee8ec278b9096d58e3459c.jpg
---

## Cutting Down Resource Drains in Windows: Managing Multimedia Consumption

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://win11.techidaily.com/expert-techniques-for-fast-utorrent-downloads-on-windows/"><u>Expert Techniques for Fast uTorrent Downloads on Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-approaches-to-isolate-and-omit-audio-from-video-content/"><u>Updated 2024 Approved Approaches to Isolate and Omit Audio From Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-mending-deskanywhere-on-windows-11/"><u>Methods for Mending DeskAnywhere on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/overcoming-common-gs-pitfalls-in-kinemaster-for-2024/"><u>Overcoming Common GS Pitfalls in KineMaster for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-xiaomi-redmi-note-13-proplus-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Xiaomi Redmi Note 13 Pro+ 5G? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-best-practices-for-compliant-twitter-videos/"><u>[Updated] 2024 Approved  Best Practices for Compliant Twitter Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-how-to-edit-titles-and-descriptions-of-igtv-videos/"><u>[New] In 2024, How to Edit Titles and Descriptions of IGTV Videos?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-esteemed-creators-best-of-breed-insta-hlv-makers/"><u>[New] Esteemed Creators  Best-of-Breed Insta HLV Makers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-definitive-guide-to-crafting-videos-on-youtube/"><u>In 2024, The Definitive Guide to Crafting Videos on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-no-uninstall-issue-on-windows-oses/"><u>How to Sidestep No Uninstall Issue on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-vanquish-xps-mysterious-printer-error-xfddddf/"><u>How to Vanquish XP's Mysterious Printer Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-printer-force-delete-on-windows-11/"><u>Step-by-Step Printer Force Delete on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-from-social-media-videos-to-audible-mp3s-one-click-conversion-for-2024/"><u>[New] From Social Media Videos to Audible MP3s - One Click Conversion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/handling-missing-component-in-windows-lsassexe/"><u>Handling Missing Component in Windows' lsass.exe</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-pause-bring-back-lost-sounds-to-tech-gadgets/"><u>Resetting Pause: Bring Back Lost Sounds to Tech Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-clearing-microsoft-protection-archives/"><u>Mastering the Art of Clearing Microsoft Protection Archives</u></a></li>
<li><a href="https://win11.techidaily.com/esd-files-demystified-creating-iso-versions-for-windows-systems/"><u>ESD Files Demystified: Creating ISO Versions for Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-exception-breaking-point-on-microsoft-os/"><u>Steps to Eliminate Exception Breaking Point on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-remote-desktop-troubleshoot-internal-errors/"><u>Resolving Windows 11 Remote Desktop: Troubleshoot Internal Errors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-your-cortana-data-on-windows/"><u>How to Download Your Cortana Data on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-crop-resize-and-reform-mastering-video-shape-editing/"><u>In 2024, Crop, Resize, and Reform Mastering Video Shape Editing</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-6s-plus-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 6s Plus Lock Screen | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/professionally-speaking-the-top-5-drone-recommendations-for-2024/"><u>Professionally Speaking  The Top 5 Drone Recommendations for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-sync-up-your-studio-setup-the-8-most-popular-music-production-applications-for-mac-and-windows/"><u>2024 Approved Sync-Up Your Studio Setup The 8 Most Popular Music Production Applications for Mac and Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-e1-in-w10w11-devices/"><u>Tackling Error Code: E1 in W10/W11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-setting-windows-filter-keys/"><u>Essential Knowledge: Setting Windows Filter Keys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-clicks-avoid-accelerated-movement-in-win-1011/"><u>Stabilizing Clicks: Avoid Accelerated Movement in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-poco-c51-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Poco C51? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-mastery-guide-downloading-windows-movie-maker-6/"><u>[New] Mastery Guide  Downloading Windows Movie Maker 6</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-bluescreenview-a-step-by-step-tutorial/"><u>Exploring BlueScreenView - A Step-By-Step Tutorial</u></a></li>
</ul></div>
