---
title: Steering Through Hidden Menu in Windows 11
date: 2024-12-06T05:29:59.186Z
updated: 2024-12-07T07:37:00.708Z
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

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-mastering-xbox-livestreaming-on-facebook-platform/"><u>[New] 2024 Approved Mastering Xbox Livestreaming on Facebook Platform</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-compelling-spotify-campaigns-a-compreran-guide/"><u>[Updated] Crafting Compelling Spotify Campaigns A Compreran Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-how-to-record-internal-audio-on-android-video-or-gameplay/"><u>[Updated] In 2024, How to Record Internal Audio on Android [Video or Gameplay]</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-strategic-guide-gain-traction-with-podcast-seo-techniques/"><u>[Updated] Strategic Guide Gain Traction with Podcast SEO Techniques</u></a></li>
<li><a href="https://driver-download.techidaily.com/brother-hl-l2370dw-printer-driver-latest-version-download/"><u>Brother HL-L2370DW Printer Driver - Latest Version Download</u></a></li>
<li><a href="https://win11.techidaily.com/enlarge-windows-memory-protect-user-data/"><u>Enlarge Windows Memory, Protect User Data</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-nokia-c32-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Nokia C32 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-persistent-0x800f0831-error-in-windows-11-and-11/"><u>How to Fix a Persistent 0X800f0831 Error in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-persistent-crashing-in-insurgency-sandstorm-a-complete-guide/"><u>How to Fix Persistent Crashing in Insurgency: Sandstorm - A Complete Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-method-skipping-windows-11-logon/"><u>Master Method: Skipping Windows 11 Logon</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-linux-with-windows-software/"><u>Maximizing Linux with Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-headset-mic-problems/"><u>Navigating Through Windows Headset Mic Problems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-repairing-windows-11-help-tool/"><u>Quick Guide: Repairing Windows 11 Help Tool</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unleash-your-inner-athlete-how-the-airpods-pro-3-track-your-workouts-and-monitor-heart-rate-techsavvy/"><u>Unleash Your Inner Athlete: How the AirPods Pro 3 Track Your Workouts and Monitor Heart Rate | TechSavvy</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-phones-in-the-windows-audio-domain/"><u>Unleashing Potential: Phones in the Windows Audio Domain</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    