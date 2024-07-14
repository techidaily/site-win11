---
title: "Deleting Windows ~BT Directory: Purpose & Process"
date: 2024-07-13T10:07:45.578Z
updated: 2024-07-14T10:07:45.578Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Deleting Windows ~BT Directory: Purpose & Process"
excerpt: "This Article Describes Deleting Windows ~BT Directory: Purpose & Process"
keywords: BT Window Deletion Guide,Windows BT Delete Steps,Purpose of Windows BT Removal,How to Remove BT Files in Win,BT Directory Process Explained,Windows BT Clearance Procedure,Understanding BT Windows Cleanup
thumbnail: https://thmb.techidaily.com/82946b1471bda0a94f0756d1b1276fee19eddaa4566634791522addb362bdc3b.jpg
---

## Deleting Windows ~BT Directory: Purpose & Process

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
<li><a href="https://win11.techidaily.com/fixes-for-frozen-windows-volume-backup-service/"><u>Fixes for Frozen Windows Volume Backup Service</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-samsung-galaxy-s23-fe-frp-bypass-by-drfone-android/"><u>In 2024, About Samsung Galaxy S23 FE FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-youtube-creator-studio-vs-youtube-studio-beta-for-2024/"><u>[Updated] YouTube Creator Studio Vs. YouTube Studio (Beta) for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-seamless-tutorial-for-image-background-cleanup-on-canva/"><u>[New] The Seamless Tutorial for Image Background Cleanup on Canva</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-audio-output-on-microsofts-read-aloud-functionality/"><u>Resetting Audio Output on Microsoft's Read Aloud Functionality</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/key-tips-for-configuring-and-measuring-effective-fb-instream-ads/"><u>Key Tips for Configuring and Measuring Effective FB Instream Ads</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fall-guys-network-woes-on-windows-systems/"><u>Mastering Fall Guys Network Woes on Windows Systems</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-verify-your-youtube-account-a-simple-guide/"><u>[New] 2024 Approved  How to Verify Your YouTube Account - a Simple Guide</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-unlock-the-power-of-microsoft-video-editor-windows-video-editing-tips-and-tricks-for-2024/"><u>New Unlock the Power of Microsoft Video Editor Windows Video Editing Tips and Tricks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/installation-triumph-fixed-mspm-in-windows-10/"><u>Installation Triumph: Fixed MSPM in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-calendar-a-step-by-step-guide/"><u>Mastering Windows 11 Calendar: A Step-by-Step Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-clandestine-snapsnapper-concealed-techniques-for-image-capturing-for-2024/"><u>[New] Clandestine SnapSnapper  Concealed Techniques for Image Capturing for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-realme-12-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Realme 12 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/advance-repair-for-bad-and-corrupt-video-files-of-xiaomi-redmi-a2-by-stellar-video-repair-mobile-video-repair/"><u>Advance Repair for Bad and Corrupt Video Files of Xiaomi Redmi A2</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-fatal-glitches-fixing-xbox-game-pass-error-0x00000001-in-windows-11/"><u>How to Eliminate Fatal Glitches: Fixing Xbox Game Pass Error 0X00000001 in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-iphone-tips-for-time-dilation-in-videography-for-2024/"><u>[New] IPhone Tips for Time-Dilation in Videography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/boosting-instagram-video-speed-onlinemobile/"><u>Boosting Instagram Video Speed Online/Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-obs-studio-unable-to-record-audio-on-windows-11-try-these-fixes/"><u>Is OBS Studio Unable to Record Audio on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-meizu-21-pro-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Meizu 21 Pro to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-personalize-wins-standard-cli-application/"><u>How To Personalize Win’s Standard CLI Application</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-your-guide-to-exceptional-online-marketing-savor-our-selection-of-50-free-ads/"><u>[New] 2024 Approved  Your Guide to Exceptional Online Marketing – Savor Our Selection of 50 FREE Ads</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-mac-video-editing-made-easy-download-splice/"><u>Updated Mac Video Editing Made Easy Download Splice</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-connection-issue-on-windows-os/"><u>Fixing No Connection Issue on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfecting-the-look-a-guide-to-haul-video-post-production/"><u>In 2024, Perfecting the Look  A Guide to Haul Video Post-Production</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-meizu-21-by-drfone-android/"><u>In 2024, How to Bypass FRP from Meizu 21?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
</ul></div>
