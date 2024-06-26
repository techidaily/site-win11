---
title: Customizing Firewall Defenses in 5 Easy Steps
date: 2024-06-25T10:29:36.873Z
updated: 2024-06-26T10:29:36.873Z
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
<li><a href="https://win11.techidaily.com/overhauling-windows-aural-outputs-with-win-compatible-audacity/"><u>Overhauling Windows' Aural Outputs with Win-Compatible Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-security-six-pathways-for-safe-mode/"><u>Accessing Windows 11'S Security: Six Pathways for Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-pin-verification-errors-on-w11w10-systems/"><u>Solutions for Fixing PIN Verification Errors on W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/skillful-workflow-customizing-windows-11-shortcuts-by-power-button/"><u>Skillful Workflow: Customizing Windows 11 Shortcuts by Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-steam-performance-overcoming-degraded-download-rates/"><u>Skyrocket Steam Performance: Overcoming Degraded Download Rates</u></a></li>
<li><a href="https://win11.techidaily.com/windows-history-top-removed-and-evolved-characteristics/"><u>Windows History: Top Removed and Evolved Characteristics</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-embedding-app-shortcuts-in-windows-11/"><u>Step-by-Step Guide to Embedding App Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://extra-support.techidaily.com/jocular-images-for-apple-devices-for-2024/"><u>Jocular Images for Apple Devices for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-integrating-instant-video-playback-within-the-social-media-webspace/"><u>[Updated] Integrating Instant Video Playback Within the Social Media Webspace</u></a></li>
<li><a href="https://extra-information.techidaily.com/transformative-guide-gifs-becoming-stickers-on-discord-whatsapp-and-telegram/"><u>Transformative Guide  GIFs Becoming Stickers on Discord, WhatsApp & Telegram</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/5-best-vob-video-editors-that-wont-break-the-bank-for-2024/"><u>5 Best VOB Video Editors That Wont Break the Bank for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713950501549-in-todays-article-we-are-going-to-show-you-how-adding-a-simple-lower-third-to-your-video-can-add-a-degree-of-professionalism-and-polish-to-your-videos-while/"><u>In Todays Article, We Are Going to Show You How Adding a Simple Lower Third to Your Video Can Add a Degree of Professionalism and Polish to Your Videos While Giving It a Higher Perceived Value for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-from-iphone-11-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons From iPhone 11? Find the Best Solution Here</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-economical-android-communication-tools-list/"><u>[Updated] Economical Android Communication Tools List</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-poco-m6-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-lightroom-lut-guide-discovering-the-best-10-tools-for-color-grading/"><u>In 2024, Lightroom LUT Guide  Discovering the Best 10 Tools for Color Grading</u></a></li>
</ul></div>
