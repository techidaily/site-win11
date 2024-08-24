---
title: Decoding Dism's Potential in Win11 System Restoration
date: 2024-08-23T06:11:27.917Z
updated: 2024-08-24T06:11:27.917Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding Dism's Potential in Win11 System Restoration
excerpt: This Article Describes Decoding Dism's Potential in Win11 System Restoration
keywords: Dism Win11 Restore,Dism System Reset,Dism Win11 Recovery,Windows Dism Tools,Win11 Dism Guide,System Restore with Dism,Dism Win10 Repair
thumbnail: https://thmb.techidaily.com/8b5881e327b9c1ba2eb90535b5e52b8fb37d29efd85f95b1f8c43ff4375091ae.jpg
---

## Decoding Dism's Potential in Win11 System Restoration

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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-free-software-strategies-for-efficient-educational-streaming/"><u>[New] 2024 Approved  Free Software Strategies for Efficient Educational Streaming</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-deciphering-the-language-of-haptic-interaction/"><u>2024 Approved  Deciphering the Language of Haptic Interaction</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715859966576-2024-approved-silent-blades-and-righteous-honor-your-next-game-adventure-awaits/"><u>2024 Approved  Silent Blades & Righteous Honor  Your Next Game Adventure Awaits!</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-secret-sauce-for-clearer-more-informative-youtube-videos/"><u>2024 Approved  The Secret Sauce for Clearer, More Informative YouTube Videos</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nokia-g22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-display-not-responding-on-windows-11/"><u>Correcting 'Display Not Responding' On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-steps-for-fixing-ms-store-crash-code-0x0-on-win-1011/"><u>Detailed Steps for Fixing MS Store Crash (Code 0X0) on Win 10/11</u></a></li>
<li><a href="https://techtrends.techidaily.com/diagnose-and-resolve-powerpoint-speaker-errors-expert-tips/"><u>Diagnose & Resolve PowerPoint Speaker Errors - Expert Tips</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-utilizing-condensed-explorer-settings/"><u>Enhance Visibility: Utilizing Condensed Explorer Settings</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-workflow-with-win-11s-auto-organize-functionality/"><u>Enhance Workflow with Win 11'S Auto-Organize Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-removing-inaccurate-tags-from-onedrive-reparse-points/"><u>Fix Guide: Removing Inaccurate Tags From OneDrive Reparse Points</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-a00f4289-webcam-issues-in-win1011/"><u>Fixing Error A00F4289: Webcam Issues in Win10/11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-leave-a-life360-group-on-infinix-hot-40-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Infinix Hot 40 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-sleep-on-win11/"><u>How to Reactivate Sleep on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-windows-component-services-manager/"><u>How to Use Windows Component Services Manager</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Redmi 12 5G? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-samsung-galaxy-m14-4g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Samsung Galaxy M14 4G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-ultimate-guide-to-real-time-audio-recording-in-the-digital-age/"><u>In 2024, The Ultimate Guide to Real-Time Audio Recording in the Digital Age</u></a></li>
<li><a href="https://win11.techidaily.com/increasing-pin-length-safely-on-windows-devices/"><u>Increasing Pin Length Safely on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-system-recovery-in-windows-10-and-11/"><u>Mastering File System Recovery in Windows 10 & 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/no-cost-all-benefits-with-fcp-downloads/"><u>No Cost, All Benefits with FCP Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-screen-limitations-with-effective-strategies/"><u>Overcome Screen Limitations with Effective Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-off-switch-on-network-sight-windows/"><u>Overhauling Off Switch on Network Sight Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protecting-yourself-from-counterfeit-chatgpt-alternatives-available-for-iphoneipad/"><u>Protecting Yourself From Counterfeit ChatGPT Alternatives Available for iPhone/iPad</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-boot-menu-colors/"><u>Restoring Legacy BOOT Menu Colors</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-the-clear-edge-tips-to-rectify-blurry-win11-displays/"><u>Reveal the Clear Edge: Tips to Rectify Blurry Win11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-obscured-filespace-with-altwindirstat/"><u>Reviving Obscured Filespace with AltWinDirStat</u></a></li>
<li><a href="https://win11.techidaily.com/securing-dialog-box-for-trusted-hardware-in-windows-11/"><u>Securing Dialog Box for Trusted Hardware in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-x80780119-error-windows-system-restore/"><u>Solving X80780119 Error: Windows System Restore</u></a></li>
<li><a href="https://win11.techidaily.com/start-with-windows-basic-tools-for-new-users/"><u>Start with Windows: Basic Tools for New Users</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-world-of-call-management-windows-11-dialer/"><u>Step Into the World of Call Management: Windows 11 Dialer</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-bypass-access-denied-issues-on-windows-pc/"><u>Strategies to Bypass 'Access Denied' Issues on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-operations-with-process-insight-and-elegant-theming-in-windows-11/"><u>Streamline Operations with Process Insight and Elegant Theming in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/taming-technology-turmoil-essential-techniques-for-windows-application-resets/"><u>Taming Technology Turmoil: Essential Techniques for Windows Application Resets</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-approach-to-unlock-your-start-menu-potential-in-windows-11/"><u>The Ultimate Approach to Unlock Your Start Menu Potential in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-guide-to-using-google-analytics-for-growth-for-2024/"><u>The Ultimate Guide to Using Google Analytics for Growth for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unreachable-ms-sql-server-for-malwarebytes-on-win-1011/"><u>Troubleshooting Unreachable MS SQL Server for Malwarebytes on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-your-resource-monitor-app-in-windows-11/"><u>Unfreezing Your Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-store-issue-code-0x80073cf3/"><u>Unlocking Windows Store Issue (Code 0X80073CF3)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-harmonizing-tech-with-creativity-best-10-song-editors-for-windowsmac-enthusiasts-for-2024/"><u>Updated Harmonizing Tech with Creativity – Best 10 Song Editors for Windows/Mac Enthusiasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-strategies-eradicating-disk-read-failures/"><u>Win Strategies: Eradicating Disk Read Failures</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-a-study-on-cloud-vs-physical-installation-methods/"><u>Windows Update: A Study on Cloud Vs. Physical Installation Methods</u></a></li>
<li><a href="https://win11.techidaily.com/winrar-file-integrity-6-strategies-for-checksum-precision/"><u>WinRAR File Integrity: 6 Strategies for Checksum Precision</u></a></li>
<li><a href="https://win11.techidaily.com/witness-windows-11-evolve-with-its-latest-moment-updates/"><u>Witness Windows 11 Evolve with Its Latest Moment Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-samsung-galaxy-z-flip-5-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Samsung Galaxy Z Flip 5? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/worldwide-unity-windows-encompasses-iphoneipad-macpc-communities/"><u>Worldwide Unity: Windows Encompasses iPhone/iPad, Mac/PC Communities</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>