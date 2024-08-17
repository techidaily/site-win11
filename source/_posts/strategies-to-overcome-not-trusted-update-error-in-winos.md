---
title: Strategies to Overcome Not Trusted Update Error in WinOS
date: 2024-08-15T23:43:13.442Z
updated: 2024-08-16T23:43:13.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Overcome Not Trusted Update Error in WinOS
excerpt: This Article Describes Strategies to Overcome Not Trusted Update Error in WinOS
keywords: Windows Trust Issues,Fixing OS Updates,WinOS Not Updated Correctly,Overcoming Update Errors,Secure OS Update,Trusted Windows Update,Resolving OS Trust Error
thumbnail: https://thmb.techidaily.com/738343d11636524e97e883ecdfb55ee8c179338e8409002b7334f65b8debc634.jpg
---

## Strategies to Overcome Not Trusted Update Error in WinOS

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-insider-tips-selecting-the-best-ig-video-editors-for-success/"><u>[New] Insider Tips  Selecting the Best IG Video Editors for Success</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-swapping-streams-saving-songs-cross-service-shuffling/"><u>[New] Swapping Streams, Saving Songs  Cross-Service Shuffling</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-top-20-youtube-bards-for-unforgettable-tales/"><u>[Updated] In 2024, Top 20 YouTube Bards for Unforgettable Tales</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-the-ultimate-guide-to-video-excellence-and-staff-picks-at-vimeo-for-2024/"><u>[Updated] The Ultimate Guide to Video Excellence & Staff Picks at Vimeo for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-frames-to-fabulous-the-ultimate-list-of-photo-plugins/"><u>2024 Approved  Frames to Fabulous  The Ultimate List of Photo Plugins</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-strategies-for-deleting-watch-later-items-on-youtube/"><u>2024 Approved  Strategies for Deleting Watch Later Items on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-driver-verification-on-windows-enforcement-off-unsigned-loaded/"><u>Bypass Driver Verification on Windows: Enforcement Off, Unsigned Loaded</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-secrets-5-entertaining-hacks/"><u>Command Prompt Secrets: 5 Entertaining Hacks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-tecno-pova-5-pro-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Tecno Pova 5 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nvidias-opengl-failure-no-3-in-windows-11/"><u>Eliminating NVIDIA's OpenGL Failure No. 3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-prevent-vscode-failures-w11/"><u>Essential Steps to Prevent VSCode Failures W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unverified-session-error-by-steams-vac/"><u>Fixing Unverified Session Error by Steam's VAC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-13-pro-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-windows-11-to-notify-you-when-someone-accesses-your-camera/"><u>How to Force Windows 11 to Notify You When Someone Accesses Your Camera</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-achieving-proficiency-comprehensive-photoshop-hdr-tutorial/"><u>In 2024, Achieving Proficiency  Comprehensive Photoshop HDR Tutorial</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-starting-from-scratch-best-game-editing-programs-for-newbies/"><u>In 2024, Starting From Scratch  Best Game Editing Programs for Newbies</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/making-waves-in-popularity-how-to-earn-vimeo-writers-picks/"><u>Making Waves in Popularity  How to Earn Vimeo' Writers’ Picks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fps-in-csgo-essential-insights/"><u>Mastering FPS in CS:GO - Essential Insights</u></a></li>
<li><a href="https://win11.techidaily.com/mending-usb30-device-failure-in-windows-1011-systems/"><u>Mending USB3.0 Device Failure in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-pathway-restrictions-in-windows/"><u>Overcoming Device Pathway Restrictions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launchers-secure-login-failures-on-windows-os/"><u>Overcoming Launcher's Secure Login Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outdated-boot-options-gray/"><u>Overcoming Outdated BOOT Options Gray</u></a></li>
<li><a href="https://win11.techidaily.com/steer-clear-from-cheap-windows-codes-a-cautionary-tale/"><u>Steer Clear From Cheap Windows Codes: A Cautionary Tale</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-the-delayed-folder-upload-issue-onedrive-errors/"><u>Swift Remedies for the Delayed Folder Upload Issue: OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-temporary-path-errors-quick-fix-guide-for-windows-error-1152/"><u>Tackling Temporary Path Errors - Quick Fix Guide for Windows Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-device-issue-on-windows-os/"><u>Troubleshooting Missing Device Issue on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-potential-7-efficient-practices-for-windows-11-users/"><u>Unleash Peak Potential: 7 Efficient Practices for Windows 11 Users</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-best-10-software-for-video-editors/"><u>Updated In 2024, Best 10 Software for Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-secure-access-tips-for-stuck-pins/"><u>Windows Secure Access: Tips for Stuck Pins</u></a></li>
</ul></div>
