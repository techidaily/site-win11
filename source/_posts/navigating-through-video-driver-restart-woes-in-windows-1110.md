---
title: Navigating Through Video Driver Restart Woes in Windows 11/10
date: 2024-06-25T11:43:11.964Z
updated: 2024-06-26T11:43:11.964Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Video Driver Restart Woes in Windows 11/10
excerpt: This Article Describes Navigating Through Video Driver Restart Woes in Windows 11/10
keywords: WinXPartsRestartSolve,Windows11DriverFix,XPVideoResetGuide,VideoDriverTroubleshoot,FixWin10VDRestart,XperiaVRWoesResolved,Win11XPRestartHelp
thumbnail: https://thmb.techidaily.com/0cd373a6b0eece48a6e2d5d0248da5d1df8fff3f71196cdaae4af6176a3b33bf.jpg
---

## Navigating Through Video Driver Restart Woes in Windows 11/10

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11s-camera-issue-fixing-a00f425d-error/"><u>Tackling Windows 11'S Camera Issue: Fixing A00F425D Error</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/reflect-organize-and-proliferate-using-obsidian-canvas/"><u>Reflect, Organize, and Proliferate: Using Obsidian Canvas</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-voice-to-text-unlocking-the-power-of-automatic-transcription/"><u>Updated Voice to Text Unlocking the Power of Automatic Transcription</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-vids-deep-dive-a-comprehensive-handbook-for-2024/"><u>[New] Twitter Vids Deep Dive  A Comprehensive Handbook for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/ultimate-mp4-to-social-media-focus-on-facebook-for-2024/"><u>Ultimate MP4 to Social Media  Focus on Facebook for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-curriculum-capturers-selection-defining-the-most-effective-recorders/"><u>[New] Curriculum Capturer's Selection  Defining the Most Effective Recorders</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-complete-visual-vocabulary-of-tiktok-emojis-and-icons/"><u>The Complete Visual Vocabulary of TikTok Emojis & Icons</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/3-ways-to-export-contacts-from-apple-iphone-6-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>3 Ways to Export Contacts from Apple iPhone 6 to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/transform-photos-into-videos-top-maker-software-and-apps/"><u>Transform Photos Into Videos Top Maker Software and Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-unified-event-tracking-harmonizing-phone-and-tablet-with-pc-zoom/"><u>[New] 2024 Approved  Unified Event Tracking  Harmonizing Phone & Tablet with PC Zoom</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-ultimate-guide-to-downloading-instagram-soundtracks/"><u>The Ultimate Guide to Downloading Instagram Soundtracks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>