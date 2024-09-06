---
title: The Ultimate Guide to Purging Windows Drives' Partition Units
date: 2024-09-05T08:39:00.291Z
updated: 2024-09-06T08:39:00.291Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-essential-tips-for-choosing-fpv-drone-blades/"><u>[New] 2024 Approved  Essential Tips for Choosing FPV Drone Blades</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-free-unique-audio-selections-for-video-conclusions/"><u>[New] 2024 Approved  Free, Unique Audio Selections for Video Conclusions</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-tapered-music-transitions-an-intuitive-premiere-pro-tutorial/"><u>[New] 2024 Approved  Tapered Music Transitions  An Intuitive Premiere Pro Tutorial</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-unveiling-youtubes-mechanism-post-upload/"><u>[New] 2024 Approved  Unveiling YouTube's Mechanism Post-Upload</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-commercial-cloud-repository-standouts/"><u>[New] Commercial Cloud Repository Standouts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tailor-topical-laughs/"><u>[Updated] Tailor Topical Laughs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-stay-updated-the-latest-on-changing-win11-walls/"><u>2024 Approved  Stay Updated  The Latest on Changing Win11 Walls</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-untangling-aerial-vehicles-a-guide-to-drones-operation/"><u>2024 Approved  Untangling Aerial Vehicles  A Guide to Drones' Operation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-your-youtube-shorts-have-been-restored/"><u>2024 Approved  Your YouTube Shorts Have Been Restored</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-critical-appraisal-of-sound-forge-pros-cons-and-potentials/"><u>2024 Approved Critical Appraisal of Sound Forge Pros, Cons, and Potentials</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-smartphones-with-ois-for-shooting-smooth-videos-for-2024/"><u>Best Smartphones with OIS for Shooting Smooth Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-windows-ram-cache/"><u>Comprehensive Guide to Window’s RAM Cache</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-error-code-0xc00000f-in-windows/"><u>Deciphering and Resolving Error Code 0xC00000F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-vcplusplus-distribution-essence/"><u>Decoding VC++ Distribution Essence</u></a></li>
<li><a href="https://win11.techidaily.com/ease-into-windows-11-troubleshooting-update-issue-0x30017/"><u>Ease Into Windows 11: Troubleshooting Update Issue #0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/easing-expiry-headache-fixing-windows-license-alarms/"><u>Easing Expiry Headache: Fixing Windows License Alarms</u></a></li>
<li><a href="https://win11.techidaily.com/empowered-windows-operations-advanced-run-enhancements-guide/"><u>Empowered Windows Operations: Advanced Run Enhancements Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-troubleshooting-steps-to-prevent-recurring-windows-explorer-breakdowns-with-revo/"><u>Expert Troubleshooting Steps to Prevent Recurring Windows Explorer Breakdowns with Revo</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-efficient-installation-of-msixbundle-and-apppackages-from-microsoft-store/"><u>Fast Track: Efficient Installation of MSixbundle & Apppackages From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-best-of-linux-ditch-wsl/"><u>Get the Best of Linux - Ditch WSL</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-error-code-0x80004004-in-defender/"><u>How to Address Error Code 0X80004004 in Defender</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-creative-capture-of-sims-4-sagas-innovative-ways-to-record-your-journey/"><u>In 2024, Creative Capture of Sims 4 Sagas  Innovative Ways to Record Your Journey</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leading-workspace-high-flying-space-for-2024/"><u>Leading Workspace High-Flying Space for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-tasks-with-these-excellent-8-windows-timer-apps/"><u>Master Your Tasks with These Excellent 8 Windows Timer Apps</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-win11-startup-efficiency/"><u>Maximizing Win11 Startup Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-spotify-crash-in-windows-11-without-it-help/"><u>Overcoming Spotify Crash in Windows 11 without IT Help</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-taskbar-concealment-when-maximizing-browser/"><u>Overcoming Taskbar Concealment When Maximizing Browser</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-mcuicnt-execution-error-on-modern-windows-pcs/"><u>Overhauling McUICnt Execution Error on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quantifying-storage-quotient-for-windows-programs/"><u>Quantifying Storage Quotient for Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-stopping-windows-11-from-running/"><u>Quick Fixes: Stopping Windows 11 From Running</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-vintage-windows-pcs-for-elders/"><u>Reimagining Vintage Windows PCs for Elders</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steams-unavailable-content-servers-issue-on-pc/"><u>Resolving Steam's Unavailable Content Servers Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revert-to-regular-contrast-on-windows/"><u>Revert to Regular Contrast on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/separating-the-sincere-from-the-spoof-in-the-windows-store/"><u>Separating the Sincere From the Spoof in the Windows Store</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-elevate-taskmanager-on-desktop/"><u>Strategies to Elevate TaskManager on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-performance-via-virtual-memory-adjustment-in-windows-11/"><u>Streamlining Performance via Virtual Memory Adjustment in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-eliminate-autominimize-effects/"><u>Streamlining Windows: Eliminate AutoMinimize Effects</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-22h2-moment-update-could-bring-7-exciting-features/"><u>The Windows 11 22H2 Moment Update Could Bring 7 Exciting Features</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-htc-u23-pro-by-drfone-android/"><u>Top 10 Password Cracking Tools For HTC U23 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-launchers-security-code-delivery-issues-on-windows/"><u>Troubleshooting: Overcoming Launcher's Security Code Delivery Issues on Windows</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/tutorial-rapido-scaricare-e-preservare-i-filmati-in-dvd-usando-windowsmacos/"><u>Tutorial Rapido: Scaricare E Preservare I Filmati in DVD Usando Windows/macOS</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-code-mastery-reclaiming-your-windows-1011-key/"><u>Unlock Code Mastery: Reclaiming Your Windows 10/11 Key</u></a></li>
<li><a href="https://win11.techidaily.com/win11-image-camouflage-techniques-for-zip-files/"><u>Win11 Image Camouflage Techniques for ZIP Files</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>