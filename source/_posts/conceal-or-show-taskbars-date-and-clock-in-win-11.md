---
title: Conceal or Show Taskbar's Date & Clock in Win 11
date: 2025-01-27T22:15:37.594Z
updated: 2025-02-04T08:30:42.112Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conceal or Show Taskbar's Date & Clock in Win 11
excerpt: This Article Describes Conceal or Show Taskbar's Date & Clock in Win 11
keywords: Windows 11 Bar Hide Time,Hide Win 11 Clock,Taskbar Date Conceal,Win 11 Show Hide,Clock on Win Taskbar,Remove Clock Win11,Setup Date Clock Win11
thumbnail: https://thmb.techidaily.com/f5eeb9ebfa2de64a3d4ee3942e718c9f14502e6b864cfccf1cdec1e982bafc3d.jpg
---

## Conceal or Show Taskbar's Date & Clock in Win 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://fox-glue.techidaily.com/new-supreme-reconciliation-of-vr-realms/"><u>[New] Supreme Reconciliation of VR Realms</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-strategies-for-crafting-intriguing-vlog-storylines-for-2024/"><u>[Updated] Strategies for Crafting Intriguing Vlog Storylines for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-velocity-for-the-visionary-quick-frame-android-tools/"><u>2024 Approved Velocity for the Visionary Quick-Frame Android Tools</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/5-facons-efficaces-de-recuperer-un-fichier-zip-perdu-sur-windows/"><u>5 Façons Efficaces De Récupérer Un Fichier Zip Perdu Sur Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oppo-k11-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Oppo K11 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-windows-tapping-into-startup-directories/"><u>Jumpstart Windows: Tapping Into Startup Directories</u></a></li>
<li><a href="https://activate-lock.techidaily.com/latest-guide-on-ipad-23-and-apple-iphone-12-pro-max-icloud-activation-lock-bypass-by-drfone-ios/"><u>Latest Guide on iPad 2/3 and Apple iPhone 12 Pro Max iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://fox-where.techidaily.com/migration-de-donnees-vers-un-ssd-western-digital-en-guidant-sans-reinstallation/"><u>Migration De Données Vers Un SSD Western Digital En Guidant Sans Reinstallation</u></a></li>
<li><a href="https://extra-support.techidaily.com/optimizing-unused-scenes-a-filmmakers-approach-for-2024/"><u>Optimizing Unused Scenes A Filmmaker's Approach for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-lost-tabs-in-navigator-interface/"><u>Recovering Lost Tabs in Navigator Interface</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11s-media-app-a-fix-guide/"><u>Reviving Windows 11'S Media App: A Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/samsungs-dex-breakthrough-control-your-phone-on-windows-with-ease/"><u>Samsung’s DeX Breakthrough: Control Your Phone on Windows with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-error-0xc00ce556-in-winoss/"><u>Steps to Correct Error 0xC00CE556 in WinOSs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-file-management-windows-11s-automatic-deletion-feature-explained/"><u>Streamlining File Management: Windows 11'S Automatic Deletion Feature Explained</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-magic-behind-16gb-memory-in-windows-pcs/"><u>Unveiling the Magic Behind 16GB Memory in Windows PCs</u></a></li>
</ul></div>

