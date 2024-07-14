---
title: How To Silence the Expiring Window's License Message
date: 2024-07-13T10:44:29.883Z
updated: 2024-07-14T10:44:29.883Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Silence the Expiring Window's License Message
excerpt: This Article Describes How To Silence the Expiring Window's License Message
keywords: Silencing License Error,Windows License Fix,Disable Expiry Alert,Stop License Message,End License Warning,Cease License Popup,Quiet Licensing Reminder
thumbnail: https://thmb.techidaily.com/84fef5f35988a89f310851ba69e27f36f222e4900085b075caa3fb4e05a962a8.jpg
---

## How To Silence the Expiring Window's License Message

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
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://win11.techidaily.com/age-friendly-features-in-pre-windows-10-systems/"><u>Age-Friendly Features in Pre-Windows 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-oneplus-device-sim-by-drfone-android/"><u>Easily Unlock Your OnePlus Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://extra-skills.techidaily.com/is-consumer-feedback-compensated-in-vlogs-in-2024/"><u>Is Consumer Feedback Compensated in Vlogs, In 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-passcode-screen-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 Passcode Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-slovak-online-in-just-10-minutes-a-day/"><u>Learn Slovak Online in Just 10 Minutes a Day</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-ultimate-list-of-online-audio-visualization-software/"><u>Updated In 2024, The Ultimate List of Online Audio Visualization Software</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://article-files.techidaily.com/premiere-selection-of-virtual-gaming-essentials/"><u>Premiere Selection of Virtual Gaming Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-sound-controls-in-windows-os/"><u>Addressing Faulty Sound Controls in Windows OS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-worth-of-sns-hdr-an-in-depth-comparison-study-for-2024/"><u>The Worth of SNS HDR  An In-Depth Comparison Study for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/oad-youtube-videos-anywhere-anytime-free-android-tips/"><u>Download YouTube Videos Anywhere, Anytime  Free Android Tips</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-20-funny-tiktok-jokes-and-riddles-to-make-you-laugh-out/"><u>[Updated] 2024 Approved  20 Funny TikTok Jokes and Riddles to Make You Laugh Out</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-10-moments-that-made-a-mark-on-twitter-and-tiktok/"><u>[Updated] 2024 Approved  10 Moments That Made a Mark on Twitter and TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-efficiency-strategies-for-effective-multitasking-with-windows-11/"><u>Amplify Efficiency: Strategies for Effective Multitasking with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-seamless-video-editing-the-top-software-for-a-hassle-free-experience/"><u>New 2024 Approved Seamless Video Editing The Top Software for a Hassle-Free Experience</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-seamless-media-magic-turning-xml-ssa-into-dynamic-srts-for-2024/"><u>[Updated] The Seamless Media Magic  Turning XML, SSA Into Dynamic SRTs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/download-free-sound-effects-for-youtubers-for-2024/"><u>Download Free Sound Effects for YouTubers for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-vivo-y77t-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Vivo Y77t Black and White | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-apowersoft-picks-unveiling-the-best-for-pc-screen-recorders/"><u>[New] 2024 Approved  Apowersoft Picks  Unveiling the Best for PC Screen Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unleash-your-videos-potential-thriving-in-youtube-rankings/"><u>Unleash Your Video's Potential  Thriving in YouTube Rankings</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-guide-to-automated-iphone-podcast-downloads-for-2024/"><u>Step-By-Step Guide to Automated iPhone Podcast Downloads for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-smart-8-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Smart 8 without backup.</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-zte-blade-a73-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your ZTE Blade A73 5G</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-unleashing-the-power-of-bots-in-discord-servers/"><u>[New] In 2024, Unleashing the Power of Bots in Discord Servers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-maximize-your-reach-best-practices-for-instagram-video-dimensions-and-aspect-ratios/"><u>In 2024, Maximize Your Reach Best Practices for Instagram Video Dimensions and Aspect Ratios</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-transforming-your-twitter-feed-adding-custom-thumbnails-to-videos/"><u>In 2024, Transforming Your Twitter Feed  Adding Custom Thumbnails to Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-art-of-flawless-audio-capture-mic-free-for-2024/"><u>[New] The Art of Flawless Audio Capture, Mic-Free for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-revealing-graphic-excellence-our-top-10-design-tool-list/"><u>In 2024, Revealing Graphic Excellence  Our Top 10 Design Tool List</u></a></li>
</ul></div>
