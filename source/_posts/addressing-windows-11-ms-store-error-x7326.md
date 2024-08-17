---
title: Addressing Windows 11 MS Store Error X7326
date: 2024-08-15T23:14:08.104Z
updated: 2024-08-16T23:14:08.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows 11 MS Store Error X7326
excerpt: This Article Describes Addressing Windows 11 MS Store Error X7326
keywords: WinX7326Error,MSStoreX7326,Windows11InstallIssue,X7326MSStoreError,FixWindows11Error,StoreErrorW11,ResolveWinX7326
thumbnail: https://thmb.techidaily.com/3a3db1628b8f2814d2040ecfe00634d164ea4b5f3058a85b825026993cb96502.jpg
---

## Addressing Windows 11 MS Store Error X7326

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-9-ultimate-free-online-editors-for-content-creators-for-2024/"><u>[New] 9 Ultimate Free Online Editors for Content Creators for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-effortlessly-download-top-5-chromium-plug-ins-for-fb-video-access/"><u>[New] Effortlessly Download  Top 5 Chromium Plug-Ins for FB Video Access</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-peepcapture-snapshot-scrutiny-and-choices/"><u>[New] In 2024, PeepCapture Snapshot Scrutiny & Choices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-swaying-symbols-dynamic-animation-for-text-effects/"><u>[New] Swaying Symbols  Dynamic Animation for Text Effects</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-video-vanguard-vs-studio-giants/"><u>[Updated] In 2024, Video Vanguard VS Studio Giants</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-driver-updates-made-easy-for-windows-versions-7-10-and-11-users/"><u>AMD Driver Updates Made Easy for Windows Versions 7, 10 and 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-not-empty-directive-with-error-x80070091-fixes/"><u>Disabling Windows' Not Empty Directive with Error X80070091 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/effective-steps-to-update-login-credentials-on-win-11/"><u>Effective Steps to Update Login Credentials on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-phone-tethering-experience-in-windows-11-era/"><u>Elevating Phone Tethering Experience in Windows 11 Era</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-fixing-incomplete-network-commands-on-pc/"><u>Enhancing Wi-Fi Connectivity: Fixing Incomplete Network Commands on PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-eliminate-microsoft-offices-error-code-0x80041015/"><u>Guide to Eliminate Microsoft Office's Error Code 0X80041015</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-apple-iphone-15-pro-max-by-drfone-ios/"><u>How to jailbreak iCloud locked Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-xiaomi-13-ultra-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Xiaomi 13 Ultra Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tailor-your-program-palette-the-windows-11-way/"><u>How To Tailor Your Program Palette: The Windows 11 Way</u></a></li>
<li><a href="https://win-able.techidaily.com/improving-visuals-in-cyberpunk-2077-tackling-and-enhancing-fps-drops/"><u>Improving Visuals in Cyberpunk 2077 - Tackling and Enhancing FPS Drops</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-cutting-edge-methods-for-capturing-your-playtime/"><u>In 2024, Cutting-Edge Methods for Capturing Your Playtime</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transformative-power-in-healthcare-through-vr/"><u>In 2024, Transformative Power in Healthcare Through VR</u></a></li>
<li><a href="https://win11.techidaily.com/latency-less-viewing-optimizing-winx-media-with-these-fixes/"><u>Latency-Less Viewing: Optimizing WinX Media with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mending-inactive-mail-signals-for-outlook-users/"><u>Mending Inactive Mail Signals for Outlook Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-hurdles-fixing-amd-1e95-error-in-windows/"><u>Navigating Past Hurdles: Fixing AMD 1E95 Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/network-prowess-4-tactics-to-measure-ethernet-speed-on-windows/"><u>Network Prowess: 4 Tactics to Measure Ethernet Speed on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-fixing-spotify-errors-on-win11/"><u>Overcoming the Hurdles: Fixing Spotify Errors on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sensors-windows-based-methods-for-examining-network-rate/"><u>Speed Sensors: Windows-Based Methods for Examining Network Rate</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-stop-video-resets-on-win1110-devices/"><u>Strategies to Stop Video Resets on Win11/10 Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-essential-handbook-for-incorporating-music-into-ppt/"><u>The Essential Handbook for Incorporating Music Into PPT</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-symbiosis-navigating-github-desktop-and-windows-11/"><u>The Perfect Symbiosis: Navigating GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-guide-to-choosing-your-macbook-air-vs-pro-highlights/"><u>The Ultimate Guide to Choosing Your MacBook: Air Vs. Pro Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-mcuicntexe-missing-in-windows/"><u>Troubleshooting McUICnt.exe Missing in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-cpu-limitation-detectors/"><u>Ultimate CPU Limitation Detectors</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-gaming-combat-0x00000001-on-pcs/"><u>Unfreezing Gaming: Combat 0X00000001 on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unpackaging-problems-solved-fixing-windows-package-not-open-errors/"><u>Unpackaging Problems Solved: Fixing Windows Package Not Open Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-drives-c-and-d/"><u>Unraveling the Mystery of Windows Drives (C & D)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-innovation-four-revolutionary-updates-for-paint/"><u>Unveiling Innovation: Four Revolutionary Updates for Paint</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-bt-folders/"><u>Unveiling the Mystery of Windows ~BT Folders</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-the-run-command-wont-save-history-on-windows/"><u>What to Do When the Run Command Won’t Save History on Windows</u></a></li>
</ul></div>
