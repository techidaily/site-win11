---
title: "Deleting Windows ~BT Directory: Purpose & Process"
date: 2024-06-25T11:28:53.861Z
updated: 2024-06-26T11:28:53.861Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boost-budget-efficiency-windows-11-pro-discounts/"><u>Boost Budget Efficiency: Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-google-play-on-w11-os/"><u>Guide: Setting Up Google Play on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-note-apps-for-the-modern-windows-slates/"><u>Perfect Note Apps for the Modern Windows Slates</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-dxgierror-windows-devices-reattached/"><u>Combat the DXGI_ERROR: Windows Devices Reattached</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-uncover-hidden-system-startups/"><u>Tips to Uncover Hidden System Startups</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-windows-0x80242016-update-fails/"><u>Navigating Past Windows' 0X80242016 Update Fails</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/igtv-vs-youtube-unveiling-key-distinctions-and-best-platform-for-sharing/"><u>IGTV Vs. YouTube  Unveiling Key Distinctions & Best Platform for Sharing</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-find-game-sound-effects-for-2024/"><u>New Find Game Sound Effects for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-pivotal-role-of-thumbnails-in-video-success-stories/"><u>[New] In 2024, The Pivotal Role of Thumbnails in Video Success Stories</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-a-professionals-primer-to-perfecting-picture-colors/"><u>[New] A Professional's Primer to Perfecting Picture Colors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-media-showdown-twitters-top-tiktok-trends-for-2024/"><u>[New] Social Media Showdown  Twitters' Top TikTok Trends for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-efficient-recording-capture-your-dell-display-swiftly/"><u>2024 Approved  Efficient Recording  Capture Your Dell Display Swiftly</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-pro-video-guide-crafting-engaging-screencasts/"><u>[Updated] In 2024, Pro Video Guide  Crafting Engaging Screencasts</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/culinary-chronicles-global-eats-showcased-by-tiktok-for-2024/"><u>Culinary Chronicles  Global Eats Showcased by TikTok for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-constructing-mc-neighborhoods/"><u>[New] In 2024, The Ultimate Guide to Constructing MC Neighborhoods</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-country-on-app-store-for-iphone-14-plus-with-7-methods-by-drfone-ios/"><u>How To Change Country on App Store for iPhone 14 Plus With 7 Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>