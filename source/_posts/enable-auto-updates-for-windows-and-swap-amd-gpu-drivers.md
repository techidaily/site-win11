---
title: Enable Auto-Updates for Windows & Swap AMD GPU Drivers
date: 2024-11-03T16:50:53.933Z
updated: 2024-11-07T19:04:46.009Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Auto-Updates for Windows & Swap AMD GPU Drivers
excerpt: This Article Describes Enable Auto-Updates for Windows & Swap AMD GPU Drivers
keywords: Windows Auto-Update,Swap AMD GPU,Update AMD GPU,Drivers Upgrade,Windows Driver Update,AMD GPU Switcher,Enable GPU Update
thumbnail: https://thmb.techidaily.com/5a836c04a4d923a2e47e122afc97ffb5e93afa98d18b4563b5a8924a658295ed.jpg
---

## Enable Auto-Updates for Windows & Swap AMD GPU Drivers

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.

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
<li><a href="https://youtube-lab.techidaily.com/he-art-of-adding-emojis-to-youtube-comments/"><u>[New] The Art of Adding Emojis to YouTube Comments</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-craft-a-unique-channel-look-for-free/"><u>[Updated] 2024 Approved Craft a Unique Channel Look for Free</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-swift-solution-tweeting-videos-not-functioning-chrome/"><u>[Updated] In 2024, Swift Solution Tweeting Videos Not Functioning Chrome</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bringing-out-the-best-advanced-color-correction-in-gopro-for-2024/"><u>Bringing Out the Best Advanced Color Correction in GoPro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/discover-blank-filespace-and-delete-them-using-windows-tools/"><u>Discover Blank Filespace and Delete Them Using Windows Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elevate-your-gaming-experience-mastering-steam-recordings/"><u>Elevate Your Gaming Experience - Mastering Steam Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-benefits-of-dxvk-on-your-windows-pc/"><u>Exploring the Benefits of DXVK on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fix-a-non-installable-windows-store-app/"><u>Fix a Non-Installable Windows Store App</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-mini-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 mini to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-hot-30-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Infinix Hot 30 5G Phone with Broken Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/master-list-the-finest-10-pixel-archives-at-zero-cost/"><u>Master List The Finest 10 Pixel Archives at Zero Cost</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-new-wave-with-copilot-key-for-windows-11-enthusiasts/"><u>Navigating the New Wave with Copilot Key for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-windows-taskbar-thumbnail-failures/"><u>Remedy Windows Taskbar Thumbnail Failures</u></a></li>
<li><a href="https://win11.techidaily.com/securely-ending-non-registered-users-in-windows/"><u>Securely Ending Non-Registered Users in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-file-explorer-by-omitting-onedrive/"><u>Streamlining Your File Explorer by Omitting OneDrive</u></a></li>
<li><a href="https://win-blog.techidaily.com/the-ultimate-guide-to-overcoming-halo-infinites-black-screen-problem/"><u>The Ultimate Guide to Overcoming Halo Infinite's Black Screen Problem</u></a></li>
<li><a href="https://win11.techidaily.com/win11-performance-reducing-boot-time/"><u>Win11 Performance: Reducing Boot Time</u></a></li>
</ul></div>

