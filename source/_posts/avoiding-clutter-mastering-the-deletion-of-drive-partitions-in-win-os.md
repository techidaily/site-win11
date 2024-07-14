---
title: "Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS"
date: 2024-07-13T11:18:51.697Z
updated: 2024-07-14T11:18:51.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS"
excerpt: "This Article Describes Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS"
keywords: Delete Windows Partition,Win OS Partition Cleanup,Clear Drive Space Win,Avoid Drive Clutter Win,Win Deletion Guide,Optimize Win OS Drives,Simplify Win File Management
thumbnail: https://thmb.techidaily.com/052918d3e56b96021eca7b3225588078d8b2ee409e0b799bdcb8f9f006f59b01.jpg
---

## Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS

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
<li><a href="https://youtube-video-recordings.techidaily.com/becoming-a-pro-in-video-game-broadcasts/"><u>Becoming a Pro in Video Game Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-error-unauthorized-file-reading-in-win11/"><u>Addressing Steam Error: Unauthorized File Reading in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-window-settings-unseen-toolbar-configurations/"><u>Advanced Window Settings: Unseen Toolbar Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/app-and-browser-domination-on-windows-os/"><u>App & Browser Domination on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/activation-verification-methods-for-windows-11/"><u>Activation Verification Methods for Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-srt-revelation-transforming-computer-performance/"><u>In 2024, SRT Revelation  Transforming Computer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-multi-archive-handling-in-windows-os/"><u>Advanced Multi-Archive Handling in Windows OS</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-6-plus-drfone-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transitioning-from-sierra-to-legacy-os-el-capitan/"><u>[New] Transitioning From Sierra To Legacy OS - El Capitan</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-concealment-for-windows-11-task-view-icon/"><u>Advanced Concealment for Windows 11 Task View Icon</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ultimate-guide-to-action-film-snapshotting/"><u>In 2024, Ultimate Guide to Action Film Snapshotting</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-in-the-ms-store-a-step-by-step-guide/"><u>Accelerating Downloads in the MS Store - A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-c-spans-watchlist-for-the-curious-netizen/"><u>2024 Approved  C-Span's Watchlist for the Curious Netizen</u></a></li>
<li><a href="https://win11.techidaily.com/altwindirstat-reigniting-your-file-systems-potential-on-windows/"><u>AltWinDirStat: Reigniting Your File System's Potential on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-media-error-your-input-not-opened-by-vlc/"><u>Addressing Media Error: Your Input Not Opened by VLC</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-age-old-directx-experience-via-dxvk-compatibility/"><u>Amplifying Age-Old DirectX Experience via DXVK Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-seo-power-play-strategies-to-amplify-your-podcasts-impact/"><u>[Updated] SEO Power Play  Strategies To Amplify Your Podcast's Impact</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-malfunctions-in-windows-batch-file-systems/"><u>Addressing Malfunctions in Windows Batch File Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-endless-entertainment-loop-youtube-videos-for-continuous-tv-viewing/"><u>[Updated] In 2024, Endless Entertainment Loop  YouTube Videos for Continuous TV Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-portaudio-hiccup-on-windows-11-and-11/"><u>Addressing Audacity’s PortAudio Hiccup on Windows 11 & 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/video-testimonials-the-trusted-connection-for-2024/"><u>Video Testimonials  The Trusted Connection for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-skyline-pixel-boost-pro-windowsmac-suite/"><u>[New] Skyline Pixel Boost Pro  Windows/Mac Suite</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unleash-your-creativity-free-gif-loop-creator-tools/"><u>Updated Unleash Your Creativity Free GIF Loop Creator Tools</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-for-windowsapps-acquisition/"><u>Advanced Methods for WindowsApps Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-clutter-pro-tips-to-adhere-sticky-notes-on-w11w10/"><u>Avoid Clutter: Pro Tips to Adhere Sticky Notes on W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/access-from-afar-zero-password-connectivity-on-win-11/"><u>Access From Afar: Zero-Password Connectivity on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-if-you-want-to-replace-or-delete-the-sky-pictures-or-background-media-then-give-a-quick-read-to-this-article-for-effective-solutions/"><u>New In 2024, If You Want to Replace or Delete the Sky Pictures or Background Media, Then Give a Quick Read to This Article for Effective Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-mouse-dynamics-for-a-more-natural-response-in-win-1011/"><u>Adjusting Mouse Dynamics for a More Natural Response in Win 10/11</u></a></li>
</ul></div>
