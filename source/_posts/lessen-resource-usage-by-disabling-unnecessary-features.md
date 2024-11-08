---
title: Lessen Resource Usage by Disabling Unnecessary Features
date: 2024-11-04T23:54:12.807Z
updated: 2024-11-07T22:34:27.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Lessen Resource Usage by Disabling Unnecessary Features
excerpt: This Article Describes Lessen Resource Usage by Disabling Unnecessary Features
keywords: Save Resources, Turn Off Extras,Cut Power,Reduce Energy Use,Minimize Battery Drain,Disable Features Saves,Optimize Resource Usage,Efficient Performance Gain
thumbnail: https://thmb.techidaily.com/f7e33e46d8576e8a405f890f9187eb22b423a0b9361503ab0ea4cb809046ec66.jpg
---

## Lessen Resource Usage by Disabling Unnecessary Features

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Antimalware Service Executable?

 You’re probably familiar with Windows Security (previously Microsoft Defender). Windows Security is a reliable antivirus that comes pre-installed on Windows 10 and 11\. The Antimalware Service Executable (you may find it listed as**MsMpEng.exe** in the**Task Manager**) is a core part of Windows Security.

 The service helps ensure your PC stays protected against any virus, worms, and other malware by continually scanning files and programs on your PC in the background. If the Antimalware Service Executable finds a malicious file or program, it will immediately delete or quarantine the affected files.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable[real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

 Real-time protection will be turned back on automatically by Windows Security.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to[disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press**OK** to save your changes and restart your system for the changes to take effect.

## Should You Rely on Windows Security for Windows 10 and 11?

 Many users opt for a dedicated third-party antivirus on Windows 10 or 11, but Windows Security has made significant improvements in the past few years. Not only is Windows Security a complete antivirus package, but it's also free and comes pre-installed on Windows.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-angled-artistry-elevating-youtube-video-editing-skills/"><u>[New] 2024 Approved Angled Artistry Elevating YouTube Video Editing Skills</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-go-beyond-boundaries-with-panasonic-hx-a1-wearable-camera-for-2024/"><u>[New] Go Beyond Boundaries with Panasonic HX-A1 Wearable Camera for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-google-ar-stickers-an-introduction-and-comparisons-for-2024/"><u>[New] Google AR Stickers An Introduction & Comparisons for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-a-compre-written-in-the-stars-how-to-choose-an-ideal-podcast-title/"><u>[Updated] 2024 Approved A Compre Written in the Stars How to Choose an Ideal Podcast Title</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-game-speed-controls-unveiled-a-comprehensible-guide/"><u>[Updated] Game Speed Controls Unveiled A Comprehensible Guide</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-honor-x8b-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Honor X8b | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/custom-chatgpt-modus-operandi-the-ultimate-5-methods/"><u>Custom ChatGPT Modus Operandi: The Ultimate 5 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-methods-to-fire-up-win-11-rdc/"><u>Cutting-Edge Methods to Fire Up Win 11 RDC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-memory-test-failed-errors-in-windows/"><u>Fixing 'Memory Test Failed' Errors in Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/get-on-the-move-with-mods-simplified-sidecar-electric-bicycle/"><u>Get on the Move with Mod's Simplified Sidecar Electric Bicycle</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-a-novel-framework-redefining-admin-access-control/"><u>Introducing a Novel Framework: Redefining Admin Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steganography-hiding-zip-in-photos-windows-11/"><u>Mastering Steganography: Hiding ZIP in Photos (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-cant-access-the-source-problem-in-windows-os/"><u>Overcoming Can't Access the Source Problem in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-virtualbox-on-win-starts-with-deps-checks/"><u>Ready, Set, Go! VirtualBox on Win Starts With Deps Checks</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-unresponsive-touch-pad-issues-in-windows-a-step-by-step-fix-for-windows-10-8-and-7-users/"><u>Resolve Unresponsive Touch Pad Issues in Windows: A Step-by-Step Fix for Windows 10, 8 & 7 Users</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unreachable-status-from-nvidia-on-win-pcs/"><u>Resolving Unreachable Status From NVIDIA on Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-process-setting-up-msoffice-on-windows-11/"><u>Streamlining the Process: Setting Up MSOffice on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-free-fun-on-switch-curated-collection/"><u>Unlock Free Fun on Switch: Curated Collection</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-cab-file-mystique-its-structure-and-implementation-methods/"><u>Unraveling Windows Cab File Mystique: Its Structure & Implementation Methods</u></a></li>
</ul></div>

