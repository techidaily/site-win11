---
title: Dealing with Video Reset Error on Windows Systems
date: 2024-07-13T10:01:23.311Z
updated: 2024-07-14T10:01:23.311Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Video Reset Error on Windows Systems
excerpt: This Article Describes Dealing with Video Reset Error on Windows Systems
keywords: Fixing Win Reset Video Error,Solve Video Glitches in Windows,Overcoming Video Reset Issue,Troubleshoot Video Playback Crash,Remedy Video Freeze on PC,Resolving Disrupted Windows Media,Unblocking Stuck Video Stream
thumbnail: https://thmb.techidaily.com/310914a9091489c802247fe59fe85918c611bccb81eaf0425c85e3bbe8a07c5a.jpg
---

## Dealing with Video Reset Error on Windows Systems

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
<li><a href="https://win11.techidaily.com/securely-manage-local-drive-space-in-win11-without-loss-of-files-max-156-chars/"><u>Securely Manage Local Drive Space in Win11 Without Loss of Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-gear-use-windows-widgets-for-efficiency/"><u>Streamlining Your Gear Use: Windows Widgets for Efficiency</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-engage-and-captivate-viewers-ultimate-tips-for-cutting-edge-youtube-edits/"><u>In 2024, Engage and Captivate Viewers  Ultimate Tips for Cutting-Edge Youtube Edits</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-your-unboxing-channel-a-complete-how-to/"><u>Elevating Your Unboxing Channel  A Complete How-To</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-honor-magic-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/turning-off-google-chrome-alerts-windows-edition/"><u>Turning Off Google Chrome Alerts, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-directx-update-failure-in-windows-systems/"><u>Overcoming DirectX Update Failure in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-window-bar-transparency-in-win11/"><u>A Step-by-Step for Window Bar Transparency in Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/breakthrough-practices-in-youtube-video-saving/"><u>Breakthrough Practices in YouTube Video Saving</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-prolific-mobile-video-makers-iphone-and-android/"><u>[New] Prolific Mobile Video Makers (iPhone & Android)</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-connection-speed-clearing-steam-dns-in-windows/"><u>Revamping Connection Speed: Clearing Steam DNS in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-navigating-post-omegle-ban-a-pathway-back-into-conversation/"><u>2024 Approved Navigating Post-Omegle Ban A Pathway Back Into Conversation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-saving-your-whatsapp-chat-history-with-confidence/"><u>[New] 2024 Approved  Saving Your WhatsApp Chat History with Confidence</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-craft-an-invisible-taskbar-on-windows-11/"><u>Steps to Craft an Invisible Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-couldnt-load-page-in-windows-marketplace/"><u>Troubleshooting 'Couldn't Load Page' In Windows Marketplace</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-chromebooks-best-capture-tools-no-cost/"><u>[New] In 2024, Chromebook's Best Capture Tools (No Cost)</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-auto-opens-on-microsofts-marketplace-app/"><u>Ceasing Auto-Opens on Microsoft's Marketplace App</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/transform-your-tech-skills-mastering-screen-capture-in-macos-for-2024/"><u>Transform Your Tech Skills  Mastering Screen Capture in macOS for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-guide-on-unlocking-iphone-12-pro-max-with-a-broken-screen-by-drfone-ios/"><u>Complete Guide on Unlocking iPhone 12 Pro Max with a Broken Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winerror-740-resolving-operation-needs-promotion-in-windows-os/"><u>Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/budget-friendly-video-settings-for-low-end-systems/"><u>Budget-Friendly Video Settings for Low-End Systems</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-out-windows-11-drag-and-drop-issues/"><u>Smooth Out Windows 11 Drag-and-Drop Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permission-barriers-in-windows-updates/"><u>Overcoming Permission Barriers in Windows Updates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-underscrutinized-to-unforgettable-bio-hacks-for-love-success/"><u>[New] From Underscrutinized to Unforgettable  Bio Hacks for Love Success</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-file-navigation-on-windows-implementing-movecopy-actions/"><u>Optimizing File Navigation on Windows: Implementing 'Move'/'Copy' Actions</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-installation-mishaps-on-windows-10-and-11/"><u>Repairing Installation Mishaps on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-ascertaining-your-pcs-intel-core-gen/"><u>Techniques for Ascertaining Your PC's Intel Core Gen</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-network-defenses-with-5-tweaks-to-firewall/"><u>Revitalizing Network Defenses with 5 Tweaks to Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-insufficient-rights-for-program-removal-in-win-11/"><u>Overcoming Insufficient Rights for Program Removal in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-protection-enable-windows-11s-controlling-access/"><u>Setting Up Protection: Enable Windows 11’S Controlling Access</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-how-can-you-use-clownfish-voice-changer-on-discord-fortnite-skype/"><u>2024 Approved How Can You Use Clownfish Voice Changer on Discord/ Fortnite/ Skype</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-asus-rog-phone-7-ultimate-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-expert-tips-on-muting-audios-from-visual-sources-for-enhanced-focus/"><u>New 2024 Approved Expert Tips on Muting Audios From Visual Sources for Enhanced Focus</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-essential-upgrades-in-gaming-gloves-for-vr/"><u>[New] In 2024, Essential Upgrades in Gaming Gloves for VR</u></a></li>
<li><a href="https://screen-capture.techidaily.com/audiovisual-elevation-leading-high-definition-hdmi-21-displays-for-2024/"><u>Audiovisual Elevation  Leading High-Definition (HDMI 2.1) Displays for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hidden-wi-fi-in-the-realm-of-windows-11/"><u>Resurrecting Hidden Wi-Fi in the Realm of Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-mastering-sound-a-comprehensive-guide-to-normalizing-audio-in-multimedia-content/"><u>In 2024, Mastering Sound A Comprehensive Guide to Normalizing Audio in Multimedia Content</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-hardware-requirements-for-games/"><u>Resolving Windows Hardware Requirements for Games</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-initial-load-issues-in-lol/"><u>Overcoming Initial Load Issues in LOL</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-inaccessible-pin-unlock-routine-in-windows-11/"><u>Resetting Inaccessible Pin Unlock Routine in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-gaps-in-systems-startup-list/"><u>Troubleshooting Gaps in System's Startup List</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-technique-for-mkv-to-mp4-change/"><u>Step-by-Step Windows Technique for MKV to MP4 Change</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-void-seven-strategies-for-stabilizing-obs-studio-link/"><u>Avoiding the Void: Seven Strategies for Stabilizing OBS Studio Link</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-discover-the-art-of-live-discord-recording/"><u>2024 Approved  Discover the Art of Live Discord Recording</u></a></li>
</ul></div>
