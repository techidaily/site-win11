---
title: Fixing WSL Disruptions After Win 11 Rollout
date: 2024-09-05T08:44:59.622Z
updated: 2024-09-06T08:44:59.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing WSL Disruptions After Win 11 Rollout
excerpt: This Article Describes Fixing WSL Disruptions After Win 11 Rollout
keywords: Win 11 WSL Stability,WSL Issue Fixes,Post-Win11 WSL,Win 11 WSL Disruptions,Resolve WSL Win11,WSL Troubleshooting Win11,Win 11 WSL Repair Guide
thumbnail: https://thmb.techidaily.com/641461279d3ad9059bf4fdcda2c6b1609c3c8007cc281a812d3b0157adab9f77.jpg
---

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing WSL Disruptions After Win 11 Rollout

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
<a href="https://unicoeye.pxf.io/c/5597632/2121331/18498" target="_top" id="2121331">
  <img src="//a.impactradius-go.com/display-ad/18498-2121331" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121331/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-live-transmission-via-obs-to-instagram/"><u>[New] 2024 Approved  Live Transmission via OBS to Instagram</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-mastering-vlc-mp4-and-various-format-conversion-techniques/"><u>[Updated] 2024 Approved  Mastering VLC  MP4 & Various Format Conversion Techniques</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-instructions-removing-videos-from-youtubes-watchlater/"><u>[Updated] Instructions  Removing Videos From YouTube's Watchlater</u></a></li>
<li><a href="https://win11.techidaily.com/combining-windows-partitions-an-expert-guide/"><u>Combining Windows Partitions: An Expert Guide</u></a></li>
<li><a href="https://win11.techidaily.com/comparative-study-how-microsoft-and-default-windows-user-accounts-diverge/"><u>Comparative Study: How Microsoft and Default Windows User Accounts Diverge</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-webcam-written-as-how-to-fix-your-webcam-showing-a-black-screen-on-windows/"><u>Correcting Windows Webcam' Written as How to FIX Your WebCam Showing a BLACK SCREEN on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-spacing-on-windows-11/"><u>Customizing Taskbar Spacing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-effective-email-delivery-feedback-on-windows-machines/"><u>Enabling Effective Email Delivery Feedback on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-photo-functionality/"><u>Enhancing Windows Explorer Photo Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/exciting-laptop-releases-at-ifa-2023/"><u>Exciting Laptop Releases at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/first-timers-guide-to-navigating-windows-tools/"><u>First Timer's Guide to Navigating Windows Tools</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/football-manager-2020-solved-no-more-game-crashes/"><u>Football Manager 2020: Solved - No More Game Crashes!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-vivo-v27e-to-mac-drfone-by-drfone-android/"><u>How to Mirror Vivo V27e to Mac? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-iphone-8-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on iPhone 8</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-vivo-y100-5g-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Vivo Y100 5G Devices</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-cli-toolbar-in-windows-11-task-manager/"><u>Integrating CLI Toolbar in Windows 11 Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-printer-support-into-application-guard/"><u>Integrating Printer Support Into Application Guard</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-opening-windows-credential-hideout/"><u>Key to Opening Windows Credential Hideout</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-advanced-visuals-within-edges-security/"><u>Mastering Advanced Visuals Within Edge's Security</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-warhammers-precision-gameplay-end-stuttering-on-windows/"><u>Mastering Warhammer's Precision Gameplay - End Stuttering on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-to-solve-command-not-found-error-in-windows/"><u>Methodology to Solve 'Command Not Found Error' In Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-s-best-video-editing-apps-for-macbook-and-imac/"><u>New 2024 Approved S Best Video Editing Apps for MacBook and iMac</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-with-high-dynamic-range-on-windows-11-systems/"><u>Pushing Boundaries with High Dynamic Range on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-disabled-recycle-bin-on-win11/"><u>Re-Enabling Disabled Recycle Bin on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-not-found-entry-point-errors/"><u>Rectifying Windows 'Not Found' Entry Point Errors</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-your-system-replacing-outdated-windows-cards/"><u>Rejuvenating Your System: Replacing Outdated Windows Cards</u></a></li>
<li><a href="https://win11.techidaily.com/removing-restrictions-for-microsoft-store-in-windows-11/"><u>Removing Restrictions for Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-copypaste-errors-on-windows-11-pcs/"><u>Resolving Copy/Paste Errors on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-errors-in-windows/"><u>Resolving Disk Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/smartly-sorted-7-preferred-windows-photos-apps/"><u>Smartly Sorted: 7 Preferred Windows Photos Apps</u></a></li>
<li><a href="https://win11.techidaily.com/snip-and-sketch-vs-prtsc-the-window-warriors-showdown/"><u>Snip & Sketch Vs. PrtSc: The Window Warriors Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/snooze-button-secrets-for-window-computers/"><u>Snooze Button Secrets for Window Computers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frequent-file-explorer-freezes-in-windows-11/"><u>Solving Frequent File Explorer Freezes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-microsoft-11s-input-lag-8-effective-steps/"><u>Solving Microsoft 11'S Input Lag: 8 Effective Steps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-your-routine-with-chatgpt-explore-9-key-methods/"><u>Streamline Your Routine with ChatGPT: Explore 9 Key Methods</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-windows-update-eliminating-error-0x800736cc/"><u>Swift Solutions for Windows Update: Eliminating Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-troubleshoot-restore-functionality-on-windows-devices/"><u>Synapse Troubleshoot: Restore Functionality on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/top-strategies-for-resolving-minecrafts-win-error-1/"><u>Top Strategies for Resolving Minecraft's Win Error: 1</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-top-6-mickey-mouse-voice-generators/"><u>Updated Top 6 Mickey Mouse Voice Generators</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-setup-effortless-installation-of-legacy-applications/"><u>Windows 11 Setup: Effortless Installation of Legacy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/windows-arp-cache-explained-and-guide-to-clear-it-out/"><u>Windows ARP Cache Explained & Guide to Clear It Out</u></a></li>
<li><a href="https://win11.techidaily.com/winrush-securing-past-command-actions/"><u>WinRush: Securing Past Command Actions</u></a></li>
</ul></div>
