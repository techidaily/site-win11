---
title: "Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
date: 2024-06-25T10:27:43.024Z
updated: 2024-06-26T10:27:43.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
excerpt: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
keywords: Windows Sandbox Woes,Hyproc Manager Missing,Sandbox Troubleshoot,Zero-Vulnerability Test,Non-Hyproc Window Sys,Tech Issue Resolution,Vulnerability Free Workspace
thumbnail: https://thmb.techidaily.com/6631d02aad6297e4d6f700e032b5f1a6df7f0a4821dff69d11f95fe1acb0191f.jpg
---

## Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor

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
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-key-combinations-for-effortless-recalibration/"><u>Mastering Windows: Key Combinations for Effortless Recalibration</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-and-essence-of-wintoys-an-uncomplicated-yet-comprehensive-explanation/"><u>The Power & Essence of 'WinToys': An Uncomplicated, Yet Comprehensive Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/transformational-taskbar-update-windows-system-resources-in-view/"><u>Transformational Taskbar Update: Windows System Resources in View</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-control-over-your-screen-amidst-the-dark/"><u>Reclaim Control Over Your Screen Amidst the Dark</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-top-8-best-fbx-game-recorder-alternatives/"><u>[Updated] 2024 Approved  Top 8 Best FBX Game Recorder Alternatives</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-achieve-seamless-retrieval-of-twitters-humor-gifs-on-your-system/"><u>In 2024, Achieve Seamless Retrieval of Twitter's Humor (GIFs) on Your System</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-audible-content-conversion-into-slide-ready-format-with-powerpoint/"><u>[New] Mastering Audible Content Conversion Into Slide-Ready Format with PowerPoint</u></a></li>
<li><a href="https://extra-skills.techidaily.com/optimal-energy-kits-for-gopro-hero5-genuine-and-third-party-brands-for-2024/"><u>Optimal Energy Kits for GoPro Hero5 – Genuine and Third-Party Brands for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-vibevault-download-and-spin-professional-dj-music/"><u>In 2024, VibeVault Download and Spin Professional DJ Music</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlined-social-integration-linktree-and-tiktok-profiles-united/"><u>[Updated] Streamlined Social Integration  Linktree and TikTok Profiles United</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-infinix-hot-40-pro-screen-sharing-drfone-by-drfone-android/"><u>How To Do Infinix Hot 40 Pro Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-nokia-g310-frp-by-drfone-android/"><u>How Can We Bypass Nokia G310 FRP?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-jaunt-vr-unleashed-an-in-depth-look/"><u>In 2024, Jaunt VR Unleashed  An In-Depth Look</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-clearer-streams-youtube-video-borderless-adjustment/"><u>[Updated] 2024 Approved  Clearer Streams  YouTube Video Borderless Adjustment</u></a></li>
</ul></div>
