---
title: Resetting the Windows Firewall with Precision
date: 2024-06-25T11:43:28.822Z
updated: 2024-06-26T11:43:28.822Z
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
<li><a href="https://win11.techidaily.com/delving-into-the-heart-of-windows-11-registry-explained/"><u>Delving Into the Heart of Windows 11: Registry Explained</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-vs-powershell-pinpointing-the-distinguishing-aspects/"><u>Terminal Vs. PowerShell: Pinpointing the Distinguishing Aspects</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-mic-silenced-tips-to-unmute-for-google-meet-on-pc/"><u>Microsoft Mic Silenced: Tips to Unmute for Google Meet on PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-stop-laptops-internal-keystrokes/"><u>Step-by-Step: Stop Laptop's Internal Keystrokes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-simple-processes-for-logging-vimeo-content/"><u>[New] 2024 Approved  Simple Processes for Logging Vimeo Content</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-in-depth-steps-to-document-googles-collaborative-sessions/"><u>2024 Approved  In-Depth Steps to Document Google's Collaborative Sessions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-prime-capture-device-your-ally-in-youtube-ventures/"><u>[Updated] Prime Capture Device  Your Ally in YouTube Ventures</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/final-cut-pro-x-freeze-frames-and-slow-motion/"><u>Final Cut Pro X Freeze-Frames and Slow Motion</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-from-shots-to-screens-the-importance-of-camera-lenses-in-vlogs-for-2024/"><u>[Updated] From Shots to Screens  The Importance of Camera Lenses in Vlogs for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-ultimate-guide-to-choosing-your-best-online-mp3-editor-from-five-sought-after-options/"><u>New The Ultimate Guide to Choosing Your Best Online MP3 Editor From Five Sought-After Options</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-grasping-your-youtube-popularity-with-precision/"><u>[New] Grasping Your YouTube Popularity with Precision</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-advanced-software-options-for-distilling-pure-auditory-experiences/"><u>Updated 2024 Approved Advanced Software Options for Distilling Pure Auditory Experiences</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-smart-tips-for-gif-lovers-iphone-edition/"><u>2024 Approved  Smart Tips for GIF Lovers  IPhone Edition</u></a></li>
</ul></div>
