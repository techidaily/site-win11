---
title: Integrating Elevated Access in Windows 11 Settings
date: 2024-11-03T23:49:19.312Z
updated: 2024-11-07T18:32:28.871Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Elevated Access in Windows 11 Settings
excerpt: This Article Describes Integrating Elevated Access in Windows 11 Settings
keywords: Win11 Elevation Control,Windows Access Integration,High-Level Window Settings,Advanced Windows Options,Elevated Access Configurations,Windows Security Enhancement,Secure User Privileges
thumbnail: https://thmb.techidaily.com/83a5e7f4b304717df57e5c96a8beb60fe39d761265a0a53063f5a3b844f4f838.png
---

## Integrating Elevated Access in Windows 11 Settings

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-detailed-screencasting-techniques-systematic-approach-for-2024/"><u>[New] Detailed Screencasting Techniques Systematic Approach for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-capturing-every-angle-top-choice-pro-360cameras-of-2023/"><u>[Updated] Capturing Every Angle Top Choice Pro 360°Cameras of 2023</u></a></li>
<li><a href="https://win11.techidaily.com/decoy-control-panel-mastering-invisibility-in-win-1011/"><u>Decoy Control Panel - Mastering Invisibility in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-premier-laptops-from-ifa-2023/"><u>Discover Premier Laptops From IFA 2023</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/pasos-para-cambiar-del-viejo-sistema-bios-al-nuevo-uefi-una-guia-completa/"><u>Pasos Para Cambiar Del Viejo Sistema BIOS Al Nuevo UEFI: Una Guía Completa</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/prime-16-video-openers-to-surge-your-traffic-for-2024/"><u>Prime 16 Video Openers to Surge Your Traffic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-windows-to-its-original-energy-configuration/"><u>Resetting Windows to Its Original Energy Configuration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/richest-revenue-generators-in-the-youtube-universe-for-2024/"><u>Richest Revenue Generators in the YouTube Universe for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-address-windows-breakpoint-exception-message/"><u>Steps to Address Window's Breakpoint Exception Message</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-against-dxgi-error-device-detachment/"><u>Strategies Against DXGI Error: Device Detachment</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-initiation-with-ease/"><u>Streamlining Windows 11 Initiation with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/the-slim-way-to-win11-no-bloatware/"><u>The Slim Way to Win11: No Bloatware</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-gt-3-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme GT 3</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/transform-your-computer-display-install-intel-graphics-drivers-now-windows-10/"><u>Transform Your Computer Display: Install Intel Graphics Drivers Now, Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-menus-fresh-ideas-for-freezing-fix/"><u>Unlocking Windows Menus: Fresh Ideas for Freezing Fix</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    