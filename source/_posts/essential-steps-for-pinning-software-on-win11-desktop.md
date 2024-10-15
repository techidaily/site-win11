---
title: Essential Steps for Pinning Software on Win11 Desktop
date: 2024-10-09T16:51:16.640Z
updated: 2024-10-15T19:07:09.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Pinning Software on Win11 Desktop
excerpt: This Article Describes Essential Steps for Pinning Software on Win11 Desktop
keywords: Win11 PinSoftware Guide,PinSoftware Installation,Win11 Software Pinning,Essential PinTool Steps,Secure PinWin11 Software,Win11 PinSetup Process,IntegrateSoftware on Win11
thumbnail: https://thmb.techidaily.com/9420d8c67dc649498f45244e433ec706e66933c2bf2f2b4b3c5585601cba7b98.jpg
---

## Essential Steps for Pinning Software on Win11 Desktop

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  
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
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-craft-images-with-orbital-soft-edge-psx-tech/"><u>[New] Craft Images with Orbital Soft Edge PSX Tech</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-dynamic-gifs-from-video-an-illustrative-tutorial-for-2024/"><u>[New] Crafting Dynamic Gifs From Video An Illustrative Tutorial for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sticker-free-showcase-crafting-cleansed-tiktok-videos/"><u>[New] Sticker-Free Showcase Crafting Cleansed TikTok Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-facebooks-blue-icon-decoding-its-meaning-in-chats/"><u>[Updated] In 2024, Facebook's Blue Icon Decoding Its Meaning in Chats</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-nubia-red-magic-9-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Nubia Red Magic 9 Pro FRP</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/ttamp3movavi/"><u>線上即時TTA到MP3轉換：使用Movavi進行快速、無限制的音效改編</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722893082787-all-you-need-to-know-about-the-anticipated-tesla-cellphone-expected-price-release-date-and-specs-coverage/"><u>All You Need to Know About the Anticipated Tesla Cellphone - Expected Price, Release Date, and Specs Coverage</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-writable-functionality-of-steam-folder-directories/"><u>Enhancing Writable Functionality of Steam Folder Directories</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-system-integrity-and-security-turn-on-controlled-access/"><u>Ensuring System Integrity & Security: Turn on Controlled Access</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-fatal-javascript-problem-in-discord-on-windows-11/"><u>How to Rectify Fatal Javascript Problem in Discord on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-analyzing-the-impact-of-reduced-photo-jiggles-in-adobe/"><u>In 2024, Analyzing the Impact of Reduced Photo Jiggles in Adobe</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-blue-screen-fixation-error-code-0x8007007e/"><u>Mastering Windows Blue Screen Fixation - Error Code 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-11-from-snooping-on-activities/"><u>Prevent Windows 11 From Snooping on Activities</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-overcome-upgrade-error-in-windows-1011/"><u>Quick Guide to Overcome Upgrade Error in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-pathway-to-stunning-window-display-quality/"><u>The Ultimate Pathway to Stunning Window Display Quality</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-linux-commands-on-windows-via-sudo/"><u>Unlocking Linux Commands on Windows via Sudo</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-voice-translation-english-to-bangla-online-and-offline-apps/"><u>Updated 2024 Approved Voice Translation English to Bangla Online and Offline Apps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    