---
title: Reducing CPU/RAM Drain From Consuming Video Content
date: 2024-07-13T09:46:27.772Z
updated: 2024-07-14T09:46:27.772Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reducing CPU/RAM Drain From Consuming Video Content
excerpt: This Article Describes Reducing CPU/RAM Drain From Consuming Video Content
keywords: Video Content Efficiency,Reduce Resource Usage,Optimize Video Playback,Streamline Memory Use,Improve CPU Performance,RAM Consumption Lessening,Video Buffering Reduction
thumbnail: https://thmb.techidaily.com/d5e8491d3f34992956d5390f8a8c8192037db1bb4f39254b71c759c472e8e33a.jpg
---

## Reducing CPU/RAM Drain From Consuming Video Content

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
<li><a href="https://some-skills.techidaily.com/new-top-6-video-editing-apps-for-macos-big-sur-11/"><u>[New] Top 6 Video Editing Apps for macOS Big Sur 11</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-typing-efficiency-with-w11-bespo-points/"><u>Elevate Typing Efficiency with W11, Bespo Points</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-menu-items-in-windows-11-desktop/"><u>Addressing Frozen Menu Items in Windows 11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-the-coolest-anime-characters-ever-list-of-top-favorites/"><u>In 2024, The Coolest Anime Characters Ever| List of Top Favorites</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/thumbnail-crafting-101-the-fundamentals-covered-for-2024/"><u>Thumbnail Crafting 101  The Fundamentals Covered for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-facebooks-2023-vision-mastering-the-art-of-short-videos/"><u>[Updated] In 2024, Facebook's 2023 Vision  Mastering the Art of Short Videos</u></a></li>
<li><a href="https://win11.techidaily.com/audio-amplifiers-4-essential-tools-that-push-pc-sounds-past-100/"><u>Audio Amplifiers: 4 Essential Tools that Push PC Sounds Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-opengl-error-3-from-nvidia/"><u>Correcting OpenGL Error 3 From NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-null-associated-app-error-on-windows-systems/"><u>Fixing Null Associated App Error on Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-saving-reels-made-simple-direct-and-indirect-techniques-explained/"><u>[New] 2024 Approved  Saving Reels Made Simple  Direct and Indirect Techniques Explained</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-generic-device-halt-a-guide/"><u>Bypassing Windows Generic Device Halt: A Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-xiaomi-14-ultra-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Xiaomi 14 Ultra phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-retrieve-faded-bios-messages/"><u>Tips to Retrieve Faded BIOS Messages</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-windows-speech-to-text-app-using-whisper-and-ahk/"><u>Creating a Personalized Windows Speech-to-Text App Using Whisper & AHK</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-chkdsk-sfc-and-dism-for-system-repairing/"><u>Decoding CHKDSK, SFC & DISM for System Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-plan-9-steps-to-stop-wwe-crashes-in-windows/"><u>Accelerated Action Plan: 9 Steps to Stop WWE Crashes in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-in-the-spotlight-top-viewers-choice/"><u>[New] In 2024, In the Spotlight  Top Viewers' Choice</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-perfecting-switch-pro-techniques-on-steam-platform/"><u>2024 Approved  Perfecting Switch Pro Techniques on Steam Platform</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-get-final-cut-pro-for-free/"><u>[Updated] How to Get Final Cut Pro for Free</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-a-comprehensive-guide-to-instagram-edits-for-professionals-for-2024/"><u>[New] A Comprehensive Guide to Instagram Edits for Professionals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-failed-0x0000011b-in-windows/"><u>Overcoming Operation Failed 0X0000011B in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-setting-up-your-gaming-studio-with-obs/"><u>[New] In 2024, Setting Up Your Gaming Studio with OBS</u></a></li>
<li><a href="https://win11.techidaily.com/cease-alerts-for-unrequested-system-recommendations/"><u>Cease Alerts for Unrequested System Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-windows-ui-cli-features-for-taskmgr-windowed-console/"><u>Augmenting Windows UI: CLI Features for TaskMgr Windowed Console</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-powerpoint-and-voice-a-seamless-journey-explored/"><u>[New] In 2024, PowerPoint and Voice  A Seamless Journey Explored</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-the-artist-writes-an-ipad-guide-to-time-lapse-photography/"><u>In 2024, The Artist' Writes  An iPad Guide to Time-Lapse Photography</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-video-editing-on-mac-vn-editor-and-other-top-picks/"><u>2024 Approved Video Editing on Mac VN Editor and Other Top Picks</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-apple-iphone-7-without-a-passcode-drfone-by-drfone-ios/"><u>8 Safe and Effective Methods to Unlock Your Apple iPhone 7 Without a Passcode | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-realme-gt-5-240w-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Realme GT 5 (240W) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-your-content-game-perfectly-tailored-youtube-shorts-thumbnails-for-2024/"><u>[New] Elevate Your Content Game  Perfectly Tailored YouTube Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/investment-alert-avoid-the-trap-of-artificial-youtube-engagement-for-2024/"><u>Investment Alert  Avoid the Trap of Artificial YouTube Engagement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-fix-steam-not-detecting-your-controller-on-windows/"><u>10 Ways to Fix Steam Not Detecting Your Controller on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-taskbar-with-numeric-key-and-caps-indicator-symbols/"><u>Augment Windows Taskbar with Numeric Key & Caps Indicator Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
</ul></div>
