---
title: The Art of Disassembling Dism for Image Recovery
date: 2024-06-25T11:31:47.546Z
updated: 2024-06-26T11:31:47.546Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Art of Disassembling Dism for Image Recovery
excerpt: This Article Describes The Art of Disassembling Dism for Image Recovery
keywords: Image Recovery Techniques,Dismassing Methods,Data Extraction Steps,Photo File Restoration,Disassembly Process,Digital Image Revival,Optimal Recover Tools
thumbnail: https://thmb.techidaily.com/f6caddae96019a4142339a6d719f3ef49075dd557e8c99c8c7fa75aee528315d.jpg
---

## The Art of Disassembling Dism for Image Recovery

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastery-setting-updeactivating-metric-tracker-in-win11/"><u>Mastery: Setting Up/Deactivating Metric Tracker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-keystroke-chaos-an-effective-guide-to-repair-common-windows-shortcut-issues/"><u>Banish Keystroke Chaos! An Effective Guide to Repair Common Windows Shortcut Issues</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nvidias-opengl-failure-no-3-in-windows-11/"><u>Eliminating NVIDIA's OpenGL Failure No. 3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-restart-your-windows-graphics-driver/"><u>How to Effectively Restart Your Windows Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/opera-stuck-swift-solutions-for-a-smooth-windows-patch/"><u>Opera Stuck? Swift Solutions for a Smooth Windows Patch</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-11s-6-unusual-visual-cues/"><u>Understanding Windows 11'S 6 Unusual Visual Cues</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-xiaomi-civi-3-disney-100th-anniversary-edition-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Xiaomi Civi 3 Disney 100th Anniversary Edition FRP</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-streamlining-production-workflow-extracting-audio-separately-on-a-mac-with-imovie/"><u>New Streamlining Production Workflow Extracting Audio Separately on a Mac with iMovie</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-effortless-audio-recording-on-chromeos-top-tips-for-success/"><u>In 2024, Effortless Audio Recording on ChromeOS Top Tips for Success</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/time-travellers-guide-sharing-past-photos-as-snaps/"><u>Time Traveller's Guide - Sharing Past Photos as Snaps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-the-swift-secrets-to-selecting-superior-screen-names/"><u>In 2024, The Swift Secrets to Selecting Superior Screen Names</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeo-cameo-review/"><u>In 2024, Vimeo Cameo Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-streaming-programs-for-live-content/"><u>[New] Leading Streaming Programs for Live Content</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-an-in-depth-examination-of-samsungs-picture-editing-tech/"><u>[Updated] An In-Depth Examination of Samsung’s Picture Editing Tech</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>