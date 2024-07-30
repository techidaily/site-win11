---
title: Avoidance of DXGI_Error Post Device Disconnect
date: 2024-07-29T15:47:37.476Z
updated: 2024-07-30T15:47:37.476Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoidance of DXGI_Error Post Device Disconnect
excerpt: This Article Describes Avoidance of DXGI_Error Post Device Disconnect
keywords: Device Disconnect Errors,Avoiding DXGI Issues,GPU Connection Failures,Preventing Graphic Glitches,Secure DXGI Operations,Minimize Graphics Disconnect,Stable DXGI Management
thumbnail: https://thmb.techidaily.com/265c34a9ea730206243923e3674c50a6adee1664031b51ad4dc762eeccdfd025.jpg
---

## Avoidance of DXGI_Error Post Device Disconnect

 The DXGI\_ERROR\_DEVICE\_REMOVED error sometimes occurs when users try to start certain Windows games or when playing them. Players have reported this error to occur for games like FIFA 2022, Prepar3D, Need for Speed Rivals, Apex, and Crysis 3, among others. This DirectX error message says, “DirectX function ‘GetDeviceRemovedReason’ failed with DXGI\_ERROR\_DEVICE\_REMOVED.”

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.

## 1\. Modify the GraphicsDriver Registry Key

 Modifying the GraphicsDriver registry key is the most widely confirmed potential fix for the DXGI\_ERROR\_DEVICE\_REMOVED error. This resolution involves adding a TDR (Timeout Detection and Recovery) DWORD to the GraphicsDrivers key. Setting that DWORD to 0 disables TDR detection. You can apply this registry edit as follows:

1. Press **Win + S**, type **regedit** inside the search tool, and click **Registry Editor**.
2. Next, navigate to the GraphicsDrivers key at this registry location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
3. Right-click on **GraphicsDrivers** and select the context menu’s **New** and **DWORD** options.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-new-key-options.jpg)
4. Type in a **TdrLevel** title for the DWORD.
5. Double-click on **TdrLevel** to activate its **Value** box.
6. The DWORD’s value should already be set to zero by default. However, change that value to **0** if it’s not and click **OK**.  
![The TrdLevel DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/trdlevel-dword.jpg)
7. Now close Registry Editor, click **Start**, and select **Power** \> **Restart**.

 A few users also confirm deleting a TdrDelay QWORD in the same key can also work for fixing the DXGI\_ERROR\_DEVICE\_REMOVED error. If you can see a TdrDelay QWORD in the GraphicsDrivers key, try deleting it as well. To do so, right-click the **TdrDelay** QWORD and select **Delete**. Select **Yes** to confirm the erasure.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## 2\. Disable the Antialiasing Setting

 Antialiasing is a graphic setting that smoothens jagged lines when enabled. However, this graphical effect can sometimes cause crashing issues like the DXGI\_ERROR\_DEVICE\_REMOVED error. This is how you can turn off Antialiasing within the NVIDIA Control Panel:

1. Right-click on the NVIDIA logo in the system tray area and select **NVIDIA Control Panel**.  
![The NVIDIA Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-geforce-experience.jpg)
2. Click the **Manage 3D** settings navigation option within the sidebar.
3. Select NVIDIA Control Panel’s **Global Settings** tab.
4. Next, click the **Antialiasing – Mode** option and select **Off**.  
![The Antialising - Mode setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antialiasing.jpg)
5. Repeat the previous step for the **Antialiasing – Transparency**, **FXAA**, and **Gamma** correction options.
6. Then select **Apply** to set the new graphics options.

 You can also disable Antialiasing for AMD GPUs within the Radeon software. Check out our guide about [tweaking AMD Radeon settings](https://www.makeuseof.com/amd-radeon-settings-gaming-performance-windows/) for further details about how to turn off Antialiasing there.

## 3\. Turn Off the NVIDIA ShadowPlay (Overlay) Feature

 GeForce Experience’s ShadowPlay feature for game recording can place a notable burden on GPUs. So, we recommend that you turn that feature off for the sake of fixing the DXGI\_ERROR\_DEVICE\_REMOVED error if it’s enabled. You can turn off NVIDIA ShadowPlay in GeForce Experience like this:

1. To open GeForce Experience, right-click the NVIDIA system tray icon and select that software on the context menu.
2. Then click on the **cog** (Settings) button to access further options.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![The Settings button in GeForce Experience.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/settings-button.jpg)
3. Toggle off the **In-Game Overlay** option.  
![The in-game overlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/in-game-overlay.jpg)
4. Exit the GeForce Experience software and try playing your games with ShadowPlay disabled.

## 4\. Turn Off the DLSS Graphics Setting

 Some players confirm disabling DLSS graphics settings in games fixes the DXGI\_ERROR\_DEVICE\_REMOVED error. If the affected game doesn’t always crash when you start it, try turning off its **DLSS** option. You can usually find that setting within a game’s video or graphics tab options.

![A DLSS option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dlss-option.jpg)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Undo Overclocking

 Have you done any GPU or processor overclocking on your PC? If you have, that overclocking could have caused the DXGI\_ERROR\_DEVICE\_REMOVED error. Undo the overclocking with the software you applied it with. Or you can undo overclocking by [resetting the BIOS](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) (Basic Input Output System).

![MSI Afterburner homepage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msi-afterburner.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Run the DirectX Web Installer

 DXGI\_ERROR\_DEVICE\_REMOVED can occur because of DirectX issues. For example, some required DirectX components might be missing on your PC. You can address that by downloading and running the DirectX Web Installer like this:

1. Open this [DirectX download page](https://www.microsoft.com/en-us/download/details.aspx?id=35).
2. Click on the orange **Download** button to obtain a DirectX setup file.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Download button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-button.jpg)
3. To view File Explorer, hold the **Windows** logo button and press **E**. Then open the folder containing the Microsoft DirectX End-User Runtime package.
4. Double-click **dxwebsetup.exe** to bring up an Installing Microsoft (R) DirectX (R) window.
5. Click **I accept the agreement** and **Next**.  
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
![I accept the agreement radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/i-accept-the-radio-button.jpg)
6. If you don’t want Bing Bar, uncheck the **Install the Bing Bar** option.
7. Select **Next** to install DirectX components.

## Try Some Generic Windows Fixes

 If nothing has worked yet, here are some generic fixes for GPU issues.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
### Update the Graphics Driver for Your GPU

 The DXGI\_ERROR\_DEVICE\_REMOVED error message clearly says that this issue is often the result of a graphics driver crash. It also suggests users update their GPU graphics drivers to remedy the error. You can update your PC’s graphics driver with the methods covered in this guide to [updating a GPU’s driver in Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Cleanly Reinstall the Graphics Driver

 Cleanly reinstalling a graphics driver is a variation of the previous potential resolution for updating it. This involves completely uninstalling the current GPU driver and then installing the latest one. We recommend thoroughly uninstalling the graphics driver with the DDU software before installing the new one. You can apply this solution as covered in our [article about reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![uninstall graphics drivers DDU](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-graphics-drivers-ddu.jpg)

##

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
### Run a Windows Memory Diagnostic Check

 Some users have said they needed to replace faulty RAM modules to resolve DXGI\_ERROR\_DEVICE\_REMOVED. So, try running a Windows Memory Diagnostic check if other resolutions here don’t work for you. Our guide to [resolving RAM issues with Windows Memory Diagnostic](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) includes full instructions for utilizing that tool.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Memory Diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-windows-memory-diagnostic-tool.jpg)

 If that tool detects issues, removing the faulty RAM module from your PC will probably resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. However, you’ll still need enough RAM for the game. If removing RAM leaves insufficient system memory for the game, purchase and add a new RAM module to your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy Your Windows Games Again

 The potential fixes above have worked for many players who’ve needed to resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. That doesn’t necessarily mean they’re guaranteed fixes, but one will probably resolve that issue on your PC. Then you can play the Windows 11/10 games that error crashed without further issues.

 If the solutions above don’t resolve the DXGI\_ERROR\_DEVICE\_REMOVED error on your PC, there could be an issue with your graphics card. Persistent GPU crashing is one of the signs that it’s time to upgrade your graphics card.

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-2024-approved-supreme-graphics-power-for-4k-gamers-only/"><u>[New] 2024 Approved  Supreme Graphics Power  For 4K Gamers Only</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-add-border-to-instagram-photos-with-best-apps-for-2024/"><u>[New] How to Add Border to Instagram Photos with Best Apps for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-live-broadcast-essentials-for-macos-users-on-mixer/"><u>[Updated] Live Broadcast Essentials for macOS Users on Mixer</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mac-users-mastering-mp3-conversion-from-youtube-for-2024/"><u>[Updated] Mac Users  Mastering MP3 Conversion From YouTube for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-terrariums-topography-selecting-prime-maps-for-2024/"><u>[Updated] Terrarium's Topography  Selecting Prime Maps for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-revel-in-these-14-enthralling-text-based-movements/"><u>2024 Approved  Revel in These 14 Enthralling Text-Based Movements</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/acoustic-imprinting-pc-noises-logged-for-2024/"><u>Acoustic Imprinting  PC Noises Logged for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/best-8-lite-simulations-playing-android-on-desktop/"><u>Best 8 Lite Simulations: Playing Android on Desktop</u></a></li>
<li><a href="https://fox-http.techidaily.com/boost-your-photo-game-on-android-smartphones/"><u>Boost Your Photo Game on Android Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-uac-alerts-a-windows-screenshot-guide/"><u>Capturing UAC Alerts: A Windows ScreenShot Guide</u></a></li>
<li><a href="https://win11.techidaily.com/cross-examining-microsoft-vs-standard-windows-user-accounts/"><u>Cross-Examining Microsoft vs Standard Windows User Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/displaying-networked-storage-options-on-screen/"><u>Displaying Networked Storage Options on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/easy-deactivation-four-proven-methods-to-cut-off-users-in-win11/"><u>Easy Deactivation: Four Proven Methods to Cut Off Users in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-address-winget-malfunctioning-in-windows-11/"><u>Easy Steps to Address Winget Malfunctioning in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/end-live-recording-mode-immediately-in-qt-app/"><u>End Live Recording Mode Immediately in QT App</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-powertoys-on-win11/"><u>Enhancing User Experience: PowerToys on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wireless-speaker-quality-in-win11-os/"><u>Enhancing Wireless Speaker Quality in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-text-messaging-with-emoji-15-on-windows-11/"><u>Enrich Text Messaging with Emoji 15 on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-oneplus-open-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your OnePlus Open Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-see-someones-location-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>How to See Someones Location on Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-nokia-c12-plus-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Nokia C12 Plus to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-luminosity-a-comprehensive-hdr-guide-for-windows-11-users/"><u>Leveraging Luminosity: A Comprehensive HDR Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/managing-out-of-memory-alerts-in-fantasy-school-of-wizardry-game/"><u>Managing Out-of-Memory Alerts in Fantasy School of Wizardry Game</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-0xc000003e-application-startup-troubleshooting/"><u>Mastering 0xC000003E Application Startup Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ntfs-enablingdisabling-file-compression/"><u>Mastering NTFS: Enabling/Disabling File Compression</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-virtual-boxs-capabilities-with-v70-on-windows-11-systems/"><u>Maximize Virtual Box's Capabilities with v7.0 on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-discord-search-on-windowed-devices/"><u>Optimizing Discord Search on Windowed Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-initial-load-issues-in-lol/"><u>Overcoming Initial Load Issues in LOL</u></a></li>
<li><a href="https://fox-http.techidaily.com/photo-fusion-mastery-windows-users-guide-for-2024/"><u>Photo Fusion Mastery  Windows Users Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-synapse-glitches-in-1011-windows-edition/"><u>Repairing Synapse Glitches in 10/11 Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-outlook-folder-unreadable-error-steps-for-personal-computers/"><u>Resolve 'Outlook Folder Unreadable' Error: Steps for Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-network-defenses-with-5-tweaks-to-firewall/"><u>Revitalizing Network Defenses with 5 Tweaks to Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/showcasing-taskmanager-preeminent-style/"><u>Showcasing TaskManager Preeminent Style</u></a></li>
<li><a href="https://techidaily.com/sign-word-2013-online-with-digisigner-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2013 Online with DigiSigner</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-craft-an-invisible-taskbar-on-windows-11/"><u>Steps to Craft an Invisible Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-overcoming-steam-file-locks/"><u>Swift Strategies for Overcoming Steam File Locks</u></a></li>
<li><a href="https://win11.techidaily.com/swift-surfing-steps-for-windows-based-network-speed-verification/"><u>Swift Surfing: Steps for Windows-Based Network Speed Verification</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-essential-2023-social-media-video-exploration-for-2024/"><u>The Essential 2023 Social Media Video Exploration for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweeted-trailblazers-cutting-edge-strategies-to-save-tweets-on-screen/"><u>Tweeted Trailblazers  Cutting-Edge Strategies to Save Tweets on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unmasking-the-undisclosed-instructions-for-accessing-windows-personal-character-console/"><u>Unmasking the Undisclosed: Instructions for Accessing Windows’ Personal Character Console</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-xiaomi-redmi-13c-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Xiaomi Redmi 13C Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pathways-three-keys-to-gaming-files/"><u>Windows Pathways: Three Keys to Gaming Files</u></a></li>
</ul></div>
