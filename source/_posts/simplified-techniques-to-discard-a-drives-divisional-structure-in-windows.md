---
title: Simplified Techniques to Discard a Drive's Divisional Structure in Windows
date: 2024-06-25T10:24:12.211Z
updated: 2024-06-26T10:24:12.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplified Techniques to Discard a Drive's Divisional Structure in Windows
excerpt: This Article Describes Simplified Techniques to Discard a Drive's Divisional Structure in Windows
keywords: Remove Drive Division in Windows,Simplify Drives Division Removal,Easy Drive Structural Cleanse,Unlocking Windows Drive Layout,Divide-Free Windows Storage,Clear Windows Drive Hierarchy,Streamline Drive Segregation
thumbnail: https://thmb.techidaily.com/72d87bf38b3f988e318217c000305d7e3da283a047b864a8cf5c572968e745b4.jpg
---

## Simplified Techniques to Discard a Drive's Divisional Structure in Windows

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/regaining-control-over-icon-placement/"><u>Regaining Control Over Icon Placement</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-write-error-in-windows-11-os/"><u>Resolving File Write Error in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-increase-win11-icons-size/"><u>Techniques to Increase Win11 Icons Size</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manage-windows-user-accounts-via-the-command-prompt/"><u>How to Manage Windows User Accounts via the Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-finding-the-balance-adding-videos-to-text-on-a-budget/"><u>[Updated] In 2024, Finding the Balance  Adding Videos to Text on a Budget</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-unlocking-ideal-image-proportions-calculation-and-adjustment-tips/"><u>Updated Unlocking Ideal Image Proportions Calculation and Adjustment Tips</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-ultimate-guide-to-clean-recording-empower-your-soundscape-via-wondershare-filmora/"><u>New 2024 Approved The Ultimate Guide to Clean Recording Empower Your Soundscape via Wondershare Filmora</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-essential-tips-for-twitpic-uploads/"><u>In 2024, Essential Tips for Twitpic Uploads</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-top-15-snapchat-sharing-tactics-for-maximum-impact/"><u>[Updated] 2024 Approved  Top 15 Snapchat Sharing Tactics for Maximum Impact</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-the-best-podcast-platforms-for-your-mac-for-2024/"><u>Explore the Best Podcast Platforms for Your Mac for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-overcome-artificial-watches-for-natural-views/"><u>[Updated] 2024 Approved  Overcome Artificial Watches for Natural Views</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>