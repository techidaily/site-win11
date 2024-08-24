---
title: "Windows Control Panel Hacks: USB Access Management"
date: 2024-08-23T06:06:25.633Z
updated: 2024-08-24T06:06:25.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Control Panel Hacks: USB Access Management"
excerpt: "This Article Describes Windows Control Panel Hacks: USB Access Management"
keywords: Windows PC Hubs,USB Manager Tricks,Enhance USB Usage,Control Panel Tweaks,Direct USB Control,Speed USB Functions,Access USB Easily
thumbnail: https://thmb.techidaily.com/8224c2eaffde473b7b29c4172387e354997fe7d2a767ebc186d1a15d8b28408a.jpg
---

## Windows Control Panel Hacks: USB Access Management

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-the-best-makeup-tutorials-on-youtube/"><u>[Updated] 2024 Approved  A Comprehensive Guide to the Best Makeup Tutorials on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-creative-composers-cache-essential-no-cost-afx-tools/"><u>[Updated] In 2024, Creative Composer's Cache  Essential, No-Cost AFX Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-5-essential-strategies-to-avoid-a-dark-screen-during-obs-recordings/"><u>2024 Approved  5 Essential Strategies to Avoid a Dark Screen During OBS Recordings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-download-instagram-vids-effortlessly-on-your-desktop-system-pcmac/"><u>2024 Approved  Download Instagram Vids Effortlessly on Your Desktop System (PC/Mac)</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-strategies-to-remove-dull-backgrounds-from-pictures/"><u>2024 Approved  Strategies to Remove Dull Backgrounds From Pictures</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-user-management-in-windows-cmd/"><u>Comprehensive Guide to User Management in Windows CMD</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-xc0351000-finding-the-absent-hypervisor/"><u>Correcting XC0351000: Finding the Absent Hypervisor</u></a></li>
<li><a href="https://article-tips.techidaily.com/creative-storytelling-vault-for-2024/"><u>Creative Storytelling Vault for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-fixing-charging-problems-with-the-playstation-5-dualsense-controller/"><u>Diagnosing and Fixing Charging Problems with the PlayStation 5 DualSense Controller</u></a></li>
<li><a href="https://fox-access.techidaily.com/economical-drones-reviewed-best-under-a-hundred-bucks/"><u>Economical Drones Reviewed  Best Under a Hundred Bucks</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-batch-execution-with-task-scheduler/"><u>Effortless Batch Execution with Task Scheduler</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-iis-manager-entry/"><u>Essential Tips for IIS Manager Entry</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-skyrocketing-your-cs-gameplay/"><u>Expert Advice on Skyrocketing Your CS Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/from-old-extensions-to-new-ones-the-windows-way/"><u>From Old Extensions to New Ones: The Windows Way</u></a></li>
<li><a href="https://win11.techidaily.com/get-chrome-back-in-windows-11-quick-recovery-methods/"><u>Get Chrome Back in Windows 11 – Quick Recovery Methods</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-oneplus-nord-ce-3-lite-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can OnePlus Nord CE 3 Lite 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-apple-iphone-se-2020-drfone-by-drfone-ios/"><u>How Do You Remove Restricted Mode on Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-iconic-inning-cameo-examination/"><u>In 2024, Iconic Inning - Cameo Examination</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-12-prominent-vivo-v27-pro-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Vivo V27 Pro Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/indulge-in-the-best-pc-experience-with-microsofts-picks/"><u>Indulge in the Best PC Experience with Microsoft's Picks</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-input-concealing-commands-in-windows-11-ui/"><u>Invisible Input: Concealing Commands in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/lockdown-strategies-for-insider-content/"><u>Lockdown Strategies for Insider Content</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-connectivity-issues-for-spotify-on-windows-11/"><u>Mastering Connectivity Issues for Spotify on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-unpredicted-error-messages/"><u>Mastering the Resolution of Unpredicted Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-win11s-cursor-anomalies-a-decades-insight/"><u>Mastering Win11's Cursor Anomalies: A Decade's Insight</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-uninstall-win11-microsoft-store/"><u>Methods to Uninstall Win11 Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-without-automation-time-zone-fixes-for-windows/"><u>Navigate Without Automation: Time Zone Fixes for Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-top-10-video-editing-online-makers-is-worth-your-attention/"><u>New 2024 Approved Top 10 Video Editing Online Makers Is Worth Your Attention</u></a></li>
<li><a href="https://win11.techidaily.com/no-ink-just-notes-best-desktop-notepad-substitutes-on-windows/"><u>No Ink, Just Notes: Best Desktop Notepad Substitutes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-stuck-at-error-e8024002e/"><u>Quick Fixes for Windows Stuck at Error E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-non-functional-windows-11-search-box-in-the-ui/"><u>Reactivating a Non-Functional Windows 11 Search Box in the UI</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-corrupted-files-with-a-faulty-bin-on-windows-11/"><u>Rectifying Corrupted Files with a Faulty Bin on WIndows 11</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-your-desktop-with-dynamic-backgrounds/"><u>Redefining Your Desktop with Dynamic Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inoperative-clipboard-mechanism-win-11/"><u>Resolving Inoperative Clipboard Mechanism Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-steam-games-images-in-windows/"><u>Restoring Lost Steam Games Images in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-standard-plans-for-windows-11-battery-use/"><u>Restoring Standard Plans for Windows 11 Battery Use</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/signs-youre-not-in-someones-contact-list-for-2024/"><u>Signs You're Not in Someone's Contact List for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/six-secrets-to-temporarily-halt-updates-on-your-pc/"><u>Six Secrets to Temporarily Halt Updates on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-windows-voicemail-capture/"><u>Step-by-Step Guide to Windows Voicemail Capture</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-turn-onoff-handwriting-on-windows-pcs/"><u>Step-by-Step Guide: Turn On/Off Handwriting on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-immediate-reopening-of-battlenet-interface/"><u>Strategies for Immediate Reopening of Battle.net Interface</u></a></li>
<li><a href="https://buynow-info.techidaily.com/test-ride-the-simplified-mods-latest-addition-the-sidecar-e-bike/"><u>Test Ride the Simplified Mod's Latest Addition - The Sidecar E-Bike</u></a></li>
<li><a href="https://techidaily.com/the-5-best-methods-to-track-a-lost-or-stolen-iphone-8-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>The 5 Best Methods to Track a Lost or Stolen iPhone 8 | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-pathway-creating-personalized-pin-patterns-on-windows/"><u>The Insider's Pathway: Creating Personalized Pin Patterns on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-enabling-fingerwriting-on-pcs/"><u>The Ultimate Guide: Enabling Fingerwriting on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-resource-roundup-top-free-must-haves-for-win11/"><u>The Ultimate Resource Roundup: Top Free Must-Haves for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/three-approaches-to-test-windows-11-activation/"><u>Three Approaches to Test Windows 11 Activation</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/track-lost-friends-on-instagram-for-2024/"><u>Track Lost Friends on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-disconnected-steam-contacts-w11/"><u>Troubleshooting Disconnected Steam Contacts W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-text-display-error-in-windows-11-resource/"><u>Troubleshooting Text Display Error in Windows 11 Resource</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlocking-creativity-in-youtube-shorts-template-development-for-2024/"><u>Unlocking Creativity in YouTube Shorts Template Development for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-online-how-to-mend-fall-guys-connection-glitches-on-pc/"><u>Winning Back Online: How to Mend Fall Guys Connection Glitches on PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-affiliate-marketing-how-to-make-money-with-it-for-2024/"><u>YouTube Affiliate Marketing  How to Make Money with It for 2024</u></a></li>
</ul></div>
