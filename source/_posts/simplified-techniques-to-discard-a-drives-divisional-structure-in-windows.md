---
title: Simplified Techniques to Discard a Drive's Divisional Structure in Windows
date: 2024-06-25T11:35:38.424Z
updated: 2024-06-26T11:35:38.424Z
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
<li><a href="https://win11.techidaily.com/reliability-monitor-vs-performance-monitor-comparing-two-underutilized-windows-tools/"><u>Reliability Monitor Vs. Performance Monitor: Comparing Two Underutilized Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-wpm-in-windows-11-environments/"><u>Unveiling the Power of WPM in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-meaning-behind-windows-patches/"><u>Unraveling the Meaning Behind Window's Patches</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microphone-settings-in-w11-systems/"><u>Mastering Microphone Settings in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shutdown-of-windows-privacy-tools/"><u>Navigating the Shutdown of Windows Privacy Tools</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-lock-screen-stop-timer-glitch/"><u>Troubleshooting Windows Lock Screen Stop-Timer Glitch</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-xiaomi-mix-fold-3-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Xiaomi Mix Fold 3 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-key-to-effective-instagram-chats-a-comprehensive-guide/"><u>In 2024, The Key to Effective Instagram Chats  A Comprehensive Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-investigating-competitors-to-manycam-better-choices-for-2024/"><u>[Updated] Investigating Competitors to ManyCam  Better Choices for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-how-to-live-stream-to-instagram-from-obs/"><u>[Updated] 2024 Approved  How To Live Stream to Instagram From OBS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-monetization-changes-500-subscribers-now-eligible/"><u>2024 Approved  YouTube Monetization Changes  500 Subscribers Now Eligible</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-complete-imovie-users-manual-on-excising-background-music-from-videos/"><u>New 2024 Approved The Complete iMovie Users Manual on Excising Background Music From Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-review-of-the-immersive-4k-experience-lg-digital-cinema-31mu97-b/"><u>[New] Review of the Immersive 4K Experience - LG Digital Cinema 31MU97-B</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pixel-perfect-free-mobile-photography-booster/"><u>In 2024, Pixel Perfect  Free Mobile Photography Booster</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enhancing-engagement-how-to-utilize-youtubes-prominent-channels-for-2024/"><u>Enhancing Engagement  How to Utilize YouTube's Prominent Channels for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>