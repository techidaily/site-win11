---
title: "Strengthen Your System: Activating TPM & Secure Boot Prior to W11 Upgrade"
date: 2024-10-10T17:58:56.073Z
updated: 2024-10-15T20:59:34.446Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Strengthen Your System: Activating TPM & Secure Boot Prior to W11 Upgrade"
excerpt: "This Article Describes Strengthen Your System: Activating TPM & Secure Boot Prior to W11 Upgrade"
keywords: Windows 11 Security Update,TPM Activation Steps,Enable Secure Boot,W11 System Prep Guide,TPM Configuration Boost,Upgrade to W11 Safely,Boosting System Resilience
thumbnail: https://thmb.techidaily.com/177db7c45381f8f94f304fef5764a3ae21d49762f0d50b119bc79b8987d4ee6b.jpg
---

## Strengthen Your System: Activating TPM & Secure Boot Prior to W11 Upgrade

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [What Are Secure Boot and TPM?](#what-are-secure-boot-and-tpm)
* [How to Enable TPM and Secure Boot](#how-to-enable-tpm-and-secure-boot)
* [Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible](#use-microsoft-39-s-pc-health-check-app-to-check-if-your-hardware-is-compatible)

### Key Takeaways

* Windows 11 requires specific hardware, including AMD Ryzen 3000 series or Intel 7th Gen CPU or better, TPM, and Secure Boot.
* TPM is a hardware-level security solution that protects data from hacking, while Secure Boot prevents unauthorized operating systems from booting up.
* You can enable TPM and Secure Boot in your BIOS/UEFI settings, but be aware that Secure Boot may prevent dual-booting and updates on unsupported hardware.

 Considering upgrading to Windows 11? There are a couple of requirements that might stop you in your tracks. We'll explain how to know if your hardware will pass Windows 11's checks.

 First up is your physical hardware. If you're not using an AMD Ryzen 3000 series or Intel 7th Gen CPU or better, neither a clean Windows 11 installation nor the Windows 10 upgrade path will work. Second, if your computer doesn't support Secure Boot and TPM, you'll also fall at the initial hurdle. However, all is not lost because you can switch on Secure Boot and TPM from your BIOS/UEFI menu.

## What Are Secure Boot and TPM?

 The [Trusted Module Platform (TPM) is a hardware-level security solution](http://www.makeuseof.com/what-is-a-trusted-platform-module-tpm/) that protects your data from hacking and other data breaches. The TPM holds unique encryption keys stored in such a way that it is nearly impossible for a hacker to access. If someone breaches your computer and your data is encrypted, it will remain secure.

 Microsoft's recommended requirements for Windows 11 list TMP 2.0\. However, you can still upgrade using a previous version, TPM 1.2, which is the minimum requirement.

 Along with TPM 2.0, Microsoft also requires you to activate Secure Boot, a UEFI-level security setting that stops any unauthorized operating system from booting up. Secure Boot is effectively a gatekeeper, stopping malicious code from booting up before your system, and its primary goal is to protect against rootkits, bootkits, and other malicious code.

![windows bios secure boot warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/windows-bios-secure-boot-warning.jpg)

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-soundscapes-for-vimeo-a-compreayers-manual-for-2024/"><u>[New] Soundscapes for Vimeo A Compreayer's Manual for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-audio-alerts-high-quality-pages/"><u>[New] Ultimate Audio Alerts High-Quality Pages</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-sightgallery-review-system/"><u>[Updated] 2024 Approved SightGallery Review System</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-free-cam-screen-recorder-review-and-best-alternatives-for-2024/"><u>[Updated] Free Cam Screen Recorder Review and Best Alternatives for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-the-future-is-now-how-vida-transforms-video-editing/"><u>[Updated] In 2024, The Future Is Now How Vida Transforms Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-the-ultimate-gaming-experience-with-amd-tweaks/"><u>Crafting the Ultimate Gaming Experience with AMD Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-options-performance-metrics/"><u>Deciphering Windows N Options: Performance Metrics</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-connection-methods-for-ps-vr-and-your-desktop-system/"><u>Easy Connection Methods for PS VR and Your Desktop System</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-dolby-atmos-malfunctions-for-a-smooth-experience-on-windows-platforms-11-and-10/"><u>Fixing Dolby Atmos Malfunctions for a Smooth Experience on Windows Platforms (11 & 10)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-filter-processes-and-set-a-new-theme-in-the-windows-11-task-manager/"><u>How to Filter Processes and Set a New Theme in the Windows 11 Task Manager</u></a></li>
<li><a href="https://fox-metric.techidaily.com/leading-software-solutions-for-instantaneous-change-detection-and-file-syncing/"><u>Leading Software Solutions for Instantaneous Change Detection and File Syncing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/lock-your-lava-yuva-3-pro-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Lava Yuva 3 Pro Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-failure-resolve-error-0xc0000001-on-win1011/"><u>Overcoming System Failure: Resolve Error 0xC0000001 on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-user-profile-issues-on-windows-1111-system/"><u>Resolving User Profile Issues on Windows 11/11 System</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-admin-unblocking-disabled-apps/"><u>Solving Windows Admin: Unblocking Disabled Apps</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-route-to-integrating-apple-events-in-windows-11/"><u>The Ultimate Route to Integrating Apple Events in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-avoid-adobe-genuineness-error/"><u>Tips to Avoid Adobe Genuineness Error</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    