---
title: Advanced Insight Into Fixing DirectDraw Discrepancies in Win10/11
date: 2024-07-13T11:29:36.905Z
updated: 2024-07-14T11:29:36.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Insight Into Fixing DirectDraw Discrepancies in Win10/11
excerpt: This Article Describes Advanced Insight Into Fixing DirectDraw Discrepancies in Win10/11
keywords: Win10 Graphics Fixing,DirectDraw Win10,DirectDraw Win11 Solutions,Windows Graphics Issue,DirectX Drawbacks,Fix Win10 Graphics Glitches,DirectDraw Compatibility
thumbnail: https://thmb.techidaily.com/c9b8fd1733901244b30160c420a56660fbc28694609982153cd6de4dd43a450d.jpg
---

## Advanced Insight Into Fixing DirectDraw Discrepancies in Win10/11

 The DirectDraw error is one some players have reported occurring when they try to start older retro games on Windows 11/10 PCs. Those players see an error message that says, “DirectDraw error (variable error code) DDERR\_UNSUPPORTED.” Windows games don’t start when that error message pops up.

 Consequently, players can’t play older games like Age of Empires, Might and Magic 7, and Diablo because of the DirectDraw error. The same error can also occur for art and design software. This is how you can fix the DirectDraw error on a Windows 11/10 PC.

## 1\. Configure Affected Apps to Run in Compatibility Mode

 Running games and software in compatibility mode is a resolution that’s fixed the DirectDraw error for many users. As the DirectDraw error usually arises for older games and software, it makes sense to do so. You can set games to run in compatibility mode like this:

1. Open the Explorer file and folder manager by pressing **Win + E** and navigate to the affected game’s installation directory.
2. Right-click the game’s EXE (application) file and select **Properties**.
3. Click on **Compatibility** within the properties window.
4. Select **Run this program in compatibility** **mode** to activate that setting’s drop-down menu.  
![The Run the program in compatibility mode option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-this-program-in-compatibility-mode-for.jpg)
5. Then select the latest Windows platform that was available in the game’s release year. If you’re not sure, choose a **Windows 8** or 7 option on the menu.
6. Select **Apply** to set the new compatibility option.
7. Click **OK** to close out of the properties window.

 There’s also a Program Compatibility Troubleshooter that might be useful for troubleshooting the DirectDraw error. That troubleshooter includes an option that sets recommended compatibility settings for a selected program. It enables you to test programs with compatibility settings.

 If selecting the compatibility mode setting doesn’t work, consider utilizing the Program Compatibility Troubleshooter. This [Program Compatibility Troubleshooter guide](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/) provides guidelines for accessing and utilizing that troubleshooter.

## 2\. Set a 640 x 480 Resolution for the Game

 The DirectX error can also occur because your monitor’s resolution is incompatible with that of the affected game or software. Remember that higher resolutions of today might not have existed in an old game’s release year.

 To remedy that, try setting a 640 x 480 resolution for the game. You can do that by opening the **Compatibility** tab for a game as instructed for the first three steps of the preceding resolution. Then select the **Run in 640 x 480 screen** **resolution** checkbox and click **Apply** \> **OK**.

 If 640 x 480 is too low for you, you can also try applying a lower universal resolution within Windows settings. However, a resolution set within the Settings app will apply to Windows and all software. These are the steps for lowering the resolution within Settings:

1. Click on the taskbar’s magnifying glass button or **Search** text box.
2. Input the keyword **change resolution** in the settings.
3. Select **Change the resolution** **of the display** inside the search results_._
4. Next, click on the **Display resolution** drop-down menu.  
![The Display resolution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/display-resolution-setting.jpg)
5. Select a lower-resolution option on the menu.  
![Resolution options in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/resolution-options.jpg)
6. Then click the **Keep Changes** button to set the selected resolution.
7. Try starting the game or software.

## 3\. Enable Legacy Component Features

 Some users might need to enable older legacy component features to resolve the DirectDraw error. To be more specific, an older game might need the deprecated **DirectPlay** feature enabled to run. This is how you can enable legacy component features on Windows 11/10:

1. First, [open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/) by pressing **Windows** key + **R**, entering **appwiz.cpl** inside the Run dialog, and selecting **OK**.
2. Click on the **Turn Windows features on or off navigation** option along the left side of the uninstaller tool.  
![The Turn Windows features on or off option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-turn-windows-features-on-or-off-option.jpg)
3. Double-click **Legacy Components** to expand it.
4. Then select the **DirectPlay** checkbox.  
![The DirectPlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/directplay-option.jpg)
5. Select the **.NET Framework 3.5 (includes .NET 2.0 and 3.0)** checkbox if it’s not selected.  
![The .NET Framework 3.5 option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-features-options.jpg)
6. Press **OK** to install the features.
7. Restart Windows after installing the features.

## 4\. Install Missing DirectX Runtime Components

 As DirectDraw is a part of DirectX, this error is linked to that API. The error can arise because legacy games need older DirectX runtime libraries that might be missing on your PC. You can install missing DirectX components with DirectX End-User Runtime Web Installer like this:

1. Bring up this [DirectX End-User Runtime Web Installer](https://www.microsoft.com/en-us/download/details.aspx?id=35) page in your browsing software.
2. Press **Download** on that webpage.  
![The Download option for Microsoft DirectX End-User Runtime](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-download-option3.jpg)
3. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/#:~:text=the%20Command%20Prompt%3A-,Press%20Win%20%2B%20R%20to%20open%20the%20Run%20command%20dialog%20box,Explorer%20and%20then%20press%20Enter.) to go to whatever folder your browser is set to download files to.
4. Double-click the DirectX End-User Runtime Web Installer file (otherwise **dxwebsetup.exe**) to bring up an Installing Microsoft (R) DirectX (R) window.
5. Then click **I accept** to make your agreement with Microsoft.  
![The DirectX Runtime installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/directx-installer.jpg)
6. Select **Next** to install DirectX 9, 10, and 11 runtime components.

## 5\. Try Some Basic Windows Fixes

 If nothing has worked yet, there are some simple Windows tricks that usually fix display issues with software and games.

### Update Your Video Card’s Driver

 This error can also feasibly occur because an outdated or corrupted graphics driver is causing DirectDraw display component issues. Installing the latest graphics driver available for your PC’s GPU could remedy such issues. Our guide to [updating GPU drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) includes instructions for installing new graphics drivers in five different ways.

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-downloads-page.jpg)

### Run the Affected App in Windowed Mode

 Running the game or software in windowed mode can also address resolution issues. To do so, check out our article about [forcing games into windowed mode on Windows](https://www.makeuseof.com/windows-10-11-windowed-mode-games/). Follow the instructions for that guide’s third method to set the software to start in windowed mode.

![The Target box for a Windows game](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/target-box-for-a-game-shortcut.jpg)

### Reinstall the Affected Game or Software

 Reinstall affected games or software packages if you’re still trying to fix the DirectDraw error after applying other possible resolutions in this guide. If you’ve installed a game with gaming client software like Steam, Epic, or GOG, you can uninstall it with the same software. Or remove the software within the Control Panel or Settings with a method in this [guide to uninstalling programs on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-option-in-epic-games.jpg)

 When you’ve done that, restart Windows and reinstall the game with your gaming client software. If the game has a DVD/CD, you’ll need to reinstall it with that disc.

## Enjoy Your Retro Games or Apps on Windows

 Those are the best and most likely potential resolutions to work for fixing the DirectDraw error on Windows 11/10 PCs. One of the possible solutions in this guide will likely get the DirectDraw error sorted on your PC since many users have fixed that issue by applying them. Then you can return to playing the games that didn’t start because of that error.

 Consequently, players can’t play older games like Age of Empires, Might and Magic 7, and Diablo because of the DirectDraw error. The same error can also occur for art and design software. This is how you can fix the DirectDraw error on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boot-barriers-busted-5-proven-steps-for-secure-boot-fixes/"><u>Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-with-dev-drive-on-the-latest-windows-11-release/"><u>Boosting Efficiency with Dev Drive on the Latest Windows 11 Release</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-image-edition-excellence-tutorial-insights/"><u>[New] 2024 Approved  Image Edition Excellence  Tutorial Insights</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-pc-how-to-turn-on-hyper-v-in-win11/"><u>Boosting Your PC: How To Turn On Hyper-V in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-print-settings-made-easy-a-win11-guide-max-52-chars/"><u>Accessing Print Settings Made Easy: A Win11 Guide (Max 52 Chars)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-find-the-finest-tools-to-remove-background-noise-online/"><u>New Find The Finest Tools To Remove Background Noise Online</u></a></li>
<li><a href="https://win11.techidaily.com/bluetooth-woes-try-these-9-fixes-for-a-seamless-link-in-windows-11/"><u>Bluetooth Woes? Try These 9 Fixes for a Seamless Link in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-frustration-of-disconnected-discord-setup/"><u>Avoiding the Frustration of Disconnected Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-add-motion-blur-in-after-effects-for-2024/"><u>Updated How to Add Motion Blur in After Effects for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bound-windows-login-with-ms-account-essentials/"><u>Bound Windows Login with MS Account Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-10-and-11s-vital-parts-missing-alert/"><u>Avoiding Windows 10 & 11'S Vital Parts Missing Alert</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-widget-integration-in-windows-11/"><u>Boosting Productivity with Widget Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beautifying-your-pc-adding-a-weather-image-to-the-system-tray/"><u>Beautifying Your PC: Adding a Weather Image to the System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-user-interface-with-scroll-lock-icon-on-windows-11-systray/"><u>Boosting User Interface with Scroll Lock Icon on Windows 11 SysTray</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-windows-overload-7-ways-to-fix-too-many-requests-error/"><u>Beating Back Window's Overload: 7 Ways to Fix Too Many Requests Error</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-poco-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Poco</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-nvidia-cp-in-w11-environments/"><u>Addressing Non-Operational NVidia CP in W11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-prevent-unauthorized-device-usage/"><u>Best Practices to Prevent Unauthorized Device Usage</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-vram-maximizing-graphics-power-on-windows-os/"><u>Boosting VRAM: Maximizing Graphics Power on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-adjusting-immovable-gif-sizes-for-windows-users-of-discord/"><u>Breaking Free: Adjusting Immovable GIF Sizes for Windows Users of Discord</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-lights-camera-action-mastering-fundamental-shots-first/"><u>2024 Approved  Lights, Camera, Action! Mastering Fundamental Shots First</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-wow-crash-code-132-from-windows-11/"><u>Banishing WoW Crash Code 132 From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boot-into-admin-powershell-for-system-administration-in-windows-11/"><u>Boot Into Admin PowerShell for System Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-productivity-enlarge-or-minify-software-via-keyboard-in-win11/"><u>Boost Your Productivity: Enlarge or Minify Software via Keyboard in Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-youtube-news-sources-list-for-2024/"><u>Essential YouTube News Sources List for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-make-gif-stickers-for-whatsapp-100-the-easy-way/"><u>New 2024 Approved How to Make GIF Stickers for WhatsApp 100 The Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-type-speed-harnessing-windows-powertoys/"><u>Boost Your Type-Speed: Harnessing Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-no-more-space-on-windows-oses/"><u>Avoiding 'No More Space' On Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/boost-file-navigation-use-box-for-selection-in-win11/"><u>Boost File Navigation: Use Box for Selection in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-disk-capacity-7-affordable-tricks-for-windows-enthusiasts/"><u>Boosting Disk Capacity: 7 Affordable Tricks for Windows Enthusiasts</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unwanted-chrome-notifications-windows/"><u>Avoiding Unwanted Chrome Notifications (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-top-5-file-management-hacks/"><u>Boost Productivity with These Top 5 File Management Hacks</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/ragnors-rebirth-warriors-alliance-for-2024/"><u>Ragnor's Rebirth  Warriors Alliance for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boot-security-errors-squashed-in-5-easy-steps-for-windows-users/"><u>Boot Security Errors Squashed in 5 Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-opengl-failure-code-3-on-win11/"><u>Addressing NVIDIA OpenGL Failure Code 3 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-file-explorer-performance-on-win-11/"><u>Boosting File Explorer Performance on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-excels-speed-on-windows-pcs/"><u>Boost Your Excel's Speed on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-rdc-usability-in-the-latest-os/"><u>Boosting RDC Usability in the Latest OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-real-score-of-youtube-video-success-beyond-basic-view-counts/"><u>[Updated] The Real Score of YouTube Video Success  Beyond Basic View Counts</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-gameplay-flush-and-optimize-steam-dns-cache/"><u>Boost Your Gameplay: Flush and Optimize Steam DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-calculator-on-windows-11-effortlessly/"><u>Accessing the Calculator on Windows 11 Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/boost-note-visibility-for-effective-productivity/"><u>Boost Note Visibility for Effective Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-isolating-subjects-in-photography/"><u>Advanced Tips for Isolating Subjects in Photography</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-defenses-steps-to-turn-on-tpm-and-secure-boot-in-windows-11/"><u>Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-customizing-hotkey-behavior/"><u>Boost Productivity: Customizing Hotkey Behavior</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>