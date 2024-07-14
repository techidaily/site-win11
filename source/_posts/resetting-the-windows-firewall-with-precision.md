---
title: Resetting the Windows Firewall with Precision
date: 2024-07-13T11:00:31.240Z
updated: 2024-07-14T11:00:31.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting the Windows Firewall with Precision
excerpt: This Article Describes Resetting the Windows Firewall with Precision
keywords: Firewall Reset Guide,Precision Firewall Controls,Fine-Tune Firewall Settings,Manage Windows Firewall,Optimize Firewall Config,Secure Network Protocol,Enhance Security Policy
thumbnail: https://thmb.techidaily.com/02374ddd20d049e41c0d0fe41e4dbd023d73e596f3add5f5b8f6d266eddb08ec.png
---

## Resetting the Windows Firewall with Precision

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
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-decoding-twitter-archived-content-for-clarity/"><u>[New] 2024 Approved  Decoding Twitter Archived Content for Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-uninstalling-apps-on-windows-11/"><u>Efficiently Uninstalling Apps on Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-reigning-over-tiktok-secrets-to-viral-success-in-advertising/"><u>[New] In 2024, Reigning Over TikTok  Secrets to Viral Success in Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-devhome-navigating-windows-11-with-ease/"><u>Introducing DevHome: Navigating Windows 11 with Ease</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-strategies-adding-engaging-chapters-to-your-youtube-content-for-2024/"><u>Step-by-Step Strategies  Adding Engaging Chapters to Your YouTube Content for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1716068740162-updated-2024-approved-obs-full-screen-no-more-problem/"><u>[Updated] 2024 Approved  Obs Full-Screen No More Problem!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-eagleeyesnap-ultimate-mac-and-windows-image-tools/"><u>[New] 2024 Approved  EagleEyeSnap  Ultimate Mac & Windows Image Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-dance-revolution-tiktok-routines-on-a-mac-platform/"><u>In 2024, Dance Revolution  TikTok Routines on a Mac Platform</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://extra-support.techidaily.com/nikon-d-500-4k-dslr-camera-review-for-2024/"><u>Nikon D 500 4K DSLR Camera Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-task-manager-unresponsiveness/"><u>Overcoming Windows Task Manager Unresponsiveness</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-microsoft-store-sign-in-blocks/"><u>Navigate Through Microsoft Store Sign-In Blocks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://facebook.techidaily.com/beware-the-web-discerning-social-media-pitfalls/"><u>Beware the Web: Discerning Social Media Pitfalls</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-how-to-record-gameplay-and-webcam/"><u>[Updated] 2024 Approved  How to Record Gameplay and Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/harnessing-youtube-and-fb-techniques-for-maximum-engagement-for-2024/"><u>Harnessing YouTube & FB Techniques for Maximum Engagement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
</ul></div>
