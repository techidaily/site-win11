---
title: Illuminating the Veiled Parts of Windows 11 UI
date: 2024-11-26T01:12:07.607Z
updated: 2024-11-28T04:30:14.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Illuminating the Veiled Parts of Windows 11 UI
excerpt: This Article Describes Illuminating the Veiled Parts of Windows 11 UI
keywords: Win11UIEnlightenment,UXWindowsUnveiling,Windows11InterfaceLights,UIVeiledWindowsInsight,UncoveredWinUX,IlluminatedWinUser,WindowsUIShadowExplore
thumbnail: https://thmb.techidaily.com/afa50b24e25ed08989c229ae73d3b233da6ab60b7cf21c80e9cb56c9f6856e1f.jpg
---

## Illuminating the Veiled Parts of Windows 11 UI

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-yielding-yearly-yield-channel-to-currency-conversion/"><u>[New] 2024 Approved Yielding Yearly Yield Channel to Currency Conversion</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-strategies-for-creating-a-positive-interview-environment/"><u>[New] In 2024, Strategies for Creating a Positive Interview Environment</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effective-strategies-for-avoiding-knots-in-your-3d-printing-filaments/"><u>Effective Strategies for Avoiding Knots in Your 3D Printing Filaments</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/get-your-favorite-films-and-tunes-instantly-with-einthusan-downloader/"><u>Get Your Favorite Films & Tunes Instantly with Einthusan Downloader</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-enjoy-every-star-wars-movie-in-chronological-order-with-disneyplus-a-step-by-step-guide/"><u>How to Enjoy Every 'Star Wars' Movie in Chronological Order with Disney+: A Step-by-Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-huawei-p60-by-fonelab-android-recover-photos/"><u>How To Restore Missing Photos Files from Huawei P60.</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-xiaomi-redmi-k70e-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Xiaomi Redmi K70E to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-chromebook-friendly-video-editors-a-2023-comparison-for-2024/"><u>New Chromebook-Friendly Video Editors A 2023 Comparison for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/thinkers-playground-top-10-mind-bending-rooms/"><u>Thinkers' Playground Top 10 Mind-Bending Rooms</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-solutions-for-resolving-nothing-to-record-errors-with-windows-10-game-bar/"><u>Top 7 Solutions for Resolving 'Nothing to Record' Errors with Windows 10 Game Bar</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-to-saving-your-favorite-tenplay-videos-for-offline-access-best-tools-compared/"><u>Ultimate Guide to Saving Your Favorite Tenplay Videos for OFFLINE Access – Best Tools Compared!</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-mastering-ram-file-playback-and-conversion-using-top-rated-rmp-software/"><u>Ultimate Guide: Mastering .RAM File Playback & Conversion Using Top-Rated RMP Software</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-selection-of-kodi-matrix-entertainment-packages-for-streaming-refreshed-monthly/"><u>Ultimate Selection of Kodi Matrix Entertainment Packages for Streaming, Refreshed Monthly!</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-ts-file-translator-fast-efficient-video-converting-infrom-mpeg-transport-stream/"><u>Ultimate TS File Translator - Fast, Efficient Video Converting In/From MPEG Transport Stream</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-adding-and-using-the-kingdom-extension-on-kodi-platform/"><u>Ultimate Tutorial: Adding and Using the Kingdom Extension on Kodi Platform</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-flv-format-a-complete-guide-on-opening-and-using-flv-files/"><u>Understanding FLV Format: A Complete Guide on Opening and Using FLV Files</u></a></li>
<li><a href="https://win11.techidaily.com/wavitunes/"><u>WAVファイルがiTunesで利用可能にするためのガイドと、挿入しきれないケースへの解決方法</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    