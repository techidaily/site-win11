---
title: Tackling the 0X800736CC Windows Update Hurdle
date: 2024-08-23T06:09:44.975Z
updated: 2024-08-24T06:09:44.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the 0X800736CC Windows Update Hurdle
excerpt: This Article Describes Tackling the 0X800736CC Windows Update Hurdle
keywords: Windows Update Error X,Fixing Windows Updates,Overcoming Updater Issues,Xbox Console Update Failures,Troubleshoot Update Errors,Resolve Windows KB Error,ZeroX800736CC Windows Hack
thumbnail: https://thmb.techidaily.com/57b8dccb20eee61b9862d74c48858978ad644b0b3c9c032196c655a977f2efc6.jpg
---

## Tackling the 0X800736CC Windows Update Hurdle

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-unveil-creativity-15plus-free-tools-for-youtube-intros/"><u>[New] 2024 Approved  Unveil Creativity  15+ Free Tools for YouTube Intros</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-art-of-inspiration-crafting-captivating-ig-posts/"><u>[New] In 2024, The Art of Inspiration  Crafting Captivating IG Posts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-s18-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo S18 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accelerate-office-productivity-with-speech-recognition-word/"><u>Accelerate Office Productivity with Speech Recognition (Word)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/be-amongst-the-few-essential-metaverse-technology-for-2024/"><u>Be Amongst the Few  Essential Metaverse Technology for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-executables-from-batch-files-in-windows/"><u>Crafting Executables From Batch Files in Windows</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/or-payment-frequency-on-youtube-platform/"><u>Creator Payment Frequency on YouTube Platform</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-made-simple-top-10-windows-fixers/"><u>Debugging Made Simple: Top 10 Windows Fixers</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-resolving-elevation-needed-errors/"><u>Decoding and Resolving 'Elevation Needed' Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enlightening-windows-users-on-camera-memory-issues/"><u>Enlightening Windows Users on Camera Memory Issues</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-performance-in-the-epic-launcher/"><u>Ensuring Smooth Performance in the Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-timely-updates-adding-an-efficient-checkup-toolbar-to-win11/"><u>Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/essential-guide-to-affordable-online-recording-software/"><u>Essential Guide to Affordable Online Recording Software</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-into-using-microsofts-error-resolution-w11/"><u>Expert Insights Into Using Microsoft's Error Resolution W11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-perfectly-execute-background-blur-in-windows-11-photos-app/"><u>Expert Tips to Perfectly Execute Background Blur in Windows 11 Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-option-to-skip-pcs-built-in-graphics/"><u>Exploring the Option to Skip PC's Built-In Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/four-hacks-stopping-automatic-windows-and-office-updates/"><u>Four Hacks: Stopping Automatic Windows & Office Updates</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581890717-get-up-and-learn-urdu-10-minute-rule/"><u>Get Up & Learn Urdu – 10-Minute Rule!</u></a></li>
<li><a href="https://win11.techidaily.com/go-direct-to-linux-with-no-wsl/"><u>Go Direct to Linux with No WSL</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-store-error-0x800704cf-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error 0X800704CF in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-download-rates-for-epic-launcher/"><u>Mastering Fast Download Rates for Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-folder-descriptions-in-windows-11-explorer/"><u>Mastering Folder Descriptions in Windows 11 Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-discord-setup-in-windows-11/"><u>Navigating Through Failed Discord Setup in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-virtualdub-2023-review-features-pros-and-cons-plus-alternatives/"><u>New Virtualdub 2023 Review Features, Pros, and Cons, Plus Alternatives</u></a></li>
<li><a href="https://driver-install.techidaily.com/nvidia-driver-update-simplified-for-maximum-efficiency/"><u>Nvidia Driver Update: Simplified for Maximum Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-system-streamlined-windows-autoupdate-and-driver-change/"><u>Optimize System: Streamlined Windows Autoupdate & Driver Change</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-world-effortless-windows-factory-techniques/"><u>Reboot Your World: Effortless Windows Factory Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-luster-to-extended-volume-settings-in-wm/"><u>Reinstate Luster to Extended Volume Settings in WM</u></a></li>
<li><a href="https://win11.techidaily.com/remote-file-management-via-smb-protocols/"><u>Remote File Management via SMB Protocols</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solution-found-overcoming-common-problems-when-your-csgo-headset-mic-fails-to-work/"><u>Solution Found! Overcoming Common Problems When Your CS:GO Headset Mic Fails to Work</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-accessing-and-downloading-podcasts-via-apple-device/"><u>Step-by-Step  Accessing & Downloading Podcasts via Apple Device</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-append-folders-to-windows-11-menu/"><u>Step-by-Step Guide: Append Folders to Windows 11 Menu</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-amend-browsers-copy-and-paste-issues-on-windows/"><u>Steps to Amend Browser's Copy & Paste Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-swap-from-s-mode-tips-for-modern-windows-users/"><u>Swiftly Swap From S Mode: Tips for Modern Windows Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-comedy-cache-twitters-best-jokes-for-2024/"><u>The Comedy Cache  Twitter’s Best Jokes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-finest-alternatives-to-microsofts-core-applications/"><u>The Finest Alternatives to Microsoft's Core Applications</u></a></li>
<li><a href="https://win11.techidaily.com/the-sunsetting-of-windows-7-and-81-by-microsoft/"><u>The Sunsetting of Windows 7 and 8.1 by Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-stopping-windows-11-security-guard/"><u>Tutorial: Stopping Windows 11 Security Guard</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-windows-10s-approach-to-phasing-out-win32-programs-in-favor-of-windows-store-options/"><u>Understanding Windows 10'S Approach to Phasing Out Win32 Programs in Favor of Windows Store Options</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://win11.techidaily.com/win-strategies-accelerating-valorants-sluggish-downloads/"><u>Win Strategies: Accelerating Valorant's Sluggish Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10-vs-windows-11-all-the-major-changes/"><u>Windows 10 vs Windows 11: All the Major Changes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>