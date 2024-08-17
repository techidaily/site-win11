---
title: Mastering the Art of Purging Partitions on Your Win OS
date: 2024-08-15T23:36:16.531Z
updated: 2024-08-16T23:36:16.531Z
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

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
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
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-ephemeral-to-everlasting-the-art-of-saving-social-media-snaps/"><u>[New] 2024 Approved  From Ephemeral to Everlasting  The Art of Saving Social Media Snaps</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-navigating-online-content-the-merits-of-youtubes-ad-free-alternative/"><u>[New] 2024 Approved  Navigating Online Content  The Merits of YouTube's Ad-Free Alternative</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fluid-fusion-combining-videos-for-a-unified-youtube-presence/"><u>[New] In 2024, Fluid Fusion  Combining Videos for a Unified Youtube Presence</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-transformative-strategies-in-creating-engaging-fb-content/"><u>[New] In 2024, Transformative Strategies in Creating Engaging FB Content</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-intermittent-brightness-on-dell-system/"><u>[Solved] Intermittent Brightness on Dell System</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfect-color-accuracy-in-canon-imagery-with-free-and-paid-lut-combinations/"><u>[Updated] Perfect Color Accuracy in Canon Imagery with Free & Paid LUT Combinations</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-speed-racers-remarkable-22-run/"><u>[Updated] Speed Racers' Remarkable '22 Run</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-strategies-for-syncing-zoom-meetings-across-devices-for-2024/"><u>[Updated] Strategies for Syncing Zoom Meetings Across Devices for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-symphony-of-selection-trailer-music-mastery/"><u>[Updated] The Symphony of Selection  Trailer Music Mastery</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-guide-to-time-lapses-with-iphone-for-2024/"><u>[Updated] The Ultimate Guide to Time-Lapses with iPhone for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-transforming-footage-the-ultimate-guide-to-youtube-video-editing/"><u>[Updated] Transforming Footage  The Ultimate Guide to YouTube Video Editing</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-immersive-tech-triumphs-upcoming-top-5-playstation-vr-games/"><u>2024 Approved  Immersive Tech Triumphs  Upcoming Top 5 PlayStation VR Games</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-unlocking-the-potential-of-drone-footage-through-editing/"><u>2024 Approved  Unlocking the Potential of Drone Footage Through Editing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-htc-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock HTC Phone When You Forget the Password</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-vivo-x100-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Vivo X100 Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/apex-creations-workspace-assessment/"><u>Apex Creations Workspace Assessment</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-back-into-your-computers-print-command-wwinplusp/"><u>Breathe Life Back Into Your Computer's Print Command (WWin+P).</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-gaps-windows-11-legacy-computers-to-go-and-rufus-guide/"><u>Bridging Technology Gaps: Windows 11, Legacy Computers, To Go & Rufus Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-elevating-your-windows-experience-by-reclaiming-offscreen-panes/"><u>Bridging the Gap: Elevating Your Windows Experience by Reclaiming Offscreen Panes</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-unifying-your-pcs-with-files-through-aoemi/"><u>Bridging the Gap: Unifying Your PCs With Files Through AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-your-windows-11-interface-pointer/"><u>Brighten Up Your Windows 11 Interface Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-lifelayer-trashbin-on-the-windows-1011-environment/"><u>Building a Lifelayer Trashbin on the Windows 10/11 Environment</u></a></li>
<li><a href="https://article-files.techidaily.com/building-dynamic-photographic-ensembles/"><u>Building Dynamic Photographic Ensembles</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-directory-not-empty-warnings-solutions-for-error-x80070091/"><u>Bypassing 'Directory Not Empty' Warnings: Solutions for Error X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-restricted-windows-11-themes-with-skilled-registry-editing/"><u>Bypassing Restricted Windows 11 Themes with Skilled Registry Editing</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-security-warning-glitches/"><u>Bypassing Windows 11 Security Warning Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'.</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-to-locate-windows-app-habitats/"><u>Charting a Course to Locate Windows' App Habitats</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigating-permission-fail-in-installer-errors/"><u>Circumnavigating Permission Fail in Installer Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-differences-how-exes-stack-up-against-msis/"><u>Clarifying Differences: How EXEs Stack Up Against MSIs</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-installation-package-could-not-be-opens-errors-in-w10w11/"><u>Clearing Up 'Installation Package Could Not Be Opens' Errors in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-missing-file-alert-in-win-11/"><u>Clearing Up Missing File Alert in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-path-unavailability-issue/"><u>Clearing Up WIN Path Unavailability Issue</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-way-for-startup-icons-visibility/"><u>Clearing Way for Startup Icons' Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/clipchamp-win11-install-issues-step-by-step-remedies/"><u>ClipChamp Win11 Install Issues: Step-by-Step Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/combatant-guide-for-the-windows-updater-error-0x80070003/"><u>Combatant Guide for the Windows Updater Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/combating-darkened-windows-display-during-remote-workspace-access/"><u>Combating Darkened Windows Display During Remote Workspace Access</u></a></li>
<li><a href="https://win11.techidaily.com/develop-a-custom-speech-to-text-app-for-windows-step-by-step-guide/"><u>Develop a Custom Speech-to-Text App for Windows: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-pink-screens-an-essential-skill/"><u>Disabling Windows Pink Screens: An Essential Skill</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Lava Agni 2 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixed-positioning-of-windows-tasks-a-guide/"><u>Fixed Positioning of Windows Tasks: A Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-launch-failures-a-comprehensive-walkthrough-for-harvest-heroes-22/"><u>Fixing Launch Failures: A Comprehensive Walkthrough for Harvest Heroes 22</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-portaudio-problems-in-audacity-for-windows-1111-devices/"><u>Fixing PortAudio Problems in Audacity for Windows 11/11 Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-view-tiktok-content-on-a-big-tv-for-an-enhanced-experience/"><u>How to View TikTok Content on a Big TV for an Enhanced Experience</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-realme-c67-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Realme C67 5G Without PUK Codes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-industrial-giants-taking-flight-heavy-duty-drones/"><u>In 2024, Industrial Giants Taking Flight  Heavy-Duty Drones</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-mastering-xml-files-in-final-cut-pro-x-the-ultimate-guide/"><u>In 2024, Mastering XML Files in Final Cut Pro X The Ultimate Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-13-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 13</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snapchat-boomerangs-demystified-your-comprehensive-guide/"><u>In 2024, Snapchat Boomerangs Demystified  Your Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mending-forgotten-windows-key-logon-message/"><u>Mending Forgotten Windows Key Logon Message</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-problems-smooth-your-pcs-cpu-flow-with-rm/"><u>Pinpointing Problems: Smooth Your PC's CPU Flow With RM</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-write-access-blockage-in-windows-11/"><u>Remedying Write Access Blockage in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/removing-recycle-icon-inactivity-issue-in-win11/"><u>Removing Recycle Icon Inactivity Issue in Win11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-out-memory-dump-files-on-windows-11/"><u>Step-by-Step Guide: Clearing Out Memory Dump Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-language-settings-add-and-switch-layouts-in-win-11-os/"><u>Streamlining Language Settings: Add & Switch Layouts in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-copy-and-paste-on-edge-within-windows-11s-app-guard/"><u>Unlock Copy & Paste on Edge Within Windows 11'S App Guard</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-solutions-for-windows-color-synchronization/"><u>Unveiling Solutions for Windows Color Synchronization</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-touchpad-controls-with-new-synaptics-driver-download-tutorial/"><u>Update Your Touchpad Controls with New Synaptics Driver Download Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/windows-web-woes-7-simple-solutions-for-site-shutdown-syndrome/"><u>Windows Web Woes? 7 Simple Solutions for Site Shutdown Syndrome</u></a></li>
</ul></div>
