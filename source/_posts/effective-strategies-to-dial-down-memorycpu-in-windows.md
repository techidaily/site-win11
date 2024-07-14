---
title: Effective Strategies to Dial Down Memory/CPU in Windows
date: 2024-07-13T10:07:49.769Z
updated: 2024-07-14T10:07:49.769Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Strategies to Dial Down Memory/CPU in Windows
excerpt: This Article Describes Effective Strategies to Dial Down Memory/CPU in Windows
keywords: Reduce Memory Usage (Windows),CPU Load Control (Windows),Optimize RAM Efficiency (Windows),Cut Down Processing Power (Windows),Speed Up CPU Performance (Windows),Manage System Resources (Windows),Efficient Windows Memory (CPU & RAM)
thumbnail: https://thmb.techidaily.com/ec5c93589cbbf4437a85d01509aad074c0824b7a47a862a6e3798990cfe51fb1.png
---

## Effective Strategies to Dial Down Memory/CPU in Windows

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
<li><a href="https://facebook-record-videos.techidaily.com/top-10-tunes-turned-into-wit-wonders-for-2024/"><u>Top 10 Tunes Turned Into Wit Wonders for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-new-design-horizons-the-leading-10-vector-apps/"><u>[New] Navigating New Design Horizons  The Leading 10 Vector Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-windows-error-0xc0000001/"><u>Overcoming the Challenge of Windows Error 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-window-11-wallpaper-settings-for-individual-monitors/"><u>Navigating Window 11 Wallpaper Settings for Individual Monitors</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-miniature-mastery-in-the-social-sphere-who-wins-with-youtube-shorts-or-tiktoks/"><u>In 2024, Miniature Mastery in the Social Sphere  Who Wins with YouTube Shorts or TikToks?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/vectors-for-novices-uncover-essentials-types-and-applications/"><u>Vectors for Novices  Uncover Essentials, Types & Applications</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-beginners-obs-techniques-for-youtube-live-streaming/"><u>In 2024, Beginner's OBS Techniques for YouTube Live Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-access-preventing-read-only-windows-folders/"><u>Secure File Access: Preventing Read-Only Windows Folders</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-realme-11-proplus-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Realme 11 Pro+</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-11-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 11 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-issues-with-windows-system-health-indicator/"><u>Remedying Issues with Windows System Health Indicator</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-steam-sync-issue/"><u>Solving Windows Steam Sync Issue</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-unresponsive-windows-media-files/"><u>Steps to Rectify Unresponsive Windows Media Files</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-barriers-reviving-spotify-streams/"><u>Overcoming Network Barriers: Reviving Spotify Streams</u></a></li>
<li><a href="https://win11.techidaily.com/routine-task-for-eliminating-steam-dns-cache-on-pc/"><u>Routine Task for Eliminating Steam DNS Cache on PC</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pathway-to-choosing-between-game-and-studio-nvidia-drivers/"><u>Personalized Pathway to Choosing Between Game and Studio Nvidia Drivers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-close-up-confidence-navigating-google-meets-zoom-feature/"><u>[New] Close-Up Confidence  Navigating Google Meet's Zoom Feature</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-iphone-x-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From iPhone X</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-composing-accompaniment-for-film-scenes/"><u>Updated 2024 Approved Composing Accompaniment for Film Scenes</u></a></li>
<li><a href="https://win11.techidaily.com/easing-frustrations-with-a-fix-to-non-working-pen-devices-in-windows/"><u>Easing Frustrations with a Fix to Non-Working Pen Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/shining-up-dull-desktops-with-vibrant-colors/"><u>Shining Up Dull Desktops with Vibrant Colors</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-older-bios-setup-elements/"><u>Refreshing Older BIOS Setup Elements</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-perplexity-of-blued-in-windows-10/"><u>Overcoming the Perplexity of Blued in Windows 10</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-xiaomi-14-pro-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Xiaomi 14 Pro To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resurrect-inactive-windows-email-rule-configurations/"><u>Methods to Resurrect Inactive Windows Email Rule Configurations</u></a></li>
</ul></div>
