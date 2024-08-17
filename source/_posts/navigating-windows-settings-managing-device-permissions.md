---
title: "Navigating Windows Settings: Managing Device Permissions"
date: 2024-08-15T23:40:07.729Z
updated: 2024-08-16T23:40:07.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Windows Settings: Managing Device Permissions"
excerpt: "This Article Describes Navigating Windows Settings: Managing Device Permissions"
keywords: Windows Privacy Controls,Manage Device Access,System Permission Settings,Navigate Windows Options,Regulate Device Permissions,Security in Windows Settings,Optimize Windows Authorization
thumbnail: https://thmb.techidaily.com/0ad1f89069cff4b2779ade10913206262c7bed58531552359326ac17834a5d8d.jpg
---

## Navigating Windows Settings: Managing Device Permissions

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://extra-lessons.techidaily.com/new-balancing-core-and-supporting-visual-elements/"><u>[New] Balancing Core & Supporting Visual Elements</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-smartphone-photographers-must-have-app-list/"><u>[New] Smartphone Photographers' Must-Have App List</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unveiling-authentic-identity-in-fb-messages/"><u>[New] Unveiling Authentic Identity in FB Messages</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-how-to-fix-blurry-facebook-videos-on-iphoneandroidchrome/"><u>[Updated] 2024 Approved  How to Fix Blurry Facebook Videos on iPhone/Android/Chrome?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-optimizing-discord-stream-quality-with-these-key-steps/"><u>[Updated] 2024 Approved  Optimizing Discord Stream Quality with These Key Steps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-earning-by-critiquing-goodies-a-youtube-guide/"><u>[Updated] Earning by Critiquing Goodies  A YouTube Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-tapestry-translator-looms-screen-recording-guide/"><u>[Updated] The Tapestry Translator  Loom’s Screen Recording Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-from-separation-to-synergy-unite-obs-with-zoom/"><u>2024 Approved  From Separation to Synergy  Unite OBS with Zoom</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimal-storage-solution-for-sony-a7c-cameras/"><u>2024 Approved  Optimal Storage Solution for Sony A7C Cameras</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-superior-guide-to-16-freeware-players-for-pc-and-mac/"><u>2024 Approved  Superior Guide to 16 Freeware Players for PC & Mac</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/analyzing-lack-of-interaction-is-it-a-block-in-2024/"><u>Analyzing Lack of Interaction  Is It a Block, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-life-for-outdated-bios-features/"><u>Breath of Life for Outdated BIOS Features</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-winvpn-fixed-remote-access-errors/"><u>Bridging Gaps in WinVPN: Fixed Remote Access Errors</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-divide-with-winpc-galaxy-flow-link/"><u>Bridging Technology Divide with WinPC-Galaxy Flow Link</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-gaps-syncing-android-plus-windows/"><u>Bridging Technology Gaps: Syncing Android + Windows</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-the-grayed-extend-volume-buttons/"><u>Brighten Up the Grayed Extend Volume Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-vibrancy-to-windows-extended-volume-controls/"><u>Bring Back Vibrancy to Windows’ Extended Volume Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bring-holiday-cheer-with-windows-store-gifts/"><u>Bring Holiday Cheer with Windows Store Gifts</u></a></li>
<li><a href="https://win11.techidaily.com/bring-life-to-monitors-with-custom-spotlight-backdrops/"><u>Bring Life to Monitors with Custom Spotlight Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bring-slack-notifications-back-from-the-dead-in-windows-11/"><u>Bring Slack Notifications Back From the Dead in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-alive-silent-office-outlook-mail-feeds/"><u>Bringing Alive Silent Office Outlook Mail Feeds</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forth-hidden-windows-drive/"><u>Bringing Forth Hidden Windows Drive</u></a></li>
<li><a href="https://win11.techidaily.com/brushes-and-pixels-our-top-7-choices-for-sketching-on-win10/"><u>Brushes and Pixels: Our Top 7 Choices for Sketching on Win10</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-google-chromes-file-transfer-blockade-on-windows/"><u>Bypass Google Chrome's File Transfer Blockade on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-stranded-status-a-quick-guide-for-xbox-users/"><u>Bypassing ‘Stranded’ Status: A Quick Guide for Xbox Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-0x800713f-in-windows-1011s-mail-app/"><u>Bypassing 0X800713F in Windows 10/11'S Mail App</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-connection-issues-0x00000001-resolution-guide/"><u>Bypassing Connection Issues - 0X00000001 Resolution Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-store-crash-code-x800704cf/"><u>Bypassing Microsoft's Store Crash Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-photocapture-failures-on-windows-11-device/"><u>Bypassing PhotoCapture Failures on Windows 11 Device</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windowed-world-exiting-wired-networks-at-100mbps/"><u>Bypassing the Windowed World: Exiting Wired Networks at 100Mbps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11s-operation-failure-error-code-0x0000011b/"><u>Bypassing Windows 11'S Operation Failure (Error Code: 0X0000011B)</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-0x80072af9-solution/"><u>Bypassing Windows Error: 0X80072AF9 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/camouflaging-keyboard-actions-on-windows-platforms/"><u>Camouflaging Keyboard Actions on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/can-pressing-print-screen-start-snip-in-windows-11-block-it/"><u>Can Pressing Print Screen Start Snip in Windows 11? Block It</u></a></li>
<li><a href="https://win11.techidaily.com/changing-default-administrator-in-windows-11-pro/"><u>Changing Default Administrator in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/changing-functionality-of-fn-keys-in-windows-11-pcs/"><u>Changing Functionality of FN Keys in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-and-justifying-your-preferred-video-codecs-on-windows/"><u>Choosing and Justifying Your Preferred Video Codecs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-notification-banishment-for-windows-users/"><u>Chrome Notification Banishment for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/chronos-remedy-restoring-lost-windows-server-time-functionality/"><u>Chronos' Remedy: Restoring Lost Windows Server Time Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigate-windows-s-mode-limitations/"><u>Circumnavigate Windows' S Mode Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-verification-failures-when-downloading-apps/"><u>Circumventing Verification Failures when Downloading Apps</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-windows-restrictions-quickly/"><u>Circumventing Windows Restrictions Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clear-your-script-crisis-essential-solutions-for-windows-errors/"><u>Clear Your Script Crisis: Essential Solutions for Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-cluttered-drives-the-defrag-walkthrough/"><u>Clearing Cluttered Drives: The Defrag Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-black-screen-problem-in-windows-marketplace/"><u>Clearing Up Black Screen Problem in Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-not-written-memory-problems-on-windows/"><u>Clearing Up Not Written Memory Problems on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-conflicting-audio-application-problem-in-windows/"><u>Clearing Up the Conflicting Audio Application Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clipquick-error-nine-easy-steps-for-a-smooth-resume/"><u>ClipQuick Error? Nine Easy Steps for a Smooth Resume</u></a></li>
<li><a href="https://win11.techidaily.com/combat-code-confusion-skyrim-sse-troubleshoot/"><u>Combat Code Confusion: Skyrim SSE Troubleshoot</u></a></li>
<li><a href="https://win11.techidaily.com/combat-strategy-for-fixing-update-errors-in-windows-0xc1900101/"><u>Combat Strategy for Fixing Update Errors in Windows (0xC1900101)</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-strategies-to-prevent-armored-core-n-6-from-crashing-on-pc-a-users-guide-for-stability-during-fires-of-rubicon/"><u>Effective Strategies to Prevent Armored Core N 6 From Crashing on PC - A User's Guide for Stability During Fires of Rubicon</u></a></li>
<li><a href="https://program-issues.techidaily.com/fortnite-launch-glitches-unraveling-and-fixing-entry-point-errors-successfully/"><u>Fortnite Launch Glitches: Unraveling & Fixing Entry Point Errors Successfully</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-vivo-y100-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Vivo Y100 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-lava-blaze-pro-5g-easily-by-drfone-android/"><u>How To Unlock a Lava Blaze Pro 5G Easily?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-vivo-y36i-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Vivo Y36i Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-poco-m6-pro-4g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Poco M6 Pro 4G</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-from-iphone-15-plus-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud from iPhone 15 Plus Safe and Legal</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-xiaomi-redmi-k70-pro-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Xiaomi Redmi K70 Pro Devices</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-sound-creation-utilizing-chatgpt-within-your-digital-audio-workstation/"><u>Mastering Sound Creation: Utilizing ChatGPT Within Your Digital Audio Workstation</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/pioneering-tools-top-5-cloud-based-videography-platforms-for-2024/"><u>Pioneering Tools  Top 5 Cloud-Based Videography Platforms for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/regain-entry-how-to-successfully-reset-and-reclaim-your-snapchat-username/"><u>Regain Entry: How to Successfully Reset and Reclaim Your Snapchat Username</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-hitman-3-stability-issues-on-pc-effective-strategies-for-gamers/"><u>Resolving HITMAN 3 Stability Issues on PC - Effective Strategies for Gamers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-osetupdll-absence-on-your-computer-a-step-by-step-guide/"><u>Resolving osetup.dll Absence on Your Computer: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguarding-professional-confidentiality-tips-for-securely-utilizing-chatgpt-in-the-office/"><u>Safeguarding Professional Confidentiality: Tips for Securely Utilizing ChatGPT in the Office</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-case-for-local-llm-models-benefits-and-drawbacks-examined/"><u>The Case for Local LLM Models – Benefits & Drawbacks Examined</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/total-domination-a-ranking-of-the-7-best-war-based-titans/"><u>Total Domination  A Ranking of the 7 Best War-Based Titans</u></a></li>
</ul></div>
