---
title: How to Add a God Mode Option to Windows 11’S Context Menu
date: 2024-10-03T02:38:54.851Z
updated: 2024-10-04T07:12:19.472Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Add a God Mode Option to Windows 11’S Context Menu
excerpt: This Article Describes How to Add a God Mode Option to Windows 11’S Context Menu
keywords: God Mode Windows 11,Windows God Enable,Customize Win 11 Context,Context Menu Modification,Adding God Option Windows,Windows Script Editor,Windows Script Tips
thumbnail: https://thmb.techidaily.com/04440a12467eb00d2e76ab58c49996f10e544f909e1d6b3abfc42368ffd69851.jpg
---

## How to Add a God Mode Option to Windows 11’S Context Menu

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-choosing-androids-favorite-freepaid-video-tile-tools-8-ranked/"><u>[New] Choosing Android's Favorite Free/Paid Video Tile Tools #8 Ranked</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-demystifying-the-symbolism-of-a-blue-marker-in-facebook-chats/"><u>[New] Demystifying the Symbolism of a Blue Marker in Facebook Chats</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-apowersoft-free-software-review-for-techies/"><u>[Updated] In 2024, Apowersoft Free Software Review for Techies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-excellent-record-maker-chromebook-edition/"><u>[Updated] In 2024, Excellent Record Maker Chromebook Edition</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-unlock-retro-classics-on-android-choose-the-best-ps2-emulators-for-2024/"><u>[Updated] Unlock Retro Classics on Android – Choose the Best PS2 Emulators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gui-add-folders-to-windows-11s-taskbar/"><u>Elevate Your GUI - Add Folders to Windows 11'S Taskbar</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-a-black-start-up-screen-in-helldivers-2-top-solutions-for-players/"><u>Fixing a Black Start-Up Screen in Helldivers 2 – Top Solutions for Players</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-realme-gt-5-pro-by-fonelab-android-recover-music/"><u>How To Restore Missing Music Files from Realme GT 5 Pro</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/hulu-or-hulu-plus-exploring-key-differences-for-a-better-streaming-experience/"><u>Hulu or Hulu Plus? Exploring Key Differences for a Better Streaming Experience</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/keep-pace-with-technology-iphones-trade-up-system/"><u>Keep Pace with Technology: IPhone's Trade-Up System</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-type-fixes-for-windows-11s-x80049dd3-error/"><u>Mastering the Art of Type Fixes for Windows 11'S X80049DD3 Error</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-windows-11s-unwanted-apps-quickly/"><u>Navigate Through Windows 11'S Unwanted Apps Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eradicate-error-80080300-in-windows-team-collaboration/"><u>Steps to Eradicate Error 80080300 in Windows Team Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-practices-for-getting-most-from-windows-11s-launchpad/"><u>The Best Practices for Getting Most From Windows 11'S Launchpad</u></a></li>
<li><a href="https://win11.techidaily.com/the-components-configuration-console-in-windows-explored/"><u>The Components Configuration Console in Windows Explored</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-managing-printers-in-windows-1011/"><u>The Essentials of Managing Printers in Windows 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    