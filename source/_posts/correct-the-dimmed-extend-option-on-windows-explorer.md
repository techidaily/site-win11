---
title: Correct the Dimmed Extend Option on Windows Explorer
date: 2024-06-25T11:22:56.755Z
updated: 2024-06-26T11:22:56.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correct the Dimmed Extend Option on Windows Explorer
excerpt: This Article Describes Correct the Dimmed Extend Option on Windows Explorer
keywords: Fix Windows Explorer Fade,Resolve Dimming Issue,Enhance Window Brightness,Correct Explorer Visibility,Tweak Windows Display,Adjust Explore Shadows,Modify View Extension
thumbnail: https://thmb.techidaily.com/f1ae1ebf673254b46f0a821d8d5736e61a916c4eb6fabc72096593a99e32594f.png
---

## Correct the Dimmed Extend Option on Windows Explorer

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/fixes-for-windows-task-management-addressing-misplaced-cpu-metrics/"><u>Fixes for Windows Task Management: Addressing Misplaced CPU Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/1719350994094-winshift-stuck-heres-how-to-tackle-it/"><u>WinShift Stuck? Here's How to Tackle It</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-for-seamless-windows-android-integration/"><u>Key Apps for Seamless Windows-Android Integration</u></a></li>
<li><a href="https://win11.techidaily.com/grow-windows-capacity-without-file-loss/"><u>Grow Windows Capacity Without File Loss</u></a></li>
<li><a href="https://win11.techidaily.com/managing-your-digital-life-restarting-apps-in-windows-11/"><u>Managing Your Digital Life: Restarting Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vanished-hardware-on-windows/"><u>Resolving Vanished Hardware on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-accessing-your-iis-management-center/"><u>Quick Fixes for Accessing Your IIS Management Center</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-read-only-filters-in-win-os/"><u>Eliminating Read-Only Filters in Win OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-create-a-green-screen-video-in-after-effects/"><u>Updated How To Create A Green Screen Video In After Effects</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-oneplus-ace-2-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On OnePlus Ace 2 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/demystifying-and-decollecting-gopros-fish-eye-photos/"><u>Demystifying & Decollecting GoPro's Fish Eye Photos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-access-youtube-tracks-without-spending-a-dime-25plus-no-cost-audio-extractors/"><u>[New] In 2024, Access YouTube Tracks Without Spending a Dime  25+ No-Cost Audio Extractors</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-xiaomi-redmi-note-12-pro-4g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Xiaomi Redmi Note 12 Pro 4G Phone?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-swiftly-adjust-video-speeds-a-users-guide-to-youtube-features/"><u>[Updated] Swiftly Adjust Video Speeds  A User's Guide to YouTube Features</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-tomtom-bandit-action-camera-review/"><u>In 2024, TomTom Bandit Action Camera Review</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-vivo-x100-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Vivo X100 Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>