---
title: "Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect"
date: 2024-09-05T08:30:10.479Z
updated: 2024-09-06T08:30:10.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect"
excerpt: "This Article Describes Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect"
keywords: Chkdsk Basics,ScanDisk Functionality,OS Maintenance Tips,Disk Repair Utility,VsChkdskFeatures,DissectOSTools,OptimizeSystemHealth
thumbnail: https://thmb.techidaily.com/64cbdaa1aef5615ff39347b9db4c0280ec8c3ce520d27154774aa65c3ef13831.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Explaining OS Maintenance: The Unique Traits of Chkdsk, Scan Disk Vs. Dissect

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115927/19272" target="_top" id="2115927">
  <img src="//a.impactradius-go.com/display-ad/19272-2115927" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/0-best-youtube-makeup-artists-you-should-follow-for-2024/"><u>[New] 10 Best YouTube Makeup Artists You Should Follow for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-screen-capture-in-depth-look-at-top-obs-tools/"><u>[New] 2024 Approved  Screen Capture  In-Depth Look at Top OBS Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-advanced-tips-for-accurate-and-smooth-hp-laptop-screen-capture-for-2024/"><u>[New] Advanced Tips for Accurate and Smooth HP Laptop Screen Capture for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-lenovos-screen-recording-an-in-depth-user-manual-for-2024/"><u>[New] Lenovo’s Screen Recording – An In-Depth User Manual for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-choreographing-compelling-cinematic-hooks-for-2024/"><u>[Updated] Choreographing Compelling Cinematic Hooks for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-2023-how-to-autoplay-facebook-videos/"><u>[Updated] In 2024, 2023 | How to Autoplay Facebook Videos?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-slay-the-game-designing-quirky-text-memes/"><u>2024 Approved  Slay the Game  Designing Quirky Text Memes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-upload-made-easy-your-device-based-guide-for-youtube-shorts/"><u>2024 Approved  Upload Made Easy  Your Device-Based Guide for YouTube Shorts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-infinix-smart-7-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Infinix Smart 7</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-windows-bar-to-reflect-internet-speed/"><u>Customizing Windows Bar to Reflect Internet Speed</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/elevate-online-presence-with-next-gen-tech-from-cookiebot/"><u>Elevate Online Presence with Next-Gen Tech From Cookiebot</u></a></li>
<li><a href="https://win11.techidaily.com/empower-your-pc-with-these-critical-windows-update-tips/"><u>Empower Your PC with These Critical Windows Update Tips</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fix-malfunctioning-windows-keyboard-buttons/"><u>Fix Malfunctioning Windows Keyboard Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unmute-yourself-on-google-meet-windows-edition/"><u>How to Unmute Yourself on Google Meet, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-graphics-prowess-in-windows-11s-shielded-mode/"><u>Leveraging Graphics Prowess in Windows 11'S Shielded Mode</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-cc-adjustments-in-windows-11/"><u>Mastering CC Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mending-failed-volume-backup-in-microsoft-os/"><u>Mending Failed Volume Backup in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/mending-window-11-opengl-driver-flaw-code-3/"><u>Mending Window 11 OpenGL Driver Flaw Code #3</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-high-end-hardware-overuse-in-games/"><u>Mitigating High-End Hardware Overuse in Games</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-git-branches-using-github-desktop-in-win-11/"><u>Navigating Git Branches Using GitHub Desktop in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-collaboration-and-efficiency-master-these-5-innovative-window-tips/"><u>Optimize Collaboration and Efficiency: Master These 5 Innovative Window Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-freeze-fixing-error-0x887a0006/"><u>Overcoming Device Freeze: Fixing Error 0X887A0006</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-grammarly-freeze-on-windows-systems/"><u>Overcoming Grammarly Freeze on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-experience-connection-issues-on-win-11/"><u>Overcoming Nvidia Experience Connection Issues on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-file-organization-skills-in-windows-11-edition/"><u>Perfect Your File Organization Skills in Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-non-working-shortcuts-guide-to-solving-win-11-issues/"><u>Rectify: Non-Working Shortcuts - Guide to Solving Win 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unauthorized-user-profile-issue-in-windows/"><u>Resolving Unauthorized User Profile Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-recalibration-windows-update-restart-guide/"><u>Streamlining System Recalibration: Windows Update Restart Guide</u></a></li>
<li><a href="https://win11.techidaily.com/switching-up-your-desktop-how-to-change-themes-in-win11/"><u>Switching Up Your Desktop: How To Change Themes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-resurrecting-non-operative-resource-monitors-in-win11/"><u>Tips & Tricks for Resurrecting Non-Operative Resource Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-window-to-climate-control-best-apps-for-windows-11/"><u>Ultimate Window to Climate Control: Best Apps for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-vcplusplus-distributor-functions/"><u>Understanding VC++ Distributor Functions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>