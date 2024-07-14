---
title: Identifying and Fixing Absence of Hypervisor on Windows Sandbox
date: 2024-07-13T09:44:13.639Z
updated: 2024-07-14T09:44:13.639Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identifying and Fixing Absence of Hypervisor on Windows Sandbox
excerpt: This Article Describes Identifying and Fixing Absence of Hypervisor on Windows Sandbox
keywords: Hypervisor Window Fix,Sandbox Error Resolve,Windows VM Absence,Hyper-V Detection,Virtualization Glitch,Hyper-VM Windows Issue,Windows Sandbox Check
thumbnail: https://thmb.techidaily.com/f8310fb64fe59131a1a603b74493ef91ec9be3bf91a44a7ee26654a9f6fff3c0.jpg
---

## Identifying and Fixing Absence of Hypervisor on Windows Sandbox

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.


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
<li><a href="https://youtube-clips.techidaily.com/a-compreshift-guide-to-creating-profitable-and-engaging-youtube-collaborations/"><u>A Compreshift Guide to Creating Profitable & Engaging YouTube Collaborations</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-vms-from-windows-host-to-linux-guest-with-hyper-v/"><u>Setting Up VMs: From Windows Host to Linux Guest with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-printer-friendly-presentations-on-windows/"><u>Mastering the Art of Printer-Friendly Presentations on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-samsung-galaxy-f34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/prodigy-preparation-must-haves-from-microsoft-store/"><u>Prodigy Preparation: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-conquer-screen-capture-in-depth-windows-pc-guide-for-live-tv-recording/"><u>[New] 2024 Approved  Conquer Screen Capture  In-Depth Windows PC Guide for Live TV Recording</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-to-download-movie-cast-releases/"><u>2024 Approved  Free-to-Download Movie Cast Releases</u></a></li>
<li><a href="https://win11.techidaily.com/create-a-distinctive-color-scheme-in-wt-terminal/"><u>Create a Distinctive Color Scheme in WT Terminal</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-guide-to-using-luts-perfectly-in-final-cut-pro/"><u>2024 Approved Guide To Using Luts Perfectly in Final Cut Pro</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-y78plus-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo Y78+</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-transfer-files-on-a-network-using-a-python-server-on-windows/"><u>How to Transfer Files on a Network Using a Python Server on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-upgrade-failure-in-windows-11-error-0x800f0922/"><u>Steps to Fix Upgrade Failure in Windows 11 - Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outlook-stuck-in-safe-mode-a-step-by-step-solution/"><u>Overcoming Outlook Stuck in Safe Mode: A Step-by-Step Solution</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-audio-equipment-for-crystal-clear-4k-video-capture/"><u>[New] Top Audio Equipment for Crystal Clear 4K Video Capture</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eradicating-system-call-failed-problem-in-windows-11/"><u>Steps for Eradicating System Call Failed Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-prevent-windows-control-center-crashes/"><u>Quick-Fix Guide to Prevent Windows Control Center Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-error-0xc0000001-efficiently/"><u>How To Tackle Windows Error 0xC0000001 Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/"><u>Renaissance PC: Refresh with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/easy-access-mastering-folders-and-files-props/"><u>Easy Access: Mastering Folders and Files Props</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-rectifying-confirm-pin-error-in-w11w10-setups/"><u>Guides to Rectifying Confirm PIN Error in W11/W10 Setups</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-windows-os-issues/"><u>Quick Guide to Resolving Common Windows OS Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-elusive-theme-options-through-registry/"><u>Mastering Windows 11'S Elusive Theme Options Through Registry</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-vivo-s18-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Vivo S18 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-interaction-on-windows-discord-app/"><u>Enhancing Live Interaction on Windows Discord App</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-unresponsive-plugins-in-fcpx-heres-what-you-need-to-do/"><u>2024 Approved Unresponsive Plugins in FCPX? Heres What You Need to Do</u></a></li>
<li><a href="https://win11.techidaily.com/redirecting-onedrive-location-in-windows-10/"><u>Redirecting OneDrive Location in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/sync-windows-display-avoiding-overscan-limitations/"><u>Sync Windows Display: Avoiding Overscan Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-permissions-management-in-w11-domains/"><u>Navigating Permissions Management in W11, Domains</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-top-8-troubleshooting-steps/"><u>Mastering Windows: Top 8 Troubleshooting Steps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-art-of-amplifying-audience-engagement-on-igtv/"><u>[New] The Art of Amplifying Audience Engagement on IGTV</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-taskbar-tweaks-in-windows-11/"><u>Expert Guide to Taskbar Tweaks in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-most-effective-windows-to-do-apps/"><u>Navigating the Most Effective Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/prime-time-performance-top-5-wins-speed-up-solutions/"><u>Prime Time Performance: Top 5 Win's Speed-Up Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/recover-missing-wireless-signal-a-windows-10-solution-guide/"><u>Recover Missing Wireless Signal: A Windows 10 Solution Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-management-navigating-through-network-tools-on-window/"><u>Effortless Management: Navigating Through Network Tools on Window</u></a></li>
<li><a href="https://win11.techidaily.com/rav-antivirus-intrusion-origin-and-removal-guide/"><u>Rav Antivirus Intrusion: Origin & Removal Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-vivo-y36-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Vivo Y36 PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-3-in-nvidia-opengl-win10-and-11/"><u>Eliminating Error Code 3 in NVIDIA OpenGL (Win10 & 11)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/is-the-smoothing-effect-in-photoshop-a-game-changer-or-not-for-2024/"><u>Is the Smoothing Effect in Photoshop a Game Changer or Not for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-realme-12-5g-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Realme 12 5G</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-secure-your-contents-identity-adding-logo-and-watermark-to-videos/"><u>In 2024, Secure Your Content's Identity  Adding Logo and Watermark to Videos</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-email-banners-in-windows-os/"><u>Solving Disabled Email Banners in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-silent-windows-headset-mic/"><u>Mending Your Silent Windows Headset Mic</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-exclusive-free-mcb-banner-designs/"><u>In 2024, Exclusive Free MCB Banner Designs</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-for-local-admin-credentials-on-windows-11/"><u>Stealth Mode for Local Admin Credentials on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-find-my-friends-work-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overmal-restarting-windows-11-software/"><u>Mastery Overmal: Restarting Windows 11 Software</u></a></li>
</ul></div>
