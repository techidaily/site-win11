---
title: "Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11"
date: 2024-07-13T10:23:03.911Z
updated: 2024-07-14T10:23:03.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11"
excerpt: "This Article Describes Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11"
keywords: Win 11 Copy & Move Tutorial,Win 11 Command Integration,Windows 11 File Management Guide,Win 11 Move Files Steps,Copy Files in Win 11 Guide,Moving Texts in Win 11,Execute Copy/Move Commands Win 11
thumbnail: https://thmb.techidaily.com/f2d53ebba5315caabb937b6a02076182259db722e8470506c861929020be203d.jpg
---

## Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the [Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our [how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
2. Click inside the address bar at the top of Registry Editor, and erase the current key location there.
3. Then enter this**ContextMenuHandlers** key location and press**Return** :  
`HKEY_CLASSES_ROOT\AllFilesystemObjects\shellex\ContextMenuHandlers`
4. Next, right-click**ContextMenuHandlers** and select the**New** submenu.
5. Click**Key** on the submenu.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-key-option.jpg)

1. Enter**Move to folder** for the new key’s name.
2. Select the new**Move to folder** key in the Registry Editor’s sidebar.
3. Double-click the**(Default)** string for the selected key.
4. Input**{C2FBB631-2971-11D1-A18C-00C04FD75D13}** inside the**Value data** box.  
![The value data for the Move to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window.jpg)
5. Select**OK** to set the new value for the (Default) string.
6. Exit the Registry Editor.

 You can now try out the new**Move to folder** option on the context menu. Press the**Explorer** taskbar button to view the Windows file manager. Right-click a file and select the new**Move to folder** option. You’ll need to select**Show more options** \>**Move to folder i** n Windows 11.

![The Move to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-to-folder-context-menu-option.jpg)

 A small Move Items window will then appear from which you can select a destination folder. Choose a folder to move the file to in that window. Then click**Move** to place the file in the selected directory.

![The Move Items window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-items-window.jpg)

## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to [the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
![The Extract all option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/extract-all-option.jpg)
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

## Move and Copy Files to Folders With Your New Context Menu Options

 The**"** Copy/Move to folder" context menu options undoubtedly provide more convenient ways to copy and move files into alternative directories. You won’t need to drag files about anymore for moving items in Windows 11 after adding a new**"** Move to Folder option" to the right-click menu. Nor will you need to paste copied files elsewhere in Windows 11 thanks to the "Copy to folder" menu option.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook.techidaily.com/5-pinnacle-platforms-revolutionizing-business-marketing/"><u>5 Pinnacle Platforms Revolutionizing Business Marketing</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-printer-network-errors-in-windows/"><u>Steps to Resolve Printer Network Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-lockout-duration-post-failed-logon/"><u>Altering Windows Lockout Duration Post-Failed Logon</u></a></li>
<li><a href="https://howto.techidaily.com/fix-vivo-y100a-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Vivo Y100A Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-process-how-to-setup-google-maps-on-pc/"><u>A Step-by-Step Process: How to Setup Google Maps on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamline-your-path-to-youtubes-srt-files/"><u>In 2024, Streamline Your Path to YouTube's SRT Files</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-overcoming-windows-1011s-isdonedll-errors/"><u>Deciphering and Overcoming Windows 10/11'S ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-13-step-blueprint-to-reactivating-your-windows/"><u>The 13-Step Blueprint to Reactivating Your Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-advice-to-supercharge-your-wsl-2-and-docker-use/"><u>Essential Advice to Supercharge Your WSL 2 and Docker Use</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-your-computers-msvcr110dll-void/"><u>Remedying Your Computer’s Msvcr110.dll Void</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-risks-for-windows-bt-folder-expert-advice/"><u>Deletion Risks for Windows ~BT Folder: Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/winmc-lan-connectivity-woes-solutions-explored/"><u>WinMC LAN Connectivity Woes: Solutions Explored</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/breakthrough-personalities-on-tiktok-a-guide-for-motivation-for-2024/"><u>Breakthrough Personalities on TikTok  A Guide for Motivation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-a-distraction-free-start-with-win-11/"><u>Embrace a Distraction-Free Start with Win 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-z50s-pro-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Z50S Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-nubia-red-magic-8s-proplus-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Nubia Red Magic 8S Pro+ Phone</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-dedicated-ram-win-11-edition-guide/"><u>Augmenting Dedicated RAM: Win 11 Edition Guide</u></a></li>
<li><a href="https://win11.techidaily.com/ditching-taskbar-chatting-in-windows-11-how-will-it-influence-your-experience/"><u>Ditching Taskbar Chatting in Windows 11: How Will It Influence Your Experience?</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-slow-motion-on-tiktok-a-step-by-step-guide-for-2024/"><u>Mastering Slow Motion on TikTok  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-on-windows-11-desktop-ui/"><u>Increase Visible Pins on Windows 11 Desktop UI</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-everlasting-file-elimination-on-your-desktop-bin-with-windows-11/"><u>Simplifying Everlasting File Elimination on Your Desktop Bin with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-accessing-win-11s-call-center/"><u>Quick Guide: Accessing Win 11'S Call Center</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-honor-magic-v2-by-drfone-android/"><u>How to Bypass FRP from Honor Magic V2?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-charting-your-path-to-higher-youtube-spotlight/"><u>In 2024, Charting Your Path to Higher YouTube Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-access-barriers-top-solutions/"><u>Navigating Through Windows Access Barriers: Top Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-login-remote-desktop-innovations-on-win-11/"><u>Zero-Entry Login: Remote Desktop Innovations on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-compatible-nds-emulators/"><u>Top Windows Compatible NDS Emulators</u></a></li>
<li><a href="https://audio-editing.techidaily.com/top-sites-to-download-lofi-wallpapers-and-lofi-background-music-for-2024/"><u>Top Sites to Download Lofi Wallpapers and Lofi Background Music for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-adding-gmaps-in-windows-os/"><u>The Ultimate Guide to Adding GMaps in Windows OS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-7-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone 7 i Do? Get Answers here</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-handshake-direct-pc-links-in-windows-11-rdp/"><u>The Invisible Handshake: Direct PC Links in Windows 11 RDP</u></a></li>
<li><a href="https://win11.techidaily.com/fast-setupuninstall-bings-ai-on-win-11-taskbar/"><u>Fast Setup/Uninstall: Bing's AI on Win 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steam-network-access-on-pc-windows/"><u>Unlocking Steam Network Access on PC Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-username-switch-on-windows-11/"><u>Streamlining the UserName Switch on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-recognition-failure-in-windows-installation/"><u>Overcoming Device Recognition Failure in Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-optimal-windows-11-search-performance/"><u>Navigating to Optimal Window's 11 Search Performance</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
</ul></div>
