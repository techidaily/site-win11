---
title: Boot Security Errors Squashed in 5 Easy Steps for Windows Users
date: 2024-08-08T13:11:45.508Z
updated: 2024-08-09T13:11:45.508Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boot Security Errors Squashed in 5 Easy Steps for Windows Users
excerpt: This Article Describes Boot Security Errors Squashed in 5 Easy Steps for Windows Users
keywords: Windows Boot Security,Booting Steps Secure,Windows Boot Fix Guide,Error-Free Boot Windows,Squash Boot Issues,Windows Boot Tips,Easy Boot Safety
thumbnail: https://thmb.techidaily.com/ec364dbb6168e683e422487379a99c7901eeab42baca05e040ad76d70daee8c3.jpg
---

## Boot Security Errors Squashed in 5 Easy Steps for Windows Users

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

## What Causes the "Secure Boot State Unsupported" Error?

[Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) is a feature of modern computers that uses a digital signature to verify the authenticity of the system's software, especially the operating system's files. It is one of the minimum requirements to install Windows 11\.

 Although you can easily [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/), doing so would adversely affect your computer. You could expect your device to slow down or even crash on a frequent basis.

 Some of the common reasons behind the "Secure Boot state unsupported" error are:

1. You'll likely see the error message if TPM is disabled or not installed on your computer.
2. The error message will appear if Secure Boot is disabled in the BIOS.
3. You'll also encounter the error if BIOS mode is set to Legacy instead of UEFI.

 Now, let's dive into fixes that will help you eliminate the problem.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 1\. Enable Secure Boot in BIOS

 You must enable Secure Boot in BIOS if you want to install Windows 11 on your computer. But before doing that, view Secure Boot's current state. Here's how to do it:

1. Press the **Win + R** hotkey to open the Run dialog box. Then, type **msinfo32,** and press **Enter**. It'll [open the System information window](https://www.makeuseof.com/windows-open-system-information/).
2. Click **System** **Summary** in the left panel.
3. Check the **Secure Boot State** in the right pane.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![Secure Boot State in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Secure-Boot-State.jpg)

 If the Secure Boot status is **Off**, you'll have to enable it through your BIOS. To do that, follow the instructions:

1. Open the Settings menu by pressing the Win + I hotkey, and navigate to **System** \> **Recovery.**
2. Click **Restart now** next to **Advanced startup.** It'll restart your computer.  
![Restart Now option next to Advanced Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Now-option.jpg)
3. In the Advanced startup mode, choose **Troubleshoot** and then **Advanced options.**
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

 Restart your computer and check for the problem.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## 3\. Choose UEFI as the BIOS' Mode

 Windows supports two BIOS modes–**UEFI** and **Legacy**. The difference between these two modes is in the process that the firmware uses to locate the boot target.

 You must install Windows using the new UEFI mode as it offers more security features than the Legacy BIOS mode.

 To choose UEFI as the BIOS mode, follow the below steps:

1. Open the BIOS page on your computer.
2. Choose **Boot Sequence** from the left panel.
3. Check the **UEFI option** under **Boot List** Options.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![UEFI Option in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/UEFI-Option.jpg)
4. Save the changes and restart your computer.

 Again, the process will differ for different manufacturers; therefore, you must check your manufacturer's BIOS page to know how to do it on your computer.

## 4\. Convert the Partition Style From MBR to GPT

 In modern computers, the boot mode is set to UEFI and has GPT (GUID Partition Style) partition style. However, if your computer is using Legacy Boot mode and MBR (Master Boot Record) partition style, then you will face the problem at hand.

 The solution, in this case, is to convert the partition style from MBR to GPT. But before doing that, you must check your computer partition style. Here's how:

1. Press **Win + X** to open the **Power menu.**
2. Choose **Disk Management.**
3. In the Disk Management window, right-click on the hard disk drive and choose **Properties** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![Properties option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/properties-option.jpg)
4. Switch to the **Volumes** tab.
5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

![System configuration window on desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-configuration-window.jpg)

 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-basic-snaps-to-expertly-crafted-images-on-snapchat/"><u>[New] 2024 Approved  From Basic Snaps to Expertly Crafted Images on Snapchat</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-decoding-veiled-content-on-youtube/"><u>[New] In 2024, Decoding Veiled Content on YouTube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/trategies-for-earnings-on-youtube-revealing-minimum-view-targets/"><u>[New] Strategies for Earnings on YouTube  Revealing Minimum View Targets</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-funimate-on-your-phone-unzipping-the-apk-guide/"><u>2024 Approved  Funimate on Your Phone  Unzipping the APK Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-realme-note-50-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/best-camera-stabilizers-for-youtuber-for-2024/"><u>Best Camera Stabilizers for YouTuber for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-slow-windows-excel-with-easy-fixes/"><u>Breathe Life Into Slow Windows-Excel with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-hidden-panes-6-strategies-in-win11/"><u>Breathing Life Into Hidden Panes: 6 Strategies in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-apple-maps-for-windows-operating-system/"><u>Bridging Platforms: Apple Maps for Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-for-a-non-opening-command-prompt-window/"><u>Bridging the Gap for a Non-Opening Command Prompt Window</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-integrating-gmail-with-outlook-app-for-windows/"><u>Bridging the Gap: Integrating Gmail with Outlook App for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-icons-on-windows-11-easily/"><u>Bring Back Missing Icons on Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-dormant-wastebin-icon-in-windows/"><u>Bring Back the Dormant Wastebin Icon in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forlorn-windows-apps-back-into-use/"><u>Bringing Forlorn Windows Apps Back Into Use</u></a></li>
<li><a href="https://win11.techidaily.com/building-python-applications-to-handle-file-operations-in-networks/"><u>Building Python Applications to Handle File Operations in Networks</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-non-genuine-adobe-pop-up-on-pcs/"><u>Bypass Non-Genuine Adobe Pop-Up on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-screen-locks-for-uninterrupted-presentations/"><u>Bypass Screen Locks for Uninterrupted Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-webp-conversion-modifying-images-settings-in-chrome-windows/"><u>Bypass WebP Conversion: Modifying Images Settings in Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-wi-fi-in-windows-11-a-guide-of-8-methods/"><u>Bypassing Limited Wi-Fi in Windows 11: A Guide of 8 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-zero-error-on-windows-11/"><u>Bypassing Microsoft's Zero-Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-printer-busy-on-windows-11-systems/"><u>Bypassing Printer Busy on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/can-pressing-prtscr-open-snipping-tool-how-to-block-it-on-windows-11/"><u>Can Pressing PrtScr Open Snipping Tool? How to Block It on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cease-self-scrolling-in-your-windowed-world/"><u>Cease Self-Scrolling in Your Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-windows-key-consequences-a-warning-list/"><u>Cheap Windows Key Consequences: A Warning List</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-steam-game-accomplishments/"><u>Clean Slate for Steam Game Accomplishments</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-air-solving-microphone-problems-in-microsoft-powered-meet/"><u>Clear the Air: Solving Microphone Problems in Microsoft-Powered Meet</u></a></li>
<li><a href="https://win11.techidaily.com/combat-plan-against-windows-update-setback-code-0x800f080a/"><u>Combat Plan Against Windows Update Setback: Code 0X800f080a</u></a></li>
<li><a href="https://win11.techidaily.com/combating-app-not-uploading-issue-a-guide-to-microsofts-store/"><u>Combating App Not Uploading Issue: A Guide to Microsoft's Store</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signature-for-pdf-file-document-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Free electronic signature for .pdf file document</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-infinix-gt-10-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Infinix GT 10 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-20-pro-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Camon 20 Pro 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-most-advanced-iphone-videography-apps/"><u>In 2024, Most Advanced iPhone Videography Apps</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-complete-gif-makers-manual-for-2024/"><u>The Complete GIF Maker's Manual for 2024</u></a></li>
</ul></div>
