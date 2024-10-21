---
title: The Fourfold Approach to Discarding Partition on Windows Systems
date: 2024-10-19T21:13:38.951Z
updated: 2024-10-20T18:05:36.916Z
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

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-lessons.techidaily.com/new-advanced-anonymization-techniques-to-blur-faces/"><u>[New] Advanced Anonymization Techniques to Blur Faces</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-harness-your-creativity-with-high-quality-free-images-from-these-12-sites-for-2024/"><u>[Updated] Harness Your Creativity with High-Quality, Free Images From These 12 Sites for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-essence-of-time-stretching-detailed-review-of-slomo-2e1924/"><u>[Updated] The Essence of Time Stretching Detailed Review of SloMo, 2E1924</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-monitor-kids-internet-use/"><u>Configuring Windows 11 to Monitor Kids' Internet Use</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-dodge-windows-11s-protective-shield/"><u>Expert Tips: Dodge Windows 11'S Protective Shield</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-steam-file-access-restricted-issue-expert-solutions/"><u>Fixing the 'Steam File Access Restricted' Issue - Expert Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-new-amd-drivers-for-enhanced-window-11-performance/"><u>Harness the Power of New AMD Drivers for Enhanced Window 11 Performance</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-premier-no-8-digital-composers-kit/"><u>In 2024, Premier No. 8 Digital Composer's Kit</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-premiered-top-8-crowd-pleasing-ae-setups/"><u>In 2024, Premiered Top 8 Crowd-Pleasing AE Setups</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-switch-in-windows-11-replace-pin-with-secure-passwords/"><u>Navigating the Switch in Windows 11: Replace PIN with Secure Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-5-replacements-for-windows-snipping-capability-in-other-oses/"><u>The Top 5 Replacements for Windows' Snipping Capability in Other OSes</u></a></li>
</ul></div>

