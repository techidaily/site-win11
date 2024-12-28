---
title: Secure Windows with These 5 Firewall Adjustments
date: 2024-12-23T06:45:17.844Z
updated: 2024-12-27T19:20:08.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure Windows with These 5 Firewall Adjustments
excerpt: This Article Describes Secure Windows with These 5 Firewall Adjustments
keywords: Secure Windows Firewall,Enhance Security Windows,Stronger Windows Defense,Improve Windows Safety,Optimize Windows Protection,Boost Windows Security,Tighten Windows Shields
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Secure Windows with These 5 Firewall Adjustments

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-cutting-edge-e-learning-sites-that-dont-fit-udemy/"><u>[New] 2024 Approved Cutting-Edge E-Learning Sites That Don't Fit Udemy</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-perfect-pixels-with-pro-android-tips/"><u>[New] Perfect Pixels with Pro Android Tips</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-easy-steps-how-to-master-the-best-of-9-free-youtube-logomakers/"><u>[Updated] Easy Steps How to Master the Best of 9 Free YouTube Logomakers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-average-earnings-per-view-whats-the-income-for-youtubers-per-ad-playback/"><u>[Updated] In 2024, Average Earnings Per View What's the Income for YouTubers per Ad Playback?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-transform-free-channel-into-a-profitable-venture-with-500plus-subscribers/"><u>2024 Approved Transform Free Channel Into a Profitable Venture - With 500+ Subscribers</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-read-only-barriers-a-windows-users-guide/"><u>Eliminating Read-Only Barriers: A Windows User's Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-virtual-reality-cinema-experiences/"><u>Essential Virtual Reality Cinema Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-default-settings-in-windows-terminal/"><u>Establishing Default Settings in Windows Terminal</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-strategies-for-merging-youtube-music-and-video-content-effectively/"><u>In 2024, Strategies for Merging YouTube Music & Video Content Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-sidestepping-file-explorer-faux-pas/"><u>Mastering the Art: Sidestepping File Explorer Faux Pas</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-the-ultimate-guide/"><u>Mastering Windows Display: The Ultimate Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/mixed-emotions-after-moving-from-windows-10-to-windows-11-the-irreplaceable-features-i-yearn-for/"><u>Mixed Emotions After Moving From Windows 10 to Windows 11: The Irreplaceable Features I Yearn For</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reduce-resource-bottlenecks-on-android-wsl/"><u>Techniques to Reduce Resource Bottlenecks on Android WSL</u></a></li>
<li><a href="https://win11.techidaily.com/the-clearview-guide-nine-solutions-for-fuzzy-window-views/"><u>The ClearView Guide: Nine Solutions for Fuzzy Window Views</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-tools-to-maximize-webp-image-experience/"><u>Top Windows Tools to Maximize WebP Image Experience</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshoot-and-resolve-syntpsys-blue-screen-errors-in-windows-systems/"><u>Troubleshoot and Resolve SYNTP.SYS 'Blue Screen' Errors in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/why-keeping-track-with-wins-11-alerts-matters/"><u>Why Keeping Track With Wins 11 Alerts Matters</u></a></li>
</ul></div>

