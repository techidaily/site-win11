---
title: Secure Windows with These 5 Firewall Adjustments
date: 2024-08-28T00:52:12.513Z
updated: 2024-08-29T00:52:12.513Z
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

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-mastering-the-social-media-puzzle-decoding-ig-data-for-enhanced-campaigns/"><u>[New] 2024 Approved  Mastering the Social Media Puzzle  Decoding IG Data for Enhanced Campaigns</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-effortlessly-journey-to-your-custom-designed-music-library-on-youtube/"><u>[Updated] 2024 Approved  Effortlessly Journey to Your Custom-Designed Music Library on Youtube</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-unlocking-the-code-a-guide-to-your-own-special-tiktok-hash/"><u>[Updated] 2024 Approved  Unlocking the Code  A Guide to Your Own Special TikTok Hash</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-seamlessly-enhancing-content-learn-video-filter-techniques-on-pcmobile/"><u>2024 Approved  Seamlessly Enhancing Content  Learn Video Filter Techniques on PC/Mobile</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-step-by-step-journey-into-professional-gopro-editing-for-2024/"><u>A Step-by-Step Journey Into Professional GoPro Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/curing-windows-error-elusive-startup-items/"><u>Curing Windows Error: Elusive Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-discarding-your-windows-11-trail/"><u>Deciphering and Discarding Your Windows 11 Trail</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-to-enhance-laptop-response-time-post-extended-setup/"><u>Effective Methods to Enhance Laptop Response Time Post-Extended Setup</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-connectivity-with-telnet-ways-3/"><u>Enhance Windows Connectivity with Telnet (Ways 3)</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-airflow-for-windows-11-gadgets/"><u>Enhancing Airflow for Windows 11 Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/essential-to-do-list-software-for-windows-users/"><u>Essential To-Do List Software for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-achieving-a-90-degree-display-flip/"><u>Expert Advice on Achieving a 90-Degree Display Flip</u></a></li>
<li><a href="https://win11.techidaily.com/five-steps-to-wipe-ms-defender-history-on-windows-systems/"><u>Five Steps to Wipe MS Defender History on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/formulating-enduring-file-disposal-strategies-on-windows-systems/"><u>Formulating Enduring File Disposal Strategies on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/get-direct-access-to-processes-in-win11-with-a-search-box/"><u>Get Direct Access to Processes in Win11 with a Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-or-disable-the-windows-installer-service-on-windows/"><u>How to Enable or Disable the Windows Installer Service on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-video-driver-crashed-and-was-reset-error-in-windows-1110/"><u>How to Fix the “Video Driver Crashed and Was Reset” Error in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-file-isnt-playable-error-0xc10100bf-in-windows/"><u>How to Fix the This File Isn’t Playable Error 0Xc10100bf in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-quick-settings-on-windows-11/"><u>How to Use Quick Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-your-operational-window-11-state/"><u>Identifying Your Operational Window 11 State</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-vivo-y27-4g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo Y27 4G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tips-for-non-vid-based-self-education-success/"><u>In 2024, Tips for Non-Vid Based Self-Education Success</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-overhauled-window-for-selecting-widgets-in-win11/"><u>Leveraging Overhauled Window for Selecting Widgets in Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/mix-fold-3-messages-recovery-recover-deleted-messages-from-mix-fold-3-by-fonelab-android-recover-messages/"><u>Mix Fold 3 Messages Recovery - Recover Deleted Messages from Mix Fold 3</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workflow-with-windows-and-sudo-integration/"><u>Optimize Your Workflow with Windows & Sudo Integration</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-wi-fi-woes-enhance-your-windows-apps-connectivity/"><u>Overcome Wi-Fi Woes: Enhance Your Windows Apps' Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-denial-on-windows-11/"><u>Overcoming File Access Denial on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pace-up-tech-locating-gpu-specifications-on-windows-11/"><u>Pace Up Tech: Locating GPU Specifications on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-unlocking-your-os-control-panel/"><u>Quick Access: Unlocking Your OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/quick-method-to-shut-off-windows-11-alerts/"><u>Quick Method to Shut Off Windows 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-color-from-chrome-on-pcs/"><u>Recovering Color From Chrome on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/remedies-for-low-memory-indicators-in-windows-based-vmware/"><u>Remedies for Low Memory Indicators in Windows-Based VmWare</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unselectable-text-in-windows-pdf-viewers/"><u>Resolve Unselectable Text in Windows' PDF Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-0x800700e9-on-xbox-game-pass-in-windows-11/"><u>Resolving 0X800700E9 on Xbox Game Pass in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-usage-metrics-infusing-cpu-and-memory-details-into-systray/"><u>Reveal Usage Metrics: Infusing CPU & Memory Details Into SysTray</u></a></li>
<li><a href="https://win11.techidaily.com/speed-difference-how-to-match-pc-and-android-connectivity/"><u>Speed Difference: How to Match PC and Android Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-power-management-hitch-with-third-party-software/"><u>Steps to Overcome Windows Power Management Hitch with Third-Party Software</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-no-data-usb-devices-in-microsoft-systems/"><u>Strategies for Fixing No-Data USB Devices in Microsoft Systems</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-stuck-easy-fixes-for-w11w10-users/"><u>Synapse Stuck? Easy Fixes for W11/W10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-issue-0x800704b3-in-windows/"><u>Tackling Network Issue 0X800704B3 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-xpatch-problem-error-code-0x80073712/"><u>Tackling XPatch Problem: Error Code 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-through-the-years-in-windows-os/"><u>Taskbar Through the Years in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peaceful-application-management-in-window-11/"><u>The Path to Peaceful Application Management in Window 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-11-breakthroughs-in-technology-since-the-invention-of-morse-code-1844/"><u>Top 11 Breakthroughs in Technology Since the Invention of Morse Code (1844)</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-x7217-at-microsoft-store/"><u>Troubleshooting Error Code X7217 at Microsoft Store</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/uncover-the-solution-what-to-do-when-you-encounter-a-mapp32dll-not-detected-error/"><u>Uncover the Solution: What To Do When You Encounter a 'mapp32.dll Not Detected' Error</u></a></li>
<li><a href="https://win11.techidaily.com/unite-pilot-and-ai-on-windows-11-after-disconnection/"><u>Unite Pilot & AI on Windows 11 After Disconnection</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/when-should-you-share-your-insta-story/"><u>When Should You Share Your Insta Story?</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-influence-on-desktop-linux-landscape-shift/"><u>WSL Influence on Desktop Linux Landscape Shift</u></a></li>
</ul></div>
