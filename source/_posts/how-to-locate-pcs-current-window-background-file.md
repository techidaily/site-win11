---
title: How to Locate PC's Current Window Background File
date: 2024-07-13T11:01:12.757Z
updated: 2024-07-14T11:01:12.757Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Locate PC's Current Window Background File
excerpt: This Article Describes How to Locate PC's Current Window Background File
keywords: Find Windows Backdrop File,PC Desktop Image Path,Get PC Screen Theme,Locate PC Wallpaper,Identify Windows Backdrop,Uncover Window Background,Pinpoint PC Screenfile
thumbnail: https://thmb.techidaily.com/cb9e2ddf28e5428496f53b353379d173f81be07c333aa30876bace061b3bea41.jpg
---

## How to Locate PC's Current Window Background File

 Some users may like to customize Windows 11 desktop wallpapers with editing software. However, the Personalization section of the Settings app doesn’t show you the folder paths for wallpapers in themes downloaded from Microsoft’s site. Nor can you find the directory locations for Windows 11’s default backgrounds from there.

 You can’t edit a desktop wallpaper when you don’t know what folder it’s in. So, here we’re going to look at some different ways you can find your current desktop wallpaper. This is how you can find the wallpaper file for your current desktop background in Windows 11\.

## How to Find Your Desktop Wallpaper’s Location With Run Commands

 Run is a command dialog app with which you can access folders and files in Explorer. You can find the file for the wallpaper currently on your Windows desktop with a couple of alternative commands. One command will bring up the folder that includes the background, and the other will enable you to open the image in editing software. This is how you can find your desktop wallpaper with both Run commands:

1. Click the Windows **Start** button icon on the taskbar with the right button on your mouse and select **Run**.
2. To open your current wallpaper’s folder, input this command and click **OK**:  
`%AppData%\Microsoft\Windows\Themes\CachedFiles`
3. A CachedFiles folder including your current wallpaper’s file will open. Double-click the wallpaper there to open it in the default image viewer (probably Photos).  
![The Cachedfiles folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cachedfiles-folder.jpg)
4. Alternatively, input this Run command and press **Return** to open your current wallpaper file:  
`%AppData%\Microsoft\Windows\Themes\TranscodedWallpaper`
5. Then choose an image editor with which to open the wallpaper file inside the software selection menu and select **OK**. If you can’t see the software you want to utilize, click **Look for another app on this PC**, select an editor, and click **Open**.  
![The open with software selection menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/software-selection-menu.jpg)

## How to Find the Folder That Includes All Your Current Theme’s Desktop Wallpaper

 The Run commands above will only find the wallpaper currently on your desktop. However, Windows slideshow themes have multiple wallpapers. If you have a wallpaper slideshow theme set, you can find all its background image files by opening the folder that includes them as follows:

1. Bring up the file and folder manager with Explorer’s **Win + E** keyboard shortcut.
2. Delete the current location in the folder address bar and enter this replacement path:  
`C:\Users\<user folder>\AppData\Local\Microsoft\Windows\Themes`
3. Click your theme’s folder to open it.  
![A DeskBackground folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/a-desktopbackground-folder.jpg)
4. Then open the DesktopBackground subfolder that includes all the theme’s image files.  
![The image files for a Windows theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/a-theme-s-wallpaper-folder.jpg)

 Now you can open all your Windows theme’s background images from that folder. Note that you’ll need to change **<user folder>** in the specified path above to your real user folder’s name. The Themes folder that the path opens includes directories for all Windows themes you’ve downloaded.

## How to Find Your Desktop Wallpaper’s Location With PowerShell

 PowerShell is a useful command-line shell app for many things. You can find your wallpaper within PowerShell by executing a joint command that shows its full folder path. This is how you can find your wallpaper with that command:

1. Open Windows Search with **Win + S**.
2. Enter the **PowerShell** search phrase.
3. [Start PowerShell with elevated permissions](https://www.makeuseof.com/windows-11-powershell-administrator/) by clicking **Run as administrator** for that app’s search result.
4. Next, copy this joint PowerShell command by selecting the text for it and pressing **Ctrl** \+ **C**:  
`$TIC=(Get-ItemProperty 'HKCU:\Control Panel\Desktop' TranscodedImageCache -ErrorAction Stop).TranscodedImageCache  

[System.Text.Encoding]::Unicode.GetString($TIC) -replace '(.+)([A-Z]:[0-9a-zA-Z\\])+','$2'`
5. Paste that command into PowerShell by pressing **Ctrl** \+ **V**.  
![the-show-wallpaper-path-command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-show-wallpaper-path-command.jpg)
6. Then press your **Enter** key to execute the command.

 Now you’ll see a folder path for your desktop wallpaper in PowerShell just below the executed command. Copy that location and open File Explorer. Then paste the path into Explorer’s address bar and press **Enter** to open the file in your default image viewer software.

 Or you can open the file’s folder instead. Delete the file’s name at the end of the path within Explorer. Pressing **Enter** will then bring up the folder from which you can open the file. Right-click the wallpaper file to select **Open with** and choose a suitable app.

## How to Find Your Desktop Wallpaper’s Location With the Registry Editor

 A wallpaper string within the registry includes the full path of your current desktop background. So, you can find your wallpaper’s location by looking at the **Value data** box for that string. These are the steps for finding your desktop wallpaper’s path with the Registry Editor app:

1. First, find Registry Editor by opening the Windows search box and typing in **regedit**.
2. [Open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by selecting the app found.
3. Input this **Desktop** registry key path within the address bar:  
`Computer\HKEY_CURRENT_USER\Control Panel\Desktop`
4. Double-click the **WallPaper** string within the **Desktop** key.
5. Copy the wallpaper’s path within the **Value data** box.  
![The WallPaper string's Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-wallpaper-edit-string-window.jpg)
6. Click **OK** to exit the string’s window and close Registry Editor.
7. [Open Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and input the copied folder path to bring up the wallpaper’s file.

 The registry also includes some strings that store the path locations of previously set desktop wallpapers. So, you can find the locations of previously set backgrounds with those strings. To do so, go to the wallpaper registry key:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers`

![The BackgroundHistoryPath strings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-backgroundhistorypath-strings.jpg)

 That registry key includes five numbered BackgroundHistoryPath strings. Double-click the **BackgroundHistoryPath0**, 1, 2, 3, or 4 string to view its **Value data** box. Then copy and paste the wallpapers’ paths into the File Explorer address bar.

## How to Add a Desktop Wallpaper Location Option to the Context Menu

 A context menu option for opening the folder that includes your current desktop wallpaper will give you more direct access to backgrounds. Of course, Windows 11’s right-click menu doesn’t have such a shortcut, but you can add a handy D**esktop Wallpaper Location** context menu option with the freeware Winaero Tweaker. This is how to add a **Desktop Wallpaper Location** shortcut to the context menu with that software:

1. Open this download page for [Winaero Tweaker](https://winaero.com/winaero-tweaker/#download).
2. Click **Download Winaero Tweaker** to obtain the ZIP archive for that software.
3. Check out our [how to customize Windows 11 with Winaero Tweaker](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) guide for instructions about how to extract, install, and launch that software.
4. Double-click the **Context Menu** settings category inside Winaero Tweaker’s window.  
![The Context Menu category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/context-menu-category.jpg)
5. Select the **Wallpaper Location** setting.
6. Click the **Add “Desktop Wallpaper Location” context menu** checkbox.  
![The Add "Desktop Wallpaper Location" context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-add-desktop-wallpaper-location-folder.jpg)
7. Close the Winaero Tweaker software.

 Try out the new **Desktop Wallpaper Location** option on the right-click menu. Click an area of your Windows 11 desktop with the right mouse button and select **Show more options**. Select the **Desktop Wallpaper Location** option on the classic menu. That shortcut with bring up the DesktopBackground directory for your theme or one of the subfolders within the Wallpaper folder.

![The Desktop Wallpaper Location context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/desktop-wallpaper-location-context-menu-option.jpg)

## Edit Your Current Windows 11 Desktop Wallpaper

 When you’ve found your current Windows 11 desktop wallpaper with any of the methods above, you can edit it to your heart’s content. You can enhance your wallpaper with the filter, cropping, and adjustment tools in the Photos app included with Windows. Or spruce up your desktop’s background with the best freeware image editors, such as GIMP, Paint.NET, PhotoScapeX, and Pixlr E.

 You can’t edit a desktop wallpaper when you don’t know what folder it’s in. So, here we’re going to look at some different ways you can find your current desktop wallpaper. This is how you can find the wallpaper file for your current desktop background in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-top-10-streaming-software-in-the-gaming-world/"><u>[New] Top 10 Streaming Software in the Gaming World</u></a></li>
<li><a href="https://win11.techidaily.com/1719367447353-multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-modifying-windows-system-booting-behavior/"><u>A Practical Guide to Modifying Windows System Booting Behavior</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-vivo-y100-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Vivo Y100 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-end-game-for-youtube-content-pros-secrets-and-templates/"><u>[New] End Game for YouTube Content  Pros' Secrets & Templates</u></a></li>
<li><a href="https://win11.techidaily.com/1719360178726-navigate-and-rectify-common-errors-using-snip-and-sketch-on-windows/"><u>Navigate and Rectify Common Errors Using Snip & Sketch on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-zte-nubia-z60-ultra-frp-bypass-by-drfone-android/"><u>Ultimate Guide on ZTE Nubia Z60 Ultra FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-your-windows-photo-app/"><u>A Comprehensive Guide to Fixing Your Windows Photo App</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-step-by-step-guide-to-launching-your-own-product-critique-network-for-2024/"><u>A Step-by-Step Guide to Launching Your Own Product Critique Network for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-network-security-key-mismatch-error-on-windows-11/"><u>5 Ways to Fix the Network Security Key Mismatch Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-concierge-guide-to-entering-your-windows-11-appshabitat/"><u>A Concierge Guide to Entering Your Windows 11 AppsHabitat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-pinnacle-screenshot-programs/"><u>[Updated] 2024 Approved  Pinnacle Screenshot Programs</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-troubleshooting-windows-desktop-icons/"><u>A Guide to Troubleshooting Windows Desktop Icons</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/create-ai-avatar-video-for-2024/"><u>Create AI Avatar Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719366214502-efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns!</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-efficiency-introducing-flow-launcher-methodology/"><u>Accelerate Workflow Efficiency: Introducing Flow Launcher Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/1719366357478-6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719350786682-operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-11-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-delete-a-drive-partition-on-windows/"><u>4 Ways to Delete a Drive Partition on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-and-upgrade-top-5-essentials-to-enhance-win-pcs/"><u>Accelerate and Upgrade: Top 5 Essentials to Enhance Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1719330356134-unlocking-direct-storage-sharing-using-dropbox-googledrive-on-c/"><u>Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-open-the-startup-repair-tool-on-windows/"><u>5 Ways to Open the Startup Repair Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-expert-tips-for-effortless-instagram-video-dialogues/"><u>[Updated] Expert Tips for Effortless Instagram Video Dialogues</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/gateways-to-googles-advertising-on-youtube-platforms/"><u>Gateways to Google's Advertising on YouTube Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-clear-the-wallpaper-history-on-windows/"><u>3 Ways to Clear the Wallpaper History on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719338015239-team-share-dilemma-heres-the-solution/"><u>Team Share Dilemma? Here's the Solution</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/earn-the-art-of-video-to-animation-stepwise-guide-for-efficient-gif-creation/"><u>[New] Learn The Art Of Video to Animation  Stepwise Guide for Efficient Gif Creation</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dawn-of-taskbars-in-windows-11-proposing-six-crucial-changes-for-enhanced-ux/"><u>A New Dawn of Taskbars in Windows 11: Proposing Six Crucial Changes for Enhanced UX</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-convert-images-to-cartoons-with-ease/"><u>In 2024, Convert Images to Cartoons with Ease</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unrestricted-creativity-the-ultimate-android-editing-selection/"><u>Unrestricted Creativity  The Ultimate Android Editing Selection</u></a></li>
<li><a href="https://win11.techidaily.com/8-handy-windows-11-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 11 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-factory-reset-your-windows-computer/"><u>3 Ways to Factory Reset Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719369400663-unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elevate-your-video-workflow-capturing-mov-files-on-windows-10/"><u>Elevate Your Video Workflow  Capturing MOV Files on Windows 10</u></a></li>
</ul></div>
