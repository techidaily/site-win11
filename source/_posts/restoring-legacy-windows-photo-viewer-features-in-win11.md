---
title: Restoring Legacy Windows Photo Viewer Features in Win11
date: 2024-07-13T11:03:22.244Z
updated: 2024-07-14T11:03:22.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Legacy Windows Photo Viewer Features in Win11
excerpt: This Article Describes Restoring Legacy Windows Photo Viewer Features in Win11
keywords: Legacy Windows View,Win11 Photo Viewer,Restore Win11 Image,Photo Editor Win11,Classic Window Display,Update Win11 Tools,Enhance Win11 Imagery
thumbnail: https://thmb.techidaily.com/e83f983f9af6b6adf732e263161638d4efc710da8fc4b32e0850fa910996aed9.jpg
---

## Restoring Legacy Windows Photo Viewer Features in Win11

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

### Key Takeaways

* Microsoft replaced the classic Windows Photo Viewer app in Windows 10 and 11 with the new Photos app.
* Fortunately, you can restore Windows Photo Viewer on your Windows computer using a registry hack.
* Additionally, you could try a third-party Windows Photo Viewer alternative like One Photo Viewer, as it offers a clean UI, better performance, and more features.

 Microsoft replaced the classic Photo Viewer app in Windows 10 and 11 with Photos, its modern, feature-rich image viewer. However, if you liked the simplicity of Photo Viewer, here's how you can bring it back in Windows 10 and 11\.

## How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry

 You can enable the classic Windows Photo Viewer app using a Windows Registry script. The following Windows Registry script reconfigures and enables the Windows Photo Viewer app.

 Modifying your Windows Registry involves risk as incorrect modifications can cause your system to malfunction. If you intend to proceed with the steps below, first [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This will help you to recover your system if something goes wrong.

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the Notepad file. This script activates the Windows Photo Viewer.  
`Windows Registry Editor Version 5.00 [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open] "MuiVerb"="@Windowsphotoviewer.dll,-3043" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_Fullscreen %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\DropTarget] "Clsid"="{FFE2A43C-56B9-4bf5-9A79-CC6D4285608A}" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_PrintTo %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\DropTarget] "Clsid"="{60fd46de-f830-4894-a628-6fa81bc0190d}"`  
![Notepad App Showing a Written Registry Script in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-written-registry-script-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog. Alternatively, go to **File > Save As**.
4. In the **Save as** dialog, enter **ActivateWindowsPhotoViewer.reg** as the file name. Click the **Save as** **type** drop-down and choose **All Files(\*.\*)**. Choose a location and **Save** the file to your drive.  
![Notepad App Showing a Save As Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-in-windows-11.png)
5. Next, open **File Explorer**, browse to the location where you saved the file, double-click **ActivateWindowsPhotoViewer.reg**, and then click **Yes**. When a warning prompt appears, click **Yes**.
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00 [-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/separate-onedrive-and-microsoft-accounts-on-desktop-windows/"><u>Separate OneDrive & Microsoft Accounts on Desktop Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-elevating-your-music-collection-advanced-mp3-file-editing-tips-and-tricks/"><u>New In 2024, Elevating Your Music Collection Advanced MP3 File Editing Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-revitalize-retro-computers/"><u>AtlasOS Resurgence: Revitalize Retro Computers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-snapchats-zoom-for-crisp-visuals-for-2024/"><u>Navigating Snapchat's Zoom for Crisp Visuals for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-podcasters-income-streams/"><u>Dissecting Podcasters' Income Streams</u></a></li>
<li><a href="https://win11.techidaily.com/fix-static-speakers-after-disabling-default-sounds/"><u>Fix Static Speakers After Disabling Default Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unite-with-your-absent-astra-pilot-on-windows-11/"><u>Unite With Your Absent Astra Pilot On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-device-integration-using-googles-nearby/"><u>Seamless Device Integration Using Google's Nearby</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-iphoneipad-cutting-edge-free-video-editing-tools-guide/"><u>In 2024, IPhone/iPad  Cutting Edge Free Video Editing Tools Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-interactions-between-devices-and-windows-snooze/"><u>Fine-Tuning Interactions Between Devices and Windows Snooze</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-internal-sound-malfunctions-in-winaudacity-interface/"><u>Pinpointing Internal Sound Malfunctions in WinAudacity Interface</u></a></li>
<li><a href="https://win11.techidaily.com/immerse-in-vividness-adding-life-like-wallpapers-on-windows-11/"><u>Immerse in Vividness: Adding Life-Like Wallpapers on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-tactical-approaches-to-youtube-revenue-with-adsense/"><u>In 2024, Tactical Approaches to YouTube Revenue with AdSense</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-status-check-top-three-techniques/"><u>Windows 11 Status Check: Top Three Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mcuicntexe-entry-point-not-found-error-on-windows/"><u>How to Fix the “McUICnt.exe Entry Point Not Found” Error on Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-innovating-your-fb-experience-with-stunning-video-covers/"><u>2024 Approved  Innovating Your FB Experience with Stunning Video Covers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-the-2024-techniques-for-youtube-to-facebook-synergy/"><u>[New] Unveiling the 2024 Techniques for YouTube to Facebook Synergy</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-partner-selection-for-youtube-joint-ventures/"><u>2024 Approved  Navigating Partner Selection for YouTube Joint Ventures</u></a></li>
<li><a href="https://win11.techidaily.com/curing-a-non-operational-windows-control-panel/"><u>Curing a Non-Operational Windows Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-windows-11-cortana-commands/"><u>Overcoming Unresponsive Windows 11 Cortana Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-restoring-bluetooth-visibility-win/"><u>Steps for Restoring Bluetooth Visibility WIN</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pro-tips-for-effective-youtube-tag-utilization/"><u>In 2024, Pro Tips for Effective YouTube Tag Utilization</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-exploring-filmora-magic-top-10-intriguing-edits/"><u>In 2024, Exploring Filmora Magic  Top 10 Intriguing Edits</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ey-to-wealth-in-web-videos-view-count-imperative-for-2024/"><u>The Key to Wealth in Web Videos  View Count Imperative for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-a-journey-with-the-taskbar-through-time/"><u>Windows UI: A Journey with the Taskbar Through Time</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revolutionizing-audio-liberation-a-deep-dive-into-pazeras-extractor-for-2024/"><u>Revolutionizing Audio Liberation  A Deep Dive Into Pazera's Extractor for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-undetermined-status-messages-on-windows/"><u>Remedying 'Undetermined' Status Messages on Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-effortless-note-management-on-mematic-platform/"><u>2024 Approved  Effortless Note Management on Mematic Platform</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 with a Mask On</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-optimal-templates-for-introducing-panzoids/"><u>In 2024, Optimal Templates for Introducing Panzoids</u></a></li>
<li><a href="https://driver-install.techidaily.com/systematic-guide-to-replace-older-nvidia-installation/"><u>Systematic Guide to Replace Older NVIDIA Installation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-essential-guide-for-adding-depth-and-style-in-instagram-stories-for-2024/"><u>[Updated] The Essential Guide for Adding Depth & Style in Instagram Stories for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/humbnail-wizardry-top-8-tools-to-boost-view-counts/"><u>[New] Thumbnail Wizardry  Top 8 Tools to Boost View Counts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-selective-soundscape-picks-for-video-editors/"><u>In 2024, Selective Soundscape Picks for Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-tips-for-discovering-computer-gpu-make/"><u>Fast-Track Tips for Discovering Computer GPU Make</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-eliminate-auto-change-backgrounds/"><u>Windows 11: Eliminate Auto-Change Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-hidden-notifications-on-desktops/"><u>Recovering Hidden Notifications on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/greatest-non-microsoft-options-easy-screen-captures-without-windows/"><u>Greatest Non-Microsoft Options: Easy Screen Captures Without Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-of-both-worlds-exclusive-11-bridge-camera-guide/"><u>2024 Approved  Best of Both Worlds  Exclusive 11 Bridge Camera Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-troubleshooting-xbox-audio-failures-in-pcs/"><u>Steps for Troubleshooting Xbox Audio Failures in PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-modules-installer-workers-high-cpu-usage/"><u>How to Fix the Windows Modules Installer Worker's High CPU Usage</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-harness-the-power-of-keywords-top-selection-software-unveiled/"><u>[New] Harness the Power of Keywords  Top Selection Software Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-9-indisputable-reasons-to-choose-a-pc-over-a-mac/"><u>Unveiling 9 Indisputable Reasons to Choose a PC Over a Mac</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-your-design-how-to-eliminate-backgrounds-in-figma/"><u>[New] Unveiling Your Design  How To Eliminate Backgrounds in Figma</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-the-screen-savers-strategy-top-recording-tactics/"><u>[Updated] In 2024, The Screen Saver's Strategy  Top Recording Tactics</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/insiders-take-top-9-digital-mic-recorder-selections/"><u>Insider's Take  Top 9 Digital Mic Recorder Selections</u></a></li>
<li><a href="https://video-capture.techidaily.com/diy-techniques-transforming-smartphones-into-webcams-for-2024/"><u>DIY Techniques  Transforming Smartphones Into Webcams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-of-windows-11-is-ai-whether-you-like-it-or-not/"><u>The Future of Windows 11 Is AI, Whether You Like It or Not</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-xiaomi-redmi-note-12-pro-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Xiaomi Redmi Note 12 Pro 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/setting-specific-windows-lockdown-period/"><u>Setting Specific Windows Lockdown Period</u></a></li>
<li><a href="https://win11.techidaily.com/silent-storage-strategies-for-stealthy-windows-users/"><u>Silent Storage Strategies for Stealthy Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-speedy-utorrent-in-windows/"><u>Winning Strategies: Speedy uTorrent in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-transform-your-fb-advertising-simplify-with-a-free-toolkit-for-2024/"><u>[New] Transform Your FB Advertising  Simplify with a Free Toolkit for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-free-business-visual-aids-to-enhance-your-meetings/"><u>[Updated] 2024 Approved  Free Business Visual Aids to Enhance Your Meetings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-infinix-zero-5g-2023-turbo-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Infinix Zero 5G 2023 Turbo</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-ultimate-audio-enhancer-eliminate-unwanted-soundtracks-for-2024/"><u>New Ultimate Audio Enhancer Eliminate Unwanted Soundtracks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-analysis-underutilized-windows-system-health-metrics/"><u>A Dual Analysis: Underutilized Windows System Health Metrics</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-breaking-barriers-next-level-strategies-for-fb-video-success/"><u>[New] 2024 Approved  Breaking Barriers  Next-Level Strategies for FB Video Success</u></a></li>
<li><a href="https://win11.techidaily.com/expert-windows-11-weather-app-reviews/"><u>Expert Windows 11 Weather App Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/explore-5-innovative-windows-folder-strategies/"><u>Explore 5 Innovative Windows Folder Strategies</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-6-economical-projector-brands-for-4k/"><u>2024 Approved  Ideal 6 Economical Projector Brands for 4K</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-supercharge-video-memory-on-windows-devices/"><u>Tips to Supercharge Video Memory on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-spirit-of-victory-a-steam-achievements-reset/"><u>Reviving the Spirit of Victory: A Steam Achievements Reset</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-ultimate-guide-to-youtubes-best-music-responses/"><u>[Updated] In 2024, The Ultimate Guide to YouTube's Best Music Responses</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-immediate-failure-how-to-successfully-add-a-folder-in-onedrive-on-pc/"><u>Tackling Immediate Failure: How to Successfully Add a Folder in OneDrive on PC</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-home-movie-mastery-ezvid-for-mac-makes-video-creation-a-breeze/"><u>In 2024, Home Movie Mastery Ezvid for Mac Makes Video Creation a Breeze</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-vmware-errors-on-windows-11/"><u>How to Reset VMware Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-driver-loading-issues-in-the-latest-os/"><u>Overcoming Failed Driver Loading Issues in the Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-unlinking-saved-wi-fi/"><u>Win 11: Unlinking Saved Wi-Fi</u></a></li>
</ul></div>
