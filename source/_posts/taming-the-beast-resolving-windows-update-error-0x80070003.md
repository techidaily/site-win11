---
title: "Taming the Beast: Resolving Windows Update Error 0X80070003"
date: 2024-09-11T09:42:43.339Z
updated: 2024-09-12T09:42:43.339Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Taming the Beast: Resolving Windows Update Error 0X80070003"
excerpt: "This Article Describes Taming the Beast: Resolving Windows Update Error 0X80070003"
keywords: Fixing Windows UpdErr,Solve WinUpdate Fail,Eliminate UpdError X8007,Overcoming Windows ErrX,Stop Update Error WIN,Correct Windows Update X08,Remedying WinUpdFailure
thumbnail: https://thmb.techidaily.com/c67c5cabd77bd497290dc569fa7f62d814f0daa9ae95d19e4c91539b2a1b2dd0.jpg
---

## Taming the Beast: Resolving Windows Update Error 0X80070003

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137972/21526" target="_top" id="2137972">
  <img src="//a.impactradius-go.com/display-ad/21526-2137972" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137972/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114264/17093" target="_top" id="2114264">
  <img src="//a.impactradius-go.com/display-ad/17093-2114264" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114264/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-ultimate-list-of-social-media-analytics-for-instagram-excellence/"><u>[New] 2024 Approved The Ultimate List of Social Media Analytics for Instagram Excellence</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-smirk-stash-ultimate-guide-to-free-meme-templates/"><u>[New] Smirk Stash Ultimate Guide to FREE Meme Templates</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-explore-artistic-possibilities-premier-android-graphics-app-selection/"><u>[Updated] Explore Artistic Possibilities Premier Android Graphics App Selection</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximize-content-experience-with-these-top-6-youtube-shorts-downloader-apps/"><u>[Updated] Maximize Content Experience with These Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-pros-secret-windows-11-gems-uncovered/"><u>2024 Approved Pro's Secret Windows 11 Gems Uncovered</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capture-and-store-nine-excellent-windows-tools-for-animation-gifs-for-2024/"><u>Capture and Store Nine Excellent Windows Tools for Animation GIFs for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/clear-out-liked-songs-from-your-playlist-a-users-guide-for-spotify/"><u>Clear Out Liked Songs From Your Playlist - A User's Guide for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-simplified-your-companion-for-w11-transitioning/"><u>DevHome Simplified: Your Companion for W11 Transitioning</u></a></li>
<li><a href="https://win11.techidaily.com/direct-guide-square-windows-interface/"><u>Direct Guide: Square Windows' Interface</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722975006440-download-the-latest-hp-deskjet-ink-advantage-3050a-driver-software-for-windows-no-cost/"><u>Download the Latest HP Deskjet Ink Advantage 3050A Driver Software for Windows - No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0xc00ce556-in-winoss-parsing/"><u>Eliminating Error 0xC00CE556 in WinOSs PARSING</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-windows-performance-data-accuracy/"><u>Ensuring Windows Performance Data Accuracy</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insight-converting-esd-files-to-iso-on-windows-machines/"><u>Essential Insight: Converting ESD Files to ISO on Windows Machines</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/financial-fortune-with-facebook-video-marketing-key-strategies-explored/"><u>Financial Fortune with Facebook Video Marketing Key Strategies Explored</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-lock-apps-on-sony-xperia-5-v-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Sony Xperia 5 V to Protect Your Individual Information</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-step-by-step-to-becoming-a-9gag-meme-genius/"><u>In 2024, Step-by-Step to Becoming a 9GAG Meme Genius</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-edge-2023-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola Edge 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/laughlenslab-pixelpunchers/"><u>LaughLensLab PixelPunchers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-chrome-notification-suppression-windows/"><u>Mastering Chrome Notification Suppression, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fixes-for-unsuccessful-windows-upgrades/"><u>Mastering the Fixes for Unsuccessful Windows Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-with-microsofts-copilot-key-insights/"><u>Mastering Windows 11 with Microsoft's Copilot Key Insights</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-program-management-thwarting-windows-autoshrink/"><u>Optimal Program Management: Thwarting Windows' Autoshrink</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-inadequate-systems-to-satisfy-intel-graphic-standards/"><u>Overhauling Inadequate Systems to Satisfy Intel Graphic Standards</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-overcoming-windows-10-bsod-issues/"><u>Quick Guide: Overcoming Windows 10 BSOD Issues</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-non-running-mcuicntexe-file-error-on-pcs/"><u>Remedying the Non-Running McUICnt.exe File Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unresponsive-snip-tools-shortcuts/"><u>Resolving Unresponsive Snip Tools Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/slip-through-system-demands-barrier-in-win11/"><u>Slip Through System Demands Barrier in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-connectivity-how-to-enable-telnet-in-windows-os/"><u>Streamline Connectivity: How to Enable Telnet in Windows OS</u></a></li>
<li><a href="https://driver-download.techidaily.com/swift-download-hp-stream-graphics-driver-set/"><u>Swift Download: HP Stream Graphics Driver Set</u></a></li>
<li><a href="https://os-tips.techidaily.com/the-ultimate-tutorial-for-connecting-iphone-to-samsung-tv-screen-mirroring-simplified/"><u>The Ultimate Tutorial for Connecting iPhone to Samsung TV – Screen Mirroring Simplified</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-itel-a60s-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Itel A60s</u></a></li>
<li><a href="https://win11.techidaily.com/tips-on-resetting-achievements-in-steam-titles/"><u>Tips on Resetting Achievements in Steam Titles</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-distinctions-and-overlaps-between-mp4-and-m4v-file-formats/"><u>Understanding the Distinctions & Overlaps Between MP4 and M4V File Formats</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand!</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-of-geforce-error-x0001-in-windows-os/"><u>Unraveling the Cause of GeForce Error X0001 in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unsafe-synthetic-methods-for-windows-11-key-creation/"><u>Unsafe Synthetic Methods for Windows 11 Key Creation</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-surface-devices-firmware-edition-explained/"><u>Upgrading Surface Devices: Firmware Edition Explained</u></a></li>
<li><a href="https://win11.techidaily.com/venturing-into-the-visual-void-ms-paints-dark-mode-guide/"><u>Venturing Into the Visual Void: MS Paint's Dark Mode Guide</u></a></li>
</ul></div>

