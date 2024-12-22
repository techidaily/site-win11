---
title: Infuse Windows UI with Supernatural Shortcuts
date: 2024-12-17T17:52:51.244Z
updated: 2024-12-22T16:08:30.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Infuse Windows UI with Supernatural Shortcuts
excerpt: This Article Describes Infuse Windows UI with Supernatural Shortcuts
keywords: Supernatural UI Enhancements,Infused Window Functionality,Shortcut Magic for WinUI,Windows UI Supernatural Tweaks,Enchanted UX Design (WinUI),Fantasy User Interface Tricks,Mystic WinUi Efficiency
thumbnail: https://thmb.techidaily.com/c23fd39a2d5eab7804c8c0b256c287da5a7d97c2d7588b0ef8db354da07eb1bf.jpg
---

## Infuse Windows UI with Supernatural Shortcuts

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-leading-websites-for-free-game-of-thrones-ringtones/"><u>[New] In 2024, Leading Websites for Free Game of Thrones Ringtones</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-streamline-your-game-logs-advanced-camcapturing-techniques/"><u>[Updated] 2024 Approved Streamline Your Game Logs Advanced CamCapturing Techniques</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/apple-iphone-15-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>Apple iPhone 15 Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-0x8004def5-nine-fixes-for-onedrive-issues-win11/"><u>Deciphering 0X8004DEF5 - Nine Fixes for Onedrive Issues, Win11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-best-7-ai-driven-tools-for-tackling-difficult-mathematics-with-ease/"><u>Discover the Best 7 AI-Driven Tools for Tackling Difficult Mathematics with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-photo-retouch-dive-into-background-removal/"><u>Effortless Photo Retouch Dive Into Background Removal</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fps-counters-in-windows-11-landscape/"><u>Essential FPS Counters in Windows 11 Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-perfectly-configure-the-win11s-dns-service/"><u>How to Perfectly Configure the Win11's DNS Service</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-realme-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-navigating-video-production-with-captivate/"><u>In 2024, Navigating Video Production with Captivate</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-charge-indicators-for-modern-wins/"><u>Optimize Full Charge Indicators for Modern WINs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-soundheadphones-plugged-error-on-pc/"><u>Overcoming No Sound/Headphones Plugged Error on PC</u></a></li>
<li><a href="https://fox-direct.techidaily.com/overcoming-technical-hurdles-in-iphone-xs-facial-detection/"><u>Overcoming Technical Hurdles in iPhone X's Facial Detection</u></a></li>
<li><a href="https://buynow-info.techidaily.com/resolution-revealed-understanding-the-impact-on-image-quality-between-1080p-144-cups-and-ultra-hd-monitors/"><u>Resolution Revealed: Understanding the Impact on Image Quality Between 1080P, 144 Cups, and Ultra-HD Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pcs-visual-output-update-radeon-on-windows-11/"><u>Revitalize Your PC's Visual Output: Update Radeon on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/shrinking-startup-latency-adjusting-windows-11-timeout-settings/"><u>Shrinking Startup Latency: Adjusting Windows 11 Timeout Settings</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-hand-hidden-descriptors-for-folders-in-windows/"><u>The Invisible Hand: Hidden Descriptors for Folders in Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unify-your-visuals-how-to-match-colors-across-video-clips-in-final-cut-pro-for-2024/"><u>Updated Unify Your Visuals How to Match Colors Across Video Clips in Final Cut Pro for 2024</u></a></li>
</ul></div>

