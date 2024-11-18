---
title: "Detailed Guide: Managing VM's Secure Boot & TPM on VirtualBox"
date: 2024-11-17T02:06:56.499Z
updated: 2024-11-18T08:03:38.924Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Detailed Guide: Managing VM's Secure Boot & TPM on VirtualBox"
excerpt: "This Article Describes Detailed Guide: Managing VM's Secure Boot & TPM on VirtualBox"
keywords: VirtualBox Secure Boot,VirtualBox TPM Setup,Secure Boot Control,Manage VM TPM,TPM Configuration Guide,VirtualSecure Boot Management,VM Secure Boot Troubleshooting
thumbnail: https://thmb.techidaily.com/499d16f8fa9d73db2896cc95dd1103614d6afb1a8c7743ea30004b41e37daeda.jpg
---

## Detailed Guide: Managing VM's Secure Boot & TPM on VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-examining-the-breadth-of-features-in-obs-studio/"><u>[New] In 2024, Examining the Breadth of Features in OBS Studio</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-perfect-panning-leading-stabilizers-unveiled/"><u>[New] Perfect Panning Leading Stabilizers Unveiled</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-the-art-of-frames-with-top-rated-tools-24/"><u>[Updated] Mastering the Art of Frames with Top-Rated Tools '24</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/apple-wwdc-2025-a-sneak-peek-at-future-technologies-and-tools/"><u>Apple WWDC 2025 – A Sneak Peek at Future Technologies and Tools</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-uninstalling-apps-on-windows-11/"><u>Efficiently Uninstalling Apps on Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/effortlessly-converse-top-17-casual-spanish-utterances/"><u>Effortlessly Converse: Top 17 Casual Spanish Utterances</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-iphone-15-plus-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock iPhone 15 Plus</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-checklist-for-post-editing-and-uploading-your-360-vids-on-youtube/"><u>In 2024, The Ultimate Checklist for Post-Editing & Uploading Your 360 Vids on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-microsoft-store-sign-in-blocks/"><u>Navigate Through Microsoft Store Sign-In Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-task-manager-unresponsiveness/"><u>Overcoming Windows Task Manager Unresponsiveness</u></a></li>
<li><a href="https://win-bytes.techidaily.com/rmvbmp4-movavi/"><u>RMVB到MP4转换精选：最快捷、最简单的教程 | Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows.</u></a></li>
</ul></div>

