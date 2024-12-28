---
title: Implementing Divine Window Controls in Windows 11
date: 2024-12-22T01:08:06.969Z
updated: 2024-12-28T01:39:28.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Divine Window Controls in Windows 11
excerpt: This Article Describes Implementing Divine Window Controls in Windows 11
keywords: Divine Window Tools,Win11 Screen Adjust,Windows 11 UI Tweaks,Godly Display Settings,Windows 11 Controls,Pure Window Customization,Deity GUI in Win11
thumbnail: https://thmb.techidaily.com/b0d6f56b3e6efb0ac5881b741c9c12ef541c2aef549de1d2cc8ab07a2bd3f133.jpg
---

## Implementing Divine Window Controls in Windows 11

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.

5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crafting-gifs-from-youtube-detailed-step-by-step-guide-for-pcmobile/"><u>[New] 2024 Approved Crafting GIFs From YouTube Detailed Step-by-Step Guide for PC/Mobile</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unveiling-the-top-5-facebook-video-downloaders-today/"><u>[New] In 2024, Unveiling the Top 5 Facebook Video Downloaders Today</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-streamline-your-multi-tasking-pip-settings-in-safari/"><u>[Updated] 2024 Approved Streamline Your Multi-Tasking PIP Settings in Safari</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtube-editing-tutorial-mastering-video-cuts-for-2024/"><u>[Updated] YouTube Editing Tutorial Mastering Video Cuts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-to-custom-window-design-with-winbubbles-insights/"><u>A Visual Journey to Custom Window Design with WinBubble's Insights</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-on-iphone-11-pro-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons On iPhone 11 Pro? Find the Best Solution Here</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-disabled-obstacles-for-executing-powershell-scripts/"><u>Eliminating 'Disabled' Obstacles for Executing PowerShell Scripts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/tial-travel-vloggers-the-ultimate-10-list-for-2024/"><u>Essential Travel Vloggers The Ultimate 10 List for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-windows-update-issue-code-x80246007/"><u>How To Quickly Resolve Windows Update Issue Code X80246007</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-nubia-red-magic-8s-proplus-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Nubia Red Magic 8S Pro+ Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-system-recovery-conquering-blue-screen-errors/"><u>Mastering System Recovery: Conquering Blue Screen Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-block-after-failure/"><u>Overcoming Windows Login Block After Failure</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-brightness-overcoming-dark-screen-problems/"><u>Restoring Brightness: Overcoming Dark Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-15-ways-to-reach-windows-settings/"><u>Simplify: 15 Ways to Reach Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-windows-security-today-with-free-desktop-pass-gen-apps/"><u>Step Up Windows Security Today With Free Desktop Pass Gen Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/strategies-to-maximize-mobile-income-from-youtube/"><u>Strategies to Maximize Mobile Income From YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-windows-experience-resetting-apps/"><u>Streamlining Your Windows Experience: Resetting Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tempo-transformation-techniques-for-videos/"><u>Tempo Transformation Techniques for Videos</u></a></li>
</ul></div>

