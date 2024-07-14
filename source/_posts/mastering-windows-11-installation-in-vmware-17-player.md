---
title: Mastering Windows 11 Installation in VMWare 17 Player
date: 2024-07-13T10:24:47.367Z
updated: 2024-07-14T10:24:47.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows 11 Installation in VMWare 17 Player
excerpt: This Article Describes Mastering Windows 11 Installation in VMWare 17 Player
keywords: Win11_Installation_VMWare,VMWarePlayer_WindowsSetup,VMWareUltraClone_Win11,HyperV_Win11_Installer,Win11_Guide_VMware,Windows11_Installation_Virtual,Ultimate_VMWare_SetupWin11
thumbnail: https://thmb.techidaily.com/c522feb97d3790da90f4e047ee57c321868c402d131fe0f5a053db33ae9c232d.jpg
---

## Mastering Windows 11 Installation in VMWare 17 Player

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
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

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
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
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
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-creating-captivating-youtube-openers-two-ways/"><u>2024 Approved  Creating Captivating YouTube Openers - Two Ways</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-window-11-wallpaper-settings-for-individual-monitors/"><u>Navigating Window 11 Wallpaper Settings for Individual Monitors</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resurrect-inactive-windows-email-rule-configurations/"><u>Methods to Resurrect Inactive Windows Email Rule Configurations</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-looking-for-simple-steps-to-apply-fade-in-effect-to-your-text-in-premiere-pro-here-are-two-different-methods-along-with-an-alternative-way/"><u>New 2024 Approved Looking for Simple Steps to Apply Fade in Effect to Your Text in Premiere Pro? Here Are Two Different Methods Along with an Alternative Way to Fade Text in Videos</u></a></li>
<li><a href="https://win11.techidaily.com/make-the-best-out-of-what-you-have-even-without-11/"><u>Make the Best Out of What You Have, Even Without 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-mastering-gopro-quik-on-mac-effortless-video-editing/"><u>In 2024, Mastering GoPro Quik on Mac Effortless Video Editing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audiovisual-expertise-selecting-top-video-minds/"><u>Audiovisual Expertise  Selecting Top Video Minds</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-handle-printmanagement-service-failure/"><u>Essential Tips to Handle 'PrintManagement' Service Failure</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-amazing-techniques-of-motion-graphics-in-premiere-pro/"><u>New 2024 Approved Amazing Techniques of Motion Graphics in Premiere Pro</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-top-11-best-online-facebook-cover-photo-makers/"><u>[Updated] In 2024, Top 11 Best Online Facebook Cover Photo Makers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-windows-error-0xc0000001/"><u>Overcoming the Challenge of Windows Error 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-same-account-issues-on-a-device/"><u>Disentangling Same-Account Issues on a Device</u></a></li>
<li><a href="https://win11.techidaily.com/making-older-computers-more-comfortable-for-seniors/"><u>Making Older Computers More Comfortable for Seniors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-low-resource-utilization-wlanextexe/"><u>Mastering Low Resource Utilization: Wlanext.EXE</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-best-friends-at-your-feeds-disposal-topest-15-trusty-gratis-aid-sites/"><u>2024 Approved  Best Friends at Your Feed's Disposal  Topest 15 Trusty, Gratis Aid Sites</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-steps-to-clear-up-steam-errors-in-games-on-windows/"><u>Immediate Steps to Clear Up Steam Errors in Games on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-admin-imposed-setup-barriers/"><u>How to Tackle Windows 'Admin-Imposed' Setup Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/digital-canvas-on-windows-desktops-tips-and-tricks/"><u>Digital Canvas on Windows Desktops: Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hyper-v-installation-on-w11-home-edition/"><u>Mastering Hyper-V Installation on W11 Home Edition</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-windows-update-stuck-at-100-here-are-6-fixes/"><u>Is Your Windows Update Stuck at 100%%? Here Are 6 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-windows-11-a-guide-to-taskbar-search-functionality/"><u>Dive Into Windows 11: A Guide to Taskbar Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-file-system-errors-in-windows-10-and-11/"><u>How to Fix File System Errors in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/easing-frustrations-with-a-fix-to-non-working-pen-devices-in-windows/"><u>Easing Frustrations with a Fix to Non-Working Pen Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-barriers-reviving-spotify-streams/"><u>Overcoming Network Barriers: Reviving Spotify Streams</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>How to Turn Off Google Location to Stop Tracking You on Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-xiaomi-redmi-note-12-proplus-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Xiaomi Redmi Note 12 Pro+ 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pathway-to-choosing-between-game-and-studio-nvidia-drivers/"><u>Personalized Pathway to Choosing Between Game and Studio Nvidia Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-new-home-for-onedrive-folder-in-windows/"><u>Configuring New Home for OneDrive Folder in Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-upgrade-your-creativity-easy-steps-for-transforming-video-backgrounds-on-tiktok/"><u>[New] Upgrade Your Creativity  Easy Steps for Transforming Video Backgrounds on TikTok</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/streamlining-tiktok-twitter-integration/"><u>Streamlining TikTok-Twitter Integration</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-solid-state-drive-harnessing-power-of-windows-and-fresh/"><u>Elevate Your Solid State Drive - Harnessing Power of Windows & Fresh</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-guide-to-stunning-collage-artistry/"><u>[Updated] Step-by-Step Guide to Stunning Collage Artistry</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-perplexity-of-blued-in-windows-10/"><u>Overcoming the Perplexity of Blued in Windows 10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/assistance-by-danny-from-colombia-for-the-disadvantaged/"><u>Assistance by Danny From Colombia for the Disadvantaged</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Oppo A1 5G | Dr.fone</u></a></li>
</ul></div>
