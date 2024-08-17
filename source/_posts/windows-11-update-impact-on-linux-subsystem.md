---
title: "Windows 11 Update: Impact on Linux Subsystem"
date: 2024-08-16T00:49:53.850Z
updated: 2024-08-17T00:49:53.850Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Update: Impact on Linux Subsystem"
excerpt: "This Article Describes Windows 11 Update: Impact on Linux Subsystem"
keywords: Win11 Update Effects,Linux Subsystem Changes,OS Upgrade Repercussions,Windows 11 Sysimpact,System Integration Shift,Latest WinOS Update,Subsystem Compatibility
thumbnail: https://thmb.techidaily.com/1f521609b1c133bd14e0ec883446171896f3c613d559912a6d4e6e048b474186.jpg
---

## Windows 11 Update: Impact on Linux Subsystem

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://facebook-video-files.techidaily.com/new-avatar-asymmetry-artistry-designing-your-animated-look/"><u>[New] Avatar Asymmetry Artistry  Designing Your Animated Look</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-incorporate-engaging-text-in-videos-at-no-extra-cost/"><u>[New] In 2024, Incorporate Engaging Text in Videos at No Extra Cost</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-reel-mastery-made-simple-with-these-free-apps-to-manage-instagram-videos/"><u>[New] Reel Mastery Made Simple with These Free Apps to Manage Instagram Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-becoming-a-pro-at-using-igtv-for-business-and-personal-growth/"><u>[Updated] In 2024, Becoming a Pro at Using IGTV for Business and Personal Growth</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-digital-stream-capturers-2023-edition/"><u>[Updated] In 2024, Digital Stream Capturers, 2023 Edition</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-navigating-youtubes-maker-central-interface/"><u>[Updated] Navigating YouTube's Maker Central Interface</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pinnacle-cloud-solutions-highest-rated-reviewed/"><u>[Updated] Pinnacle Cloud Solutions  Highest-Rated Reviewed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-full-exploration-of-the-sj7s-high-definition-star-cameras-for-action/"><u>2024 Approved  Full Exploration of the SJ7's High-Definition Star Cameras for Action</u></a></li>
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/5-key-strategies-for-overcoming-onedrive-errors/"><u>5 Key Strategies for Overcoming OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-discrepancies-in-to-do-app/"><u>A Comprehensive Guide to Fixing Discrepancies in To-Do App</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://win11.techidaily.com/a-tri-method-approach-to-understanding-and-applying-windows-policies/"><u>A Tri-Method Approach to Understanding and Applying Windows Policies</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-users-guide-for-web-site-app-conversion/"><u>A Windows User's Guide for Web Site App Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-system32-folder-on-windows-11/"><u>Accessing System32 Folder on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-success-reinstalling-microsofts-pc-manager-in-winxp/"><u>Achieve Success: Reinstalling Microsoft's PC Manager in WinXP</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-secure-browsing-feature-edge/"><u>Activating Prints with Secure Browsing Feature (Edge)</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-discreprancies-in-power-usage-display-for-win-11-systems/"><u>Addressing Discreprancies in Power Usage Display for Win 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-fault-finders-in-windows/"><u>Addressing Inoperative Fault Finders in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-empty-directory-issue-in-windows-11-error-0x80070091/"><u>Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unclickable-elements-in-the-new-os/"><u>Addressing Unclickable Elements in the New OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/advanced-deletion-methods-a-guide-to-unerasable-file-removal-algorithms/"><u>Advanced Deletion Methods: A Guide to Unerasable File Removal Algorithms</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-blunders-proper-techniques-for-file-explorer-use/"><u>Avoiding Blunders: Proper Techniques for File Explorer Use</u></a></li>
<li><a href="https://win11.techidaily.com/boost-keyboard-efficiency-top-strategies-for-speed-on-windows-devices/"><u>Boost Keyboard Efficiency: Top Strategies for Speed on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-in-remote-steam-functionality/"><u>Breaking Barriers in Remote Steam Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-fixing-steam-problems-on-windows-11-os/"><u>Breaking Down Barriers: Fixing Steam Problems on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-windows-now-on-apples-ios-and-microsoft-devices/"><u>Bridging Platforms: Windows Now on Apple's iOS and Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-frozen-windows-pin-with-easy-fixes/"><u>Bypass Frozen Windows Pin with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-obstacles-quick-fixes-for-stuck-windows-apps/"><u>Bypass Obstacles: Quick Fixes for Stuck Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-httptoomanyreq-error-quick-fixes-for-app-overloads/"><u>Bypassing HTTP_TOO_MANY_REQ Error: Quick Fixes for App Overloads</u></a></li>
<li><a href="https://win11.techidaily.com/cant-sign-into-onedrive-on-windows-try-these-fixes/"><u>Can't Sign Into OneDrive on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/capture-notes-effortlessly-on-windows-11/"><u>Capture Notes Effortlessly on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/character-inspection-the-win11-way/"><u>Character Inspection: The Win11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dual-windows-devices-with-ms-error/"><u>Clearing Up Dual Windows Devices with MS Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-iomap64-blue-screen-of-death-issues-quickly/"><u>Clearing Up IOMap64 Blue Screen of Death Issues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-stuck-gpsvc-delay-mystery/"><u>Clearing Up the Stuck GPSVC Delay Mystery</u></a></li>
<li><a href="https://win11.techidaily.com/code-of-shadows-mastering-invisibles-in-win11/"><u>Code of Shadows: Mastering Invisibles in Win11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/decoding-the-complexities-of-drone-photography-and-gimbals-for-2024/"><u>Decoding the Complexities of Drone Photography and Gimbals for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/farewell-to-errors-a-step-by-step-fix-for-cyberpunk-2077-downloads-via-steam/"><u>Farewell to Errors: A Step-by-Step Fix for Cyberpunk 2077 Downloads via Steam</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-y200e-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-effortlessly-update-your-windows-with-new-gtx-780-graphics-card-drivers/"><u>How to Effortlessly Update Your Windows with New GTX 780 Graphics Card Drivers</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Motorola Razr 40 Ultra? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-magic-5-pro-bootloader-easily-by-drfone-android/"><u>How to Unlock Honor Magic 5 Pro Bootloader Easily</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/imessage-for-android-heres-how-you-can-achieve-it/"><u>IMessage for Android? Here's How You Can Achieve It!</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-the-heart-of-srt-in-depth/"><u>In 2024, Exploring the Heart of SRT in Depth</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-infinix-hot-30-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Infinix Hot 30 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-zte-blade-a73-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your ZTE Blade A73 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leap-into-action-how-to-craft-slow-motion-videos-using-gopro-hero-10-for-2024/"><u>Leap Into Action  How to Craft Slow-Motion Videos Using GoPro Hero 10 for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-simplify-your-storytelling-easy-movie-making-techniques/"><u>New 2024 Approved Simplify Your Storytelling Easy Movie Making Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/perfecting-your-reel-integrating-music-on-instagram/"><u>Perfecting Your Reel  Integrating Music on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/1719328295929-reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way!</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://techidaily.com/sony-xperia-1-v-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Sony Xperia 1 V won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/step-into-the-future-of-streaming-with-top-audio-techniques/"><u>Step Into the Future of Streaming with Top Audio Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-samsung-galaxy-m34-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Samsung Galaxy M34 5G Location | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-secrets-to-improve-your-gopro-videos/"><u>Top Secrets to Improve Your GoPro Videos</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
<li><a href="https://win11.techidaily.com/1719364992381-unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now!</u></a></li>
</ul></div>
