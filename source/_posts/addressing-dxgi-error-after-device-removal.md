---
title: Addressing DXGI Error After Device Removal
date: 2024-08-15T23:18:31.984Z
updated: 2024-08-16T23:18:31.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing DXGI Error After Device Removal
excerpt: This Article Describes Addressing DXGI Error After Device Removal
keywords: DXGI Post-Removal Issues,Removing Devices & Errors,Graphics Driver Troubleshooting,Device Disconnection Glitches,Xbox Error Fixing,Visual Debugging Tips,GPU Reconnect Challenges
thumbnail: https://thmb.techidaily.com/a33821f7d1add97134f0556ceb5947dead1c89e2bf8e16eab36445ca53259ede.jpg
---

## Addressing DXGI Error After Device Removal

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

## 2\. Disable the Antialiasing Setting

 Antialiasing is a graphic setting that smoothens jagged lines when enabled. However, this graphical effect can sometimes cause crashing issues like the DXGI\_ERROR\_DEVICE\_REMOVED error. This is how you can turn off Antialiasing within the NVIDIA Control Panel:

1. Right-click on the NVIDIA logo in the system tray area and select **NVIDIA Control Panel**.  
![The NVIDIA Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-geforce-experience.jpg)
2. Click the **Manage 3D** settings navigation option within the sidebar.
3. Select NVIDIA Control Panel’s **Global Settings** tab.
4. Next, click the **Antialiasing – Mode** option and select **Off**.  
![The Antialising - Mode setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antialiasing.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
5. Repeat the previous step for the **Antialiasing – Transparency**, **FXAA**, and **Gamma** correction options.
6. Then select **Apply** to set the new graphics options.

 You can also disable Antialiasing for AMD GPUs within the Radeon software. Check out our guide about [tweaking AMD Radeon settings](https://www.makeuseof.com/amd-radeon-settings-gaming-performance-windows/) for further details about how to turn off Antialiasing there.

## 3\. Turn Off the NVIDIA ShadowPlay (Overlay) Feature

 GeForce Experience’s ShadowPlay feature for game recording can place a notable burden on GPUs. So, we recommend that you turn that feature off for the sake of fixing the DXGI\_ERROR\_DEVICE\_REMOVED error if it’s enabled. You can turn off NVIDIA ShadowPlay in GeForce Experience like this:

1. To open GeForce Experience, right-click the NVIDIA system tray icon and select that software on the context menu.
2. Then click on the **cog** (Settings) button to access further options.  
![The Settings button in GeForce Experience.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/settings-button.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
3. Toggle off the **In-Game Overlay** option.  
![The in-game overlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/in-game-overlay.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
4. Exit the GeForce Experience software and try playing your games with ShadowPlay disabled.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off the DLSS Graphics Setting

 Some players confirm disabling DLSS graphics settings in games fixes the DXGI\_ERROR\_DEVICE\_REMOVED error. If the affected game doesn’t always crash when you start it, try turning off its **DLSS** option. You can usually find that setting within a game’s video or graphics tab options.

![A DLSS option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dlss-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 5\. Undo Overclocking

 Have you done any GPU or processor overclocking on your PC? If you have, that overclocking could have caused the DXGI\_ERROR\_DEVICE\_REMOVED error. Undo the overclocking with the software you applied it with. Or you can undo overclocking by [resetting the BIOS](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) (Basic Input Output System).

![MSI Afterburner homepage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msi-afterburner.jpg)

## 6\. Run the DirectX Web Installer

 DXGI\_ERROR\_DEVICE\_REMOVED can occur because of DirectX issues. For example, some required DirectX components might be missing on your PC. You can address that by downloading and running the DirectX Web Installer like this:

1. Open this [DirectX download page](https://www.microsoft.com/en-us/download/details.aspx?id=35).
2. Click on the orange **Download** button to obtain a DirectX setup file.  
![The Download button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-button.jpg)
3. To view File Explorer, hold the **Windows** logo button and press **E**. Then open the folder containing the Microsoft DirectX End-User Runtime package.
4. Double-click **dxwebsetup.exe** to bring up an Installing Microsoft (R) DirectX (R) window.
5. Click **I accept the agreement** and **Next**.  
![I accept the agreement radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/i-accept-the-radio-button.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
6. If you don’t want Bing Bar, uncheck the **Install the Bing Bar** option.
7. Select **Next** to install DirectX components.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## Try Some Generic Windows Fixes

 If nothing has worked yet, here are some generic fixes for GPU issues.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Update the Graphics Driver for Your GPU

 The DXGI\_ERROR\_DEVICE\_REMOVED error message clearly says that this issue is often the result of a graphics driver crash. It also suggests users update their GPU graphics drivers to remedy the error. You can update your PC’s graphics driver with the methods covered in this guide to [updating a GPU’s driver in Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Cleanly Reinstall the Graphics Driver

 Cleanly reinstalling a graphics driver is a variation of the previous potential resolution for updating it. This involves completely uninstalling the current GPU driver and then installing the latest one. We recommend thoroughly uninstalling the graphics driver with the DDU software before installing the new one. You can apply this solution as covered in our [article about reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/).

![uninstall graphics drivers DDU](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-graphics-drivers-ddu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

##

### Run a Windows Memory Diagnostic Check

 Some users have said they needed to replace faulty RAM modules to resolve DXGI\_ERROR\_DEVICE\_REMOVED. So, try running a Windows Memory Diagnostic check if other resolutions here don’t work for you. Our guide to [resolving RAM issues with Windows Memory Diagnostic](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) includes full instructions for utilizing that tool.

![The Windows Memory Diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-windows-memory-diagnostic-tool.jpg)

 If that tool detects issues, removing the faulty RAM module from your PC will probably resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. However, you’ll still need enough RAM for the game. If removing RAM leaves insufficient system memory for the game, purchase and add a new RAM module to your PC.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-3-unconventional-tactics-for-subscriber-growth/"><u>[New] 2024 Approved  3 Unconventional Tactics for Subscriber Growth</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-delving-into-t-series-revenue-generation-on-video-platforms/"><u>[New] In 2024, Delving Into T-Series' Revenue Generation on Video Platforms</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-vlc-recorder-functionality-check/"><u>[New] In 2024, VLC Recorder  Functionality Check</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-id-video-overview-length-aspect-ratio-frame-rate/"><u>[Updated] Facebook ID Video Overview  Length, Aspect Ratio, Frame Rate</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-essential-tips-installing-vrecorder/"><u>[Updated] In 2024, Essential Tips  Installing VRecorder</u></a></li>
<li><a href="https://win11.techidaily.com/5-effective-strategies-to-fix-rpc-issues-in-win/"><u>5 Effective Strategies to Fix RPC Issues in Win</u></a></li>
<li><a href="https://win11.techidaily.com/antimalware-resource-hog-turn-it-off-for-better-performance/"><u>Antimalware Resource Hog: Turn It Off for Better Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-your-windows-11-screen/"><u>Breathing Life Into Your Windows 11 Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/change-background-on-playstation-5-console/"><u>Change Background on PlayStation 5 Console</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/chromebook-tips-capturing-high-quality-webcams/"><u>Chromebook Tips  Capturing High-Quality Webcams</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-a-boundless-chatbot-experience-install-and-customize-a-freedomgpt-powered-alternative-on-windows/"><u>Crafting a Boundless Chatbot Experience: Install and Customize a FreedomGPT-Powered Alternative on Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-science-of-openai-ai/"><u>Discover the Science of OpenAI AI</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-windows-11s-voice-recorder-usability-via-shortcut-guide/"><u>Elevating Windows 11'S Voice Recorder Usability via Shortcut Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/explore-the-most-effective-zoom-screen-recorders-for-2024/"><u>Explore the Most Effective Zoom Screen Recorders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719286727564-gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-autonomous-command-line-openings/"><u>How to Disable Autonomous Command Line Openings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80072f30-on-windows/"><u>How to Fix the Microsoft Store Error 0X80072F30 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-absence-of-dxgidll-in-windows-11/"><u>How to Rectify the Absence of Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-nokia-g22-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Nokia G22 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-seamless-tutorial-for-image-background-cleanup-on-canva/"><u>In 2024, The Seamless Tutorial for Image Background Cleanup on Canva</u></a></li>
<li><a href="https://win11.techidaily.com/inside-the-windows-world-crafting-and-examining-system-data/"><u>Inside the Windows World: Crafting and Examining System Data</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-eradicating-predominant-anomalies-with-anydesk-on-windows/"><u>Key Techniques: Eradicating Predominant Anomalies with AnyDesk on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/linux-perfection-bypassing-wsl/"><u>Linux Perfection: Bypassing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-wsl-registration-failure-with-error-x80370102/"><u>Mastering The Fix: WSL Registration Failure with Error X80370102</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-complex-windows-11-install-issues/"><u>Navigating Through Complex Windows 11 Install Issues</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-keyboard-method-to-resize-programs/"><u>Navigating Windows 11'S Keyboard Method to Resize Programs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/quick-start-applying-discord-spoilers-correctly/"><u>Quick Start  Applying Discord Spoilers Correctly</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-windows-11-workspace-in-minutes/"><u>Tidy Up Windows 11 Workspace in Minutes</u></a></li>
<li><a href="https://win11.techidaily.com/top-notch-windows-11-skins-no-one-knows/"><u>Top-Notch Windows 11 Skins No One Knows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-approach-to-sound-channel-division/"><u>Understanding Windows’ Approach to Sound Channel Division</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unveiling-past-images-3-approaches-for-fb-reverse-search/"><u>Unveiling Past Images  3 Approaches for FB Reverse Search</u></a></li>
</ul></div>
