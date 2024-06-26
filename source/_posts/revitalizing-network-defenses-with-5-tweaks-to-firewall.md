---
title: Revitalizing Network Defenses with 5 Tweaks to Firewall
date: 2024-06-25T11:32:05.040Z
updated: 2024-06-26T11:32:05.040Z
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
<li><a href="https://win11.techidaily.com/mastering-fresh-windows-11-setup/"><u>Mastering Fresh Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-desktop-efficiency-with-wmdesk/"><u>Revolutionize Desktop Efficiency with WmDesk</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-video-sequences-fixing-delay-on-windows/"><u>Speeding Up Video Sequences: Fixing Delay on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011-ad-ds-printer-errors-effectively-and-efficiently/"><u>Addressing Win 10/11 AD DS Printer Errors Effectively and Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-averting-crashes-of-epic-games-launcher/"><u>Strategies for Averting Crashes of Epic Games Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/pivotal-security-titans-winning-passwords-in-windows-11/"><u>Pivotal Security Titans: Winning Passwords in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-experts-guide-to-infinite-space-utilization/"><u>[Updated] Expert's Guide to Infinite Space Utilization</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-top-picks-of-free-hd-video-backdrops-the-internets-most-reliable-sources-updated/"><u>Updated Top Picks of Free HD Video Backdrops The Internets Most Reliable Sources (Updated )</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-create-a-quick-google-collage-photo/"><u>2024 Approved  How to Create a Quick Google Collage Photo</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-expert-insights-5-pro-tips-for-getting-the-most-out-of-your-16x9-ratio-calculator/"><u>Updated In 2024, Expert Insights 5 Pro Tips for Getting the Most Out of Your 16X9 Ratio Calculator</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-cyclings-finest-gaming-experiences/"><u>[Updated] In 2024, Cycling's Finest Gaming Experiences</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-insiders-guide-to-recording-slideshows/"><u>[New] The Insider's Guide to Recording Slideshows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-xiaomi-redmi-note-12-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Xiaomi Redmi Note 12 5G For Mobile Legends? | Dr.fone</u></a></li>
</ul></div>
