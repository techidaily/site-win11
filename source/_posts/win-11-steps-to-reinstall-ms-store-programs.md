---
title: Win 11 Steps to Reinstall MS Store Programs
date: 2024-11-01T19:29:02.760Z
updated: 2024-11-07T19:58:18.585Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win 11 Steps to Reinstall MS Store Programs
excerpt: This Article Describes Win 11 Steps to Reinstall MS Store Programs
keywords: Win 11 Installation Guide,Reinstall Microsoft Store,Restarting MS Apps,Step-by-Step Store Recovery,Fixing MS Store Errors,Resetting Windows Store,Upgrading MS Store
thumbnail: https://thmb.techidaily.com/09fee241173a4d75afd314bc2889ac10d1158fd98dc41bc3885e34ece3467540.jpg
---

## Win 11 Steps to Reinstall MS Store Programs

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://youtube-lab.techidaily.com/nleashing-potential-a-treasury-of-youtube-themes-for-channels-for-2024/"><u>[New] Unleashing Potential A Treasury of YouTube Themes for Channels for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-capture-the-essence-extracting-youtube-audio-directly/"><u>[Updated] Capture the Essence Extracting YouTube Audio Directly</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/windows-11-mac/"><u>完成 Windows 11 与 Mac 连接驱动器的数据恢复方法</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-system-performance-4-strategies-for-managing-disk-on-windows-11/"><u>Elevate System Performance: 4 Strategies for Managing Disk on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/flickering-wi-fi-mouse-issues-solutions-for-windows-users/"><u>Flickering Wi-Fi Mouse Issues - Solutions for Windows Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-tailored-screen-recording-guide-for-your-lenovo-device/"><u>In 2024, Tailored Screen Recording Guide for Your Lenovo Device</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-laptop-functionality-post-monitor-hookup/"><u>Optimize Laptop Functionality Post-Monitor Hookup</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-your-pics-kinemaster-methods/"><u>Perfecting Your Pics KineMaster Methods</u></a></li>
<li><a href="https://win11.techidaily.com/prohibiting-date-manipulation-on-windows-machines/"><u>Prohibiting Date Manipulation on Windows Machines</u></a></li>
</ul></div>

