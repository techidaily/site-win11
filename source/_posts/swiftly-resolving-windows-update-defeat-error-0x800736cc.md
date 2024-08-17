---
title: "Swiftly Resolving Windows Update: Defeat Error 0X800736CC"
date: 2024-08-16T00:12:24.636Z
updated: 2024-08-17T00:12:24.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Swiftly Resolving Windows Update: Defeat Error 0X800736CC"
excerpt: "This Article Describes Swiftly Resolving Windows Update: Defeat Error 0X800736CC"
keywords: Fix Windows Update Error,Overcome XError WinUpdate,Solve Update 0X800736CC,Remove Update Failure Error,Eliminate WinUpdate Issue,Stop Updates Crashing,Prevent Windows Update Errors
thumbnail: https://thmb.techidaily.com/3ad4f7e8b48f19c37105255d0826afad52f6608bef33c5c37cef1bfce8aa66b0.jpeg
---

## Swiftly Resolving Windows Update: Defeat Error 0X800736CC

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
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

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-efficient-audio-documentation-in-academia-using-macs/"><u>[New] 2024 Approved  Efficient Audio Documentation in Academia Using Macs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-videography-titans-battle-for-2024/"><u>[New] Videography Titans Battle for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-easy-peasy-screen-transitions-for-filmmakers/"><u>[Updated] In 2024, Easy-Peasy Screen Transitions for Filmmakers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-eyecapture-screen-logger-x/"><u>[Updated] In 2024, EyeCapture Screen Logger X</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-navigating-around-youtubes-restrictions/"><u>[Updated] Navigating Around Youtube's Restrictions</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revolutionize-iphone-images-turn-them-sideways-and-upside-down/"><u>[Updated] Revolutionize iPhone Images  Turn Them Sideways & Upside Down</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-kinemasters-transition-playbook-for-cinematic-excellence/"><u>2024 Approved  Kinemaster’s Transition Playbook for Cinematic Excellence</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-itel-a70-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Itel A70 by Name | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Asus ROG Phone 7 Ultimate to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-resize-images-in-windows-11/"><u>6 Ways to Resize Images in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-the-call-not-invoked-issue-in-malwarebytes/"><u>Addressing and Fixing the Call Not Invoked Issue in Malwarebytes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-chrome-downloads-disruptions-in-the-windows-os/"><u>Addressing Chrome Downloads Disruptions in the Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-quick-access-for-file-explorer-through-onedrive/"><u>Adjusting Quick Access for File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/ais-impact-on-modern-windows-os-innovation/"><u>AI's Impact on Modern Windows OS Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/anonymizing-file-transfer-methods-for-ws11w10-enthusiasts/"><u>Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-for-correcting-err-87-invalid-parameters-on-winos/"><u>Approaches for Correcting Err 87: Invalid Parameters on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-excellence-through-windows/"><u>Augmenting Linux Excellence Through Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-disruption-bypass-game-glitches-immediately/"><u>Avoid Disruption - Bypass Game Glitches Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-offer-best-price-keys-fan-unlocked-for-all-year-lifetime-windows-11/"><u>Black Friday Offer: Best Price Keys Fan Unlocked for All-Year Lifetime Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bluescreenview-explained-with-ease-and-clarity/"><u>BlueScreenView Explained with Ease and Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-hp-laserjet-n1320-driver-software-for-your-pc/"><u>Get the Latest HP LaserJet N1320 Driver Software for Your PC!</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-tecno-pop-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-make-facebook-video-ads-in-an-creative-way/"><u>How to Make Facebook Video Ads in An Creative Way?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-v27-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Vivo V27 Phone without PIN</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-nikon-d-500-4k-dslr-camera-review/"><u>In 2024, Nikon D 500 4K DSLR Camera Review</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-watch-share-repeat-the-best-movie-trailer-apps-for-iphone-and-ipad/"><u>New 2024 Approved Watch, Share, Repeat The Best Movie Trailer Apps for iPhone and iPad</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719218745181-panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks!</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-motorola-moto-g-stylus-5g-2023-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Motorola Moto G Stylus 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/ralink-rt3290-driver-solutions-for-windows-1087-users/"><u>Ralink RT3290 Driver Solutions for Windows 10/8/7 Users</u></a></li>
<li><a href="https://win11.techidaily.com/1719284853027-ready-set-gain-administrator-status/"><u>Ready, Set, Gain Administrator Status!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-cxfreeze-catastrophic-failures-with-ease/"><u>Troubleshooting Guide: Solving Cx_Freeze Catastrophic Failures with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://win11.techidaily.com/1719258150800-win-rpc-problems-here-are-5-fixes-you-need/"><u>Win RPC Problems? Here Are 5 Fixes You Need</u></a></li>
</ul></div>
