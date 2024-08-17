---
title: 4 Ways to Delete a Drive Partition on Windows
date: 2024-08-15T23:27:24.317Z
updated: 2024-08-16T23:27:24.317Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Delete a Drive Partition on Windows
excerpt: This Article Describes 4 Ways to Delete a Drive Partition on Windows
keywords: Windows Drive Deletion,Remove Windows Partition,Clear Windows Drives,Delete Windows Partition,Partition Removal Windows,Wiping Windows Disk Space,Extract Partition on Windows
thumbnail: https://thmb.techidaily.com/61e5e75a143019f7f7c8689be3de97fce55d395ac791171ba491fd10d2883ba4.jpeg
---

## 4 Ways to Delete a Drive Partition on Windows

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-facebook-fam-bites-in-snapchat-spotlight/"><u>[New] 2024 Approved  Facebook Fam Bites in Snapchat Spotlight</u></a></li>
<li><a href="https://youtube-data.techidaily.com/esign-your-closure-the-best-free-youtube-tutorials/"><u>[New] Design Your Closure  The Best Free YouTube Tutorials</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unlocking-youtubes-encrypted-video-secrets/"><u>[New] Unlocking YouTube's Encrypted Video Secrets</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-annual-roundup-top-no-money-video-editing-software-reviewed/"><u>[Updated] 2024 Approved  Annual Roundup  Top No-Money Video Editing Software Reviewed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-streamlining-the-process-of-saving-ps3-gaming-moments/"><u>[Updated] 2024 Approved  Streamlining the Process of Saving PS3 Gaming Moments</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-high-tech-video-magnifier-kit/"><u>[Updated] High-Tech Video Magnifier Kit</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-how-to-add-border-to-instagram-photos-with-best-apps/"><u>[Updated] In 2024, How to Add Border to Instagram Photos with Best Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-the-art-of-obtaining-facebooks-prestigious-blue-badge/"><u>[Updated] Mastering the Art of Obtaining Facebook’s Prestigious Blue Badge</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pushing-boundaries-upward-an-incisive-mavic-pro-review/"><u>[Updated] Pushing Boundaries Upward  An Incisive Mavic Pro Review</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-setting-up-your-first-livestream-successfully/"><u>[Updated] Setting Up Your First Livestream Successfully</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-wallet-friendly-high-definition-equipment/"><u>[Updated] Wallet-Friendly High-Definition Equipment</u></a></li>
<li><a href="https://win11.techidaily.com/0x8004def5-on-onedrive-unraveling-windows-11-troubles/"><u>0X8004DEF5 on OneDrive - Unraveling Windows 11 Troubles</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-red-eye-remover-how-to-remove-red-eye-from-photos-on-iphone-free/"><u>2024 Approved  Red Eye Remover| How to Remove Red Eye From Photos on iPhone [Free]</u></a></li>
<li><a href="https://win11.techidaily.com/7-innovative-uses-for-windows-11-god-mode/"><u>7 Innovative Uses for Windows 11 God Mode</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-odbc-connectivity/"><u>A Comprehensive Guide to Windows' ODBC Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/a-scholarly-approach-to-embracing-hdr-in-windows-11-workflows/"><u>A Scholarly Approach to Embracing HDR in Windows 11 Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-mend-windows-1011-discord-errors/"><u>A Step-by-Step Approach to Mend Windows 10/11 Discord Errors</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-finding-documents-with-windows-11-taskbar-search-feature/"><u>Accelerate Finding Documents with Windows 11 Taskbar Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-download-rates-in-windows-environment/"><u>Accelerating Steam Download Rates in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/access-gpos-securely-a-guide-to-win11s-tools/"><u>Access GPOs Securely: A Guide to Win11's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-windows-10-navigating-as-a-first-timer/"><u>Accessible Windows 10: Navigating as a First-Timer</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/ace-set-of-rotational-recording-devices-for-2024/"><u>Ace Set of Rotational Recording Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-full-control-with-admin-cmd-role/"><u>Achieve Full Control with Admin CMD Role</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-software-operation-with-4-key-pcts/"><u>Achieve Seamless Software Operation with 4 Key PCTs</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Additional Tips About Sinnoh Stone For Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-portaudio-hiccup-on-windows-11-and-11/"><u>Addressing Audacity’s PortAudio Hiccup on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ctrl-lock-up-in-windows-11-environments/"><u>Addressing Ctrl Lock-Up in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-profile-not-valid-issue-for-users-in-windows/"><u>Addressing Profile Not Valid Issue for Users in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-configuration-for-optimal-android-resource-use/"><u>Advanced Configuration for Optimal Android Resource Use</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-infrastructure-with-windows-software/"><u>Augmenting Linux Infrastructure with Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-chaos-tidy-up-your-icons/"><u>Avoid Visual Chaos: Tidy Up Your Icons</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-management-application-hiccups/"><u>Avoid Windows Management Application Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-edge-how-to-get-rid-of-it-in-w11/"><u>Avoiding Edge: How to Get Rid of It in W11</u></a></li>
<li><a href="https://win11.techidaily.com/awareness-on-7-key-windows-events-that-signal-infection/"><u>Awareness on 7 Key Windows Events That Signal Infection</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-user-interference-with-windows-clocks/"><u>Blocking User Interference with Windows Clocks</u></a></li>
<li><a href="https://win11.techidaily.com/boost-notability-of-your-scribbles-with-strategic-sticky-note-placement-in-win-os/"><u>Boost Notability of Your Scribbles with Strategic Sticky Note Placement in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-connectivity-hurdles-clearing-up-vague-instructions/"><u>Breaking Down Wi-Fi Connectivity Hurdles: Clearing Up Vague Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windowsstore-app-folder-secrets/"><u>Breaking Into WindowsStore App Folder Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/1719302930005-bypass-incompatibility-woes-in-windows-xp-7-and-8-easily/"><u>Bypass Incompatibility Woes in Windows XP, 7 & 8 Easily.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/create-logos-via-free-logo-template-customize-and-download-for-free-for-2024/"><u>Create Logos via Free Logo Template Customize and Download for Free for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/effortless-download-scansnap-s130n-driver-update-for-enhanced-performance/"><u>Effortless Download: ScanSnap S130n Driver Update for Enhanced Performance</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-make-a-digital-signature-for-wpt-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to make a digital signature for .wpt file</u></a></li>
<li><a href="https://win11.techidaily.com/1719369512280-ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now</u></a></li>
<li><a href="https://extra-resources.techidaily.com/image-framing-essentials-top-apps-and-websites-creators/"><u>Image Framing Essentials  Top Apps & Websites Creators</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-apple-iphone-13-mini-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 13 mini Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gtx-gems-the-best-for-high-res-gaming/"><u>In 2024, GTX Gems  The Best for High-Res Gaming</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-guide-to-writing-enthralling-videography-content/"><u>In 2024, Guide to Writing Enthralling Videography Content</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-nokia-c110-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Nokia C110 FRP?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-images-without-spending-a-dime-quick-tips-here/"><u>In 2024, YouTube Images Without Spending a Dime – Quick Tips Here</u></a></li>
<li><a href="https://media-tips.techidaily.com/mp3-conversion-masterclass-transforming-flv-files-into-audio-on-macos-systems/"><u>MP3 Conversion Masterclass: Transforming FLV Files Into Audio on macOS Systems</u></a></li>
<li><a href="https://win11.techidaily.com/1719346431441-navigate-through-common-snip-and-sketch-screen-capture-issues/"><u>Navigate Through Common Snip & Sketch Screen Capture Issues.</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/transforming-live-dialogues-into-permanent-history/"><u>Transforming Live Dialogues Into Permanent History</u></a></li>
<li><a href="https://win11.techidaily.com/1719349600813-troubleshoot-unlock-handbrake-on-widows/"><u>Troubleshoot: Unlock HandBrake on Widows!</u></a></li>
</ul></div>
