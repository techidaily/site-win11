---
title: Revealing Windows 11'S System Tray Secrets
date: 2025-01-23T08:36:04.489Z
updated: 2025-01-24T22:42:56.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revealing Windows 11'S System Tray Secrets
excerpt: This Article Describes Revealing Windows 11'S System Tray Secrets
keywords: Windows 11 SysTray Info,W11 System Tray,Windows Tray Secrets,SysTray Uncovered W11,W11 Hidden SysTray,Discover W11 Tray,Tray Secrets in Win11
thumbnail: https://thmb.techidaily.com/84a4620f422e4279d6cc9c20449448701c42416dfe9f4fbdd744755993fb5c2e.png
---

## Revealing Windows 11'S System Tray Secrets

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/new-boosting-youtube-popularity-two-simple-strategies/"><u>[New] Boosting YouTube Popularity Two Simple Strategies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-cinematic-tools-the-leading-camera-selections/"><u>[Updated] Cinematic Tools The Leading Camera Selections</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-guide-to-rapid-or-slowdown-youtubes-playback-adjustments/"><u>[Updated] Guide to Rapid or Slowdown YouTube's Playback Adjustments</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-creating-an-impactful-film-short-summary/"><u>[Updated] In 2024, Creating an Impactful Film Short Summary</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-photo-clips-melody-layers-in-new-videos/"><u>2024 Approved Photo Clips, Melody Layers in New Videos</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-vibrancy-to-windows-extended-volume-controls/"><u>Bring Back Vibrancy to Windows’ Extended Volume Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-0x800713f-in-windows-1011s-mail-app/"><u>Bypassing 0X800713F in Windows 10/11'S Mail App</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-cluttered-drives-the-defrag-walkthrough/"><u>Clearing Cluttered Drives: The Defrag Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-black-screen-problem-in-windows-marketplace/"><u>Clearing Up Black Screen Problem in Windows Marketplace</u></a></li>
<li><a href="https://win-news.techidaily.com/creating-a-custom-theme-from-active-setups-in-flipbuilder-easy-tutorial/"><u>Creating a Custom Theme From Active Setups in FlipBuilder - Easy Tutorial</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mememagic-app-unleash-your-comedic-genius-online/"><u>In 2024, MemeMagic App - Unleash Your Comedic Genius Online</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/insider-secrets-to-sharpen-your-photoshop-skills-for-2024/"><u>Insider Secrets to Sharpen Your Photoshop Skills for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-fix-for-windows-11-supported/"><u>Nvidia Fix for Windows 11 Supported</u></a></li>
</ul></div>

