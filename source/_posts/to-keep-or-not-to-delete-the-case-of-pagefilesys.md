---
title: "To Keep or Not to Delete: The Case of Pagefile.sys"
date: 2024-07-29T15:49:02.736Z
updated: 2024-07-30T15:49:02.736Z
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
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

 As you can see, the Pagefile.sys file is quite large, which makes many people think deleting it is a good idea when they're running out of storage space.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Should You Delete Pagefile.sys?

 One scenario where it would be reasonable to delete Pagefile.sys to save disk space is if you have a lot of RAM. That way, it can store all the data it needs to keep apps running without needing to offload them. For the average Windows user, the minimum RAM size for this would be 16GB.

 If you delete Pagefile.sys and your computer runs out of physical memory, your system will start to become sluggish. If the sluggishness gets too bad, Windows itself might even crash.

 Also, you might notice some apps becoming slower or crashing as well. That’s because they have nowhere to put the data they need to operate properly since your computer’s RAM is full and there is no Pagefile.sys to pick up the slack.

 So unless your physical memory needs aren’t greater than your installed RAM’s capacity, we recommend leaving Pagefile.sys alone.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Delete Pagefile.sys

 Since Windows is constantly using Pagefile.sys, it will not allow you to delete it in File Explorer directly. In fact, if you selected the file and hit the**Delete** key, you will see the following message: "The action can't be completed because the file is open in another program."

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![deleting-pagefile-error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deleting-pagefile-error.jpg)

 However, there’s another method you can use to delete the file and save some disk space. To do that, follow the steps below.

1. Press**Win + S** to open Windows Search.
2. Type**sysdm.cpl** in the search box and hit the**Enter** key to open the System Properties window.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![the About page of the System window in the Settings app on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-about-windows-11.jpg)
4. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
5. In the Performance Options window, select the**Advanced** tab and click**Change** .
6. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
7. Click on the radio button for**Custom size** . Immediately, you’ll see that the two text boxes below it (**Initial size** and**Maximum size**) are no longer grayed out.
8. Enter the appropriate page file sizes in megabytes (MB) in both text boxes and then click**Set** .  
![the virtual memory dialog box on windows with the custom page file size set to 4096](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/virtual-memory-custom-size.jpg)
9. Click**OK** to close the Virtual Memory window and apply the changes.
10. Restart your Windows computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-elevating-your-channel-with-strategic-picture-posts/"><u>[Updated] 2024 Approved  Elevating Your Channel with Strategic Picture Posts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-streamlined-video-tools-for-twitter-sharing/"><u>[Updated] 2024 Approved  Streamlined Video Tools for Twitter Sharing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-complete-guide-to-mastering-instagrams-filter-features/"><u>[Updated] 2024 Approved  The Complete Guide to Mastering Instagram's Filter Features</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-analyzing-t-series-revenue-generation-on-youtube-channels/"><u>[Updated] Analyzing T-Series' Revenue Generation on Youtube Channels</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-perfecting-your-yt-visual-footprint/"><u>[Updated] The Ultimate Guide to Perfecting Your YT Visual Footprint</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-choice-of-no-cost-video-calls-plus-shared-screens-selection-for-2024/"><u>[Updated] Top Choice of No-Cost Video Calls + Shared Screens Selection for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-uncompromised-audio-with-ffmpegs-extraction-features/"><u>[Updated] Uncompromised Audio with FFmpeg's Extraction Features</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-young-entrepreneurs-guide-buying-profitable-youtube-sites/"><u>[Updated] Young Entrepreneur's Guide  Buying Profitable YouTube Sites</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hidden-echoes-to-silence-audacitys-technique-guide/"><u>2024 Approved  Hidden Echoes to Silence  Audacity's Technique Guide</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-non-adjacent-partition-integration/"><u>A Comprehensive Guide to Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://win11.techidaily.com/a-handy-guide-to-resolving-windows-filesystem-problems/"><u>A Handy Guide to Resolving Windows Filesystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/a-handy-manual-assessing-and-annulling-window-history-data/"><u>A Handy Manual: Assessing & Annulling Window History Data</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win-utorrent-downloads-tips-and-tricks/"><u>Accelerate Win uTorrent Downloads: Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-overcoming-wwe-2k23-freezes-in-windows/"><u>Accelerated Action: Overcoming WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-valorant-playthrough-with-optimized-pc-settings/"><u>Achieve Peak Valorant Playthrough with Optimized PC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-macos-window-ambiance-on-windows-pc/"><u>Achieving MacOS Window Ambiance on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-compression-and-archiving-tools/"><u>Activating Windows Compression & Archiving Tools</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-configuration-backup-by-nvidia-cp/"><u>Addressing Missing Configuration Backup by Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-surge-in-cpu-usage-by-wlanext/"><u>Addressing the Surge in CPU Usage by WLANEXT</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-code-0xca00a009/"><u>Addressing Windows Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-monitor-settings-quickly/"><u>Adjusting Monitor Settings Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-user-management-via-windows-terminal/"><u>Advanced User Management via Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-excessive-cpu-usage-by-tiworkerexe-software/"><u>Alleviating Excessive CPU Usage by TiWorker.exe Software</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-troubles-15-windows-fixes-to-consider/"><u>Arrow Troubles? 15 Windows Fixes to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-game-access-blocks-fixing-unreachable-errors/"><u>Avoiding Game Access Blocks: Fixing Unreachable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-thermal-load-of-windows-11-devices/"><u>Balancing the Thermal Load of Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-xffffeee-error-from-your-inkjet-printer/"><u>Banishing XFFFFEEE Error From Your Inkjet Printer</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-windows-overload-7-ways-to-fix-too-many-requests-error/"><u>Beating Back Window's Overload: 7 Ways to Fix Too Many Requests Error</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-excels-speed-on-windows-pcs/"><u>Boost Your Excel's Speed on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-productivity-the-ultimate-toolkit-of-5plus-apps/"><u>Boost Your Windows Productivity: The Ultimate Toolkit of 5+ Apps</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-linux-capabilities-using-windows-utilities/"><u>Boosting Linux Capabilities Using Windows Utilities</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-6s-plus-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 6s Plus Apple ID and Apple Pay</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-avchd-mts-files-on-motorola-g54-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to play AVCHD MTS files on Motorola G54 5G?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-honor-x50-gt-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Honor X50 GT Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-avi-to-gif-transformation-using-filmora-for-both-oses/"><u>In 2024, The Ultimate Guide to AVI-to-GIF Transformation Using Filmora for Both OSes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-top-economical-live-capture-software-suite/"><u>In 2024, Top Economical Live Capture Software Suite</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/insider-secrets-to-record-sims-gaming-for-2024/"><u>Insider Secrets to Record Sims Gaming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719325122258-overcome-your-win11-chrome-freeze-effective-fix-strategies/"><u>Overcome Your Win11 Chrome Freeze: Effective Fix Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/1719359386759-overcoming-dim-windows-11-screens-tips-inside/"><u>Overcoming Dim Windows 11 Screens - Tips Inside</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Oppo A59 5G | Dr.fone</u></a></li>
</ul></div>
