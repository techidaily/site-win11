---
title: Steps to Reactivate Windows Photo Viewer on Windows 11
date: 2024-12-04T17:50:30.246Z
updated: 2024-12-06T16:46:09.384Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reactivate Windows Photo Viewer on Windows 11
excerpt: This Article Describes Steps to Reactivate Windows Photo Viewer on Windows 11
keywords: WinXPViewerReactivation,PhotoViewerWin11Reboot,ReinstallPhotoViewerWin,ReviveWindowsPhotoview,WindowsPhotosWatcherFix,RestorePhotoViewWin,EnableWindowsPhotoScreen
thumbnail: https://thmb.techidaily.com/31e3ae8455d50c80842cdc2a354e8096f8d646d3db5eda647c388c8800cd490f.jpg
---

## Steps to Reactivate Windows Photo Viewer on Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://twitter-videos.techidaily.com/new-twitvid-mastery-your-go-to-resource-for-video-downloads/"><u>[New] TwitVid Mastery Your Go-To Resource for Video Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-and-contrasting-google-and-microsofts-nearby-file-services/"><u>Comparing and Contrasting Google & Microsoft's Nearby File Services</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-ustreams-features-and-rivals/"><u>Dissecting Ustream's Features and Rivals</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fresh-install-of-amd-graphics-software-on-windows-os-versions-10-11-and-7/"><u>Fresh Install of AMD Graphics Software on Windows OS Versions: 10, 11, and 7</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-novice-to-expert-kinemaster-gs-journey/"><u>From Novice to Expert KineMaster GS Journey</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-max-passcode-without-computer-by-drfone-ios/"><u>How to Unlock Apple iPhone 11 Pro Max Passcode without Computer?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-industrys-heavyweight-champions-drones-of-the-year/"><u>In 2024, Industry's Heavyweight Champions - Drones of the Year</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-livestreaming-tools-evaluation-which-bets-on-performance/"><u>In 2024, Livestreaming Tools Evaluation Which Bets on Performance?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-silent-learners-guide-to-bypassing-edgenuity-videos-effortlessly/"><u>In 2024, The Silent Learner's Guide to Bypassing Edgenuity Videos Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-storing-custom-sound-levels-effectively/"><u>Methods for Storing Custom Sound Levels Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-nuances-of-window-11-widget-installation/"><u>Navigating Through the Nuances of Window 11 Widget Installation</u></a></li>
<li><a href="https://win11.techidaily.com/secret-scrolls-of-system-files-unveil-the-steps/"><u>Secret Scrolls of System Files: Unveil the Steps</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-journey-to-w11s-printer-tools-max-50-chars/"><u>Streamline Your Journey to W11’s Printer Tools (Max 50 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/swift-sanitization-of-accounts-easy-ways-to-disable-users-on-win11/"><u>Swift Sanitization of Accounts: Easy Ways to Disable Users on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-pinnacle-of-progress-windows-beyond-11/"><u>The Pinnacle of Progress: Windows Beyond 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-for-incomplete-amd-ryzen-master-installation/"><u>Troubleshooting Steps for Incomplete AMD Ryzen Master Installation</u></a></li>
</ul></div>

