---
title: "Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11"
date: 2024-07-13T11:29:28.221Z
updated: 2024-07-14T11:29:28.221Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11"
excerpt: "This Article Describes Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11"
keywords: Windows 11 Security Tips,Enabling TPM Windows,Securing Windows Boot,Boosting Defense Windows,TPM Steps in Win11,Turn On Secure Boot Win11,TPM Activation Guide Win11
thumbnail: https://thmb.techidaily.com/802df3d91ab6daf6d905273698ce2644dd2e6aa605c087ae0dc1d7ad5065d08f.jpg
---

## Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11

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

### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/avoiding-the-frustration-of-disconnected-discord-setup/"><u>Avoiding the Frustration of Disconnected Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/behind-the-veil-of-user-interface-accessing-windows-hidden-personality-editor/"><u>Behind the Veil of User Interface: Accessing Windows’ Hidden Personality Editor</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-virtual-horizons-with-meaningful-metaverse-sentiments-for-2024/"><u>Exploring Virtual Horizons with Meaningful Metaverse Sentiments for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-disk-capacity-7-affordable-tricks-for-windows-enthusiasts/"><u>Boosting Disk Capacity: 7 Affordable Tricks for Windows Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-opengl-failure-code-3-on-win11/"><u>Addressing NVIDIA OpenGL Failure Code 3 on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-play-40c-bootloader-easily-by-drfone-android/"><u>How to Unlock Honor Play 40C Bootloader Easily</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-launching-your-first-telegram-marketing-campaign/"><u>In 2024, Launching Your First Telegram Marketing Campaign</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-adjusting-immovable-gif-sizes-for-windows-users-of-discord/"><u>Breaking Free: Adjusting Immovable GIF Sizes for Windows Users of Discord</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-gameplay-flush-and-optimize-steam-dns-cache/"><u>Boost Your Gameplay: Flush and Optimize Steam DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/boost-file-navigation-use-box-for-selection-in-win11/"><u>Boost File Navigation: Use Box for Selection in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boot-security-errors-squashed-in-5-easy-steps-for-windows-users/"><u>Boot Security Errors Squashed in 5 Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-isolating-subjects-in-photography/"><u>Advanced Tips for Isolating Subjects in Photography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-future-awaits-elevate-your-fb-chronicles-for-free/"><u>[New] In 2024, The Future Awaits  Elevate Your FB Chronicles for FREE</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-vram-maximizing-graphics-power-on-windows-os/"><u>Boosting VRAM: Maximizing Graphics Power on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-10-and-11s-vital-parts-missing-alert/"><u>Avoiding Windows 10 & 11'S Vital Parts Missing Alert</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/show-off-your-gaming-skills-a-beginners-guide-to-sharing-ps4-screenshots-for-2024/"><u>Show Off Your Gaming Skills A Beginners Guide to Sharing PS4 Screenshots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-customizing-hotkey-behavior/"><u>Boost Productivity: Customizing Hotkey Behavior</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-lgs-smart-tv-leap-discovering-the-bp550-update/"><u>[Updated] LG's Smart TV Leap  Discovering the BP550 Update</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pioneering-tech-in-vr-content-creation/"><u>2024 Approved  Pioneering Tech in VR Content Creation</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-rdc-usability-in-the-latest-os/"><u>Boosting RDC Usability in the Latest OS</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-imovie-for-android-not-exactly-but-these-10-alternatives-come-close/"><u>Updated 2024 Approved IMovie for Android? Not Exactly, But These 10 Alternatives Come Close</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/attraction-tactics-romantic-german-phrases/"><u>Attraction Tactics: Romantic German Phrases</u></a></li>
<li><a href="https://win11.techidaily.com/beware-ais-role-in-win-11-key-generation-missteps/"><u>Beware: AI's Role in Win 11 Key Generation Missteps</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-12-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Xiaomi Redmi 12 won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://win11.techidaily.com/boot-barriers-busted-5-proven-steps-for-secure-boot-fixes/"><u>Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-print-settings-made-easy-a-win11-guide-max-52-chars/"><u>Accessing Print Settings Made Easy: A Win11 Guide (Max 52 Chars)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-infinix-smart-8-hd-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Infinix Smart 8 HD Without PUK Codes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-exploring-the-cricket-soundscape-a-guide-to-field-recording/"><u>2024 Approved Exploring the Cricket Soundscape A Guide to Field Recording</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-pc-how-to-turn-on-hyper-v-in-win11/"><u>Boosting Your PC: How To Turn On Hyper-V in Win11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-scheduling-success-a-step-by-step-approach-to-google-meets/"><u>[Updated] Scheduling Success  A Step-by-Step Approach to Google Meets</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-gold-class-selection-of-unseen-video-extractors/"><u>[New] 2024 Approved  Gold-Class Selection of Unseen Video Extractors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-excels-speed-on-windows-pcs/"><u>Boost Your Excel's Speed on Windows PCs</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-15-free-music-pieces-recommended-for-crafting-memorable-video-narratives-for-2024/"><u>Updated 15 Free Music Pieces Recommended for Crafting Memorable Video Narratives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-file-explorer-performance-on-win-11/"><u>Boosting File Explorer Performance on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-nvidia-cp-in-w11-environments/"><u>Addressing Non-Operational NVidia CP in W11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-top-5-file-management-hacks/"><u>Boost Productivity with These Top 5 File Management Hacks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-digital-room-for-screen-dance-duels/"><u>In 2024, Digital Room for Screen Dance Duels</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-discover-the-art-of-curating-music-on-youtube-with-our-steps/"><u>[New] 2024 Approved  Discover the Art of Curating Music on YouTube with Our Steps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>