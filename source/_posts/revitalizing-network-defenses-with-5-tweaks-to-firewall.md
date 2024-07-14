---
title: Revitalizing Network Defenses with 5 Tweaks to Firewall
date: 2024-07-13T10:19:53.365Z
updated: 2024-07-14T10:19:53.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revitalizing Network Defenses with 5 Tweaks to Firewall
excerpt: This Article Describes Revitalizing Network Defenses with 5 Tweaks to Firewall
keywords: Boost Firewall Efficacy,Enhance Network Security,Strengthen Firewall Layer,Update Firewall Defenses,Optimize Firewall Configs,Fortify Cyber Defense,Improve Firewall Performance
thumbnail: https://thmb.techidaily.com/4bfb6726743e0e9796541acae362817f2192de4cf7881ce69268badea3558c76.jpg
---

## Revitalizing Network Defenses with 5 Tweaks to Firewall

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
<li><a href="https://win11.techidaily.com/understanding-windows-11s-6-unusual-visual-cues/"><u>Understanding Windows 11'S 6 Unusual Visual Cues</u></a></li>
<li><a href="https://win11.techidaily.com/premium-temperature-trackers-on-win-os/"><u>Premium Temperature Trackers on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-customize-your-functional-keys-configuration/"><u>Win 10/11: Customize Your Functional Keys Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-persistent-login-prompt-issues-in-windows/"><u>Skirting Persistent Login Prompt Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-a-cohesive-file-landscape-in-win1011/"><u>Conjuring a Cohesive File Landscape in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-visual-vibrancy-of-a-frozen-windows-device/"><u>Reviving the Visual Vibrancy of a Frozen Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-gems-of-windows-world-windows-11s-stealth-menu-secrets/"><u>Hidden Gems of Window's World: Windows 11’S Stealth Menu Secrets</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ow-to-maximize-video-reach-with-effective-tags-titles-for-2024/"><u>[New] How to Maximize Video Reach with Effective Tags, Titles for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-diagnose-and-correct-disk-read-errors/"><u>How to Diagnose and Correct Disk Read Errors</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-secure-network-shadows-in-windows/"><u>Crafting Secure Network Shadows in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-tiktok-sound-comprerancy-on-muted-video-segments/"><u>[Updated] TikTok Sound  Comprerancy on Muted Video Segments</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-spectrumsewn-studio-photo-montage-expertise/"><u>[Updated] SpectrumSewn Studio  Photo Montage Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/finding-lost-windows-proven-strategies-for-win11-users/"><u>Finding Lost Windows: Proven Strategies for Win11 Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-unlocking-videos-with-a-click-ios-apps-rising-in-the-rankings-on-fb-downloader-list/"><u>[Updated] 2024 Approved  Unlocking Videos with a Click  IOS Apps Rising in the Rankings on FB Downloader List</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-syncs-a-guide-to-onedrive-operations-on-windows/"><u>Fixing Failed Syncs: A Guide to OneDrive Operations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-solving-directdraw-glitches-quickly/"><u>Win10/11: Solving DirectDraw Glitches Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-addressing-winscombsvc-errors-in-windows-os/"><u>Tips & Tricks for Addressing WinScombSvc Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-text-conversations-emoji-15-installation-guide-for-windows-11/"><u>Revamping Text Conversations: Emoji 15 Installation Guide for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-system-fixes-through-keyboard-shortcuts-on-windows/"><u>Uncomplicated System Fixes Through Keyboard Shortcuts on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/does-find-my-friends-work-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-achieving-professional-sound-without-a-mic/"><u>[Updated] The Ultimate Guide  Achieving Professional Sound without a Mic</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-your-smartphone-as-a-windows-microphone/"><u>How to Use Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-exploring-the-new-frontier-of-android-gaming-with-kinemaster-for-2024/"><u>[Updated] Exploring the New Frontier of Android Gaming with KineMaster for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-clearing-up-cacophony-3-easy-steps-to-mute-audio-echoes/"><u>Updated In 2024, Clearing Up Cacophony 3 Easy Steps to Mute Audio Echoes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/uplift-your-videos-top-techniques-for-iphones-brightness/"><u>Uplift Your Videos  Top Techniques for iPhone's Brightness</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crafting-spectaculous-1080p-streams-on-fb-groups/"><u>In 2024, Crafting Spectaculous 1080P Streams on FB Groups</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-calls-fails-on-windows-devices/"><u>Overcoming System Calls Fails on Windows Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ranked-best-voice-change-software-echo-magic-edition-for-2024/"><u>[Updated] Ranked Best Voice Change Software  Echo Magic Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-interruptnothandled-error-on-win11/"><u>Eliminating the INTERRUPT_NOT_HANDLED Error on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/why-ditch-bot-helmed-windows-key-creation/"><u>Why Ditch Bot-Helmed Windows Key Creation?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-setback-preserving-saving-functionality-of-nvidia-cp/"><u>Overcoming Setback: Preserving Saving Functionality of Nvidia CP</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-poco-x5-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Poco X5 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-step-by-step-tutorial-to-elevate-your-slow-motion-videos/"><u>[Updated] 2024 Approved  Step-by-Step Tutorial to Elevate Your Slow Motion Videos</u></a></li>
</ul></div>
