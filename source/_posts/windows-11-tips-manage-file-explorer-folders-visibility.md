---
title: "Windows 11 Tips: Manage File Explorer Folders Visibility"
date: 2024-11-29T17:27:55.032Z
updated: 2024-12-06T20:00:52.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Tips: Manage File Explorer Folders Visibility"
excerpt: "This Article Describes Windows 11 Tips: Manage File Explorer Folders Visibility"
keywords: Windows 11 File Organization,File Explorer Hidden Folder Guide,Optimize Windows 11 Explorer View,Windows 11 Explore Privacy Settings,Visibility Control in W11 File Explorer,Secure File Explorer Display Mode,Enhancing Windows 11 Explorer Views
thumbnail: https://thmb.techidaily.com/faf305db1bff9ec7cfb8fafeb68d0a5e6478101d40a48c00d6fe1d681c9c048c.jpg
---

## Windows 11 Tips: Manage File Explorer Folders Visibility

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-bridging-the-gap-luts-from-cg-central-to-movie-colors/"><u>[Updated] In 2024, Bridging the Gap Luts From CG Central to Movie Colors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-mastering-android-screenshots-in-4-steps/"><u>[Updated] In 2024, Mastering Android Screenshots in 4 Steps</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-ultimate-guide-to-dimming-down-soundtracks-in-premiere-pro/"><u>2024 Approved The Ultimate Guide to Dimming Down Soundtracks in Premiere Pro</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-itel-p55-5g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Itel P55 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-functionality-resource-details-at-a-glance/"><u>Elevate SysTray Functionality: Resource Details at a Glance</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-a-dead-windows-11-wi-fi-hotspot/"><u>Essential Fixes for a Dead Windows 11 Wi-Fi Hotspot</u></a></li>
<li><a href="https://win11.techidaily.com/fuel-efficiency-the-best-pc-optimization-tools-on-a-win/"><u>Fuel Efficiency: The Best PC Optimization Tools on a Win</u></a></li>
<li><a href="https://win11.techidaily.com/guide-overturn-custom-power-plans-in-windows/"><u>Guide: Overturn Custom Power Plans in WIndows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-audience-engagement-on-demand-top-5-mac-streaming-tools/"><u>In 2024, Audience Engagement On Demand Top 5 Mac Streaming Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-definitive-2023-bandicam-handbook-for-gamers/"><u>In 2024, The Definitive 2023 Bandicam Handbook for Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-use-of-windows-subsystem-essential-tips-for-success/"><u>Optimal Use of Windows Subsystem: Essential Tips for Success</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-windows-11-experience-with-these-tools/"><u>Overhaul Your Windows 11 Experience with These Tools</u></a></li>
<li><a href="https://win11.techidaily.com/peer-to-peer-pro-winning-torrent-apps-for-your-pc/"><u>Peer-to-Peer Pro: Winning Torrent Apps for Your PC</u></a></li>
<li><a href="https://fox-that.techidaily.com/quick-fix-for-slow-mobile-internet-accelerate-with-simple-steps/"><u>Quick Fix for Slow Mobile Internet: Accelerate with Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-off-switched-network-notifications-windows/"><u>Resolving Off Switched Network Notifications Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/the-future-of-gaming-recordings-via-graphics-processing/"><u>The Future of Gaming Recordings via Graphics Processing</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-poco-c55-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Poco C55 Screen | Dr.fone</u></a></li>
</ul></div>

