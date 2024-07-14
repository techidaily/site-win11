---
title: Flattening Windows 11 Corner Style
date: 2024-07-13T11:06:47.415Z
updated: 2024-07-14T11:06:47.415Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Flattening Windows 11 Corner Style
excerpt: This Article Describes Flattening Windows 11 Corner Style
keywords: Win11 Modernize,Flat UI Window,Cornerless PC Aesthetic,Unified Windows Design,Sleek Windows Edge,Streamlined WS11 Interface,Simplified Windows Style
thumbnail: https://thmb.techidaily.com/4f7878f35a5617dd30422b38a025795d7b590bfdd2ba7a274f89a9a6584223ab.jpg
---

## Flattening Windows 11 Corner Style

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://mondly-stories.techidaily.com/pidgin-into-mainstream-the-evolution-of-english-vocabulary/"><u>Pidgin Into Mainstream: The Evolution of English Vocabulary</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-onedrive-error-adding-folder-not-possible-immediately/"><u>Resolving OneDrive Error - Adding Folder Not Possible Immediately</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-speak-with-style-mastering-the-art-of-altering-vocal-effects-on-snapchat-for-2024/"><u>[Updated] Speak with Style  Mastering the Art of Altering Vocal Effects on Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-efficiently-engaging-recovery-tool/"><u>Key Steps for Efficiently Engaging Recovery Tool</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-window-task-completion-via-key-combinations/"><u>Speedy Window Task Completion via Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mcuicntexe-entry-point-not-found-error-on-windows/"><u>How to Fix the “McUICnt.exe Entry Point Not Found” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-read-only-mode-on-windows-folders/"><u>Preventing Read-Only Mode on Windows Folders</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-disrupting-the-norms-standing-out-from-mass-market-tiktoks/"><u>[New] In 2024, Disrupting the Norms  Standing Out From Mass-Market TikToks</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-xiaomi-civi-3-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Xiaomi Civi 3 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/refinement-of-visuals-windows-11-dpi-tweaks/"><u>Refinement of Visuals: Windows 11 DPI Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/quicker-battlenet-file-syncing-on-windows-devices/"><u>Quicker Battle.net File Syncing on Windows Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-periscope-understanding-features-pricing-and-registration-steps/"><u>2024 Approved  Navigating Periscope  Understanding Features, Pricing & Registration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/stop-system-spontaneities-fixing-windows-11-restarts/"><u>Stop System Spontaneities: Fixing WIndows 11 Restarts</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-good-ways-to-make-sure-your-video-editing-course-is-worthing-to-watch/"><u>Updated In 2024, Good Ways to Make Sure Your Video Editing Course Is Worthing to Watch</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-archiving-concealing-data-within-images-windows-11/"><u>Invisible Archiving: Concealing Data Within Images (Windows 11)</u></a></li>
<li><a href="https://extra-support.techidaily.com/preventing-htc-vive-disorientation-and-nausea-for-2024/"><u>Preventing HTC Vive Disorientation and Nausea for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-acquire-and-implement-microsoft-stores-application-bundles/"><u>Simple Steps to Acquire & Implement Microsoft Store's Application Bundles</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Samsung Galaxy F54 5G? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-ultimate-guide-to-windows-1110s-screen-capture-leaders/"><u>2024 Approved  Ultimate Guide to Windows 11/10'S Screen Capture Leaders</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-image-editing-techniques-for-subject-separation/"><u>Masterful Image Editing: Techniques for Subject Separation</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-make-animated-magic-happen-top-online-animation-tools-revealed/"><u>New Make Animated Magic Happen Top Online Animation Tools Revealed</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-how-can-you-import-and-adjust-the-video-clips-on-wondershare-filmora/"><u>New 2024 Approved How Can You Import and Adjust the Video Clips on Wondershare Filmora?</u></a></li>
<li><a href="https://win11.techidaily.com/solving-common-closed-captions-issues-in-win11/"><u>Solving Common Closed Captions Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-fine-tune-windows-with-ease-using-alomware-suite/"><u>Navigate & Fine-Tune Windows with Ease Using AlomWare Suite</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-uncover-the-secrets-of-mp3-conversion-on-windows-a-compelling-read/"><u>Updated 2024 Approved Uncover the Secrets of Mp3 Conversion on Windows A Compelling Read</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-say-goodbye-to-format-issues-the-top-12-audio-converters-for-easy-conversion/"><u>In 2024, Say Goodbye to Format Issues The Top 12 Audio Converters for Easy Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-split-view-failures-in-os/"><u>Overcoming Split View Failures in OS</u></a></li>
<li><a href="https://win11.techidaily.com/sharpen-system-speed-lowering-high-usage-of-interest-tasks/"><u>Sharpen System Speed: Lowering High Usage of Interest Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-windows-11-cc-issues/"><u>Quick-Fix Strategies for Windows 11 CC Issues</u></a></li>
<li><a href="https://youtube-data.techidaily.com/echniques-to-improve-video-visibility-on-youtube-platform-for-2024/"><u>[New] Techniques to Improve Video Visibility on YouTube Platform for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unwind-and-learn-your-guide-to-podcasting-multitasking-for-2024/"><u>Unwind and Learn  Your Guide to Podcasting Multitasking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-windows-automatic-deletion/"><u>Revolutionize File Management with Windows' Automatic Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gaming-setup-direct-to-windows-ps3-pad/"><u>Seamless Gaming Setup: Direct-to-Windows PS3 Pad</u></a></li>
<li><a href="https://win11.techidaily.com/immerse-in-vividness-adding-life-like-wallpapers-on-windows-11/"><u>Immerse in Vividness: Adding Life-Like Wallpapers on Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-ultimate-list-10-best-android-apps-for-video-editing/"><u>New In 2024, The Ultimate List 10 Best Android Apps for Video Editing</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-honor-90-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Honor 90? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obtrusive-quit-request-error-in-roblox-players-computers/"><u>Overcoming Obtrusive Quit Request Error in Roblox Players' Computers</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-creativity-microsoft-paints-fresh-additions/"><u>Revolutionizing Creativity: Microsoft Paint's Fresh Additions</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-control-over-your-screen-amidst-the-dark/"><u>Reclaim Control Over Your Screen Amidst the Dark</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/effortlessly-blur-video-footage-on-iphone-and-android-devices-for-2024/"><u>Effortlessly Blur Video Footage on iPhone and Android Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-integration-for-steam-deck-users/"><u>Seamless Windows Integration for Steam Deck Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-modules-installer-workers-high-cpu-usage/"><u>How to Fix the Windows Modules Installer Worker's High CPU Usage</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-update-failure-0x800f0845-error/"><u>Resolving Windows Update Failure: 0X800F0845 Error</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-web-experience-implementing-mouse-gestures-in-ms-edge-win-11/"><u>Reimagine Your Web Experience: Implementing Mouse Gestures in MS Edge (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-vmware-errors-on-windows-11/"><u>How to Reset VMware Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/precision-configurations-for-an-excellent-windows-11-experience/"><u>Precision Configurations for an Excellent Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-windows-error-0xc1900101/"><u>Strategies for Correcting Windows Error 0xC1900101</u></a></li>
</ul></div>
