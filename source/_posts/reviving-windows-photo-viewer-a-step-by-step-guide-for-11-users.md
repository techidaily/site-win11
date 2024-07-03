---
title: "Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users"
date: 2024-06-25T11:40:57.326Z
updated: 2024-06-26T11:40:57.326Z
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
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-to-your-favorite-ms-store-games-and-tools/"><u>Regaining Access to Your Favorite MS Store Games & Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-streaming-on-windows-counteracting-zero-speed-phenomenon/"><u>Optimize Streaming on Windows: Counteracting Zero-Speed Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-multiple-computers-to-one-printer-seamlessly/"><u>Syncing Multiple Computers to One Printer Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-reboot-file-explorer-on-win1011/"><u>Methods to Reboot File Explorer on Win10/11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-top-10plus-instagram-content-downloaders-reviewed/"><u>[New] 2024 Approved  Top 10+ Instagram Content Downloaders Reviewed</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-narzo-60x-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme Narzo 60x 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-collective-echo-boom-impact-for-2024/"><u>Updated Collective Echo Boom Impact for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snap-tales-with-flair-unearth-over-120-ingenious-titles-for-your-unique-snapchat-chronicles-for-2024/"><u>[New] Snap Tales with Flair  Unearth over 120 Ingenious Titles for Your Unique Snapchat Chronicles for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-the-definitive-list-of-popular-software-for-auditory-disentanglement-from-video-footage/"><u>2024 Approved The Definitive List of Popular Software for Auditory Disentanglement From Video Footage</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-export-video-in-filmora/"><u>How To Export Video in Filmora</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-reset-the-scene-fixing-your-facebook-for-2024/"><u>[New] Reset the Scene  Fixing Your Facebook for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-hush-zoom-muting-your-devices-voice-output-made-simple-with-our-tips-and-tricks/"><u>2024 Approved Hush, Zoom! Muting Your Devices Voice Output Made Simple with Our Tips & Tricks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Oppo A1x 5G? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>