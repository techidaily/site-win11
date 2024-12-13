---
title: Restore Color to Extended Volume Option in Disk Management
date: 2024-12-11T19:39:07.417Z
updated: 2024-12-13T05:49:54.008Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-boosting-youtube-descriptions-with-expert-templates/"><u>[New] In 2024, Boosting YouTube Descriptions with Expert Templates</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-insider-look-at-youtube-revenue-policies/"><u>[New] Insider Look at YouTube Revenue Policies</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-prime-list-of-affordable-high-definition-cameras/"><u>[New] Prime List of Affordable High Definition Cameras</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-decoding-how-to-effectively-swap-photo-genders-online-a-comprehensive-approach/"><u>[Updated] In 2024, Decoding How to Effectively Swap Photo Genders Online A Comprehensive Approach</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/ctrlplusz-untuk-membatalkan-fail-rate-tebal-langkah-langkah-perbaikan-terpadu/"><u>Ctrl+Z Untuk Membatalkan Fail Rate Tebal - Langkah-Langkah Perbaikan Terpadu</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-vivo-t2-pro-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Vivo T2 Pro 5G</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pathway-to-choosing-between-game-and-studio-nvidia-drivers/"><u>Personalized Pathway to Choosing Between Game and Studio Nvidia Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-older-bios-setup-elements/"><u>Refreshing Older BIOS Setup Elements</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-access-preventing-read-only-windows-folders/"><u>Secure File Access: Preventing Read-Only Windows Folders</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/streamerease-screen-recording-on-win11-for-2024/"><u>StreamerEase Screen Recording on Win11 for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamlining-communication-integrating-chatgpt-into-virtual-work-sessions/"><u>Streamlining Communication: Integrating ChatGPT Into Virtual Work Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-photoshop-performance-issues/"><u>Streamlining Windows Photoshop Performance Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-in-windows-cmd/"><u>Unlock Full Control in Windows CMD</u></a></li>
<li><a href="https://win11.techidaily.com/windows-1011-reimagined-establishing-personalized-pin-patterns/"><u>Windows 10/11 Reimagined: Establishing Personalized Pin Patterns</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    