---
title: The Ultimate Guide to Purging Windows Drives' Partition Units
date: 2024-11-29T16:53:03.422Z
updated: 2024-12-06T23:40:11.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Purging Windows Drives' Partition Units
excerpt: This Article Describes The Ultimate Guide to Purging Windows Drives' Partition Units
keywords: Windows Drive Cleanup,Partition Management Tips,Purging Disk Space Efficiently,Optimize Drive Storage,Deleting Unused Drives,Manage Partitions Quickly,Guide to Drive Space Saving
thumbnail: https://thmb.techidaily.com/796380b2f6e477c41fdb5986a336623e799bf688b4a29cd4a3d817de3e2d744c.jpg
---

## The Ultimate Guide to Purging Windows Drives' Partition Units

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the steps, the partition and everything on it will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/n-2024-google-meet-on-youtube-streaming-made-easy-step-by-step/"><u>[New] In 2024, Google Meet on YouTube Streaming Made Easy, Step by Step</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transforming-hobby-footage-into-professional-vlogs/"><u>[New] Transforming Hobby Footage Into Professional Vlogs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-unleash-potential-10-top-motivational-gems/"><u>[New] Unleash Potential 10 Top Motivational Gems</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-choosing-your-soundtrack-the-podcast-vs-youtube-showdown-for-2024/"><u>[Updated] Choosing Your Soundtrack The Podcast Vs. YouTube Showdown for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/compre-written-guide-for-windows-error-code-0xc00000f/"><u>Compre Written Guide for Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://fox-place.techidaily.com/error-unable-to-locate-webpage-encountered-a-missing-page-issue/"><u>Error: Unable to Locate Webpage – Encountered a Missing Page Issue</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-gaming-worlds-windows-directories-unlocked/"><u>Exploring Gaming Worlds: Windows Directories Unlocked</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/great-image-quality-overshadowed-by-confusing-a10-interface/"><u>Great Image Quality Overshadowed by Confusing A10 Interface</u></a></li>
<li><a href="https://driver-install.techidaily.com/master-technique-for-usb-mouse-driver-revival-in-win1011/"><u>Master Technique for USB-Mouse Driver Revival in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-msstore-troubleshooting-for-error-code-0x0-failure/"><u>Mastering MsStore Troubleshooting for Error Code 0X0 Failure</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-top-level-calculator-in-windows/"><u>Preserving Top-Level Calculator in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-restoration-regaining-razers-control-on-pcs/"><u>Rapid Restoration: Regaining Razer's Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-windows-inactive-start-button/"><u>Reviving Your Window's Inactive Start Button</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-file-handling-with-powershell-expertise/"><u>Streamlining File Handling with PowerShell Expertise</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-convenient-hp-stream-11-notebook-for-simple-on-the-move-internet-use/"><u>The Convenient HP Stream 11 Notebook for Simple, On-the-Move Internet Use</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-0xc000003e-application-initiation-faults-on-pcs/"><u>Troubleshooting 0XC000003E Application Initiation Faults on PCs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unveiling-the-secrets-to-superior-gaming-recordings-for-2024/"><u>Unveiling the Secrets to Superior Gaming Recordings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/usb-boot-media-creation-windows-11-tutorial-in-three-parts/"><u>USB Boot Media Creation – Windows 11 Tutorial in Three Parts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/watch-your-favorite-games-for-free-2024s-premier-streaming-options/"><u>Watch Your Favorite Games for Free: 2024'S Premier Streaming Options</u></a></li>
</ul></div>

