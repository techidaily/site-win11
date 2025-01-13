---
title: "Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11"
date: 2025-01-06T01:06:00.393Z
updated: 2025-01-12T18:51:32.649Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11"
excerpt: "This Article Describes Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11"
keywords: Win11 Update Toolbar,Win11 Maintenance Tool,Win11 Performance Check,Win11 System Updates,Quick Win11 Checkup,Efficient Win11 Updater,Timely Windows 11 Updates
thumbnail: https://thmb.techidaily.com/25dfc703be5473423edfc66113d30469d26da4408f6261979d298982619597ae.jpg
---

## Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-total-insight-navigating-through-googles-podcast-app/"><u>[New] In 2024, Total Insight Navigating Through Google's Podcast App</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-full-assessment-of-slomo-application-trends/"><u>[Updated] 2024 Approved Full Assessment of SloMo Application - Trends</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-elevate-your-online-interactions-master-microsoft-teams-snap/"><u>2024 Approved Elevate Your Online Interactions Master Microsoft Teams Snap</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-the-complexities-of-spotifys-ad-ecosystem/"><u>2024 Approved Navigating the Complexities of Spotify's Ad Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-way-through-printer-error-messages/"><u>Easing the Way Through Printer Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-for-unwanted-new-tabs-in-chrome-browser/"><u>Easy Fixes for Unwanted New Tabs in Chrome Browser</u></a></li>
<li><a href="https://fox-making.techidaily.com/efficient-methods-to-clear-storage-on-iphone-or-ipad-prior-to-upgrading-to-ios-8/"><u>Efficient Methods to Clear Storage on iPhone or iPad Prior to Upgrading to iOS 8</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/evaluating-the-owc-mercury-pro-a-high-performance-storage-solution-reviewed/"><u>Evaluating the OWC Mercury Pro: A High-Performance Storage Solution Reviewed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/gratis-online-movavi-converter-au-naar-mp4-uploaden-effortlessly-editieren/"><u>Gratis Online Movavi-Converter: AU Naar MP4 Uploaden - Effortlessly Editieren</u></a></li>
<li><a href="https://win11.techidaily.com/missing-out-regain-access-to-windows-11s-hidden-upgrades-and-tools/"><u>Missing Out? Regain Access to Windows 11'S Hidden Upgrades and Tools</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functional-capacity-of-ctrl-key-in-windows-11/"><u>Restoring Full Functional Capacity of CTRL Key in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reclaim-faulty-wi-fi-settings-on-a-windows-machine/"><u>Steps to Reclaim Faulty Wi-Fi Settings on a Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-turbulent-troubles-stop-lag-on-star-wars-battlefront-2-pc/"><u>Tackle Turbulent Troubles: Stop Lag on Star Wars Battlefront 2 PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-permission-based-save-errors-in-windows-os/"><u>Tackling Permission-Based Save Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-detecting-hidden-bluetooth-clients-devices-mgr/"><u>Tips for Detecting Hidden Bluetooth Clients Devices Mgr</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/top-10-visual-gratification-tools-for-instagram-grids/"><u>Top 10 Visual Gratification Tools for Instagram Grids</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-16-unbeatable-christmas-season-offers-on-hewlett-packard-products-zdnet/"><u>Top 16 Unbeatable Christmas Season Offers on Hewlett Packard Products - ZDNet</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-guide-to-the-maxoak-185wh50kmah-power-reserve-your-comprehensive-review/"><u>Ultimate Guide to the MaxOak 185Wh/50KmAh Power Reserve: Your Comprehensive Review</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-file-explorer-keeps-opening-by-itself-on-windows/"><u>What to Do if File Explorer Keeps Opening by Itself on Windows</u></a></li>
</ul></div>

