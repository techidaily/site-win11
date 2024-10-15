---
title: Upgrade Your File Handling on Windows 11 - Addition of Move/Copy
date: 2024-10-09T19:56:12.616Z
updated: 2024-10-15T18:01:45.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Upgrade Your File Handling on Windows 11 - Addition of Move/Copy
excerpt: This Article Describes Upgrade Your File Handling on Windows 11 - Addition of Move/Copy
keywords: Windows 11 File Upgrade,Copy Move File Tools,Enhanced File Management,New Windows 11 Handling,Efficient File Transfer Windows,Windows 11 File Addition,Optimized File Operation Windows
thumbnail: https://thmb.techidaily.com/b0e0b3709f1348652118c2459af9389796059e0f6579c4e1ae20b05da950739b.jpg
---

## Upgrade Your File Handling on Windows 11 - Addition of Move/Copy

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148127/17093" target="_top" id="2148127">
  <img src="//a.impactradius-go.com/display-ad/17093-2148127" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148127/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-expert-tips-on-choosing-the-best-youtube-to-avi-software/"><u>[New] 2024 Approved Expert Tips on Choosing the Best YouTube-to-AVI Software</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-arcadia-elite-seamless-full-hd-multi-touch-desktops/"><u>[New] In 2024, Arcadia Elite Seamless, Full HD Multi-Touch Desktops</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-importing-audio-steps-for-inshot-video-editing/"><u>[Updated] In 2024, Importing Audio Steps for InShot Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/1-quick-and-simple-guide-downloading-and-setting-up-showbox-on-your-computer/"><u>1. Quick & Simple Guide: Downloading & Setting Up ShowBox on Your Computer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-top-10-screen-free-android-apps-for-leisurely-gaming/"><u>2024 Approved Top 10 Screen-Free Android Apps for Leisurely Gaming</u></a></li>
<li><a href="https://driver-download.techidaily.com/correct-methods-for-installing-new-drivers-on-dell-webcams/"><u>Correct Methods for Installing New Drivers on Dell Webcams</u></a></li>
<li><a href="https://win11.techidaily.com/handling-runtime-failure-tips-for-correcting-malwarebytes-execution-errors-on-win10win11/"><u>Handling Runtime Failure: Tips for Correcting Malwarebytes' Execution Errors on Win10/Win11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-capturing-the-web-in-motion-a-compact-list-of-leading-recorders/"><u>In 2024, Capturing the Web in Motion A Compact List of Leading Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/intel-unison-not-working-try-this-fix-guide-on-windows-11/"><u>Intel Unison Not Working? Try This Fix Guide on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-notes-at-the-forefront-on-win-oses/"><u>Keep Your Notes at the Forefront on Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-search-troubleshooting-steps/"><u>Navigating Through Windows Search Troubleshooting Steps</u></a></li>
<li><a href="https://article-posts.techidaily.com/premium-memory-device-for-sony-a7s-cameras-for-2024/"><u>Premium Memory Device for Sony A7S Cameras for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-win11-vagrant-start-issues-with-7-effective-approaches/"><u>Resolve Win11 Vagrant Start Issues with 7 Effective Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-getting-started-with-outlook-preview-on-windows-11/"><u>Seamless Transition: Getting Started with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-software-windows-best-photo-arrangers-reviewed/"><u>Winning Software: Windows' Best Photo Arrangers Reviewed</u></a></li>
</ul></div>

