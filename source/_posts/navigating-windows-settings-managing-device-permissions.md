---
title: "Navigating Windows Settings: Managing Device Permissions"
date: 2024-06-25T11:42:10.015Z
updated: 2024-06-26T11:42:10.015Z
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

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

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

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

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
<li><a href="https://win11.techidaily.com/how-to-manage-windows-user-accounts-via-the-command-prompt/"><u>How to Manage Windows User Accounts via the Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-sie-and-load-unverified-drivers-in-windows/"><u>How to Bypass SIE & Load Unverified Drivers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-file-damaged-message-error-0x80070570-in-windows-oses/"><u>Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hypervisor-bsos-quick-solutions-on-winxose/"><u>Mastering Hypervisor BSOS: Quick Solutions on WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-telnet-activation-on-modern-windows/"><u>Quick Guide to Telnet Activation on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-correction-of-writing-permissions-issue-on-pcs/"><u>Mastering Correction of Writing Permissions Issue on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/1719337024529-get-chrome-back-in-windows-11-quick-recovery-methods/"><u>Get Chrome Back in Windows 11 – Quick Recovery Methods.</u></a></li>
<li><a href="https://win11.techidaily.com/an-effective-guide-to-fix-error-0xc0000001-on-windows-pcs/"><u>An Effective Guide to Fix Error 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-play-every-game-at-home-nba-streaming-made-simple-top-15/"><u>In 2024, Play Every Game at Home  NBA Streaming Made Simple (Top 15)</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-stop-worrying-if-your-adobe-premiere-playback-slows-down-this-guide-will-show-you-the-best-solutions-to-resolve-this-issue-and-a-perfect-alternative/"><u>New Stop Worrying if Your Adobe Premiere Playback Slows Down. This Guide Will Show You the Best Solutions to Resolve This Issue and a Perfect Alternative</u></a></li>
<li><a href="https://extra-tips.techidaily.com/8-top-tier-filters-to-elevate-your-live-feed/"><u>8 Top-Tier Filters to Elevate Your Live Feed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-pro-level-playback-advanced-techniques-for-capturing-minecraft-games-on-mac/"><u>In 2024, Pro-Level Playback  Advanced Techniques for Capturing Minecraft Games on Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-zte-blade-a73-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your ZTE Blade A73 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovating-your-viewing-experience-android-and-vr-videos/"><u>Innovating Your Viewing Experience  Android & VR Videos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/magic-voice-transformation-is-this-app-feasible-discover-other-solutions/"><u>Magic Voice Transformation  Is This App Feasible? Discover Other Solutions</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-from-apple-iphone-6s-plus-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock From Apple iPhone 6s Plus Online</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-samsung-image-maker-insights-and-overview-2023/"><u>[Updated] Samsung Image Maker  Insights & Overview 2023</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo Like A Pro 5 Easy Ways</u></a></li>
</ul></div>
