---
title: Navigating Your PC's Firewall Settings with Ease
date: 2024-10-08T22:39:17.643Z
updated: 2024-10-15T22:22:57.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Your PC's Firewall Settings with Ease
excerpt: This Article Describes Navigating Your PC's Firewall Settings with Ease
keywords: PC Firewall Guide,Easy Firewall Navigation,Firewall Control Tips,Secure PC Access,Optimize PC Security,Manage Firewall Settings,Simplify Firewall Use
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## Navigating Your PC's Firewall Settings with Ease

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-transform-your-playtime-mastering-ps4-live-recordings-with-obs/"><u>[New] 2024 Approved Transform Your Playtime Mastering PS4 Live Recordings with OBS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-expert-tips-for-streamlining-mov-recordings-on-win10-for-2024/"><u>[New] Expert Tips for Streamlining MOV Recordings on Win10 for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-mastery-manual-for-dynamic-distracting-filters/"><u>[New] In 2024, Mastery Manual for Dynamic, Distracting Filters</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-art-of-authenticity-financial-fruits-in-filmmaking/"><u>[New] The Art of Authenticity Financial Fruits in Filmmaking</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-stand-out-from-the-noise-logo-design-for-podcast-success/"><u>[Updated] Stand Out From the Noise Logo Design for Podcast Success</u></a></li>
<li><a href="https://win-data.techidaily.com/complete-tutorial-for-reinstating-missing-partitions-in-windows-1011-systems/"><u>Complete Tutorial for Reinstating Missing Partitions in Windows 10/11 Systems</u></a></li>
<li><a href="https://win-able.techidaily.com/dragon-quest-xi-resolving-the-game-crash-problem/"><u>Dragon Quest XI - Resolving the Game Crash Problem</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-windows-search-speed-use-everywhereapp/"><u>Enhanced Windows Search Speed, Use EverywhereApp</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-text-input-integrating-wordpad-shortcuts-with-context-menus-in-windows-11/"><u>Enhancing Text Input: Integrating WordPad Shortcuts with Context Menus in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/exploring-new-gadgets-with-toms-electronics-hub/"><u>Exploring New Gadgets with Tom's Electronics Hub</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-enhancing-fidelity-close-up-minecraft-tactics/"><u>In 2024, Enhancing Fidelity Close-Up Minecraft Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unexpected-system-call-issues-on-windows/"><u>Tackling Unexpected System Call Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-to-overcome-sign-in-problems-on-windows/"><u>Top 8 Methods to Overcome Sign-In Problems on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-vivetool-techniques-for-copilot-setup/"><u>Unveiling ViveTool Techniques for Copilot Setup</u></a></li>
</ul></div>

