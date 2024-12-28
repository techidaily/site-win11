---
title: Restore Color to Extended Volume Option in Disk Management
date: 2024-12-22T06:27:46.872Z
updated: 2024-12-27T19:39:07.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restore Color to Extended Volume Option in Disk Management
excerpt: This Article Describes Restore Color to Extended Volume Option in Disk Management
keywords: Restore Color Disks,VolOption Revive,ExtVolume Hue Fix,ManageDisc Refresh,DiskColour Repair,ExtVolColor Update,Volume Palette Restore
thumbnail: https://thmb.techidaily.com/9dc3437ed1a0c4e12ecf0fe73c74b8d72b51654a1b0d3ea6af6735c5a10c75f4.jpg
---

## Restore Color to Extended Volume Option in Disk Management

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-seamless-methodology-viewing-favorited-and-well-liked-youtube-remarks/"><u>[New] 2024 Approved Seamless Methodology Viewing Favorited and Well-Liked YouTube Remarks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-disrupt-bot-patterns-for-natural-viewer-increase/"><u>[Updated] In 2024, Disrupt Bot Patterns for Natural Viewer Increase</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-vegas-pro-gambit-unveiled-a-21-comprehensive-review/"><u>2024 Approved Vegas Pro Gambit Unveiled A '21 Comprehensive Review</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-tecno-spark-20-proplus-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Tecno Spark 20 Pro+ via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-effortless-photo-combinations-picshots-way/"><u>Discover Effortless Photo Combinations - Picshot's Way</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-when-your-media-device-wont-connect-to-windows-system/"><u>Easy Fixes When Your Media Device Won’t Connect to Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/edges-steady-cycle-managing-on-windows-11/"><u>Edge's Steady Cycle: Managing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-tab-integrity-in-explorer/"><u>Ensuring Continuous Tab Integrity in Explorer</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/expert-reviews-the-most-effective-storm-chasing-tools-for-navigating-2024/"><u>Expert Reviews: The Most Effective Storm Chasing Tools for Navigating 2024</u></a></li>
<li><a href="https://win11.techidaily.com/extending-windows-10-shutdown-time-tips-for-active-tasks/"><u>Extending Windows 10 Shutdown Time: Tips for Active Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fix-a-non-responsive-login-screen-in-windows-1011/"><u>Guide to Fix a Non-Responsive Login Screen in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stopping-discord-initial-launch-and-updates-on-windows/"><u>Guide: Stopping Discord Initial Launch & Updates on Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Poco C55? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-plugged-in-but-not-charging-problems-on-your-microsoft-surface/"><u>Solving Plugged In But Not Charging Problems on Your Microsoft Surface</u></a></li>
<li><a href="https://win11.techidaily.com/the-ins-and-outs-of-windows-11-calendar-interface/"><u>The Ins and Outs of Windows 11 Calendar Interface</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-stuck-exe-files-in-windows-systems/"><u>Unlocking Stuck .exe Files in Windows Systems</u></a></li>
</ul></div>

