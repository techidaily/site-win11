---
title: How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows
date: 2024-06-25T11:45:19.179Z
updated: 2024-06-26T11:45:19.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows
excerpt: This Article Describes How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows
keywords: Fix Gray Volume Extend Option,Resolve Extend Volume Error,Remedy Grayed Volume Control,Correct Extend Button Issue,Address Ext Volume Problem,Solve Grayed Volume Setting,Mend Extension Volume Display
thumbnail: https://thmb.techidaily.com/1d7a3c5b577ddb7940a6a2457c0bee5c40f1807e21452ed2f6065cb51e5a9f16.jpg
---

## How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows

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
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-cannot-open-file-problems-in-win1110/"><u>Mastering the Art of Fixing 'Cannot Open File' Problems in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/no-snip-from-prtscan-how-to-prevent-launch-of-snipping-tool-in-windows-11/"><u>No Snip From PrtScan: How to Prevent Launch of Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-realme-narzo-60x-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Realme Narzo 60x 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-lava-agni-2-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Lava Agni 2 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-insta-facebook-connection-essentials/"><u>[Updated] In 2024, Insta-Facebook Connection Essentials</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/vocalizing-your-visual-content-a-complete-tiktok-manual/"><u>Vocalizing Your Visual Content  A Complete TikTok Manual</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-maintain-your-memories-android-plus-mac-video-preservation-for-2024/"><u>[Updated] Maintain Your Memories  Android + Mac Video Preservation for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-maximize-ms-edge-usage-understanding-and-using-picture-in-picture/"><u>[New] Maximize MS Edge Usage  Understanding and Using Picture-in-Picture</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-editing-videos-on-mac-try-vn-video-editor-or-these-alternatives/"><u>2024 Approved Editing Videos on Mac? Try VN Video Editor or These Alternatives</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-vivo-y27s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-way-of-the-warrior-game-lineup-mirroring-ghost-of-tsushima/"><u>The Way of the Warrior  Game Lineup Mirroring Ghost of Tsushima</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-tecno-pova-5-pro-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Tecno Pova 5 Pro Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>