---
title: How to Eradicate Partitioned Units on Your Disk in a Flash
date: 2024-08-16T00:54:16.444Z
updated: 2024-08-17T00:54:16.444Z
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
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-mastering-the-art-of-uploading-youtube-videos-on-fb/"><u>[New] In 2024, Mastering the Art of Uploading YouTube Videos on FB</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-reimagining-time-flow-a-thorough-2024-app-review/"><u>[New] Reimagining Time Flow  A Thorough 2024 App Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-romantic-recitals-perfect-love-songs-for-your-proposal-moment/"><u>[New] Romantic Recitals  Perfect Love Songs for Your Proposal Moment</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-unlocking-the-art-of-film-preservation-in-tech-era/"><u>2024 Approved  Unlocking the Art of Film Preservation in Tech Era</u></a></li>
<li><a href="https://fox-helps.techidaily.com/achieving-flawless-photos-with-size-tweaks-on-ios-for-2024/"><u>Achieving Flawless Photos with Size Tweaks on iOS for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-about-the-new-apple-ring-projected-pricing-availability-and-technical-specifications/"><u>All About the New Apple Ring: Projected Pricing, Availability, and Technical Specifications</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-between-windows-and-wsl-with-post-update-strategies/"><u>Bridging Gaps Between Windows & WSL With Post-Update Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-local-libraries-and-online-oceans-dropbox-googledrive-on-c/"><u>Bridging Local Libraries & Online Oceans: Dropbox, GoogleDrive on C:/</u></a></li>
<li><a href="https://win11.techidaily.com/bring-order-to-your-notetaking-chaos-using-obsidian-palette/"><u>Bring Order to Your Notetaking Chaos Using Obsidian Palette</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-back-typical-window-explorer-options/"><u>Bringing Back Typical Window Explorer Options</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-winget-back-online-window-11-edition/"><u>Bringing Winget Back Online: Window 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-connections-ps3-dualshock-on-windows/"><u>Bypass Connections: PS3-DualShock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-update-warnings-with-these-4-tips/"><u>Bypass Update Warnings with These 4 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-internal-failure-for-smooth-rd-session/"><u>Bypassing Internal Failure for Smooth RD Session</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumble-errors-on-microsoft-store-win-1011/"><u>Bypassing Server Stumble Errors on Microsoft Store, Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-alerts-fast-track/"><u>Bypassing Windows 11 Alerts Fast-Track</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fixing-outdated-windows-user-password-issue/"><u>Bypassing: Fixing Outdated Window's User Password Issue</u></a></li>
<li><a href="https://win11.techidaily.com/cease-unsolicited-search-menu-activation-win11-style/"><u>Cease Unsolicited Search Menu Activation, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/change-windows-11-taskbar-size/"><u>Change Windows 11 Taskbar Size</u></a></li>
<li><a href="https://win11.techidaily.com/chatgpt-deployment-for-windows-computers/"><u>ChatGPT Deployment for Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/classic-game-connector-directing-past-fun-into-the-future/"><u>Classic Game Connector: Directing Past Fun Into the Future</u></a></li>
<li><a href="https://win11.techidaily.com/clear-out-clutter-personalize-your-w11-workspace/"><u>Clear Out Clutter: Personalize Your W11 Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-nine-tricks-to-dodge-steady-windows-update-stalls/"><u>Clear the Path: Nine Tricks to Dodge Steady Windows Update Stalls</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-from-the-recycle-bin-in-win-11-edition/"><u>Clearing Errors From the Recycle Bin in Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusions-removing-read-only-from-folders/"><u>Clearing Up Confusions: Removing Read-Only From Folders</u></a></li>
<li><a href="https://win11.techidaily.com/cleverly-camouflaged-these-programs-slow-down-windows-users/"><u>Cleverly Camouflaged, These Programs Slow Down Windows Users</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-tips-on-getting-sea-of-thieves-running-after-launch-failures/"><u>Expert Tips on Getting Sea of Thieves Running After Launch Failures</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-oneplus-nord-ce-3-lite-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the OnePlus Nord CE 3 Lite 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-mdm-from-iphone-6-without-a-computer-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove MDM from iPhone 6 without a computer?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-ringtones-guide-top-downloads/"><u>In 2024, Ultimate Ringtones Guide  Top Downloads</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-11x-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Realme 11X 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-vivo-v30-lite-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Vivo V30 Lite 5G Phone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-reasons-why-zerogpt-and-similar-ai-detectors-may-not-be-reliable-case-studies/"><u>Top Reasons Why ZeroGPT & Similar AI Detectors May Not Be Reliable: Case Studies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>