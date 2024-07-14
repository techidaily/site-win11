---
title: "Windows 11: Guide to Security-Focused Dialogue Shortcuts"
date: 2024-07-13T09:44:47.924Z
updated: 2024-07-14T09:44:47.924Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Guide to Security-Focused Dialogue Shortcuts"
excerpt: "This Article Describes Windows 11: Guide to Security-Focused Dialogue Shortcuts"
keywords: Windows 11 Secure Keyboard,W11 Safety Shortcuts,Protecting PC with W11,Security in W11 Shortcuts,W11 Safe Function Keys,Enhancing W11 Safety,W11 Secure Commands Guide
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## Windows 11: Guide to Security-Focused Dialogue Shortcuts

 After inserting an external USB flash drive, you can select an option on Windows 11’s system tray to eject it. The eject option is available to enable users to remove external storage devices safely. Data can get corrupted if you remove a USB drive still in use.

 The Safely Remove Hardware dialog is a window that displays all connected USB devices and enables you to stop them for safe ejection. That dialog is accessible with a Run command, but you can set up shortcuts for opening it with the methods below.

## How to Set Up a "Safely Remove Hardware" Desktop Shortcut

 The Safely Remove Hardware dialog has a long Run command that’s not easy to remember. To make that feature more directly accessible, you can create a desktop shortcut based on its command. Then you can also turn that shortcut into a taskbar, Start menu, or keyboard one. This is how to set up a Safely Remove Hardware dialog desktop shortcut in Windows 11:

1. Click anywhere on the desktop wallpaper with the mouse’s right button to select**New** and**Shortcut** .  
![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)
2. Input this command within the location box:  
`rundll32.exe shell32.dll,Control_RunDLL hotplug.dll`
3. Select**Next** to view the shortcut name box.
4. Delete the text in the box, and input**Safely Remove Hardware** to replace it.
5. Click**Finish** to add the Safely Remove Hardware desktop shortcut.

 Now try opening the Safely Remove Hardware window with the shortcut. Double-clicking the**Safely Remove Hardware** shortcut should open the window shown directly below. Select a listed USB device you want to remove there and click**Stop** . Clicking that button opens a**Stop** hardware device window on which you can select to stop a device before removing it.

![The Safely Remove Hardware dialog window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-devices-window.jpg)

 That**Stop** option is not entirely the same as an ejection one. Selecting**Eject Portable** in the system tray will merely tell you if the device is still in use or safe to remove. Clicking**Stop** will stop what’s using the drive to make the device free for removal.

![The Eject Portable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/eject-portable-option.jpg)

 The Safely Remove Hardware window also enables you to view properties for listed devices. To do so, select a device and click the**Properties** button. That will bring up a window that includes general, event, and driver details for the device.

 The Safely Remove Hardware desktop shortcut will be blank by default. However, you can add an icon to it by following the instructions in our [guide for customizing Windows 11/10 icons](https://www.makeuseof.com/tag/customize-icon-windows/) .

## How to Set Up "Safely Remove Hardware" Taskbar and Start Menu Shortcuts

 Setting up a Safely Remove Hardware desktop shortcut will enable you to pin it to the taskbar or Start menu. To do so, right-click the Safely Remove Hardware icon on the desktop and select**Show more options** . The classic context menu in Windows 11 includes**Pin to taskbar** and**Pin to Start** menu options. So, select one of those options to create an alternative Safely Remove Hardware taskbar or Start menu shortcut.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pin-to-taskbar-option.jpg)

 Adding Safely Remove Hardware to the taskbar or Start menu will make its desktop shortcut redundant. You can remove that desktop shortcut by right-clicking its icon and selecting**Delete** (the trash can icon).

## How to Set Up a "Safely Remove Hardware" Hotkey

 There’s no quicker way to open anything in Windows 11 than pressing a hotkey. A keyboard shortcut enables you to open anything without having to minimize windows to reach the desktop, bring up the Start menu, or move the mouse at all. You can set up a hotkey that opens the Safely Remove Hardware dialog as instructed for method one in our [how to assign keyboard shortcuts to programs on Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) guide.

![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/shortcut-key-box.jpg)

 Creating such a hotkey doesn’t make the Safely Remove Hardware desktop shortcut redundant. The hotkey activates the desktop shortcut you assigned it to. So, erasing the Safely Remove Hardware desktop shortcut will delete the shortcut key.

## How to a Set Up a "Safely Remove Hardware" Context Menu Shortcut

 The context menu is an out-of-the-way place to stick shortcuts for opening things. Adding a Safely Remove Hardware option there will enable you to access that dialog by right-clicking the desktop area. Such a shortcut will probably be preferable for users who prefer to minimize desktop and taskbar clutter.

 However, this final method for creating a Safely Remove Hardware shortcut involves editing the registry because Windows 11 doesn’t include any editing feature for customizing the context menu. The registry tweak is a relatively straightforward one to apply that adds a couple of new keys. Follow these steps exactly as specified to add a**Safely Remove Hardware** option to the context menu:

1. Press**Start** (the taskbar menu button) and click inside the search box.
2. Enter**Registry Editor** inside the file search tool and select to open that app from the results.
3. Delete whatever text is in Registry Editor’s address bar, and input this key location there:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Then right-click the Shell key and select**New** to bring up a context menu submenu.
5. Select the**Key** option to add a new registry entry.

1. Type**Safely Remove Hardware** inside the key’s text box.
2. Then right-click the newly added**Safely Remove Hardware** registry entry and select the**New** \>**Key** options.
3. Input**command** to be the second key’s title.
4. Select the newly added**command** registry entry and double-click its**(Default)** string value.
5. Then input the following Safely Remove Hardware dialog location inside the**Data value** box:  
`C:\\Windows\\System32\\control.exe hotplug.dll`
6. Click**OK** to confirm the new value.

 Now you can have a look at what you’ve just added to Windows 11’s context menu. Right-click an empty part of your desktop area to select Show more options, which opens the secondary classic menu. Select the**Safely Remove Hardware** option on the classic context menu to bring up that window.

![The Safely Remove Hardware context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/safely-remove-hardware-option.jpg)

 That option can be easily removed from the context menu if you decide not to keep it there. To remove it, return to the registry key specified in step three above; right-click the**Safely Remove Hardware** key you added and select**Delete** . Then select**Yes** to delete the key.

## Utilize the Safely Remove Hardware Dialog Faster on Windows

 Creating a Safely Remove Hardware shortcut with any method above will make that dialog window more accessible whenever you need to remove a device. That dialog provides a handy alternative way for users to safely remove USB drives with additional options for viewing device details. You can use that dialog to view properties for connected drives and select to stop them so they can be removed without corrupting data.

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
<li><a href="https://win11.techidaily.com/windows-11-quick-guide-to-open-sticky-notes/"><u>Windows 11: Quick Guide to Open Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/craft-command-capabilities-for-the-windowed-world/"><u>Craft Command Capabilities for the Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-users-a-comprehensive-guide-to-windows-tweaks-via-alomware/"><u>Empowering Users: A Comprehensive Guide to Windows Tweaks via AlomWare</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-incorporate-google-maps-into-windows/"><u>Effortlessly Incorporate Google Maps Into Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/quick-start-guide-to-setup-and-use-obs-on-apple-systems-for-2024/"><u>Quick Start Guide to Setup and Use OBS on Apple Systems for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-tutorial-on-3d-lut-tools/"><u>[New] Ultimate Tutorial on 3D LUT Tools</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-system-failures-code-0xc0000001/"><u>Eradicating System Failures: Code 0xC0000001</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-speed-up-and-slow-down-a-video-for-2024/"><u>How to Speed Up and Slow Down a Video for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/right-moves-to-use-tts-in-descript-for-2024/"><u>Right Moves to Use TTS in Descript for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-tips-for-youtube-channel-aesthetics-finding-optimal-sizes-for-2024/"><u>[Updated] Expert Tips for YouTube Channel Aesthetics  Finding Optimal Sizes for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-debut-video-capture-review-and-alternative-for-2024/"><u>[Updated] Debut Video Capture Review and Alternative for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-ultimate-screen-capture-review-obs-vs-fraps/"><u>[New] In 2024, Ultimate Screen Capture Review  OBS vs Fraps</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-faulty-windows-update-error/"><u>Correcting Faulty Windows Update Error</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-lut-application-in-adobe-premiere/"><u>2024 Approved  Navigating LUT Application in Adobe Premiere</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-hurdles-of-error-0x80040610-a-comprehensive-approach/"><u>Eliminating the Hurdles of Error 0X80040610: A Comprehensive Approach</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-gaming-upgrade-guide-top-tips-for-a-seamless-experience/"><u>Win 11 Gaming Upgrade Guide: Top Tips for a Seamless Experience</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-how-to-use-audacity-for-podcasts/"><u>New 2024 Approved How to Use Audacity for Podcasts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nail-length-a-guide-to-captivating-audiences-for-2024/"><u>Thumbnail Length  A Guide to Captivating Audiences for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-triumph-over-triviality-amass-a-million-ish-followers-on-ig/"><u>[Updated] Triumph Over Triviality  Amass a Million-Ish Followers on IG</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-elevating-your-cinematic-experience-strategies-for-using-suspenseful-music-in-film-scoring/"><u>Updated Elevating Your Cinematic Experience Strategies for Using Suspenseful Music in Film Scoring</u></a></li>
<li><a href="https://win11.techidaily.com/from-minuscule-to-monumental-boosting-windows-11-icon-sizes/"><u>From Minuscule to Monumental - Boosting Windows 11 Icon Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/excel-in-windows-top-5-productivity-enhancers-you-cant-miss/"><u>Excel in Windows: Top 5 Productivity Enhancers You Can't Miss</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-expert-advice-for-achieving-larger-head-effects-in-tiktok-vfx/"><u>[New] In 2024, Expert Advice for Achieving Larger Head Effects in TikTok VFX</u></a></li>
<li><a href="https://win11.techidaily.com/master-system-configurations-optimizing-usage-options/"><u>Master System Configurations: Optimizing Usage Options</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-merging-made-easy-the-top-5-free-online-video-combination-tools/"><u>New Merging Made Easy The Top 5 Free Online Video Combination Tools</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-the-health-of-your-windows-11-setup/"><u>Confirming the Health of Your Windows 11 Setup</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-understanding-youtubes-content-crafting-environment/"><u>[Updated] Understanding YouTube's Content Crafting Environment</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-windows-music-managers-for-2024/"><u>Best Windows Music Managers for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ntle-bots-elevate-youtube-watch-time-for-2024/"><u>Dismantle Bots, Elevate YouTube Watch Time for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-curse-of-wow-error-132-a-step-by-step-approach/"><u>Beating the Curse of WoW Error #132: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-offline-windows-update-plan/"><u>Crafting an Offline Windows Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience/"><u>7 Proven Methods to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlocking-visual-potential-the-9-best-mobile-accessories-for-vloggers/"><u>Unlocking Visual Potential  The 9 Best Mobile Accessories for Vloggers</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-dll-loss-restoring-mfc71u-on-pcs/"><u>Addressing Critical DLL Loss: Restoring Mfc71u on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/get-icloud-running-without-glitches-on-your-windows-device/"><u>Get iCloud Running Without Glitches on Your Window's Device</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-mouse-pointer-prominence-in-windows-11/"><u>Enhancing Mouse Pointer Prominence in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-windows-task-management-addressing-misplaced-cpu-metrics/"><u>Fixes for Windows Task Management: Addressing Misplaced CPU Metrics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/how-to-add-filters-and-music-on-windows-10-photos-app-for-2024/"><u>How to Add Filters and Music on Windows 10 Photos App for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-y78plus-t1-edition-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-win-10s-internet-safety-mechanism/"><u>How to Set Win 10’S Internet Safety Mechanism</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-digital-sound-shaping-at-no-charge-the-best-free-online-trimming-experience/"><u>Updated In 2024, Digital Sound Shaping at No Charge The Best Free Online Trimming Experience</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-exclusive-list-of-the-top-5-integrated-car-audio-editors-for-mac-users/"><u>Updated 2024 Approved Exclusive List of the Top 5 Integrated Car Audio Editors for Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/banish-unfulfilled-system-criteria-marking-on-win11/"><u>Banish Unfulfilled System Criteria Marking on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-non-functionality-in-windows-10/"><u>Fixing Grammarly Non-Functionality in Windows 10</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-rhythm-and-reel-leveraging-premiere-pro-features-for-time-synchronized-video-editing/"><u>New 2024 Approved Rhythm and Reel Leveraging Premiere Pro Features for Time-Synchronized Video Editing</u></a></li>
</ul></div>
