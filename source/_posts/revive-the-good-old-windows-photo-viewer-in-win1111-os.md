---
title: Revive the Good Old Windows Photo Viewer in Win11/11 OS
date: 2024-06-25T11:38:40.325Z
updated: 2024-06-26T11:38:40.325Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revive the Good Old Windows Photo Viewer in Win11/11 OS
excerpt: This Article Describes Revive the Good Old Windows Photo Viewer in Win11/11 OS
keywords: Win11 Photo Viewer,Revive Photo Viewer,Windows Image Viewer,Restore Old Viewing,XP Photo Viewer Revert,NT Photo Tools,OS X Photo Viewer (Assuming a Cross-Reference Relevance for Users Interested in Alternatives to Windows Viewers on Different Operating Systems)
thumbnail: https://thmb.techidaily.com/b0ea6d61080761dc873cfd8c694bea1246e45e087ea28aa28a47640ed6e89f83.jpg
---

## Revive the Good Old Windows Photo Viewer in Win11/11 OS

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
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/solving-windows-11-menu-glitches-a-step-by-step-guide/"><u>Solving Windows 11 Menu Glitches: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-firewall-options-for-blocking-software-to-windows-11s-context-menu/"><u>How to Add Firewall Options for Blocking Software to Windows 11’S Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/curb-the-constant-reopening-of-windows-file-explorer/"><u>Curb the Constant Reopening of Windows' File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/phoenix-rise-revive-gaming-pcs-with-atlasos/"><u>Phoenix Rise: Revive Gaming PCs with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-the-health-of-your-windows-11-setup/"><u>Confirming the Health of Your Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/finding-and-fixing-non-functional-delete-keys-on-windows/"><u>Finding and Fixing Non-Functional Delete Keys on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unlock-the-6th-richest-strategies-for-successful-ig/"><u>Unlock the 6Th Richest Strategies for Successful IG</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-audiblefromtwitvid-direct-audio-conversion/"><u>[Updated] In 2024, AudibleFromTwitVid  Direct Audio Conversion</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-samsung-galaxy-a14-4g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Samsung Galaxy A14 4G to Protect Your Individual Information</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-innovate-your-mobile-photography-with-these-free-overlay-experts/"><u>In 2024, Innovate Your Mobile Photography with These Free Overlay Experts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-navigating-snapchats-video-slowdown-feature/"><u>2024 Approved  Navigating Snapchat's Video Slowdown Feature</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-freeze-time-like-never-before-on-the-newest-mi-phone/"><u>2024 Approved  Freeze Time Like Never Before on the Newest Mi Phone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-dissecting-obs-technology-for-top-level-recording/"><u>[Updated] 2024 Approved  Dissecting OBS Technology for Top-Level Recording</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-funny-noise-finder-a-directory-of-humorous-audio-elements/"><u>In 2024, Funny Noise Finder A Directory of Humorous Audio Elements</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-kitchen-chronicles-filming-every-bite/"><u>In 2024, Kitchen Chronicles  Filming Every Bite</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>