---
title: Addressing DXGI Failures on Windows 10/11
date: 2024-06-25T11:27:16.536Z
updated: 2024-06-26T11:27:16.536Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing DXGI Failures on Windows 10/11
excerpt: This Article Describes Addressing DXGI Failures on Windows 10/11
keywords: Win10DXGIFailure,Win11DXGICorrupt,Win10GraphicsError,DXGIWindows10Fail,Windows10DXGIDefficiency,FixWin11DXGIA,10/11DXGITroubleshoot
thumbnail: https://thmb.techidaily.com/a6f140ff4ddda64bd14cec3cab639274aa642e4bb60e8fa6d0c6031cee3c6ed0.jpg
---

## Addressing DXGI Failures on Windows 10/11

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
5. Repeat the previous step for the **Antialiasing – Transparency**, **FXAA**, and **Gamma** correction options.
6. Then select **Apply** to set the new graphics options.

 You can also disable Antialiasing for AMD GPUs within the Radeon software. Check out our guide about [tweaking AMD Radeon settings](https://www.makeuseof.com/amd-radeon-settings-gaming-performance-windows/) for further details about how to turn off Antialiasing there.

## 3\. Turn Off the NVIDIA ShadowPlay (Overlay) Feature

 GeForce Experience’s ShadowPlay feature for game recording can place a notable burden on GPUs. So, we recommend that you turn that feature off for the sake of fixing the DXGI\_ERROR\_DEVICE\_REMOVED error if it’s enabled. You can turn off NVIDIA ShadowPlay in GeForce Experience like this:

1. To open GeForce Experience, right-click the NVIDIA system tray icon and select that software on the context menu.
2. Then click on the **cog** (Settings) button to access further options.  
![The Settings button in GeForce Experience.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/settings-button.jpg)
3. Toggle off the **In-Game Overlay** option.  
![The in-game overlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/in-game-overlay.jpg)
4. Exit the GeForce Experience software and try playing your games with ShadowPlay disabled.

## 4\. Turn Off the DLSS Graphics Setting

 Some players confirm disabling DLSS graphics settings in games fixes the DXGI\_ERROR\_DEVICE\_REMOVED error. If the affected game doesn’t always crash when you start it, try turning off its **DLSS** option. You can usually find that setting within a game’s video or graphics tab options.

![A DLSS option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dlss-option.jpg)

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
6. If you don’t want Bing Bar, uncheck the **Install the Bing Bar** option.
7. Select **Next** to install DirectX components.

## Try Some Generic Windows Fixes

 If nothing has worked yet, here are some generic fixes for GPU issues.

### Update the Graphics Driver for Your GPU

 The DXGI\_ERROR\_DEVICE\_REMOVED error message clearly says that this issue is often the result of a graphics driver crash. It also suggests users update their GPU graphics drivers to remedy the error. You can update your PC’s graphics driver with the methods covered in this guide to [updating a GPU’s driver in Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Cleanly Reinstall the Graphics Driver

 Cleanly reinstalling a graphics driver is a variation of the previous potential resolution for updating it. This involves completely uninstalling the current GPU driver and then installing the latest one. We recommend thoroughly uninstalling the graphics driver with the DDU software before installing the new one. You can apply this solution as covered in our [article about reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/).

![uninstall graphics drivers DDU](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-graphics-drivers-ddu.jpg)

##

### Run a Windows Memory Diagnostic Check

 Some users have said they needed to replace faulty RAM modules to resolve DXGI\_ERROR\_DEVICE\_REMOVED. So, try running a Windows Memory Diagnostic check if other resolutions here don’t work for you. Our guide to [resolving RAM issues with Windows Memory Diagnostic](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) includes full instructions for utilizing that tool.

![The Windows Memory Diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-windows-memory-diagnostic-tool.jpg)

 If that tool detects issues, removing the faulty RAM module from your PC will probably resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. However, you’ll still need enough RAM for the game. If removing RAM leaves insufficient system memory for the game, purchase and add a new RAM module to your PC.

## Enjoy Your Windows Games Again

 The potential fixes above have worked for many players who’ve needed to resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. That doesn’t necessarily mean they’re guaranteed fixes, but one will probably resolve that issue on your PC. Then you can play the Windows 11/10 games that error crashed without further issues.

 If the solutions above don’t resolve the DXGI\_ERROR\_DEVICE\_REMOVED error on your PC, there could be an issue with your graphics card. Persistent GPU crashing is one of the signs that it’s time to upgrade your graphics card.

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/experts-choice-10-error-finder-apps-for-pc/"><u>Expert's Choice: 10 Error Finder Apps for PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-a-sleeker-system-auto-delete-files-on-windows/"><u>The Key to a Sleeker System: Auto-Delete Files on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-photo-corrections-stripping-backdrops/"><u>Expert Advice on Photo Corrections: Stripping Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-se-2020-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone SE (2020) After Forgetting the Passcode?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-how-to-assemble-a-personalized-youtube-music-list/"><u>[New] How to Assemble a Personalized YouTube Music List</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-13-mini-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 13 mini and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-perfecting-your-home-studios-auditory-experience-a-2023-guide/"><u>New Perfecting Your Home Studios Auditory Experience (A 2023 Guide)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-biz-cloud-storage-excellence/"><u>[New] Leading Biz Cloud Storage Excellence</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/go-incognito-your-step-by-step-instagram-live-guide-for-2024/"><u>Go Incognito  Your Step-by-Step Instagram Live Guide for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-swift-playback-on-instagram-videos-mobiledesktop-for-2024/"><u>[New] Swift Playback on Instagram Videos (Mobile/Desktop) for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pioneering-tomorrow-visionary-developments-in-vr/"><u>[Updated] Pioneering Tomorrow  Visionary Developments in VR</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>