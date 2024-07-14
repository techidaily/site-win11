---
title: "Personalize Your Workspace: Switching Themes on Win11"
date: 2024-07-13T09:56:37.896Z
updated: 2024-07-14T09:56:37.896Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalize Your Workspace: Switching Themes on Win11"
excerpt: "This Article Describes Personalize Your Workspace: Switching Themes on Win11"
keywords: Workspace Personalization,Win11 Theme Change,Custom Windows Desktop,Enhance Workspace UI,Dynamic Win11 Aesthetics,User-Defined Window Layouts,Adaptive Win11 Design
thumbnail: https://thmb.techidaily.com/f247ef7a94b421ec0fcafea579ee074c3050225ad0c19a044a9d73401964e5e7.jpg
---

## Personalize Your Workspace: Switching Themes on Win11

 Windows has inbuilt support for themes in customization settings. While Microsoft doesn’t officially make any new themes as it did before, plenty of options are available on Microsoft Store. If you aren’t satisfied with them, you can also try third-party themes.

 Microsoft moved many Control Panel options to the Settings app. So, you need to head over to the Personalization options in the Settings app to apply a new theme. But, do you know that you can do it using multiple other methods? Here’s how:

## 1\. Using the Desktop Context Menu

 The desktop context menu is the most preferred method to change desktop wallpaper and themes in Windows OS. Windows 11 retains that option in the context menu, and we hope that it doesn’t go away. Here’s how to change the theme using the Desktop context menu:

1. Boot up your Windows PC and right-click on the desktop.
2. Now, click on the**Personalization** option from the context menu.  
![Changing Theme Using the Desktop Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-desktop-context-menu.jpg)
3. Scroll down and click on the**Themes** option.
4. Under the Current theme section, click on any of the available themes to apply them to your system.
5. Close the settings app.

## 2\. Using the Settings App

 Since the desktop context menu redirects you to the Settings app, you can directly open it and change the system theme. Here’s how:

1. Press**Win + I** to launch the Settings app.
2. Click on the**Personalization** option in the left-hand side menu.
3. Scroll down and select the**Themes** option.  
![Changing Theme Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-settings-app.jpg)
4. Now, click on any theme from the section of available themes. You can also apply a high-contrast theme by selecting the Contrast Theme option below.

## 3\. Using the Old Control Panel Personalization Utility

 The older version of Windows OS had a control panel personalization utility, using which you could change the themes, color schemes, and wallpapers. Microsoft hid this option in Windows 11, but you can still access it using the run command box. Here’s how:

`shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}-Microsoft.Personalization`

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type the following command and press the enter key.
2. The old Personalization utility will launch. Navigate to the themes window and click on any theme to apply it. The utility won’t redirect you to the Settings app.  
![Changing Theme Using the Old Control Panel Personalization Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-the-old-control-panel-personalization-utility.jpg)
3. Close the Personalization utility window.

## 4\. Using the Run Command Box

 You can even skip the hassle to go through layers of the Settings app and can directly launch the theme settings using the Run command box. Here’s how:

1. Press**Win + R** to launch the Run command box. Type**ms-settings:themes** and press the enter key.
2. Windows 11 Settings app will launch and directly take you to the themes section.
3. Click on any of the available themes to apply and change the current theme.

## 5\. Using File Explorer

 All the installed themes on your Windows 11 system reside in the Windows AppData folder. You can access the folder using File Explorer and then apply any theme on your system. Here’s how:

1. Press**Win + E** to [launch the File Explorer app](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, paste the following path, and press the enter key:**%LocalAppData%\\Microsoft\\Windows\\Themes**
3. You will see a bunch of themes listed here. Double-click on any ".theme" file to apply it to your system.  
![Changing Theme Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-file-explorer.jpg)
4. There will be a bunch of folders as well. These usually belong to the downloaded themes. Open the folder, and locate the theme file to apply a downloaded theme.

## 6\. Using CMD

 You can change the theme in Windows 11 using the command prompt. All you need to do is enter the location of the theme and run it. Repeat the following steps:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (admin)** option from the menu.
2. The Terminal app will launch. Click on the**+** icon to open a command prompt window with admin privileges.
3. Now, type**C:\\Windows\\resources\\Themes\\aero.theme** command and press the enter key.  
![Changing Theme Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-cmd.jpg)
4. Your Windows 11 system will change to the inbuilt aero theme. Similarly, you can replace the name of any other inbuilt theme and apply it.

## 7\. Using a Shortcut

 You can apply your favorite theme by creating a shortcut on the desktop. That way, you won’t have to launch the File Explorer or Settings app to change the theme. Here’s how to do it:

1. Press**Win + E** to launch the File Explorer app.
2. Navigate to the address bar and type the following path:**C:\\Windows\\resources\\Themes\\**
3. Press the enter key to open the Themes folder.
4. Now, right-click on a theme and click on**Show More** options.
5. Then click on the**Send to** option and select the**Desktop (create shortcut)** option.  
![Changing Theme Using a Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-a-shortcut.jpg)
6. Press**Win + D** to switch to the Desktop. Make sure to close the Settings app before running the shortcut.
7. Double-click on the newly created theme shortcut to apply the theme to your computer

## 8\. Using PowerShell

 Like CMD, you can access the theme files from PowerShell and change the theme. Repeat the following steps:

1. Press**Win + R** to launch the Run command box. Type PowerShell in the text input area and press**Ctrl + Shift + Enter** to launch PowerShell with admin privileges.
2. Now enter the following command and press the enter key:
3. start-process -filepath "C:\\Windows\\Resources\\Themes\\aero.theme"
4. You can replace the “aero.theme” portion of the command with any other theme name. Some of the examples include: “dark.theme” and “spotlight.theme”.  
![Changing Theme Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-powershell.jpg)
5. Type**exit** and press enter to close the command prompt.

## 9\. Using a Batch File

 You can create a batch file and run it every time someone changes your preferred theme. Moreover, you can place it on the desktop to quickly switch to a theme. Here’s how to do it:

`C:\Windows\resources\Themes\aero.theme  
 taskkill /F /IM systemsettings.exe`

1. Press**Win + S** and type Notepad. Click on the first search result to open the Notepad app.
2. Now, paste the following script into the Notepad file:
3. Go to the top menu bar and click on**File > Save as** option. Keep the filename as**changetheme.bat** , select the**All files** option, and save it on the desktop.  
![Changing Theme Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/changing-theme-using-a-batch-file.jpg)
4. Close the Notepad app and Press Win + D to switch to the desktop.
5. Now, right-click on the changetheme.bat file and select the**Run as administrator** option.
6. The file will open a command prompt window, change the theme and close the CMD and System Settings window automatically.

## Change Your Windows 11 Themes Like a Pro

 Windows 11 stores themes in multiple locations. The simplest way to change the theme is by using the Settings app. But if you want to keep the mouse clicks to a minimum, creating the shortcut of a theme file or running a batch script is better. If you aren’t afraid of the Terminal, the command prompt and PowerShell methods also work like a charm.


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
<li><a href="https://video-capture.techidaily.com/updated-streamlined-list-6-efficient-mac-screen-recording-solutions-for-2024/"><u>[Updated] Streamlined List  6 Efficient Mac Screen Recording Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-the-comprehensive-srt-handbook-for-enthusiasts/"><u>[New] 2024 Approved  The Comprehensive SRT Handbook for Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-mastering-silence-effective-video-noise-reduction-techniques-in-adobe-premiere-pro/"><u>2024 Approved Mastering Silence Effective Video Noise Reduction Techniques in Adobe Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-11-taskbar/"><u>Addressing Non-Operational Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-realme-v30-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Realme V30 Phone Pattern Lock</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-windows-107-users-guide-to-dawnbreakers-discovering-top-8-audio-workstations/"><u>New Windows 10/7 Users Guide to Dawnbreakers Discovering Top 8 Audio Workstations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-10-2-methods-for-2024/"><u>How to Restore Windows Photo Viewer in Windows 10 (2 Methods) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17 Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-mastering-access-to-exclusive-snapshots/"><u>[Updated] 2024 Approved  Mastering Access to Exclusive Snapshots</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-most-used-aspect-ratio-adjustment-tools-online/"><u>In 2024, Most Used Aspect Ratio Adjustment Tools Online</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-6-ways-to-record-minecraft-gameplay/"><u>[Updated] In 2024, 6 Ways to Record Minecraft Gameplay</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-vivo-v27-by-fonelab-android-recover-music/"><u>How to recover old music from your Vivo V27</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-delete-white-background-in-photoshop-how-to-create-a-transparent-background-in-photoshop-steps-to-get-rid-of-white-background-in-ph/"><u>New 2024 Approved How to Delete White Background in Photoshop. How to Create a Transparent Background in Photoshop? Steps to Get Rid of White Background in Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-10-best-websites-for-copyright-free-gaming-music/"><u>[Updated] 2024 Approved  10 Best Websites for Copyright-Free Gaming Music</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-best-10-video-editing-apps-to-edit-and-make-instagram-reels-for-2024/"><u>[New] Best 10 Video Editing Apps to Edit and Make Instagram Reels for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-upload-footage-seamlessly-to-facebook-pc-and-android-style/"><u>2024 Approved  Upload Footage Seamlessly to Facebook, PC & Android Style</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-vlc-video-trimmer-for-mac-how-to-cut-clips-without-losing-a-single-pixel/"><u>Updated In 2024, VLC Video Trimmer for Mac How to Cut Clips Without Losing a Single Pixel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-making-money-with-youtube-understanding-partner-program/"><u>2024 Approved  Making Money with YouTube  Understanding Partner Program</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-lifetime-of-memories-elevated-in-the-cloud-free-and-paid-storage-compared/"><u>In 2024, Lifetime of Memories, Elevated in the Cloud  Free & Paid Storage Compared</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/perfecting-snapchat-gifting-a-guide-to-gifs-for-2024/"><u>Perfecting Snapchat Gifting - A Guide to Gifs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
</ul></div>
