---
title: 4 Ways to Delete a Drive Partition on Windows
date: 2024-07-13T11:08:25.379Z
updated: 2024-07-14T11:08:25.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Delete a Drive Partition on Windows
excerpt: This Article Describes 4 Ways to Delete a Drive Partition on Windows
keywords: Windows Drive Deletion,Remove Windows Partition,Clear Windows Drives,Delete Windows Partition,Partition Removal Windows,Wiping Windows Disk Space,Extract Partition on Windows
thumbnail: https://thmb.techidaily.com/61e5e75a143019f7f7c8689be3de97fce55d395ac791171ba491fd10d2883ba4.jpeg
---

## 4 Ways to Delete a Drive Partition on Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/the-artisans-guide-to-animation-enchantment-for-2024/"><u>The Artisan's Guide to Animation Enchantment for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-revolutionize-your-videos-essential-obs-edits-at-hand/"><u>In 2024, Revolutionize Your Videos  Essential OBS Edits at Hand</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/edit-like-a-pro-best-android-video-editor-apps-for-chromebook-users-for-2024/"><u>Edit Like a Pro Best Android Video Editor Apps for Chromebook Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-unveiling-the-secrets-of-vimeo-videos-exploring-aspect-ratio-options-for-2024/"><u>New Unveiling the Secrets of Vimeo Videos Exploring Aspect Ratio Options for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>How To Unlock Apple iPhone 11 Pro Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-ten-essential-cam-covers-to-upgrade-your-security/"><u>[Updated] In 2024, Ten Essential Cam Covers to Upgrade Your Security</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-guide-to-extracting-and-refining-your-audacity-recordings-as-mp3s-for-2024/"><u>New Guide to Extracting and Refining Your Audacity Recordings as MP3s for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leveraging-brand-partnerships-for-youtube-content-creators/"><u>[Updated] Leveraging Brand Partnerships for YouTube Content Creators</u></a></li>
<li><a href="https://games-able.techidaily.com/minecraft-unplugged-secure-and-save-your-spheres/"><u>Minecraft Unplugged: Secure and Save Your Spheres</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-vivo-y17s-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Vivo Y17s to New Phone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/videosnatch-quality-inspector-for-2024/"><u>VideoSnatch Quality Inspector for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-views-prime-seo-equipment-for-videos/"><u>2024 Approved  Elevate Views  Prime SEO Equipment for Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/broadcasting-twitch-to-facebook-friends-easily/"><u>Broadcasting Twitch to Facebook Friends Easily</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-perfect-6-apps-for-private-android-video-capturing/"><u>[Updated] 2024 Approved  Perfect 6 Apps for Private Android Video Capturing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-infinix-hot-40-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Infinix Hot 40 Phone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-zooming-in-on-podcast-quality-an-ultimate-video-recording-guidebook/"><u>In 2024, Zooming In on Podcast Quality  An Ultimate Video Recording Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-flicker-studio-the-complete-lightroom-alternatives-guide/"><u>[Updated] Flicker Studio  The Complete Lightroom Alternatives Guide</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-seamless-synergy-wearable-helps-open-mac-gadgets/"><u>2024 Approved  Seamless Synergy  Wearable Helps Open Mac Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-navigating-the-digital-realm-uploading-with-premiere-and-youtube-for-2024/"><u>[Updated] Navigating the Digital Realm  Uploading with Premiere & YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-excellence-in-separating-silence-and-signal-audio-extraction-from-videos-for-modern-tech/"><u>New Excellence in Separating Silence and Signal Audio Extraction From Videos for Modern Tech</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-performance-gpu-picks-for-quality-video-streaming/"><u>[New] 2024 Approved  High-Performance GPU Picks for Quality Video Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://extra-resources.techidaily.com/photo-memory-locker-at-no-cost-plus-elite-charged-cloud-spheres/"><u>Photo Memory Locker at No Cost, Plus Elite Charged Cloud Spheres</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/watch-over-instagrams-friendship-shifts-for-2024/"><u>Watch Over Instagram's Friendship Shifts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-freedom-in-memories-your-instagrams-savior-for-2024/"><u>[New] Freedom in Memories  Your Instagram's Savior for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
</ul></div>
