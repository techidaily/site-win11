---
title: Decoding and Fixing the Windows Update File Absence Issue (Error 0X80070003)
date: 2024-08-08T13:17:11.616Z
updated: 2024-08-09T13:17:11.616Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding and Fixing the Windows Update File Absence Issue (Error 0X80070003)
excerpt: This Article Describes Decoding and Fixing the Windows Update File Absence Issue (Error 0X80070003)
keywords: WinUpdateErrorFix,0X80070003Solution,WindowsUpdateNoFile,ErrorCodeX70003,FixUpdaterFailure,UpdateFileIssueCorrection,ZeroXErrorWinUpdate
thumbnail: https://thmb.techidaily.com/beb79c97cd88302125e646092101e6316bc065b6e8c0e4d468eed617783ebeeb.jpg
---

## Decoding and Fixing the Windows Update File Absence Issue (Error 0X80070003)

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

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
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-propel-your-social-impact-with-strategic-facebook-video-ads/"><u>[New] 2024 Approved  Propel Your Social Impact with Strategic Facebook Video Ads</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mastering-stardews-core-principles-and-secrets-with-special-emphasis-on-ginger-island-for-2024/"><u>[New] Mastering Stardew's Core Principles and Secrets, With Special Emphasis on Ginger Island for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-roadmap-to-unearth-gorgeous-pexel-pictures/"><u>[Updated] The Ultimate Roadmap to Unearth Gorgeous Pexel Pictures</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-aesir-clash-in-the-shadow-of-ragnarok/"><u>2024 Approved  Aesir Clash  In the Shadow of Ragnarok</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-capture-clear-and-smooth-aquatic-moments/"><u>2024 Approved  How to Capture Clear and Smooth Aquatic Moments</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-infinite-playground-top-10-affordable-online-adventures/"><u>2024 Approved  Infinite Playground  Top 10 Affordable Online Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-view-the-applied-group-policies-on-windows/"><u>3 Ways to View the Applied Group Policies on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-pivotal-points-for-reconnecting-your-obs-studio-link-win-compatible/"><u>7 Pivotal Points for Reconnecting Your OBS Studio Link (Win-Compatible)</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-sign-in-method-youre-trying-to-use-isnt-allowed-error-on-windows/"><u>8 Ways to Fix The Sign-In Method You're Trying to Use Isn't Allowed Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-developers-journey-github-desktop-in-the-era-of-win-11/"><u>A Developer's Journey: GitHub Desktop in the Era of Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-keeping-your-tasks-visible-and-high-priority/"><u>A Guide to Keeping Your Tasks Visible and High-Priority</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-steam-download-rates-overcoming-sluggish-pace/"><u>Accelerate Steam Download Rates: Overcoming Sluggish Pace</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-forbidden-page-in-windows-environment/"><u>Addressing Forbidden Page in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-nvidia-cp-in-w11-environments/"><u>Addressing Non-Operational NVidia CP in W11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-systemsettings-issue-on-windows-11/"><u>Addressing SystemSettings Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-lockout-interval-after-multiple-login-failures/"><u>Adjusting Lockout Interval After Multiple Login Failures</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-alchemy-how-to-seamlessly-change-windows-11-themes-and-enrich-your-workspace/"><u>Aesthetic Alchemy: How to Seamlessly Change Windows 11 Themes and Enrich Your Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-folder-empty-warning-on-windows-pcs/"><u>Avoiding Folder Empty Warning on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-power-and-performance-in-windows-systems/"><u>Balancing Power and Performance in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-camera-driver-software-for-all-windows-versions-including-11-10-8-and-7/"><u>Get the Latest Camera Driver Software for All Windows Versions Including 11, 10, 8, and 7</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-apple-iphone-7-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on Apple iPhone 7 With or Without Password</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-xr-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone XR without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-k70-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi K70 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instagram-success-stories-adopting-viral-techniques-from-tiktok/"><u>In 2024, Instagram Success Stories  Adopting Viral Techniques From TikTok</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premium-steadicam-models-to-transform-your-dslr-filmmaking-experience/"><u>In 2024, Premium Steadicam Models to Transform Your DSLR Filmmaking Experience</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-revolutionary-q500-the-ultimate-4k-bird/"><u>In 2024, Revolutionary Q500  The Ultimate 4K Bird</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-six-sensational-videos-that-keep-on-watchers/"><u>In 2024, Six Sensational Videos That Keep On Watchers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-conversational-support-merging-gpt-with-whatsapp/"><u>Mastering Conversational Support: Merging GPT with WhatsApp</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/strategic-tagging-for-skyrocketing-youtube-statistics-for-2024/"><u>Strategic Tagging for Skyrocketing YouTube Statistics for 2024</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-honor-magic-5-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719298121554-troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-your-iphones-dimmed-flashlight-12-essential-strategies/"><u>Troubleshooting Your iPhone's Dimmed Flashlight: 12 Essential Strategies</u></a></li>
</ul></div>
