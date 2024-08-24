---
title: "Installation Procedures: Windows 11 & VMWare Workstation 17"
date: 2024-08-23T06:13:08.481Z
updated: 2024-08-24T06:13:08.481Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Installation Procedures: Windows 11 & VMWare Workstation 17"
excerpt: "This Article Describes Installation Procedures: Windows 11 & VMWare Workstation 17"
keywords: Windows 11 Install Guide,VMware WS 17 Setup,Win11 Virtualization,Vmware Enable Windows,New Windows Procedures,Launching Win11 VMs,11WOS VM Configuration
thumbnail: https://thmb.techidaily.com/b4ed3f08ab6e820bb58ff66c5f5e67696c65d753e22482d093bffe3ae2ca67e1.png
---

## Installation Procedures: Windows 11 & VMWare Workstation 17

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.

## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on[how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
2. A Windows 10 or above operating system with TPM 2.0 and virtualization support.
3. The latest version of VMware Workstation 17 Player must be pre-installed on the host system.
4. Adequate computing resources to run Windows 11 as a virtual machine. The list includes 64 GB disk space, 4 GB RAM, and a dual-core x64 processor.

 Once you have the necessary ISO file and the latest copy of VMware on your system, you can proceed to the virtual machine creation and Windows 11 installation.

## How to Install Windows 11 in VMware Workstation 17 Player

 Firstly, we will create a virtual machine in VMware for Windows 11\. Then, we will install Windows 11 on the virtual machine. Lastly, we will install VMware tools to finish setting up the virtual machine.

### 1\. Create a Windows 11 Virtual Machine

 Here’s how to create a virtual machine for Windows 11 in VMware:

1. Launch VMware Player on your system. On the home page, click on**Create a new virtual machine** option.
2. Select the**I will install the operating system later** radio button and click on the**Next** button.  
![Creating a Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/creating-a-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Click on the**Customize Hardware** button. Under the memory tab, increase the**RAM** allocation to**6 GB** or more to avoid a sluggish Windows 11 experience.
2. Switch to the**Processors** tab and allocate**4 or more cores** to the Windows virtual machine.
3. Next, move to the**New CD/DVD (SATA)** tab, and click on the**Use ISO image file** option located under the**Connection** section.
4. Click on the**Browse** button and select the Windows 11 ISO image file you previously downloaded. Click on the**Open** button.
5. Now, close the Hardware window and click on the**Finish** button to create the new virtual machine.

### 2\. Install Windows 11 on the Virtual Machine

 Repeat the following steps to install Windows 11 on the newly created virtual machine:

1. Navigate to the left-hand side menu and select the Windows 11 virtual machine. Click on the**Play virtual machine** option.
2. Press any keyboard key to boot from the ISO file. Pick the appropriate language and region and click on the**Next** button. Then, click on the**Install now** button.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. In the Windows setup window, click on the**I don’t have a product key** option.
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## Run Windows 11 on VMware Without Any Registry Hacks

 With TMP emulation, there is no need for registry tweaking to disable secure boot and TPM requirements on Windows 11\. All the features work fine, and you don’t need to switch to another hypervisor program. However, Oracle VirtualBox offers the same TPM virtualization and secure boot features.


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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-get-your-hands-on-the-best-9-online-shops-featuring-futuristic-graffiti-fonts/"><u>[New] 2024 Approved  Get Your Hands on the Best 9 Online Shops Featuring Futuristic Graffiti Fonts</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-unleashing-inspiration-ideas-for-engaging-channels/"><u>[New] 2024 Approved  Unleashing Inspiration  Ideas for Engaging Channels</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-deciding-your-gopro-comparative-analysis-at-hand-for-2024/"><u>[New] Deciding Your GoPro  Comparative Analysis at Hand for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-essential-software-for-enthusiasts-top-5-ps1-emulators/"><u>[New] In 2024, Essential Software for Enthusiasts  Top 5 PS1 Emulators</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-navigate-the-digital-realm-uploading-to-instagram-tv-for-2024/"><u>[New] Navigate the Digital Realm  Uploading to Instagram TV for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-recovery-of-windows-photo-viewer-functionality-on-win10/"><u>[New] Recovery of Windows Photo Viewer Functionality on Win10</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-storytelling-schools-1-8-rankings-and-insights/"><u>[New] Top Storytelling Schools  #1-#8 Rankings & Insights</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-dive-into-peace-with-these-soothing-games/"><u>[Updated] 2024 Approved  Dive Into Peace with These Soothing Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-add-music-to-instagram-videos-and-stories/"><u>[Updated] 2024 Approved  How to Add Music to Instagram Videos and Stories</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-best-methods-to-try-for-changing-playback-speed-in-spotify/"><u>[Updated] Best Methods to Try for Changing Playback Speed in Spotify</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-significant-details-in-asmr-recording-art-for-2024/"><u>[Updated] Significant Details in ASMR Recording Art for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-heres-what-you-dont-know-about-instagram-story-viewer/"><u>2024 Approved  Here's What You Don't Know About Instagram Story Viewer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-unveil-secretive-watch-video-icon/"><u>2024 Approved  Unveil Secretive Watch Video Icon</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-strategies-for-effective-data-management/"><u>Command Prompt Strategies for Effective Data Management</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/connect-to-a-real-time-tiktok-livestayers-world/"><u>Connect to a Real-Time TikTok Livestayer's World</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-ai-driven-tools-on-microsofts-platform/"><u>Discovering AI-Driven Tools on Microsoft's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-server-unreachable-for-ea-games/"><u>Eliminating Server Unreachable for EA Games</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-monitoring-add-analyzer-to-windows-context-menu/"><u>Enhance System Monitoring: Add Analyzer to Windows Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-system-accessibility-with-elevated-privileges/"><u>Enhancing System Accessibility with Elevated Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-streamlined-approaches-for-decoding-qr-codes-on-windows/"><u>Enhancing User Experience: Streamlined Approaches for Decoding QR Codes on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-tips-for-navigating-and-utilizing-google-gemini-effectively/"><u>Essential Tips for Navigating and Utilizing Google Gemini Effectively</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-gear-insights-and-comparisons-by-team-toms-technology/"><u>Expert Gear Insights and Comparisons by Team Tom's Technology</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-crash-0x00000709-issue/"><u>Fixing Windows Crash: 0X00000709 Issue</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-view-6-image-rotation-techniques-in-win11/"><u>Flip Your View: 6 Image Rotation Techniques in Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signature-for-pdf-file-document-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Free electronic signature for .pdf file document</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722960669536-get-the-m-audio-fast-track-ultra-driver-for-free-elevate-your-sound-today/"><u>Get the M-Audio Fast Track Ultra Driver For Free – Elevate Your Sound Today</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-capture-gameplay-on-windows-with-intel-graphics-command-center/"><u>How to Capture Gameplay on Windows With Intel Graphics Command Center</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-hidefake-snapchat-location-on-your-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-apple-iphone-15-pro-max-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on Apple iPhone 15 Pro Max online without jailbreak</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-assessing-video-file-size-in-a-days-watching/"><u>In 2024, Assessing Video File Size in a Day's Watching</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-practices-a-guide-to-optimal-mobile-video-reduction/"><u>In 2024, Best Practices  A Guide to Optimal Mobile Video Reduction</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cinematic-tools-the-leading-camera-selections/"><u>In 2024, Cinematic Tools  The Leading Camera Selections</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-freshly-taken-images-dissection-and-secondary-ideas/"><u>In 2024, Freshly Taken Images Dissection & Secondary Ideas</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-apple-iphone-11-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on Apple iPhone 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-strategic-giants-identifying-the-prime-7-total-war-battles/"><u>In 2024, Strategic Giants  Identifying the Prime 7 Total War Battles</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-scroll-capslock-indicators-in-systemtray-win11/"><u>Incorporating Scroll, CapsLock Indicators in SystemTray Win11</u></a></li>
<li><a href="https://win11.techidaily.com/is-windows-scrolling-by-itself-heres-how-to-fix-it/"><u>Is Windows Scrolling By Itself? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directory-management-windows-11-techniques/"><u>Mastering Directory Management: Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/merge-gmail-with-outlook-on-windows-a-detailed-guide/"><u>Merge Gmail with Outlook on Windows: A Detailed Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-top-6-to-do-apps-for-windows/"><u>Navigating the Top 6 To-Do Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-for-professionals-automated-archive-operations/"><u>PowerShell for Professionals: Automated Archive Operations</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/ps4-broadcast-simplified-detailed-steps-using-obs-for-2024/"><u>PS4 Broadcast Simplified  Detailed Steps Using OBS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-keyboard-mastery-typingaids-way/"><u>Quick Keyboard Mastery - TypingAid's Way</u></a></li>
<li><a href="https://win11.techidaily.com/regular-update-reactivating-microsoft-store-on-windows-pcs/"><u>Regular Update: Reactivating Microsoft Store on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-delete-functionality-on-windows-systems/"><u>Reinstating Delete Functionality on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-ms-store-error-code-0x80073d26-on-windows-11-os/"><u>Remedying MS Store Error Code 0X80073D26 on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-code-0xa00f4243-for-multiple-camera-usage/"><u>Sidestepping Error Code: 0XA00F4243 for Multiple Camera Usage</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unblocked-files-via-powershell-on-pc/"><u>Simplifying Unblocked Files via PowerShell on PC</u></a></li>
<li><a href="https://win11.techidaily.com/solving-camera-problems-in-windows-like-a-pro/"><u>Solving Camera Problems in Windows Like a Pro</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unidentified-fingerprint-scanner-errors-in-windows/"><u>Solving Unidentified Fingerprint Scanner Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-restoring-the-functionality-of-windows-defenders-threat-barrier/"><u>Swift Remedies: Restoring the Functionality of Windows Defender's Threat Barrier</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-gone-security-questions-for-your-local-admin-user/"><u>The Guide to Gone Security Questions for Your Local Admin User</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-vintage-pc-a-step-by-step-guide-to-windows-11-to-go-and-rufus/"><u>Transform Your Vintage PC: A Step-by-Step Guide to Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-active-directory-errors-with-xp-devices/"><u>Troubleshooting Active Directory Errors with XP Devices</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-blocked-app-notification-in-windows/"><u>Troubleshooting Blocked App Notification in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win11-compatibility-with-google-play-store/"><u>Win11 Compatibility with Google Play Store</u></a></li>
</ul></div>
