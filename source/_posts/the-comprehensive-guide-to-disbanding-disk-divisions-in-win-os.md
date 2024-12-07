---
title: The Comprehensive Guide to Disbanding Disk Divisions in Win OS
date: 2024-11-30T06:33:34.474Z
updated: 2024-12-07T11:23:57.614Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Comprehensive Guide to Disbanding Disk Divisions in Win OS
excerpt: This Article Describes The Comprehensive Guide to Disbanding Disk Divisions in Win OS
keywords: Win OS File Division Terms,Disbanding Disk Partitions,Windows OS Directory Disassembly,Deleting Disk Volumes (Win),Win OS Divisional Removal Guide,Clearing Drives in WinOS,Ending Disk Segments in Windows
thumbnail: https://thmb.techidaily.com/8eb93e1b1b19fd0df7a5c4a69b010fd291b98c2d5042e30f7996e1ded01bfda5.jpg
---

## The Comprehensive Guide to Disbanding Disk Divisions in Win OS

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-mastering-mobile-asmr-must-have-apps/"><u>[Updated] 2024 Approved Mastering Mobile ASMR Must-Have Apps</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-streamlining-profits-how-ajay-maximizes-youtube-earnings/"><u>[Updated] In 2024, Streamlining Profits How AJay Maximizes YouTube Earnings</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-linking-giants-a-step-by-step-guide-to-merging-instagram-and-tiktok/"><u>[Updated] Linking Giants A Step-by-Step Guide to Merging Instagram and TikTok</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-sidestep-personalized-podcast-suggestions-in-spotify/"><u>2024 Approved Sidestep Personalized Podcast Suggestions in Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/designing-safe-quick-access-tool-for-hardware-in-win11/"><u>Designing Safe, Quick Access Tool for Hardware in Win11</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-realme-gt-neo-5-se-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Realme GT Neo 5 SE Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/inside-look-how-lg-products-reach-consumers-through-various-channels/"><u>Inside Look: How LG Products Reach Consumers Through Various Channels</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-norm-keyboard-shortcuts-to-optimize-windows/"><u>Navigating the Norm: Keyboard Shortcuts to Optimize Windows</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/2550779-9781250070074-os-little-guide-to-starting-over/"><u>O's Little Guide to Starting Over | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-steam-sync-errors-on-pc/"><u>Rectifying Steam Sync Errors on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-new-look-of-windows-11-admin-panel/"><u>The New Look of Windows 11 Admin Panel</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-workflow-windows-11s-elite-selection-of-widgets/"><u>Transform Your Workflow: Windows 11'S Elite Selection of Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-resolving-total-war-saga-troy-stability-problems-on-windowspc/"><u>Troubleshooting Guide: Resolving Total War Saga: Troy Stability Problems on Windows/PC</u></a></li>
</ul></div>

