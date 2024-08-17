---
title: "Accelerating Virtualization: Setting Up Win11 with VMware 17 Player"
date: 2024-08-15T23:18:24.693Z
updated: 2024-08-16T23:18:24.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerating Virtualization: Setting Up Win11 with VMware 17 Player"
excerpt: "This Article Describes Accelerating Virtualization: Setting Up Win11 with VMware 17 Player"
keywords: Virtual Win11 Setup,Win11 VMware Player,Accelerate Win11 VM,Win11 VM Optimization,VMware Win11 Installation,Enhancing Win11 Virtualization,Win11 Virtual Setup Tips
thumbnail: https://thmb.techidaily.com/7111378cc0205319da99cc8db3992a3d311982c554186166a280e12ee8590487.png
---

## Accelerating Virtualization: Setting Up Win11 with VMware 17 Player

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.

## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on [how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Windows setup window, click on the**I don’t have a product key** option.
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
3. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-dynamic-duo-of-images-on-ig/"><u>[New] 2024 Approved  Dynamic Duo of Images on IG</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-cinematic-hope-the-top-10-inspirational-films/"><u>[Updated] 2024 Approved  Cinematic Hope  The Top 10 Inspirational Films</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-affordable-aerial-cameras-top-picks-under-100/"><u>[Updated] Affordable Aerial Cameras  Top Picks Under $100</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-fixing-problematic-youtube-shorts-thumbnails-display/"><u>[Updated] Fixing Problematic YouTube Shorts Thumbnails Display</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-vlc-users-guide-to-screen-capturing-for-2024/"><u>[Updated] VLC User's Guide to Screen Capturing for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-honor-x50-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Honor X50 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-comprehensive-examination-of-simple-hdr-methods-for-2024/"><u>A Comprehensive Examination of Simple HDR Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://games-able.techidaily.com/advantages-transitioning-console-players-to-pc-gaming/"><u>Advantages: Transitioning Console Players to PC Gaming</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-practices-for-capturing-streamed-television-for-2024/"><u>Best Practices for Capturing Streamed Television for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-x70-file-and-directory-recovery-on-windows-1011/"><u>Bypassing Error X70: File and Directory Recovery on Windows 10/11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capturing-brilliance-with-the-q500-drone/"><u>Capturing Brilliance with the Q500 Drone</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-edges-load-times-and-resource-use/"><u>Decreasing Edge's Load Times and Resource Use</u></a></li>
<li><a href="https://win-blog.techidaily.com/dota-5/"><u>Dota 지그재그즈 : 게임이 끝날 수 없는 방법, 플레이어가 찾아야 할 5가지 해결 방법</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/effortless-solution-the-ultimate-guide-to-repairing-damaged-dvds-with-minimal-fuss/"><u>Effortless Solution: The Ultimate Guide to Repairing Damaged DVDs with Minimal Fuss</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-for-getting-payday-2-running-smoothly-on-desktop-computers/"><u>Expert Tips for Getting Payday 2 Running Smoothly on Desktop Computers</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-lens-6-simple-steps-for-picture-spin-on-windows-11/"><u>Flip Your Lens: 6 Simple Steps for Picture Spin on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/gently-lowering-highs-a-guide-to-windowed-serenity/"><u>Gently Lowering Highs: A Guide to Windowed Serenity</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-life360-on-windows-pc-for-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Infinix Note 30 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-infinix-note-30-5g-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Infinix Note 30 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-k70e-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi K70E to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/league-of-legends-stability-tips-no-more-crashing/"><u>League of Legends Stability Tips - No More Crashing!</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-bsod-data-for-system-debugging/"><u>Leveraging BSOD Data for System Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-grans-old-computer-senior-friendly-and-simple/"><u>Make Your Gran’s Old Computer Senior-Friendly & Simple</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-characters-on-windows-11-screen/"><u>Navigating the Characters on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-your-guide-to-color-perfection-on-windows/"><u>Overcoming Obstacles: Your Guide to Color Perfection on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-default-heat-reduction-rules-in-winos/"><u>Reclaiming Default Heat Reduction Rules in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-copy-pasting-malfunctions-in-windows-11/"><u>Rectifying Copy-Pasting Malfunctions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/secrets-to-successfully-archive-facebook-messenger-chat/"><u>Secrets to Successfully Archive Facebook Messenger Chat</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unseen-second-monitor-problems/"><u>Solving Unseen Second Monitor Problems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-instructions-for-sending-print-outputs-to-pc-or-mac/"><u>Step-by-Step Instructions for Sending Print Outputs to PC or Mac</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-notes-obsidian-canvas-approach/"><u>Streamline Your Notes: Obsidian Canvas Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-xiaomi-redmi-a2-frp-by-drfone-android/"><u>The Updated Method to Bypass Xiaomi Redmi A2 FRP</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-essential-iphone-gadgets-and-add-ons-for-enhanced-performance/"><u>Top Essential iPhone Gadgets and Add-Ons for Enhanced Performance</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-tricks-making-powerful-yt-thumbnails/"><u>Top Tricks  Making Powerful YT Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://screen-recording.techidaily.com/ultimate-indoor-adventures-select-escapade-venues/"><u>Ultimate Indoor Adventures  Select Escapade Venues</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-access-navigating-localized-onedrive-files/"><u>Unplugged Access: Navigating Localized OneDrive Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>Unraveling Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-expect-from-microsofts-win11-feb-release/"><u>What to Expect From Microsoft's Win11 Feb Release</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-samsung-galaxy-f15-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Samsung Galaxy F15 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
</ul></div>
