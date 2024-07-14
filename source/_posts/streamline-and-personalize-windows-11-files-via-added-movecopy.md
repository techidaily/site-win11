---
title: Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'
date: 2024-07-13T10:00:58.466Z
updated: 2024-07-14T10:00:58.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'
excerpt: This Article Describes Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'
keywords: Streamlined Win11 Organization,Personalized File Management in Win11,Enhanced Move/Copy Options,Windows 11 Efficient Transfer,Customize Win11 Copy Feature,Optimized Win11 Moving Tools,Intuitive Win11 File Handling
thumbnail: https://thmb.techidaily.com/c26754d00328593cefb7ceb60f51391dcd2a8dd934a3e89af40244a078e590d9.jpg
---

## Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-expert-analysis-highest-quality-video-snappers/"><u>[New] In 2024, Expert Analysis  Highest Quality Video Snappers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-exploring-the-hidden-gems-of-jazz-musics-fundamentals/"><u>New In 2024, Exploring the Hidden Gems of Jazz Musics Fundamentals</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-microsoft-powerpoint-prints-on-windows/"><u>Navigating the Maze of Microsoft PowerPoint Prints on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-path-not-found-on-pc-networks/"><u>Addressing Path Not Found on PC Networks</u></a></li>
<li><a href="https://win11.techidaily.com/mapping-out-gpo-landscape-a-gpresult-perspective/"><u>Mapping Out GPO Landscape: A GPResult Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/deleting-windows-bt-directory-purpose-and-process/"><u>Deleting Windows ~BT Directory: Purpose & Process</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-image-formats-stopping-chromes-webp-savings-on-pc/"><u>Mastering Image Formats: Stopping Chrome's WebP Savings on PC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-utilizing-the-virtual-whiteboard-in-webinars-cross-platform-tips-and-tricks-for-2024/"><u>[New] Utilizing the Virtual Whiteboard in Webinars  Cross-Platform Tips and Tricks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-valorant-lags-with-windows-tweaks/"><u>Eliminating Valorant Lags with Windows Tweaks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-guide-uploading-vimeo-videos/"><u>In 2024, Instagram Guide  Uploading Vimeo Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-ace-your-youtube-live-with-these-7-powerful-live-streaming-apps-iosandroid-os/"><u>2024 Approved  Ace Your YouTube LIVE with These 7 Powerful Live Streaming Apps (iOS/Android OS)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-to-windows-odbc-settings/"><u>Mastering Access to Windows' ODBC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-password-protectionists-for-the-modern-windows-user/"><u>Masterful Password Protectionists for the Modern Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-to-reality-efficiently-launching-windows-11-from-scratch/"><u>Rewind to Reality: Efficiently Launching Windows 11 From Scratch</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-or-displaying-time-win-1011-tutorial/"><u>Disguising or Displaying Time: Win 10/11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-task-of-updating-administrator-name-on-windows-11/"><u>Simplifying the Task of Updating Administrator Name on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/journey-through-audio-production-initiating-with-auditions-fade-in/"><u>Journey Through Audio Production  Initiating with Audition’s Fade In</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-instructions-eradicating-wsl-from-windows/"><u>Comprehensive Instructions: Eradicating WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-step-by-step-expedition-to-youtubes-unseen-layers/"><u>[Updated] 2024 Approved  A Step-by-Step Expedition to YouTube's Unseen Layers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sales-surge-strategy-techniques/"><u>2024 Approved  Sales Surge Strategy Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-cutting-down-cpu-load-on-windows-hosts/"><u>Mastery of Cutting Down CPU Load on Windows Hosts</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-of-discrete-audio-erosion-in-audacity/"><u>[Updated] The Art of Discrete Audio Erosion in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-high-cpu-usage-a-guide-via-windows-resource-monitor/"><u>Conquering High CPU Usage: A Guide via Windows Resource Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-workspace-incorporating-sketches-into-windows-11/"><u>Customize Your Workspace: Incorporating Sketches Into Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-viral-video-alert-the-days-10-heat-generating-tweets/"><u>[New] 2024 Approved  Viral Video Alert  The Day's 10 Heat-Generating Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-files-navigate-smaller-with-windows-explorer/"><u>Simplifying Files: Navigate Smaller with Windows Explorer</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-track-analyze-improve-top-motion-tracking-apps-for-athletes-and-more/"><u>New In 2024, Track, Analyze, Improve Top Motion Tracking Apps for Athletes and More</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-closed-caption-mishaps-in-windows-10/"><u>Resolving Closed Caption Mishaps in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-access-10-fast-methods-to-control-center/"><u>Accelerate Access: 10 Fast Methods to Control Center</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/google-nearby-share-vs-windows-nearby-sharing-which-should-you-use/"><u>Google Nearby Share Vs. Windows Nearby Sharing: Which Should You Use?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/stunning-glitch-effect-and-its-creation-guideline-for-premiere-pro-for-2024/"><u>Stunning Glitch Effect and Its Creation Guideline for Premiere Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-onedrive-servers-errors-easily/"><u>Navigating Through OneDrive Servers Errors Easily</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-dont-get-lost-in-conversion-mp3-to-mp4-best-practices/"><u>2024 Approved Dont Get Lost in Conversion MP3 to MP4 Best Practices</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-best-chrome-os-tts-tools-top-5-online-speech-converters/"><u>[Updated] In 2024, Best Chrome OS TTS Tools  Top 5 Online Speech Converters</u></a></li>
<li><a href="https://extra-resources.techidaily.com/voices-on-the-page-techniques-for-effective-scriptwriting/"><u>Voices on the Page  Techniques for Effective Scriptwriting</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-your-apple-iphone-x-from-your-apple-id-by-drfone-ios/"><u>In 2024, How To Unlink Your Apple iPhone X From Your Apple ID</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-winget-on-w11/"><u>Comprehensive Guide to Fixing Winget on W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://win11.techidaily.com/windows-1011-reimagined-establishing-personalized-pin-patterns/"><u>Windows 10/11 Reimagined: Establishing Personalized Pin Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-rgb-customization-on-your-win11-device/"><u>Enabling RGB Customization on Your Win11 Device</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/master-background-banishment-tool-content-creators-sharpen-your-visual-narratives-for-2024/"><u>Master Background Banishment Tool Content Creators Sharpen Your Visual Narratives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/skillful-workflow-customizing-windows-11-shortcuts-by-power-button/"><u>Skillful Workflow: Customizing Windows 11 Shortcuts by Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-life-solutions-for-non-responsive-bluetooth-mice-windows/"><u>Bring Back the Life: Solutions for Non-Responsive Bluetooth Mice (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/skimming-through-complex-windows-update-issues-with-error-0x800736cc/"><u>Skimming Through Complex Windows Update Issues with Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-control-slider-not-working-in-windows-11-and-11/"><u>How to Fix the Volume Control Slider Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-block-of-microsoft-store-in-windows-11/"><u>Disabling Block of Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-achieve-a-seamless-experience-less-latency-more-fps/"><u>How to Achieve a Seamless Experience: Less Latency, More FPS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-should-you-review-off-facebook-histories-security-tips-and-tricks/"><u>[New] Should You Review Off-Facebook Histories? Security Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-effortless-data-purging-in-windows-1011/"><u>Master the Art of Effortless Data Purging in Windows 10/11</u></a></li>
</ul></div>
