---
title: "Proactive Measures for Win 11 Upgrades: Enable TPM, Secure Boot"
date: 2024-11-04T18:03:16.487Z
updated: 2024-11-07T18:42:05.043Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Proactive Measures for Win 11 Upgrades: Enable TPM, Secure Boot"
excerpt: "This Article Describes Proactive Measures for Win 11 Upgrades: Enable TPM, Secure Boot"
keywords: Win 11 Security,Proactive Upgrade,TPM Enablement,Secure Boot Protection,Windows 11 Safety,Patch Management,System Integrity
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Proactive Measures for Win 11 Upgrades: Enable TPM, Secure Boot

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
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-elite-cgi-green-screen-tutorial-for-kinemaster-enthusiasts-for-2024/"><u>[New] Elite CGI Green Screen Tutorial for Kinemaster Enthusiasts for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-list-of-8-best-free-and-paid-movie-apps-for-iphone-for-2024/"><u>[New] List of 8 Best Free and Paid Movie Apps for iPhone for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-complete-playbook-for-team-call-recording-desktopmobile-for-2024/"><u>[New] The Complete Playbook for Team Call Recording (Desktop/Mobile) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-exploring-screenflow-features-a-mac-developers-perspective/"><u>2024 Approved Exploring ScreenFlow Features – A Mac Developer's Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-prime-sites-for-uploading-and-viewing-new-releases-in-telugu-cinema/"><u>Discover the Prime Sites for Uploading & Viewing New Releases in Telugu Cinema</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-analysis-the-evolutionary-escort-ix-a-clever-radar-sensor-for-drivers/"><u>Expert Analysis: The Evolutionary Escort iX, a Clever Radar Sensor for Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/1726028493420-pc/"><u>PC向けビデオからオーディオへの変換ガイド</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-tricks-to-overcome-the-magic-mouses-tracking-issue/"><u>Simple Tricks to Overcome the Magic Mouse's Tracking Issue</u></a></li>
<li><a href="https://ai-video.techidaily.com/stellars-new-wave-in-data-salvage-crafting-a-seamless-interface-for-end-users/"><u>Stellar's New Wave in Data Salvage: Crafting a Seamless Interface for End-Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-tips-accessing-c-span-recordings-without-cost/"><u>Top Tips Accessing C-Span Recordings Without Cost</u></a></li>
<li><a href="https://win11.techidaily.com/44gk6jam44kb44gu44kk44ok44ob44oz44gn6zplusz5aow6yyy6zplusz5qmf6io944gm44gc44kl44oe44o844or/"><u>お薦めのイヤホンで音声録音機能があるツール</u></a></li>
<li><a href="https://win11.techidaily.com/1726029050456-zoom/"><u>スムーズに連続した状態でZOOM動画を編集する専門技術</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    