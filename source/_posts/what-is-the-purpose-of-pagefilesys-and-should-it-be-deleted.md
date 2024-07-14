---
title: What Is the Purpose of Pagefile.sys and Should It Be Deleted?
date: 2024-07-13T09:43:47.688Z
updated: 2024-07-14T09:43:47.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Is the Purpose of Pagefile.sys and Should It Be Deleted?
excerpt: This Article Describes What Is the Purpose of Pagefile.sys and Should It Be Deleted?
keywords: Pagefile-Purpose,DeletePagefile,SystemPageFile,FileSystemUsage,PurposeOfPagefile,RemoveFileSys,PagefileFunction
thumbnail: https://thmb.techidaily.com/67c52f8f8d1e1c526acfd18d30076a8ec8c694652a5ccde76155c26629dae8fb.png
---

## What Is the Purpose of Pagefile.sys and Should It Be Deleted?

 When your Windows computer is running out of storage space, you may find yourself looking for ways to free up some of it, even if they're a bit unconventional. One of these unconventional methods you may come across is deleting the Pagefile.sys file. But before you consider deleting it, you should know what Pagefile.sys is and if you should delete it in the first place.

Here's what you need to know.

## What Is Pagefile.sys?

 Pagefile.sys is a system file in Windows set aside for your computer’s [Random Access Memory (RAM)](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , also known as physical memory. When your computer's RAM begins to run out of memory, it uses the pagefile to offload data it doesn't need, such as files and apps.

 So how does your computer’s RAM decide when to offload data? Let’s use an app as an example of how this works.

 Usually, when you minimize an app, Windows will leave it running in the background. However, it will keep its data in the RAM so it can quickly access them when needed.

 Then, when you boot up a RAM-intensive app, Windows needs to make room for it within the RAM. As such, Windows will instruct your PC’s RAM to dump the minimized app’s program files into Pagefile.sys, so it can free up memory without losing data.

 By default, Windows will store Pagefile.sys in the root folder of your local drive (C:).

 When you need to use the minimized app again, Windows will read its data from the Pagefile.sys file. And you'll be none the wiser that it's compensating for its physical memory shortcomings with the help of your local drive.

 Reading an app’s program files from Pagefile.sys is slower than reading them from RAM. The process is even slower when you're using a hard disk drive (HDD)[instead of a solid-state drive (SDD)](https://www.makeuseof.com/choose-ssd-or-hdd-storage/) . However, It’s faster than closing the app and then relaunching it.

## How to Check the Size of Pagefile.sys

 To prevent tampering with Pagefile.sys, Windows will hide it by default. If you want to see it, here’s what you should do.

1. Press**Win + E** to open File Explorer.
2. Click on**This PC** in the navigation pane on the left and double-click your**local drive (C:)** on the right to open it.
3. Now you need to open Folder Options. On Windows 11, click the**three vertical dots** in the top menu and select**Options** . On Windows 10, click**View** in the top menu and then on**Options** .  
![selecting options in the top menu of file explorer in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/file-explorer-options.jpg)
4. Select the**View** tab in Folder Options and uncheck**Hide protected operating system files (Recommended)** .  
![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

 As you can see, the Pagefile.sys file is quite large, which makes many people think deleting it is a good idea when they're running out of storage space.

## Should You Delete Pagefile.sys?

 One scenario where it would be reasonable to delete Pagefile.sys to save disk space is if you have a lot of RAM. That way, it can store all the data it needs to keep apps running without needing to offload them. For the average Windows user, the minimum RAM size for this would be 16GB.

 If you delete Pagefile.sys and your computer runs out of physical memory, your system will start to become sluggish. If the sluggishness gets too bad, Windows itself might even crash.

 Also, you might notice some apps becoming slower or crashing as well. That’s because they have nowhere to put the data they need to operate properly since your computer’s RAM is full and there is no Pagefile.sys to pick up the slack.

 So unless your physical memory needs aren’t greater than your installed RAM’s capacity, we recommend leaving Pagefile.sys alone.

## How to Delete Pagefile.sys

 Since Windows is constantly using Pagefile.sys, it will not allow you to delete it in File Explorer directly. In fact, if you selected the file and hit the**Delete** key, you will see the following message: "The action can't be completed because the file is open in another program."

![deleting-pagefile-error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deleting-pagefile-error.jpg)

 However, there’s another method you can use to delete the file and save some disk space. To do that, follow the steps below.

1. Press**Win + S** to open Windows Search.
2. Type**sysdm.cpl** in the search box and hit the**Enter** key to open the System Properties window.  
![searching for sysdm.cpl in windows search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-search-sysdm-cpl.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.  
![the system properties dialog box in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/system-properties-advanced.jpg)
4. In the Performance Options window, select the**Advanced** tab and click**Change** .  
![the Perfomance Options window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/performance-options-advanced.jpg)
5. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
6. Click on the radio button for**No paging file** , and click the**Set** button on the right.  
![the Virtual Memory window on Windows with the No paging radio button ticked](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-no-paging-windows.jpg)
7. You’ll get a warning from Windows. Click**Yes** to bypass it.
8. Click on**OK** to close the Virtual Memory window and apply the changes.
9. Restart your Windows computer for the changes to take effect.

 When Windows boots back up, the OS will have no use for Pagefile.sys, and it will delete it from your local drive. It will also delete the Swapfile.sys along with it. If you don't know what that file is and its importance, please read our guide on [what Swapfile.sys is and if you can delete it](https://www.makeuseof.com/windows-swapfile-sys-guide/) .

## How to Restore Pagefile.sys

 If you deleted Pagefile.sys and discovered that you're experiencing problems because of it, you can easily restore it. However, if the problems are so severe that Windows is constantly freezing or can't even boot up properly, you should try entering Safe Mode first. To do that, please check out guides on [ways to boot into Safe Mode on Windows 11](https://www.makeuseof.com/windows-11-boot-safe-mode/) and [what is Safe Mode on Windows 10](https://www.makeuseof.com/windows-11-boot-safe-mode/) .

Now, to bring back Pagefile.sys, follow the steps below:

1. Press**Win + R** to open Windows Run.
2. In the text box, enter**sysdm.cpl** and then hit the**Enter** key to launch the System Properties window.  
![opening the System Properties window using Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-system-properties-windows-run.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
4. In the Performance Options window, select the**Advanced** tab and click**Change** .
5. In the Virtual Memory window, make sure the**Automatically manage paging file size for all drives** checkbox at the top is checked.
6. Click on**OK** to close the Virtual Memory window and apply the changes.
7. Restart your Windows computer for the changes to take effect.

 Once your computer boots up, and you go to the folder where Pagefile.sys is located, you will see that the file has returned, along with Swapfile.sys.

## How to Resize Pagefile.sys

 If deleting Pagefile.sys isn’t an option for you, consider resizing it instead. Here’s how to do that:

1. Press**Win + E** to open File Explorer.
2. In the Navigation Pane, right-click**This PC** and select**Properties** . On Windows 11, you will have to select**Show more options** first before you can see the**Properties** option.
3. Click on the**Advanced system settings** link to open the System Properties window. On Windows 11, you will find the link on the right panel, while, on Windows 10, it will be on the left side menu.  
![the About page of the System window in the Settings app on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-about-windows-11.jpg)
4. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
5. In the Performance Options window, select the**Advanced** tab and click**Change** .
6. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
7. Click on the radio button for**Custom size** . Immediately, you’ll see that the two text boxes below it (**Initial size** and**Maximum size**) are no longer grayed out.
8. Enter the appropriate page file sizes in megabytes (MB) in both text boxes and then click**Set** .  
![the virtual memory dialog box on windows with the custom page file size set to 4096](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/virtual-memory-custom-size.jpg)
9. Click**OK** to close the Virtual Memory window and apply the changes.
10. Restart your Windows computer for the changes to take effect.

## Pagefile.sys, Demystified

 Pagefile.sys is an extremely important file when it comes to keeping your Windows computer running smoothly. It helps give your PC's RAM more breathing room when physical memory can no longer hold more data. You can delete it, but only do so when you know your computer's RAM has enough capacity to stand on its own. If not, you’re better off just resizing Pagefile.sys so it doesn’t take up too much space.

 If you’re unsure of what to do with Pagefile.sys, just leave it to Windows to handle the file and look for other ways to free up space on your storage drive.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-your-content-impact-with-insights-from-social-blade-on-youtube/"><u>[Updated] Maximize Your Content Impact with Insights From Social Blade on YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-discovering-facebooks-quintessential-updates/"><u>[New] In 2024, Discovering Facebook's Quintessential Updates</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-finding-top-8-free-reliable-srt-translator-picks-online/"><u>[New] Finding Top 8 Free, Reliable SRT Translator Picks Online</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-rise-with-the-pros-acquire-1k-ig-admirers-daily/"><u>[New] Rise with the Pros  Acquire 1K IG Admirers Daily</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-lava-storm-5g-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Lava Storm 5G FRP</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unleash-the-full-potential-of-your-images-with-snapchat/"><u>[New] In 2024, Unleash the Full Potential of Your Images with Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-typing-experience-speed-up-windows-keyboard-delay/"><u>Enhance Your Typing Experience: Speed Up Windows Keyboard Delay</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pro-level-phone-and-camera-gimbal-tracking-systems/"><u>In 2024, Pro-Level Phone & Camera Gimbal Tracking Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-essential-summary-5-superior-cost-free-audio-volume-correctors/"><u>Updated In 2024, The Essential Summary 5 Superior, Cost-Free Audio Volume Correctors</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-8-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 8 iOS System? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-redmi-note-12-pro-4g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Redmi Note 12 Pro 4G</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-obs-issue-full-screen-bug-fixed/"><u>[Updated] 2024 Approved  Obs Issue  Full-Screen Bug Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-nubia-z50s-pro-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Nubia Z50S Pro Device</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-fast-to-slow-mastering-slow-motion-video-creation-on-kapwing/"><u>New From Fast to Slow Mastering Slow-Motion Video Creation on Kapwing</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
</ul></div>
