---
title: Overcoming Erroneous Non-Existing Device Alert on Win 11
date: 2024-08-16T00:23:27.275Z
updated: 2024-08-17T00:23:27.275Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Erroneous Non-Existing Device Alert on Win 11
excerpt: This Article Describes Overcoming Erroneous Non-Existing Device Alert on Win 11
keywords: Windows 11 Error Fix,W11 False Devices Alert,Unknown Device Warning Win11,Resolve Win11 Alerts,Disable Non-Existent Device Windows,Win11 Erroneous Device Notify,Eliminate W11 Fake Errors
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
---

## Overcoming Erroneous Non-Existing Device Alert on Win 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to [running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
6. Select a drive letter that you’ve never used.
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** on the drive’s permissions window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to [unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://extra-information.techidaily.com/new-adventure-capturing-toolskit/"><u>[New] Adventure Capturing Toolskit</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-free-windows-programs-expertly-record-live-shows-for-2024/"><u>[New] Free Windows Programs  Expertly Record Live Shows for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-getting-comfy-with-video-chats-in-instagrams-ecosystem-for-2024/"><u>[New] Getting Comfy with Video Chats in Instagram's Ecosystem for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-instantaneous-video-and-picture-revival-on-snap/"><u>[New] Instantaneous Video & Picture Revival on Snap</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-apowersoft-a-complete-guide-to-screen-recording/"><u>[Updated] In 2024, Apowersoft  A Complete Guide to Screen Recording</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-securing-top-quality-pixel-ringtones-where-to-go/"><u>[Updated] Securing Top Quality Pixel Ringtones  Where to Go?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-ultimate-screen-capture-showdown-free-vs-paid-cam-recorders-for-2024/"><u>[Updated] The Ultimate Screen Capture Showdown  Free vs Paid Cam Recorders for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-elevating-educational-content-by-adding-youtube-music-to-vids/"><u>2024 Approved  Elevating Educational Content by Adding YouTube Music to Vids</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-windows-photo-inspector-fast-edition/"><u>2024 Approved  Top Windows Photo Inspector, Fast Edition</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024s-8-must-have-iphone-selfie-enhancers/"><u>2024'S #8 Must-Have iPhone Selfie Enhancers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-innovation-new-pcs-best-tools-from-msistore/"><u>Accelerated Innovation: New PC's Best Tools From MSIStore</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lag-on-extended-screens/"><u>Addressing Windows Lag on Extended Screens</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-distractions-mastering-wins-on-windows-11/"><u>Avoiding Distractions: Mastering Wins on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-google-pixel-8-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-unmasking-your-ip/"><u>Command Prompt Wizardry: Unmasking Your IP</u></a></li>
<li><a href="https://win11.techidaily.com/creating-digital-wonders-on-win11-with-paint-cocreator-the-ultimate-guide-for-ai-image-creation/"><u>Creating Digital Wonders on Win11 With Paint Cocreator: The Ultimate Guide for AI Image Creation</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-installs-time-mastering-grouped-deployments-with-winstall-on-windows-11/"><u>Cutting Down Installs Time: Mastering Grouped Deployments with Winstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-persistent-boot-related-windows-audio-failures/"><u>Eliminate Persistent Boot-Related Windows Audio Failures</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-hp-lcd-flashes/"><u>Eliminating HP LCD Flashes</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-window-resolutions/"><u>Enhancing Your Visual Experience with Window Resolutions</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-error-x800704cf-on-windows-devices/"><u>Guide to Resolving Error X800704CF on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-login-after-failures/"><u>How to Reactivate Windows Login After Failures</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-vivo-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Vivo</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-iphone-11-pro-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked iPhone 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-system-top-tips-for-black-screen-on-win11/"><u>Jumpstart Your System: Top Tips for Black Screen on Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-oppo-find-x7-ultra-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Oppo Find X7 Ultra Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-pip-macos-sierras-guide-to-multimedia-magic/"><u>Mastering PIP  MacOS Sierra's Guide to Multimedia Magic</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-roblox-boot-up-obstacles-a-comprehensive-guide-updated/"><u>Overcoming Roblox Boot-Up Obstacles: A Comprehensive Guide [Updated ]</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-interruptions-during-steam-video-streaming/"><u>Preventing Interruptions During Steam Video Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-11-arm-installation-via-iso-download/"><u>Seamless Windows 11 ARM Installation via ISO Download</u></a></li>
<li><a href="https://win11.techidaily.com/secure-app-locations-in-windows-task-management/"><u>Secure App Locations in Windows Task Management</u></a></li>
<li><a href="https://os-tips.techidaily.com/setting-up-screen-time-restrictions-for-ios-devices-easy-step-by-step-instructions/"><u>Setting Up Screen Time Restrictions for iOS Devices - Easy Step-by-Step Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-booster-issues-windows-repair-guide/"><u>Skyrim Booster Issues: Windows Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/switching-notepad-to-dark-mode-on-windows-11plus/"><u>Switching Notepad to Dark Mode on Windows 11+</u></a></li>
<li><a href="https://win11.techidaily.com/system-fixes-for-error-0x800700e1-in-windows-11/"><u>System Fixes for Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-auto-clickers-with-hotkeys-for-windows/"><u>The 5 Best Auto Clickers With Hotkeys for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-selection-of-premium-3d-printing-filaments/"><u>The Ultimate Selection of Premium 3D Printing Filaments</u></a></li>
<li><a href="https://win11.techidaily.com/trick-to-invoke-admin-level-powershell-on-your-win11-pc/"><u>Trick to Invoke Admin-Level PowerShell on Your Win11 PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-hdmi-problems-caused-by-conflicting-application-usage/"><u>Troubleshooting HDMI Problems Caused by Conflicting Application Usage</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/understanding-ipad-vs-ipad-air-key-features-and-comparisons/"><u>Understanding iPad Vs. IPad Air: Key Features and Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-menu-unlocking-ancestral-functions/"><u>Windows 11'S Menu: Unlocking Ancestral Functions</u></a></li>
</ul></div>
