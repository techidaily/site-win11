---
title: "Direct Guide: Square Windows' Interface"
date: 2024-12-06T10:35:22.126Z
updated: 2024-12-12T16:09:42.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Direct Guide: Square Windows' Interface"
excerpt: "This Article Describes Direct Guide: Square Windows' Interface"
keywords: Window Interface Basics,Square Windows Setup,Windows Design Guide,Interactive Window UI,Navigating Square Windows,Simple Window Navigation,Optimizing Square UI
thumbnail: https://thmb.techidaily.com/3cd047344d86e8920c72e515095d66dfd7e255dbcb41fa2030513ad2ed26d835.jpg
---

## Direct Guide: Square Windows' Interface

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-in-2024-visual-consistency-through-masterful-use-of-luts-in-ae/"><u>[New] In 2024, Visual Consistency Through Masterful Use of LUTs in AE</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-exploring-the-core-inside-apples-m1-innovation/"><u>[Updated] 2024 Approved Exploring the Core Inside Apple’s M1 Innovation</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-stratagem-starter-kit-unboxing-business-growth/"><u>[Updated] In 2024, Stratagem Starter Kit Unboxing Business Growth</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-guide-to-understanding-and-joining-a-youtube-media-company/"><u>A Guide to Understanding and Joining a YouTube Media Company</u></a></li>
<li><a href="https://win-web.techidaily.com/announcement-launch-of-emeditor-professional-v13-beta-4-the-latest-text-editing-software-update/"><u>Announcement: Launch of EmEditor Professional v13 Beta 4 - The Latest Text Editing Software Update</u></a></li>
<li><a href="https://extra-information.techidaily.com/concealing-identity-swift-methods-for-picscanner/"><u>Concealing Identity Swift Methods for PicScanner</u></a></li>
<li><a href="https://some-guidance.techidaily.com/defleurage-dimages-des-astuces-simples-pour-un-resultat-impeccable/"><u>Défleurage D'Images: Des Astuces Simples Pour Un Résultat Impeccable</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-win11-writings-using-ai-master/"><u>Elevate Win11' Writings Using AI Master</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-operate-and-access-windows-component-services-console/"><u>How to Operate and Access Windows’ Component Services Console</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/live-and-record-flawlessly-find-the-best-conference-tech-today-for-2024/"><u>Live and Record Flawlessly - Find the Best Conference Tech Today for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-missing-data-in-the-windows-1011-search-feature/"><u>Methods to Rectify Missing Data in the Windows 10/11 Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-troubleshooting-the-case-of-the-gone-print-management/"><u>Navigating Troubleshooting: The Case of the Gone Print Management</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/skype-call-chronicles-20plus-strategies-for-savvy-windowsmac-users-for-2024/"><u>Skype Call Chronicles 20+ Strategies for Savvy Windows/Mac Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-editing-mastering-windows-photo-keys/"><u>Speedy Editing: Mastering Windows Photo Keys</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-12-prominent-motorola-razr-40-ultra-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Motorola Razr 40 Ultra Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-window-blunders-what-every-novice-should-dodge/"><u>Top 8 Window Blunders: What Every Novice Should Dodge</u></a></li>
<li><a href="https://win11.techidaily.com/unjamming-the-amd-195-pipeline-on-windows-systems/"><u>Unjamming the AMD 195 Pipeline on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-network-issues-windows-error-code-0x800704b3/"><u>Unlocking Network Issues: Windows Error Code 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tactics-for-disguising-language-line-feature/"><u>Windows 11: Tactics for Disguising Language Line Feature</u></a></li>
</ul></div>

