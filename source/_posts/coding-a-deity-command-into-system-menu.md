---
title: Coding a Deity Command Into System Menu
date: 2024-06-25T11:33:45.754Z
updated: 2024-06-26T11:33:45.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Coding a Deity Command Into System Menu
excerpt: This Article Describes Coding a Deity Command Into System Menu
keywords: Coding DevCommand,Integrate DeityMenu,SystemDeityIntegration,UIDeitySystemUpdate,CodeMenubox,SystemDeityCoding,AddDeityToUI
thumbnail: https://thmb.techidaily.com/c11b89b923631ed5d512ccc32ee592a5fb46939b31266627ae16098d24a9cb49.jpg
---

## Coding a Deity Command Into System Menu

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

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

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reverse-onedrive-lockout-windows-user-guide-needed/"><u>Reverse OneDrive Lockout: Windows User Guide Needed</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-login-new-pin-creation/"><u>Streamline Your Windows Login: New PIN Creation</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-savvy-in-the-world-of-windows-11/"><u>Sticky Note Savvy in the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/openai-whisper-for-windows-voice-to-text-techniques-unveiled/"><u>OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/rebuilding-with-purpose-windows-11-from-scratch/"><u>Rebuilding with Purpose: Windows 11 From Scratch</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-non-automatic-timezone-change/"><u>Overcoming Windows' Non-Automatic Timezone Change</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
<li><a href="https://win11.techidaily.com/procedures-for-resolving-unresponsive-installation-on-windows-os/"><u>Procedures for Resolving Unresponsive Installation on Windows OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-windows-and-mac-recording-tactics-finding-your-perfect-match-freepaid/"><u>[Updated] In 2024, Windows & Mac Recording Tactics - Finding Your Perfect Match (Free/Paid)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/where-can-i-find-free-songs-for-video-editing-for-2024/"><u>Where Can I Find Free Songs for Video Editing for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-streamline-your-screens-the-benefits-of-using-showmore/"><u>In 2024, Streamline Your Screens  The Benefits of Using ShowMore</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-moto-z2-play-smartphone-review-for-2024/"><u>[New] MOTO Z2 Play Smartphone Review for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fixing-feed-frustration-reclaim-missing-video-suggestions/"><u>[New] Fixing Feed Frustration  Reclaim Missing Video Suggestions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-calculate-aspect-ratios-like-a-pro-best-online-tools/"><u>Updated Calculate Aspect Ratios Like a Pro Best Online Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-strategies-to-combat-freezing-in-high-quality-mode/"><u>[Updated] Strategies to Combat Freezing in High Quality Mode</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2-methods-to-crop-video-in-vlc-for-2024/"><u>2 Methods to Crop Video in VLC for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tranquil-acoustic-settings-on-computers/"><u>[Updated] Tranquil Acoustic Settings on Computers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>