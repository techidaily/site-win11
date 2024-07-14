---
title: Step-by-Step Guide to Prepare Win11 in VMware 17 Player
date: 2024-07-13T10:05:06.606Z
updated: 2024-07-14T10:05:06.606Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Prepare Win11 in VMware 17 Player
excerpt: This Article Describes Step-by-Step Guide to Prepare Win11 in VMware 17 Player
keywords: Windows 11 Virtual Setup,Win11 VMware Installation,Prepare Win11 VM,VMware Player Guide,Win11 VM Guide Steps,Setting Up Win11 Virtual,Installing Windows 11 on VM
thumbnail: https://thmb.techidaily.com/c89ca4d2db8c8241f93b3a96e44489938109c01f6c557fc5515bb23aae45515d.JPG
---

## Step-by-Step Guide to Prepare Win11 in VMware 17 Player

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
<li><a href="https://win11.techidaily.com/top-7-steps-before-factory-clearing-a-pc/"><u>Top 7 Steps Before Factory Clearing a PC</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-pick-prime-photo-organizers-for-windows/"><u>Excellent Pick: Prime Photo Organizers For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unsigned-files-error-for-windows-1110/"><u>Bypassing Unsigned Files Error for Windows 11/10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-discover-the-best-movies-on-youtube-no-pay-required/"><u>[New] Discover the Best Movies on YouTube - No Pay Required</u></a></li>
<li><a href="https://win11.techidaily.com/curing-frozen-windows-desktop-context-options/"><u>Curing Frozen Windows Desktop Context Options</u></a></li>
<li><a href="https://win11.techidaily.com/stay-on-top-of-your-windows-11-devices-with-our-5-crucial-uptime-methods/"><u>Stay on Top of Your Windows 11 Devices with Our 5 Crucial Uptime Methods</u></a></li>
<li><a href="https://win11.techidaily.com/windows-blues-troubleshooting-rare-system-crashes/"><u>Windows Blues: Troubleshooting Rare System Crashes</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-samsung-galaxy-f54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-next-generation-virtual-collaboration-tools-post-zoom-era/"><u>[New] 2024 Approved  Next Generation Virtual Collaboration Tools, Post-Zoom Era</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-unlock-waxs-potential-a-beginners-guide-to-video-editing/"><u>Updated 2024 Approved Unlock Waxs Potential A Beginners Guide to Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-task-management-learn-filters-and-themes-customization-in-windows-11/"><u>Boost Productivity with Task Management: Learn Filters and Themes Customization in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-repairing-your-windows-11-printer/"><u>Essential Tips for Repairing Your Windows 11 Printer</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Realme C33 2023? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-moto-g84-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Moto G84 5GFRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/fan-the-fire-essential-tips-for-cooler-gameplay-on-overheated-windows-laptops/"><u>Fan the Fire: Essential Tips for Cooler Gameplay on Overheated Windows Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-go-no-net-with-your-new-os-win11/"><u>How to Go No Net With Your New OS, Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-comparing-cloud-space-charges-methods-and-results/"><u>[Updated] Comparing Cloud Space Charges  Methods and Results</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overwatch-2s-missing-graphics-driver-error/"><u>Fixing Overwatch 2'S Missing Graphics Driver Error</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-files-preventing-read-only-in-win11/"><u>Unlocking Your Files: Preventing Read-Only in Win11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-taking-flight-in-video-editing-a-drone-perspective/"><u>2024 Approved  Taking Flight in Video Editing  A Drone Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-your-microphone-usage-with-keyboard-techniques-for-win-11/"><u>Speeding Up Your Microphone Usage with Keyboard Techniques for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-11s-limited-editions-feature-impact/"><u>Assessing Windows 11’S Limited Editions Feature Impact</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-youtube-success-top-10-keyword-research-utilities-listed/"><u>2024 Approved  Unlocking YouTube Success  Top 10 Keyword Research Utilities Listed</u></a></li>
<li><a href="https://win11.techidaily.com/easing-shared-printer-usage-conflict/"><u>Easing Shared Printer Usage Conflict</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-trembling-cursor-a-guide-to-windows/"><u>Stop the Trembling Cursor: A Guide to Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-infinix-note-30-5g-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Infinix Note 30 5G FRP</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-8-innovative-tablets-changing-the-face-of-photo-editing-landscape/"><u>In 2024, 8 Innovative Tablets Changing the Face of Photo Editing Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-your-login-with-these-11-ultimate-tricks-to-open-windows-credentials/"><u>Speed Up Your Login with These 11 Ultimate Tricks to Open Windows Credentials</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-stalled-windows-batch-processes/"><u>Guide to Reactivating Stalled Windows Batch Processes</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-the-reserve-memory-concept/"><u>Unveiling Windows: The Reserve Memory Concept</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unveiling-the-secrets-to-a-flawless-fb-live-session-for-2024/"><u>[New] Unveiling the Secrets to a Flawless FB Live Session for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unlock-the-full-potential-of-snapkit-in-business-ads/"><u>[New] Unlock the Full Potential of SnapKit in Business Ads</u></a></li>
<li><a href="https://win11.techidaily.com/guide-recovering-invisible-bluetooth-in-device-manager/"><u>Guide: Recovering Invisible Bluetooth in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-comprehensive-policies-reports-via-gpresult/"><u>Crafting Comprehensive Policies Reports via GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-windows-embracing-ai-dominance/"><u>Tomorrow's Windows: Embracing AI Dominance</u></a></li>
<li><a href="https://win11.techidaily.com/faster-utorrent-file-sharing-a-guide-for-windows/"><u>Faster uTorrent File Sharing: A Guide for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-dll-file-disappearance-on-windows/"><u>Troubleshooting DLL File Disappearance on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11.</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-harmony-windows-app-compatible-with-apple-and-microsoft-pcsmacs/"><u>Cross-Platform Harmony: Windows App Compatible with Apple & Microsoft PCs/Macs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-capture-masters-expertly-reviewing-recorders-for-2024/"><u>[New] Capture Masters  Expertly Reviewing Recorders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/displaying-numeric-key-status-in-system-tray-for-win11-users/"><u>Displaying Numeric Key Status in System Tray for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-no-hypervisor-detection-in-sandbox-mode/"><u>How to Address No Hypervisor Detection in Sandbox Mode</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-a-spotless-system-restart-in-windows-11/"><u>Achieving a Spotless System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-no-notification-policy-for-ws11-cameras/"><u>Bypassing No-Notification Policy for WS11 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-read-only-folders-a-step-by-step-guide/"><u>Unlocking Read-Only Folders: A Step-by-Step Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-advanced-video-conversion-suites-for-2024/"><u>[Updated] Advanced Video Conversion Suites for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-deactivating-nvidias-visual-effects/"><u>Windows Guide: Deactivating NVIDIA's Visual Effects</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-5-tools-for-enhancing-web-videos/"><u>Top 5 Tools for Enhancing Web Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-novice-to-connoisseur-of-funimate-games/"><u>[New] From Novice to Connoisseur of Funimate Games</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-premier-advice-superior-iphone-audio-artists/"><u>2024 Approved  Premier Advice  Superior iPhone Audio Artists</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unresponsive-windows-service-error-error-1053/"><u>Eliminating the Unresponsive Windows Service Error (Error 1053)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-learn-to-master-character-voice-customization-the-ultimate-guide-to-transforming-in-game-speech-free/"><u>In 2024, Learn to Master Character Voice Customization  The Ultimate Guide to Transforming In-Game Speech (Free)</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-powerpoint-wont-record-audio-while-recording-the-screen-on-windows/"><u>What to Do if PowerPoint Won’t Record Audio While Recording the Screen on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-premier-racing-experience-series-top-5/"><u>[New] In 2024, Premier Racing Experience Series (Top 5)</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-realme-c67-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Realme C67 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/curating-a-personal-touch-for-windows-mouse-pointer/"><u>Curating a Personal Touch for Windows Mouse Pointer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-choice-webcams-boosting-podcast-quality-for-2024/"><u>Top Choice Webcams Boosting Podcast Quality for 2024</u></a></li>
</ul></div>
