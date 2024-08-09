---
title: "Advanced File System Interactions: A Step-Bystep Guide"
date: 2024-08-08T13:13:04.653Z
updated: 2024-08-09T13:13:04.653Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced File System Interactions: A Step-Bystep Guide"
excerpt: "This Article Describes Advanced File System Interactions: A Step-Bystep Guide"
keywords: Filesystem Basics,Storage Device Management,Data Access Methods,OS File Handling,I/O Operations Analysis,Disk Scheduling Strategies,File System Efficiency
thumbnail: https://thmb.techidaily.com/904e4358c32651c8870cd752598cbad0b1afa3205d185e4b265bf0a0d105bd32.jpg
---

## Advanced File System Interactions: A Step-Bystep Guide

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
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to [the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-youtube-beginners-basics-establishing-your-channel-and-earning-profits/"><u>[New] 2024 Approved  Youtube Beginner's Basics  Establishing Your Channel & Earning Profits</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-key-10-windows-software-for-superior-tiktok-editing-for-2024/"><u>[New] Key 10 Windows Software for Superior TikTok Editing for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-streamlining-your-zoom-recordings-a-comprehensive-workshop/"><u>[Updated] Streamlining Your Zoom Recordings  A Comprehensive Workshop</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-leading-9-mic-technology-a-comprehensive-analysis/"><u>2024 Approved  Leading 9 Mic Technology  A Comprehensive Analysis</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-nba-game-broadcasting-select-the-best-platforms/"><u>2024 Approved  NBA Game Broadcasting  Select the Best Platforms</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-video-editors-alternatives-to-inshot/"><u>2024 Approved  Video Editors Alternatives to Inshot</u></a></li>
<li><a href="https://win11.techidaily.com/averting-steam-library-write-errors-on-modern-windows-pcs/"><u>Averting Steam Library Write Errors on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-losses-commit-to-daily-windows-data-archiving/"><u>Avoid Losses: Commit to Daily Windows Data Archiving</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-frequent-rainmeter-setbacks-an-easy-guide/"><u>Decoding and Fixing Frequent Rainmeter Setbacks: An Easy Guide</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multi-selection-activating-windows-11s-checkboxes/"><u>Efficient Multi-Selection: Activating Windows 11'S Checkboxes</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-connection-stop-usb-sleep-in-win-11/"><u>Ensuring Continuous Connection: Stop USB Sleep in Win 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/fast-tracking-fb-content-efficiency-strategies-explored/"><u>Fast-Tracking FB Content  Efficiency Strategies Explored</u></a></li>
<li><a href="https://tech-haven.techidaily.com/global-warming-or-just-hot-summers-climate-clarity/"><u>Global Warming or Just Hot Summers? Climate Clarity</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-to-completely-erase-data-on-iphone-11-to-avoid-privacy-leak-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Guide to Completely Erase Data on iPhone 11 to Avoid Privacy Leak | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-fix-non-opening-photoshop-on-latest-windows-11/"><u>Guides to Fix Non-Opening Photoshop on Latest Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-xiaomi-redmi-k70-pro-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Xiaomi Redmi K70 Pro? Fix Now | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-13-proipad-drfone-by-drfone-virtual-ios/"><u>In 2024, A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 13 Pro/iPad | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-beginners-bonanza-affordable-profitable-channel-options/"><u>In 2024, Beginner's Bonanza  Affordable, Profitable Channel Options</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-beginners-guide-to-inconspicuous-image-tinkering/"><u>In 2024, Beginner's Guide to Inconspicuous Image Tinkering</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-best-10-volume-elevators-for-windows-ios-and-android/"><u>In 2024, Best 10 Volume Elevators for Windows, iOS & Android</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-poco-c50-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Poco C50 FRP</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-huawei-nova-y71-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Huawei Nova Y71 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-xiaomi-redmi-k70-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Xiaomi Redmi K70 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-from-iphone-15-pro-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server From iPhone 15 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-instructions-for-setting-up-dolby-atmos-in-windows-1111/"><u>In-Depth Instructions for Setting Up Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/master-window-11s-icon-arrangement/"><u>Master Window 11'S Icon Arrangement</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-space-windows-11s-disk-defragmentation-guide/"><u>Maximizing Space: Windows 11'S Disk Defragmentation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-fatal-js-error-in-discord-on-modern-windows-11/"><u>Navigating Past Fatal JS Error in Discord on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-and-thrive-harnessing-the-power-of-wintoys/"><u>Optimize and Thrive: Harnessing the Power of Wintoys</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/premium-planet-friendly-recording-software-for-2024/"><u>Premium, Planet-Friendly Recording Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-dormant-slack-alerts-on-modern-windows-pcs/"><u>Reinstating Dormant Slack Alerts on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reinvigorating-the-stuck-windows-start-menu-symbol/"><u>Reinvigorating the Stuck Windows Start Menu Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016162732-resolving-sound-distortion-and-stuttering-troubles-on-your-windows-117-system-expert-solutions-revealed/"><u>Resolving Sound Distortion & Stuttering Troubles on Your Windows 11/7 System - Expert Solutions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-deleted-characters-a-guide-for-windows-users/"><u>Restoring Deleted Characters: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-microsoft-store-crash-0x80073d26/"><u>Strategies to Overcome Microsoft Store Crash: 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-dynamic-walls-in-windows-11-for-enhanced-aesthetics/"><u>The Art of Dynamic Walls in Windows 11 for Enhanced Aesthetics</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-file-transfer-integrating-zip-into-image-files-win/"><u>The Unseen File Transfer: Integrating ZIP Into Image Files (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadows-tackling-wacatacbml-on-microsoft-windows/"><u>Unveiling the Shadows: Tackling Wacatac.B!ml on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719338109987-windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony</u></a></li>
</ul></div>
