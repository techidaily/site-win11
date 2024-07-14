---
title: "To Keep or Not to Delete: The Case of Pagefile.sys"
date: 2024-07-13T09:49:45.956Z
updated: 2024-07-14T09:49:45.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes To Keep or Not to Delete: The Case of Pagefile.sys"
excerpt: "This Article Describes To Keep or Not to Delete: The Case of Pagefile.sys"
keywords: Pagefile_system,File_preservation,System_snapshot,Data_retention,Delete_risks,Pagefile_purge,Storage_health
thumbnail: https://thmb.techidaily.com/8823459ab6574b19c976d6905c67df41ee5da35193b7ba8be663bba21950e5e8.jpg
---

## To Keep or Not to Delete: The Case of Pagefile.sys

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
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-the-power-of-words-crafting-impactful-documentary-narratives/"><u>Unleash the Power of Words  Crafting Impactful Documentary Narratives</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-media-error-your-input-not-opened-by-vlc/"><u>Addressing Media Error: Your Input Not Opened by VLC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-portaudio-hiccup-on-windows-11-and-11/"><u>Addressing Audacity’s PortAudio Hiccup on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-error-unauthorized-file-reading-in-win11/"><u>Addressing Steam Error: Unauthorized File Reading in Win11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-on-apple-iphone-11-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked On Apple iPhone 11?</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-clutter-pro-tips-to-adhere-sticky-notes-on-w11w10/"><u>Avoid Clutter: Pro Tips to Adhere Sticky Notes on W11/W10</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-rapid-replay-adjusting-video-duration-in-keynote/"><u>2024 Approved  Rapid Replay  Adjusting Video Duration in Keynote</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-window-settings-unseen-toolbar-configurations/"><u>Advanced Window Settings: Unseen Toolbar Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-switch-cards-between-apple-iphone-8-and-other-iphones-will-move-all-phone-services-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Switch Cards Between Apple iPhone 8 and other iPhones Will Move All Phone Services? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-malfunctions-in-windows-batch-file-systems/"><u>Addressing Malfunctions in Windows Batch File Systems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exploring-earning-potential-revenue-from-youtube-advertisements-in-2024/"><u>[Updated] Exploring Earning Potential  Revenue From YouTube Advertisements, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-concealment-for-windows-11-task-view-icon/"><u>Advanced Concealment for Windows 11 Task View Icon</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-best-cloud-storage-service-for-videos/"><u>Updated Best Cloud Storage Service for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-achieve-social-stardom-essential-tips-for-thriving-instagram-unboxings/"><u>In 2024, Achieve Social Stardom  Essential Tips for Thriving Instagram Unboxings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-11-taskbar/"><u>Addressing Non-Operational Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-age-old-directx-experience-via-dxvk-compatibility/"><u>Amplifying Age-Old DirectX Experience via DXVK Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-convert-live-facebook-videos-to-mp3s-on-the-fly/"><u>In 2024, Convert Live Facebook Videos to MP3s on the Fly</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1714310328940-updated-there-are-several-options-for-smoothing-and-stabilizing-motion-in-after-effects-stable-footage-the-three-most-important-methods-to-master-are-listed/"><u>Updated There Are Several Options for Smoothing and Stabilizing Motion in After Effects Stable Footage. The Three Most Important Methods to Master Are Listed Below for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-key-differences-between-cloud-and-physical-windows-installations/"><u>Assessing Key Differences Between Cloud and Physical Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
</ul></div>
