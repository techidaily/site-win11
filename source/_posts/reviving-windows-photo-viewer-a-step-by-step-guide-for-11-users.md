---
title: "Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users"
date: 2024-07-13T10:51:45.956Z
updated: 2024-07-14T10:51:45.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users"
excerpt: "This Article Describes Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users"
keywords: WinXP PhotoViewer Revival,Reinstalling WavePhoto,Photo Viewer Repair Steps,Windows 10 PhotoViewer Guide,Restoring PhotoApp Functions,XP PhotosView FIX Guide,PhotoViewer Troubleshooting Tips
thumbnail: https://thmb.techidaily.com/02545b46a0f89851cd200be4f89aa4a5cf07cac669a6cce1f1cfbd0428355e0a.jpg
---

## Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users

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
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-lsa-error-on-windows-systems/"><u>Fixing LSA Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-motorola-edge-40-neo-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Motorola Edge 40 Neo Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-itel-p55-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Itel P55 Device</u></a></li>
<li><a href="https://win11.techidaily.com/graphics-correction-step-by-step-windows-11/"><u>Graphics Correction: Step-by-Step Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstructions-a-guide-to-windows-11s-search-problems/"><u>Clearing Obstructions: A Guide to Windows 11'S Search Problems</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-subtitle-your-videos-for-free-top-10-online-makers/"><u>Updated Subtitle Your Videos for Free Top 10 Online Makers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-bio-link-addition-on-tiktok/"><u>Mastering Bio Link Addition on TikTok</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-jest-journeys-charting-7-comedic-paths-to-viral-videos/"><u>In 2024, Jest Journeys  Charting 7 Comedic Paths to Viral Videos</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-insiders-guide-to-authentic-instagram-imagery/"><u>In 2024, The Insider’s Guide to Authentic Instagram Imagery</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-7-best-video-joiners-with-no-watermark-or-logo-for-2024/"><u>New 7 Best Video Joiners with No Watermark or Logo for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-premier-discord-font-makers-seamless-online-and-portable-use/"><u>In 2024, Premier Discord Font Makers - Seamless Online & Portable Use</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-youtube-name-makers-plus-creative-idea-sparking-techniques-for-2024/"><u>Top YouTube Name Makers + Creative Idea Sparking Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/visionary-views-our-countdown-of-the-top-10-camera-lenses-2024/"><u>Visionary Views  Our Countdown of the Top 10 Camera Lenses 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-xiaomi-redmi-note-12-pro-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Xiaomi Redmi Note 12 Pro 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-unveiling-the-leaders-free-top-6-youtube-snackers/"><u>In 2024, Unveiling the Leaders  Free Top 6 YouTube Snackers</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-add-folder-not-possible-issue-with-windows-onedrive/"><u>Combatting 'Add Folder Not Possible' Issue with Windows OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-user-experience-tailoring-windows-via-alomware-applications/"><u>Elevate User Experience: Tailoring Windows via AlomWare Applications</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/top-7-strategies-for-capturing-sound-on-your-chromebook-for-2024/"><u>Top 7 Strategies for Capturing Sound on Your Chromebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-reverting-customized-windows-configurations/"><u>Effective Methods: Reverting Customized Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-personalized-taskbar-in-w11-windows/"><u>Crafting a Personalized Taskbar in W11 Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/facing-the-falls-top-action-cameras-2023-for-2024/"><u>Facing the Falls  Top Action Cameras 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-infinix-note-30-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Infinix Note 30</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-nokia-c02-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Nokia C02 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-senior-accessibility-on-legacy-computers/"><u>Enhancing Senior Accessibility on Legacy Computers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-spots-unveiling-stunning-no-cost-tiktok-backgrounds/"><u>[New] Top Spots  Unveiling Stunning, No-Cost TikTok Backgrounds</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-discovering-an-original-tiktok-identifier-code/"><u>2024 Approved  Discovering an Original TikTok Identifier Code</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-sudden-invisibility-issues-in-pc-gaming/"><u>Eradicating Sudden Invisibility Issues in PC Gaming</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-make-a-video-a-live-photo-2023-for-2024/"><u>How to Make a Video a Live Photo 2023 for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-enhance-engagement-sharing-videos-on-instagram/"><u>[New] Enhance Engagement  Sharing Videos on Instagram</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-unlocking-cinematic-storytelling-how-to-apply-ken-burns-effect-in-final-cut-pro/"><u>In 2024, Unlocking Cinematic Storytelling How to Apply Ken Burns Effect in Final Cut Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-redmi-note-12-proplus-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi Redmi Note 12 Pro+ 5G Through Google Earth?</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-in-windows-11-os/"><u>Ensuring a Valid Temp Directory in Windows 11 OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-instagram-maximizing-post-engagement/"><u>[New] 2024 Approved  Mastering Instagram  Maximizing Post Engagement</u></a></li>
<li><a href="https://techidaily.com/hard-reset-vivo-y100t-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Vivo Y100t in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-experts-to-follow-on-igtv/"><u>[Updated] In 2024, Experts to Follow on IGTV</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlock-srt-mastery-a-detailed-manual-and-tips/"><u>[Updated] Unlock SRT Mastery  A Detailed Manual and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-a-parallels-driven-path-for-windows-11-installation/"><u>Embark on a Parallels-Driven Path for Windows 11 Installation</u></a></li>
</ul></div>
