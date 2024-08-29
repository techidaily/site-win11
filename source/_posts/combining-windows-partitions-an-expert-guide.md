---
title: "Combining Windows Partitions: An Expert Guide"
date: 2024-08-28T00:53:33.537Z
updated: 2024-08-29T00:53:33.537Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Combining Windows Partitions: An Expert Guide"
excerpt: "This Article Describes Combining Windows Partitions: An Expert Guide"
keywords: Windows Partition Combine,Partition Merge Tips,Mastering Disk Partition,Windows Space Joining,Optimize Windows Sectors,Expert Partition Guide,Uniting Windows Volumes
thumbnail: https://thmb.techidaily.com/4f7677089ce9d876fde36aa600317f042b44ee73a802e442be2008c2b3992f0d.jpg
---

## Combining Windows Partitions: An Expert Guide

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
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  
![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-best-ios-video-streaming-tools-for-iphones-ipads/"><u>[New] Best iOS Video Streaming Tools for iPhones, iPads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-guide-to-recording-adobe-presentation-videos/"><u>[New] Guide to Recording Adobe Presentation Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-igniting-virality-with-captivating-fb-giveaway-campaigns/"><u>[New] Igniting Virality with Captivating FB Giveaway Campaigns</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-creative-command-center-studio-for-youtubers/"><u>[New] In 2024, Creative Command Center  Studio for YouTubers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-the-art-of-haul-video-shopping-showcasing-and-editing/"><u>[New] Mastering the Art of Haul Video  Shopping, Showcasing & Editing</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nleash-the-full-potential-of-youtube-with-variable-playback-rates-for-2024/"><u>[New] Unleash the Full Potential of YouTube With Variable Playback Rates for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-break-free-the-chuckles-the-most-hilarious-facebook-detainment-stories/"><u>[Updated] Break Free the Chuckles  The Most Hilarious Facebook Detainment Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-financial-motives-in-consumer-video-evaluations/"><u>[Updated] Financial Motives in Consumer Video Evaluations?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-10-zoom-recording-essentials-for-2024/"><u>[Updated] Top 10 Zoom Recording Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719316562070-boosting-window-light-in-windows-11-top-solutions-explored/"><u>Boosting Window Light in Windows 11: Top Solutions Explored!</u></a></li>
<li><a href="https://win11.techidaily.com/delaying-windows-11-shutdown-techniques-for-active-processestasks/"><u>Delaying Windows 11 Shutdown: Techniques for Active Processes/Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-computer-experience-with-worldwide-mouse-expertise-in-powertoys/"><u>Enhance Your Computer Experience with Worldwide Mouse Expertise in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/evaluate-your-needs-best-windows-11-choice-between-home-and-pro/"><u>Evaluate Your Needs: Best Windows 11 Choice Between Home and Pro</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-mystery-of-not-found-in-windows-pc/"><u>Fixing the Mystery of 'Not Found' In Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unclog-printer-usage-jams-in-win11/"><u>Guide to Unclog Printer Usage Jams in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-c67-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Realme C67 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-0x800700e1-in-windows-10-and-11/"><u>How to Fix Error 0X800700E1 in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-10-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 10 & 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-lava-agni-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reclaim-your-spot-in-epic-launcher-windows-style/"><u>How to Reclaim Your Spot in Epic Launcher, Windows-Style</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-the-application-couldnt-start-error-code-0xc000003e-on-win11/"><u>How to Rectify The The Application Couldn't Start Error Code 0XC000003e on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-hard-drive-type-hddssd/"><u>Identifying Hard Drive Type: HDD/SSD</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-erase-discord-server-settings-desktopsmartphones/"><u>In 2024, Erase Discord Server Settings (Desktop/Smartphones)</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-honor-x9b-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Honor X9b Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x90s-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Vivo X90S Bootloader Easily</u></a></li>
<li><a href="https://tech-haven.techidaily.com/in-the-world-of-ai-is-claude-more-advanced-than-chatgpt-evaluating-top-tier-chatbots/"><u>In The World of AI, Is Claude More Advanced Than ChatGPT? Evaluating Top-Tier Chatbots</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-contextual-menu-additions-in-win1011/"><u>Mastering Contextual Menu Additions in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-control-in-windows-11-os/"><u>Mastering Highlight Control in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ipmac-discovery-on-windows-ps-style/"><u>Mastering IP/MAC Discovery on Windows, PS Style</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-batch-to-executable-conversion-in-windows/"><u>Mastering the Art of Batch-to-Executable Conversion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-net-ensuring-stable-connections/"><u>Mastering Windows Net: Ensuring Stable Connections</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-direct-image-access-with-windows-11/"><u>Maximizing Direct Image Access with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-failed-geforce-scans-on-pcs-running-windows/"><u>Navigating Failed GeForce Scans on PCs Running Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-complexities-of-high-dpi-settings/"><u>Navigating Through the Complexities of High-DPI Settings</u></a></li>
<li><a href="https://win-able.techidaily.com/overcome-extended-launch-delays-in-fallout-4-with-these-easy-solutions/"><u>Overcome Extended Launch Delays in Fallout 4 with These Easy Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/power-through-work-on-windows-our-picks-for-the-best-5plus-productivity-tools/"><u>Power Through Work on Windows: Our Picks for the Best 5+ Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-a-swaying-cursor-in-windows-os/"><u>Resolving a Swaying Cursor in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-wsl-the-4294967295-error-explained/"><u>Resolving WSL: The 4294967295 Error Explained</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-severe-javascript-crashes-in-discord-on-pcs-running-win-1011/"><u>Sidestep Severe JavaScript Crashes in Discord on PCs Running Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solutions-for-win-11-issues-through-shortcut-buttons-guide/"><u>Speedy Solutions for Win 11 Issues Through Shortcut Buttons Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-unblock-printer-access-in-windows-11/"><u>Steps to Unblock Printer Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-with-w11-pinning-tips/"><u>Streamline Your Desktop with W11 Pinning Tips</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-harmonized-workspaces-in-win1011/"><u>The Path to Harmonized Workspaces in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-stealth-attacker-uncovered-defending-windows-against-wacatacbml/"><u>The Stealth Attacker Uncovered: Defending Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-guide-to-inexpensive-cams/"><u>The Ultimate Guide to Inexpensive Cams</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-streamlining-storage-in-win-11/"><u>The Ultimate Guide to Streamlining Storage in Win 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-htc-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your HTC Phone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3dx939dll-absence-on-windows-11/"><u>Troubleshooting D3DX9_39.dll Absence on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-the-isdonedll-isarcextract-fault-on-pcs/"><u>Troubleshooting the ISDone.dll (ISArcExtract) Fault on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-system-call-failures-in-windows-11/"><u>Troubleshooting: Resolving System Call Failures in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-install-clipchamp-on-windows-11-try-these-fixes/"><u>Unable to Install ClipChamp on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/winning-workflows-6-top-time-management-apps-reviewed/"><u>Winning Workflows: 6 Top Time Management Apps Reviewed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>