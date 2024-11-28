---
title: "Windows Security Reboot: A Guide to Altering Rules"
date: 2024-11-21T16:13:51.776Z
updated: 2024-11-28T04:16:36.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Security Reboot: A Guide to Altering Rules"
excerpt: "This Article Describes Windows Security Reboot: A Guide to Altering Rules"
keywords: Windows Secure Boot,Windows Safety Reboot,Security Rule Change,Safe Windows Reboot,Update Windows Guard,Windows Security Hack,Altering Windows Defend
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Windows Security Reboot: A Guide to Altering Rules

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-tips.techidaily.com/new-in-2024-focus-and-frame-the-art-of-intimate-movie-filming/"><u>[New] In 2024, Focus & Frame The Art of Intimate Movie Filming</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-orderly-quest-for-veiled-youtube-vaults/"><u>[New] In 2024, The Orderly Quest for Veiled YouTube Vaults</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-shaping-letters-in-visual-content/"><u>[Updated] 2024 Approved Shaping Letters in Visual Content</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-building-a-brand-on-instagram-establishing-a-business-entity-for-2024/"><u>[Updated] Building a Brand on Instagram Establishing a Business Entity for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/achieving-seamless-background-blurs-in-video-calls-for-2024/"><u>Achieving Seamless Background Blurs in Video Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsofts-income-streaming-with-windows-11/"><u>Decoding Microsoft's Income Streaming with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-geforce-notaxc0f1103f-issue-on-windows-pcs/"><u>Eradicating GeForce NotaXC0F1103F Issue on Windows PCs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-you-cast-your-apple-iphone-xs-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>How Can You Cast Your Apple iPhone XS to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-f54-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-webinar-label-builder-kit/"><u>In 2024, Expert Webinar Label Builder Kit</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-guide-to-synchronized-screen-time-on-yt/"><u>In 2024, The Ultimate Guide to Synchronized Screen Time on YT</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-revolutionary-approach-in-retail-the-ai-hub/"><u>Microsoft's Revolutionary Approach in Retail: The AI Hub</u></a></li>
<li><a href="https://os-tips.techidaily.com/navigation-showdown-assessing-the-superiority-between-waze-and-google-maps/"><u>Navigation Showdown: Assessing the Superiority Between Waze and Google Maps.</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-inaudibility-windows-11s-wireless-speaker-problems/"><u>Overcoming Inaudibility: Windows 11'S Wireless Speaker Problems</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-gamesplay-fullscreen-mastery-on-pc/"><u>Transforming Your Gamesplay: FullScreen Mastery on PC</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-terminal-reset-on-win11/"><u>Understanding Terminal Reset on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveil-missing-windows-11-control-panel-features/"><u>Unveil Missing Windows 11 Control Panel Features</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-reference-mastering-text-meanings/"><u>Win11 Quick Reference: Mastering Text Meanings</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-deep-dive-into-its-data-acquisition-tactics/"><u>Windows 11: A Deep Dive Into Its Data Acquisition Tactics</u></a></li>
</ul></div>

