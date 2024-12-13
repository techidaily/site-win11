---
title: How to Turn Search Highlights On and Off on Windows 11
date: 2024-12-10T21:36:08.645Z
updated: 2024-12-12T21:14:48.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Search Highlights On and Off on Windows 11
excerpt: This Article Describes How to Turn Search Highlights On and Off on Windows 11
keywords: Win11 Highlight Control,Windows 11 Search Off/On,Manage Windows Highlighting,Enable Windows Search Highlights,Turn On/Off Windows Highlights,Adjust Windows 11 Search Features,Highlight Settings in Windows 11
thumbnail: https://thmb.techidaily.com/7713f731aa5d1a79b016145c24d7f030b3ba8189c712906ad5104406a0711035.jpg
---

## How to Turn Search Highlights On and Off on Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-ultimate-guide-to-youtube-autoplay-on-facebook/"><u>[New] In 2024, The Ultimate Guide to YouTube Autoplay on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-path-not-found-on-pc-networks/"><u>Addressing Path Not Found on PC Networks</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-winget-on-w11/"><u>Comprehensive Guide to Fixing Winget on W11</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-instructions-eradicating-wsl-from-windows/"><u>Comprehensive Instructions: Eradicating WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deleting-windows-bt-directory-purpose-and-process/"><u>Deleting Windows ~BT Directory: Purpose & Process</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/exciting-enhancements-top-new-functionalities-of-apples-watchos-11-revealed/"><u>Exciting Enhancements: Top New Functionalities of Apple's WatchOS 11 Revealed</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/harnessing-the-power-of-multilingual-potential-in-english/"><u>Harnessing the Power of Multilingual Potential in English</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-control-slider-not-working-in-windows-11-and-11/"><u>How to Fix the Volume Control Slider Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-apple-iphone-15-plus-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your Apple iPhone 15 Plus Apple ID and Apple Pay</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-art-of-words-on-the-screen-crafting-clear-concise-dialogue/"><u>In 2024, The Art of Words on the Screen Crafting Clear, Concise Dialogue</u></a></li>
<li><a href="https://article-files.techidaily.com/masterful-digital-brushstrokes-essential-top-10-android-graphics-apps/"><u>Masterful Digital Brushstrokes Essential Top 10 Android Graphics Apps</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-microsoft-powerpoint-prints-on-windows/"><u>Navigating the Maze of Microsoft PowerPoint Prints on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-erratic-behavior-of-windows-event-viewer/"><u>Resolving Erratic Behavior of Windows Event Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-task-of-updating-administrator-name-on-windows-11/"><u>Simplifying the Task of Updating Administrator Name on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-top-7-online-auto-subtitle-translators-for-content-creators/"><u>Updated 2024 Approved Top 7 Online Auto Subtitle Translators for Content Creators</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    