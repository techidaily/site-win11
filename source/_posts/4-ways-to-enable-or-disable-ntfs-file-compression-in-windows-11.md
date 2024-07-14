---
title: 4 Ways to Enable or Disable NTFS File Compression in Windows 11
date: 2024-07-13T11:09:07.617Z
updated: 2024-07-14T11:09:07.617Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Enable or Disable NTFS File Compression in Windows 11
excerpt: This Article Describes 4 Ways to Enable or Disable NTFS File Compression in Windows 11
keywords: NTFS Compression Settings,Win11 File Compress Control,Windows Compression Feature,Enable/Disable NTFS Compaction,Adjusting NTFS Compression,Modify NTFS Compression in Win11,Turn On/Off File Compression WIN11
thumbnail: https://thmb.techidaily.com/1c9229fb0800113350dfae57f612d2aef9036646b6591dcd5ed2f832a16cf380.jpg
---

## 4 Ways to Enable or Disable NTFS File Compression in Windows 11

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
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-expert-discord-video-capturing-apps-mobile-desktop/"><u>2024 Approved  Expert Discord Video Capturing Apps  Mobile, Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-error-0x80073cf3-on-marketplace/"><u>Deciphering and Fixing Error 0X80073CF3 on Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-stopping-discords-autostart-and-updating-habits/"><u>Guide on Stopping Discord's Autostart & Updating Habits</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-on-walls-top-3-techniques/"><u>Fresh Start on Walls: Top 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-interactions-from-power-save-mode/"><u>Steering Device Interactions From Power Save Mode</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-viral-video-to-visuals-converting-tweets-to-costless-cgi-for-2024/"><u>[New] Viral Video to Visuals  Converting Tweets to Costless CGI for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-ultimate-list-of-affordable-android-speech-capture-and-audio-recording-tools/"><u>New The Ultimate List of Affordable Android Speech Capture and Audio Recording Tools</u></a></li>
<li><a href="https://win11.techidaily.com/clear-path-to-correctness-resolving-server-stumbled-issues-in-win-store/"><u>Clear Path to Correctness: Resolving Server Stumbled Issues in Win Store</u></a></li>
<li><a href="https://games-able.techidaily.com/your-guide-to-exciting-paid-nothing-switch-games/"><u>Your Guide to Exciting, Paid-Nothing Switch Games</u></a></li>
<li><a href="https://fox-helps.techidaily.com/leading-12-free-video-trimming-apps-for-android-users/"><u>Leading 12 Free Video Trimming Apps for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-post-update-linux-subsystem-challenges-on-windows-11/"><u>Unraveling Post-Update Linux Subsystem Challenges on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-how-to-proficiently-use-twitter-archives-for-2024/"><u>[New] How to Proficiently Use Twitter Archives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-spot-and-defeat-keygen-malware-in-your-windows-os-environment/"><u>How to Spot & Defeat Keygen Malware in Your Windows OS Environment</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-elevating-your-brand-with-intriguing-instagram-puzzle-feeds/"><u>[Updated] In 2024, Elevating Your Brand with Intriguing Instagram Puzzle Feeds</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-photoslideshow-pro-on-insta/"><u>In 2024, PhotoSlideshow Pro on Insta</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-woes-a-script-error-cure-all-guide/"><u>Tackling Windows Woes: A Script Error Cure-All Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphered-doorkeeper-no-swift-shift-to-new-solution/"><u>Deciphered Doorkeeper? No Swift Shift to New Solution</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-diy-tricks-for-professional-quality-homemade-films/"><u>Quick DIY Tricks for Professional-Quality Homemade Films</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-jailbreak-joy-top-funny-faces-at-the-social-networks-limits/"><u>2024 Approved  Jailbreak Joy - Top Funny Faces at the Social Network’s Limits</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-the-windows-11-guide-to-altering-fax-cover-pages/"><u>Getting Started: The Windows 11 Guide to Altering Fax Cover Pages</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-top-web-based-audio-visualizers-for-videos/"><u>Updated In 2024, Top Web-Based Audio Visualizers for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-mastering-yourwebcamrecordingbasics/"><u>2024 Approved  Mastering YourWebcam RecordingBasics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-crafting-the-perfect-blend-in-minutes-with-picshot/"><u>In 2024, Crafting the Perfect Blend in Minutes with Picshot</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6s-passcode-screen-by-drfone-ios/"><u>How to Unlock iPhone 6s Passcode Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-blue-screen-wins-unhandled-exception/"><u>How to Address Blue Screen: Win's Unhandled Exception</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-store-issues-address-x80072f17/"><u>Streamlining Windows Store Issues: Address X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-utilizing-apples-messaging-service-on-pc/"><u>Understanding and Utilizing Apple's Messaging Service on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-upgrade-error-0xc004f050/"><u>How to Fix the Windows Upgrade Error 0Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-external-hard-drive-access-in-windows/"><u>Controlling External Hard Drive Access in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-mastering-facebook-video-covers-a-step-by-step-guide-to-sizing/"><u>Updated In 2024, Mastering Facebook Video Covers A Step-by-Step Guide to Sizing</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-why-excel-opens-fail-in-notepad/"><u>Understanding Why Excel Opens Fail in Notepad</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-final-cut-pro-tips-and-tricks-reversing-video-clips-like-a-pro/"><u>Updated In 2024, Final Cut Pro Tips and Tricks Reversing Video Clips Like a Pro</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-bandwidth-gap-between-laptops-phones/"><u>Bridging the Bandwidth Gap Between Laptops, Phones</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-functionality-of-law-filters-for-windows-users/"><u>Decoding the Functionality of LAW Filters for Windows Users</u></a></li>
</ul></div>
