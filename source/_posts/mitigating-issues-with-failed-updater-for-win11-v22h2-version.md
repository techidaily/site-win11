---
title: Mitigating Issues with Failed Updater for WIN11 V22H2 Version
date: 2024-08-16T00:45:11.560Z
updated: 2024-08-17T00:45:11.560Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating Issues with Failed Updater for WIN11 V22H2 Version
excerpt: This Article Describes Mitigating Issues with Failed Updater for WIN11 V22H2 Version
keywords: Windows 11 Update Troubleshooting,WIN11 Fixer Toolkit,Updater Issues Resolution,Bypassing WIN11 V22H2 Errors,Quick Fix for Win11 Update,Solve Failed Windows 11 Updates,WIN11 Firmware Fail Fixes
thumbnail: https://thmb.techidaily.com/2a29084ef28c5d6ebf693615660d627bf6405cc5a8ac614e41f7b335143de3df.jpg
---

## Mitigating Issues with Failed Updater for WIN11 V22H2 Version

 Microsoft released its first Windows 11 build version update in September 2022\. The 22H2 update has added a slew of new Windows 11 features and options. Many users are now installing that update via Settings.

 However, some users have reported in forums that they can’t upgrade Windows 11 to the 22H2 version. Those users have said that updates get stuck at percentage marks when they try to download and install them from Settings. Some users see error codes like 0x800f0806 for that update. This is how you can fix the Windows 11 22H2 update not installing.

## 1\. Run Windows 11’s Troubleshooter for Updates

 The Windows Update troubleshooter is there to check for and resolve issues with the update process. That troubleshooter isn’t guaranteed to fix all update errors, but it might fix Windows 11’s 22H2 update not installing for some users at least. You can run the Windows Update troubleshooter in the following steps:

1. Press**Win** +**I** to open**Settings** .
2. Select the**System** tab’s**Troubleshoot** option.
3. Click**Other trouble-shooters** to reach the troubleshooting utilities.
4. Select**Run** for the Windows Update troubleshooter.  
![The Run button for Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-run-button-for-windows-update-1.jpg)
5. Wait for the troubleshooter to detect issues and display an outcome. It will usually automatically apply fixes for detected issues.

## 2\. Disconnect Non-Essential External Hardware and Peripherals From PC

 It's recommended that users unplug non-essential hardware from PCs before attempting to upgrade to a new Windows 11 version. Doing so will ensure that there aren't any non-essential hardware devices that can potentially interrupt or conflict with the upgrade process. You'll still need your mouse and keyboard of course, but disconnect all the following non-essential peripherals:

* Headphones
* External storage drives
* Printers
* Scanners
* Speakers (they're not essential)
* Gamepads
* USB Hubs
* Webcams
* Microphones
* Secondary monitors (you only need one)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 3\. Run a System File and Deployment Image Scan

 System file corruption can cause Windows update errors to arise. You can check for and remedy corrupted files by running a System File Checker scan in the Command Prompt. It’s also recommended to run a Deployment Image Servicing and Management scan to check the system image before that. This is how to run both scanning tools in Windows 11.

1. Open the file search tool with the**Windows** +**S** hotkey.
2. Search for Command Prompt by inputting**cmd** in the text box.
3. Right-click Command Prompt inside the search tool’s results to select a**Run as administrator** option.
4. Start by inputting this command and pressing**Enter** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Then run the SFC tool by typing in the following command and pressing**Return** :  
`sfc /scannow`
6. Wait for the SFC scan to show an outcome message in the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Free Up Some Drive Storage Space

 You’ll need at least 64 gigabytes of drive storage space available for the Windows 11 22H2 update. So, check your hard drive has enough space for the 22H2 update before installing it.

 If it doesn’t, free up the required drive storage space for the update by erasing superfluous files and uninstalling Windows software. Check out our[Cleanup recommendations guide](https://www.makeuseof.com/free-storage-space-with-cleanup-recommendations/) for further details about how to create storage space via Settings.

![Cleanup recommendations in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/cleanup-recommendations-1.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Check If the Dependency Services for Windows Update are Enabled

 The Windows Update service has some service dependencies that need to be enabled and running. Windows 11 22H2 update issues will likely arise if necessary prerequisite services are disabled. You can make sure the Windows Module Installer, BITS, and CryptSvc services are enabled like this:

1. Open Windows 11’s Services utility. You can check out our[how-to-open Services guide](https://www.makeuseof.com/windows-11-open-services-app/) for further instructions.
2. Double-click**Windows Module Installer** to view a properties window for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/windows-modules-installer-1.jpg)
3. Select the**Automatic** start option for the service on its**Startup type** drop-down menu.
4. Click**Start** on the properties window if the service isn’t running.  
![The Windows Modules Installer service properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/a-service-properties-window-1.jpg)
5. Select**Apply** \>**OK** to set the service’s settings.
6. Repeat the previous four steps for the Background Intelligent Transfer Service, Cryptographic Service, and Windows Update services.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 6\. Make Sure .NET Framework 3.5 is Enabled

 The .NET Framework 3.5 feature also needs to be enabled for the Windows Update service to work. That should be enabled by default in Windows 11, but some users may still need to turn on .NET Framework 3.5\. This is how you can make sure .NET Framework 3.5 is enabled in Windows 11:

1. Open the file and app search utility by pressing the**Windows** +**S** key combo.
2. Enter**Windows features** in the**Type here to search** box.
3. Click the**Turn Windows features on or off** applet in the search tool.
4. Select the**.NET Framework 3.5** checkbox if that feature isn’t enabled.  
![The Windows Features window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-features-window-1.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Also, click the**.NET Framework 4.8** checkbox if it’s not selected.
6. Press the**OK** button in the Windows Features window.
7. Then click**Yes** to install.
8. Restart Windows 11 after installing the feature.

## 7\. Reset the Components for Windows Update

 Windows 11 22H2 update issues can also arise because of corrupted update components. You can repair the update components by resetting them. This troubleshooting method involves restarting update services and refreshing the catroot2 and SoftwareDistribution folders by renaming them. You can reset components for Windows updates with the Command Prompt like this:

1. Open Command Prompt with elevated permissions, as outlined in steps one to three of method two.
2. Then stop four services by inputting and executing the following commands:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Next, rename the SoftwareDistribution folder by executing this command:  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren SoftwareDistribution command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-softwaredistribution-command-1.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Input this rename catroot2 command and press**Return** :  
`ren C:\Windows\System32\catroot2 Catroot2.old`  
![The ren catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-catroot2-folder-1.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Then restart the services with these commands:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`
6. Close Command Prompt, and select**Restart** on your Start menu.

## 8\. Turn Off Third-Party Antivirus Utilities

 Some third-party antivirus utilities can mistakenly interfere with the update process for Windows 11’s 22H2 update. To stop this from happening, disable real-time scanning for third-party antivirus software.

 If you have a third-party antivirus tool installed, right-click its system tray icon and select a context menu option to turn off its shield for a few hours; then try upgrading Windows 11 to the 22H2 version with the antivirus software disabled.

 AVG and Avast are two antivirus software packages that often generate Windows update errors. Those antivirus tools have also been incompatible with some Windows 10 builds. If you have either of those two installed, consider uninstalling them instead of merely disabling their shields.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Disable Kernel DMA Protection

 Some users have said the Kernel DMA Protection security feature in Windows 11 causes the 22H2 update to fail when enabled. If that feature is enabled on your desktop or laptop, disabling it could fix the Windows 11 22H2 not installing. To check if Kernel DMA Protection is enabled,[open the System Information app](https://www.makeuseof.com/windows-11-check-system-information/) and look for that feature in the**System Summary** section.

![The Kernel DMA Protection system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-kernal-dma-system-detail-1.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->

 The only way to turn off Kernel DMA Protection is to disable a setting for it in the BIOS (Basic Input Output System). You can access Basic Input Output System settings on Windows 11/10 PCs as outlined within our guide on[how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) . Look for and disable a Kernel DMA Protection setting on a**Security** tab within the BIOS.

## 10\. Update Your PC's Drivers

 Outdated device drivers can cause Windows upgrade issues. So, we recommend that you generally update device drivers on your PC. The quickest way to do that is to utilize a driver updater tool like Driver Booster.

 A Driver Booster scan will show you what devices on your PC have antiquated drivers. You can also select an**Update Now** option in that software to update the drivers for listed devices. Our[Driver Booster guide](https://www.makeuseof.com/update-windows-drivers-driver-booster-8/) includes instructions for updating drivers with that software.

![Driver Booster 8](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/driver-booster2.jpg)

 Alternatively, you may be able to install some new drivers with optional Windows updates. This is how you can check available optional updates in Windows 11:

1. [Open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and its**Windows Update** tab.
2. Select**Advanced options** to bring up some configuration settings for updates.
3. Click**Optional updates** to see if there are any driver updates available.
4. Select the checkboxes for driver updates there.
5. Click the**Download and install** option for selected driver updates.

## 11\. Install the 22H2 Update via the Installation Assistant

 This final resolution is more of a workaround than a fix for the 22H2 update not installing via Settings. Instead of using Settings, try upgrading with the Windows 11 Installation Assistant. We have a full guide that tells you[how to use the Installation Assistant](https://www.makeuseof.com/windows-11-installation-assistant-guide/) for updating Windows 11.

![The Windows 11 Update Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-11-update-assistant.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Discover the Windows 11 2022 Update

 Those possible solutions will likely resolve most 22H2 update errors for the majority of users. The resolutions on Microsoft’s[Windows update troubleshooting](https://support.microsoft.com/en-us/windows/troubleshoot-problems-updating-windows-188c2b0f-10a7-d72f-65b8-32d177eb136c#WindowsVersion=Windows%5F11) page might also help some users fix Windows 11’s 22H2 update not installing. With that issue fixed, you can discover all the interesting new features and options in the Windows 11 2022 Update.

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


