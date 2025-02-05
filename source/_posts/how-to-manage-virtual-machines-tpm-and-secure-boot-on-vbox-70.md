---
title: How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
date: 2025-02-03T09:15:02.674Z
updated: 2025-02-03T22:36:29.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
excerpt: This Article Describes How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
keywords: VM TPM Control,Secure Boot VBOX,VBox 7.0 Security,TPM Management in VBox,Enable Secure Boot (VBOX),VBox TPM Guide,Virtual Secure Boot Setup
thumbnail: https://thmb.techidaily.com/30c580f4aaa4373c8a4d05322fd912eb007bcd184d7b7f33639176575d3c4909.jpg
---

## How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.

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
<li><a href="https://extra-resources.techidaily.com/new-beats-and-brilliance-creating-soundtracked-instagram-feeds/"><u>[New] Beats & Brilliance Creating Soundtracked Instagram Feeds</u></a></li>
<li><a href="https://article-files.techidaily.com/new-expertly-charged-hero5-black-batteries-authenticity-and-counterparts/"><u>[New] Expertly Charged Hero5 Black Batteries - Authenticity & Counterparts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-slack-vs-discord-selecting-teams-ideal-chat-platform/"><u>[New] Slack Vs. Discord Selecting Teams' Ideal Chat Platform</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/tep-by-step-process-of-amplifying-your-channel-with-high-impact-placement-for-2024/"><u>[New] Step-by-Step Process of Amplifying Your Channel with High-Impact Placement for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-elevate-your-audio-curated-list-of-top-mac-friendly-recorders/"><u>[Updated] In 2024, Elevate Your Audio Curated List of Top Mac-Friendly Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-directories-3-windows-routes-for-games/"><u>Deciphering Directories: 3 Windows Routes for Games</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-virtual-memory-on-windows-11/"><u>How to Reset Virtual Memory on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-bluetooth-device-usage-focus-on-sound-outputs-alone/"><u>Maximizing Windows Bluetooth Device Usage - Focus on Sound Outputs Alone</u></a></li>
<li><a href="https://discover-help.techidaily.com/1726029415959-pc4/"><u>PC内で利用可能な4つの無料オーディオレコーダー:最高推薦品</u></a></li>
<li><a href="https://win11.techidaily.com/quieten-windows-acoustic-overlays/"><u>Quieten Windows' Acoustic Overlays</u></a></li>
<li><a href="https://win11.techidaily.com/stylish-screens-diverse-decor-wallpaper-wonder-for-windows-11/"><u>Stylish Screens, Diverse Decor: Wallpaper Wonder for Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/to-ai-or-not-to-ai-financial-wisdom-from-computers/"><u>To AI or Not to AI? Financial Wisdom From Computers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-hugs-chat-the-open-source-twin-to-chatgpts-world/"><u>What Hugs Chat? - The Open Source Twin to ChatGPT's World</u></a></li>
</ul></div>

