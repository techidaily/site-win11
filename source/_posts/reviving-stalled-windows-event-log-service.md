---
title: Reviving Stalled Windows Event Log Service
date: 2024-10-11T21:41:33.431Z
updated: 2024-10-15T20:35:45.048Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Stalled Windows Event Log Service
excerpt: This Article Describes Reviving Stalled Windows Event Log Service
keywords: Windows Event Log Revival,Stalled EVT Log Fix,Event Log Service Resurrect,Windows Log Service Start,Evlog Sleeping Issue,Restart Windows EventLog,Service Reboot EventV
thumbnail: https://thmb.techidaily.com/b1a9c7a0993599ed99b0e206dce7f79b24d1d48116a23a6228f84489d96e11c6.jpg
---

## Reviving Stalled Windows Event Log Service

 Windows Event Viewer shows the system events and helps review app, security, and system logs useful to check errors on Windows 11\. However, this handy utility can stop working for various reasons, making it difficult to diagnose issues on your computer.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Windows Event Log Service

![restart windows event log service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/restart-windows-event-log-service.jpg)

 You can restart the Windows Event Viewer log service to fix temporary issues with the app. Use the Services snap-in to stop and restart the service and check for any improvements.

 To restart the Windows Event Log Service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. In the right pane, locate and right-click on the **Windows Event Log** service.
4. Select **Restart** and wait for the service to restart.
5. Close the Services snap-in and try to relaunch Event Viewer to see if the issue is resolved.

## 2\. Install the Latest Windows Updates

![windows 11 update advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update-advanced-options.jpg)

 Often the issues with Windows Event Viewer are associated with bad Windows updates. Check your Windows Updates section if a new update is available with a fix.

 To install Windows 11 updates:

1. Press **Win + I** to open **Settings**.
2. Open the **Windows Updates** tab.
3. Click **Check for Updates**. Windows will scan the server for newer updates and populate the screen with the same if available.
4. Click on **Download & install** to install any critical Windows updates available.

## 3\. Try Some Generic Troubleshooting Steps to Get Event Viewer Working

 If the issue persists, this may be an issue with a recently installed Windows update, corrupt system files, and a problematic memory stick. Here are a few tips to try and resolve issues associated with the Windows Event Viewer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Perform a System Restore

 A restore point saves a copy of your system’s working image. Depending on your System Protection settings, you can use the [existing restore point to restore the system](https://www.makeuseof.com/use-system-restore-windows/) and undo system changes caused by an update or the user.

 Start with the most recent restore point available. If the problem persists, check if you can undo the most recently installed Windows update. You can also [manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) from the Settings app.

### Check for System File Corruption

 Damaged or missing Windows system files can be a reason why some of your system apps are not working. To fix the issue, [run the System File Checker utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to perform a scan and then run the DISM command to repair or replace the damaged files.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Check for Issues With the Storage Drive

 Some apps can stop working if the storage drive is corrupt and need repair. You can [use the built-in check disk utility on Windows to scan and repair your drive](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for data corruption.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Disable Windows Defender

 If your Event Viewer cannot load the log files, check if the action is blocked by Windows Defender. To determine the problem, [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) on Windows 11 and then try to open the log files in Event Viewer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Check for Memory Leak Issues

 Issues with your system memory are another reason why the Event Viewer app is not working. Fortunately, Windows has a built-in [Memory Diagnostic tool to scan and detect issues with your system memory](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/).

 Often issues with the system memory may be due to faulty hardware. However, it is recommended to run more tests using the Memory Diagnostic tool report to get more insights into the issue.

### Perform a Windows Installation Repair

 If all else fails, you may need to repair your Windows installation. This will fix critical issues with your Windows image and reinstall the operating system without deleting apps and other data.

 You can [reinstall Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) using a Windows 11 ISO image. If you download the latest version of the ISO, the repair installation process will upgrade your Windows to the latest version available.

## The Windows Event Viewer, Back to Normal

 Event Viewer is a handy utility to troubleshoot your system for issues and keep a tab on all the system and application activities. When it stops working, start by restarting the Windows Event Viewer service. Additionally, check for newer Windows updates, corrupt storage drives, and missing Windows system files.

 If you still have no luck, consider using an Event Viewer alternative. Third-party event log analyzers offer better visualization and advanced features.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-learning-curve-to-funimate-excellence/"><u>[New] Learning Curve to Funimate Excellence</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-priority-tools-critical-6-fb-lite-downloads/"><u>[New] Priority Tools Critical 6 FB Lite Downloads</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pro-level-strategies-to-purge-backgrounds-in-figma/"><u>[New] Pro-Level Strategies to Purge Backgrounds in Figma</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unlock-the-full-potential-of-your-xbox-gameplay/"><u>[New] Unlock the Full Potential of Your Xbox Gameplay</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-do-a-poll-on-instagram-stories-the-only-guide-you-need-to-read-for-2024/"><u>[Updated] How to Do a Poll on Instagram Stories The Only Guide You Need to Read for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discover-12-cutting-edge-flip-screen-cams-for-video-content/"><u>[Updated] In 2024, Discover 12 Cutting-Edge Flip-Screen Cams for Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-of-m2ts-files-to-avi-a-step-by-step-tutorial-at-no-charge/"><u>Effortless Conversion of M2TS Files to AVI - A Step-by-Step Tutorial at No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-summer-discounts-buy-factory-pro-hd-video-converter-software-directly-from-our-website/"><u>Exclusive Summer Discounts: Buy Factory Pro HD Video Converter Software Directly From Our Website</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-shrinking-ogg-soundtracks-discover-the-leading-ogg-compression-software-solutions/"><u>Expert Tips for Shrinking OGG Soundtracks: Discover the Leading OGG Compression Software Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/h264/"><u>H264形式適用方法：他の形式への変換手順と、それをもとに戻す簡単ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-and-save-threads-video-content/"><u>How to Download and Save Thread's Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-edit-audio-in-canva-videos-removing-and-adding-voiceovers-effortlessly/"><u>How to Edit Audio in Canva Videos: Removing and Adding Voiceovers Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/huge-savings-alert-check-out-the-amazing-black-friday-bargains-of-2eusier-in-2020/"><u>Huge Savings Alert! Check Out the Amazing Black Friday Bargains of 2Eusier in 2020</u></a></li>
<li><a href="https://win11.techidaily.com/imgburn-dvd-dvd/"><u>ImgBurn フリーウェアで簡単DVDバックアップ: DVDコピー機能をご案内し、コピーガード解除に最適なツールも紹介</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location on TikTok to See More Content On your Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-video-conversion-for-portable-gaming-systems-pspps3-compatible-solutions/"><u>Master Video Conversion for Portable Gaming Systems - PSP/PS3 Compatible Solutions</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondlys-initiative-groundbreaking-ukraine-language-learning-without-cost/"><u>Mondly's Initiative: Groundbreaking Ukraine Language Learning Without Cost</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Infinix Hot 30i? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    