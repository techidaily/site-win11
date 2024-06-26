---
title: How to Address No Hypervisor Detection in Sandbox Mode
date: 2024-06-25T11:34:48.501Z
updated: 2024-06-26T11:34:48.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Address No Hypervisor Detection in Sandbox Mode
excerpt: This Article Describes How to Address No Hypervisor Detection in Sandbox Mode
keywords: Sandbox Vulnerability,Hypervisor Hideout,Sandbox Security Fix,Non-Detective VMware,No-Detection Coding,Escape Mode Defense,Detection Skirting Sandbox
thumbnail: https://thmb.techidaily.com/9482ded5e871af812d18f96a64c4deb315943988e9201916667eb608e7a9ffd3.jpg
---

## How to Address No Hypervisor Detection in Sandbox Mode

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

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out[how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

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

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

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
<li><a href="https://win11.techidaily.com/command-line-trick-turn-off-nvidias-visual-effects/"><u>Command Line Trick: Turn Off NVIDIA's Visual Effects</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-apples-messaging-on-your-windows-machine/"><u>Embracing Apple's Messaging on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-regain-basic-windows-settings-after-restart/"><u>Guide to Regain Basic Windows Settings After Restart</u></a></li>
<li><a href="https://win11.techidaily.com/chronicle-reclaim-unearthing-windows-11s-archive/"><u>Chronicle Reclaim: Unearthing Windows 11'S Archive</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-without-mishap-avoiding-errors-in-windows-11/"><u>Navigating Without Mishap: Avoiding Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-memory-integrity-feature-grayed-out-on-windows-11/"><u>7 Ways to Fix the Memory Integrity Feature Grayed Out on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-writing-errors-for-files-in-windows-systems/"><u>Overcoming Writing Errors for Files in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-autonomous-windows-speech-transcription-app-with-whisper-aid/"><u>Crafting an Autonomous Windows Speech Transcription App with Whisper Aid</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-unlock-fcp-xs-power-adding-effects-in-just-3-clicks/"><u>New 2024 Approved Unlock FCP Xs Power Adding Effects in Just 3 Clicks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-instagram-editors-handbook-maximizing-video-impact-for-2024/"><u>The Instagram Editor's Handbook  Maximizing Video Impact for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-no-cost-3gp-video-rotation-solutions-top-5-tools-you-need/"><u>Updated In 2024, No-Cost 3GP Video Rotation Solutions Top 5 Tools You Need</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-creative-teaching-incorporating-youtube-into-your-curriculum/"><u>[Updated] Creative Teaching  Incorporating YouTube Into Your Curriculum</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fine-tune-viewing-the-ultimate-zoom-journey/"><u>In 2024, Fine-Tune Viewing  The Ultimate Zoom Journey</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-oppo-find-x7-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Oppo Find X7 Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-seamless-transfer-of-tiktok-content-to-your-facebook-page-for-2024/"><u>[New] Seamless Transfer of TikTok Content to Your Facebook Page for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-streamlining-presentations-webcam-screen-capture-techniques/"><u>In 2024, Streamlining Presentations  Webcam Screen Capture Techniques</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-how-to-make-a-video-a-live-photo/"><u>New How to Make a Video a Live Photo</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-reimagining-your-tiktok-presence-step-by-step-renaming-process/"><u>[New] In 2024, Reimagining Your TikTok Presence  Step-by-Step Renaming Process</u></a></li>
</ul></div>
