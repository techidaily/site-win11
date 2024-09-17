---
title: The Fourfold Approach to Discarding Partition on Windows Systems
date: 2024-09-13T08:38:34.931Z
updated: 2024-09-17T00:49:22.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Fourfold Approach to Discarding Partition on Windows Systems
excerpt: This Article Describes The Fourfold Approach to Discarding Partition on Windows Systems
keywords: WIN_PartitionDiscard,WindowsPartitionMethod,SystemFourApproaches,DiscardWindowsPartitions,FourfoldPartitionTechniques,PartitionFreeWindows,EliminateWinPartitioning
thumbnail: https://thmb.techidaily.com/a4dc30780e032f6d710992cf5481b7eec2d5a638075023e09360ad01372b41d6.jpg
---

## The Fourfold Approach to Discarding Partition on Windows Systems

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114264/17093" target="_top" id="2114264">
  <img src="//a.impactradius-go.com/display-ad/17093-2114264" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114264/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-streamlining-your-instagram-video-experience/"><u>[Updated] 2024 Approved Streamlining Your Instagram Video Experience</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-navigating-steam-with-your-switch-pro-controller-for-2024/"><u>[Updated] Navigating Steam With Your Switch Pro Controller for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-reversing-frozen-dark-theme-on-computers/"><u>A Guide to Reversing Frozen Dark Theme on Computers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ace-your-shoots-with-the-top-ranking-dji-mavic-2-pro-examined-by-experts/"><u>Ace Your Shoots with the Top-Ranking DJI Mavic 2 Pro Examined by Experts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-convincing-movie-markers/"><u>Crafting Convincing Movie Markers</u></a></li>
<li><a href="https://win11.techidaily.com/enigmatic-toolbars-windows-11s-invisible-commands/"><u>Enigmatic Toolbars: Windows 11’S Invisible Commands</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-epic-games-launcher-login-issues-on-windows/"><u>How to Fix Epic Games Launcher Login Issues on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/identifying-top-memory-consuming-apps-on-your-android-device/"><u>Identifying Top Memory-Consuming Apps on Your Android Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/prevent-recurring-amd-driver-failures/"><u>Prevent Recurring AMD Driver Failures</u></a></li>
<li><a href="https://win11.techidaily.com/prove-to-users-you-care-with-these-8-windows-customizations/"><u>Prove to Users You Care with These 8 Windows Customizations</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-successful-microsoft-store-app-setup/"><u>Steps for Successful Microsoft Store App Setup</u></a></li>
<li><a href="https://facebook.techidaily.com/top-4-tricks-for-finding-exciting-online-communities/"><u>Top 4 Tricks for Finding Exciting Online Communities</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-microphone-settings-on-windows-os/"><u>Unveiling Microphone Settings on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-grandparents-windows-pc-for-seniors/"><u>Upgrading Grandparents' Windows PC for Seniors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    