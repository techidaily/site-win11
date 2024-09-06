---
title: Stepwise Guide to Immediate Accessibility of Software Shortcuts
date: 2024-09-05T08:26:29.742Z
updated: 2024-09-06T08:26:29.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Guide to Immediate Accessibility of Software Shortcuts
excerpt: This Article Describes Stepwise Guide to Immediate Accessibility of Software Shortcuts
keywords: Quick Shortcut Enabling,Accessible Shortcut Use,Immediate Software Keybinding,Easy Shortcut Setup Guide,Instant Software Commanding,Fast F1+F2 Shortcut Activation,Direct Access Software Keys
thumbnail: https://thmb.techidaily.com/51471ca8a7054ce3eae075b674d92ea208c6509841b94168b4ee14b78abb841b.jpg
---

## Stepwise Guide to Immediate Accessibility of Software Shortcuts

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Key context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-key-option.png)

1. Input **Edge** as the new registry key’s title.
2. Right-click your **Edge** key and select the **New** \> **Key** options again.
3. Enter **command** to be the new subkey’s name.  
![The command registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-command-key.png)
4. Click File Explorer’s taskbar button.
5. Open Edge’s folder, which has this default path: **C:\\Program Files (x86)\\Microsoft\\Edge\\Application**.

1. Right-click msedge.exe there to select the **Copy as** **path** option shown directly below.  
![The Copy as path option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/copy-as-path-option.png)
2. Then return to the Registry Editor, and select the new **command** key you added.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

## How to Add Program Shortcuts to the Context Menu With Easy Context Menu

 If you prefer not to manually edit the registry, add program shortcuts to the desktop’s context menu with Easy Context Menu. Easy Context Menu is a freeware third-party app for customizing context menus in Windows 11/10\. It enables you to add and remove shortcuts to and from the context menu. This is how you can add shortcuts for opening programs to Windows 11’s context menu with that software:

1. Open this [Easy Context Menu page](https://www.sordum.org/7615/easy-context-menu-v1-6/) in a web browser and download the app.
2. Extract the **ec\_menu** ZIP archive with a method in this article about [unzipping ZIP files in Windows 11](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).
3. Open the extracted **ec\_menu** folder and double-click the **EcMenu\_x64** file to open Easy Context Menu.
4. Click the **List Editor** button.  
![The List Editor button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/list-editor-button.jpg)
5. Press the **Add new** button.

1. Select the application (EXE) file for a program to add to the context menu and click **Open**.
2. Next, select **Desktop Context Menu** on the **Target Context Menu** drop-down menu for the shortcut.  
![The Target Context Menu drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/target-context-menu-drop-down-menu.jpg)
3. Click the **Show at bottom of the menu** radio button.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128842/7443" target="_top" id="2128842">
  <img src="//a.impactradius-go.com/display-ad/7443-2128842" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128842/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-end-screen-magic-free-templates-to-boost-video-appeal/"><u>[Updated] In 2024, End-Screen Magic  Free Templates to Boost Video Appeal</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-instantly-connect-youtube-and-facebook-for-viewers-for-2024/"><u>[Updated] Instantly Connect YouTube and Facebook for Viewers for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-conquer-the-camera-prostrate-techniques-with-gopro-hero5-black/"><u>2024 Approved  Conquer the Camera  Prostrate Techniques With GoPro Hero5 Black</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-exclusive-reveal-top-downloading-tools-for-fans-of-apples-ios-and-facebook/"><u>2024 Approved  Exclusive Reveal  Top Downloading Tools for Fans of Apple's iOS and Facebook</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-soft-onset-showcasing/"><u>2024 Approved  Soft Onset Showcasing</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-phantom-hardware-listings-on-windows-system/"><u>Correcting Phantom Hardware Listings on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-folder-dimensions-with-powershell-scripts/"><u>Deciphering Folder Dimensions with PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-workings-of-windows-sound-graph-separation/"><u>Delving Into the Workings of Windows' Sound Graph Separation</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-windows-outclasses-linux-in-gaming/"><u>Discover How Windows Outclasses Linux in Gaming</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-oppo-find-x6-pro-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Oppo Find X6 Pro.</u></a></li>
<li><a href="https://buynow-help.techidaily.com/evaluating-the-top-of-the-line-asus-ax6000-wireless-router-wi-fi-6-excellence-meets-smart-technology/"><u>Evaluating the Top-of-the-Line Asus AX6000 Wireless Router: Wi-Fi 6 Excellence Meets Smart Technology</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-windows-help-top-5-routes-uncovered/"><u>Fast Track to Windows Help - Top 5 Routes Uncovered</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-discord-javascript-crisis-a-step-by-step-approach/"><u>Fixing Windows 11'S Discord JavaScript Crisis: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-edge-off-windows-11-shapes/"><u>How to Edge Off: Windows 11 Shapes</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-perfecting-chromes-sound-best-apps-for-online-text-to-speech-transformation/"><u>In 2024, Perfecting Chrome's Sound  Best Apps for Online Text-to-Speech Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/innovate-taskbar-functionality-with-additional-folders-in-11/"><u>Innovate Taskbar Functionality with Additional Folders in 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/mastering-ipad-screen-capture-techniques/"><u>Mastering iPad Screen Capture Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-change-of-guard-swapping-your-windows-11-logon-method/"><u>Navigating the Change of Guard: Swapping Your Windows 11 Logon Method</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-optimizing-video-output-a-comprehensive-guide-to-compressor-in-fcpx/"><u>New In 2024, Optimizing Video Output A Comprehensive Guide to Compressor in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-compatibility-woes-fix-your-programs-in-windows/"><u>No More Compatibility Woes: Fix Your Programs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-limitations-maximizing-ram-in-windows/"><u>Overcoming Limitations: Maximizing RAM In Windows</u></a></li>
<li><a href="https://win11.techidaily.com/propel-your-productivity-top-5-must-have-windows-11-apps/"><u>Propel Your Productivity: Top 5 Must-Have Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-fixes-to-reinstall-overlooked-windows-apps/"><u>Quick and Easy Fixes to Reinstall Overlooked Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-missing-windows-quick-fixes-for-windows-1011/"><u>Reviving Missing Windows: Quick Fixes for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-purge-image-borders/"><u>Simplified Techniques to Purge Image Borders</u></a></li>
<li><a href="https://win11.techidaily.com/starting-storytelling-voice-commands-in-windows-11/"><u>Starting Storytelling: Voice Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-mitigating-the-failed-lunar-client-launch-errors/"><u>Strategies for Mitigating the Failed Lunar Client Launch Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-fix-disk-read-error-in-windows/"><u>Strategies to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-xps-xffffffff-printer-failure/"><u>Swift Solutions for XP's XFFFFFFFF Printer Failure</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-unlocking-blank-login-portals-on-win1011/"><u>Tactics for Unlocking Blank Login Portals on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-size-spectrum-of-your-windows-apps/"><u>Unveiling the Size Spectrum of Your Windows Apps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>