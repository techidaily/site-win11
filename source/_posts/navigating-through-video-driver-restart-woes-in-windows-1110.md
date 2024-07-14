---
title: Navigating Through Video Driver Restart Woes in Windows 11/10
date: 2024-07-13T10:59:27.444Z
updated: 2024-07-14T10:59:27.444Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-snagging-stunning-pexels-pictures/"><u>2024 Approved  Step-by-Step  Snagging Stunning Pexels Pictures</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-deciding-the-top-iphone-video-editor-cameo-or-filmorago-for-2024/"><u>[Updated] Deciding the Top iPhone Video Editor  Cameo or FilmoraGo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/compreenas-a-solution-for-xbox-app-failure-error-0x80073d26/"><u>Compreenas a Solution for Xbox App Failure: Error 0X80073D26</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-nokia-c32-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Nokia C32 to Roku | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-out-windows-11-drag-and-drop-issues/"><u>Smooth Out Windows 11 Drag-and-Drop Issues</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-remedying-outlook-failures/"><u>Essential Steps for Remedying Outlook Failures</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-efficiency-and-productivity-discover-powertoys-top-usage-tips/"><u>Enhance Efficiency & Productivity: Discover PowerToys' Top Usage Tips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-all-encompassing-review-the-hero4-black-guide/"><u>[New] All-Encompassing Review  The Hero4 Black Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-monetization-verification-maximizing-streamer-incomes/"><u>2024 Approved  Monetization Verification  Maximizing Streamer Incomes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-secrets-to-compelling-instagram-video-descriptions/"><u>In 2024, The Secrets to Compelling Instagram Video Descriptions</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hidden-wi-fi-in-the-realm-of-windows-11/"><u>Resurrecting Hidden Wi-Fi in the Realm of Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-5-ways-to-record-facetime-calls/"><u>In 2024, 5 Ways to Record FaceTime Calls</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-window-bar-transparency-in-win11/"><u>A Step-by-Step for Window Bar Transparency in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-volume-mixer-in-the-action-center-in-windows-11/"><u>How to Enable the Volume Mixer in the Action Center in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/making-the-right-vr-purchase-on-the-go-vs-tethered-tech/"><u>Making the Right VR Purchase  On-the-Go Vs. Tethered Tech</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-inaccessible-pin-unlock-routine-in-windows-11/"><u>Resetting Inaccessible Pin Unlock Routine in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gopro-hero-10-secrets-for-flawless-long-exposure-films/"><u>2024 Approved  GoPro Hero 10 Secrets for Flawless Long-Exposure Films</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-gear-use-windows-widgets-for-efficiency/"><u>Streamlining Your Gear Use: Windows Widgets for Efficiency</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-beats-optimal-background-music-for-vids/"><u>2024 Approved  Unveiling Beats  Optimal Background Music for Vids</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-explore-the-world-of-custom-thumbnails-top-6-tools-reviewed-for-2024/"><u>[New] Explore the World of Custom Thumbnails - Top 6 Tools Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-gaps-in-systems-startup-list/"><u>Troubleshooting Gaps in System's Startup List</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/visual-virtuosos-the-ultimate-resource-for-filters-perfection/"><u>Visual Virtuosos  The Ultimate Resource for Filters Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-revenue-generation-from-windows-11/"><u>Exploring Revenue Generation From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/find-the-folder-windows-captured-photos/"><u>Find the Folder: Windows Captured Photos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevating-marketing-through-real-peoples-endorsements/"><u>Elevating Marketing Through Real People’s Endorsements</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-signals-secure-connections-windows-wi-fi-tips/"><u>Hidden Signals, Secure Connections: Windows Wi-Fi Tips</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-in-this-article-i-will-share-top-40-keyboard-shortcuts-for-final-cut-pro-and-ive-categorized-them-to-make-these-easier-to-find/"><u>New 2024 Approved In This Article, I Will Share Top 40 Keyboard Shortcuts for Final Cut Pro and Ive Categorized Them to Make These Easier to Find</u></a></li>
<li><a href="https://win11.techidaily.com/fortifying-data-travel-best-practices-for-ws11w10/"><u>Fortifying Data Travel: Best Practices for WS11/W10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevating-content-strategy-through-youtube-metrics/"><u>[Updated] In 2024, Elevating Content Strategy Through YouTube Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/freedom-from-epic-game-launcher-in-windows-11-steps-explained/"><u>Freedom From Epic Game Launcher in Windows 11: Steps Explained</u></a></li>
<li><a href="https://fox-http.techidaily.com/4kplus-3d-blu-ray-magic-high-end-players-guide/"><u>4K+ 3D Blu-Ray Magic  High-End Players Guide</u></a></li>
<li><a href="https://win11.techidaily.com/turning-off-google-chrome-alerts-windows-edition/"><u>Turning Off Google Chrome Alerts, Windows Edition</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-pinpointing-areas-renowned-for-waves-of-excited-cheering/"><u>2024 Approved Pinpointing Areas Renowned for Waves of Excited Cheering</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-aesthetic-adjustments-iphones-pro-image-cropping-apps/"><u>2024 Approved  Aesthetic Adjustments  IPhone's Pro Image Cropping Apps</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-auto-opens-on-microsofts-marketplace-app/"><u>Ceasing Auto-Opens on Microsoft's Marketplace App</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-0x80070194-a-guide-to-onedrive-in-ws/"><u>Counteracting 0X80070194: A Guide to OneDrive in WS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oppo-a2-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Oppo A2 Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/from-fuchsia-to-functional-8-fixes-for-windows-color-issues/"><u>From Fuchsia to Functional: 8 Fixes for Windows Color Issues</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-facebooks-enhanced-privacy-hub-for-safer-browsing/"><u>Decoding Facebook’s Enhanced Privacy Hub for Safer Browsing</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-xs-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-pixel-perfection-top-tools-for-preserving-tweets-videos/"><u>[New] In 2024, Pixel Perfection  Top Tools for Preserving Tweets' Videos</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-tecno-pova-5-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Tecno Pova 5 FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-hardware-requirements-for-games/"><u>Resolving Windows Hardware Requirements for Games</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-couldnt-load-page-in-windows-marketplace/"><u>Troubleshooting 'Couldn't Load Page' In Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-technique-for-mkv-to-mp4-change/"><u>Step-by-Step Windows Technique for MKV to MP4 Change</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-network-defenses-with-5-tweaks-to-firewall/"><u>Revitalizing Network Defenses with 5 Tweaks to Firewall</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-revolutionize-chromebooks-tone-with-our-essential-list-of-extensions/"><u>[New] 2024 Approved  Revolutionize Chromebook's Tone with Our Essential List of Extensions</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-mastering-the-art-of-sniping-on-mac-with-these-tools/"><u>[New] In 2024, Mastering the Art of Sniping on Mac with These Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-syncing-twitter-vids-with-instagrams-social-sharing/"><u>[New] Syncing Twitter Vids with Instagram's Social Sharing</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-11-pro-screen-lock-without-data-loss-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock iPhone 11 Pro screen lock without data loss?</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-local-drive-space-in-win11-without-loss-of-files-max-156-chars/"><u>Securely Manage Local Drive Space in Win11 Without Loss of Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-read-only-filters-in-win-os/"><u>Eliminating Read-Only Filters in Win OS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oppo-a79-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Oppo A79 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/simplified-systems-for-saving-screen-calls/"><u>Simplified Systems for Saving Screen Calls</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-it-admin-cant-do-more-on-windows-os/"><u>Fixing 'Your IT Admin Can't Do More' On Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-void-seven-strategies-for-stabilizing-obs-studio-link/"><u>Avoiding the Void: Seven Strategies for Stabilizing OBS Studio Link</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-ascertaining-your-pcs-intel-core-gen/"><u>Techniques for Ascertaining Your PC's Intel Core Gen</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-elevating-visuals-with-vocal-synchrony-a-curated-list-of-pivotal-song-choices/"><u>Updated 2024 Approved Elevating Visuals with Vocal Synchrony A Curated List of Pivotal Song Choices</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-your-windows-pcs-character-map-functionality-succeeds/"><u>Ensuring Your Windows PC's Character Map Functionality Succeeds</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-tall-tales-reimagined-edits-for-vt-videos-on-fcpx/"><u>[New] In 2024, Tall Tales Reimagined  Edits for VT Videos on FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-bluetooth-device-unable-to-use-buttons-or-mute/"><u>Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-kiddo-cars-miniature-mayhem-matches/"><u>In 2024, Kiddo Cars  Miniature Mayhem Matches</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xc0f1103f-issue-with-geforce-now-on-windows/"><u>Fixing XC0F1103F Issue with GeForce Now on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-craft-an-invisible-taskbar-on-windows-11/"><u>Steps to Craft an Invisible Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-spotifys-code-4-error/"><u>Deciphering and Rectifying Spotify's Code 4 Error</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-vanguard-of-radio-theatre-composition/"><u>[New] The Vanguard of Radio-Theatre Composition</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-protection-enable-windows-11s-controlling-access/"><u>Setting Up Protection: Enable Windows 11’S Controlling Access</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-effortless-free-capture-of-your-android-world/"><u>2024 Approved  Effortless Free Capture of Your Android World</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-creative-geniuses-selecting-the-best-youtube-videos-for-channels-for-2024/"><u>[Updated] Creative Geniuses  Selecting the Best YouTube Videos for Channels for 2024</u></a></li>
</ul></div>
