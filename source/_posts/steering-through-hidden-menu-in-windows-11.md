---
title: Steering Through Hidden Menu in Windows 11
date: 2024-12-07T03:30:29.546Z
updated: 2024-12-12T17:12:08.114Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steering Through Hidden Menu in Windows 11
excerpt: This Article Describes Steering Through Hidden Menu in Windows 11
keywords: Navigate Windows 11 Menus,Unveil Windows Navigation,Master Windows Hidden Items,Explore Windows Features,Access Windows Extras Easily,Find Windows Submenus,Decipher Windows Interface
thumbnail: https://thmb.techidaily.com/36f59289f42403367e98ee01ecd7f903ee9a9399b65951332a255432e2acfb47.jpg
---

## Steering Through Hidden Menu in Windows 11

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/updated-dazzle-with-directors-lighting-tips-for-captivating-clips/"><u>[Updated] Dazzle with Directors' Lighting Tips for Captivating Clips</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-decode-and-resolve-youtube-short-errors-for-2024/"><u>[Updated] Decode and Resolve YouTube Short Errors for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-a-visual-journey-the-art-of-editing-with-snapchat-filters/"><u>2024 Approved A Visual Journey The Art of Editing with Snapchat Filters</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-notetaking-tips-for-windows-users/"><u>Convenient Notetaking Tips for Windows Users</u></a></li>
<li><a href="https://win-studio.techidaily.com/enhancing-your-computers-speed-and-stability-with-expert-tips-from-yl-software/"><u>Enhancing Your Computer's Speed & Stability with Expert Tips From YL Software</u></a></li>
<li><a href="https://fox-http.techidaily.com/from-youtube-to-high-quality-mpegs-the-essential-guide/"><u>From YouTube to High-Quality MPEGs The Essential Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gemini-unleashed-1m-tokens-redefine-market-value/"><u>Gemini Unleashed - $1M Tokens Redefine Market Value</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-inside-the-core-of-xstream-studios-an-exhaustive-studio-guide/"><u>In 2024, Inside the Core of XStream Studios – An Exhaustive Studio Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quantifying-videography-storage-needs-128gb/"><u>In 2024, Quantifying Videography Storage Needs, 128GB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obs-on-pc-overcoming-launching-problems/"><u>OBS on PC: Overcoming Launching Problems</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-walkthrough-to-tablet-bar-setup-in-windows-11/"><u>The Complete Walkthrough to Tablet Bar Setup in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-win1011-error-0x800700e1/"><u>Troubleshooting Win10/11 Error 0X800700E1</u></a></li>
<li><a href="https://win11.techidaily.com/win-steam-tips-for-overcoming-offline-problems/"><u>Win Steam: Tips for Overcoming Offline Problems</u></a></li>
</ul></div>

