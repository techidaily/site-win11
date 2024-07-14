---
title: Addressing Video Driver Crash on Win11/10
date: 2024-07-13T10:04:28.525Z
updated: 2024-07-14T10:04:28.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Video Driver Crash on Win11/10
excerpt: This Article Describes Addressing Video Driver Crash on Win11/10
keywords: Windows Driver Error Fix,Win11 Video Glitch Resolution,Win10 Video Driver Failure,Video Driver Stability Win11,Crashing Video Driver Win10/11,Fixing Win11/10 Video Crash,Addressing Win10 Video Drivers
thumbnail: https://thmb.techidaily.com/43e39de2530caaef8af78f1650abc11434992b40c432e7b5caac8bd0f3cdf48f.png
---

## Addressing Video Driver Crash on Win11/10

 Users have widely reported an error message that says “Video driver crashed and was reset” pops up when playing or trying to start Windows games. This error message crashes games whenever it arises. Players have reported that the issue usually occurs in games like Fortnite, ARK: Survival, Final Fantasy 7, and Sea of Thieves, among others.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.

## 1\. Utilize the Video Playback Troubleshooter

 The Video Playback troubleshooter might be useful for fixing the “Video driver crashed” error when that error affects video playback. That is a troubleshooter for fixing video playback issues, which the “Video driver crashed” error sometimes is. Our [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) guide provides instructions for accessing that troubleshooter and others.

 When you start that troubleshooting tool, you’ll have three options. Select the **I want to continue with this troubleshooter** option to initialize the automated video troubleshooting. The troubleshooter might automatically make some system changes or suggest you do something like installing a codec.

![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-video-playback-troubleshooter.jpg)

## 2\. Update Your PC’s Graphics Driver

 Updating graphics drivers is one of the most widely confirmed ways to fix the “Video driver crashed” error. Even the error message itself suggests users update their graphics cards’ drivers. So, it’s quite likely this potential resolution will address the error if your graphics card driver needs updating.

 Our [how to update graphics drivers](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) article covers the different methods for applying this potential resolution on a Windows PC. You could utilize driver updater software, but that won’t necessarily install the very latest driver available for your graphics card.

 Manually updating graphics drivers by downloading them from the NVIDIA, AMD, or Intel sites is a bit slower but will ensure you get the very latest driver package.

![The NVIDIA driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-nvidia-driver-download-options.jpg)

## 3\. Reinstall Your PC’s Graphics Driver

 If your PC’s current graphics driver is the latest one available, it won’t be outdated, but there could still be an issue with that driver. In this case, you might still need to reinstall the driver to resolve this error.

 These are the steps for reinstalling a graphics driver:

1. [Open Device Manager](https://www.makeuseof.com/windows-open-device-manager/), which is accessible on the Power User menu (press **Windows** key + **X** to open).
2. Click the small arrow beside the **Display adapters** category.
3. Right-click your PC’s GPU and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-device-option.jpg)
4. Select a checkbox option for deleting the driver and click **Uninstall**.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option3.jpg)
5. Click on **Action > Scan for hardware changes** to reinstall the graphics driver.

 If the **Scan for hardware** changes option doesn’t reinstall the GPU’s driver, download the latest driver package for your graphics card from the [Intel](https://www.intel.com/content/www/us/en/download-center/home.html), [AMD](https://www.amd.com/en/support), or [NVIDIA](https://www.nvidia.com/download/index.aspx) websites. Double-click on the downloaded driver package file to open its setup window and select the installation option there.

## 4\. Lower Your Monitor’s Refresh Rate

 Some users have said on forums that lowering the frame rate can resolve the “Video driver crashed” error. So, that might be worth trying if your monitor has a higher maximum refresh rate. You can reduce the frame rate by lowering a monitor’s refresh rate as follows:

1. Open the file search tool (accessible with a **Windows** logo + **S** hotkey).
2. Input **advanced display settings**.
3. Select **View advanced display info** to open that part of Settings.
4. Then, select a lower setting in the **Refresh rate** drop-down menu.  
![The Refresh rate drop-down menu in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/advanced-display-settings.jpg)

 If you can access in-game settings, you might also be able to select a lower frame rate option from there. Look through an affected game’s graphical settings menu to see if it includes an FPS option for selecting lower or higher frame rates.

## 5\. Reduce an Affected Game’s Graphical Quality Settings

 The “Video driver crashed” error can sometimes occur when a game’s graphical settings are set too high. That’s more likely on lower-spec PCs with poorer GPUs that can’t handle higher graphics settings so well.

 A few players have said they fixed the “Video driver crashed” error by lowing in-game graphics options. So, that’s worth trying if you can reach in-game settings.

 There will probably be numerous in-game graphical options you can adjust. Lower the screen, texture, and shadow resolution settings that are included in many games. Then, select to apply the new graphical settings and restart the game.

![A game's Graphics Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/graphics-settings.jpg)

 Alternatively, you can try selecting a lower graphics preset option instead. Most games have three or more graphics presets that generally change graphical settings. Selecting a lower-quality preset will automatically reduce various graphics options.

 Some players have also reported this error occurring after enabling DirectX 12\. So, look for a DirectX setting in the graphics menu. If you can find it, make sure that option is set to DirectX 11\.

## 6\. Set a Higher TDR Delay Value

 TDR delay is the Timeout Detection and Recovery delay period. Setting a higher TDR delay value will give a graphics card more time to respond, which can resolve GPU errors such as the “Video driver crashed” error.

 You can set a higher TDR delay value by tweaking the registry like this:

1. Bring up the tool for finding files and input Registry Editor in its search box.
2. Select **Registry Editor** to view that app’s window.
3. Go to this **GraphicsDrivers** key by entering the following path inside the registry address bar:  
HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\GraphicsDrivers
4. If a **TDRDelay** DWORD already exists, you can skip to step six. If not, right-click **GraphicsDrivers** in Registry Editor’s left sidebar and select the **New** and **DWORD (32-bit) Value** options from the context menu.  
![The DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-dword-32-bit-value-option.jpg)
5. Input **TDRDelay** for the key’s title.
6. Double-click on the **TDRDelay** registry entry.
7. Delete the current number and enter **8** in the **Value data** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-edit-dword-window.jpg)
8. Select **OK** to finish.

 Restart the PC after applying this registry tweak. Then, try playing games or videos to see if this error still occurs.

## Enjoy Your Windows Games and Videos Again

 Those potential resolutions are among the most widely confirmed troubleshooting methods for fixing the “Video driver crashed” error. Many users have discussed how to fix the “Video driver crashed” error on forums and confirmed them to work.

 So, maybe one of them will fix the same issue on your PC, and then you can enjoy all your Windows games or videos again without further crashing.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-apple-iphone-13-pro-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your Apple iPhone 13 Pro Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-audionists-toolkit-for-silencing-unwanted-audio-elements/"><u>New The Audionists Toolkit for Silencing Unwanted Audio Elements</u></a></li>
<li><a href="https://win11.techidaily.com/7-w11-ui-aspects-that-seem-out-of-place/"><u>7 W11 UI Aspects That Seem Out of Place</u></a></li>
<li><a href="https://extra-support.techidaily.com/pioneering-audio-tools-the-creme-de-la-creme-for-mac-for-2024/"><u>Pioneering Audio Tools  The Crème De La Crème for Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/surging-downloads-overcome-the-01kbs-stall-on-windows/"><u>Surging Downloads: Overcome the 0.1KB/S Stall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-xbox-mic-in-windows-11/"><u>Troubleshooting Non-Functional Xbox Mic in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/precision-in-film-craft-advanced-kinemaster-strategies-for-2024/"><u>Precision in Film Craft  Advanced Kinemaster Strategies for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-itel-a70-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Itel A70 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-8-streamers-pick-high-end-cameras-reviewed/"><u>In 2024, Best 8 Streamer's Pick  High-End Cameras Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-games-on-windows-avoid-common-setup-pitfalls/"><u>Xbox Games on Windows: Avoid Common Setup Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-access-denied-a-comprehensive-guide-to-5-solutions/"><u>Winning Against 'Access Denied': A Comprehensive Guide to 5 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-key-differences-between-windows-terminal-and-powershell/"><u>Understanding Key Differences Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/a-slumberful-cycle-for-your-pcs-life/"><u>A Slumberful Cycle for Your PC's Life</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-wi-fi-showing-limited-access-in-windows-11/"><u>9 Ways to Fix Wi-Fi Showing Limited Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/data-deluge-infographics-on-youtubes-intriguing-insights-for-2024/"><u>Data Deluge  Infographics on YouTube's Intriguing Insights for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-windows-understanding-report-generation-and-analysis/"><u>The Art of Windows Understanding: Report Generation & Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-memory-integrity-feature-grayed-out-on-windows-11/"><u>7 Ways to Fix the Memory Integrity Feature Grayed Out on Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-revive-the-past-best-ps1-emulation-software-for-modern-systems/"><u>[Updated] 2024 Approved  Revive the Past  Best PS1 Emulation Software for Modern Systems</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-age-for-gaming-the-mmo-evolution-tale/"><u>A New Age for Gaming: The MMO Evolution Tale</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-fond-memories-old-phone-xxs-photography/"><u>[New] Fond Memories  Old Phone Xx's Photography</u></a></li>
</ul></div>
