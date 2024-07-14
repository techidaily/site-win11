---
title: "Boost Performance: Using NTFS File Compression Wisely"
date: 2024-07-13T11:25:01.483Z
updated: 2024-07-14T11:25:01.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Performance: Using NTFS File Compression Wisely"
excerpt: "This Article Describes Boost Performance: Using NTFS File Compression Wisely"
keywords: Boost Performance,NTFS Compression,Data Optimization,Faster Storage,NTFS Files,Efficient Space,File Compression Use
thumbnail: https://thmb.techidaily.com/41b376d29e85724c5481e57f7a36ad6deb299d08d21887a298dcedb2ce73aa51.jpg
---

## Boost Performance: Using NTFS File Compression Wisely

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.


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
<li><a href="https://location-social.techidaily.com/in-2024-does-motorola-moto-g13-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Motorola Moto G13 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-honor-play-8t-by-drfone-android/"><u>How to Show Wi-Fi Password on Honor Play 8T</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-resolving-obs-darkness-during-playbacks/"><u>[New] In 2024, Resolving OBS Darkness During Playbacks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-pioneering-tiktok-creations-with-foundational-tools/"><u>[New] In 2024, Pioneering TikTok Creations with Foundational Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-tray-displaying-cpu-and-memory-usage/"><u>Boosting System Tray: Displaying CPU & Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-cursor-signal-strength-in-win-11-os/"><u>Boosting Cursor Signal Strength in Win 11 OS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-advanced-steps-in-monitoring-and-archiving-system-sounds/"><u>[New] Advanced Steps in Monitoring & Archiving System Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-customized-windows-cmd/"><u>Boosting Productivity with Customized Windows Cmd</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-platform-selection-guide-determining-the-best-for-individual-creators/"><u>In 2024, Platform Selection Guide  Determining the Best for Individual Creators</u></a></li>
<li><a href="https://win11.techidaily.com/banish-already-in-use-errors-and-unique-device-naming/"><u>Banish 'Already in Use' Errors and Unique Device Naming</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-final-cut-pro-x-jump-cuts-from-beginner-to-pro-in-no-time/"><u>New Final Cut Pro X Jump Cuts From Beginner to Pro in No Time</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-samurai-spirit-explored-in-top-10-gaming-worlds-for-2024/"><u>[New] Samurai Spirit, Explored in Top 10 Gaming Worlds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-youtube-viewing-on-chrome-windows/"><u>Achieving Flawless YouTube Viewing on Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-thorough-breakdown-googles-podcast-app-unveiled/"><u>[New] Thorough Breakdown  Google's Podcast App Unveiled</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-pioneering-tiktok-creations-with-foundational-tools/"><u>[New] Pioneering TikTok Creations with Foundational Tools</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-microsofts-shielded-browsing/"><u>Activating Prints with Microsoft's Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-harmonious-sound-editing-guide-advantages-disadvantages-and-substitutes/"><u>2024 Approved Harmonious Sound Editing Guide Advantages, Disadvantages, and Substitutes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-secrets-of-effective-free-youtube-video-transcriptions-revealed/"><u>[New] The Secrets of Effective, FREE YouTube Video Transcriptions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/get-rid-of-youtube-distractions-ad-blocking-on-chrome-firefox-and-ios-for-2024/"><u>Get Rid of YouTube Distractions  Ad-Blocking on Chrome, Firefox & iOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-user-management-via-windows-terminal/"><u>Advanced User Management via Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
</ul></div>
