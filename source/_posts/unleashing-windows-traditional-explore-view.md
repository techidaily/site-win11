---
title: Unleashing Windows' Traditional Explore View
date: 2024-06-25T11:31:26.881Z
updated: 2024-06-26T11:31:26.881Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unleashing Windows' Traditional Explore View
excerpt: This Article Describes Unleashing Windows' Traditional Explore View
keywords: Windows Explorer View,Window GUI Navigation,UI Exploration in Win,Standard Windows Navigation,Enhanced OS Interface,Classic Windows Pathfinding,Traditional Win Interface
thumbnail: https://thmb.techidaily.com/287414ff43ab53f27880b8114eed3693184381a70cdfc416ba85990af80f04e8.jpg
---

## Unleashing Windows' Traditional Explore View

 Microsoft redesigned File Explorer’s user interface for Windows 11\. Windows 11’s File Explorer has a command bar on which you can select options. That bar replaces the tabbed ribbon interface from Windows 10’s File Explorer.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

## 1\. Press the Up Button in the Control Panel

 File Explorer is accessible from the Control Panel. Furthermore, Explorer will still have the old, ribbon interface from Windows 10 when you open it from there. You can access the classic File Explorer in Windows 11 by clicking the up button in the Control Panel as follows:

1. Press the **Windows + S** key combination to access Windows 11’s search box.
2. Input **Control Panel** and select to open the matching search result.
3. If the Control Panel opens in an icon view, click the **View by** drop-down menu and select **Category**.  
![The View by menu in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/view-by-menu.jpg)
4. Then click the **Up to “Desktop”** button (up arrow) button on the Control Panel’s navigation bar. Alternatively, press the **Alt + Up arrow key** keyboard shortcut.  
![The Up to Desktop button in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/up-button.jpg)

 Now you’ll see the classic File Explorer from Windows 10 that incorporates a tab bar. You’ll always need to open the Control Panel first to access classic File Explorer through it. So, consider [setting up a Control Panel shortcut](https://www.makeuseof.com/windows-11-set-up-control-panel-shortcuts/) in Windows 11 to give you more direct access.

## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
3. You can bring back the command bar by executing this command:  
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

## 4\. Restore Explorer’s Classic Ribbon UI With ExplorerPatcher

 You can still restore Explorer’s ribbon interface in Windows 11 22H2 and all other build versions with ExplorerPatcher. ExplorerPatcher is freeware software that enables you to customize Windows 11’s Start menu, taskbar, File Explorer, and system tray. It includes many options for [making Windows 11 look more like Windows 10](https://www.makeuseof.com/windows-11-look-like-windows-10-explorerpatcher/).

 This is how you can restore tabs in Windows 11’s File Explorer with ExplorerPatcher.

1. Open this [ExplorerPatcher Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Explorer-Patcher-for-Windows-11.shtml) and download the file.
2. Double-click the **ep\_setup** file to install Explorer Patcher.
3. Activate the Power User menu by right-clicking the **Start** taskbar button to select **Search**.
4. Enter **ExplorerPatcher** in the Windows 11 search box and click **Properties (ExplorerPatcher)**.
5. Click the **File Explorer** tab in ExplorerPatcher.
6. Next, click the **Control interface** option to select **Windows 10 Ribbon**.  
![The Windows 10 Ribbon option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-10-ribbon.jpg)
7. Click **Restart File Explorer** on the Properties window.

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)

 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/averting-interruptions-with-solid-connections-in-windows/"><u>Averting Interruptions with Solid Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clumped-up-windows-11-icon-grouping/"><u>Adjusting Clumped-Up Windows 11 Icon Grouping</u></a></li>
<li><a href="https://win11.techidaily.com/windows-installation-manual-for-chatgpt/"><u>Windows Installation Manual for ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-persistent-ps4-controller-connections-in-windows/"><u>Strategies for Persistent PS4 Controller Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-compatible-fingerprint-in-windows/"><u>Troubleshooting No Compatible Fingerprint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-admin-blocked-application-issue/"><u>Troubleshooting Admin-Blocked Application Issue</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-screen-captures-adding-sound-in-the-snipping-tool-max-156/"><u>Elevate Your Screen Captures: Adding Sound in the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-windows-ethernet-connection-access/"><u>Regaining Windows Ethernet Connection Access</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-device-communication-efficiency-by-optimizing-windows-systems/"><u>Enhancing Device Communication Efficiency by Optimizing Windows Systems</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-unlocking-compressors-power-tips-and-tricks-for-final-cut-pro-x-editors-for-2024/"><u>New Unlocking Compressors Power Tips and Tricks for Final Cut Pro X Editors for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-exploring-visual-storytelling-creating-time-lapse-videos-on-ipad-for-2024/"><u>[Updated] Exploring Visual Storytelling  Creating Time-Lapse Videos on iPad for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-unlocking-talkshoplive-pros-and-tips-for-live-shopping-success/"><u>Updated 2024 Approved Unlocking TalkShopLive Pros and Tips for Live Shopping Success</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-samsung-galaxy-a14-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Samsung Galaxy A14 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-footage-to-dvd-mastering-home-video-production/"><u>From Footage to DVD Mastering Home Video Production</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-ideal-tags-elevating-your-contents-discovery-potential/"><u>In 2024, Ideal Tags  Elevating Your Content's Discovery Potential</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-crafting-visual-narratives-adding-memorable-story-emoji-images/"><u>[Updated] Crafting Visual Narratives  Adding Memorable Story Emoji Images</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-create-effective-youtube-advertisements-on-a-budget/"><u>2024 Approved  Create Effective YouTube Advertisements on a Budget</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-scaling-up-on-igtv-through-powerful-hash-tagging/"><u>2024 Approved  Scaling Up on IGTV Through Powerful Hash Tagging</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-creating-engaging-content-for-effective-discord-live-streams/"><u>[New] In 2024, Creating Engaging Content for Effective Discord Live Streams</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>