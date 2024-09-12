---
title: Direct Steps to Activate/Disable Wifi Cost Metering in Win11
date: 2024-09-11T09:35:57.358Z
updated: 2024-09-12T09:35:57.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Steps to Activate/Disable Wifi Cost Metering in Win11
excerpt: This Article Describes Direct Steps to Activate/Disable Wifi Cost Metering in Win11
keywords: Win11 WiFi Metering Control,Disable WiFi Cost Tracking,Enable WiFi No Metering,Windows 11 Wifi Adjustment,Activate/Disable Wifi Metering,Win11 WiFi Economy Mode,Turn Off Wifi Usage Feature
thumbnail: https://thmb.techidaily.com/d09e418474d756f5a8ffe485c9482504fd4de6868009955288d3f3888a8492e7.jpg
---

## Direct Steps to Activate/Disable Wifi Cost Metering in Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123466/16836" target="_top" id="2123466">
  <img src="//a.impactradius-go.com/display-ad/16836-2123466" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123466/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-earnings-spectrum-unveiling-the-financial-power-of-dailymovement-and-youtube/"><u>[New] 2024 Approved Earnings Spectrum Unveiling the Financial Power of DailyMovement and YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-transforming-viewership-engaging-end-screens-tutorials/"><u>[New] 2024 Approved Transforming Viewership Engaging End Screens Tutorials</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-complete-obs-guide-to-skype-call-recording-for-2024/"><u>[New] The Complete OBS Guide to Skype Call Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-using-windows-canary-service/"><u>Comprehensive Guide for Using Windows' Canary Service</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-network-drive-configuration-for-enhanced-workflow/"><u>Efficient Network Drive Configuration for Enhanced Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workflow-personalized-shortcut-keys/"><u>Elevate Your Workflow: Personalized Shortcut Keys</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-disabled-obstacles-for-executing-powershell-scripts/"><u>Eliminating 'Disabled' Obstacles for Executing PowerShell Scripts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-tips-for-sims-4-video-gaming/"><u>Essential Tips for Sims 4 Video Gaming</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-do-i-sim-unlock-my-apple-iphone-xr-by-drfone-ios/"><u>How Do I SIM Unlock My Apple iPhone XR?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-windows-update-issue-code-x80246007/"><u>How To Quickly Resolve Windows Update Issue Code X80246007</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-odt-file-document-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign a .odt file document online</u></a></li>
<li><a href="https://hardware-help.techidaily.com/huaweis-future-processor-strategy-drawing-inspiration-from-apples-m-series-and-intels-lunar-lake-for-next-gen-kirin-cpu/"><u>Huawei's Future Processor Strategy: Drawing Inspiration From Apple's M-Series & Intel's Lunar Lake for Next-Gen Kirin CPU</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-asus-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Asus FRP</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-navigating-the-zoom-interface-like-a-pro-in-win11/"><u>In 2024, Navigating the Zoom Interface Like a Pro in Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/leveraging-modern-ios-features-for-seamless-task-management-for-2024/"><u>Leveraging Modern iOS Features for Seamless Task Management for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202017468-master-the-fix-for-windows-10s-persistent-0x80072efd-problem-with-these-proven-tips/"><u>Master the Fix for Windows 10'S Persistent 0X80072EFD Problem with These Proven Tips!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-system-recovery-conquering-blue-screen-errors/"><u>Mastering System Recovery: Conquering Blue Screen Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC</u></a></li>
<li><a href="https://win11.techidaily.com/modify-display-scaling-in-windows-11/"><u>Modify Display Scaling in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/navigating-the-world-of-instagram-stories-easily-for-2024/"><u>Navigating the World of Instagram Stories Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-0x80070003-during-system-upgrades/"><u>Overcoming Windows Error: 0X80070003 During System Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-block-after-failure/"><u>Overcoming Windows Login Block After Failure</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-windows-model-years-simplified/"><u>Pinpointing Windows Model Years Simplified</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-brightness-overcoming-dark-screen-problems/"><u>Restoring Brightness: Overcoming Dark Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-15-ways-to-reach-windows-settings/"><u>Simplify: 15 Ways to Reach Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-windows-security-today-with-free-desktop-pass-gen-apps/"><u>Step Up Windows Security Today With Free Desktop Pass Gen Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-strategies-to-address-and-fix-critical-ntldr-error-messages/"><u>Step-by-Step Strategies to Address and Fix Critical NTLDR Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-approach-to-remedy-error-0x80070570-and-file-corruption-in-windows-11/"><u>Strategic Approach to Remedy Error 0X80070570 & File Corruption in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-windows-experience-resetting-apps/"><u>Streamlining Your Windows Experience: Resetting Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-ios-photo-importers-on-windows-11/"><u>Troubleshooting iOS Photo Importers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-steps-for-windows-copilot-enablement/"><u>ViveTool Steps for Windows Copilot Enablement</u></a></li>
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-samsung-galaxy-m54-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Samsung Galaxy M54 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-reset-triggers-top-10-tips/"><u>Windows Reset Triggers: Top 10 Tips</u></a></li>
</ul></div>

