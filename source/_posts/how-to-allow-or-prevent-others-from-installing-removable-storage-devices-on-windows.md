---
title: How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
date: 2024-09-05T08:26:29.495Z
updated: 2024-09-06T08:26:29.495Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
excerpt: This Article Describes How to Allow or Prevent Others From Installing Removable Storage Devices on Windows
keywords: Permit USB Access,Block Removable USB,USB Device Control,Prevent External Storage,Allow Removable Devices Windows,Disable USB Installation,Secure USB Access Windows
thumbnail: https://thmb.techidaily.com/19529825bc864f6a7105eee056c51264b322fc80a0ff9dab5d25b004c909ef6a.jpg
---

## How to Allow or Prevent Others From Installing Removable Storage Devices on Windows

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-top-choice-for-fb-vids-mp4-download-toolkit/"><u>[New] 2024 Approved  Top Choice for FB Vids – MP4 Download Toolkit</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-clip-weaver-workshop/"><u>[New] Clip Weaver Workshop</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-outro-crafting-made-easy-the-best-free-guide-top-6/"><u>[New] Outro Crafting Made Easy - The Best Free Guide (Top 6)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-command-and-conquer-triumphant-tales-of-the-best-7-total-wars/"><u>[Updated] Command & Conquer  Triumphant Tales of the Best 7 Total Wars</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-oppo-f23-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Oppo F23 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/augmenting-crypto-dialogues-gpts-top-8-integrative-tools-revealed/"><u>Augmenting Crypto Dialogues: GPT's Top 8 Integrative Tools Revealed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combining-windows-partitions-an-expert-guide/"><u>Combining Windows Partitions: An Expert Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/creating-layered-text-the-illustration-expertise-for-2024/"><u>Creating Layered Text  The Illustration Expertise for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-spacing-on-windows-11/"><u>Customizing Taskbar Spacing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-erasing-your-windows-11-actions-trail/"><u>Decoding and Erasing Your Windows 11 Actions Trail</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-effective-email-delivery-feedback-on-windows-machines/"><u>Enabling Effective Email Delivery Feedback on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-custom-pin-lengths-for-windows-users/"><u>Enhance Accessibility: Custom PIN Lengths for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/essential-preparations-what-you-need-prior-to-windows-overhaul/"><u>Essential Preparations: What You Need Prior To Windows Overhaul</u></a></li>
<li><a href="https://win11.techidaily.com/harness-tdarr-to-multiply-windows-pc-video-conversion-efficiency/"><u>Harness Tdarr to Multiply Window's PC Video Conversion Efficiency</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-x7b-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor X7b to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-everything-to-know-about-apple-id-password-requirements-for-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, Everything To Know About Apple ID Password Requirements For iPhone 12 Pro Max</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-optimal-viewing-times-on-instagram-videos/"><u>In 2024, Optimal Viewing Times on Instagram Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-techniques-for-elevating-your-tiktok-unboxing-popularity/"><u>In 2024, Techniques for Elevating Your TikTok Unboxing Popularity</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitters-viral-top-10-all-about-tiktoks/"><u>In 2024, Twitter's Viral Top 10  All About TikToks</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-cli-toolbar-in-windows-11-task-manager/"><u>Integrating CLI Toolbar in Windows 11 Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-printer-support-into-application-guard/"><u>Integrating Printer Support Into Application Guard</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/is-your-iphone-14-pro-max-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>Is Your iPhone 14 Pro Max in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-opening-windows-credential-hideout/"><u>Key to Opening Windows Credential Hideout</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-to-solve-command-not-found-error-in-windows/"><u>Methodology to Solve 'Command Not Found Error' In Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-the-essential-process-of-adding-sound-to-mkv-updated-videographies/"><u>New In 2024, The Essential Process of Adding Sound to MKV-Updated Videographies</u></a></li>
<li><a href="https://win11.techidaily.com/pros-choice-top-video-trimming-apps-for-windows-pcs/"><u>Pro's Choice: Top Video Trimming Apps for Windows PCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/quick-effortless-and-free-red-eye-removal-for-ios-users/"><u>Quick, Effortless, and FREE  Red-Eye Removal for iOS Users</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-6-plus-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 6 Plus Data From iOS iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-errors-in-windows/"><u>Resolving Disk Errors in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/simplifying-the-process-of-designing-fb-social-gatherings/"><u>Simplifying the Process of Designing FB Social Gatherings</u></a></li>
<li><a href="https://win11.techidaily.com/smartly-sorted-7-preferred-windows-photos-apps/"><u>Smartly Sorted: 7 Preferred Windows Photos Apps</u></a></li>
<li><a href="https://win11.techidaily.com/snip-and-sketch-vs-prtsc-the-window-warriors-showdown/"><u>Snip & Sketch Vs. PrtSc: The Window Warriors Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/snooze-button-secrets-for-window-computers/"><u>Snooze Button Secrets for Window Computers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frequent-file-explorer-freezes-in-windows-11/"><u>Solving Frequent File Explorer Freezes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/staying-ahead-insights-into-windows-11s-enhanced-security-updates/"><u>Staying Ahead: Insights Into Windows 11'S Enhanced Security Updates</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-restoration-how-to-get-your-beyond-the-wire-mic-working-again/"><u>Step-by-Step Restoration: How to Get Your Beyond The Wire Mic Working Again</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-ux-a-blueprint-of-essential-taskbar-amendments-in-windows-11/"><u>Streamlining UX: A Blueprint of Essential Taskbar Amendments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-windows-update-eliminating-error-0x800736cc/"><u>Swift Solutions for Windows Update: Eliminating Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/synapse-troubleshoot-restore-functionality-on-windows-devices/"><u>Synapse Troubleshoot: Restore Functionality on Windows Devices</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-f34-5g-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://win11.techidaily.com/top-strategies-for-resolving-minecrafts-win-error-1/"><u>Top Strategies for Resolving Minecraft's Win Error: 1</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-nighttime-paints-dark-aesthetics/"><u>Transition to Nighttime: Paint's Dark Aesthetics</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/uncover-the-secrets-to-quieting-tiktoks-background-noise-simple-tricks-revealed/"><u>Uncover the Secrets to Quieting TikToks Background Noise Simple Tricks Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-the-ultimate-guide-to-windows-powertoy-features/"><u>Unleash Potential: The Ultimate Guide to Windows PowerToy Features</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-bulk-directory-formation-on-windows-10-and-11-systems/"><u>Unlock the Power of Bulk Directory Formation on Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-arp-cache-explained-and-guide-to-clear-it-out/"><u>Windows ARP Cache Explained & Guide to Clear It Out</u></a></li>
<li><a href="https://win11.techidaily.com/winrush-securing-past-command-actions/"><u>WinRush: Securing Past Command Actions</u></a></li>
</ul></div>
