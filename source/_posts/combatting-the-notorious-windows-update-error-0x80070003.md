---
title: "Combatting the Notorious Windows Update Error: 0X80070003"
date: 2024-09-21T19:39:22.202Z
updated: 2024-09-29T01:27:44.000Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Combatting the Notorious Windows Update Error: 0X80070003"
excerpt: "This Article Describes Combatting the Notorious Windows Update Error: 0X80070003"
keywords: Fixing Windows UpdError,Resolve WinUpdateFail,Solve 0X80070003 Update Error,Overcome WinErrCode,Stop WinUpdX80070003,Tackle Windows UpdError,Correct 0xUpdateFail Error,Fix WinUpdErr,Stop UpdX8007,Solve 0xUpdateError,Overcome ErrCodeWin,Tackle WinUpdErrCode,Conquer UpdErrorX7003,Address 0xWindowsUpdateError
thumbnail: https://thmb.techidaily.com/aaeee5a2f3c8b68771aea3a6cb049a51985742ce0b32853fb4db395a79eb5210.jpg
---

## Combatting the Notorious Windows Update Error: 0X80070003

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094483/7443" target="_top" id="2094483">
  <img src="//a.impactradius-go.com/display-ad/7443-2094483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094483/7443" style="position:absolute;visibility:hidden;" border="0" />
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
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

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
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-navigating-through-an-absent-obs-camera-input/"><u>[Updated] In 2024, Navigating Through an Absent OBS Camera Input</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-open-minds-open-tech-easeus-report-for-2024/"><u>[Updated] Open Minds, Open Tech - EaseUS Report for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-superior-streaming-made-simple-enabling-av1-in-youtube/"><u>[Updated] Superior Streaming Made Simple Enabling AV1 in YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-dll-issue-in-windows-810/"><u>Addressing Missing DLL Issue in Windows 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-black-screen-in-windows-quick-fix-guide/"><u>Banish Black Screen in Windows - Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-11-pro-max-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 11 Pro Max iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-examining-various-windows-movie-maker-product-types/"><u>In 2024, Examining Various Windows Movie Maker Product Types</u></a></li>
<li><a href="https://hardware-help.techidaily.com/introducing-the-new-oneplus-11-a-rocky-launch-amidst-high-expectations/"><u>Introducing the New OnePlus 11: A Rocky Launch Amidst High Expectations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/meet-the-titans-discovering-the-worlds-most-innovative-large-scale-language-models/"><u>Meet the Titans: Discovering the World's Most Innovative Large-Scale Language Models</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-best-of-the-bunch-top-rated-meme-generator-apps-for-android-and-ios-for-2024/"><u>New Best of the Bunch Top-Rated Meme Generator Apps for Android and iOS for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-potency-of-the-asus-tuf-gaming-a14-a-review-for-gamers-and-professionals/"><u>Unveiling the Potency of the ASUS TUF Gaming A14: A Review for Gamers and Professionals</u></a></li>
</ul></div>

