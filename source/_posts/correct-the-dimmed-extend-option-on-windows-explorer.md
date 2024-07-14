---
title: Correct the Dimmed Extend Option on Windows Explorer
date: 2024-07-13T09:46:03.027Z
updated: 2024-07-14T09:46:03.027Z
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

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

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

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
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
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-motorola-moto-g-5g-2023-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Motorola Moto G 5G (2023) Phone When You Forget the Password</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-11-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-10-key-strategies-to-enhance-insta-highlights/"><u>[Updated] 10 Key Strategies to Enhance Insta Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>Planning to Use a Pokemon Go Joystick on Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-notch-techniques-for-saving-online-radio-broadcasts-for-2024/"><u>Top-Notch Techniques for Saving Online Radio Broadcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://win11.techidaily.com/1719364636660-self-hosted-windows-gptclone-via-gpt4all/"><u>Self-Hosted Windows GPTClone via GPT4All</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-beyond-the-basics-secrets-for-tiktok-live-studio-success/"><u>New Beyond the Basics Secrets for TikTok Live Studio Success</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x100-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Vivo X100 Phone with Broken Screen</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-efficient-facebook-video-extraction-procedures/"><u>[Updated] 2024 Approved  Efficient Facebook Video Extraction Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-high-definition-on-demand-samsungs-ue590-monitor-revisited/"><u>[Updated] High Definition on Demand  Samsung's UE590 Monitor Revisited</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cutting-edge-creativity-top-10-online-trimmer-apps-reviewed-for-2024/"><u>Cutting Edge Creativity - Top 10 Online Trimmer Apps Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-open-the-sound-settings-in-windows-11/"><u>9 Ways to Open the Sound Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719383152108-tackle-lagginess-in-winoutlook-effortlessly/"><u>Tackle Lagginess in WinOutlook, Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-the-windows-11-mixer-interface/"><u>A Beginner’s Guide to the Windows 11 Mixer Interface</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-ultimate-guide-10-tiktok-tactics/"><u>2024 Approved  The Ultimate Guide  10 TikTok Tactics</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-honor-90-lite-lock-screen-password-by-drfone-android/"><u>How to Reset your Honor 90 Lite Lock Screen Password</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-restoring-content-servers-connectivity/"><u>A Step-by-Step Guide to Restoring Content Servers' Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dimension-of-cleanliness-windows-eraser-feature/"><u>A New Dimension of Cleanliness: Windows' Eraser Feature</u></a></li>
<li><a href="https://screen-capture.techidaily.com/how-to-pick-a-preferred-screen-recorder-app-for-2024/"><u>How to Pick a Preferred Screen Recorder App for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-slack-notifications-not-working-on-windows-11/"><u>8 Ways to Fix Slack Notifications Not Working on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-freesync-review-the-latest-from-lg-27uhd68-monitor-for-2024/"><u>[New] FreeSync Review  The Latest From LG 27UHD68 Monitor for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
</ul></div>
