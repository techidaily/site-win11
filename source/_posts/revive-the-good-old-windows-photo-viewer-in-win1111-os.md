---
title: Revive the Good Old Windows Photo Viewer in Win11/11 OS
date: 2024-08-15T23:52:50.814Z
updated: 2024-08-16T23:52:50.814Z
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
5. Next, open **File Explorer**, browse to the location where you saved the file, double-click **ActivateWindowsPhotoViewer.reg**, and then click **Yes**. When a warning prompt appears, click **Yes**.
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00 [-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-discover-the-top-30-free-intro-creators-on-youtube/"><u>[New] 2024 Approved  Discover the Top 30 Free Intro Creators on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-silencing-ambient-sound-in-recordings-free-or-paid-guide/"><u>[New] 2024 Approved  Silencing Ambient Sound in Recordings  Free or Paid Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-compile-presentation-asset-to-video-for-2024/"><u>[New] Compile Presentation Asset to Video for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-elevate-your-ppt-game-with-clear-concise-voiceover-techniques/"><u>[New] Elevate Your PPT Game with Clear, Concise Voiceover Techniques</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-examining-audio-and-visual-content-podcasts-against-youtube/"><u>[New] Examining Audio and Visual Content  Podcasts Against YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-complete-breakdown-of-game-capture-in-overwatch-for-2024/"><u>[New] The Complete Breakdown of Game Capture in Overwatch for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-thorough-review-easy-approach-to-hdr-enhancement/"><u>[New] Thorough Review  Easy Approach to HDR Enhancement</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-dual-display-dynamics-video-recorder-rankings/"><u>[Updated] 2024 Approved  Dual Display Dynamics  Video Recorder Rankings</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-modify-twitter-video-capture-image/"><u>[Updated] 2024 Approved  Modify Twitter Video Capture Image</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-moments-of-quietude-top-idle-smartphone-games/"><u>[Updated] In 2024, Moments of Quietude  Top Idle Smartphone Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-ultimate-guide-to-finding-instagram-filters-for-no-cost-for-2024/"><u>[Updated] The Ultimate Guide to Finding Instagram Filters for No Cost for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/11-things-to-consider-before-deleting-your-social-media-accounts/"><u>11 Things to Consider Before Deleting Your Social Media Accounts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-verbal-to-written-an-intensive-guide-to-google-document-voice-functionality/"><u>2024 Approved  From Verbal to Written  An Intensive Guide to Google Document Voice Functionality</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-stream-mastery-on-mac-with-these-5-tools/"><u>2024 Approved  Stream Mastery on Mac with These 5 Tools</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cosmic-comforts-top-10-starry-night-accessories-for-sj4000/"><u>Cosmic Comforts  Top 10 Starry Night Accessories for SJ4000</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-unforeseen-security-issues-in-win10win11/"><u>Counteracting Unforeseen Security Issues in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-marketplace-failures-error-0x80073cf3/"><u>Deciphering and Resolving Windows Marketplace Failures (Error 0X80073CF3)</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-11-the-intricacies-of-its-file-system/"><u>Demystifying Windows 11: The Intricacies of Its File System</u></a></li>
<li><a href="https://win11.techidaily.com/does-file-explorer-keep-crashing-on-windows-11-try-these-fixes/"><u>Does File Explorer Keep Crashing on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-screen-recording-with-audio-in-the-latest-snipping-tool-update-max-156/"><u>Efficient Screen Recording with Audio in the Latest Snipping Tool Update (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-0x80070194-in-onedrive-errors/"><u>Eliminating Windows' 0X80070194 in OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-programming-with-a-newly-installed-jdk-in-windows-11/"><u>Enhance Your Programming with a Newly Installed JDK in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-solving-blue-screens-caused-by-not-handled-error/"><u>Guide to Solving Blue Screens Caused by Not Handled Error</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-time-and-date-on-win-11-ui-bar/"><u>Hiding or Showing Time & Date on Win 11 UI Bar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-biometric-authentication-in-11th-gen-windows/"><u>How to Enable Biometric Authentication in 11Th Gen Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-disabled-discord-overlay/"><u>How to Reactivate Windows' Disabled Discord Overlay</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-honor-magic-5-pro-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Honor Magic 5 Pro to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-smart-techniques-save-your-insta-story-videos/"><u>In 2024, Smart Techniques  Save Your Insta Story Videos</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-13t-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi 13T Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-file-explorer-with-onedrive-integration/"><u>Initiating File Explorer with OneDrive Integration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-distance-remote-podcast-broadcast/"><u>Mastering Distance  Remote Podcast Broadcast</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-rdp-troubleshooting-in-windows-oses/"><u>Mastering RDP Troubleshooting in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-reset-for-mail-and-calendars-in-w11/"><u>Mastering the Reset for Mail & Calendars in W11</u></a></li>
<li><a href="https://win11.techidaily.com/meet-the-new-wave-exciting-laptops-from-ifa-2023/"><u>Meet the New Wave - Exciting Laptops From IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/muting-file-explorer-tabs-in-windows-11-guide/"><u>Muting File Explorer Tabs in Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-for-rapid-epic-games-access/"><u>Optimizing Windows for Rapid Epic Games Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-issues-of-not-allowing-file-writes-on-windows-11/"><u>Overcoming Issues of Not Allowing File Writes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-store-access-blockades/"><u>Overcoming Microsoft Store Access Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-office-activation-roadblocks/"><u>Overcoming Windows Office Activation Roadblocks</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-measures-eliminate-email-from-logon-window/"><u>Privacy Measures: Eliminate Email From Logon Window</u></a></li>
<li><a href="https://win11.techidaily.com/reawakening-computers-top-8-windows-restart-techniques/"><u>Reawakening Computers: Top 8 Windows Restart Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-your-login-experience-opting-for-stronger-protection-over-windows-11s-default-pin/"><u>Reimagining Your Login Experience: Opting for Stronger Protection over Windows 11'S Default PIN</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-sticky-windows-credential-puzzle/"><u>Reversing Sticky Windows Credential Puzzle</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reviving-archived-communication-exporting-to-live-exchange-server/"><u>Reviving Archived Communication: Exporting to LIVE Exchange Server</u></a></li>
<li><a href="https://facebook.techidaily.com/safe-sharing-strategy-social-media-tips-for-privacy-protection/"><u>Safe Sharing Strategy: Social Media Tips for Privacy Protection</u></a></li>
<li><a href="https://win11.techidaily.com/silent-speakers-unveil-audio-steps-immediately/"><u>Silent Speakers? Unveil Audio Steps Immediately</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/snapchat-intro-video-breakdown-size-format-duration/"><u>SnapChat Intro Video Breakdown  Size, Format, Duration</u></a></li>
<li><a href="https://win11.techidaily.com/spruce-up-your-windows-mail-and-schedule-with-pics/"><u>Spruce Up Your Window's Mail & Schedule With Pics</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-revealing-hidden-windows-drives/"><u>Strategies for Revealing Hidden Windows Drives</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-storage-efficiently-identifying-large-disk-users/"><u>Streamline Your Storage: Efficiently Identifying Large Disk Users</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-calendars-ifttt-meets-microsoft-to-do/"><u>Syncing Calendars: IFTTT Meets Microsoft To-Do</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/tested-and-asus-chromebook-c202sa-as-a-dependable-companion-for-students-and-children/"><u>Tested & Asus Chromebook C202SA as a Dependable Companion for Students & Children</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-beginners-guide-to-microsoft-copilot/"><u>The Ultimate Beginner's Guide to Microsoft Copilot</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-10-effective-substitutes-for-chatgpt/"><u>Top 10 Effective Substitutes for ChatGPT</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-troubleshooting-techniques-fixing-dll-files-that-arent-detected/"><u>Ultimate Troubleshooting Techniques: Fixing DLL Files That Aren't Detected</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-microsofts-copilot-key-insights-for-windows-11-users/"><u>Unlocking Microsoft's Copilot Key: Insights for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-of-windows-error-0xca00a009/"><u>Unpacking the Mystery of Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/win-sound-troubleshooting-overcoming-silence-hurdles/"><u>Win Sound Troubleshooting: Overcoming Silence Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-screen-sharing-disabling-pin-during-cast/"><u>Windows 11 Screen Sharing: Disabling PIN During Cast</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-custom-shortcut-for-safe-hardware-disconnect/"><u>Windows 11: Custom Shortcut for Safe Hardware Disconnect</u></a></li>
</ul></div>
