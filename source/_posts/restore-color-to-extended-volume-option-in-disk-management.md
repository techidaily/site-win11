---
title: Restore Color to Extended Volume Option in Disk Management
date: 2024-12-16T17:49:04.910Z
updated: 2024-12-22T16:15:26.844Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-bandicam-revisited-a-deep-dive-into-screen-recording/"><u>[Updated] 2024 Approved Bandicam Revisited A Deep Dive Into Screen Recording</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-secure-survival-housing-in-minecraft/"><u>[Updated] Secure Survival Housing in Minecraft</u></a></li>
<li><a href="https://win-forum.techidaily.com/convertissez-gratuitement-un-fichier-ts-en-format-mov-en-ligne-avec-movavi/"><u>Convertissez Gratuitement Un Fichier .TS en Format .MOV en Ligne Avec Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unresponsive-windows-11-expert-advice-for-resolution/"><u>Dealing with Unresponsive Windows 11: Expert Advice for Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/from-fuchsia-to-functional-8-fixes-for-windows-color-issues/"><u>From Fuchsia to Functional: 8 Fixes for Windows Color Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-volume-mixer-in-the-action-center-in-windows-11/"><u>How to Enable the Volume Mixer in the Action Center in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-nokia-xr21-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Nokia XR21 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-measures-to-mend-ms-store-malfunctions-in-windows-os/"><u>Masterful Measures to Mend MS Store Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-gpo-report-generation-via-gpresult/"><u>Mastering GPO Report Generation via GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/quick-methods-to-nullify-laptops-built-in-input-device/"><u>Quick Methods to Nullify Laptop's Built-In Input Device</u></a></li>
<li><a href="https://win-able.techidaily.com/1723013312389-troubleshoot-fortnite-sign-in-problems-fast-fixes-to-get-you-playing/"><u>Troubleshoot Fortnite Sign-In Problems - Fast Fixes to Get You Playing!</u></a></li>
</ul></div>

