---
title: Implementing Windows 10/11 Update Reminder Feature
date: 2024-10-16T03:20:30.182Z
updated: 2024-10-21T11:37:42.540Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Windows 10/11 Update Reminder Feature
excerpt: This Article Describes Implementing Windows 10/11 Update Reminder Feature
keywords: Win10UpdateReminder,Win11UpdaterNotify,PCWindows10UpdateAlert,Windows10UpdateSchedule,UpgradeWindowsFeature,RemindWinUpdateInstall,LatestWindowsUpdateCheck
thumbnail: https://thmb.techidaily.com/8d1de21c666386207e0a2c0896dc0647ebc82a413cfdd6aa282a235213b145ee.jpg
---

## Implementing Windows 10/11 Update Reminder Feature

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105882/7443" target="_top" id="2105882">
  <img src="//a.impactradius-go.com/display-ad/7443-2105882" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-innovative-fbx-gametime-tracking-solutions/"><u>[Updated] 2024 Approved Innovative FBX Gametime Tracking Solutions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-windows-artistry-nine-top-tools-for-animated-gif-preservation/"><u>[Updated] 2024 Approved Mastering Windows Artistry Nine Top Tools for Animated GIF Preservation</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-canvas-to-crypto-top-7-artwork-conversion-platforms/"><u>[Updated] From Canvas to Crypto Top 7 Artwork Conversion Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-performance-with-vm-cache-clear/"><u>Boost PC Performance with VM Cache Clear</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-file-management-altering-timestamps-in-windows/"><u>Cutting-Edge File Management: Altering Timestamps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-x-official-method-to-unlock-your-iphone-x-by-drfone-ios/"><u>How To Unlock iPhone X Official Method to Unlock Your iPhone X</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-unlock-content-creation-uploading-videos/"><u>In 2024, Unlock Content Creation Uploading Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/konvertera-gratis-m4v-video-till-mp4-format-online-en-simplen-vardagslos-av-konverteringstools/"><u>Konvertera Gratis M4V-Video Till MP4 Format Online - en Simplen Vardagslös Av Konverteringstools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-and-fixing-windows-update-issues/"><u>Mastering the Art of Finding and Fixing Windows Update Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/modifying-text-in-instagram-direct-a-comprehensive-tutorial/"><u>Modifying Text in Instagram Direct: A Comprehensive Tutorial</u></a></li>
<li><a href="https://tech-revival.techidaily.com/multimidia-de-software-segura-com-foco-em-recuperacao-de-imagens-a-solucao-de-movavi/"><u>Multimídia De Software Segura Com Foco Em Recuperação De Imagens – A Solução De Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-unlock-windows-defense-against-admins-choice/"><u>Techniques to Unlock Windows Defense Against Admins' Choice</u></a></li>
<li><a href="https://some-approaches.techidaily.com/uploading-avchd-content-on-youtube-a-step-by-step-guide-to-format-conversion/"><u>Uploading AVCHD Content on YouTube: A Step-by-Step Guide to Format Conversion</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    