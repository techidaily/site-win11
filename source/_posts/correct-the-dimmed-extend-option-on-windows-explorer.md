---
title: Correct the Dimmed Extend Option on Windows Explorer
date: 2024-06-25T09:43:47.394Z
updated: 2024-06-26T09:43:47.394Z
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
<li><a href="https://win11.techidaily.com/essential-note-taking-software-the-winning-seven/"><u>Essential Note-Taking Software: The Winning Seven</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-limited-use-of-chatgpt-in-pc/"><u>Optimizing Limited Use of ChatGPT in PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-device-stall-code-0x887a0006-guide/"><u>Fixing Device Stall: Code 0X887A0006 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unknown-value-issue-in-windows-tech-environment/"><u>Remedy for Unknown Value Issue in Windows Tech Environment</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-windows-11-logins-restoration/"><u>Mastering Quick Windows 11 Logins Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-fix-rpc-fails-on-your-pc/"><u>Master Plan to Fix RPC Fails on Your PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-maximize-networking-with-fb-link-downloader-tools/"><u>[New] Maximize Networking with FB Link Downloader Tools</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-nokia-130-music-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Nokia 130 Music in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-imagepurityplus-professional-photo-editing-suite/"><u>2024 Approved  ImagePurityPlus  Professional Photo Editing Suite</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-shopping-highlights-editing-steps-for-hauls-and-collections/"><u>[New] 2024 Approved  Shopping Highlights  Editing Steps for Hauls & Collections</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-photographers-manual-how-to-crop-images-seamlessly-online-for-2024/"><u>The Photographer's Manual  How To Crop Images Seamlessly Online for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-top-10-video-editing-solutions-for-creators/"><u>Updated In 2024, The Top 10 Video Editing Solutions for Creators</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-tecno-camon-30-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-10-android-and-ios-timers-for-effortless-wedding-countdown-management/"><u>[Updated] Top 10 Android and iOS Timers for Effortless Wedding Countdown Management</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-stand-out-strategy-carving-a-niche-on-tiktoks-map/"><u>[Updated] Stand Out Strategy  Carving a Niche on TikTok's Map</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>