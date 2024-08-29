---
title: How to Restore Windows Photo Viewer in Windows 10/11
date: 2024-08-28T00:52:51.074Z
updated: 2024-08-29T00:52:51.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Restore Windows Photo Viewer in Windows 10/11
excerpt: This Article Describes How to Restore Windows Photo Viewer in Windows 10/11
keywords: WinPhotosViewerRestore,WIndowsPhotoviewerUpdate,WindowsPhotoViewerRepair,PhotoViewerWin10Fix,ViewerPhotoWindows10,RestorePhotoViewWin10,FixPhotoViewerWin11
thumbnail: https://thmb.techidaily.com/43a1f72d8140b4852b3ec1b168bf1a5fdf9e93b16a9fa8da6c72d7e20d694e32.jpg
---

## How to Restore Windows Photo Viewer in Windows 10/11

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
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-embrace-the-season-ideal-winter-backgrounds-for-yt-for-2024/"><u>[Updated] Embrace the Season  Ideal Winter Backgrounds for YT for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-7-crucial-tiktok-utilities-for-enhanced-viral-progress/"><u>[Updated] In 2024, 7 Crucial TikTok Utilities for Enhanced Viral Progress</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-poco-x6-pro-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-humor-capabilities-explored-plus-a-fascinating-look-at-laptops-throughout-history-and-how-vpns-are-leveling-up/"><u>AI Humor Capabilities Explored: Plus, a Fascinating Look at Laptops Throughout History & How VPNs Are Leveling Up</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-kali-a-windows-users-guide/"><u>Dive Into Kali: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-qt-platform-support-from-app-launch-errors/"><u>Eliminating 'No Qt Platform Support' From App Launch Errors</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-flicker-in-windows-os-a-step-by-step-guide/"><u>Eliminating Flicker in Windows OS: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-fullscreen-experience-tackling-windows-overscan/"><u>Enhance Fullscreen Experience: Tackling Windows Overscan</u></a></li>
<li><a href="https://techtrends.techidaily.com/get-free-access-to-roku-channels-without-owning-a-set-top-device/"><u>Get Free Access to Roku Channels Without Owning a Set-Top Device</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-ctrl-key-malfunction-fixes-on-win11/"><u>Guiding You Through Ctrl Key Malfunction Fixes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-do-not-have-access-error-during-uninstall-on-windows-11/"><u>How to Overcome Do Not Have Access Error During Uninstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-xbox-game-update-issues-on-pc/"><u>How to Solve Xbox Game Update Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-windows-update-interruptions/"><u>How to Turn Off Windows Update Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-wirelessly-connect-a-ps3-dualshock-controller-to-windows/"><u>How to Wirelessly Connect a PS3 DualShock Controller to Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-vivo-v29-pro-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Vivo V29 Pro to Roku | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-precision-in-every-frame-top-9-tips-for-vr-filmmaking/"><u>In 2024, Precision in Every Frame  Top 9 Tips for VR Filmmaking</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-techniques-for-clearing-ms-defender-log-on-pc/"><u>Master the Techniques for Clearing MS Defender Log on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-no-permission-error-on-windows-explorer/"><u>Mastering the 'No Permission' Error on Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/mend-resolving-keyboard-issues-on-windows-11/"><u>Mend: Resolving Keyboard Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/off-the-cuff-tricks-to-work-with-onedrive-locally/"><u>Off-the-Cuff Tricks to Work with OneDrive Locally</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-multiscreen-woes-in-windows/"><u>Overcoming Multiscreen Woes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-adding-dolby-atmos-in-win-11-pro/"><u>Quick Steps for Adding Dolby Atmos in Win 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/rethinking-user-authorization-on-windows-systems/"><u>Rethinking User Authorization on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice!</u></a></li>
<li><a href="https://win11.techidaily.com/slash-cpu-usage-spikes-utilizing-windows-rm-wisdom/"><u>Slash CPU Usage Spikes: Utilizing Window's RM Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-autonomous-opens-in-microsoft-marketplace/"><u>Stopping Autonomous Opens in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-data-with-tips-max-156/"><u>Streamline Your Windows Data with Tips (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-app-screens-on-windows-11-properly/"><u>Tailoring App Screens on Windows 11 Properly</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-oneplus-nord-ce-3-lite-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to OnePlus Nord CE 3 Lite 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-joining-onedrive-with-liveid-windows/"><u>The Ultimate Guide: Joining OneDrive with LiveID (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-potential-of-windows-11s-package-control-using-wingetui/"><u>Unleash the Potential of Windows 11'S Package Control Using WingetUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diablo-secrets-basic-techniques/"><u>Unlocking Diablo Secrets: Basic Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-filefolder-secrets-6-property-steps-in-windows/"><u>Unlocking File/Folder Secrets: 6 Property Steps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/uphold-your-online-experience-windows-connection-audit/"><u>Uphold Your Online Experience: Windows Connection Audit</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/vs-gopro-hero-session-and-polaroid-cube-top-pick-for-filmmakers/"><u>Vs. GoPro Hero Session & Polaroid Cube  Top Pick for Filmmakers</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-typing-lag-seven-effective-fixes-for-win-os/"><u>Win over Typing Lag: Seven Effective Fixes for WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-trick-showhide-user-defined-directories/"><u>Windows 11 Trick: Show/Hide User-Defined Directories</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>