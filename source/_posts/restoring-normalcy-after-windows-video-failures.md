---
title: Restoring Normalcy After Windows Video Failures
date: 2024-07-13T10:24:00.379Z
updated: 2024-07-14T10:24:00.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Normalcy After Windows Video Failures
excerpt: This Article Describes Restoring Normalcy After Windows Video Failures
keywords: Fix Windows Video Issues,Video Playback Restoration,Regain Gaming Control,Reclaim Screen Display,Resolve VIDEO Errors,Normalize System Videos,Correct Video Glitches
thumbnail: https://thmb.techidaily.com/8f13b229b4309cc607ca12c22275ed95f06f33bc5a9a2ad4f10fdb3f8f16d4fd.jpeg
---

## Restoring Normalcy After Windows Video Failures

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
<li><a href="https://win11.techidaily.com/enabling-connection-to-unreachable-windows-11-printer/"><u>Enabling Connection to Unreachable Windows 11 Printer</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-the-fascinating-realm-of-tiktok-anime-culture/"><u>In 2024, The Fascinating Realm of TikTok Anime Culture</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-top-10-windows-camera-apps-reviewed-for-2024/"><u>[Updated] The Top 10 Windows Camera Apps - Reviewed for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/slow-down-your-footage-top-video-editing-software-for-slo-mo-for-2024/"><u>Slow Down Your Footage Top Video Editing Software for Slo-Mo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-security-six-pathways-for-safe-mode/"><u>Accessing Windows 11'S Security: Six Pathways for Safe Mode</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-reversing-macos-sierra-update-to-os-x-el-capitan/"><u>2024 Approved  Reversing MacOS Sierra Update to OS X El Capitan</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-approach-for-backup-of-snippets/"><u>Methodical Approach for Backup of Snippets</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-top-10-best-gif-speed-changers/"><u>2024 Approved Top 10 Best GIF Speed Changers</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-firewall-4-methods-explored/"><u>Bypassing Disabled Windows Firewall: 4 Methods Explored</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-vanish-without-a-trace-tips-for-anonymous-instagram-live/"><u>[Updated] In 2024, Vanish Without A Trace  Tips for Anonymous Instagram Live</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-decoding-the-best-platform-for-real-time-team-collaboration-slack-vs-discord-comparison/"><u>[New] Decoding the Best Platform for Real-Time Team Collaboration  Slack Vs. Discord Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-startup-options-your-ultimate-guidebook/"><u>Decoding Windows Startup Options: Your Ultimate Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-hardware-alerts-in-windows/"><u>Troubleshooting Steps for Hardware Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-mp3s-to-audio-cds-using-imgburn/"><u>Windows Guide: Converting MP3s to Audio CDs Using ImgBurn</u></a></li>
<li><a href="https://win11.techidaily.com/best-vm-options-compatible-with-windows-11-pcs/"><u>Best VM Options Compatible With Windows 11 PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/quick-fixes-to-repair-microsoft-excel-2019-content-related-error-stellar-by-stellar-guide/"><u>Quick Fixes to Repair Microsoft Excel 2019 Content related error | Stellar</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-comprehensive-handbook-for-proficient-periscope-use/"><u>[New] Comprehensive Handbook for Proficient Periscope Use</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-how-to-speak-clearly-on-discord-via-tts/"><u>[New] How to Speak Clearly on Discord via TTS</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-app-support-issues-on-newer-windows/"><u>Techniques to Address App Support Issues on Newer Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gain-money-on-youtube-understanding-required-number-of-views-for-2024/"><u>[New] Gain Money on YouTube  Understanding Required Number of Views for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-chaos-of-mbr-errors-with-data-interpretation/"><u>Taming the Chaos of MBR Errors with Data Interpretation</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hypervisor-bsos-quick-solutions-on-winxose/"><u>Mastering Hypervisor BSOS: Quick Solutions on WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/configure-windows-apps-with-personalized-keys/"><u>Configure Windows Apps with Personalized Keys</u></a></li>
<li><a href="https://win11.techidaily.com/choco-vs-wslm-optimal-windows-software-downloader/"><u>Choco vs WSLM: Optimal Windows Software Downloader</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-10-recommended-sites-for-downloading-creative-end-credit-melodies-lawfully-for-2024/"><u>Updated 10 Recommended Sites for Downloading Creative End Credit Melodies Lawfully for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-3d-gold-text-effect-sites-on-the-web/"><u>Top 3D Gold Text Effect Sites on the Web</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-way-to-windows-11-group-policies/"><u>Streamline Your Way to Windows 11 Group Policies</u></a></li>
<li><a href="https://win11.techidaily.com/win11-control-panel-lost-find-unlisted-system-configurations/"><u>Win11 Control Panel Lost, Find Unlisted System Configurations</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-track-imei-number-of-vivo-y27-4g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Vivo Y27 4G Through Google Earth?</u></a></li>
<li><a href="https://win11.techidaily.com/cortanas-farewell-windows-future-awaits/"><u>Cortana's Farewell, Windows' Future Awaits</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-the-differences-between-standard-and-premium-youtube-viewing/"><u>In 2024, The Differences Between Standard and Premium YouTube Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-blue-screen-error/"><u>Strategies for Overcoming Blue Screen Error</u></a></li>
<li><a href="https://win11.techidaily.com/flicker-free-windows-experience-step-by-step-guide/"><u>Flicker-Free Windows Experience: Step-by-Step Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-top-10-gimbals-enhancing-dsrl-quality/"><u>[New] 2024 Approved  Top 10 Gimbals Enhancing DSRL Quality</u></a></li>
<li><a href="https://ai-topics.techidaily.com/the-power-of-ai-thumbnail-generators/"><u>The Power of AI Thumbnail Generators</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-9-methods-for-altering-windows-sound-settings/"><u>Unlock 9 Methods for Altering Windows Sound Settings</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-no-shake-guarantee-free-video-stabilizers-for-pc-and-mac-for-2024/"><u>Updated No-Shake Guarantee Free Video Stabilizers for PC and Mac for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-stream-control-showdown-is-obs-best-over-twitch-studio/"><u>[Updated] In 2024, Stream Control Showdown  Is OBS Best over Twitch Studio?</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-reactivating-a-greyed-out-secure-boot-in-bios/"><u>Steps for Reactivating a Greyed Out Secure Boot in BIOS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/altering-network-addresses-on-win11/"><u>Altering Network Addresses on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-n-series-what-you-need-to-know/"><u>Delving Into Windows N Series: What You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-the-power-of-java-sdk-on-windows-11/"><u>Unleashing the Power of Java SDK on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-using-windows-11-toolbars-effectively/"><u>The Pathway to Using Window's 11 Toolbars Effectively</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Realme C51 | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-twitters-peak-moments-top-viewers-stories/"><u>[Updated] 2024 Approved  Twitter's Peak Moments  Top Viewers' Stories</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-samsung-galaxy-a15-4g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Samsung Galaxy A15 4G FRP</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-enable-razer-recognition-by-synapse/"><u>How to Re-Enable Razer Recognition by Synapse</u></a></li>
<li><a href="https://win11.techidaily.com/feel-windows-power-with-curated-app-selection/"><u>Feel Windows Power with Curated App Selection</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-ways-to-remove-search-icon-art/"><u>Efficient Ways to Remove Search Icon Art</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-robot-generated-passwords-for-win-11-access/"><u>Bypassing Robot-Generated Passwords for Win 11 Access</u></a></li>
<li><a href="https://extra-resources.techidaily.com/discover-the-finest-free-video-player-options-for-pcmobile-tech-users/"><u>Discover the Finest Free Video Player Options for PC/Mobile Tech Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-vivo-y36-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-update-interruptions/"><u>Disabling Windows Update Interruptions</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-a-found-iphone-14-plus-drfone-by-drfone-ios/"><u>How To Unlock A Found iPhone 14 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/digging-deep-into-digital-details-step-by-step/"><u>Digging Deep Into Digital Details, Step by Step</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-motorola-razr-40-ultra-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Motorola Razr 40 Ultra?</u></a></li>
<li><a href="https://win11.techidaily.com/correct-the-dimmed-extend-option-on-windows-explorer/"><u>Correct the Dimmed Extend Option on Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-inquiry-speed-using-everythingapp/"><u>Boost PC Inquiry Speed Using EverythingApp</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-evaluating-the-impact-of-true-to-self-imagery-on-instagram-for-2024/"><u>[New] Evaluating the Impact of True-to-Self Imagery on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-how-to-recover-lost-x-configuration/"><u>Unraveling the Mystery: How to Recover Lost X Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-android-studio-efficiency-on-windows-dev-environment/"><u>Maximize Android Studio Efficiency on Windows Dev Environment</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-fixing-broken-internet-connections-6-strategies-for-windows-users/"><u>The Art of Fixing Broken Internet Connections - 6 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-old-directx-software-via-dxvk-conversion/"><u>Enriching Old DirectX Software via DXVK Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigating-the-challenges-of-itunes-on-windows-pcs/"><u>Circumnavigating the Challenges of iTunes On Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keyboard-mastery-with-typingaid/"><u>Swift Keyboard Mastery with TypingAid</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unleash-the-power-of-pause-tips-for-instas-next-viral-slow-motion-reels/"><u>[Updated] In 2024, Unleash the Power of Pause  Tips for Insta's Next Viral Slow-Motion Reels</u></a></li>
</ul></div>
