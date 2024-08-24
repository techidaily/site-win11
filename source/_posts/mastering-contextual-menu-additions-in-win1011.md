---
title: Mastering Contextual Menu Additions in Win10/11
date: 2024-08-23T06:07:38.133Z
updated: 2024-08-24T06:07:38.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Contextual Menu Additions in Win10/11
excerpt: This Article Describes Mastering Contextual Menu Additions in Win10/11
keywords: Win10 Menu Tips,Win11 Menu Strategies,UI Customization Win10,Win10 Contextual Adds,Win11 Enhanced Menus,Contextual Menu Advance,Modern Windows Menu
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
---

## Mastering Contextual Menu Additions in Win10/11

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fitness-forward-6-video-concepts-to-energize-your-online-community/"><u>[New] 2024 Approved  Fitness Forward  6 Video Concepts to Energize Your Online Community</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-video-capturing-warriors-choosing-between-obs-and-fraps/"><u>[New] 2024 Approved  Video Capturing Warriors  Choosing Between OBS and Fraps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-ace-soundtracks-collection-for-cinematography/"><u>[New] Ace Soundtracks Collection for Cinematography</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-bridging-the-gap-an-introduction-to-av1/"><u>[New] Bridging the Gap  An Introduction to AV1</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-cg318-4k-unveiled-eizos-high-res-monitor-review/"><u>[New] CG318-4K Unveiled  EIZO's High-Res Monitor Review</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-add-filters-and-music-on-windows-11-photos-app/"><u>[New] How to Add Filters and Music on Windows 11 Photos App</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-using-telegram-web-effectively/"><u>[New] The Ultimate Guide to Using Telegram Web Effectively</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-capture-the-essence-extracting-youtube-audio-directly/"><u>[Updated] Capture the Essence  Extracting YouTube Audio Directly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-heaviest-heroes-in-the-air-drone-power-list/"><u>[Updated] Heaviest Heroes in the Air  Drone Power List</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-optimize-online-presence-video-embellishment-with-logos-and-watermarks-for-2024/"><u>[Updated] Optimize Online Presence  Video Embellishment with Logos and Watermarks for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-video-repair-tool-to-fix-and-repair-corrupted-video-files-of-nubia-z50s-pro-by-stellar-video-repair-mobile-video-repair/"><u>Best Video Repair tool to Fix and Repair Corrupted video files of Nubia Z50S Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/capturing-gaming-moments-look-beyond-xboxs-game-bar-for-2024/"><u>Capturing Gaming Moments  Look Beyond Xbox's Game Bar for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-a-chorus-of-images-and-sound-on-instagram/"><u>Crafting a Chorus of Images & Sound on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/does-pressing-prtscr-start-snipping-tool-on-win-11-trick-to-block-it/"><u>Does Pressing PrtScr Start Snipping Tool on Win 11? Trick to Block It</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/effortless-voice-memo-recording-on-your-iphone-for-2024/"><u>Effortless Voice Memo Recording on Your iPhone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-ide-speed-and-productivity-for-developers-on-windows/"><u>Enhancing IDE Speed & Productivity for Developers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enlightening-windows-users-on-camera-memory-issues/"><u>Enlightening Windows Users on Camera Memory Issues</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-top-8-win11-choices-for-professional-videoscripting/"><u>Explore the Top 8 Win11 Choices for Professional Videoscripting</u></a></li>
<li><a href="https://extra-resources.techidaily.com/finding-voice-changers-for-vtubers-two-best-app-recommended/"><u>Finding Voice Changers for Vtubers  Two Best App Recommended</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-y55s-5g-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-zero-x-error-in-windows-11s-mail-application/"><u>Fixing Zero X Error in Windows 11'S Mail Application</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-your-camon-20-lock-screen-pattern-pin-or-password-heres-what-to-do-by-drfone-android-unlock-android-unlock/"><u>Forgot your Camon 20 lock screen pattern, PIN or password? Here’s what to do</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-successful-or-failed-login-attempts-on-your-windows-computer/"><u>How to Check Successful or Failed Login Attempts on Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-discords-cannot-resize-gif-error-on-windows-11/"><u>How to Fix Discord's Cannot Resize GIF Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-merge-adjacent-and-non-adjacent-partitions-in-windows/"><u>How to Merge Adjacent and Non-Adjacent Partitions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reconnect-disconnected-file-apps-in-windows/"><u>How to Reconnect Disconnected File Apps in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-meizu-21-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Meizu 21 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beyond-the-screen-a-vr-odyssey/"><u>In 2024, Beyond the Screen  A VR Odyssey</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-honor-play-8t-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Honor Play 8T Devices | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-harness-social-blade-for-profound-youtube-stats-analysis/"><u>In 2024, Harness Social Blade for Profound YouTube Stats Analysis</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-itel-a70-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Itel A70 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oppo-reno-11f-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Oppo Reno 11F 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-exclusion-dilemma-is-someone-hidden-on-snapchat/"><u>In 2024, The Exclusion Dilemma  Is Someone Hidden On Snapchat?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-bloatware-removal-in-windows-11/"><u>Mastering Bloatware Removal in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-microsofts-phone-link-app-explained/"><u>Mastering Connectivity: Microsoft’s Phone Link App Explained</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-download-rates-for-epic-launcher/"><u>Mastering Fast Download Rates for Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-transparency-on-windows-11-machines/"><u>Maximizing Window Transparency on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-rectify-game-pass-issues-on-windows-os/"><u>Methods to Rectify Game Pass Issues on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-restore-on-windows-for-past-fixes/"><u>Navigating System Restore on Windows for Past Fixes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/on-the-go-conversations-leveraging-chatgpt-features-across-ios-and-android-platforms/"><u>On-the-Go Conversations: Leveraging ChatGPT Features Across iOS and Android Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-flawed-menu-navigation-in-windows-desktops/"><u>Overcoming Flawed Menu Navigation in Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-overcoming-xbox-game-pass-warzones-directx-issues/"><u>Quick Fixes for Overcoming Xbox Game Pass Warzone's DirectX Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solution-conquer-camera-fails-in-windows-os/"><u>Quick Solution: Conquer Camera Fails in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-reconnecting-distant-devices-in-windows/"><u>Regaining Control: Reconnecting Distant Devices in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/revealing-the-top-six-where-to-grab-your-snack-videos/"><u>Revealing the Top Six  Where to Grab Your Snack Videos</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-cyber-travel-mastering-connections-on-windows-pc/"><u>Seamless Cyber Travel: Mastering Connections on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/six-proven-techniques-for-pinpointing-your-pcs-brand-and-version/"><u>Six Proven Techniques for Pinpointing Your PC's Brand & Version</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-performance-with-expert-tips-on-wintoys-usage/"><u>Skyrocket Performance with Expert Tips on Wintoys Usage</u></a></li>
<li><a href="https://win-amazing.techidaily.com/speedy-setup-secure-intel-cpu-driver-downloads-today/"><u>Speedy Setup: Secure Intel CPU Driver Downloads Today</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-unexpected-command-prompt-displays/"><u>Stopping Unexpected Command Prompt Displays</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-11-logon-from-pin-to-password-a-step-by-step-guide/"><u>Switching Windows 11 Logon From PIN to Password: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-operation-failed-problem-on-pcs/"><u>Tackling the Operation Failed Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-functionalities-of-fn-keys-on-windows-11-devices/"><u>Tailoring Functionalities of FN Keys on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-integrity-in-the-windows-registry/"><u>The Ultimate Guide to Restoring Integrity in the Windows Registry</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-ultimate-guide-to-scheduling-zoom-events-for-2024/"><u>The Ultimate Guide to Scheduling Zoom Events for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/loggers-retreat-excellence-unleashed/"><u>The Vloggers' Retreat  Excellence Unleashed</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-breakdown-how-to-pre-emptive-access-updates/"><u>ViVeTool Breakdown: How to Pre-Emptive Access Updates</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-comprehensive-navshortcut-compendium/"><u>Win11's Comprehensive NavShortcut Compendium</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-diverse-monitor-decorations-1011-edition/"><u>Windows Wonders: Diverse Monitor Decorations, 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-adoption-and-linux-market-dynamics/"><u>WSL Adoption and Linux Market Dynamics</u></a></li>
</ul></div>
