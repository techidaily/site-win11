---
title: How to Bring Back Photo Viewer in Modern Windows 11/11
date: 2024-12-01T09:38:07.712Z
updated: 2024-12-06T20:14:47.536Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Bring Back Photo Viewer in Modern Windows 11/11
excerpt: This Article Describes How to Bring Back Photo Viewer in Modern Windows 11/11
keywords: WinViewPhotoRestore,WindowsPhotosViewer,RestartWindowsForImages,FixWindowsImageViewer,EnableWinPhotoView,PhotoViewerReviveWin,ImageViewerEnableW11
thumbnail: https://thmb.techidaily.com/ae200a2185b5d6e93408c97ace7b66b8254fa867626e84f986d0cc30e800ea8d.jpg
---

## How to Bring Back Photo Viewer in Modern Windows 11/11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-mastering-video-capturing-step-by-step-manual/"><u>[New] 2024 Approved Mastering Video Capturing Step-by-Step Manual</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-smart-strategies-for-itunes-video-logging-for-2024/"><u>[New] The Smart Strategies for iTunes Video Logging for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-bite-sized-tips-for-aspiring-video-editors/"><u>[Updated] In 2024, Bite-Sized Tips for Aspiring Video Editors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y78-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y78 5G</u></a></li>
<li><a href="https://win11.techidaily.com/defenders-data-dilemma-how-to-clean-windows-systems/"><u>Defender’s Data Dilemma: How to Clean Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-network-connectivity-addressing-prompt-incompleteness-in-windows/"><u>Enhancing Network Connectivity: Addressing Prompt Incompleteness in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-methods-to-refresh-file-explorer-in-windows-11/"><u>Essential Methods to Refresh File Explorer in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-realme-c67-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Realme C67 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-staying-relevant-essential-instagram-hashtags-for-success/"><u>In 2024, Staying Relevant Essential Instagram Hashtags for Success</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-frozen-service-control-panel-through-these-7-essential-fixes/"><u>Reviving a Frozen Service Control Panel Through These 7 Essential Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-removal-of-security-logs-in-win-1111/"><u>Simplifying the Removal of Security Logs in Win 11/11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solving-the-launch-problem-in-simcity-buildit-sequel-a-comprehensive-guide/"><u>Solving the Launch Problem in SimCity BuildIt Sequel - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-ps1-experience-with-duckstation-and-windows/"><u>Transform Your PS1 Experience with Duckstation and Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    