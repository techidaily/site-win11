---
title: How to Merge Adjacent and Non-Adjacent Partitions in Windows
date: 2024-08-16T00:55:18.110Z
updated: 2024-08-17T00:55:18.110Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Merge Adjacent and Non-Adjacent Partitions in Windows
excerpt: This Article Describes How to Merge Adjacent and Non-Adjacent Partitions in Windows
keywords: WinPartitionMerge,NonAdjacentWinMerge,AdjacentPartitionFusion,SplitWindowsMerge,WinPartitionAlignment,MergeNonAdjacentWin,FuseWindowsPartitions
thumbnail: https://thmb.techidaily.com/98cce883f8c6d6df0bb852da7eb40767e5514e4304dfa4fcbf005c1298bed966.jpg
---

## How to Merge Adjacent and Non-Adjacent Partitions in Windows

 Have you run out of space on one of your drives and want to expand it by merging in it another drive with free space? If so, you can easily do this if the partitions you want to merge are adjacent; if they are not adjacent, the process would be more complicated. This begs the question: how do adjacent and nonadjacent partitions differ?

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

## How Do Adjacent and Non-Adjacent Partitions Differ?

 As the name implies, adjacent partitions are located next to each other. If you have two drives right next to each other, C and D, they are considered adjacent partitions. In contrast, if you have three partitions, C, D, and E, then C and E are nonadjacent partitions because drive D separates them.

 It's straightforward to merge adjacent partitions using the Windows built-in tool and any third-party app. However, merging two non-adjacent partitions could be complicated.

## How to Merge Adjacent Partitions Using Windows Disk Management

 Disk Management is a Windows built-in utility that allows us to manage the hard drives installed on our device. The tool enables us to create, format, and delete partitions, shrink the drive volume by creating a new partition, expand the drive volume by merging space from another drive, and much more.

 When merging a partition with the Disk Management tool, it is necessary to delete an existing volume (adjacent to the drive you wish to extend) and release some space first. Later, you can merge this unallocated space into a partition of your choice.

 Therefore, you'll lose all your data on the drive you want to merge (or delete), which is a major disadvantage. Because of that, you'll need to [relocate your essential Windows apps](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/) and files from that drive, and then delete the volume.

 Let's say you want to merge drive D with drive C. This will require you to delete drive D first and merge it into drive C after that. You can delete the volume by following these steps:

1. Type **"Create and format"** in the Windows Search box and click **Create and format hard disk partitions**.  
![Type Create and Format in Windows Search to Open the Disk Management Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-type-create-and-format-in-windows-search-to-open-the-disk-management-utility.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
2. Right-click the volume (the drive you want to merge into another) and select **Delete Volume**.  
![Delete Volume D From Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-delete-volume-d-from-windows-disk-management-tool.jpg)

 Once you've got enough unallocated space available, follow these steps to merge it into your preferred drive:

1. Right-click the drive you want to extend and select **Extend Volume**.  
![Right-Click the Drive You Want to Extend and select Extend Volume in the Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-right-click-the-drive-you-want-to-extend-and-select-extend-volume-in-the-windows-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
2. Click **Next**, then select the amount of space you want to merge in the box next to **Select the amount of space in MB**. Following that, click **Next** a second time.  
![Click Next After Selecting the Amount of Space in MB You Want to Extend the Volume By in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-click-next-after-selecting-the-amount-of-space-in-mb-you-want-to-extend-the-volume-by-in-windows-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Then, click **Finish** to merge the unallocated space into your destination drive.

## How to Merge Non-Adjacent Partitions With Disk Management

 If you have unallocated space non-adjacent to the destination drive, the Extend Volume option will appear grayed out in Disk Management, meaning you can't merge the non-adjacent space into the destination drive. You need to first delete the volumes between your destination drive and unallocated space.

 Deleting the in-between volumes will increase the unallocated space and it'll become adjacent to your destination drive. Later, you can merge some portion of the unallocated space into the destination drive and use the rest to recreate the in-between volumes you deleted earlier.

![Delete the Volumes Between Your Destination Drive and Unallocated Space in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-delete-the-volumes-between-your-destination-drive-and-unallocated-space-in-windows-disk-management-tool.jpg)

 Because deleting a volume also deletes its data, you have to [create a backup of all drives](https://www.makeuseof.com/windows-11-create-complete-backup/) en route to your destination and unallocated space before deleting them. Because of this, merging nonadjacent partitions using Device Management is considered ineffective and time-consuming. An easy way to avoid this hassle is to use third-party tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## How to Merge Two Non-Adjacent Partitions Using NIUBI Partition Editor

 NIUBI Partition Editor makes merging nonadjacent partitions easy and doesn't require you to delete partitions between the unallocated space and destination partition. Here's how you can merge two non-adjacent partitions, say C and E, using NIUBI:

1. Download the NIUBI Partition Editor software from the [HDD-Tool official website](https://www.hdd-tool.com/download.html). There are two ways to use the software: download and install the setup file or download the portable version and use it without installing it.
2. Search for **NIUBI** in Windows Search to open the software.
3. Right-click the **E** drive you want to merge into **C** and click **Delete volume**. Click **Yes** to confirm; this will release the space.  
![Delete Volume E in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-delete-volume-e-in-niubi-partition-editor.jpg)
4. Now, right-click on partition **D,** which is between partition **C** and unallocated space, and click **Resize/Move volume**.  
![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  
![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  
![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-pixelperfect-the-modern-recorder-diagnosis/"><u>[New] 2024 Approved  'PixelPerfect'  The Modern Recorder Diagnosis</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-blueprints-for-impressive-fb-ad-campaigns/"><u>[New] 2024 Approved  Blueprints for Impressive FB Ad Campaigns</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-mastery-of-playback-essential-skills-in-ps3-recording/"><u>[New] 2024 Approved  Mastery of Playback  Essential Skills in PS3 Recording</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-precision-editing-perfecting-the-art-of-fades-in-pro/"><u>[New] In 2024, Precision Editing  Perfecting the Art of Fades in Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-the-art-of-partial-youtube-extraction/"><u>[New] Mastering the Art of Partial YouTube Extraction</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-capture-unbroken-webspace/"><u>[Updated] In 2024, Capture Unbroken Webspace</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-mastering-quick-youtube-comment-removal-techniques/"><u>[Updated] In 2024, Mastering Quick YouTube Comment Removal Techniques</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/25-animated-visionaries-shaping-tiktok-trends-for-2024/"><u>25 Animated Visionaries Shaping TikTok Trends for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-hacks-for-accessing-windows-repair-options/"><u>5 Hacks for Accessing Windows Repair Options</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://extra-information.techidaily.com/audacitys-secrets-creating-smooth-soundscapes/"><u>Audacity's Secrets  Creating Smooth Soundscapes</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-alternative-edits-skip-youtube-not-just-content-for-2024/"><u>Elite Alternative Edits  Skip Youtube, Not Just Content for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/embracing-peace-gpts-stress-intervention/"><u>Embracing Peace: GPT’s Stress Intervention</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-analysis-of-twelve-souths-compact-and-secure-compass-pro/"><u>Expert Analysis of Twelve South's Compact and Secure Compass Pro</u></a></li>
<li><a href="https://win-forum.techidaily.com/finding-out-which-powershell-version-you-have-in-windows-11-tips-and-tricks/"><u>Finding Out Which PowerShell Version You Have in Windows 11: Tips & Tricks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-90-lite-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Honor 90 Lite Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-oppo-find-x6-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Oppo Find X6 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/minisnapper-screen-recorder-feedback-for-2024/"><u>MiniSnapper Screen Recorder Feedback for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reclaiming-ravaged-recordings-a-sample-method/"><u>Reclaiming Ravaged Recordings: A Sample Method</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-5ghz-connection-in-windows-11-effective-fixes-here/"><u>Reintroduce Missing 5GHz Connection in Windows 11: Effective Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-graphics-restoration-on-latest-windows-oses/"><u>Simplifying Graphics Restoration on Latest Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-mkv-conversion-to-mp4-in-windows-systems/"><u>Simplifying MKV Conversion to MP4 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/solving-issues-with-ccleaner-not-working-on-windows-1011/"><u>Solving Issues with CCleaner Not Working on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-prepare-win11-in-vmware-17-player/"><u>Step-by-Step Guide to Prepare Win11 in VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-secure-entry-into-windows-admin-console/"><u>Steps for Secure Entry Into Windows' Admin Console</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-fundamentals-of-synchronizing-audio-and-video-in-screencasts/"><u>The Fundamentals of Synchronizing Audio and Video in Screencasts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-in-depth-guide-to-screen-capturing-in-online-meetings/"><u>The In-Depth Guide to Screen Capturing in Online Meetings</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>