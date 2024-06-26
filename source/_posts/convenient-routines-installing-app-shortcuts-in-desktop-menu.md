---
title: "Convenient Routines: Installing App Shortcuts in Desktop Menu"
date: 2024-06-25T10:32:01.829Z
updated: 2024-06-26T10:32:01.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Convenient Routines: Installing App Shortcuts in Desktop Menu"
excerpt: "This Article Describes Convenient Routines: Installing App Shortcuts in Desktop Menu"
keywords: App Shortcut Desktop,Quick App Access,Shortcut Menu Setup,Easy App Installation,Enhance Desktop Speed,Simplify Routine Tasks,Integrate App Menus
thumbnail: https://thmb.techidaily.com/fa51da89f91ea3306806b0c92d6d119cfa0eae393a63e41c230a883a3e7c64cd.jpg
---

## Convenient Routines: Installing App Shortcuts in Desktop Menu

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

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
4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reverse-color-issue-with-windows-marketplace/"><u>Techniques to Reverse Color Issue with Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/improving-the-effectiveness-of-win-based-discord-queries/"><u>Improving the Effectiveness of Win-Based Discord Queries</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-halted-wow-installation/"><u>Reactivating a Halted WoW Installation</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-regain-control-over-non-operational-media-playback/"><u>Strategies to Regain Control Over Non-Operational Media Playback</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Tecno Pop 8? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/map-to-wealth-terrarias-quintessential-gold-hunt-for-2024/"><u>Map to Wealth  Terraria's Quintessential Gold Hunt for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-reaction-video-makers-top-picks-for-iphone-and-android/"><u>In 2024, Reaction Video Makers Top Picks for iPhone and Android</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-facebooks-ultimate-guide-selective-downloader-addons-and-extensions-for-firefox/"><u>[New] Facebook's Ultimate Guide  Selective Downloader Addons & Extensions for Firefox</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-pick-your-favorite-top-ios-apps-for-facebook-video-loading/"><u>In 2024, Pick Your Favorite  Top iOS Apps for Facebook Video Loading</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-complete-2023-guide-to-effortless-fb-posting-tools/"><u>In 2024, The Complete 2023 Guide to Effortless FB Posting Tools</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/tips-for-choosing-location-and-scheduling-music-video-for-2024/"><u>Tips for Choosing Location and Scheduling Music Video for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Nokia C110 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>