---
title: Simplified Techniques to Discard a Drive's Divisional Structure in Windows
date: 2024-07-13T10:32:29.220Z
updated: 2024-07-14T10:32:29.220Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/addressing-critical-dll-loss-restoring-mfc71u-on-pcs/"><u>Addressing Critical DLL Loss: Restoring Mfc71u on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-quick-guide-to-open-sticky-notes/"><u>Windows 11: Quick Guide to Open Sticky Notes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-evaluating-the-value-of-sns-hdr-in-a-crowded-market/"><u>2024 Approved  Evaluating the Value of SNS HDR in a Crowded Market</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-vivo-t2-pro-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Vivo T2 Pro 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-gaming-upgrade-guide-top-tips-for-a-seamless-experience/"><u>Win 11 Gaming Upgrade Guide: Top Tips for a Seamless Experience</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 To Other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-empowering-tiktok-sharing-on-twitter-networks/"><u>[New] Empowering TikTok Sharing on Twitter Networks</u></a></li>
<li><a href="https://win11.techidaily.com/excel-in-windows-top-5-productivity-enhancers-you-cant-miss/"><u>Excel in Windows: Top 5 Productivity Enhancers You Can't Miss</u></a></li>
<li><a href="https://win11.techidaily.com/visual-virtuoso-top-tips-to-overcome-blurry-windows-11-displays/"><u>Visual Virtuoso: Top Tips to Overcome Blurry Windows 11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-users-a-comprehensive-guide-to-windows-tweaks-via-alomware/"><u>Empowering Users: A Comprehensive Guide to Windows Tweaks via AlomWare</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/8-premier-mp3-downloaders-for-android-devices/"><u>8 Premier MP3 Downloaders for Android Devices</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-system-failures-code-0xc0000001/"><u>Eradicating System Failures: Code 0xC0000001</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-titans-of-tutorials-youtube-leaders/"><u>[Updated] The Titans of Tutorials  YouTube Leaders</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-incorporate-google-maps-into-windows/"><u>Effortlessly Incorporate Google Maps Into Windows</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-the-health-of-your-windows-11-setup/"><u>Confirming the Health of Your Windows 11 Setup</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-elevate-your-gaming-experience-nintendo-switch-and-steam-synergy/"><u>[New] In 2024, Elevate Your Gaming Experience  Nintendo Switch and Steam Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-common-vscode-crash-causes-on-winw11/"><u>Sidestep Common VSCode Crash Causes on WinW11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-real-time-caption-generator/"><u>2024 Approved  Real-Time Caption Generator</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-decoding-video-potential-dslr-vs-mirrorless-innovation/"><u>[Updated] Decoding Video Potential  DSLR vs Mirrorless Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-mouse-pointer-prominence-in-windows-11/"><u>Enhancing Mouse Pointer Prominence in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-offline-windows-update-plan/"><u>Crafting an Offline Windows Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience/"><u>7 Proven Methods to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-altitude-heroes-aerospaces-persistent-innovations-top-10/"><u>[Updated] High Altitude Heroes  Aerospace's Persistent Innovations (Top 10)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-time-lapse-mastery-unlock-the-power-of-accelerated-video/"><u>Updated Time Lapse Mastery Unlock the Power of Accelerated Video</u></a></li>
<li><a href="https://win11.techidaily.com/from-minuscule-to-monumental-boosting-windows-11-icon-sizes/"><u>From Minuscule to Monumental - Boosting Windows 11 Icon Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/craft-command-capabilities-for-the-windowed-world/"><u>Craft Command Capabilities for the Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-faulty-windows-update-error/"><u>Correcting Faulty Windows Update Error</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-comprehensive-examination-videon-x-the-ultimate-video-editor/"><u>[Updated] Comprehensive Examination  Videon X – The Ultimate Video Editor</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-explore-uncharted-territories-with-these-iphone-vr-apps/"><u>2024 Approved  Explore Uncharted Territories with These iPhone VR Apps</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-windows-task-management-addressing-misplaced-cpu-metrics/"><u>Fixes for Windows Task Management: Addressing Misplaced CPU Metrics</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-transforming-raw-footage-an-in-depth-guide-to-applying-lut-filters-in-obs-studio/"><u>[New] Transforming Raw Footage  An In-Depth Guide to Applying LUT Filters in OBS Studio</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-master-the-science-and-art-of-attention-grabbing-titles/"><u>[New] Master the Science and Art of Attention-Grabbing Titles</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-curse-of-wow-error-132-a-step-by-step-approach/"><u>Beating the Curse of WoW Error #132: A Step-by-Step Approach</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-perfect-your-titling-skills-with-our-best-practices/"><u>[Updated] Perfect Your Titling Skills with Our Best Practices</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nhancing-your-youtube-reach-with-famebit-ad-sponsorships/"><u>[New] Enhancing Your YouTube Reach with FameBit Ad Sponsorships</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-hurdles-of-error-0x80040610-a-comprehensive-approach/"><u>Eliminating the Hurdles of Error 0X80040610: A Comprehensive Approach</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-taste-trek-journey-through-global-cuisine-secrets/"><u>[New] Taste Trek  Journey Through Global Cuisine Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/banish-unfulfilled-system-criteria-marking-on-win11/"><u>Banish Unfulfilled System Criteria Marking on Win11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/asmr-expertise-soundscapes-that-ease-sleeplessness/"><u>ASMR Expertise  Soundscapes That Ease Sleeplessness</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-non-functionality-in-windows-10/"><u>Fixing Grammarly Non-Functionality in Windows 10</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-mastering-video-posts-on-tiktok-your-guide-for-mac-and-pc-users/"><u>2024 Approved  Mastering Video Posts on TikTok  Your Guide for MAC & PC Users</u></a></li>
</ul></div>
