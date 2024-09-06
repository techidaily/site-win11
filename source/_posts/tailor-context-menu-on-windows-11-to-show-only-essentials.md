---
title: Tailor Context Menu on Windows 11 to Show Only Essentials
date: 2024-09-05T08:30:18.278Z
updated: 2024-09-06T08:30:18.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailor Context Menu on Windows 11 to Show Only Essentials
excerpt: This Article Describes Tailor Context Menu on Windows 11 to Show Only Essentials
keywords: Win11 ContextMenu Tune,Essential Menu Items,Streamline Win11 UI,ContextMenu Optimization,Minimize Window Menus,Windows UI Simplify,Tailor WinContext Efficiently
thumbnail: https://thmb.techidaily.com/63d0193e0fa009273c448c859b93e6725b6f99b3ee60a88ba18b85321387d187.jpg
---

## Tailor Context Menu on Windows 11 to Show Only Essentials

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-mastering-animations-and-crafting-custom-visual-impact/"><u>[New] 2024 Approved  Mastering Animations & Crafting Custom Visual Impact</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-discarding-virtual-gatherings-on-fb-pcsmartphones/"><u>[New] Discarding Virtual Gatherings on FB, PC/Smartphones</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-share-wisdom-top-strategies-for-video-sharing-on-instagram-for-2024/"><u>[New] Share Wisdom  Top Strategies for Video Sharing on Instagram for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-full-review-and-how-to-for-facetunes-new-features/"><u>[New] The Full Review and How-To for Facetune's New Features</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-deep-dive-into-asus-pa32u-review-excellence-in-professionalism/"><u>[Updated] 2024 Approved  Deep Dive Into Asus PA32U Review  Excellence in Professionalism</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-mastering-the-art-of-screen-sharing-in-zoom-for-2024/"><u>[Updated] Mastering the Art of Screen Sharing in Zoom for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-remote-recording-mastery-a-comprehensive-approach/"><u>[Updated] Remote Recording Mastery  A Comprehensive Approach</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-unpacking-the-power-of-yis-4k-action-capture/"><u>[Updated] Unpacking the Power of Yi's 4K Action Capture</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-the-ultimate-guide-to-media-player-replacements-for-vlc/"><u>2024 Approved  The Ultimate Guide to Media Player Replacements for VLC</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/become-a-persuasive-speaker-in-english-heres-how/"><u>Become a Persuasive Speaker in English – Here's How</u></a></li>
<li><a href="https://techtrends.techidaily.com/cinema-classics-and-hits-to-stream-immediately-as-chosen-by-lifewire/"><u>Cinema Classics & Hits to Stream Immediately, as Chosen by Lifewire</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-removing-x80300024-from-pcs/"><u>Deciphering and Removing X80300024 From PCs</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-the-best-of-win11s-feb-2023-update/"><u>Discovering the Best of Win11's Feb 2023 Update</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-develop-with-wsl-2-core-practices-for-dev-on-windows/"><u>Efficiently Develop with WSL 2: Core Practices for Dev on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-typing-precision-in-windows-11-sidestep-key-lag-pitfalls/"><u>Enhance Typing Precision in Windows 11: Sidestep Key Lag Pitfalls</u></a></li>
<li><a href="https://screen-capture.techidaily.com/enhancing-presence-how-to-effortlessly-eliminate-borders/"><u>Enhancing Presence  How to Effortlessly Eliminate Borders</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-razer-device-compatibility-in-windows-1011/"><u>Enhancing Razer Device Compatibility in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-seamless-spotify-links-on-windows-11-pc/"><u>Ensuring Seamless Spotify Links on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-start-of-programs-despite-qt-platform-missing/"><u>Ensuring Smooth Start of Programs Despite Qt Platform Missing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expert-recommendations-for-8-windows-audio-apps-for-2024/"><u>Expert Recommendations for 8-Windows Audio Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-privilege-access-denial-error-error-0x80070522-on-modern-windows-pcs/"><u>Fixing Privilege Access Denial Error (Error 0X80070522) on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/from-mobile-to-stationary-setting-up-your-android-as-a-windows-webcam/"><u>From Mobile to Stationary: Setting Up Your Android as a Windows Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/full-fledged-quest-mastery-classics-full-hd-and-the-power-of-scummvm-windows/"><u>Full-Fledged Quest Mastery: Classics, Full HD, and the Power of ScummVM Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722978260970-get-your-surface-book-updated-with-new-drivers-today/"><u>Get Your Surface Book Updated with New Drivers Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-started-with-updated-arduino-usb-controllers-for-windows-users/"><u>Getting Started with Updated Arduino USB Controllers for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-common-steam-errors-blocking-game-launch-on-win-11/"><u>How To Solve Common Steam Errors Blocking Game Launch on Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-sony-xperia-1-v-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Sony Xperia 1 V to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-nokia-c300-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Nokia C300 to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maintaining-windows-volume-control-configuration/"><u>Maintaining Windows Volume Control Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/master-control-unscheduling-gpgpu-on-windows-platforms/"><u>Master Control: Unscheduling GPGPU on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-passwords-in-windows-11-with-the-four-best-guardians/"><u>Master Your Passwords in Windows 11 with The Four Best Guardians</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-attributes-on-windows-a-practical-guide/"><u>Mastering File Attributes on Windows: A Practical Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-w11s-startup-process-for-csgo/"><u>Mastering W11's Startup Process for CS:GO</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inadequate-video-ram-issues-in-witchcraft-and-wizardry-simulation/"><u>Mending Inadequate Video RAM Issues in Witchcraft & Wizardry Simulation</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-safe-mode-in-6-steps/"><u>Navigate to Windows 11 Safe Mode in 6 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/nvidias-geforce-error-on-windows-heres-the-fix/"><u>Nvidia's GeForce Error on Windows? Here’s the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/optimized-experience-faster-teams-slimmer-memory-use/"><u>Optimized Experience: Faster Teams, Slimmer Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/pace-up-decoding-your-graphics-spec-in-windows-11/"><u>Pace Up: Decoding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/premium-windows-emulators-for-nintendos-switch-library/"><u>Premium Windows Emulators for Nintendo's Switch Library</u></a></li>
<li><a href="https://win11.techidaily.com/pro-naming-schemes-for-windows-files-max-156/"><u>Pro Naming Schemes for Windows Files (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-microphone-problems-for-smooth-gaming/"><u>Resolving Microphone Problems for Smooth Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11-for-a-retro-windows-98-aesthetic/"><u>Reviving Windows 11 for a Retro Windows 98 Aesthetic</u></a></li>
<li><a href="https://win11.techidaily.com/silencing-windows-graphics-enhancements-from-geforce/"><u>Silencing Windows Graphics Enhancements From GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-tasks-using-ifttt-for-microsoft-to-do/"><u>Simplifying Tasks: Using IFTTT for Microsoft To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/solving-greyed-recycle-icon-problem-in-windows/"><u>Solving Greyed Recycle Icon Problem in Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/tcl-50s425-50-inch-roku-smart-tv-201n-comprehensive-review-and-value-analysis/"><u>TCL 50S425 50-Inch Roku Smart TV (201N) - Comprehensive Review & Value Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/the-conquerors-guide-taking-back-control-over-windows-11-themes/"><u>The Conquerors Guide: Taking Back Control over Windows 11 Themes</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-virtualbox-usb-attachment-failures/"><u>Understanding and Solving VirtualBox USB Attachment Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-update-9-tactics-against-steady-verify-failures/"><u>Unlock Windows Update: 9 Tactics Against Steady Verify Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-fixing-missing-updates-on-windows-os-code-0x80070003/"><u>Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-bsod-log-files-in-microsoft-os/"><u>Unveiling BSOD Log Files in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-11-a-comprehensive-directdraw-troubleshooting-manual/"><u>Win11 & 11: A Comprehensive DirectDraw Troubleshooting Manual</u></a></li>
</ul></div>
