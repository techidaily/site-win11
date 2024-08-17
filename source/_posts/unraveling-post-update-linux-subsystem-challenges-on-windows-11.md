---
title: Unraveling Post-Update Linux Subsystem Challenges on Windows 11
date: 2024-08-16T00:32:00.343Z
updated: 2024-08-17T00:32:00.343Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Post-Update Linux Subsystem Challenges on Windows 11
excerpt: This Article Describes Unraveling Post-Update Linux Subsystem Challenges on Windows 11
keywords: Post-Linux Update Issues,Win11 Subsystem Woes,Windows 11 LXC Troubleshooting,Linux Subsystem Instability,BIOS Setup After Linux,Windows/Linux Compatibility,LXC Optimization Strategies
thumbnail: https://thmb.techidaily.com/f78a12d6fa260b60593d7d84df0572fbc03e543ca8c86ab396fe09af56299ebf.jpg
---

## Unraveling Post-Update Linux Subsystem Challenges on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-honored-advisors-elite-iphone-audio-experts/"><u>[New] 2024 Approved  Honored Advisors  Elite iPhone Audio Experts</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-cloud-space-costs-analyzing-and-top-tier-savings-guide-for-2024/"><u>[New] Cloud Space Costs  Analyzing & Top-Tier Savings Guide for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-unlock-superior-mac-gif-capture-with-these-apps/"><u>[New] In 2024, Unlock Superior Mac GIF Capture with These Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-instructions-for-crafting-and-installing-whatsapp-alerts/"><u>[New] Step-By-Step Instructions for Crafting & Installing WhatsApp Alerts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-proven-ways-to-record-and-save-ps4-games/"><u>[Updated] 2024 Approved  Proven Ways to Record and Save PS4 Games</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-circulating-camera-mounts-for-vr/"><u>[Updated] Circulating Camera Mounts for VR</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-debugging-techniques-identifying-and-resolving-common-javascript-errors/"><u>[Updated] Debugging Techniques  Identifying and Resolving Common JavaScript Errors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-ipads-best-practices-for-clear-voice-recording/"><u>[Updated] IPad's Best Practices for Clear Voice Recording</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leading-free-converters-ranking-the-10-for-jpg-to-gif-changeover/"><u>[Updated] Leading Free Converters  Ranking the 10 for JPG to GIF Changeover</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-science-of-audience-retention-on-tweets/"><u>[Updated] The Science of Audience Retention on Tweets</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfecting-audio-records-with-our-step-by-step-guide/"><u>2024 Approved  Perfecting Audio Records with Our Step-by-Step Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-unlocking-hdr-photography-selecting-superior-models/"><u>2024 Approved  Unlocking HDR Photography  Selecting Superior Models</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-zipping-with-command-prompt-step-by-step/"><u>Advanced Zipping with Command Prompt, Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-you-trust-chatgpt-with-your-proofreading-needs/"><u>Can You Trust ChatGPT with Your Proofreading Needs?</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-hp-officejet-pro-8720-drivers-on-windows-free-guide/"><u>Download & Update HP OfficeJet Pro 8720 Drivers on Windows - Free Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-uninstalling-apps-on-windows-11/"><u>Efficiently Uninstalling Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-on-capturing-windows-calls-effectively/"><u>Essential Tips on Capturing Windows Calls Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-iphone-se-2020-in-lost-mode-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock iPhone SE (2020) in Lost Mode</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-tecno-spark-20-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Tecno Spark 20 Phone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-iphone-12-mini-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your iPhone 12 mini Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-devhome-navigating-windows-11-with-ease/"><u>Introducing DevHome: Navigating Windows 11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-surface-studio-2-almost-perfect-creators-choice/"><u>Microsoft Surface Studio 2 - Almost Perfect Creator's Choice</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-microsoft-store-sign-in-blocks/"><u>Navigate Through Microsoft Store Sign-In Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-public-ip-using-windows-command-window/"><u>Navigate to Public IP Using Windows Command Window</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-maintenance-tips-for-setting-active-windows-11-times/"><u>Navigating System Maintenance: Tips for Setting Active Windows 11 Times</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-task-manager-unresponsiveness/"><u>Overcoming Windows Task Manager Unresponsiveness</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://driver-install.techidaily.com/rectify-acuity-inkjet-issues-on-windows-11/"><u>Rectify Acuity Inkjet Issues on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/reel-it-in-8-online-utilities-for-creating-and-sharing-instagram-videos/"><u>Reel It In  8 Online Utilities For Creating & Sharing Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revealing-windows-10-screen-extras-unlocked/"><u>Revealing Windows 10 Screen Extras Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-shield-5-key-fixes-for-windows-family-protection/"><u>Revive the Shield: 5 Key Fixes for Windows Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>Spoofing Life360 How to Do it on Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-wallpapers-for-each-windows-11-workspace-element/"><u>Step-by-Step Wallpapers for Each Windows 11 Workspace Element</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/subtlety-matters-fading-out-sounds-in-logic-pro/"><u>Subtlety Matters  Fading Out Sounds in Logic Pro</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-se-2020-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-disabled-microsoft-outlook-push-notifications/"><u>Troubleshooting Disabled Microsoft Outlook Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-virtual-disk-service-failure-in-windows/"><u>Troubleshooting: Resolving Virtual Disk Service Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-auditory-interference-mystery/"><u>Unraveling Windows' Auditory Interference Mystery</u></a></li>
<li><a href="https://facebook.techidaily.com/whats-new-facebook-writes-checks-with-every-streamed-tune/"><u>What's New: Facebook’ Writes Checks with Every Streamed Tune</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
</ul></div>
