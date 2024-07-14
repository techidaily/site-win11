---
title: Bypassing the About To Expire Message on Microsoft OS
date: 2024-07-13T10:53:09.736Z
updated: 2024-07-14T10:53:09.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing the About To Expire Message on Microsoft OS
excerpt: This Article Describes Bypassing the About To Expire Message on Microsoft OS
keywords: Bypass Expiry Alert MSFT,Override MS Windows,Avoid OS EOL Warning,Hide End-of-Life Notice,Skip Expiry Message Windows,Ignore Deprecation Notify,Elude Final Support Msg MS
thumbnail: https://thmb.techidaily.com/0bb0f990e78102071e50c31f7028b725d7f6b1084837b38e9693d564989750d9.jpg
---

## Bypassing the About To Expire Message on Microsoft OS

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unveiling-space-hogs-on-your-windows-hard-drive/"><u>Unveiling Space Hogs on Your Windows Hard Drive</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-microscopic-views-in-microsoft-teams-chat/"><u>In 2024, Mastering the Microscopic Views in Microsoft Teams Chat</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wsl-2-streamline-docker-usage/"><u>Boosting WSL 2: Streamline Docker Usage</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-whisperer-guide-to-win11-menu-hiding/"><u>The Silent Whisperer Guide to Win11 Menu Hiding</u></a></li>
<li><a href="https://win11.techidaily.com/typography-transition-on-windows-multilingual-scripts/"><u>Typography Transition on Windows: Multilingual Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-guide-to-soundcloud-mp3-conversion/"><u>Updated The Ultimate Guide to Soundcloud MP3 Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://extra-support.techidaily.com/secrets-to-selecting-a-premier-cinematographer-for-2024/"><u>Secrets to Selecting a Premier Cinematographer for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80246007-in-windows-11s-update-process/"><u>Tackling Error 0X80246007 in Windows 11'S Update Process</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-best-zero-cost-video-repeater-options/"><u>In 2024, The Best Zero-Cost Video Repeater Options</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beginners-blueprint-for-green-screen-in-kinemaster/"><u>Beginner's Blueprint for Green Screen in KineMaster</u></a></li>
<li><a href="https://win11.techidaily.com/ten-strategies-to-keep-windows-safe-without-bitlocker-support/"><u>Ten Strategies to Keep Windows Safe without Bitlocker Support</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-iis-8-key-steps/"><u>Unlocking IIS: 8 Key Steps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/elevate-your-zoom-experience-syncing-speakers-and-microphones/"><u>Elevate Your Zoom Experience  Syncing Speakers & Microphones</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-save-configuration-errors-in-pubg/"><u>Correcting Save Configuration Errors in PUBG</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-fix-the-green-screen-on-youtube-on-mac/"><u>[Updated] In 2024, How to Fix the Green Screen on YouTube on Mac?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/live-streaming-simplified-with-top-webcam-recorders-for-2024/"><u>Live Streaming Simplified with Top WebCam Recorders for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-some-of-the-top-sites-to-replace-a-sky-background-in-videos/"><u>In 2024, Some of the Top Sites to Replace a Sky Background in Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-phones-speed-up-sound-essential-app-listing/"><u>2024 Approved  Phones’ Speed Up Sound  Essential App Listing</u></a></li>
<li><a href="https://win11.techidaily.com/superior-pc-weather-apps-selection/"><u>Superior PC Weather Apps Selection</u></a></li>
<li><a href="https://win11.techidaily.com/winsecurely-solutions-for-windows-without-bitlocker/"><u>WinSecurely: Solutions for Windows Without Bitlocker</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unleashing-creativity-uploading-movies-from-mmc-to-vimeo/"><u>[Updated] Unleashing Creativity  Uploading Movies From MMC to Vimeo</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How To Simulate GPS Movement With Location Spoofer On Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-veiled-side-of-instagram-stories-what-youre-not-seeing/"><u>2024 Approved  The Veiled Side of Instagram Stories  What You're Not Seeing</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/gamers-masterclass-advanced-recording-tips-unveiled-for-2024/"><u>Gamers' Masterclass  Advanced Recording Tips Unveiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-mediamolder-for-mac/"><u>Updated MediaMolder for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-error-0x80070194-with-onedrive/"><u>Addressing the Error 0X80070194 with OneDrive</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-4k-videos-are-the-in-thing-because-of-their-flexibility-and-high-resolution-stick-around-to-learn-how-to-choose-the-best-frame-rate-for-4k/"><u>New 2024 Approved 4K Videos Are the in Thing because of Their Flexibility and High Resolution. Stick Around to Learn How to Choose the Best Frame Rate for 4K Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/swift-restoration-retrieving-lost-fb-access-for-2024/"><u>Swift Restoration  Retrieving Lost FB Access for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-potential-of-batch-files-via-exes/"><u>Unlock the Potential of Batch Files via EXEs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-mouse-controls-in-win11-effortlessly/"><u>Navigating Mouse Controls in Win11 Effortlessly</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-sound-of-silence-expert-advice-on-noise-reduction-in-final-cut-pro-x/"><u>Updated In 2024, The Sound of Silence Expert Advice on Noise Reduction in Final Cut Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-functional-window-11-menu-bar/"><u>Tackling Non-Functional Window 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-optimal-sound-stripping-applications-windows-and-mac-compatible-revolutionizing-video-enhancement-2024/"><u>Updated Optimal Sound Stripping Applications Windows & Mac Compatible (Revolutionizing Video Enhancement, 2024)</u></a></li>
</ul></div>
