---
title: Mastering the Art of Purging Partitions on Your Win OS
date: 2024-07-13T10:59:19.829Z
updated: 2024-07-14T10:59:19.829Z
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

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

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

 Once you run the above commands, PowerShell will delete the specified partition.

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
<li><a href="https://fox-friendly.techidaily.com/2024-approved-editors-eye-view-visualscape-pro-edition/"><u>2024 Approved  Editor's Eye View  VisualScape Pro Edition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gopro-vs-drift-ghost-speed-camera-showdown-explained-for-2024/"><u>GoPro vs Drift Ghost - Speed Camera Showdown Explained for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-interruptexception-solution-for-win11/"><u>Unveiling INTERRUPT_EXCEPTION Solution for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disconnect-in-windows-remote-play-feature/"><u>Solving Disconnect in Windows Remote Play Feature</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-login-delays-windows-and-rust-edition/"><u>Resolving Steam Login Delays: Windows & Rust Edition</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-poco-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Poco</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-xs-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone XS? Heres the Best Fixes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-step-by-step-guide-live-broadcast-of-recorded-videos-on-fb/"><u>[Updated] Step-by-Step Guide  Live Broadcast of Recorded Videos on FB</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/address-fixing-non-responsive-function-keys-in-win-11-os/"><u>Address: Fixing Non-Responsive Function Keys in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-drawing-apps-for-windows-10/"><u>The 7 Best Drawing Apps for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-11-notification-settings/"><u>Tailor Windows 11 Notification Settings</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-playlist-extraction-made-simple-download-steps-revealed/"><u>2024 Approved  Playlist Extraction Made Simple  Download Steps Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-altering-file-deletion-alerts-in-win/"><u>Steps for Altering File Deletion Alerts in Win</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-excel-is-running-slow-on-windows/"><u>What to Do if Excel Is Running Slow on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-playback-issues-with-windows-errors/"><u>Overcoming Playback Issues with Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-phone-dialer-mechanics/"><u>Unveiling Windows Phone Dialer Mechanics</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-chromes-profiles-issues/"><u>Comprehensive Guide to Fixing Chrome's Profiles Issues</u></a></li>
<li><a href="https://audio-editing.techidaily.com/fine-tuning-sound-from-afar-a-comprehensive-guide-to-changing-volume-speed-and-timbre-over-the-web/"><u>Fine-Tuning Sound From Afar A Comprehensive Guide to Changing Volume, Speed & Timbre Over the Web</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-vivo-s17-pro-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Vivo S17 Pro to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-tools-optimize-multi-screen-brightness/"><u>Top 6 Windows Tools: Optimize Multi-Screen Brightness</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-replacing-sky-in-your-pictures-using-online-and-offline-tools/"><u>New In 2024, Replacing Sky in Your Pictures Using Online and Offline Tools</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-windows-update-failure-0x800f0845/"><u>Dealing with Windows Update Failure - 0X800F0845</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-pixelpunch-custom-humor-images/"><u>In 2024, PixelPunch  Custom Humor Images</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-seamless-mp4-to-fb-video-transfer-technology-for-2024/"><u>[Updated] Seamless MP4-to-FB Video Transfer Technology for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-aspers-secrets-soundscapes-that-lull-you-to-sleep/"><u>In 2024, Asper's Secrets  Soundscapes That Lull You to Sleep</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-powerrename-for-files/"><u>Transforming Chaos: PowerRename for Files</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-control-on-1011-windows-os/"><u>Reinstating Synapse Control on 10/11 Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-faulty-m365-functionality-code-30015-26/"><u>Disabling Faulty M365 Functionality: Code 30015-26</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-do-i-explore-every-shared-piece-by-friends-on-messages-for-2024/"><u>How Do I Explore Every Shared Piece by Friends on Messages for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/probing-the-heart-of-windows-systems-generating-insightful-reports/"><u>Probing the Heart of Windows Systems: Generating Insightful Reports</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-efficiency-counteracting-zero-speed/"><u>Boosting Windows Steam Efficiency: Counteracting Zero-Speed</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10-mastery-how-to-get-best-deals-on-keys/"><u>Windows 10 Mastery: How to Get Best Deals on Keys</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unlock-advanced-capturing-a-guide-to-aiseesoft-screen-recorder-use-for-2024/"><u>[New] Unlock Advanced Capturing  A Guide to Aiseesoft Screen Recorder Use for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-bokeh-magic-top-rated-apps-for-ios-and-android-phones/"><u>New In 2024, Bokeh Magic Top-Rated Apps for iOS and Android Phones</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-some-outdated-your-hardware-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>Identify some outdated your hardware drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-mac-tips-for-effective-lecture-saves/"><u>2024 Approved  Mac Tips for Effective Lecture Saves</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-realme-10t-5g-frp-by-drfone-android/"><u>How Can We Bypass Realme 10T 5G FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-audiovisual-capabilities-through-new-driver-installation/"><u>Boosting Windows Audiovisual Capabilities Through New Driver Installation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-effective-strategies-for-archiving-vimeo-footage/"><u>[New] 2024 Approved  Effective Strategies for Archiving Vimeo Footage</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-chorus-of-creativity-the-mac-studio-experience/"><u>[Updated] In 2024, Chorus of Creativity  The Mac Studio Experience</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-stabilizing-aerial-vision-a-comprehensive-guide-to-choosing-a-gimbal/"><u>[Updated] Stabilizing Aerial Vision  A Comprehensive Guide to Choosing a Gimbal</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-soulful-sounds-for-somber-days-unearthing-emotional-tunes-for-2024/"><u>Updated Soulful Sounds for Somber Days Unearthing Emotional Tunes for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enlightenment-without-cost-marking-the-milestone-of-1500-free-sessions/"><u>Enlightenment Without Cost: Marking the Milestone of 1500 Free Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/win32keygen-understanding-identifying-and-neutralizing-its-threat-to-windows/"><u>Win32/Keygen: Understanding, Identifying & Neutralizing Its Threat to Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-proven-methods-to-prevent-photos-app-freezes-in-windows-10/"><u>[Updated] Proven Methods to Prevent Photos App Freezes in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-file-explorer-on-win11-effective-repair-methods/"><u>Trouble with File Explorer on Win11? Effective Repair Methods</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-mastering-game-capture-windows-11-edition-for-2024/"><u>[Updated] Mastering Game Capture  Windows 11 Edition for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-beginners-blueprint-for-winning-animation-in-windows/"><u>2024 Approved  The Beginner’s Blueprint for Winning Animation in Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-stop-motion-for-beginners-a-comprehensive-guide-to-getting-started/"><u>Updated Stop Motion for Beginners A Comprehensive Guide to Getting Started</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-samsung-galaxy-a34-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719286453674-library-installation/"><u>Library Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-installation-obstacles-for-app-removal-in-windows-11/"><u>Bypassing Installation Obstacles for App Removal in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-fresh-social-media-perspectives-without-the-need-for-tiktok/"><u>[New] Fresh Social Media Perspectives Without the Need for TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/taming-windows-cameras-troubles-with-saves/"><u>Taming Windows Camera's Troubles with Saves</u></a></li>
<li><a href="https://win11.techidaily.com/secure-edge-with-microsofts-advanced-protection-technology-aguard-on-windows-11/"><u>Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-simplifying-subtitle-addition-in-multilingual-vimeo-video-platforms/"><u>[New] 2024 Approved  Simplifying Subtitle Addition in Multilingual Vimeo Video Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-speed-mastering-double-click-on-windows-pc/"><u>Triumph in Speed: Mastering Double-Click on Windows PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-revealing-the-best-of-both-worlds-1-tiktoks-on-twitter-for-2024/"><u>[Updated] Revealing the Best of Both Worlds  #1 TikToks on Twitter for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-secrets-of-high-quality-steam-gameplay-footage/"><u>2024 Approved  Secrets of High-Quality Steam Gameplay Footage</u></a></li>
</ul></div>
