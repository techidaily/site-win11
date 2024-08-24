---
title: How to Wirelessly Connect a PS3 DualShock Controller to Windows
date: 2024-08-23T06:10:01.238Z
updated: 2024-08-24T06:10:01.238Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Wirelessly Connect a PS3 DualShock Controller to Windows
excerpt: This Article Describes How to Wirelessly Connect a PS3 DualShock Controller to Windows
keywords: PS3 Controller Wi-Fi Tips,DualShock Ps3 Wireless PC,PS3 Controller for Windows,Bluetooth PS3 DualShock,Connecting PS3 Controllers,PS3 Gamepad Windows Guide,PS3 Remote Play Setup
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## How to Wirelessly Connect a PS3 DualShock Controller to Windows

 Your PS3 is probably gathering dust by now, so why not put it to good use... or, at least, its controllers? Use them on your PC and give them a new life.

 Although it was possible to use PS3 joypads on PCs in the past, the process was finicky, and their wireless functionality was wonky. That was until DsHidMini entered the scene. Here's how you can use a PS3 DualShock controller on your PC, both through a USB connection and wirelessly through Bluetooth

## What Is DsHidMini?

 DsHidMini is an open-source solution for connecting and configuring many types of joypads to a PC. As such, if you have your old PS3 or PS4 DualShock controllers around, why not put them to use with this app?

 DsHidMini enables your PC to recognize them and provides XInput emulation. With Xinput being the modern standard for joypads under Windows, you'll be able to use your PlayStation controller with most modern games.

## Getting the Necessary Software for Using Your PS3 Controller on a PC

 By combining two pieces of software, DsHidMini, and BthPS3, you can have your PC detect your DualShock controller effortlessly both when connected with a USB cable and wirelessly through Bluetooth.

 Note, though, that for this guide, we take the existence of correctly working Bluetooth functionality for granted. If your PC lacks Bluetooth support, check our buyer's guide on[the best Bluetooth adapters you can grab today](https://www.makeuseof.com/best-bluetooth-adapters/) . Then, check our guide on[how to add Bluetooth to any computer](https://www.makeuseof.com/add-bluetooth-pc/) .

### Download and Install DsHidMini and BthPS3

 DsHidMini suggests installing BthPS3 to have your DualShock controllers correctly detected and connected to your PC. This guide will follow that suggestion, especially since we want them to work wirelessly.

1. Start by downloading the first piece of software from[DsHidMini's GitHub page](https://github.com/ViGEm/DsHidMini) .  
![DsHidMini GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-github-page.jpg)
2. Do the same with a visit at[BthPS3's GitHub page](https://github.com/ViGEm/BthPS3) .  
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![BthPS3 GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-page.jpg)
3. In both cases, you'll find the downloadable files by clicking on the link under**Installation** , then checking out the links under**Assets** . Most people should go for the x64 versions. If you're still using an older 32-bit version of Windows, get the x86 files.  
![BthPS3 GitHub Assets Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-assets-links.jpg)
4. Click on**BthPS3's MSI file** that you've downloaded to install the Bluetooth driver. "MSI" stands for Microsoft Software Installer. Unlike executable installers, MSI relies on the "official" installation libraries bundled with Windows. If you meet any problems during that step, check our guide on[how to fix issues with the Windows Installer package](https://www.makeuseof.com/windows-installer-package-fix-issues/) .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![BthPS3 Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installation.jpg)
5. After BthPS3's successful installation, you'll see it as a new device under the**Bluetooth** category in**Device Manager** . The easiest way to access the Device Manager is by using the**Windows Key** +**X** shortcut and selecting it from the menu that shows up.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![BthPS3 Installed Bluetooth Driver in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installed-bluetooth-driver-in-device-manager.jpg)
6. DsHidMini's installation is a tad more complicated since it comes in a compressed archive. Open**Windows File Explorer** , and pay a visit to the folder where you saved DsHidMini's downloaded archive. All modern versions of Windows support the ZIP archive format, so you can right-click on the file and choose**Extract** . However, we used WinRAR instead simply because we had it installed, and it's somewhat faster. In both cases, the result is the same.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![Extracting DsHidMini Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extracting-dshidmini-archive.jpg)
7. Look inside the extracted archive's folder, and you'll see two more folders:**x64** and**x86** . Enter the one matching your Windows architecture. As mentioned above, most people nowadays should go for**x64** .  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![DsHidMini Extracted Archive Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents.jpg)
8. Inside that folder, you'll find another subfolder named**dshidmini** . Enter that one, too.  
![DsHidMini Extracted Archive Contents x64](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64.jpg)
9. Right-click on the**dshidmini.inf** file, and choose**Install** from the menu that shows up. When that step completes, install the**igfilter.inf** the same way.  
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![DsHidMini Extracted Archive Contents x64 dshidmini inf install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64-dshidmini-inf-install.jpg)

 Theoretically, that's everything you need for your DualShock to work with your PC. Practically, as is Windows' tradition, it wouldn't hurt to restart once to ensure the drivers are correctly installed, activated, and work as they should.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Pair and Configure Your PS3 DualShock

 The next step is to "pair" your controller with your PC. However, that process is somewhat unconventional compared to how you usually connect Bluetooth devices to your PC.

1. Connect your DualShock joypad to your PC using a mini-USB cable. Your joypad should begin charging.
2. Pay a visit to the folder with DsHidMini's extracted files. Double-click on the**DSHMC.exe** to run it.  
![DSHMC.exe File In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-file-in-file-explorer.jpg)
3. You should see your "PlayStation controller" detected on the left side of the app's window. Now, if you run Steam with its outstanding controller support, it should detect and configure your joypad for use in modern games. As for wireless? Unplug the cable, and your joypad should keep working as if nothing happened.  
![DSHMC.exe Controller Detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-controller-detected.jpg)
4. DsHidMini will have your controller recognized as an**XInput** device by default to maximize compatibility with modern software. But what if you want to use it on an older title that uses the older**DirectInput** standard or to have emulators like PPSSPP, PCSX2, and RPCS3 recognize it as an actual PlayStation controller? Close DSHMC.exe, then right-click on it and re-run it, but this time choose**Run as Administrator** . When its window shows up again, click on your controller on the left, and you'll see more details about it on the right and some options you can tweak.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![DSHMC Configuration As Admin](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-configuration-as-admin.jpg)
5. You can change the HID device mode from**XInput** to another mode compatible with the software where you want to use your controller. You can also tweak its**Idle disconnect** period or define after how much time of inactivity the controller should disconnect and turn off.  
![DSHMC Change HID Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-change-hid-mode.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Remove Remnants of Old Drivers

 If your joypad isn't correctly detected, did you use another solution in the past to have it work under Windows, like Sony's official driver or ScpToolkit? If yes, the problem might be a conflict between those and the DsHidMini and BthPS3 combo.

 Removing the older drivers and software is somewhat complicated. Plus, the process varies based on the driver and software used. So, we won't go over it in detail but offer a "generic guide" covering the basic steps for most cases.

 Run the**Command Prompt** or**PowerShell** with Administrative rights. Then, use the commands, in sequence, if you were using ScpToolkit:

`taskkill /F /IM ScpServer.exe  
taskkill /F /IM ScpMonitor.exe  
taskkill /F /IM ScpTrayApp.exe  
sc stop Ds3Service  
sc delete Ds3Service`

 These will stop and remove all active processes and services for PlayStation joypad-enabling software you might have used in the past.

 Now, press**Win** +**X** and choose**Device Manager** . Find and remove any mention of a "PlayStation controller" under**Human Interface Devices** if you were using the official Sony drivers.

 For ScpToolkit, look under**libusbK USB Devices** instead, and right-click and**Uninstall** any entry you see. Also, check for and, if found, uninstall the drivers for any "Bluetooth Dongle", "DualShock controller", or "PlayStation controller" under**Universal Serial Bus devices** .

 Then, download[DriverStore Explorer from its GitHub page](https://github.com/lostindark/DriverStoreExplorer/releases/tag/v0.11.79) . Extract its archive and run the app. Enable**Force Deletion** on the right. Seek any**libusbK USB Devices** , a standalone**scpvbus.inf** , or**bluetoothhost.inf** and**ds3controller.inf** if using ScpToolkit.

 Look for**sixaxis.inf** instead if using the official Sony driver. In both cases, place a checkmark next to any of those entries you'll find, and then click on**Delete Drivers** on the right.

 Afterward, exit the app, restart your PC, and let Windows re-detect any hardware and install the default drivers. Then, repeat the steps we covered above to install BthPS3 and DsHidMini from scratch.

## How to Use Your PS3 DualShock in Games

 Your controller should work now in most modern games that support Xbox joypads and for most joypad-enabled titles running under Steam.

 When that's not the case, run DSHMC.exe as an administrator and change the HID mode used by your joypad to the one supported by the game or app where you want to use it.

 An easy way to find the HID mode to choose for a particular title is to check if there's information about it at[PCGamingWiki](https://www.pcgamingwiki.com/wiki/Main%5FPage) .

## Using Classic PS3 Joypads on Your Modern-Day Games for Windows

 Reusing your older joypads on your PC is the smartest choice. Apart from the fact you won't have to pay a dime to do it, they're great performers, tried and tested, and you're already familiar with them.

 Worst case scenario, you might have to buy a Bluetooth dongle for your PC, which would still come at a fraction of the cost of a brand-new controller.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-pcs-premier-ps3-imitators-ranked-top-5-choices/"><u>[New] In 2024, PC's Premier PS3 Imitators Ranked  Top 5 Choices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-future-with-q500-typhoon/"><u>[New] Unveiling the Future with Q500 Typhoon</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-visionary-6-eco-friendly-minecraft-mansions/"><u>[Updated] 2024 Approved  Visionary 6 Eco-Friendly Minecraft Mansions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevating-your-footage-imovie-videos-for-youtube-enthusiasts/"><u>[Updated] In 2024, Elevating Your Footage  IMovie Videos for YouTube Enthusiasts</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-reign-at-the-top-the-best-tiktok-typography-for-maximum-engagement/"><u>[Updated] In 2024, Reign at the Top  The Best TikTok Typography for Maximum Engagement</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-metaverse-vr-gear-list-top-8-choices/"><u>[Updated] Ultimate Metaverse VR Gear List  Top 8 Choices</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-dive-into-the-ocean-of-audio-visual-artistry-with-these-6-apps/"><u>2024 Approved  Dive Into the Ocean of Audio-Visual Artistry With These 6 Apps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-lightning-share-youtube-playlist-hacks/"><u>2024 Approved  Lightning Share  YouTube Playlist Hacks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/copyright-compliance-and-photovideo-sharing/"><u>Copyright Compliance & Photo/Video Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-inaccessible-recycle-bin-status-in-win11/"><u>Correcting Inaccessible Recycle Bin Status in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-monitoring-add-analyzer-to-windows-context-menu/"><u>Enhance System Monitoring: Add Analyzer to Windows Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-security-by-safe-disabling-of-windows-11-features/"><u>Enhancing Security by Safe Disabling of Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-successful-utorrent-deployment-on-windows-pcs/"><u>Enhancing Successful uTorrent Deployment on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-system-accessibility-with-elevated-privileges/"><u>Enhancing System Accessibility with Elevated Privileges</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/exploring-picture-in-picture-features-on-sierras-operating-systems/"><u>Exploring Picture in Picture Features on Sierra's Operating Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-microvid-viewer-analysis-and-comparison-tools/"><u>In 2024, MicroVid Viewer Analysis & Comparison Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-xiaomi-redmi-12-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Xiaomi Redmi 12 5G</u></a></li>
<li><a href="https://win11.techidaily.com/merge-gmail-with-outlook-on-windows-a-detailed-guide/"><u>Merge Gmail with Outlook on Windows: A Detailed Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-top-6-to-do-apps-for-windows/"><u>Navigating the Top 6 To-Do Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/open-component-services-on-windows-11-an-insiders-view/"><u>Open Component Services on Windows 11: An Insider's View</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-for-professionals-automated-archive-operations/"><u>PowerShell for Professionals: Automated Archive Operations</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-delete-functionality-on-windows-systems/"><u>Reinstating Delete Functionality on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-ms-store-error-code-0x80073d26-on-windows-11-os/"><u>Remedying MS Store Error Code 0X80073D26 on Windows 11 OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-note-30-vip-racing-edition-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-0x80070194-on-onedrive-and-windows-oses/"><u>Resolving 0X80070194 on OneDrive & Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-click-process-with-mouse-settings-tweak/"><u>Simplify Your Click Process with Mouse Settings Tweak</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-operational-keys-on-your-windows-machine/"><u>Solving Non-Operational Keys on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unidentified-fingerprint-scanner-errors-in-windows/"><u>Solving Unidentified Fingerprint Scanner Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-for-invalid-system-id-alert-in-win11/"><u>Step-by-Step Fix for Invalid System ID Alert in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-application-transfer-onto-windows-11-systems/"><u>Streamlining Application Transfer Onto Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-restoring-the-functionality-of-windows-defenders-threat-barrier/"><u>Swift Remedies: Restoring the Functionality of Windows Defender's Threat Barrier</u></a></li>
<li><a href="https://program-issues.techidaily.com/triumph-over-troubled-networks-in-terraria-with-these-proven-fixes/"><u>Triumph Over Troubled Networks in Terraria with These Proven Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-nvidias-geforce-error-in-windows-os/"><u>Troubleshooting Nvidia's GeForce Error in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-full-gaming-potential-directdraw-tips/"><u>Unlocking Windows 11'S Full Gaming Potential: DirectDraw Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-sales-how-does-microsoft-earn/"><u>Windows 11 Sales - How Does Microsoft Earn?</u></a></li>
</ul></div>
