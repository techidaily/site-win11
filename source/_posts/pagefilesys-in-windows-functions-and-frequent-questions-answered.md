---
title: "Pagefile.sys in Windows: Functions & Frequent Questions Answered"
date: 2024-10-09T16:45:44.050Z
updated: 2024-10-15T18:04:49.180Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pagefile.sys in Windows: Functions & Frequent Questions Answered"
excerpt: "This Article Describes Pagefile.sys in Windows: Functions & Frequent Questions Answered"
keywords: Windows Pagefile,Pagefile Usage,System Pagefile,File Sys Page,Paging File FAQ,File Sys Functions,Windows Memory Storage
thumbnail: https://thmb.techidaily.com/b46b34fd5ad4244a5b3542fda6e0ba281358e5c36628241992e02c966a06886d.jpg
---

## Pagefile.sys in Windows: Functions & Frequent Questions Answered

 When your Windows computer is running out of storage space, you may find yourself looking for ways to free up some of it, even if they're a bit unconventional. One of these unconventional methods you may come across is deleting the Pagefile.sys file. But before you consider deleting it, you should know what Pagefile.sys is and if you should delete it in the first place.

Here's what you need to know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Pagefile.sys?

 Pagefile.sys is a system file in Windows set aside for your computer’s[Random Access Memory (RAM)](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , also known as physical memory. When your computer's RAM begins to run out of memory, it uses the pagefile to offload data it doesn't need, such as files and apps.

 So how does your computer’s RAM decide when to offload data? Let’s use an app as an example of how this works.

 Usually, when you minimize an app, Windows will leave it running in the background. However, it will keep its data in the RAM so it can quickly access them when needed.

 Then, when you boot up a RAM-intensive app, Windows needs to make room for it within the RAM. As such, Windows will instruct your PC’s RAM to dump the minimized app’s program files into Pagefile.sys, so it can free up memory without losing data.

 By default, Windows will store Pagefile.sys in the root folder of your local drive (C:).

 When you need to use the minimized app again, Windows will read its data from the Pagefile.sys file. And you'll be none the wiser that it's compensating for its physical memory shortcomings with the help of your local drive.

 Reading an app’s program files from Pagefile.sys is slower than reading them from RAM. The process is even slower when you're using a hard disk drive (HDD)[instead of a solid-state drive (SDD)](https://www.makeuseof.com/choose-ssd-or-hdd-storage/) . However, It’s faster than closing the app and then relaunching it.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Size of Pagefile.sys

 To prevent tampering with Pagefile.sys, Windows will hide it by default. If you want to see it, here’s what you should do.

1. Press**Win + E** to open File Explorer.
2. Click on**This PC** in the navigation pane on the left and double-click your**local drive (C:)** on the right to open it.
3. Now you need to open Folder Options. On Windows 11, click the**three vertical dots** in the top menu and select**Options** . On Windows 10, click**View** in the top menu and then on**Options** .  
![selecting options in the top menu of file explorer in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/file-explorer-options.jpg)
4. Select the**View** tab in Folder Options and uncheck**Hide protected operating system files (Recommended)** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the system properties dialog box in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/system-properties-advanced.jpg)
4. In the Performance Options window, select the**Advanced** tab and click**Change** .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the Perfomance Options window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/performance-options-advanced.jpg)
5. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
6. Click on the radio button for**No paging file** , and click the**Set** button on the right.  
![the Virtual Memory window on Windows with the No paging radio button ticked](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-no-paging-windows.jpg)
7. You’ll get a warning from Windows. Click**Yes** to bypass it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Click on**OK** to close the Virtual Memory window and apply the changes.
9. Restart your Windows computer for the changes to take effect.

 When Windows boots back up, the OS will have no use for Pagefile.sys, and it will delete it from your local drive. It will also delete the Swapfile.sys along with it. If you don't know what that file is and its importance, please read our guide on[what Swapfile.sys is and if you can delete it](https://www.makeuseof.com/windows-swapfile-sys-guide/) .

## How to Restore Pagefile.sys

 If you deleted Pagefile.sys and discovered that you're experiencing problems because of it, you can easily restore it. However, if the problems are so severe that Windows is constantly freezing or can't even boot up properly, you should try entering Safe Mode first. To do that, please check out guides on[ways to boot into Safe Mode on Windows 11](https://www.makeuseof.com/windows-11-boot-safe-mode/) and[what is Safe Mode on Windows 10](https://www.makeuseof.com/windows-11-boot-safe-mode/) .

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
<li><a href="https://extra-tips.techidaily.com/new-assessing-virtual-realitys-dual-facets-pros-and-cons/"><u>[New] Assessing Virtual Reality’s Dual Facets Pros & Cons</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-expert-tips-add-ons-that-elevate-your-vimeo-video/"><u>[New] In 2024, Expert Tips Add-Ons that Elevate Your Vimeo Video</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-unveiling-the-secret-sauce-for-astonishing-gifs-from-vimeo-videos-for-2024/"><u>[New] Unveiling the Secret Sauce for Astonishing GIFs From Vimeo Videos for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-keep-your-shorts-viewer-friendly-fixing-image-absence/"><u>[Updated] In 2024, Keep Your Shorts Viewer-Friendly Fixing Image Absence</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-ultimate-vlogging-battle-gopro-hero5-black-vs-sessions/"><u>[Updated] In 2024, The Ultimate Vlogging Battle GoPro Hero5 Black VS Sessions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-2023-facebook-live-video-downloaders/"><u>2024 Approved 2023 Facebook Live Video Downloaders</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/boost-your-productivity-essential-ai-tools-for-writers/"><u>Boost Your Productivity: Essential AI Tools for Writers</u></a></li>
<li><a href="https://solve-helper.techidaily.com/dvd-video-3/"><u>DVD Video変換無料ソフトの一般的なエラーと解消方法 - 第3章</u></a></li>
<li><a href="https://win11.techidaily.com/peering-beyond-the-visible-launching-windows-concealed-character-insight-engine/"><u>Peering Beyond the Visible: Launching Windows' Concealed Character Insight Engine</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-spotify-link-troubles-with-win11/"><u>Resolving Spotify Link Troubles with Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-disabling-windows-license-deadline-alerts/"><u>Solutions for Disabling Windows License Deadline Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/solving-print-sharing-snags-with-step-by-step/"><u>Solving Print Sharing Snags with Step-by-Step</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-stuck-dilemma-easy-fixes-for-madden-nfl-22-loading-issues/"><u>Solving the 'Stuck' Dilemma: Easy Fixes for Madden NFL 22 Loading Issues</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-your-computer-restart-the-windows-11-fast-startup-guide/"><u>Speeding Up Your Computer Restart: The Windows 11 Fast Startup Guide</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-phone-pc-connection-with-windows-11/"><u>Streamlining the Phone-PC Connection with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-starting-afresh-with-windows-11-installation/"><u>The Art of Starting Afresh with Windows 11 Installation</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-reno-10-pro-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Reno 10 Pro 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-modifying-windows-1011-nat-settings/"><u>Understanding and Modifying Windows 10/11 NAT Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-fixes-for-windows-11s-grayed-out-memory-option/"><u>Unveiling Hidden Fixes for Windows 11’S Grayed-Out Memory Option</u></a></li>
</ul></div>

