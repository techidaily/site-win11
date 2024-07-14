---
title: "Risks & Precautions: Deleting Windows ~BT Folder"
date: 2024-07-13T10:55:36.155Z
updated: 2024-07-14T10:55:36.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Risks & Precautions: Deleting Windows ~BT Folder"
excerpt: "This Article Describes Risks & Precautions: Deleting Windows ~BT Folder"
keywords: BT Folder Delete Risks,Windows Safe Deletion,Secure Data Removal,Avoiding Data Leakage,Preventing BT Data Loss,Cleanup Windows Safely,Protecting Privacy Post-Deletion
thumbnail: https://thmb.techidaily.com/b478b0983a67f36010d885714312f70db32d5d3a2179d68b62f5c8d46f0ea38e.jpg
---

## Risks & Precautions: Deleting Windows ~BT Folder

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-steps-to-clear-up-steam-errors-in-games-on-windows/"><u>Immediate Steps to Clear Up Steam Errors in Games on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-perplexity-of-blued-in-windows-10/"><u>Overcoming the Perplexity of Blued in Windows 10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-powerful-relationships-through-strategic-social-media-engagement/"><u>Building Powerful Relationships Through Strategic Social Media Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-window-11-wallpaper-settings-for-individual-monitors/"><u>Navigating Window 11 Wallpaper Settings for Individual Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/making-older-computers-more-comfortable-for-seniors/"><u>Making Older Computers More Comfortable for Seniors</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-prime-tools-for-pro-video-creation-on-android-windows/"><u>2024 Approved  Prime Tools for Pro Video Creation on Android, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-windows-error-0xc0000001/"><u>Overcoming the Challenge of Windows Error 0XC0000001</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-keyboard-kings-and-queens-a-premium-free-royalty-free-collection-of-film-ready-piano-soundtracks/"><u>In 2024, Keyboard Kings & Queens A Premium, Free Royalty-Free Collection of Film-Ready Piano Soundtracks</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-best-free-video-hosting-services-for-personal-and-professional-use/"><u>2024 Approved 10 Best Free Video Hosting Services for Personal and Professional Use</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-privacy-first-securely-document-your-fb-video-conversations/"><u>[New] Privacy First  Securely Document Your FB Video Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resurrect-inactive-windows-email-rule-configurations/"><u>Methods to Resurrect Inactive Windows Email Rule Configurations</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-value-oriented-pc-screen-recorders/"><u>[New] Value-Oriented PC Screen Recorders</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/hing-into-youtube-success-a-starter-guide-for-profit/"><u>Launching Into Youtube Success  A Starter Guide for Profit</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-windows-update-stuck-at-100-here-are-6-fixes/"><u>Is Your Windows Update Stuck at 100%%? Here Are 6 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-barriers-reviving-spotify-streams/"><u>Overcoming Network Barriers: Reviving Spotify Streams</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-2017-data-overload-infographics-and-surprising-yt-stats/"><u>[Updated] 2017 Data Overload  Infographics & Surprising YT Stats</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-admin-imposed-setup-barriers/"><u>How to Tackle Windows 'Admin-Imposed' Setup Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/make-the-best-out-of-what-you-have-even-without-11/"><u>Make the Best Out of What You Have, Even Without 11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-oppo-find-n3-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hyper-v-installation-on-w11-home-edition/"><u>Mastering Hyper-V Installation on W11 Home Edition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-trending-rap-anthems-from-tiktok-stars-for-2024/"><u>[New] Trending Rap Anthems From TikTok Stars for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-complete-guide-to-audio-editing-in-audacity-made-simple/"><u>In 2024, The Complete Guide to Audio Editing in Audacity, Made Simple</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-facebook-verification-how-to-get-the-blue-verified-badge-easily/"><u>[New] In 2024, Facebook Verification  How to Get the Blue Verified Badge (Easily)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-file-system-errors-in-windows-10-and-11/"><u>How to Fix File System Errors in Windows 10 & 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/digital-delinquency-games-comparable-to-gta-v-for-2024/"><u>Digital Delinquency  Games Comparable to GTA V for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-discords-top-10-where-to-date-and-love/"><u>[Updated] Discord's Top 10  Where to Date and Love</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-multi-object-tracking-the-ultimate-guide/"><u>In 2024, Multi Object Tracking The Ultimate Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-the-ultimate-guide-to-earning-more-followers-and-likes-on-tiktok/"><u>In 2024, The Ultimate Guide to Earning More Followers and Likes on TikTok</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-how-to-organize-photo-album-on-iphone-and-icloud/"><u>[Updated] In 2024, How To Organize Photo Album On iPhone And iCloud</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-tecno-phantom-v-fold-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Tecno Phantom V Fold? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-low-resource-utilization-wlanextexe/"><u>Mastering Low Resource Utilization: Wlanext.EXE</u></a></li>
</ul></div>
