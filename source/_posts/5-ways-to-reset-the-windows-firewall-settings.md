---
title: 5 Ways to Reset the Windows Firewall Settings
date: 2024-07-02T13:03:20.005Z
updated: 2024-07-03T13:03:20.005Z
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
<li><a href="https://win11.techidaily.com/ux3405-vs-macbooks-asuss-oled-showdown/"><u>UX3405 vs MacBooks: Asus's OLED Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-recovering-without-admin-creds/"><u>Mastering Windows 11: Recovering without Admin Creds</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-the-gains-from-dxvk-adoption/"><u>Windows Users - The Gains From DXVK Adoption</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-ip-command-prompt-guide-for-pcs/"><u>Discover Your IP: Command Prompt Guide for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-social-savvy-how-to-save-gifs-for-iphoneandroid-use/"><u>[New] Social Savvy  How to Save GIFs for iPhone/Android Use</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-image-retrieval-on-pexels-a-step-by-step-guide/"><u>[New] Mastering Image Retrieval on Pexels  A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-gopro-tools-for-deep-sea-cinematography/"><u>[Updated] Best Gopro Tools for Deep-Sea Cinematography</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/keeping-memories-afloat-unlimited-free-photo-stash-plus-charged-backups/"><u>Keeping Memories Afloat  Unlimited Free Photo Stash + Charged Backups</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-13-drfone-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-avoid-spending-discover-the-finest-free-mac-screen-recorders/"><u>2024 Approved  Avoid Spending  Discover the Finest Free Mac Screen Recorders</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-mastering-the-art-of-tiktok-intros-on-mac-devices/"><u>In 2024, Mastering the Art of TikTok Intros on Mac Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-prodigys-pathway-expert-techniques-for-iphone-podcast-downloads-for-2024/"><u>The Prodigy's Pathway  Expert Techniques for iPhone Podcast Downloads for 2024</u></a></li>
</ul></div>
