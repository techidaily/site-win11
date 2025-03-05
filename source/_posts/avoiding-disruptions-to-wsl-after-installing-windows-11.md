---
title: Avoiding Disruptions to WSL After Installing Windows 11
date: 2025-03-02T23:16:06.634Z
updated: 2025-03-04T16:10:31.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Disruptions to WSL After Installing Windows 11
excerpt: This Article Describes Avoiding Disruptions to WSL After Installing Windows 11
keywords: Win11 Stability,WSL Post-Upgrade,Noise Prevention in WSL,WSL Windows Compatibility,Smooth WSL Transition,WSL Installation Tips,Minimize WSL Disturbances
thumbnail: https://thmb.techidaily.com/172d2b5e16d3f59f8f3e9aeaa8db2d7a1dcd42c1282454326ca1c10c6fe01b75.jpg
---

## Avoiding Disruptions to WSL After Installing Windows 11

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

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

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
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a [full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

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
<li><a href="https://youtube-lab.techidaily.com/astering-filmmaking-on-youtube-and-substitutes/"><u>[New] Mastering Filmmaking on YouTube & Substitutes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-leading-alternatives-to-twitter-ranked-best/"><u>[Updated] 2024 Approved Leading Alternatives to Twitter, Ranked Best</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-movavi-video-pro-review-release-for-2024/"><u>[Updated] Movavi Video Pro Review Release for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-winerror-not-found-step-by-step-guide/"><u>Eliminate WinError 'Not Found': Step-by-Step Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-the-features-of-espnplus-the-ultimate-sports-streaming-hub/"><u>Exploring the Features of ESPN+, The Ultimate Sports Streaming Hub</u></a></li>
<li><a href="https://win11.techidaily.com/fix-auto-open-in-file-explorer-on-win-pcs/"><u>Fix Auto-Open in File Explorer on Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-windows-backup-to-its-defaults/"><u>How to Reset Windows Backup to Its Defaults</u></a></li>
<li><a href="https://extra-support.techidaily.com/integrate-soundtracks-with-ppt-visuals-for-2024/"><u>Integrate Soundtracks with PPT Visuals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-workspace-positioning-gmail-bar-for-quick-access/"><u>Master Your Workspace: Positioning Gmail Bar for Quick Access</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-login-security-tweaking-the-reset-lockout-after-fails-in-windows-11/"><u>Mastering Login Security: Tweaking the Reset Lockout After Fails in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/nullify-windows-launch-tracker-effects/"><u>Nullify Windows Launch Tracker Effects</u></a></li>
<li><a href="https://fox-that.techidaily.com/resolving-compatibility-problems-for-iphone-accessories-that-dont-fit-the-mold/"><u>Resolving Compatibility Problems for iPhone Accessories That Don't Fit the Mold</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-microsofts-dism-hurdle-error-0x800f082f/"><u>Skirting Microsoft's DISM Hurdle: Error 0X800F082F</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-ranking-mini-computers-comprehensive-evaluation-by-tech-experts/"><u>Top-Ranking Mini Computers - Comprehensive Evaluation by Tech Experts</u></a></li>
<li><a href="https://win11.techidaily.com/upgraded-task-management-windowed-console-with-clis/"><u>Upgraded Task Management: Windowed Console with CLIs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210659244-why-isnt-my-razer-keyboard-lighting-up-solutions-inside/"><u>Why Isn't My Razer Keyboard Lighting Up? Solutions Inside</u></a></li>
<li><a href="https://techtrends.techidaily.com/zdnets-ultimate-guide-to-apple-vision-pro-price-specs-and-review-highlights/"><u>ZDNet's Ultimate Guide to Apple Vision Pro - Price, Specs & Review Highlights</u></a></li>
</ul></div>

