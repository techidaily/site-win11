---
title: Mastering Windows 11 Installation in VMWare 17 Player
date: 2024-06-25T11:33:36.578Z
updated: 2024-06-26T11:33:36.578Z
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
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
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
<li><a href="https://win11.techidaily.com/ready-for-success-testing-your-meeting-tech-on-windows/"><u>Ready for Success: Testing Your Meeting Tech on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-clutter-windows-generative-erasure/"><u>Say Goodbye to Clutter: Windows' Generative Erasure</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-issues-with-windows-system-health-indicator/"><u>Remedying Issues with Windows System Health Indicator</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-quiet-slack-signals-on-windows-11-pcs/"><u>Reviving Quiet Slack Signals on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-automatic-shutdown-for-w10w11/"><u>Setting Up Automatic Shutdown for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-onedrive-lockout-windows-user-guide-needed/"><u>Reverse OneDrive Lockout: Windows User Guide Needed</u></a></li>
<li><a href="https://win11.techidaily.com/yourdevice-link-assessing-risks-and-benefits-in-w10-systems/"><u>YourDevice Link - Assessing Risks and Benefits in W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/windows-11-upgrade-blueprint-stepwise-system-revamping/"><u>Windows 11 Upgrade Blueprint  Stepwise System Revamping</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-how-to-make-an-animated-travel-map-video/"><u>Updated In 2024, How to Make an Animated Travel Map Video?</u></a></li>
<li><a href="https://some-skills.techidaily.com/teacher-created-videos-precision-in-cutting-and-splicing-for-2024/"><u>Teacher-Created Videos  Precision in Cutting & Splicing for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mastering-visual-storytelling-live-broadcasts-of-360-videos-on-facebook-for-2024/"><u>Mastering Visual Storytelling  Live Broadcasts of 360 Videos on Facebook for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-guide-to-choosing-win-compatible-drawing-software/"><u>A Guide to Choosing Win-Compatible Drawing Software</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-10-audio-alteration-apps-for-disguise-and-entertainment-for-2024/"><u>New Top 10 Audio Alteration Apps for Disguise and Entertainment for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flawlessly-merged-the-linkage-of-instagram-and-tiktok/"><u>2024 Approved  Flawlessly Merged  The Linkage of Instagram & TikTok</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-from-beginner-to-expert-a-comprehensive-guide-to-looping-your-favorite-vids/"><u>In 2024, From Beginner to Expert  A Comprehensive Guide to Looping Your Favorite Vids</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-civi-3-disney-100th-anniversary-edition-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Civi 3 Disney 100th Anniversary Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ideal-ps2-emulation-software-for-ios-users/"><u>[Updated] Ideal PS2 Emulation Software for IOS Users</u></a></li>
</ul></div>
