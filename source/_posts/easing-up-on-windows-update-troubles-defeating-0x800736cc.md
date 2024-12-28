---
title: "Easing Up on Windows Update Troubles: Defeating 0X800736CC"
date: 2024-12-21T03:57:48.735Z
updated: 2024-12-28T00:50:36.764Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easing Up on Windows Update Troubles: Defeating 0X800736CC"
excerpt: "This Article Describes Easing Up on Windows Update Troubles: Defeating 0X800736CC"
keywords: Windows Update Issues,Fixing Update Errors,Zero X Code 36CC,Resolve Updates Problems,XP Updater Troubleshoot,Eliminate Update Crashes,Overcoming Update Failures
thumbnail: https://thmb.techidaily.com/b734a2c6690e4996dacb7188f3387d968781f292fbd537e9c3d8dd96d06bbb96.jpg
---

## Easing Up on Windows Update Troubles: Defeating 0X800736CC

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

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
<li><a href="https://extra-information.techidaily.com/new-a-decade-of-innovation-in-online-cricket-streaming/"><u>[New] A Decade of Innovation in Online Cricket Streaming</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-winning-with-spotify-promos-tactics-and-tricks/"><u>[New] Winning with Spotify Promos Tactics and Tricks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-link-zoom-calls-to-iphoneandroid-events-seamlessly/"><u>[Updated] 2024 Approved Link Zoom Calls to iPhone/Android Events Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-amd-graphics-on-windows-11-with-updated-drivers/"><u>Breathe New Life Into AMD Graphics on Windows 11 with Updated Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-two-email-realms-add-gmail-to-outlook-windows-edition/"><u>Bridging Two Email Realms: Add Gmail to Outlook, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-better-interface-new-menu-additions-for-win-11/"><u>Building a Better Interface: New Menu Additions for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fake-virus-detection-on-windows-chrome-edition/"><u>Bypassing Fake Virus Detection on Windows Chrome Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-ram-limitations-on-your-windows-computer/"><u>Bypassing Ram Limitations on Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windows-store-mishap-with-code-x80072f30-fix/"><u>Bypassing the Windows Store Mishap with Code X80072F30 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/champion-windows-options-for-true-nintendo-switch-experience/"><u>Champion Windows Options for True Nintendo Switch Experience</u></a></li>
<li><a href="https://win-bits.techidaily.com/clytze-byers-author-biography-and-insights-discover-more-about-the-creator-of-aomei/"><u>Clytze Byers: Author Biography & Insights - Discover More About the Creator of AOMEI</u></a></li>
<li><a href="https://win-hot.techidaily.com/error-resolution-strategies-for-key-value-deserialization-issues-within-database-partitions/"><u>Error Resolution Strategies for Key-Value Deserialization Issues Within Database Partitions</u></a></li>
<li><a href="https://win-top.techidaily.com/how-to-fix-a-corrupted-boot-partition-in-windows-10/"><u>How to Fix a Corrupted Boot Partition in Windows 10</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-htc-u23-pro-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix HTC U23 Pro Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/why-you-need-to-keep-an-eye-on-the-elusive-oneplus-nord-4-the-exceptional-choice-for-budget-conscious-tech-aficionados/"><u>Why You Need to Keep an Eye on the Elusive OnePlus Nord 4 - The Exceptional Choice for Budget-Conscious Tech Aficionados</u></a></li>
</ul></div>

