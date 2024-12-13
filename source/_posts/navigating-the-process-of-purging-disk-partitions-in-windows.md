---
title: Navigating the Process of Purging Disk Partitions in Windows
date: 2024-12-05T23:03:30.242Z
updated: 2024-12-13T06:23:03.519Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Process of Purging Disk Partitions in Windows
excerpt: This Article Describes Navigating the Process of Purging Disk Partitions in Windows
keywords: Delete Disk Space Efficiently,Partition Cleanup Steps,WIN Disk Space Management,Removing Unnecessary Parts,Purging Windows Disk Partitions,Optimize Free Storage Space,Simplify Disk Organization
thumbnail: https://thmb.techidaily.com/57ebcefbd038d5518117756c100dd6989f85e0e6cff4615a7e12084a4473983a.jpg
---

## Navigating the Process of Purging Disk Partitions in Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-no-download-necessary-youtube-to-gif-conversion-made-easy/"><u>[New] No Download Necessary YouTube-to-GIF Conversion Made Easy</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/echniques-for-selective-youtube-video-downloading/"><u>[New] Techniques for Selective YouTube Video Downloading</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unleash-the-power-of-instagram-footage-a-compilation-of-mp4-conversion-tools-for-pc-and-mac/"><u>[New] Unleash the Power of Instagram Footage A Compilation of MP4 Conversion Tools for PC & Mac</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-pubg-savings-on-windows-1011-a-step-by-step-guide/"><u>Ensuring PUBG Savings on Windows 10/11: A Step-by-Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/expert-analysis-of-leading-android-video-editor-software-choices-featuring-movavi-insights/"><u>Expert Analysis of Leading Android Video Editor Software Choices Featuring Movavi Insights</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-updater-failure-code-0x8024a205/"><u>Fixing Updater Failure: Code 0X8024a205</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-secure-boot-and-tpm-control-in-virtualbox/"><u>Guiding You Through Secure Boot & TPM Control in VirtualBox</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/high-quality-video-editing-by-metehan-kanmaz-with-movavi/"><u>High-Quality Video Editing by Metehan Kanmaz with Movavi</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-capture-your-social-face-video/"><u>In 2024, Capture Your Social Face Video</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-project-essential-keyboard-tricks/"><u>Mastering MS Project: Essential Keyboard Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/modernizing-admin-workflows-a-fresh-approach-to-uac-functionality/"><u>Modernizing Admin Workflows: A Fresh Approach to UAC Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-activate-controlled-folder-access/"><u>Step-by-Step Guide to Activate Controlled Folder Access</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-solo-creators-path-to-dynamic-animation-art-for-2024/"><u>The Solo Creator’s Path to Dynamic Animation Art for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-edges-app-guard-accessing-cameramic/"><u>Turn on Edge's App Guard: Accessing Camera/Mic</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-adobe-premiere-elements-vs-the-competition-top-10-alternatives-for-2024/"><u>Updated Adobe Premiere Elements Vs. The Competition Top 10 Alternatives for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    