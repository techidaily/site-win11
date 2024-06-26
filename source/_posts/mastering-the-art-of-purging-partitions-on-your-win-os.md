---
title: Mastering the Art of Purging Partitions on Your Win OS
date: 2024-06-25T11:43:23.431Z
updated: 2024-06-26T11:43:23.431Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Purging Partitions on Your Win OS
excerpt: This Article Describes Mastering the Art of Purging Partitions on Your Win OS
keywords: Win OS Partition Cleanup,Windows Partitions Optimization,Data Wiping for Windows Systems,Clearing Disk Space in Win OS,Effective Partition Purging on WINOS,Master Partition Management for Windows,Secure Partition Deletion in Windows OS,Mastering Win OS Partitions,Purging Partitions Securely
thumbnail: https://thmb.techidaily.com/c3ba901f926249b24c063d003163e0cc5d148f0772ca21d903055c2189241e19.jpg
---

## Mastering the Art of Purging Partitions on Your Win OS

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
<li><a href="https://win11.techidaily.com/windows-revenue-strategies-for-microsofts-profits/"><u>Windows Revenue Strategies for Microsoft's Profits</u></a></li>
<li><a href="https://win11.techidaily.com/novices-guide-to-folder-fabrication-in-win11/"><u>Novice's Guide to Folder Fabrication in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-enable-razer-recognition-by-synapse/"><u>How to Re-Enable Razer Recognition by Synapse</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-lock-screen-stop-timer-glitch/"><u>Troubleshooting Windows Lock Screen Stop-Timer Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-interruptnothandled-error-on-win11/"><u>Eliminating the INTERRUPT_NOT_HANDLED Error on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-code-0x80d03801-in-microsoft-store-on-windows-pc/"><u>How to Fix Error Code 0X80d03801 in Microsoft Store on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/expanding-your-expression-methods-for-adapting-your-natural-voice/"><u>Expanding Your Expression Methods for Adapting Your Natural Voice</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-10-popular-cartoon-characters-that-you-wont-want-to-miss-for-2024/"><u>Updated 10 Popular Cartoon Characters That You Wont Want to Miss for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Samsung Galaxy S24+? | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-mastering-the-art-of-embedding-melodies-in-windows-gifs/"><u>In 2024, Mastering the Art of Embedding Melodies in Windows GIFs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-a-beginners-blueprint-for-iphone-reflection-photography/"><u>In 2024, A Beginner's Blueprint for iPhone Reflection Photography</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-change-youtube-playback-speed-to-speed-up-or-slow-down-video/"><u>[Updated] 2024 Approved  How to Change YouTube Playback Speed to Speed Up or Slow Down Video</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unveiling-youtube-analytics-a-beginners-guide/"><u>Unveiling YouTube Analytics  A Beginner's Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-trailblazing-through-time-era-images-explore-3-inverse-techniques-on-facebook/"><u>In 2024, Trailblazing Through Time-Era Images  Explore 3 Inverse Techniques on Facebook</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-vibrations-and-beeps-unveiling-the-sonic-signatures-of-buttons-for-2024/"><u>New Vibrations & Beeps Unveiling the Sonic Signatures of Buttons for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-realme-c51-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Realme C51 FRP In 3 Different Ways</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>