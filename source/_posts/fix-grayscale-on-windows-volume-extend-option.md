---
title: Fix Grayscale on Windows' Volume Extend Option
date: 2024-10-11T18:08:36.121Z
updated: 2024-10-15T20:44:38.401Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Grayscale on Windows' Volume Extend Option
excerpt: This Article Describes Fix Grayscale on Windows' Volume Extend Option
keywords: Fix Grayscale,Windows Volume,Extend Volume,Resolve Issue,Volume Adjustment,Display Correction,Windows Settings
thumbnail: https://thmb.techidaily.com/a50a3cec0521fa6fb800284717c9122c07291a0277fd1f77229ad231586b5b14.jpg
---

## Fix Grayscale on Windows' Volume Extend Option

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the wizard completes, you will see the partition size has been increased.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-the-ultimate-guide-to-beauty-channels-your-step-by-step-blueprint/"><u>[New] 2024 Approved The Ultimate Guide to Beauty Channels Your Step-By-Step Blueprint</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-3-part-blueprint-to-monitor-and-maximize-your-youtube-profits-for-2024/"><u>[Updated] 3-Part Blueprint to Monitor and Maximize Your YouTube Profits for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-leveraging-free-luts-a-pathway-to-improved-obs-streaming/"><u>[Updated] In 2024, Leveraging Free LUTs A Pathway to Improved OBS Streaming</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-samsung-galaxy-s24-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/apple-watch-variants-explored-navigating-with-gps-or-opting-for-cellular-service/"><u>Apple Watch Variants Explored: Navigating with GPS or Opting for Cellular Service</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-0x8007045d-crash-code-from-your-windows-11-system/"><u>Eliminating 0X8007045d Crash Code From Your Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-bad-sectors-in-windows-hardware/"><u>Fixing Bad Sectors in Windows Hardware</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-iphone-11-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On iPhone 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-android-gaming-on-win-11-via-google-play-services/"><u>Mastering Android Gaming on Win 11 via Google Play Services</u></a></li>
<li><a href="https://windows11.techidaily.com/raising-the-roar-the-top-4-apps-to-boost-windows-decibels-over-limit/"><u>Raising the Roar: The Top 4 Apps to Boost Windows’ Decibels Over Limit</u></a></li>
<li><a href="https://some-approaches.techidaily.com/rapid-fire-creation-of-google-collage-photos-for-2024/"><u>Rapid-Fire Creation of Google Collage Photos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-dormant-thermal-regulation-protocol-in-windows/"><u>Repairing Dormant Thermal Regulation Protocol in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-of-unrecognized-usb-drives-in-minutes/"><u>Solving the Mystery of Unrecognized USB Drives in Minutes!</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-install-failure-of-oculus-vr-for-win11win10/"><u>Steps to Fix Install Failure of Oculus VR for Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-the-essential-guide-to-disk-defrag-in-win11/"><u>Streamlining Storage: The Essential Guide to Disk Defrag in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    