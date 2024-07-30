---
title: Correct the Dimmed Extend Option on Windows Explorer
date: 2024-07-29T15:46:07.548Z
updated: 2024-07-30T15:46:07.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correct the Dimmed Extend Option on Windows Explorer
excerpt: This Article Describes Correct the Dimmed Extend Option on Windows Explorer
keywords: Fix Windows Explorer Fade,Resolve Dimming Issue,Enhance Window Brightness,Correct Explorer Visibility,Tweak Windows Display,Adjust Explore Shadows,Modify View Extension
thumbnail: https://thmb.techidaily.com/f1ae1ebf673254b46f0a821d8d5736e61a916c4eb6fabc72096593a99e32594f.png
---

## Correct the Dimmed Extend Option on Windows Explorer

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-how-intova-x-changes-action-camera-game/"><u>[New] How Intova X Changes Action Camera Game</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-imovie-harmony-blending-visuals-and-melodies/"><u>[New] IMovie Harmony  Blending Visuals and Melodies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-premium-serene-pc-games-catalog/"><u>[New] In 2024, Premium Serene PC Games Catalog</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-master-memes-access-to-premium-free-designs/"><u>[New] Master Memes  Access to Premium FREE Designs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-top-5-secure-downloader-apps-for-fb-video-extraction-for-2024/"><u>[New] Top 5 Secure Downloader Apps for FB Video Extraction for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-balancing-visual-elements-with-ideal-video-ratios/"><u>[Updated] Balancing Visual Elements with Ideal Video Ratios</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-go-frame-by-frame-on-youtube-video-5-methods/"><u>[Updated] How to Go Frame by Frame on YouTube Video? [5 Methods]</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-snapshot-your-mobile-gamers-high-scores-on-samsungs/"><u>[Updated] In 2024, Snapshot Your Mobile Gamers' High Scores on Samsungs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-video-selfie-verification-on-instagram-helpful-or-hype/"><u>[Updated] In 2024, Video Selfie Verification on Instagram - Helpful or Hype?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-quick-tips-extracting-and-keeping-gif-tweets-for-2024/"><u>[Updated] Quick Tips  Extracting and Keeping GIF Tweets for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-analyzing-abrupt-pauses-in-your-photobooth-experience/"><u>2024 Approved  Analyzing Abrupt Pauses in Your Photobooth Experience</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-master-the-art-of-captivating-audiences-in-tiktok-unpack-videos/"><u>2024 Approved  Master the Art of Captivating Audiences in TikTok Unpack Videos</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-finding-out-what-model-you-run-on-windows/"><u>A Simple Guide to Finding Out What Model You Run on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-universal-companion-windows-now-app-for-iosmac-and-windows-devices/"><u>A Universal Companion: Windows Now App for iOS/Mac and Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-configuration-of-win11-connectivity-options/"><u>Accessible Configuration of Win11 Connectivity Options</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-perfect-sizing-of-your-pics-with-these-six-windows-11-tactics/"><u>Achieve Perfect Sizing of Your Pics with These Six Windows 11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-filter-keys-on-microsoft-os/"><u>Activating/Deactivating Filter Keys on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-qt-platform-support-error-for-app-starts/"><u>Addressing 'No Qt Platform Support' Error for App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audio-output-not-found-in-windows/"><u>Addressing Audio Output Not Found in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-runtime-exceptions-your-ultimate-guide-for-windows-users/"><u>Addressing Runtime Exceptions: Your Ultimate Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alert-it-admin-limited-power/"><u>Addressing Windows Alert: IT Admin Limited Power</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-steam-transfers-averting-sudden-halt/"><u>Amplify Windows Steam Transfers: Averting Sudden Halt</u></a></li>
<li><a href="https://win11.techidaily.com/android-transition-post-subsystem-discontinuation-whats-next/"><u>Android Transition Post-Subsystem Discontinuation: What's Next?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-of-taskbar-in-modern-win11/"><u>Boosting Functionality of Taskbar in Modern Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-screen-legibility-win11-scaling-guide/"><u>Boosting Screen Legibility: Win11 Scaling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-run-handbrake-in-windows/"><u>Breaking Barriers: Run HandBrake in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tial-gear-picking-the-very-best-among-top-9-free-logomakers/"><u>Essential Gear  Picking the Very Best Among Top 9 Free Logomakers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-mobile-privacy-the-best-7-adblocker-apps-for-android/"><u>Essential Mobile Privacy  The Best 7 AdBlocker Apps for Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-scene-to-video-canons-pathway-to-timelapse-excellence-for-2024/"><u>From Scene to Video  Canon's Pathway to Timelapse Excellence for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-a70-by-fonelab-android-recover-music/"><u>How to retrieve erased music from A70</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-samsung-galaxy-s24-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Samsung Galaxy S24 in Minutes | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-xiaomi-redmi-note-13-pro-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Xiaomi Redmi Note 13 Pro 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-frugal-shopping-for-cheap-vr-headsets-china/"><u>In 2024, Frugal Shopping for Cheap VR Headsets (China)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-zte-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on ZTE Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-oppo-f23-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Oppo F23 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-lava-yuva-3-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Lava Yuva 3 to Another | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-oneplus-12-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from OnePlus 12 to iPod | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-p55-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Itel P55 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-lava-blaze-pro-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Lava Blaze Pro 5G Without PUK Codes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Samsung Galaxy A54 5G? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-top-7-grand-strategy-masterpieces-for-epic-battles/"><u>In 2024, Top 7 Grand Strategy Masterpieces for Epic Battles</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transform-your-canon-shots-access-to-unlimited-free-and-purchasable-luts/"><u>In 2024, Transform Your Canon Shots  Access to Unlimited Free & Purchasable LUTs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-winning-at-movie-watching-leading-windows-phone-apps/"><u>In 2024, Winning at Movie Watching  Leading Windows Phone Apps</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-pro-level-mp3-cutting-discover-the-top-5-online-platforms/"><u>New Pro-Level MP3 Cutting Discover the Top 5 Online Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/1719350786682-operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze</u></a></li>
<li><a href="https://extra-hints.techidaily.com/professional-photography-hacks-perfecting-motion-blur-with-adobe-tools/"><u>Professional Photography Hacks  Perfecting Motion Blur with Adobe Tools</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://techidaily.com/solved-mac-doesnt-recognize-my-iphone-xs-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Mac Doesnt Recognize my iPhone XS Max | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
</ul></div>
