---
title: Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs
date: 2024-08-16T00:16:06.346Z
updated: 2024-08-17T00:16:06.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs
excerpt: This Article Describes Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs
keywords: CPU Usage Prevention,Reducing RAM Overload,Optimizing System Resources,PC Performance Enhancement,Combat Excessive Memory Use,CPU Efficiency Mitigation,Limiting RAM Consumption in Computers
thumbnail: https://thmb.techidaily.com/4e831fd04562f2cd6825c32accd78b3641cb3be2e3ea9cbe8b25030ed7edee4b.jpg
---

## Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs

 Is the UnrealCEFSubprocess process consuming hefty CPU and RAM resources in the Task Manager, causing your games to crash? Does it keep straining your hardware even after you close all the active programs and apps? You may also have seen it multiply in the Task Manager, which might have made you believe it's a virus.

 There's no need to worry; it's not a virus but a legitimate process belonging to Valorant. Below, we'll discuss why this process consumes many system resources and how you can reduce its resource usage to relieve the strain on your hardware.

## Why Does the UnrealCEFSubprocess Process Consume High CPU and RAM Resources?

 UnrealCEFSubprocess is a legitimate Valorant process, so it shouldn't overload your system resources. If this process starts to strain your hardware and cause CPU, RAM, or GPU usage to spike in the Task Manager, it's either not functioning correctly, or other processes are interfering with it.

 As many users pointed out in a [Reddit thread](https://www.reddit.com/r/ValorantTechSupport/comments/z66n1b/unrealcefsubprocessexe%5Fmultiplying%5Fand%5Fputting/) , one of the major causes of high resource consumption by this process is the interference from Windows' built-in security suite, Windows Defender, and third-party antivirus software, primarily AVG antivirus and Avast antivirus. If you are using security software, then it might be causing the issue.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Can You Disable the UnrealCEFSubprocess Process via the Task Manager?

 Disabling the UnrealCEFSubprocess process could adversely affect your active gaming session in Valorant. The gaming elements this process controls or handles will crash and behave abnormally. Because of this, we do not advocate closing it down.

 Furthermore, Valorant or the Riot client will automatically relaunch this process the next time you open them, so disabling only the process won't solve the issue. Therefore, we recommend that you fix the underlying problem rather than only disabling this process.

## How to Stop the UnrealCEFSubprocess Process From Taking Up Too Much RAM and CPU

 The easiest way to reduce UnrealCEFSubprocess's CPU and RAM consumption is to [permanently disable Windows Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/) , the built-in security software in Windows, and uninstall any third-party antivirus software you currently use. Even though doing this is easy and quick, we don't recommend it. Why is that?

 The Windows Defender and third-party antivirus software installed on your laptop are a solid defense against viruses and malware. They prevent any potentially harmful agents from wreaking havoc on your device. If you delete or disable them, you will remove your frontline fighters and allow enemies to attack your territory with no fear.

 These security suites would likely have already quarantined many threats and blocked potentially harmful files from affecting your computer. Disabling or deleting them can release these threats and remove restrictions on malicious files. Consequently, this could negatively affect your computer in the long run.

 Considering the risks associated with it, it would be wise not to disable security software right away. Instead of that, you can whitelist the UnrealCEFSubprocess process in them. Whitelisting any file instructs security software not to interfere with it. Therefore, whitelisting the file associated with this process will prevent antivirus programs from interfering with it.

 Consequently, you will be successful in reducing resource consumption without compromising your security.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
### How to Whitelist UnrealCEFSubprocess From Windows Defender

 Follow these steps to whitelist UnrealCEFSubprocess from Windows Defender:

1. Type**"Windows Security"** in Windows Search and open the**Windows Security** app.  
![Open Windows Security from Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-windows-security-from-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Go to the**Firewall and network protection** tab on the left.
3. Click on the**Allow an app through the firewall** link on the right side of the screen.  
![Click on the Allow an App Through the Firewall Link in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-the-allow-an-app-through-the-firewall-link-in-windows-security-app.jpg)
4. Click on**Change settings** .
5. Click on**Allow another app** .  
![Click on Allow Another App in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-allow-another-app-in-the-windows-defender-firewall-settings.jpg)

1. In the**Add an app** window, click on the**Browse** button.  
![Click on the Browse Button in the Add an App Window in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-the-browse-button-in-the-add-an-app-window-in-the-windows-defender-firewall-settings.jpg)
2. Then, go to the following path:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
3. Here, select**UnrealCEFSubProcess** from the list.  
![Select UnrealCEFSubprocess to Create an Exclusion for It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-select-unrealcefsubprocess-to-create-an-exclusion-for-it.jpg)
4. Then, click on**Add** .  
![Click on the Add Button After Selecting the Relevant Process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-click-on-the-add-button-after-selecting-the-relevant-process.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
5. After that, check the**Public** and**Private** boxes next to the**UnrealCEFSubProcess** process and click**OK** .  
![Click OK After Checking the Public and Private Boxes Next to the UnrealCEFSubprocess in the Windows Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-ok-after-checking-the-public-and-private-boxes-next-to-the-unrealcefsubprocess-in-the-windows-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
6. Restart your computer after whitelisting this process.

**I** f you have installed Valorant in a different folder or your operating system resides on a different drive, change the path above to reflect the proper location.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Whitelist UnrealCEFSubprocess From Avast Antivirus

 Follow these steps to whitelist UnrealCEFSubprocess from Avast Antivirus:

1. Launch Avast Antivirus.
2. Click the**Menu** button (represented by three horizontal lines stacked over each other) in the top-right of the screen.
3. Go to**Settings** .  
![Go to Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/8-go-to-settings-in-avast-antivirus-app.jpg)
4. Go to the**Exceptions** tab in the**General** settings.
5. Click on**Add Exception** .  
![Click on Add Exception in the General Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/9-click-on-add-exception-in-the-general-settings-in-avast-antivirus-app.jpg)
6. Click**Browse** in the**Add exception** window.  
![Click Browse in the Add Exception Window in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/10-click-browse-in-the-add-exception-window-in-avast-antivirus-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
7. Navigate to the following path if you haven't changed the default installation path when installing Valorant:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
8. Check the box beside**UnrealCEFSubprocess** and click**OK** .  
![Click OK After Checking the Box Beside UnrealCEFSubprocess in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/11-click-ok-after-checking-the-box-beside-unrealcefsubprocess-in-avast-antivirus-app.jpg)
9. After that, restart your computer once, and hopefully, the process won't overtax your computer's resources anymore.

### How to Whitelist UnrealCEFSubprocess From AVG Antivirus

 The interface of AVG antivirus is almost identical to Avast antivirus. So, you can whitelist UnrealCEFSubprocess from it by following the steps outlined above. Once you have whitelisted the file,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) once, and hopefully, the resource consumption by this process will decrease significantly.

 According to some users, whitelisting the UnrealCEFSubprocess file from AVG antivirus doesn't always reduce its resource consumption. Due to this, users had to delete AVG antivirus from their computers. So, if whitelisting the file doesn't reduce the load on your hardware, you can delete the AVG antivirus.

 Before doing that,[turn on Windows Defender](https://www.makeuseof.com/turn-on-microsoft-defender/) if it's off, or install alternative antivirus software to replace AVG and keep your computer safe from incoming threats.

 If you use an antivirus software other than the two listed above and the UnrealCEFSubprocess process consumes more than half of your system resources, you need to whitelist the UnrealCEFSubprocess file there as well. If you are not familiar with the whitelisting process, visit the antivirus software's official website.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Don't Let the UnrealCEFSubprocess Process Overburden Your Hardware

 The UnrealCEFSubprocess process consumes a lot of resources, which leaves barely any resources for other processes. Consequently, your games and apps will take a long time to load and crash frequently—enough to ruin your gaming experience.

 You should now better understand why this process consumes a lot of resources and what you can do to fix it. Therefore, whitelist the UnrealCEFSubprocess process in your security program, and if that does not solve the issue, disable or uninstall your antivirus.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-the-essential-guide-to-using-vsdc-and-comparing-it-with-others-for-2024/"><u>[New] The Essential Guide to Using VSDC & Comparing It with Others for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-best-offline-android-games-dive-into-the-fun-without-a-network/"><u>[Updated] In 2024, Best Offline Android Games - Dive Into the Fun Without a Network</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-preferred-speech-to-text-ipad-apps-3/"><u>[Updated] In 2024, Preferred Speech-to-Text iPad Apps #3</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-top-choices-for-screen-recorders-that-dont-tie-you-down/"><u>[Updated] In 2024, Top Choices for Screen Recorders That Don't Tie You Down</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-websites-to-acquire-custom-youtube-ringtones/"><u>[Updated] Prime Websites to Acquire Custom YouTube Ringtones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-refined-retakes-how-to-crop-and-perfect-iphone-shots/"><u>[Updated] Refined Retakes  How to Crop and Perfect iPhone Shots</u></a></li>
<li><a href="https://win11.techidaily.com/cant-open-exe-files-on-windows-try-these-fixes/"><u>Can’t Open EXE Files on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-problems-with-outlooks-error-0x80040610-on-windows/"><u>Curbing Problems with Outlook's Error 0X80040610 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-between-upgrades-here-are-7-reasons-for-win10/"><u>Deciding Between Upgrades? Here Are 7 Reasons for Win10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deciding-on-your-preferred-ai-companion-evaluating-chatgpt-against-microsoft-bings-creation-and-google-bard/"><u>Deciding on Your Preferred AI Companion - Evaluating ChatGPT Against Microsoft Bing's Creation & Google Bard</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/efficient-timelapse-recording-via-ipad-for-2024/"><u>Efficient Timelapse Recording via iPad for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-to-revitalize-frozen-spotify-win11/"><u>Essential Techniques to Revitalize Frozen Spotify Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-grayed-out-extend-volume-option-in-disk-management-for-windows/"><u>How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-lsassexe-unable-to-locate-error-on-win-810/"><u>How to Overcome lsass.exe Unable to Locate Error on Win 8/10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-luminous-clips-discover-5-apps-that-shine-online/"><u>In 2024, Luminous Clips  Discover 5 Apps That Shine Online</u></a></li>
<li><a href="https://win11.techidaily.com/installation-steps-for-dolby-atmos-in-windows-11/"><u>Installation Steps for Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/navigating-through-music-production-software-landscape-can-magix-samplitude-be-considered-supreme-for-2024/"><u>Navigating Through Music Production Software Landscape Can MAGIX Samplitude Be Considered Supreme for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-false-virus-detection-issue/"><u>Overcoming Chrome’s False Virus Detection Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-write-failure-in-windows/"><u>Overcoming Memory Write Failure in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revive-your-missing-iphone-x-crucial-tips-revealed-for-2024/"><u>Revive Your Missing iPhone X  Crucial Tips Revealed for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-iphone-hotspot-issues-a-step-by-step-guide-for-seamless-tethering/"><u>Solving iPhone Hotspot Issues: A Step-by-Step Guide for Seamless Tethering</u></a></li>
<li><a href="https://win11.techidaily.com/speak-get-text-win-a-comprehensible-guide-to-windows-whisper/"><u>Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-asana-glitches-on-pc/"><u>Troubleshooting Asana Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-glitches-and-error-0xc00d36b4-on-windows/"><u>Troubleshooting Glitches & Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-your-laptops-touch-sensitivity-with-ease/"><u>Unleash the Power of Your Laptop's Touch Sensitivity with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-complexities-of-windows-system-restore-for-easy-rollbacks/"><u>Unraveling the Complexities of Windows System Restore for Easy Rollbacks</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-properties-puzzles-in-windows-os/"><u>Unveiling Properties Puzzles in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastering-app-and-browser-oversight/"><u>Windows: Mastering App & Browser Oversight</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
</ul></div>
