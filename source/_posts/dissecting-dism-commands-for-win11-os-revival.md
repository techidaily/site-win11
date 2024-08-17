---
title: Dissecting Dism Commands for Win11 OS Revival
date: 2024-08-16T00:42:47.435Z
updated: 2024-08-17T00:42:47.435Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dissecting Dism Commands for Win11 OS Revival
excerpt: This Article Describes Dissecting Dism Commands for Win11 OS Revival
keywords: Win11 Recovery Steps,Dissect Dism Usage,Windows Resurrection Guide,Dism Command Analysis,Win11 OS Restore,Reviving Windows XP,Win11 System Repair
thumbnail: https://thmb.techidaily.com/c2256048fdba19e150d130af22fa0ee9a49a1cc871ecb123979c39c8bac9ef09.jpg
---

## Dissecting Dism Commands for Win11 OS Revival

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-mastery-guide-securely-archiving-snapchat-media-on-devices/"><u>[New] 2024 Approved  Mastery Guide  Securely Archiving Snapchat Media on Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-accurate-mac-photography-mastery-of-five-proven-snapshot-ways/"><u>[Updated] 2024 Approved  Accurate Mac Photography  Mastery of Five Proven Snapshot Ways</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-eden-echoes-best-rural-role-playing-realms-for-2024/"><u>[Updated] Eden Echoes  Best Rural Role-Playing Realms for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-end-game-for-youtube-content-pros-secrets-and-templates/"><u>[Updated] In 2024, End Game for YouTube Content  Pros' Secrets & Templates</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-complete-guide-to-selecting-best-free-srt-translators-online/"><u>2024 Approved  The Complete Guide to Selecting Best FREE SRT Translators Online</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-realme-note-50-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-p55t-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Itel P55T</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-performance-trimming-high-memorycpu-usage-by-news-and-interests-apps-on-windows/"><u>Boosting Performance: Trimming High Memory/CPU Usage by News & Interests Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-your-dormant-device-speakers/"><u>Breathe Life Into Your Dormant Device Speakers</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ting-user-experience-with-personalized-youtube-card-implementation-for-2024/"><u>Elevating User Experience with Personalized YouTube Card Implementation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-typing-experience-speed-up-windows-keyboard-delay/"><u>Enhance Your Typing Experience: Speed Up Windows Keyboard Delay</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Infinix Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-ultimate-guide-to-video-dubbing-6-best-apps/"><u>New 2024 Approved The Ultimate Guide to Video Dubbing 6 Best Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-interactions-from-power-save-mode/"><u>Steering Device Interactions From Power Save Mode</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-store-issues-address-x80072f17/"><u>Streamlining Windows Store Issues: Address X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-woes-a-script-error-cure-all-guide/"><u>Tackling Windows Woes: A Script Error Cure-All Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-why-excel-opens-fail-in-notepad/"><u>Understanding Why Excel Opens Fail in Notepad</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>