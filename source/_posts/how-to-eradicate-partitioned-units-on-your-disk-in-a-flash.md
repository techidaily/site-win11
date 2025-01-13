---
title: How to Eradicate Partitioned Units on Your Disk in a Flash
date: 2025-01-11T02:31:12.763Z
updated: 2025-01-13T08:05:37.656Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Eradicate Partitioned Units on Your Disk in a Flash
excerpt: This Article Describes How to Eradicate Partitioned Units on Your Disk in a Flash
keywords: Quick Disk PU Removal,Fast Unpartitioning Disks,Erase PU Efficiently,Speedy Disk Reclaim,Accelerate Disk Cleanup,Rip Vanish Partitions,Flash Units Away Quickly
thumbnail: https://thmb.techidaily.com/1766f7bb7d62dccbd0941bc3a3d98f6308c902e159cc9f0ddd8cacd9204dab92.jpg
---

## How to Eradicate Partitioned Units on Your Disk in a Flash

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-cross-service-playlist-exchange-simplified-for-2024/"><u>[New] Cross-Service Playlist Exchange Simplified for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-gratis-design-elements-for-youtube-channel-for-2024/"><u>[Updated] Gratis Design Elements for YouTube Channel for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-perfect-pairing-best-6-video-capture-tools-for-macos-for-2024/"><u>[Updated] Perfect Pairing Best 6 Video Capture Tools for MacOS for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-professionals-playbook-refined-gopro-video-production-techniques/"><u>2024 Approved The Professional's Playbook Refined GoPro Video Production Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-ea-server-offline-on-windows/"><u>Combatting the EA Server Offline On Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-windows-store-app-installs-post-error/"><u>Enabling Windows Store App Installs Post-Error</u></a></li>
<li><a href="https://win11.techidaily.com/from-novice-to-pro-mastering-windows-11s-ui-elements/"><u>From Novice to Pro: Mastering Windows 11'S UI Elements</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-disabling-windows-aural-amplifiers/"><u>Guide to Disabling Windows Aural Amplifiers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-xs-max-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone XS Max With or Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-games-not-opening-in-full-screen-mode-on-windows/"><u>How to Fix Games Not Opening in Full Screen Mode on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-13-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 13 using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/lighten-your-load-with-laughs-fb-detainment-chuckle-highlighters/"><u>Lighten Your Load with Laughs FB Detainment Chuckle Highlighters</u></a></li>
<li><a href="https://facebook.techidaily.com/recharge-methodically-incorporating-facebooks-daily-break-cues/"><u>Recharge Methodically: Incorporating Facebook's Daily Break Cues</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-14-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of 14 on Mac</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-tackle-windows-snipshot-issue/"><u>Step-by-Step Guide to Tackle Windows Snipshot Issue</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-ms-store-re-registration-on-windows-11-and-11/"><u>Streamlining MS Store Re-Registration on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-utorrent-file-download-speed-on-pcs/"><u>Turbocharge uTorrent File Download Speed on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unshackling-windows-files-ending-read-lock/"><u>Unshackling Windows Files: Ending Read Lock</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-use-speed-ramping-to-create-an-intense-action-footage/"><u>Updated In 2024, How To Use Speed Ramping to Create an Intense Action Footage</u></a></li>
</ul></div>

