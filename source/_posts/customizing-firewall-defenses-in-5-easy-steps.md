---
title: Customizing Firewall Defenses in 5 Easy Steps
date: 2024-08-15T23:56:22.602Z
updated: 2024-08-16T23:56:22.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Firewall Defenses in 5 Easy Steps
excerpt: This Article Describes Customizing Firewall Defenses in 5 Easy Steps
keywords: Custom Firewall Setup,Firewall Configuration Guide,Firewall Defense Planning,Simple Firewall Tips,Efficient Firewall Protocols,Enhanced Network Security,Steps to Firewall Optimization
thumbnail: https://thmb.techidaily.com/150a758dee3602d845be20dca449cfe34839f49d05b66229d2abdef97e1d0864.jpg
---

## Customizing Firewall Defenses in 5 Easy Steps

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-discovering-old-content-on-facebook-via-your-smartphonecomputer/"><u>[New] 2024 Approved  Discovering Old Content on Facebook via Your Smartphone/Computer</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-instantly-post-videos-on-twitter-using-phones-skipping-retweets/"><u>[New] Instantly Post Videos on Twitter Using Phones, Skipping Retweets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-insiders-look-at-vidma-screen-recording-for-2024/"><u>[New] The Insider's Look at Vidma Screen Recording for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-streamlining-time-tracking-for-youtube-videos/"><u>[Updated] 2024 Approved  Streamlining Time Tracking for YouTube Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-enhance-pc-listening-experience-install-x-recorder-for-2024/"><u>[Updated] Enhance PC Listening Experience - Install X-Recorder for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-hacks-to-dodge-digital-lessons-at-home/"><u>[Updated] Hacks to Dodge Digital Lessons at Home</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unlocking-the-process-for-final-deactivation-of-an-account-on-instagram/"><u>2024 Approved  Unlocking the Process for Final Deactivation of an Account on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/3-essential-methods-to-enable-telnet-in-win11/"><u>3 Essential Methods to Enable Telnet in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-view-the-applied-group-policies-on-windows/"><u>3 Ways to View the Applied Group Policies on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-pivotal-points-for-reconnecting-your-obs-studio-link-win-compatible/"><u>7 Pivotal Points for Reconnecting Your OBS Studio Link (Win-Compatible)</u></a></li>
<li><a href="https://win11.techidaily.com/8-handy-windows-11-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 11 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-steam-download-rates-overcoming-sluggish-pace/"><u>Accelerate Steam Download Rates: Overcoming Sluggish Pace</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-task-management-in-microsoft-project/"><u>Accelerate Task Management in Microsoft Project</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-email-checking-add-gmail-to-your-windows-side/"><u>Accelerated Email Checking: Add Gmail to Your Window's Side</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-ide-performance-android-studio-tips/"><u>Accelerating IDE Performance: Android Studio Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-icon-alignment-on-pcs/"><u>Achieve Seamless Icon Alignment on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/activatedeactivate-window-11-search-lights/"><u>Activate/Deactivate Window 11 Search Lights</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-forbidden-page-in-windows-environment/"><u>Addressing Forbidden Page in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-nvidia-cp-in-w11-environments/"><u>Addressing Non-Operational NVidia CP in W11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-task-managers-empty-startup-tab/"><u>Addressing Task Manager's Empty Startup Tab</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-lockout-interval-after-multiple-login-failures/"><u>Adjusting Lockout Interval After Multiple Login Failures</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-account-lockout-counter-following-unsuccessful-logins-in-w10w11/"><u>Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-graphics-techniques-in-edge-app-guard/"><u>Advanced Graphics Techniques in Edge App Guard</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-partition-management-tactics/"><u>Advanced Windows Partition Management Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-alchemy-how-to-seamlessly-change-windows-11-themes-and-enrich-your-workspace/"><u>Aesthetic Alchemy: How to Seamlessly Change Windows 11 Themes and Enrich Your Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-the-curve-using-vivetool-on-your-pc/"><u>Ahead of the Curve: Using ViVeTool on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-odds-tackling-installer-errors-in-win11-successfully/"><u>Beating the Odds: Tackling Installer Errors in Win11 Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-10-and-11-climate-choices/"><u>Best Windows 10 & 11 Climate Choices</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakdown-is-windows-hello-still-reliable/"><u>Biometric Breakdown: Is Windows Hello Still Reliable?</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-reimagining-administrative-protocols-on-windows/"><u>Breaking Barriers: Reimagining Administrative Protocols on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-w11-0x8004def5-onedrive-fixes/"><u>Breaking Down the W11 0X8004DEF5 Onedrive Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>How To Simulate GPS Movement With Location Spoofer On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-audio-capture-made-easy-in-windows-10/"><u>In 2024, Audio Capture Made Easy in Windows 10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-identifying-the-optimal-cloud-data-vaults/"><u>In 2024, Identifying the Optimal Cloud Data Vaults</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-on-screen-image-enhancement-mastering-online-cropping-tactics/"><u>In 2024, On-Screen Image Enhancement  Mastering Online Cropping Tactics</u></a></li>
<li><a href="https://fox-glue.techidaily.com/kinetic-mastery-in-your-pocket-a-2023-review-of-kinemaster-on-android/"><u>Kinetic Mastery in Your Pocket  A 2023 Review of KineMaster on Android</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionize-your-earning-game-with-top-13-strategies-for-novices-on-reddit/"><u>Revolutionize Your Earning Game with Top 13 Strategies for Novices on Reddit</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-text-tilt-treasures/"><u>Top Text Tilt Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/1719360575372-trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods!</u></a></li>
<li><a href="https://win11.techidaily.com/1719298121554-troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions</u></a></li>
</ul></div>
