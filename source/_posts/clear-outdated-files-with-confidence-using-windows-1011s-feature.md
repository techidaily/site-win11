---
title: Clear Outdated Files with Confidence Using Windows 10/11'S Feature
date: 2024-07-29T15:56:10.423Z
updated: 2024-07-30T15:56:10.423Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clear Outdated Files with Confidence Using Windows 10/11'S Feature
excerpt: This Article Describes Clear Outdated Files with Confidence Using Windows 10/11'S Feature
keywords: Clear Files Windows 10,Update Old Windows Files,Confident File Cleaning,Windows Updater Tool,Deleting Outdated Data,Secure File Removal,Windows 10/11 Cleanup
thumbnail: https://thmb.techidaily.com/4f408d1e600338fdfbc4fe3abf110c58fed31529d9f9f53c6cd72af0ec21a5e5.jpg
---

## Clear Outdated Files with Confidence Using Windows 10/11'S Feature

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-the-road-to-profitable-facebook-marketing-through-engaging-ads/"><u>[New] 2024 Approved  The Road to Profitable Facebook Marketing Through Engaging Ads</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-analyzing-lightroom-for-mobile-a-detailed-exploration/"><u>[New] Analyzing Lightroom for Mobile  A Detailed Exploration</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-elite-5-non-twitter-channels-online/"><u>[New] In 2024, Elite 5 Non-Twitter Channels Online</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ap-into-the-secrets-of-successful-video-thumbnails-for-youtube/"><u>[New] Tap Into the Secrets of Successful Video Thumbnails for YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-examining-the-limitations-of-immersive-tech/"><u>[Updated] Examining the Limitations of Immersive Tech</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-demystifying-youtubes-video-editing-power/"><u>[Updated] In 2024, Demystifying YouTube's Video Editing Power</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-survivals-thrill-top-picks-for-heart-pounding-zombie-games/"><u>[Updated] In 2024, Survival's Thrill  Top Picks for Heart-Pounding Zombie Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unlocking-full-potential-the-laptop-recording-manual/"><u>[Updated] In 2024, Unlocking Full Potential  The Laptop Recording Manual</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-perfect-your-recording-a-comparison-guide-for-30-vs-60fps/"><u>[Updated] Perfect Your Recording  A Comparison Guide for 30 Vs. 60FPS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-irrelevance-of-licensing-in-truth/"><u>[Updated] The Irrelevance of Licensing in Truth</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-dust-off-the-glare-avoiding-gopro-misting/"><u>2024 Approved  Dust Off the Glare  Avoiding GoPro Misting</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unlocking-potential-secrets-to-successful-fb-video-ads/"><u>2024 Approved  Unlocking Potential  Secrets to Successful FB Video Ads</u></a></li>
<li><a href="https://win11.techidaily.com/7-w11-ui-aspects-that-seem-out-of-place/"><u>7 W11 UI Aspects That Seem Out of Place</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-wi-fi-showing-limited-access-in-windows-11/"><u>9 Ways to Fix Wi-Fi Showing Limited Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-slumberful-cycle-for-your-pcs-life/"><u>A Slumberful Cycle for Your PC's Life</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-error-pitfalls-with-anydesk-on-windows-platforms/"><u>Avoiding Error Pitfalls with AnyDesk on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-cpu-consumption-by-dropbox-on-windows-pcs/"><u>Decreasing Excessive CPU Consumption by Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-discoverability-of-lost-network-elements-in-winos/"><u>Enhancing Discoverability of Lost Network Elements in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/escape-heavy-requirements-tiny11-delight/"><u>Escape Heavy Requirements: Tiny11 Delight</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-the-differences-between-srgb-and-rgb-for-2024/"><u>Exploring the Differences Between Srgb & Rgb for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/from-obscured-space-to-optimization-windows-guide-for-reclaiming-disk/"><u>From Obscured Space to Optimization: Windows Guide for Reclaiming Disk</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-reconnect-controlled-audio-from-windows-bluetooth-devices/"><u>Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-glitches-in-microsofts-nearby-sharing-service/"><u>Handling Glitches in Microsoft's Nearby Sharing Service</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-superior-control-over-windows-11-task-management/"><u>How to Activate Superior Control Over Windows 11 Task Management</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-and-retrieve-picturesvideos-from-a-water-damaged-iphone-12-that-wont-turn-on-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix & Retrieve Pictures/Videos From a Water Damaged iPhone 12 That Wont Turn on | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-tecno-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Tecno</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-face-edits-leading-iphone-and-android-apps/"><u>In 2024, Expert Face Edits  Leading iPhone & Android Apps</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-plan-ahead-on-instagram-rankings-of-the-top-8-scheduling-apps/"><u>In 2024, Plan Ahead on Instagram  Rankings of The Top 8 Scheduling Apps</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-video-conferencing-enhance-scene-details-upward-for-2024/"><u>Mastering Video Conferencing  Enhance Scene Details Upward for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximizing-visual-potential-with-hdr-technology-for-2024/"><u>Maximizing Visual Potential with HDR Technology for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://extra-information.techidaily.com/precision-in-every-frame-top-9-tips-for-vr-filmmaking/"><u>Precision in Every Frame  Top 9 Tips for VR Filmmaking</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-restoring-secure-file-connections-on-win/"><u>Strategies for Restoring Secure File Connections on Win</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-troubleshooting-fs-problems-on-windows-11/"><u>Strategies for Troubleshooting FS Problems on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-strategies-with-a-focus-on-windows-diskusage/"><u>Streamlining Storage Strategies with a Focus on Windows' DiskUsage</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-multiple-computers-to-one-printer-seamlessly/"><u>Syncing Multiple Computers to One Printer Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-a-sleeker-system-auto-delete-files-on-windows/"><u>The Key to a Sleeker System: Auto-Delete Files on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-iphone-13-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass iPhone 13 Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/the-overlooked-duo-of-windows-monitoring-metrics/"><u>The Overlooked Duo of Windows Monitoring Metrics</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-oneplus-nord-n30-se-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 OnePlus Nord N30 SE Android SIM Unlock APK</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-esd-format-to-compatible-windows-isos/"><u>Transforming ESD Format to Compatible Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-another-users-ms-error-on-pc/"><u>Troubleshooting: Another User's MS Error on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-ms-office-erase-error-code-0x80041015/"><u>Unlocking Windows MS Office: Erase Error Code 0X80041015</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>