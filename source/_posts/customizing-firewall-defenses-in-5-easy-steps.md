---
title: Customizing Firewall Defenses in 5 Easy Steps
date: 2024-06-25T11:37:28.551Z
updated: 2024-06-26T11:37:28.551Z
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
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-unlock-your-windows-pin/"><u>Efficient Methods to Unlock Your Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-the-electrical-footprint-of-your-personal-windows-pc/"><u>Analyzing the Electrical Footprint of Your Personal Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-the-not-responsive-window-software-problem/"><u>Mastery over the Not Responsive Window Software Problem</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-win11-powertoys-experience/"><u>Unveiling the Win11 PowerToys Experience</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-blackout-blitz-premiere-pro-60s/"><u>In 2024, Blackout Blitz  Premiere Pro 60S</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-reviews-features-and-tutorial-of-lexis-audio-editor/"><u>Updated In 2024, Reviews, Features and Tutorial of Lexis Audio Editor</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-essential-top-30-screen-capturing-tools-for-ubuntu/"><u>[Updated] Essential Top 30 Screen Capturing Tools for Ubuntu</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-oneplus-ace-2-pro-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on OnePlus Ace 2 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-unlock-minitool-movie-makers-full-potential-tips-tricks-and-alternatives/"><u>New 2024 Approved Unlock Minitool Movie Makers Full Potential Tips, Tricks, and Alternatives</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-the-biggest-tweet-waves-of-2023-decoded/"><u>[New] 2024 Approved  The Biggest Tweet Waves of 2023 Decoded</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-biography-breakthroughs-101-expert-tips-and-tricks-for-facebook-biographers/"><u>In 2024, Biography Breakthroughs  101 Expert Tips and Tricks for Facebook Biographers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-ultimate-roadmap-to-profit-via-instagram-platform/"><u>2024 Approved  The Ultimate Roadmap to Profit via Instagram Platform</u></a></li>
</ul></div>
