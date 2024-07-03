---
title: Elevate Your File Handling in Win 11 by Adding Move/Copy Menus
date: 2024-06-25T11:24:47.318Z
updated: 2024-06-26T11:24:47.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Your File Handling in Win 11 by Adding Move/Copy Menus
excerpt: This Article Describes Elevate Your File Handling in Win 11 by Adding Move/Copy Menus
keywords: Win 11 File Management,Copy Files Win11,Move Folders Win11,Optimize File Handling Win11,Elevate Win11 Shell,Advanced File Options Win11,Integrated File Tools Win11
thumbnail: https://thmb.techidaily.com/97b5d85adaa70d7cf066a732f43c0486f51d36a4ba60d02434a07b91f944e872.jpg
---

## Elevate Your File Handling in Win 11 by Adding Move/Copy Menus

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the[Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our[how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
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

1. Head over to[the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
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
<li><a href="https://win11.techidaily.com/troubleshooting-connect-your-device-bluetooth-error-in-windows-11/"><u>Troubleshooting Connect Your Device Bluetooth Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-regain-control-over-non-operational-media-playback/"><u>Strategies to Regain Control Over Non-Operational Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/removing-the-0x800704cf-hurdle-in-windows-store-experience/"><u>Removing the 0X800704CF Hurdle in Windows Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unravel-winerror-incorrect-file-backups-in-windows/"><u>How to Unravel WinError: Incorrect File Backups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/digging-into-drive-labels-c-and-d-unpacked/"><u>Digging Into Drive Labels: C & D Unpacked</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-disconnected-remote-resources-in-windows/"><u>Strategies to Address Disconnected Remote Resources in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-a-non-responsive-windows-notepad-application/"><u>How to Revive a Non-Responsive Windows Notepad Application</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-photoshop-wont-launch-in-windows-1011/"><u>Troubleshooting PhotoShop Won't Launch in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-boost-your-posts-with-these-8-instagram-scheduling-apps/"><u>2024 Approved  Boost Your Posts with These 8 Instagram Scheduling Apps</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-hot-40i-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Hot 40i in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-honor-70-lite-5g-phone-by-drfone-android/"><u>How to Unlock a Network Locked Honor 70 Lite 5G Phone?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-get-to-know-vrecorder-the-perfect-installation-process/"><u>In 2024, Get to Know VRecorder  The Perfect Installation Process</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-samsung-galaxy-a25-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Samsung Galaxy A25 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-exploring-top-rated-podcast-hosting-solutions/"><u>New 2024 Approved Exploring Top-Rated Podcast Hosting Solutions</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-honor-90-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Honor 90 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-top-10-android-dlna-for-nintendo-3ds-games/"><u>[Updated] Top 10 Android DLNA for Nintendo 3DS Games</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-top-10-wave-capturing-cams/"><u>[New] 2024 Approved  The Top 10 Wave-Capturing Cams</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-essential-tips-for-efficiently-using-ez-grabber/"><u>[New] 2024 Approved  Essential Tips for Efficiently Using EZ Grabber</u></a></li>
</ul></div>
