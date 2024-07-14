---
title: "Elevate Your Workflow: Adding Tasks to File Context Menus"
date: 2024-07-13T10:16:09.279Z
updated: 2024-07-14T10:16:09.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevate Your Workflow: Adding Tasks to File Context Menus"
excerpt: "This Article Describes Elevate Your Workflow: Adding Tasks to File Context Menus"
keywords: Elevate Tasks UI,Improve Workfile Menu,Streamline File Actions,Optimize File Tools,Enhance Files Menu,Boost Task Infiling,Refine Context Menus
thumbnail: https://thmb.techidaily.com/f8f467b332b89dbb4d8c51eef116fbbce4476e735f93f6027b47c78945bb4e75.jpg
---

## Elevate Your Workflow: Adding Tasks to File Context Menus

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
<li><a href="https://visual-screen-recording.techidaily.com/updated-the-gold-standard-in-selecting-accurate-3ds-simulators/"><u>[Updated] The Gold Standard in Selecting Accurate 3DS Simulators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-capture-video-like-a-pro-on-modern-laptops-for-2024/"><u>[New] Capture Video Like a Pro on Modern Laptops for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-transition-from-stuck-in-windows-1011-s-mode/"><u>Tactics to Transition From Stuck in Windows 10/11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-connect-your-device-bluetooth-error-in-windows-11/"><u>Troubleshooting Connect Your Device Bluetooth Error in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-samsung-galaxy-m54-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Samsung Galaxy M54 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/premier-10-sound-scaling-options-pcs-and-phones-for-2024/"><u>Premier 10 Sound Scaling Options  PCs & Phones for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-free-thumbnail-extract-from-youtube-videos-today/"><u>[Updated] Free Thumbnail Extract From YouTube Videos Today</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-best-obs-settings-for-low-end-pcs/"><u>2024 Approved  Best OBS Settings for Low-End PCs</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/most-asked-questions-about-pokemon-go-battle-league-rewards-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>Most Asked Questions about Pokemon Go Battle League Rewards On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-the-w11-desktop-step-by-step-guide/"><u>Revamping the W11 Desktop: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-how-to-remove-audio-from-a-video-in-imovie-for-2024/"><u>New How to Remove Audio From a Video in iMovie for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Infinix Hot 40i? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-fix-restoring-functionality-to-windows-charmap/"><u>Comprehensive Fix: Restoring Functionality to Windows CharMap</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-ethernet-connection-fixes/"><u>Navigating Through Ethernet Connection Fixes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-tecno-phone-by-drfone-android/"><u>How to Unlock a Network Locked Tecno Phone?</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-out-irregularities-a-guide-to-correction-of-windows-charmap-issues/"><u>Smoothing Out Irregularities: A Guide to Correction of Windows CharMap Issues</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-downfalls-of-modern-standby-in-windows-os/"><u>Dissecting the Downfalls of Modern Standby in Windows OS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-s-top-rated-mp4-to-mp3-converter-apps-for-smartphone-users/"><u>New 2024 Approved S Top-Rated MP4 to MP3 Converter Apps for Smartphone Users</u></a></li>
<li><a href="https://win11.techidaily.com/interfacing-with-the-core-of-windows-print-system/"><u>Interfacing with the Core of Windows Print System</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Tecno Spark 10 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/archive-your-cortana-trails-on-a-pc-operating-system/"><u>Archive Your Cortana Trails on a PC Operating System</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-innovative-methods-for-overwatch-audio-capture/"><u>[Updated] Innovative Methods for Overwatch Audio Capture</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/whats-hot-on-the-app-store-top-iphone-apps-ranked-for-2024/"><u>Whats Hot on the App Store Top iPhone Apps , Ranked for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-refinement-of-music-files-on-mac-a-look-at-the-most-acclaimed-mp3-editors/"><u>Updated Refinement of Music Files on Mac A Look at the Most Acclaimed MP3 Editors</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-income-on-instagram-comprehensive-step-by-step-guide/"><u>2024 Approved  Income on Instagram  Comprehensive Step-by-Step Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-6-plus-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 6 Plus Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-command-prompt-for-ultimate-control/"><u>Configuring Command Prompt for Ultimate Control</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-insightful-update-sonys-s6500-hd-and-bd-player/"><u>2024 Approved  Insightful Update  Sony's S6500 HD & BD Player</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-samsung-galaxy-f15-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Samsung Galaxy F15 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-git-with-github-desktop-and-windows-11/"><u>Unveiling the Power of Git with GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-stitch-it-up-creating-cohesive-tiktok-videos-for-2024/"><u>[Updated] Stitch It Up  Creating Cohesive TikTok Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/regain-lost-dxgidll-with-effective-win11-tactics/"><u>Regain Lost Dxgi.dll with Effective Win11 Tactics</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-10-great-apps-to-turn-funny-animated-images-into-comics-for-2024/"><u>New 10 Great Apps to Turn Funny Animated Images Into Comics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-np-settings-a-simple-fix-guide/"><u>Windows NP Settings: A Simple Fix Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-perfecting-your-soundtrack-techniques-for-implementing-automatic-audio-suppression-in-final-cut-pro-x/"><u>New 2024 Approved Perfecting Your Soundtrack Techniques for Implementing Automatic Audio Suppression in Final Cut Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/altering-output-displays-in-window-based-os/"><u>Altering Output Displays in Window-Based OS</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-mouse-click-rate-with-just-a-few-tweaks/"><u>Skyrocket Mouse Click Rate with Just a Few Tweaks</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-teleconference-recordings/"><u>In 2024, Teleconference Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-fall-guys-connection-errors-on-windows/"><u>How to Fix Fall Guys Connection Errors on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-adding-audio-descriptions-to-videos-on-youtube/"><u>[Updated] Adding Audio Descriptions to Videos on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/is-voice-access-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is Voice Access Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-motorola-edge-40-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Motorola Edge 40</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-joy-essential-list-of-free-media-players-for-windows/"><u>Unleash Joy: Essential List of Free Media Players for Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/precision-in-inshot-transitions-a-step-by-step-guide/"><u>Precision in Inshot Transitions  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-inadvertent-chrome-tab-openings-on-pc/"><u>A Quick Fix for Inadvertent Chrome Tab Openings on PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-2017-data-overload-infographics-and-surprising-yt-stats/"><u>2024 Approved  2017 Data Overload  Infographics & Surprising YT Stats</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/rejuvenated-dialogue-ideas-to-hook-listeners-for-2024/"><u>Rejuvenated Dialogue Ideas to Hook Listeners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-webcam-error-code-a00f4289-on-windows-11/"><u>Deciphering and Rectifying Webcam Error Code A00F4289 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-counter-strike-global-offensive-not-opening-in-windows-11/"><u>How to Fix Counter-Strike: Global Offensive Not Opening in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-transformation-of-heic-files-into-jpeg/"><u>Uncomplicated Transformation of HEIC Files Into JPEG</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-users-from-adjusting-windows-time-and-date/"><u>Stopping Users From Adjusting Windows Time and Date</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-se-2020-to-iphone-81111-pro-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone SE (2020) to iPhone 8/11/11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-hidden-icons-in-windows-11/"><u>Guiding Through Hidden Icons in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-run-as-admin-errors-a-guide/"><u>Overcoming Run as Admin Errors: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-admin-oversight-of-chromium-and-microsoft-edge-browsing-experience/"><u>Revamping Admin-Oversight of Chromium & Microsoft Edge Browsing Experience</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-creating-a-unique-terminal-theme/"><u>The Guide to Creating a Unique Terminal Theme</u></a></li>
<li><a href="https://screen-capture.techidaily.com/capture-gaming-sessions-in-hd-using-obs/"><u>Capture Gaming Sessions in HD - Using OBS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-bring-charisma-to-your-stories-mastery-of-custom-emoji-use-on-instagram/"><u>2024 Approved  Bring Charisma to Your Stories  Mastery of Custom Emoji Use on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/regulating-pcs-to-prevent-windows-11-overheats/"><u>Regulating PCs to Prevent Windows 11 Overheats</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-steam-friends-list-step-by-step-guide-windows-11/"><u>Reconnect Steam Friends List: Step-by-Step Guide, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-dilemma-is-removing-pagefilesys-advisable/"><u>Deletion Dilemma: Is Removing Pagefile.sys Advisable?</u></a></li>
</ul></div>
