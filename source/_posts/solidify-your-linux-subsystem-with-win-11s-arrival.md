---
title: Solidify Your Linux Subsystem with Win 11'S Arrival
date: 2024-12-04T18:43:09.259Z
updated: 2024-12-07T06:03:52.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solidify Your Linux Subsystem with Win 11'S Arrival
excerpt: This Article Describes Solidify Your Linux Subsystem with Win 11'S Arrival
keywords: Linux Subsystem Integration,Windows 11 & Linux Combo,Enhancing Linux Ecosystem,Win 11 for Linux Users,Optimizing Hybrid Systems,Cross-Platform Compatibility,Linux-Win 11 Synergy
thumbnail: https://thmb.techidaily.com/d37eff43ca85f1c6727bb1c48930aa293f0c1790252e534383e8e0730d7ae092.jpg
---

## Solidify Your Linux Subsystem with Win 11'S Arrival

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-the-insiders-look-at-sharing-links-on-ig-platform-for-2024/"><u>[New] The Insider's Look at Sharing Links on IG Platform for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-guide-to-uploading-videos-into-youtube-lists/"><u>[Updated] 2024 Approved Guide to Uploading Videos Into YouTube Lists</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-zoominnovatex7-advanced-imagery-enlargement/"><u>[Updated] ZoomInnovateX7 Advanced Imagery Enlargement</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-connection-problems-between-windows-11-and-nvidia-experience/"><u>Eliminating Connection Problems Between Windows 11 & NVIDIA Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-transform-flac-files-into-wav-format-with-ease-movavi/"><u>Free Online Conversion: Transform FLAC Files Into WAV Format with Ease - Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-and-convenience-with-cmd-shortcuts-in-win11/"><u>Maximize Productivity and Convenience with Cmd Shortcuts in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mp4-v-mp3-preobrazovanie-onlajn-besplatno-s-pomoshyu-servira-movavi-luchshie-rezultaty-dlya-polzovatelej-rossii/"><u>MP4 В MP3 Преобразование Онлайн Бесплатно С Помощью Сервира Movavi - Лучшие Результаты Для Пользователей России</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-0xc0000142-faults-in-win10win11/"><u>Overcoming 0XC0000142 Faults in WIN10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-glitches-apex-legends-issues/"><u>Overcoming Windows 11 Glitches: Apex Legends Issues</u></a></li>
<li><a href="https://win11.techidaily.com/programmable-shortcuts-to-boost-windows-use/"><u>Programmable Shortcuts to Boost Windows Use</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-shutdown-how-to-open-apps-again-in-w11/"><u>Reactivating Shutdown: How to Open Apps Again in W11</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-guide-solutions-for-phasmophobia-game-crashes/"><u>Ultimate Guide: Solutions for Phasmophobia Game Crashes</u></a></li>
</ul></div>

