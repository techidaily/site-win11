---
title: 5 Ways to Reset the Windows Firewall Settings
date: 2024-07-13T11:09:02.693Z
updated: 2024-07-14T11:09:02.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Reset the Windows Firewall Settings
excerpt: This Article Describes 5 Ways to Reset the Windows Firewall Settings
keywords: Windows Firewall Reset Guide,Restarting Firewall on PC,Change Windows Firewall,Enable/Disable Firewall,Update Firewall Settings,Safe Mode Firewall,Custom Firewall Configs
thumbnail: https://thmb.techidaily.com/8a309f6aebab825a6cd0baff1d0b8550d45fadce34f31fb21e5a5f2109ae3299.jpg
---

## 5 Ways to Reset the Windows Firewall Settings

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
<li><a href="https://screen-activity-recording.techidaily.com/hp-laptop-tips-for-perfect-screen-recordings-for-2024/"><u>HP Laptop Tips for Perfect Screen Recordings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-absence-of-printmanagement-on-your-system/"><u>Remedying the Absence of 'Printmanagement' On Your System</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-office-setup-on-windows-10-and-11-systems/"><u>Mastering Office Setup on WIndows 10 & 11 Systems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-expert-roundup-of-platforms-for-video-intro-acquisition/"><u>[New] 2024 Approved  Expert Roundup of Platforms for Video Intro Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ical-integration-on-windows-11-systems/"><u>Mastering iCal Integration on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/is-it-necessary-to-keep-pagefilesys-reasons-explored/"><u>Is It Necessary to Keep Pagefile.sys? Reasons Explored</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-bypassing-non-active-window-firewall/"><u>Methods for Bypassing Non-Active Window Firewall</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/having-gopro-accessories-is-easy-but-editing-on-gopro-quik-is-challenging-read-this-guide-and-stepwise-learn-to-use-gopro-slow-motion-for-perfect-shots-for-/"><u>Having GoPro Accessories Is Easy, but Editing on GoPro Quik Is Challenging. Read This Guide and, Stepwise, Learn to Use GoPro Slow-Motion for Perfect Shots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-9-methods-for-accessing-windows-11s-audio-control-panel/"><u>Navigate 9 Methods for Accessing Windows 11'S Audio Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-pc-with-the-top-10-must-try-powertoy-applications/"><u>Reimagine Your PC with the Top 10 Must-Try PowerToy Applications</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-a-simple-tutorial-starting-screen-recording-on-mac/"><u>[Updated] 2024 Approved  A Simple Tutorial  Starting Screen Recording on Mac</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-hottest-10-filter-techniques-that-captivate-audiencv3-ultimate-list-top-10-stand-out-tikfilters-for-content/"><u>[New] In 2024, Hottest 10 Filter Techniques That Captivate Audiencv3. Ultimate List  Top 10 Stand-Out TikFilters for Content</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-mass-unzipping-on-your-pc/"><u>Navigating the Maze of Mass Unzipping on Your PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-transform-your-photos-into-musical-masterpieces-withwithout/"><u>[Updated] In 2024, Transform Your Photos Into Musical Masterpieces (With/Without)</u></a></li>
<li><a href="https://win11.techidaily.com/new-wave-windows-leap-from-the-legacy-of-11/"><u>New Wave Windows: Leap From the Legacy of 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y100i-power-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y100i Power 5G Phone without PIN</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-realme-v30-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Realme V30</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigate-and-watch-harnessing-netflixs-picture-in-picture-functionality/"><u>Navigate and Watch  Harnessing Netflix's Picture-in-Picture Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-a-guide-to-mastering-window-11s-taskbar-search-function/"><u>Quick Start: A Guide to Mastering Window 11’S Taskbar Search Function</u></a></li>
<li><a href="https://extra-tips.techidaily.com/avoiding-pitfalls-in-angled-and-merged-video-manipulation-android/"><u>Avoiding Pitfalls in Angled & Merged Video Manipulation (Android)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-vimeo-cash-flow-maximizing-income-through-content-marketing/"><u>[New] Vimeo Cash Flow  Maximizing Income Through Content Marketing</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-discords-critical-js-error-on-windows-1011-systems/"><u>Resolving Discord's Critical JS Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/viral-visibility-vault-our-compreeher-guide-of-15-proven-methods-to-amass-attention-on-instagram/"><u>Viral Visibility Vault  Our Compreeher Guide of 15 Proven Methods to Amass Attention on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/seven-keys-to-unlocking-the-full-potential-of-windows-software/"><u>Seven Keys to Unlocking the Full Potential of Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-windows-uac-prompt-pictures/"><u>Securely Storing Windows UAC Prompt Pictures</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-windows-default-settings-on-reboot/"><u>Quick Tips for Windows Default Settings on Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/virality-voyage-navigating-newsfeeds-with-noteworthy-posts-for-2024/"><u>Virality Voyage  Navigating Newsfeeds with Noteworthy Posts for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-steady-as-a-rock-how-to-remove-camera-shake-in-after-effects/"><u>2024 Approved Steady as a Rock How to Remove Camera Shake in After Effects</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-to-rectify-windows-defenders-error-0x80004004/"><u>Step-by-Step to Rectify Windows Defender’s Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-traditional-windows-explorer-look/"><u>Reclaiming Traditional Windows Explorer Look</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unmasking-the-world-of-live-streamed-digital-personalities/"><u>Unmasking the World of Live-Streamed Digital Personalities</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/masked-commands-the-win-1011-trickery-guide/"><u>Masked Commands: The Win 10/11 Trickery Guide</u></a></li>
<li><a href="https://win11.techidaily.com/realign-google-chrome-clock-with-windows-time/"><u>Realign Google Chrome Clock with Windows Time</u></a></li>
</ul></div>
