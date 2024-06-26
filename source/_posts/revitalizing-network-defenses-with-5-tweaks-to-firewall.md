---
title: Revitalizing Network Defenses with 5 Tweaks to Firewall
date: 2024-06-25T10:13:29.869Z
updated: 2024-06-26T10:13:29.869Z
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
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-nonstop-teams-sign-ins-on-pc/"><u>Overcoming the Hurdle of Nonstop Teams Sign-Ins on PC</u></a></li>
<li><a href="https://win11.techidaily.com/7-strategies-to-rectify-chromes-profile-problems-on-desktop/"><u>7 Strategies to Rectify Chrome's Profile Problems on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-file-explorer-experience-with-onedrive-connection/"><u>Enhance File Explorer Experience with OneDrive Connection</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winerror-740-resolving-operation-needs-promotion-in-windows-os/"><u>Overcoming WinError 740: Resolving 'Operation Needs Promotion' In Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-integration-for-steam-deck-users/"><u>Seamless Windows Integration for Steam Deck Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-rectify-hiberflattening-windows/"><u>Easy Steps to Rectify HiberFlattening Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-digital-soundtrack-the-ultimate-dj-collection/"><u>New Digital Soundtrack The Ultimate DJ Collection</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-try-the-top-free-voice-modifier-for-an-edge-in-valorant/"><u>2024 Approved  Try the Top Free Voice Modifier for an Edge in Valorant</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-how-to-create-insta-highlight-cover-photos-a-complete-guide/"><u>2024 Approved  How to Create Insta Highlight Cover Photos  A Complete Guide</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-infinix-smart-8-plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-oppo-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Oppo</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-future-in-your-hand-top-10-cutting-edge-recorder-apps/"><u>[Updated] 2024 Approved  The Future in Your Hand  Top 10 Cutting-Edge Recorder Apps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/identifying-if-someone-has-removed-you-from-their-snap-circle/"><u>Identifying if Someone Has Removed You From Their Snap Circle</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unleash-your-creativity-3-simple-ways-to-record-video-games/"><u>New 2024 Approved Unleash Your Creativity 3 Simple Ways to Record Video Games</u></a></li>
<li><a href="https://android-frp.techidaily.com/nokia-105-classic-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Nokia 105 Classic ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-mastering-sound-quality-on-your-technology/"><u>Updated In 2024, Mastering Sound Quality on Your Technology</u></a></li>
</ul></div>
