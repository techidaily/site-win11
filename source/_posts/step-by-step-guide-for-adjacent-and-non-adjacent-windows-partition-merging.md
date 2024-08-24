---
title: Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging
date: 2024-08-23T06:08:36.552Z
updated: 2024-08-24T06:08:36.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging
excerpt: This Article Describes Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging
keywords: Windows Partition Merge Guide,Adjacent Window Merge Steps,Non-Adjacent WINDOWS Merge,Partition Merge in Windows,Split Disk Space Merging,Seamless File System Merge,Direct Partition Merging Tips
thumbnail: https://thmb.techidaily.com/6a5ef0f96e3143e13628bf5caeebc60a8c5be5cea41d7e7c6dca8a665b151ae2.jpg
---

## Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging

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
2. Right-click the volume (the drive you want to merge into another) and select **Delete Volume**.  
![Delete Volume D From Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-delete-volume-d-from-windows-disk-management-tool.jpg)

 Once you've got enough unallocated space available, follow these steps to merge it into your preferred drive:

1. Right-click the drive you want to extend and select **Extend Volume**.  
![Right-Click the Drive You Want to Extend and select Extend Volume in the Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-right-click-the-drive-you-want-to-extend-and-select-extend-volume-in-the-windows-disk-management-tool.jpg)
2. Click **Next**, then select the amount of space you want to merge in the box next to **Select the amount of space in MB**. Following that, click **Next** a second time.  
![Click Next After Selecting the Amount of Space in MB You Want to Extend the Volume By in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-click-next-after-selecting-the-amount-of-space-in-mb-you-want-to-extend-the-volume-by-in-windows-disk-management-tool.jpg)
3. Then, click **Finish** to merge the unallocated space into your destination drive.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Merge Non-Adjacent Partitions With Disk Management

 If you have unallocated space non-adjacent to the destination drive, the Extend Volume option will appear grayed out in Disk Management, meaning you can't merge the non-adjacent space into the destination drive. You need to first delete the volumes between your destination drive and unallocated space.

 Deleting the in-between volumes will increase the unallocated space and it'll become adjacent to your destination drive. Later, you can merge some portion of the unallocated space into the destination drive and use the rest to recreate the in-between volumes you deleted earlier.

![Delete the Volumes Between Your Destination Drive and Unallocated Space in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-delete-the-volumes-between-your-destination-drive-and-unallocated-space-in-windows-disk-management-tool.jpg)

 Because deleting a volume also deletes its data, you have to [create a backup of all drives](https://www.makeuseof.com/windows-11-create-complete-backup/) en route to your destination and unallocated space before deleting them. Because of this, merging nonadjacent partitions using Device Management is considered ineffective and time-consuming. An easy way to avoid this hassle is to use third-party tools.

## How to Merge Two Non-Adjacent Partitions Using NIUBI Partition Editor

 NIUBI Partition Editor makes merging nonadjacent partitions easy and doesn't require you to delete partitions between the unallocated space and destination partition. Here's how you can merge two non-adjacent partitions, say C and E, using NIUBI:

1. Download the NIUBI Partition Editor software from the [HDD-Tool official website](https://www.hdd-tool.com/download.html). There are two ways to use the software: download and install the setup file or download the portable version and use it without installing it.
2. Search for **NIUBI** in Windows Search to open the software.
3. Right-click the **E** drive you want to merge into **C** and click **Delete volume**. Click **Yes** to confirm; this will release the space.  
![Delete Volume E in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-delete-volume-e-in-niubi-partition-editor.jpg)
4. Now, right-click on partition **D,** which is between partition **C** and unallocated space, and click **Resize/Move volume**.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-transformation-from-zero-to-thousand-followers-for-2024/"><u>[New] Channel Transformation  From Zero to Thousand Followers for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-crafting-engaging-bio-stories-a-guide-to-stand-out-on-fb-for-2024/"><u>[New] Crafting Engaging Bio Stories – A Guide to Stand Out on FB for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/uide-to-livecasting-google-meet-on-youtube/"><u>[New] Guide to Livecasting Google Meet on YouTube</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-maximize-impact-with-these-11-economical-youtube-naming-tools/"><u>[New] In 2024, Maximize Impact with These 11 Economical YouTube Naming Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-no-pay-no-problem-get-your-free-passport-photo-creator-now-online-and-on-desktop/"><u>[New] No Pay, No Problem  Get Your Free Passport Photo Creator Now Online & On Desktop</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-round-the-clock-insight-detailed-look-at-google-podcast/"><u>[New] Round-the-Clock Insight  Detailed Look at Google Podcast</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-seamlessly-post-vimeo-to-instagram/"><u>[New] Seamlessly Post Vimeo to Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-top-10plus-tools-to-record-your-pc-screen-seamlessly/"><u>[New] Top 10+ Tools to Record Your PC Screen Seamlessly</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-charting-updates-youtube-money-standards/"><u>[Updated] 2024 Approved  Charting Updates  YouTube Money Standards</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevating-your-youtube-presence-with-strategic-banners/"><u>[Updated] In 2024, Elevating Your YouTube Presence with Strategic Banners</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-mastering-link-sharing-instagram-stories-and-posts/"><u>[Updated] In 2024, Mastering Link Sharing  Instagram Stories & Posts</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-cost-effective-drone-collection-affordable-flight-gadgets/"><u>2024 Approved  Cost-Effective Drone Collection  Affordable Flight Gadgets</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-the-world-of-instagram-and-podcast-sharing/"><u>2024 Approved  Navigating the World of Instagram & Podcast Sharing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-no-cost-voice-modifier-transform-your-valorant-gameplay/"><u>2024 Approved  Ultimate No-Cost Voice Modifier  Transform Your Valorant Gameplay</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/audacity-audio-basics-for-new-mac-users/"><u>Audacity Audio Basics for New Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/customize-win11-optimal-predefined-window-sizes/"><u>Customize Win11: Optimal Predefined Window Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-context-menu-for-a-cleaner-win-11-experience/"><u>Customize Your Context Menu for a Cleaner Win 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-error-0x80246007-in-w10w11/"><u>Deciphering and Dismantling Error 0X80246007 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/differences-spotlighted-microsoft-account-vs-non-microsoft-windows-logins/"><u>Differences Spotlighted: Microsoft Account vs Non-Microsoft Windows Logins</u></a></li>
<li><a href="https://win11.techidaily.com/discover-file-metrics-in-windows-with-easy-powershell-scripts/"><u>Discover File Metrics in Windows With Easy PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-ui-quality-with-dpi-tuning/"><u>Elevating UI Quality with DPI Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-file-management-and-editing-learn-to-use-text-actions-in-snip/"><u>Enhance File Management & Editing: Learn to Use Text Actions in Snip</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/foremost-5-online-video-editors-for-2024/"><u>Foremost 5 Online Video Editors for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/generate-humor-picmagic-creation-for-2024/"><u>Generate Humor  PicMagic Creation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-set-up-issues-on-win-1011/"><u>Guide to Correcting Discord Set-Up Issues on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adopt-educational-aesthetics-in-win-11/"><u>How to Adopt Educational Aesthetics in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-common-rainmeter-issues-on-windows/"><u>How to Fix Common Rainmeter Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-the-killer-javascript-issue-on-discord-windows-11/"><u>How to Tackle the Killer Javascript Issue on Discord Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-huawei-p60-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Huawei P60 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-engage-with-windows-11-privilege-center/"><u>Locate and Engage with Windows 11 Privilege Center</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-d3d11-errors-on-windows-11/"><u>Mastering the Art of Fixing D3D11 Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-stopping-self-generating-chromium-tabs/"><u>Mastering the Art of Stopping Self-Generating Chromium Tabs</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-blade-a73-5g-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Blade A73 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-effective-windows-note-tips-and-tricks/"><u>Quick and Effective Windows Note Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-correcting-the-isdonedll-error-on-windows-11/"><u>Quick Fix: Correcting the ISDone.dll Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-your-roadmap-to-printer-success-in-windows-11/"><u>Quick-Fix Guide: Your Roadmap to Printer Success in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-from-frozen-windows-itunes-a-step-by-step-approach/"><u>Recovering From Frozen Windows iTunes: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/removing-unwanted-html-from-your-windows-11-mail-previews/"><u>Removing Unwanted HTML From Your Windows 11 Mail Previews</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-window-experience-through-shortcuts/"><u>Revolutionize Your Window Experience Through Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-inclusion-of-emoji-15-in-windows-11-systems/"><u>Seamless Inclusion of Emoji 15 in Windows 11 Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solution-when-your-msi-dragon-center-fails/"><u>Step-by-Step Solution: When Your MSI Dragon Center Fails</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-samsung-galaxy-f04-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Samsung Galaxy F04? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/swift-and-simple-fixes-conquer-winerror-740-on-winos/"><u>Swift and Simple Fixes: Conquer WinError 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-elevating-taskmanager-position/"><u>Techniques for Elevating TaskManager Position</u></a></li>
<li><a href="https://win11.techidaily.com/the-fusion-of-ages-seven-windows-characteristics-persisting-into-11/"><u>The Fusion of Ages: Seven Windows Characteristics Persisting Into 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-subtle-art-of-hidden-storage-in-windows-1110/"><u>The Subtle Art of Hidden Storage in Windows 11/10</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-5-essential-factors-to-evaluate-prior-to-purchasing-your-next-gaming-system/"><u>Top 5 Essential Factors to Evaluate Prior to Purchasing Your Next Gaming System</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-strategies-for-successful-folders-management-in-win-11/"><u>Top 7 Strategies for Successful Folders Management in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-videos-on-windows-discover-these-8-outstanding-apps/"><u>Transform Videos on Windows - Discover These 8 Outstanding Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-cooperative-touchscreen-actions-in-windows/"><u>Troubleshooting Non-Cooperative Touchscreen Actions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-update-failure-code-0x80246007-on-1011/"><u>Troubleshooting: Windows Update Failure Code 0X80246007 on 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-ai-in-windows-11-the-co-pilot-effect/"><u>Understanding AI in Windows 11: The Co-Pilot Effect</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-screens-activatingdeactivating-windows-spotlight-features/"><u>Unlocking Screens: Activating/Deactivating Windows' Spotlight Features</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-roblox-error-403-on-windows/"><u>Unraveling Roblox Error 403 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/virtual-box-upgrade-unleashed-migrating-to-version-70-on-windows-11-pcs/"><u>Virtual Box Upgrade Unleashed: Migrating to Version 7.0 on Windows 11 PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/virtual-venues-clash-obstwitch-live-for-2024/"><u>Virtual Venues Clash  OBS/Twitch Live for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>