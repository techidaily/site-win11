---
title: "Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
date: 2024-08-08T13:14:41.602Z
updated: 2024-08-09T13:14:41.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
excerpt: "This Article Describes Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
keywords: VirtualBox TPM Security,Boost VirtualSecureBoot,TPM Control in VirtualBox,Secure Boot Virtualization,Enable Disable TPM (Virtual),Virtual Box TPM Activation,TPM & Secure Boot Settings
thumbnail: https://thmb.techidaily.com/16e517e86ce5511ef20be02a34a06ee211f62f0d8653c2cec4d55484854e4b69.jpg
---

## Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-behind-the-scenes-insights-for-instagram-story-audience/"><u>[Updated] 2024 Approved  Behind the Scenes  Insights for Instagram Story Audience</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unleashing-video-potential-with-effective-tagging-techniques-on-youtube-for-2024/"><u>[Updated] Unleashing Video Potential with Effective Tagging Techniques on YouTube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-techniques-for-stunning-hdr-photography/"><u>2024 Approved  Innovative Techniques for Stunning HDR Photography</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-warrior-spirits-rising-comparable-game-suggestions/"><u>2024 Approved  Warrior Spirits Rising  Comparable Game Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-tell-if-your-pc-needs-restarting/"><u>5 Simple Ways to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-language-of-windows-updates/"><u>Decoding the Language of Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-the-comprehensive-resource-for-w11-enthusiasts/"><u>DevHome: The Comprehensive Resource for W11 Enthusiasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722974464921-download-and-update-lenovo-ideapad-100-drivers-for-windows-11-step-by-step-guide/"><u>Download and Update Lenovo IdeaPad 100 Drivers for Windows 11 - Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://extra-tips.techidaily.com/harness-the-power-of-combining-zoom-with-facebook-live-features/"><u>Harness the Power of Combining Zoom with Facebook Live Features</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-samsung-galaxy-s23-tactical-edition-frp-by-drfone-android/"><u>How Can We Bypass Samsung Galaxy S23 Tactical Edition FRP?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-ipod-and-iphone-12-the-right-way-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock On iPod and iPhone 12 The Right Way</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-top-3-ways-to-use-zoom-video-converter/"><u>In 2024, Top 3 Ways to Use Zoom Video Converter</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/precision-note-taking-adopting-obsidian-written-canvas/"><u>Precision Note-Taking: Adopting Obsidian' Written Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-windows-installer-cpu-spikes/"><u>Reducing Windows Installer CPU Spikes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-lost-link-a-comprehensive-guide-to-reinstating-defective-adapters-in-windows/"><u>Reviving the Lost Link: A Comprehensive Guide to Reinstating Defective Adapters in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/silent-story-consumers-leading-anonymity-apps-for-2024/"><u>Silent Story Consumers  Leading Anonymity Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-network-visibility-in-windows/"><u>Solving Disabled Network Visibility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steering-the-path-of-your-onedrive-file-space-in-windows/"><u>Steering the Path of Your OneDrive File Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-gaming-mastering-the-art-of-fc-mascot/"><u>Step Up Your Gaming: Mastering the Art of FC Mascot</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reopen-nvidia-control-panel-in-win-11/"><u>Steps to Reopen Nvidia Control Panel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-from-crashing-windows-1110/"><u>Steps to Stop Microsoft Teams From Crashing Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcome-ppt-save-blunders-6-quick-fixes-windows-users-need/"><u>Swiftly Overcome PPT Save Blunders: 6 Quick Fixes Windows Users Need</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-unlocked-effective-tpm-deactivation/"><u>Windows 11 Unlocked: Effective TPM Deactivation</u></a></li>
<li><a href="https://win11.techidaily.com/windows-auto-update-shutdown-guide/"><u>Windows Auto-Update Shutdown Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
</ul></div>
