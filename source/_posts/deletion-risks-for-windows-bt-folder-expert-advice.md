---
title: "Deletion Risks for Windows ~BT Folder: Expert Advice"
date: 2024-06-25T11:42:33.499Z
updated: 2024-06-26T11:42:33.499Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Deletion Risks for Windows ~BT Folder: Expert Advice"
excerpt: "This Article Describes Deletion Risks for Windows ~BT Folder: Expert Advice"
keywords: Win BT Deletion Risk,Folder Safety Windows,IT BT Delete Tips,Preventing Windows Loss,BT Files Security Guide,Safe Deletion Windows,Protect Windows Folders
thumbnail: https://thmb.techidaily.com/a5dde8e23432eb9faea6481b1841af4ec33dc75da64317f31b7964d607abcd74.jpg
---

## Deletion Risks for Windows ~BT Folder: Expert Advice

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/windows-filing-mastery-key-principles-max-156/"><u>Windows Filing Mastery: Key Principles (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-yuzu-gameplay-speed/"><u>Amplify Your Yuzu Gameplay Speed</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-dormant-pane-windows-6-tips-for-win11-users/"><u>Triggering Dormant Pane Windows: 6 Tips for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-windows-11-mailcalendar/"><u>Quick Guide: Resetting Windows 11 Mail/Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-managing-directories-without-renaming-feature-in-win-11/"><u>The Ultimate Guide to Managing Directories Without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-the-best-of-the-best-12-top-online-animation-makers-for-professionals/"><u>New In 2024, The Best of the Best 12 Top Online Animation Makers for Professionals</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-enhance-imagery-with-elegant-borders-ig-edition-for-2024/"><u>[New] Enhance Imagery with Elegant Borders – IG Edition for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/inside-the-world-of-funimate-gamers/"><u>Inside the World of Funimate Gamers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/itel-p40-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel P40 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gamers-dream-the-ultimate-compilation-of-best-yt-game-entrances/"><u>[Updated] In 2024, Gamer's Dream  The Ultimate Compilation of Best YT Game Entrances</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-premium-terraria-enhancements-guide/"><u>[Updated] Premium Terraria Enhancements Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-seamlessly-integrate-into-others-tiktok-livestreams-for-2024/"><u>[New] Seamlessly Integrate Into Others’ TikTok Livestreams for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-spark-social-media-flames-facebook-success-hacks/"><u>[Updated] In 2024, Spark Social Media Flames  Facebook Success Hacks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-audio-ambition-selecting-top-6-free-downloader-apps-from-youtube-vaults/"><u>[New] Audio Ambition  Selecting Top 6 Free Downloader Apps From YouTube Vaults</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/stopping-auto-capture-in-apples-recorder-for-2024/"><u>Stopping Auto-Capture in Apple's Recorder for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>