---
title: Essential Steps for Eradicating a Drives Partition on PC
date: 2024-10-31T22:23:06.760Z
updated: 2024-11-01T19:27:31.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Eradicating a Drives Partition on PC
excerpt: This Article Describes Essential Steps for Eradicating a Drives Partition on PC
keywords: DrivePartitionEradicate,PartitionRemovalSteps,RemoveDriveError,FixDrivePartition,EraseDiskPartition,ClearPCPartition,PCDriveCleanupGuide
thumbnail: https://thmb.techidaily.com/c9e5ca8d00ac8479f694130618d3f9a3080c0193f44d3a38cfaa7537d0961fac.png
---

## Essential Steps for Eradicating a Drives Partition on PC

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettiit.sjv.io/c/5597632/2148129/17093" target="_top" id="2148129">
  <img src="//a.impactradius-go.com/display-ad/17093-2148129" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148129/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-secrets-to-affordable-buying-of-gopro-devices/"><u>[New] In 2024, Secrets to Affordable Buying of GoPro Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-turning-tides-exploring-unique-methods-to-reverse-youtube-videos/"><u>[New] Turning Tides Exploring Unique Methods to Reverse YouTube Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-discover-the-best-tiktok-to-mp3-online-costless-convertors/"><u>2024 Approved Discover the Best TikTok to MP3 Online, Costless Convertors</u></a></li>
<li><a href="https://win11.techidaily.com/compelling-arguments-opting-for-new-outlook-on-pcs/"><u>Compelling Arguments: Opting for New Outlook on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-browsing-experience-enabling-gestures-in-microsoft-edge/"><u>Customize Your Browsing Experience: Enabling Gestures in Microsoft Edge</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-bingchatgpt-token-hoaxes-a-step-by-step-guide-to-spotting-and-preventing-cryptocurrency-scams-online/"><u>Decoding BingChatGPT Token Hoaxes: A Step-by-Step Guide to Spotting & Preventing Cryptocurrency Scams Online</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-rectify-geforce-experience-error-on-windows-1011/"><u>Expert Tips: Rectify GeForce Experience Error on Windows 10/11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/experts-guide-to-infinite-space-utilization/"><u>Expert's Guide to Infinite Space Utilization</u></a></li>
<li><a href="https://win-top.techidaily.com/gratuit-mp4-vers-asf-en-direct-guide-complet-avec-movavi/"><u>Gratuit MP4 Vers ASF en Direct: Guide Complet Avec Movavi</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-the-outer-worlds-crashing-on-pc/"><u>How to Fix The Outer Worlds Crashing on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-realme-11-proplus-by-fonelab-android-recover-messages/"><u>How To Restore Missing Messages Files from Realme 11 Pro+</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-a-comprehensive-guide/"><u>Microsoft Family Safety: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-windows-11s-task-manager-main-window/"><u>Personalize Windows 11'S Task Manager Main Window</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-to-reset-your-gameplay-after-apex-crash/"><u>Tips and Tricks to Reset Your Gameplay After Apex Crash</u></a></li>
<li><a href="https://win11.techidaily.com/whats-critical-in-purchasing-a-modern-win-laptop/"><u>What's Critical in Purchasing a Modern Win Laptop?</u></a></li>
</ul></div>

