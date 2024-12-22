---
title: Expose Hidden Components in Windows 11 Display
date: 2024-12-17T16:17:49.827Z
updated: 2024-12-22T16:50:21.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expose Hidden Components in Windows 11 Display
excerpt: This Article Describes Expose Hidden Components in Windows 11 Display
keywords: Windows 11 Display Features,Uncovering Windows UI Elements,Windows 11 UI Insight,Dissect Windows Display,Hidden Windows Components Exposed,Deep Windows Display Analysis,Understanding Windows 11 Layout
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## Expose Hidden Components in Windows 11 Display

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elite-8-digital-stars-on-the-rise/"><u>[New] In 2024, Elite 8 Digital Stars on the Rise</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-full-time-careers-meet-video-content-a-harmonious-mix/"><u>[Updated] Full-Time Careers Meet Video Content A Harmonious Mix</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-future-of-cosmetics-youtube-gurus-on-the-rise/"><u>[Updated] In 2024, Future of Cosmetics YouTube Gurus on the Rise</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-savor-playtime-the-essential-guide-to-high-quality-offline-ios-games-for-2024/"><u>[Updated] Savor Playtime – The Essential Guide to High-Quality Offline iOS Games for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-solidify-zoom-sounds-avoid-amplified-annoyances/"><u>[Updated] Solidify Zoom Sounds Avoid Amplified Annoyances</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-ultimate-mac-system-all-in-one-screen-and-sound-capture-tool-for-2024/"><u>[Updated] Ultimate Mac System All-in-One Screen & Sound Capture Tool for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decipher-windows-11-pc-eligibility-quickly/"><u>Decipher Windows 11 PC Eligibility Quickly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ensuring-a-safe-chat-environment-implementing-family-friendly-restrictions-on-discord/"><u>Ensuring a Safe Chat Environment: Implementing Family-Friendly Restrictions on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-non-responsive-ctrl-issues-on-modern-pcs/"><u>Navigating Through Non-Responsive CTRL Issues on Modern PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-overcome-failed-boot-virtual-machines-in-wm11plus/"><u>Quick Cure: Overcome Failed Boot Virtual Machines in WM11+</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-shortcut-functionality-to-snip-tool/"><u>Restoring Shortcut Functionality to Snip Tool</u></a></li>
<li><a href="https://win11.techidaily.com/shield-your-pc-blocking-wi-fi-broadcast-in-windows/"><u>Shield Your PC: Blocking Wi-Fi Broadcast in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/uniting-platforms-instagrams-synergy-with-facebook/"><u>Uniting Platforms: Instagram's Synergy with Facebook</u></a></li>
</ul></div>

