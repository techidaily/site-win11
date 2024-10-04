---
title: "Implementing Custom Folder Options: Adding 'Move'/'Copy' To Context Menu"
date: 2024-09-29T01:14:21.462Z
updated: 2024-10-04T02:21:09.098Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Implementing Custom Folder Options: Adding 'Move'/'Copy' To Context Menu"
excerpt: "This Article Describes Implementing Custom Folder Options: Adding 'Move'/'Copy' To Context Menu"
keywords: Move/Copy Context Menu,Folder Actions,File Menu Change,Right-Click Modify,Custom Folders Add,Extend Context Options,Files Menu Movement
thumbnail: https://thmb.techidaily.com/a208b6b47f62fc53f6719bf37fb44710d3bca87f00271cab6e02272f4110e26d.jpg
---

## Implementing Custom Folder Options: Adding 'Move'/'Copy' To Context Menu

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-videos.techidaily.com/new-breakdown-of-earnings-how-much-does-a-clicky-make/"><u>[New] Breakdown of Earnings How Much Does a Clicky Make?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-apeak-captures-attention-an-in-depth-screen-recorder-examination-for-2024/"><u>[Updated] Apeak Captures Attention An In-Depth Screen Recorder Examination for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-game-on-video-recording-revolution/"><u>2024 Approved Game On Video Recording Revolution</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-pioneering-visual-stories-with-windows-10-photos-and-story-remix/"><u>2024 Approved Pioneering Visual Stories with Window's 10 Photos & Story Remix</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-streamlining-visual-content-applying-texts-to-photos-in-windows-10/"><u>2024 Approved Streamlining Visual Content Applying Texts to Photos in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/effective-steps-to-update-login-credentials-on-win-11/"><u>Effective Steps to Update Login Credentials on Win 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-driver-update-for-your-aoc-monitor-with-windows-compatibility-guide/"><u>Get the Newest Driver Update for Your AOC Monitor with Windows Compatibility Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-eliminate-microsoft-offices-error-code-0x80041015/"><u>Guide to Eliminate Microsoft Office's Error Code 0X80041015</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-motorola-moto-g84-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Motorola Moto G84 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://win11.techidaily.com/latency-less-viewing-optimizing-winx-media-with-these-fixes/"><u>Latency-Less Viewing: Optimizing WinX Media with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inactive-mail-signals-for-outlook-users/"><u>Mending Inactive Mail Signals for Outlook Users</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-how-to-access-and-watch-nonstop-nba-live-stream-free-online-for-2024/"><u>New How To Access and Watch Nonstop NBA Live Stream Free Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-stop-video-resets-on-win1110-devices/"><u>Strategies to Stop Video Resets on Win11/10 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-symbiosis-navigating-github-desktop-and-windows-11/"><u>The Perfect Symbiosis: Navigating GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-steps-for-smooth-playback-of-cyberpunk-2077-and-virtues-last-reward-on-desktop/"><u>Troubleshooting Steps for Smooth Playback of Cyberpunk 2077 & Virtue's Last Reward on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-drives-c-and-d/"><u>Unraveling the Mystery of Windows Drives (C & D)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-innovation-four-revolutionary-updates-for-paint/"><u>Unveiling Innovation: Four Revolutionary Updates for Paint</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-bt-folders/"><u>Unveiling the Mystery of Windows ~BT Folders</u></a></li>
<li><a href="https://vp-tips.techidaily.com/vrij-nieuw-mediaconverter-mp2-naar-flac-online-gratis-demo-versie-movavi/"><u>Vrij Nieuw Mediaconverter MP2 Naar FLAC Online - Gratis Demo Versie Movavi</u></a></li>
</ul></div>

