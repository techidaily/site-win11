---
title: "Ahead of Change: Enabling TPM, Secure Boot for Windows 11"
date: 2024-08-15T23:20:05.125Z
updated: 2024-08-16T23:20:05.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Ahead of Change: Enabling TPM, Secure Boot for Windows 11"
excerpt: "This Article Describes Ahead of Change: Enabling TPM, Secure Boot for Windows 11"
keywords: Win11 TPM Security,SecureBoot Windows 11,TPM Upgrade Pathway,Windows 11 Enhanced Boot,Cybersecurity Win11,Boot Process Modernization,Future PCs Security Standards
thumbnail: https://thmb.techidaily.com/00f9a98dfa9706757d2d82934bc9dc5159ac52a4f0751dc6a02d7459f2560fde.jpg
---

## Ahead of Change: Enabling TPM, Secure Boot for Windows 11

### Quick Links

* [What Are Secure Boot and TPM?](#what-are-secure-boot-and-tpm)
* [How to Enable TPM and Secure Boot](#how-to-enable-tpm-and-secure-boot)
* [Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible](#use-microsoft-39-s-pc-health-check-app-to-check-if-your-hardware-is-compatible)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
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

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-how-to-record-iphoneipads-screen/"><u>[New] 2024 Approved  How to Record iPhone/iPad’s Screen</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-a-comprehensive-guide-to-personalizing-video-images/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Personalizing Video Images</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-understanding-facebook-reels-and-their-production-techniques/"><u>[Updated] In 2024, Understanding Facebook Reels and Their Production Techniques</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-ultimate-vault-explorers-superior-cloud-service-review/"><u>2024 Approved  Ultimate Vault Explorers  Superior Cloud Service Review</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-defective-battery-meter-on-windows-11-devices/"><u>Correcting Defective Battery Meter on Windows 11 Devices</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/cutting-edge-techniques-for-capturing-ps4-games-in-obs-for-2024/"><u>Cutting-Edge Techniques for Capturing PS4 Games in OBS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/devising-schemes-to-skirt-sign-in-requests-in-windows/"><u>Devising Schemes to Skirt Sign-In Requests in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ditch-the-focus-spotlight-icon-on-win11-desktop/"><u>Ditch the Focus: Spotlight Icon on Win11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-accelerated-inputs-for-a-smooth-click-journey/"><u>Eliminating Accelerated Inputs for a Smooth Click Journey</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-file-security-routine-with-powertoys/"><u>Enhancing Your File Security Routine with PowerToys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-techniques-for-windows-10-repair-with-sfc-and-dism-utilities/"><u>Essential Techniques for Windows 10 Repair with SFC & DISM Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-of-windows-glass-hangout-guide/"><u>Essentials of Windows Glass Hangout Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-advanced-possibilities-combining-chatgpt-and-the-wolfram-tool-in-three-ways/"><u>Explore Advanced Possibilities: Combining ChatGPT and the Wolfram Tool in Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-severe-discord-js-error-on-pc-windows-10-and-11-guide/"><u>Fixing Severe Discord JS Error on PC: Windows 10 & 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-setup-failures-windows-10-and-11-edition/"><u>Fixing Windows Setup Failures: Windows 10 & 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-users-through-windows-search-failure-issues/"><u>Guiding Users Through Windows Search Failure Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-microsoft-edge-in-w11-os/"><u>How to Delete Microsoft Edge in W11 OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-honor-x50iplus-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Honor X50i+.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-onedrive-unsuccessful-cloud-issues/"><u>How to Rectify OneDrive Unsuccessful Cloud Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-windows-media-player-in-windows/"><u>How to Start Windows Media Player in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/installation-woes-microsoft-pc-manager-on-windows-xp/"><u>Installation Woes: Microsoft PC Manager on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-window-settings-for-optimal-space-in-win11/"><u>Master the Window Settings for Optimal Space in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-the-exception-has-been-reached-on-pcs/"><u>Mastering Fixes for The Exception Has Been Reached on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/method-reinstate-windows-base-power-plan/"><u>Method: Reinstate Windows Base Power Plan</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-managerial-maze-free-old-championship-soccer-management-guide/"><u>Navigate the Managerial Maze: Free Old Championship Soccer Management Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-display-hiccup-error-code-x0001-geforce/"><u>Overcoming Display Hiccup: Error Code X0001, GeForce</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-disconnect-restarting-your-hotspot-in-windows-11/"><u>Overcoming the Disconnect: Restarting Your Hotspot in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unpreviewed-documents-error-in-office-outlook/"><u>Quick Fixes for Unpreviewed Documents Error in Office Outlook</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Vivo Y17s? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-usability-ai-transformations-in-windows/"><u>Redefining Usability: AI Transformations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-cannot-create-errors-for-files-in-windows/"><u>Remedying 'Cannot Create' Errors for Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-directories-not-empty-error-on-win11-with-0x80070091/"><u>Remedying Directories Not Empty Error on Win11 with #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cloud-sync-failures-windows-10-and-11/"><u>Resolving Cloud Sync Failures: Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-cloud-connection-problems/"><u>Resolving Steam Cloud Connection Problems</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-tab-key-for-seamless-typing/"><u>Reviving a Dormant Tab Key for Seamless Typing</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gameplay-mastery-fixing-frames-drops-in-valorant/"><u>Seamless Gameplay Mastery: Fixing Frames Drops in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/skip-the-haste-disabling-early-edge-tab-activation-in-win11/"><u>Skip the Haste: Disabling Early Edge Tab Activation in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-resurrect-winget-in-windows-os/"><u>Solutions to Resurrect Winget in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-method-to-create-an-automatic-text-transcription-program/"><u>Step-by-Step Method to Create an Automatic Text Transcription Program</u></a></li>
<li><a href="https://win11.techidaily.com/stop-zooming-start-scrolling-essential-mouse-repairs/"><u>Stop Zooming, Start Scrolling: Essential Mouse Repairs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-first-browser-view-in-windows-11/"><u>Tailoring Your First Browser View in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-voice-of-efficiency-unleashing-the-full-potential-of-windows-accessibility-tools/"><u>The Voice of Efficiency: Unleashing the Full Potential of Windows Accessibility Tools</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-tecno-camon-20-pro-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Tecno Camon 20 Pro 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-11-themes-missed-by-many/"><u>Top Windows 11 Themes Missed by Many</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-computer-embracing-the-power-of-16gb/"><u>Upgrading Your Computer: Embracing the Power of 16GB</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-win11-control-panel-settings-locate-missing-keys/"><u>Where Are Win11 Control Panel Settings? Locate Missing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-might-prefer-windows-11-to-apples-macos/"><u>Why You Might Prefer Windows 11 to Apple's macOS</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-display-dimensions-adjustment/"><u>Window's 11 Display Dimensions Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-on-pause-four-simple-steps/"><u>Windows Update on Pause: Four Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/winx-backdrop-blues-solutions-for-a-colorful-ui/"><u>WinX Backdrop Blues: Solutions for a Colorful UI</u></a></li>
</ul></div>
