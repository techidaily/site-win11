---
title: Troubleshooting Disk Failures on PC
date: 2024-09-22T16:24:22.376Z
updated: 2024-09-29T00:26:24.033Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Disk Failures on PC
excerpt: This Article Describes Troubleshooting Disk Failures on PC
keywords: Fix Disk Errors,Repair Hard Drive,Stop PC Breakdown,Resolve Drive Issues,Cure Storage Problems,Eliminate Data Loss,Fix Drive Failures
thumbnail: https://thmb.techidaily.com/7e858d7102e5ef6f6137f0acdeeba112d7b0daf0c9e0dad5ba4b3979a33bb860.jpg
---

## Troubleshooting Disk Failures on PC

 Errors and bugs can pop up on your Windows device, no matter how well you maintain it. One such error is related to your computer's disk, which can prevent your system from booting up properly and restrict access to your files and applications.

 Let's look at various methods to repair the disk issue on your Windows device.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does the "Repairing Disk Errors" Issue Occur?

 When the disk error occurs, your computer reboots with an error message: "**Repairing disk errors. This might take over an hour to complete.**" Most of the time, this error will just show up once and won't appear the next time you reboot, but sometimes it will show up every single time you boot your PC.

 Usually, this error is caused by:

* A sudden power failure.
* An improper system shutdown.
* Physical damage to your hard drive.
* Corrupted Windows system.

 Now let’s look at possible troubleshooting ways to fix the repairing disk error on your Windows device.

## 1\. Start With These Basic Fixes

 When your Windows computer starts showing disk errors, there are a few initial steps you can take before moving on to more advanced solutions. Here's what we recommend doing:

* **Wait for an hour to pass:** Sometimes, the easiest solution is to wait. If this is the first time you've encountered this error message in a while (if ever), give it an hour, and the error might resolve itself, allowing your computer to reboot normally.
* **Check your drive for physical damage:** If your drive has suffered physical damage, this can lead to this error constantly popping up. Inspect your disk drive for any damage.
* **Revert to a previous time with a System Restore point:** System Restore undoes recent system changes without affecting your files. If the error started appearing recently, try [using System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and see if that fixes things.

 If the above solutions are not working for you, it's time to get started with the advanced troubleshooting methods.

## 2\. Run the Startup Repair Utility

 The Startup Repair tool is a built-in Windows feature to fix problems preventing your computer from starting correctly. This tool can be a lifesaver if your system keeps encountering errors when booting up.

 Here's how you can use the Startup Repair tool on your computer:

1. Launch the Settings app and go to **System > Recovery**.
2. On the Settings window, click on **Restart now** button (located next to **Advanced startup**).  
![Advanced Startup Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-startup-option.jpg)
3. A blue-colored screen must appear now. From there, click on **Troubleshoot > Advanced options** and then **Startup Repair**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Startup Repair Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-repair-option.jpg)

 The repair tool will then scan for any corrupted files to repair. If this doesn't work, check out [what to do if Startup Repair fails to fix your PC](https://www.makeuseof.com/what-to-do-if-startup-repair-fails-to-repair-your-pc/).

 Once the repair process begins, avoid interrupting it or turning off your computer. Doing so could corrupt Windows even further.

## 3\. Run the SFC and CHKDSK Tools

 If the startup repair tool does not work, it's time to use the Command Prompt to run the System File Checker and CHKDSK tool.

 The System File Checker (SFC) tool checks your computer for any buggy system files and then tries to fix them. Most of the time, this resolves the disk error issue and other [startup issues on Windows](https://www.makeuseof.com/windows-11-startup-issues-fix/).

 Follow the steps given below to use the System File Checker and CHKDSK:

1. Launch the [Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. On the Command Prompt window, input the **sfc /scannow** command and then **Enter**.
3. Then, type **chkdsk %SystemDrive% /scan** and again press **Enter**.  
![CHKDSK SCAN Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command-preview.jpg)

 The above-given commands initiates a thorough scan of your system. It might take a while, and once completed, you should no longer see the black screen on startup.

 If you cannot access your desktop, you can also run the Command Prompt and the given commands via Windows safe mode.

 If these commands came in handy, be sure to check out all the [built-in Windows tools that repair corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948909/19272" target="_top" id="1948909">
  <img src="//a.impactradius-go.com/display-ad/19272-1948909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update the Disk Controller Driver

 The "disk controller driver" usually appears under a variety of names, like "Standard SATA AHCI" Controller. It is a Windows driver that establishes communication between your operating system and your hard drive. If the disk controller driver gets outdated, it can lead to disk-related errors.

 Follow these steps to update the disk controller driver on your PC:

1. Press **Win + X** and click on **Device Manager** from the menu.  
![Device Manager In Power Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/device-manager-in-power-menu.jpg)
2. Expand the **IDE ATA/ATAPI controllers** category. Right-click on your disk controller driver (in our case, **Standard SATA AHCI Controller**) and select **Update driver**.  
![Windows 11 Device Manager Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-device-manager-preview.jpg)
3. Choose **Search automatically for drivers**, then **Search for updated drivers on Windows Update**. Windows will then search for the necessary updates for your disk controller driver.  
![Windows 11 Update Drivers Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-update-drivers-window.jpg)
4. Once it installs the driver update, restart your computer. If the error black screen doesn't appear, it means your issue is resolved.

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Try a Third-Party Disk Repair Tool

 Sometimes the in-built Windows tools for troubleshooting are of no use. So, you have to depend on third-party tools to investigate the issue. We'll use a free tool called Macrorit Partition Expert for this guide.

 Third-party disk repair tools are not a sure-shot fix. They sometimes work and sometimes create more trouble with the system. So, before using any tool, [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) as a backup.

 Here's how to use the Macrorit Partition Expert tool on Windows:

1. Download the tool from [the Macrorit website](https://macrorit.com/partition-magic-manager/partition-expert-download.html) and install the application.
2. Click on **dm.exe** to run Macrorit Partition Expert.  
![Macrorit Partition Expert Files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-files.jpg)
3. On the application window, select the disk or volume where your current Windows is present. For example, in our case, it's in **Disk 0**.
4. After selecting, click on **Check Volume** from the left-hand sidebar.  
![Macrorit Partition Expert Application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-application.jpg)
5. Choose **Fix found errors**, **Try to fix found bad sectors**, and click **OK**.  
![Macrorit Partition Expert Volume Checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-volume-checker.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, Macrorit Partition Expert will analyze your selected disk to check for any bad sectors and try to fix them.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Factory Reset Windows

 If none of the fixes were helpful, you must reinstall Windows OS as a last resort. This will wipe all the data from your computer, so ensure to back up your important data.

 Once you've backed up your files, check out [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Once the reinstallation is complete, you'll have a clean slate to work with, and you can restore all the files you've backed up.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016134/19272" target="_top" id="2016134">
  <img src="//a.impactradius-go.com/display-ad/19272-2016134" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016134/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## No More Disk Errors on Windows

 As said earlier, there's no fixed reason for the repairing disk error. However, one thing that causes the error is an issue with your disks, such as bad sectors, physical damage, and viruses.

 If you fail to resolve the issue, consider resetting your computer and fresh set up everything.

 Let's look at various methods to repair the disk issue on your Windows device.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-8-free-instagram-to-mp4-converters-you-can-try-onlinewindowsmac-for-2024/"><u>[New] 8 Free Instagram to MP4 Converters You Can Try [Online/Windows/Mac] for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-what-is-igtv-and-how-to-use-it-everything-you-need-to-know/"><u>[New] What Is IGTV and How to Use It Everything You Need to Know</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-how-to-add-youtube-end-screen-and-cards-effectively/"><u>[Updated] 2024 Approved How to Add YouTube End Screen and Cards Effectively</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-elite-zoonotic-pattern-compendium/"><u>2024 Approved Elite Zoonotic Pattern Compendium</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-premium-mac-tool-seamless-screen-plus-voice-logging/"><u>2024 Approved Premium Mac Tool Seamless Screen + Voice Logging</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-11-software-removal-primer-top-11-approaches-114-chars/"><u>A Windows 11 Software Removal Primer: Top 11 Approaches (114 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-recovery-tactics-for-unavailable-defender-security-features/"><u>Accelerated Recovery Tactics for Unavailable Defender Security Features</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incompatible-format-in-windows-vlc-error/"><u>Addressing Incompatible Format in Windows VLC Error</u></a></li>
<li><a href="https://win11.techidaily.com/automating-success-windows-audio-at-system-startup/"><u>Automating Success: Windows Audio at System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-why-windows-dominates-in-gaming-landscape/"><u>Breaking Down Why Windows Dominates in Gaming Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-11s-access-denied-5-effective-remedies/"><u>Breaking Down Windows 11'S 'Access Denied': 5 Effective Remedies</u></a></li>
<li><a href="https://fox-that.techidaily.com/bypass-calling-problems-on-your-iphone-10-effective-fixes-you-need-to-know/"><u>Bypass Calling Problems on Your iPhone - 10 Effective Fixes You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-usability-widgets-for-your-desktop/"><u>Enhancing Windows 11 Usability: Widgets for Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/1719313398544-maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-the-ultimate-guide-to-creating-viral-reaction-videos-with-filmora-for-2024/"><u>New The Ultimate Guide to Creating Viral Reaction Videos with Filmora for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-vivo-v27-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Vivo V27 Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719285802254-say-goodbye-to-troubleshooting-woes-on-vistawindows-7/"><u>Say Goodbye to Troubleshooting Woes on Vista/Windows 7.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    