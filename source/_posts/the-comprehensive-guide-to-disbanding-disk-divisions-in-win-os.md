---
title: The Comprehensive Guide to Disbanding Disk Divisions in Win OS
date: 2024-09-05T08:39:31.864Z
updated: 2024-09-06T08:39:31.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Comprehensive Guide to Disbanding Disk Divisions in Win OS
excerpt: This Article Describes The Comprehensive Guide to Disbanding Disk Divisions in Win OS
keywords: Win OS File Division Terms,Disbanding Disk Partitions,Windows OS Directory Disassembly,Deleting Disk Volumes (Win),Win OS Divisional Removal Guide,Clearing Drives in WinOS,Ending Disk Segments in Windows
thumbnail: https://thmb.techidaily.com/8eb93e1b1b19fd0df7a5c4a69b010fd291b98c2d5042e30f7996e1ded01bfda5.jpg
---

## The Comprehensive Guide to Disbanding Disk Divisions in Win OS

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-chuckle-chronicles-best-free-top-rated-comic-designs/"><u>[New] Chuckle Chronicles  Best Free, Top-Rated Comic Designs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-digital-savvy-guide-opting-between-software-and-no-software-for-vimeo-for-2024/"><u>[New] Digital Savvy Guide  Opting Between Software & No-Software for Vimeo for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-connect-your-content-from-twitch-to-facebook/"><u>[New] In 2024, Connect Your Content  From Twitch to Facebook</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-master-your-craft-exclusive-free-templates-and-tips/"><u>[New] Master Your Craft  Exclusive Free Templates & Tips</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-want-to-send-snaps-from-camera-roll-see-how-it-is-done-for-2024/"><u>[New] Want to Send Snaps From Camera Roll? See How It Is Done for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-revive-your-iphone-ipad-and-macs-airdrop-functionality-with-quick-tips/"><u>[Updated] Revive Your iPhone, iPad & Mac's Airdrop Functionality with Quick Tips</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-how-to-add-narration-to-your-videos/"><u>2024 Approved  How to Add Narration to Your Videos</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-superior-vistas-for-digital-viewership/"><u>2024 Approved  Superior Vistas for Digital Viewership</u></a></li>
<li><a href="https://some-guidance.techidaily.com/4-effective-methods-for-watching-dvd-movies-on-your-windows-11-computer/"><u>4 Effective Methods for Watching DVD Movies on Your Windows 11 Computer</u></a></li>
<li><a href="https://article-posts.techidaily.com/bridging-platforms-instagram-and-tik-tok-synergy-manual/"><u>Bridging Platforms  Instagram & Tik Tok Synergy Manual</u></a></li>
<li><a href="https://technical-tips.techidaily.com/chronological-journey-through-the-best-transformers-movies-onscreen/"><u>Chronological Journey Through The Best Transformers Movies Onscreen</u></a></li>
<li><a href="https://facebook.techidaily.com/clarifying-rights-to-your-social-media-photos/"><u>Clarifying Rights to Your Social Media Photos</u></a></li>
<li><a href="https://win11.techidaily.com/desktop-icon-disappearance-windows-11-recovery-steps/"><u>Desktop Icon Disappearance: Windows 11 Recovery Steps</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-steps-for-fixing-ms-store-crash-code-0x0-on-win-1011/"><u>Detailed Steps for Fixing MS Store Crash (Code 0X0) on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-ethernet-connectivity-loss-on-pc/"><u>Eliminating Ethernet Connectivity Loss on PC</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-workflow-with-win-11s-auto-organize-functionality/"><u>Enhance Workflow with Win 11'S Auto-Organize Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-overcoming-voice-typing-hiccups-in-windows-11/"><u>Expert Guide to Overcoming Voice Typing Hiccups in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-removing-inaccurate-tags-from-onedrive-reparse-points/"><u>Fix Guide: Removing Inaccurate Tags From OneDrive Reparse Points</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-a00f4289-webcam-issues-in-win1011/"><u>Fixing Error A00F4289: Webcam Issues in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-same-user-login-problem-for-multiple-windows-users/"><u>Fixing Same-User Login Problem for Multiple Windows Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/friend-focused-fun-strategies-for-team-success-in-monster-hunter-world-adventures/"><u>Friend-Focused Fun: Strategies for Team Success in Monster Hunter World Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/from-cr2-to-windows-jpeg-a-compreenased-conversion-guide/"><u>From CR2 to Windows JPEG: A Compreenased Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-dropbox-and-google-drive-from-a-windows-drive-letter/"><u>How to Access Dropbox and Google Drive From a Windows Drive Letter</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-add-stickers-to-instagram-in-2024/"><u>How to Add Stickers to Instagram, In 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-frame-rate-hiccups-and-stutters-in-ac-valhalla-pc/"><u>How to Resolve Frame Rate Hiccups and Stutters in AC Valhalla (PC)?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-assessing-vlcs-competitors-and-contenders/"><u>In 2024, Assessing VLC's Competitors and Contenders</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-vivo-y27s-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Vivo Y27s to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-nokia-c300-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Nokia C300 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-vivo-y100i-power-5g-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Vivo Y100i Power 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/increasing-pin-length-safely-on-windows-devices/"><u>Increasing Pin Length Safely on Windows Devices</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-effortless-video-import-and-export-tips-and-tricks-for-adobe-premiere-users/"><u>New 2024 Approved Effortless Video Import and Export Tips and Tricks for Adobe Premiere Users</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-cut-trim-and-tailor-audio-files-in-seconds-using-these-top-7-web-based-tools/"><u>New Cut, Trim, and Tailor Audio Files in Seconds Using These Top 7 Web-Based Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-screen-limitations-with-effective-strategies/"><u>Overcome Screen Limitations with Effective Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-boot-menu-colors/"><u>Restoring Legacy BOOT Menu Colors</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-obscured-filespace-with-altwindirstat/"><u>Reviving Obscured Filespace with AltWinDirStat</u></a></li>
<li><a href="https://win11.techidaily.com/right-click-rescue-6-fixes-to-reactivate-menu-items/"><u>Right-Click Rescue: 6 Fixes to Reactivate Menu Items</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-your-desktops-background-from-changes/"><u>Safeguard Your Desktop's Background From Changes</u></a></li>
<li><a href="https://win11.techidaily.com/securing-dialog-box-for-trusted-hardware-in-windows-11/"><u>Securing Dialog Box for Trusted Hardware in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-world-of-call-management-windows-11-dialer/"><u>Step Into the World of Call Management: Windows 11 Dialer</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-bypass-access-denied-issues-on-windows-pc/"><u>Strategies to Bypass 'Access Denied' Issues on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-top-7-techniques-to-master-windows-11-40/"><u>The Ultimate Guide: Top 7 Techniques to Master Windows 11 (40)</u></a></li>
<li><a href="https://win11.techidaily.com/tips-configure-wi-fi-metered-networks-in-win11/"><u>Tips: Configure Wi-Fi Metered Networks in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-hacktoolwin32keygen-malware-how-to-remove-it-on-windows/"><u>What Is the HackTool:Win32/Keygen Malware? How to Remove It on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-a-study-on-cloud-vs-physical-installation-methods/"><u>Windows Update: A Study on Cloud Vs. Physical Installation Methods</u></a></li>
<li><a href="https://win11.techidaily.com/witness-windows-11-evolve-with-its-latest-moment-updates/"><u>Witness Windows 11 Evolve with Its Latest Moment Updates</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>