---
title: Overcoming Windows Media Maker's Code 0X8007043C Issue
date: 2024-07-13T10:58:19.362Z
updated: 2024-07-14T10:58:19.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Media Maker's Code 0X8007043C Issue
excerpt: This Article Describes Overcoming Windows Media Maker's Code 0X8007043C Issue
keywords: WMMA Error Fixing,Solve WMPlayer Crash,Overcome WMV Tool Error,XCode8007043C Resolution,Windows Media Maker Troubleshooting,Handling WM Media Code 0X43C,Fixing WMV Compile Failure
thumbnail: https://thmb.techidaily.com/20c69587162d153f03eefa64dab5fb5356740a9d42978b0299a0a4d322290d05.jpeg
---

## Overcoming Windows Media Maker's Code 0X8007043C Issue

 The Media Creation Tool lets you upgrade your PC to a new Windows version or create a bootable Windows USB drive. At times, when you try to run the tool, you may encounter the error code 0x8007043C - 0x90017.

 The primary reason for this error is insufficient permission to run the tool or if it has been blocked from running on your PC. You can unblock it from the tool's properties to fix the error. Here is how to fix the Media Creation Tool 0x8007043C - 0x90017 error and perform an upgrade or create a bootable drive.

## 1\. Run the Media Creation Tool as an Administrator

 You can fix permission issues by executing the Media Creation Tool with administrator privileges. By default, the tool does not require administrator rights to run. But you can [manually run Windows apps as an administrator](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) to see if that resolves the error.

To run Media Creation Tool as administrator:

1. Open File Explorer and navigate to where you have saved the**mediacreationtool.exe** file.
2. Right-click on the**Mediacreationtool.exe** file and select**Run as administrator.**  
![run media creation tool as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-media-creation-tool-as-administrator.jpg)
3. Click**Yes** when prompted by UAC. Wait for the tool to launch and check for any improvements.

## 2\. Unblock the Media Creation Tool

 Windows can block suspicious executable files from running to protect your computer. However, it can also block genuine files due to false positives.

 If you have downloaded the Media Creation Tool from the Microsoft website, check if the file is blocked on your PC. If yes, you can unblock the executable file from the Properties dialog. Here’s how to do it.

1. Navigate to the location where the Media Creation Tool is saved.
2. Select and right-click on the tool and select**Properties** .
3. In the**General** tab, locate the**Security** section.
4. Next, check the**Unblock** option.  
![unblock media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unblock-media-creation-tool.jpg)
5. Click**Apply** , and the security option will disappear.
6. Next, click**OK** to apply the changes.
7. Run the Media Creation Tool again, and it should work without the 0x8007043C - 0x90017 error.

## 3\. Install Any Pending Windows Updates

 If the error occurs during an upgrade, ensure you have installed all the latest updates available for your PC. Often Windows updates consist of performance improvements and bug fixes. Install all the updates to see if that helps you resolve any issues interrupting the upgrade process.

To update your Windows computer:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows update** tab in the left pane.
3. Click on**Check for updates** to find the pending updates.  
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)
4. If available, click on**Download & Install** and wait for the updates to install. Restart your PC and run the tool again to see if the error is resolved.

## 4\. Run the Windows Update Troubleshooter

 The built-in Windows Update troubleshooter is a great way to fix Windows Update issues on Windows 11\. It will scan the system for issues and try to fix them automatically.

To run the Windows Update Troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .  
![Windows 11 settings troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot.jpg)
3. Next, click on**Other troubleshooters.**  
![Windows-11-settings-troubleshoot-other-troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot-other-troubleshooters.jpg)
4. Under the**Most frequent** section, click the**Run** button for**Windows Update.**  
![windows update troubleshooter run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-run.jpg)
5. The update troubleshooter will initialize diagnostic and scan for issues. If found, it will apply the fix and show a status report. With the Windows Update dialog open, run Media Creation Tool and check if the error is resolved.
6. If not, click**No** in the Windows Update troubleshooter dialog.
7. Next, click on**View detailed** information. Here you can view the issues found and potential issues that were checked.

## 5\. Check for a Third-Party Antivirus Conflict

 Third-party antivirus can be overzealous and block genuine system modifications as malicious. You can disable the security app temporarily to determine if your third-party antivirus is triggering the error.

 Once disabled, relaunch the Media Creation Tool and check if the error persists. If not, check and reconfigure your antivirus settings or switch to one of the [best antivirus solutions on Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) .

## 6\. Run the DISM and System File Checker Tool

 Deployment Image Servicing and Management (DISM) is a command-line tool to repair your Windows 10 and 11 images. It can look for corrupted or missing system files and repair them to fix critical errors on your PC.

 System File Checker utility can help you fix malfunctioning Windows functions. It will scan the system for issues and, if detected, restore the necessary files to fix the problem. You can run the DISM and System File Checker tools in tandem to get the best result. Here’s how to do it.

To run the DISM and System File Checker Tool:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command** **Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command to run the DISM tool:  
DISM.exe /Online /Cleanup-image /Restorehealth
4. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt.jpg)  
 Press**Enter** to execute the command. It may take some time for the process to complete. Once the process reaches 100%, you can run the System File Checker tool.
5. Type the following command and press**Enter** to run the System File Checker utility:  
sfc /scannow
6. The verification can take several minutes. So wait for the verification to reach 100%. The return will indicate if any issue is found and if the tool was able to fix it.
7. Type**exit** and press**Enter** to close the Command Prompt.

## 7\. Use Rufus to Create a Bootable USB Drive

 While Media Creation Tools lets you create a bootable drive, it is not your only option. You can use a popular third-party app, Rufus, to [create a bootable Windows USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/) . You can [download a Windows 11 ISO file](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft servers and then use it to create an installation media using Rufus.

 Rufus is safe to use and offers some customization, such as choosing a partition format. You can also download the ISO file using Rufus.

## 8\. Perform a Repair Reinstall or Clean Install Windows

 Before we do a full clean of Windows, consider performing a repair reinstall. This allows you to perform an in-place upgrade and [reinstall the Windows OS without deleting your files and apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) .

 If all else fails, a clean install may be necessary. Make sure to create a backup of your data and then learn [how to clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/) .

## Fixing the Media Creation Tool Error 0x8007043C - 0x90017 Error

 The 0x8007043C - 0x90017 Media Creation Tool error is often due to an insufficient permission issue. You can unblock the utility in the Properties dialog to run the utility without the error. Only in rare instances, you may need to perform a clean install due to system file corruption.


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
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-restoring-network-link-in-windows/"><u>Steps for Restoring Network Link in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-rewind-game-pc-redemption/"><u>AtlasOS Rewind: Game PC Redemption</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1110-onedrive-errors/"><u>Troubleshooting Windows 11/10 OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-from-the-windows-11-compatibility-shackles/"><u>Unlocking Your PC From the Windows 11 Compatibility Shackles</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-immersive-narratives-vr-storytelling-breakthroughs/"><u>2024 Approved  Immersive Narratives  VR Storytelling Breakthroughs</u></a></li>
<li><a href="https://games-able.techidaily.com/acquiring-ps5-steamboat-to-fortnite-vip-points/"><u>Acquiring PS5: Steamboat to Fortnite VIP Points</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-halting-windows-boot-straight-into-cmos-setup/"><u>Techniques for Halting Windows Boot Straight Into CMOS Setup</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/cut-down-on-effort-schedule-fb-posts-for-free-for-2024/"><u>Cut Down on Effort  Schedule Fb Posts for Free for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-quadcopter-showdown-dji-pro-and-hero-4-black/"><u>2024 Approved  Quadcopter Showdown  DJI Pro and Hero 4 Black</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-anonymous-glimpse-into-fb-flashbacks-for-2024/"><u>[Updated] Anonymous Glimpse Into FB Flashbacks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-and-mitigating-windows-pause-problems/"><u>Uncovering and Mitigating Windows Pause Problems</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-blend-excelling-at-classic-games-in-hd-clarity-through-scummvm-on-windows/"><u>The Perfect Blend: Excelling at Classic Games in HD Clarity Through ScummVM on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://win11.techidaily.com/winfreedomgpt-guide-launching-unrestricted-chatbots/"><u>WinFreedomGPT Guide: Launching Unrestricted ChatBots</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-cutting-edge-techniques-for-capturing-ps4-games-in-obs/"><u>[New] Cutting-Edge Techniques for Capturing PS4 Games in OBS</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-depth-guide-to-selective-zoom-in-virtual-classrooms-google-meet/"><u>In-Depth Guide to Selective Zoom in Virtual Classrooms (Google Meet)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-stalled-resource-monitors-procedure-in-windows-11/"><u>Streamlining Stalled Resource Monitors: Procedure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transformative-tips-for-a-productive-win-11-bar/"><u>Transformative Tips for a Productive Win 11 Bar</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ace-the-art-of-game-recordings-in-windows-11/"><u>[Updated] Ace the Art of Game Recordings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-system-information-tool-on-windows/"><u>10 Ways to Open the System Information Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/win11-wi-fi-data-metric-control-guide/"><u>Win11 Wi-Fi Data Metric Control Guide</u></a></li>
<li><a href="https://win11.techidaily.com/prose-perfection-on-a-windows-desktop-the-top-5-picks/"><u>Prose Perfection on a Windows Desktop - The Top 5 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-windows-with-5-mac-inspired-ideas/"><u>Simplify Your Windows with 5 Mac-Inspired Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/restore-optional-features-on-windows-os-with-ease/"><u>Restore Optional Features on Windows OS with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-cleaner-windows-11-desktop-layout/"><u>Designing a Cleaner Windows 11 Desktop Layout</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-no-audio-output-on-win-10-devices/"><u>Tackling Error: No Audio Output on Win 10 Devices</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-get-acquainted-with-the-10-best-sketching-apps-for-chrome-os/"><u>2024 Approved  Get Acquainted with The 10 Best Sketching Apps for Chrome OS</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-unsolicited-search-window-opens-in-windows-11/"><u>Stopping Unsolicited Search Window Opens in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/mp3-to-mp4-converter-how-to-convert-mp3-to-mp4/"><u>MP3 to MP4 Converter How to Convert MP3 to MP4?</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-docker-setup-tips-for-optimized-wsl-2-use/"><u>Elevate Your Docker Setup: Tips for Optimized WSL 2 Use</u></a></li>
<li><a href="https://extra-skills.techidaily.com/podcast-dominance-through-powerful-seo-tactics-for-2024/"><u>Podcast Dominance Through Powerful SEO Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/set-up-a-stunning-slideshow-easily-create-in-win11-heres-how/"><u>Set Up a Stunning Slideshow: Easily Create in Win11 Here’s How</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/optimized-video-engagement-with-peak-post-times/"><u>Optimized Video Engagement with Peak Post Times</u></a></li>
<li><a href="https://win11.techidaily.com/unshackling-your-powershell-scripts-top-4-strategies-for-execution-lift/"><u>Unshackling Your PowerShell Scripts: Top 4 Strategies for Execution Lift</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-windows-selection-of-best-nintendo-switch-imitators/"><u>Exclusive Windows Selection of Best Nintendo Switch Imitators</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-must-use-livestream-shopping-apps-for-seamless-online-system-for-2024/"><u>New Must-Use Livestream Shopping Apps for Seamless Online System for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win1011-nvidia-opengl-error-3/"><u>Overcoming Win10/11 NVIDIA OpenGL Error 3</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-sandbox-a-win-11-guide/"><u>Configure Your Sandbox: A Win 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-routine-file-explorer-revival-tips-for-win-11/"><u>Rebooting Routine: File Explorer Revival Tips for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/wu-and-orchestrator-the-pillars-of-update-routine/"><u>WU & Orchestrator: The Pillars of Update Routine</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-deciphering-online-videography-a-facebook-journey/"><u>[Updated] In 2024, Deciphering Online Videography  A Facebook Journey</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-camera-error-a00f4289-in-windows-environments/"><u>Eradicating Camera Error A00F4289 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-with-a-side-of-kali-linux/"><u>Securing Windows with a Side of Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-organize-your-pcenas-7-prime-windows-photos-tools/"><u>Effortlessly Organize Your PC'enas: 7 Prime Windows Photos Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-propel-participation-through-tailored-story-inquiry-designs/"><u>[New] In 2024, Propel Participation Through Tailored Story Inquiry Designs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-understanding-satire-building-parodies-online/"><u>2024 Approved  Understanding Satire  Building Parodies Online</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-jokes-and-puns-iphone-edition/"><u>2024 Approved  Jokes and Puns  IPhone Edition</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-seeking-out-wolves-haunting-howls-in-audio-form/"><u>2024 Approved Seeking Out Wolves Haunting Howls in Audio Form</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-key-techniques-for-a-thorough-review-of-youtube-stats/"><u>[New] Key Techniques for a Thorough Review of YouTube Stats</u></a></li>
<li><a href="https://screen-recording.techidaily.com/pioneering-innovative-webcam-functions-for-2024/"><u>Pioneering Innovative Webcam Functions for 2024</u></a></li>
</ul></div>
