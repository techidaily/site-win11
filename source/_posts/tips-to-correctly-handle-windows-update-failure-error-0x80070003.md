---
title: Tips to Correctly Handle Windows Update Failure Error 0X80070003
date: 2024-09-05T08:32:57.264Z
updated: 2024-09-06T08:32:57.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Correctly Handle Windows Update Failure Error 0X80070003
excerpt: This Article Describes Tips to Correctly Handle Windows Update Failure Error 0X80070003
keywords: Fixing Windows Updates Error,Handling Update Failures,Resolve Error 0X80070003,Windows Update Troubleshooting,Stop Update Errors in Windows,Overcoming Update Issues,Avoid Updates Error 0X80070003
thumbnail: https://thmb.techidaily.com/3f943451ad9f20674a4982a12bf6e3782b7a46fb4a594b07cf7ffe549e83acd7.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tips to Correctly Handle Windows Update Failure Error 0X80070003

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-youtube-angle-adjustment-a-step-by-step-editing-guide/"><u>[Updated] 2024 Approved  Youtube Angle Adjustment  A Step-by-Step Editing Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-how-to-preserve-your-roblox-experience-with-flawless-recording-mac/"><u>2024 Approved  How to Preserve Your Roblox Experience with Flawless Recording (Mac)</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-task-managers-curious-display/"><u>Dissecting Task Manager's Curious Display</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-navigating-windows-11-with-a-customizable-taskbar/"><u>Efficiently Navigating Windows 11 with a Customizable Taskbar</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhancing-audio-visual-elements-in-tiktok-via-zoom/"><u>Enhancing Audio-Visual Elements in TikTok via Zoom</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-task-sequence-fails-with-code-0x8007000f/"><u>Fixing Windows Task Sequence Fails with Code 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-failed-unzipping-in-windows-11-systems/"><u>How To Repair Failed Unzipping in Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-vm-setups-for-windows-11-maximizing-potential-and-efficiency/"><u>Ideal VM Setups for Windows 11: Maximizing Potential & Efficiency</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-navigating-through-ioss-recording-software-landscape/"><u>In 2024, Navigating Through iOS's Recording Software Landscape</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-ultimate-list-of-10-vectors-stock-pics-websites/"><u>In 2024, The Ultimate List of 10 Vectors Stock Pics Websites</u></a></li>
<li><a href="https://win11.techidaily.com/installing-chrome-on-windows-11-everything-you-need-to-know/"><u>Installing Chrome on Windows 11: Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/manipulating-windows-defense-display-settings/"><u>Manipulating Windows Defense Display Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-resolutions-in-modern-windows-versions/"><u>Mastering DirectDraw Resolutions in Modern Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-memory-usage-in-windows-systems/"><u>Maximizing Memory Usage in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-disabling-gpgpu-task-ordering-in-winos/"><u>Navigating Disabling GPGPU Task Ordering in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-marketplace-malfunctions-error-0x80073cf3/"><u>Navigating Through Windows' Marketplace Malfunctions (Error 0X80073CF3)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-failed-screensaver-on-windows-4-strategies/"><u>Resetting Failed Screensaver On Windows: 4 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-0x800700e1-on-w10w11/"><u>Steps to Fix 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-folders-not-open-glitch-in-windows-outlook/"><u>Steps to Overcome 'Folders Not Open' Glitch in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-tactics-for-shifting-between-windows-terminals-zones-of-attention-and-rest/"><u>Streamlined Tactics for Shifting Between Windows Terminal’s Zones of Attention and Rest</u></a></li>
<li><a href="https://win11.techidaily.com/switchingnotepadvisualswin-darkmode/"><u>SwitchingNotepadVisuals:Win-DarkMode</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-decades-most-ingenious-frames-and-organizers-24-for-2024/"><u>The Decade's Most Ingenious Frames & Organizers '24 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-underrated-world-of-windows-11-what-youre-missing-out-on/"><u>The Underrated World of Windows 11 - What You're Missing Out On</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-launching-fullscreen-gaming-on-pcs/"><u>Tips for Launching Fullscreen Gaming on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-options-on-nvidia-settings-window/"><u>Troubleshooting No Options on Nvidia Settings Window</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ultimate-techniques-for-precise-iptv-screen-imaging/"><u>Ultimate Techniques for Precise IPTV Screen Imaging</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-disk-read-issues/"><u>Understanding and Rectifying Disk Read Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-os-anomalies-a-step-by-step-approach-to-identifying-and-fixing-error-codes-using-commands/"><u>Unveiling OS Anomalies: A Step-by-Step Approach to Identifying and Fixing Error Codes Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-windows-11-on-mac-with-parallels/"><u>Unveiling the Secrets: Windows 11 on Mac with Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/windows-know-how-6-pathways-for-prop-discovery/"><u>Windows Know-How: 6 Pathways for Prop Discovery</u></a></li>
<li><a href="https://win11.techidaily.com/windows-locks-halted-master-autolock-settings/"><u>Windows Locks Halted: Master Autolock Settings</u></a></li>
</ul></div>
