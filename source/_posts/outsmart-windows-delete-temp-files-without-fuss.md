---
title: "Outsmart Windows: Delete Temp Files Without Fuss"
date: 2024-08-16T00:40:47.792Z
updated: 2024-08-17T00:40:47.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Outsmart Windows: Delete Temp Files Without Fuss"
excerpt: "This Article Describes Outsmart Windows: Delete Temp Files Without Fuss"
keywords: Deleting TempFiles Easy,Uninstall Windows Carelessly,Eliminate System Junk,Bypass Windows Trash,Clear TempSpace Hassle-Free,Erase Files No Fuss,Forget Temp Waste Quickly
thumbnail: https://thmb.techidaily.com/2a29084ef28c5d6ebf693615660d627bf6405cc5a8ac614e41f7b335143de3df.jpg
---

## Outsmart Windows: Delete Temp Files Without Fuss

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-innovate-in-fb-advertising-access-no-cost-video-tools/"><u>[New] Innovate in FB Advertising - Access No-Cost Video Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-jujutsu-kaisens-tiktok-a-creative-journey-for-2024/"><u>[New] Jujutsu Kaisen's TikTok  A Creative Journey for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unleash-creativity-with-these-4-simple-steps-to-loops-on-instagram/"><u>[New] Unleash Creativity with These 4 Simple Steps to Loops on Instagram</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-top-tier-innovations-in-virtual-reality-setup/"><u>[Updated] 2024 Approved  Top-Tier Innovations in Virtual Reality Setup</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-channeling-creativity-get-green-screen-tips-from-youtube/"><u>[Updated] Channeling Creativity  Get Green Screen Tips From YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-overflowed-drafters-to-ordered-files-learn-to-edit-hefty-tiktok-content/"><u>[Updated] From Overflowed Drafters to Ordered Files  Learn to Edit Hefty TikTok Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-upload-videos-to-youtube-a-step-by-step-guide-for-2024/"><u>[Updated] How To Upload Videos to YouTube [a Step-by-Step Guide] for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-how-to-delete-messages-on-discord/"><u>[Updated] In 2024, How To Delete Messages On Discord</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-maximizing-your-screen-real-estate-with-picture-in-picture-creation/"><u>2024 Approved  Maximizing Your Screen Real Estate with Picture in Picture Creation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-unraveling-the-secrets-of-excellent-screen-recording-with-recmeister/"><u>2024 Approved  Unraveling the Secrets of Excellent Screen Recording with Recmeister</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-stop-the-background-from-automatically-changing-on-windows-11/"><u>6 Ways to Stop the Background From Automatically Changing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-windows-11s-speedy-startup/"><u>A Beginner's Guide to Windows 11'S Speedy Startup</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-guide-to-infusing-personality-into-your-calendar/"><u>A Window's Guide to Infusing Personality Into Your Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-type-speed-cutting-down-lag-on-windows-11/"><u>Accelerating Type Speed: Cutting Down Lag on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/acceleration-at-fingertips-3-ways-to-enhance-mouse-double-click-speed/"><u>Acceleration at Fingertips: 3 Ways to Enhance Mouse Double-Click Speed</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activating-local-administrator-tools-in-windows-1110-home/"><u>Activating Local Administrator Tools in Windows 11/10 Home</u></a></li>
<li><a href="https://win11.techidaily.com/adapt-window-placement-for-windows-os/"><u>Adapt Window Placement for Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-system-breakdown-windows-c0000022-fixes/"><u>Addressing Critical System Breakdown: Windows C0000022 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-empty-folder-warning-windows/"><u>Addressing Empty Folder Warning Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alert-it-admin-limited-power/"><u>Addressing Windows Alert: IT Admin Limited Power</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-pc-energy-utilization-efficiency/"><u>Assessing Windows PC Energy Utilization Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-mastering-the-deletion-of-drive-partitions-in-win-os/"><u>Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/black-out-bliss-with-microsofts-basic-brush/"><u>Black-Out Bliss with Microsoft's Basic Brush</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win1011-graphics-power-the-ultimate-guide-to-vram/"><u>Boosting Win10/11 Graphics Power: The Ultimate Guide to VRAM</u></a></li>
<li><a href="https://article-helps.techidaily.com/comparative-review-dji-phantom-3-vs-competitors/"><u>Comparative Review  DJI Phantom 3 vs Competitors</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-g54-5g-support-mov-videos-by-aiseesoft-video-converter-play-mov-on-android/"><u>Does G54 5G support MOV videos ?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/easy-guide-to-using-your-phone-as-an-alternative-camera/"><u>Easy Guide to Using Your Phone as an Alternative Camera</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/echoing-empathy-french-movie-magic/"><u>Echoing Empathy: French Movie Magic</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enhance-leadership-by-mastering-effective-communication-tools/"><u>Enhance Leadership by Mastering Effective Communication Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-announce-a-donation-drive-a-step-by-step-guide/"><u>How to Announce a Donation Drive  A Step-by-Step Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-8-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For Apple iPhone 8?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-inshot-unveiled-effortless-laptoppc-video-editing/"><u>In 2024, Inshot Unveiled  Effortless Laptop/PC Video Editing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-insight-into-watermark-functionality-for-fb-media/"><u>In 2024, Insight Into Watermark Functionality for Fb Media</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-most-effective-ways-to-bypass-iphone-13-mini-activation-lock-by-drfone-ios/"><u>In 2024, The Most Effective Ways to Bypass iPhone 13 mini Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/1719307817163-keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ltimate-playlist-in-10-seconds-youtube-shorts-explained-for-2024/"><u>The Ultimate Playlist in 10 Seconds  YouTube Shorts Explained for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-verdict-on-asus-zephyrus-g14-a-cutting-edge-no-compromise-laptop-for-gamers/"><u>The Ultimate Verdict on Asus Zephyrus G14 - A Cutting-Edge, No Compromise Laptop for Gamers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-unlinkage-from-youtube-shorts-complete-guide-for-2024/"><u>Total Unlinkage From YouTube Shorts  Complete Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transformative-video-editing-techniques-for-viral-tiktok-creations-for-2024/"><u>Transformative Video Editing Techniques for Viral TikTok Creations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/video-selfie-verification-on-instagram-helpful-or-hype/"><u>Video Selfie Verification on Instagram - Helpful or Hype?</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/windows-stellar-file-wiper-5-professional-track-and-schedule-data-deletion/"><u>Windows Stellar File Wiper 5: Professional Track and Schedule Data Deletion</u></a></li>
</ul></div>
