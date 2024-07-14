---
title: Five Keys to a Streamlined Firewall Configuration
date: 2024-07-13T09:59:25.461Z
updated: 2024-07-14T09:59:25.461Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Five Keys to a Streamlined Firewall Configuration
excerpt: This Article Describes Five Keys to a Streamlined Firewall Configuration
keywords: Efficient Firewall Setup,Simplify Network Security,Optimize Firewall Strategy,Enhanced Firewall Management,Firewall Configuration Streamlining,Secure Network Defense,Accelerated Firewall Arrangement
thumbnail: https://thmb.techidaily.com/9ed4d2a342c503dc1182b48b6f97e1914eb836100fe0df4621fadbbe35959f4b.jpg
---

## Five Keys to a Streamlined Firewall Configuration

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

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

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
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-express-corporate-essence-designing-emblems-on-the-go/"><u>[Updated] Express Corporate Essence - Designing Emblems on the Go</u></a></li>
<li><a href="https://extra-tips.techidaily.com/tailored-audio-connector-for-podcasting-pros/"><u>Tailored Audio Connector for Podcasting Pros</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-ultimate-resource-for-adding-dynamic-gifs-to-discord-conversations-for-2024/"><u>[Updated] The Ultimate Resource for Adding Dynamic GIFs to Discord Conversations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-reliable-voice-commands-for-valorant-gaming/"><u>Ensuring Reliable Voice Commands for Valorant Gaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revealing-10-mixer-marvels-perfected-for-professional-podcasting/"><u>[New] Revealing 10 Mixer Marvels, Perfected For Professional Podcasting</u></a></li>
<li><a href="https://techidaily.com/stellar-data-recovery-for-iphone-6s-plus-failed-to-recognize-my-iphone-how-to-fix-it-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Stellar Data Recovery for iPhone 6s Plus failed to recognize my iPhone. How to fix it? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-typing-experience-changing-layouts-on-windows-11/"><u>Tailoring Your Typing Experience: Changing Layouts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sector-mastering-windows-methods-for-adapter-velocity-check/"><u>Speed Sector: Mastering Windows Methods for Adapter Velocity Check</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-demystified-how-to-resolve-windows-crashes-quickly/"><u>Blue Screen Demystified: How To Resolve Windows Crashes Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-overcoming-geforce-x0001-on-w10w11-pcs/"><u>Quick Tips: Overcoming GeForce X0001 on W10/W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-windows-11-desktop-sparkle-with-lively-wallpaper-art/"><u>Make Your Windows 11 Desktop Sparkle with Lively Wallpaper Art</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-email-banners-for-office-users/"><u>Reviving Non-Functional Email Banners for Office Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-viral-video-vanguard-top-ten-in-one-hour-one-day-on-yt/"><u>In 2024, Viral Video Vanguard  Top Ten in One Hour, One Day on YT</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-power-for-distributed-video-conversion-by-tdarr/"><u>Optimize PC Power for Distributed Video Conversion by Tdarr</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-efficiency-via-powertoys/"><u>Accelerate Keyboard Efficiency via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-no-budget-no-problem-10-free-video-editors-for-ubuntu-users/"><u>New 2024 Approved No Budget? No Problem! 10 Free Video Editors for Ubuntu Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streamlined-method-for-crafting-mobile-focused-youtube-channels/"><u>[Updated] Streamlined Method for Crafting Mobile-Focused YouTube Channels</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-oneplus-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from OnePlus</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-first-steps-in-youtube-profitability-starting-a-channel-and-revenue-streams-for-2024/"><u>[Updated] First Steps in YouTube Profitability  Starting a Channel & Revenue Streams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-dimensions-for-youtube-shorts-facebook-instagram-and-other-social-apps/"><u>[New] Dimensions for YouTube Shorts, Facebook, Instagram and Other Social Apps</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-boost-your-tiktok-presence-with-strategic-captioning-methods-for-2024/"><u>[Updated] Boost Your TikTok Presence with Strategic Captioning Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-frame-by-frame-how-to-convert-videos-to-images-with-these-10-powerful-tools-for-2024/"><u>Updated Frame by Frame How to Convert Videos to Images with These 10 Powerful Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-administrator-experience-via-terminals-every-time/"><u>Unhindered Administrator Experience via Terminals Every Time</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-windows-voice-recording/"><u>A Step-By-Step Guide to Windows Voice Recording</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-post-production-pro-tailoring-video-content-to-instagram-standards-with-x/"><u>[New] In 2024, Post-Production Pro  Tailoring Video Content to Instagram Standards with X</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-make-a-fortune-on-reddit-without-experience-top-13-methods-for-2024/"><u>How to Make a Fortune on Reddit Without Experience - Top 13 Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-gallery-in-file-explorer-in-windows-11/"><u>How to Enable the Gallery in File Explorer in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-capture-and-share-the-art-of-using-zooms-snaps/"><u>2024 Approved  Capture & Share  The Art of Using Zoom's Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-canary-your-security-ally/"><u>Intro to Windows Canary: Your Security Ally</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-x-without-passcode-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone X Without Passcode?</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-storytelling-through-scenery/"><u>[New] Unveiling Storytelling Through Scenery</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-top-10-best-introduction-editors-apps/"><u>[New] Top 10 Best Introduction Editors (Apps)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-discover-the-leading-free-game-recording-tools/"><u>2024 Approved  Discover the Leading Free Game Recording Tools</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/shattering-synthetic-statistics-on-youtube/"><u>Shattering Synthetic Statistics on YouTube</u></a></li>
</ul></div>
