---
title: "Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes"
date: 2024-08-08T13:11:59.457Z
updated: 2024-08-09T13:11:59.457Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes"
excerpt: "This Article Describes Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes"
keywords: Secure Boot Solutions,Booting Without Blocks,Fixing Boot Issues Safely,System Security Enhancement,Boot Process Optimization,Eliminate Boot Errors,Advanced Boot Protection
thumbnail: https://thmb.techidaily.com/4c2f1c5599abfece009f925c2828de86667e5982a128d746578608e8851ede9e.jpg
---

## Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## What Causes the "Secure Boot State Unsupported" Error?

[Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) is a feature of modern computers that uses a digital signature to verify the authenticity of the system's software, especially the operating system's files. It is one of the minimum requirements to install Windows 11\.

 Although you can easily [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/), doing so would adversely affect your computer. You could expect your device to slow down or even crash on a frequent basis.

 Some of the common reasons behind the "Secure Boot state unsupported" error are:

1. You'll likely see the error message if TPM is disabled or not installed on your computer.
2. The error message will appear if Secure Boot is disabled in the BIOS.
3. You'll also encounter the error if BIOS mode is set to Legacy instead of UEFI.

 Now, let's dive into fixes that will help you eliminate the problem.

## 1\. Enable Secure Boot in BIOS

 You must enable Secure Boot in BIOS if you want to install Windows 11 on your computer. But before doing that, view Secure Boot's current state. Here's how to do it:

1. Press the **Win + R** hotkey to open the Run dialog box. Then, type **msinfo32,** and press **Enter**. It'll [open the System information window](https://www.makeuseof.com/windows-open-system-information/).
2. Click **System** **Summary** in the left panel.
3. Check the **Secure Boot State** in the right pane.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

 Restart your computer and check for the problem.

## 3\. Choose UEFI as the BIOS' Mode

 Windows supports two BIOS modes–**UEFI** and **Legacy**. The difference between these two modes is in the process that the firmware uses to locate the boot target.

 You must install Windows using the new UEFI mode as it offers more security features than the Legacy BIOS mode.

 To choose UEFI as the BIOS mode, follow the below steps:

1. Open the BIOS page on your computer.
2. Choose **Boot Sequence** from the left panel.
3. Check the **UEFI option** under **Boot List** Options.  
![UEFI Option in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/UEFI-Option.jpg)
4. Save the changes and restart your computer.

 Again, the process will differ for different manufacturers; therefore, you must check your manufacturer's BIOS page to know how to do it on your computer.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Convert the Partition Style From MBR to GPT

 In modern computers, the boot mode is set to UEFI and has GPT (GUID Partition Style) partition style. However, if your computer is using Legacy Boot mode and MBR (Master Boot Record) partition style, then you will face the problem at hand.

 The solution, in this case, is to convert the partition style from MBR to GPT. But before doing that, you must check your computer partition style. Here's how:

1. Press **Win + X** to open the **Power menu.**
2. Choose **Disk Management.**
3. In the Disk Management window, right-click on the hard disk drive and choose **Properties** from the context menu.  
![Properties option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/properties-option.jpg)
4. Switch to the **Volumes** tab.
5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-free-makers-hub-for-top-tier-fb-visuals/"><u>[New] 2024 Approved  Free Maker's Hub for Top-Tier FB Visuals</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-overcoming-instagrams-video-length-restrictions/"><u>[New] Overcoming Instagram's Video Length Restrictions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harmonic-havens-expert-picks-of-ringtone-download-sites/"><u>[Updated] Harmonic Havens  Expert Picks of Ringtone Download Sites</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-find-youtube-partners-and-make-collab-videos/"><u>[Updated] How to Find YouTube Partners and Make Collab Videos?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-streamlining-your-powerpoint-to-video-journey/"><u>[Updated] In 2024, Streamlining Your PowerPoint to Video Journey</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-precision-planning-the-guide-to-online-collaboration-for-2024/"><u>[Updated] Precision Planning  The Guide to Online Collaboration for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-peepcapture-snapshot-scrutiny-and-choices/"><u>2024 Approved  PeepCapture Snapshot Scrutiny & Choices</u></a></li>
<li><a href="https://games-able.techidaily.com/5-strategies-for-ultimate-ps5-gaming-bliss/"><u>5 Strategies for Ultimate PS5 Gaming Bliss</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-boot-blockers-top-windows-troubleshooting-steps/"><u>Breaking Through Boot Blockers: Top Windows Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-back-into-disconnected-adapters-a-six-step-guide-on-winos/"><u>Breathing Life Back Into Disconnected Adapters: A Six-Step Guide on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-apple-and-windows-calendars-a-comprehensive-guide/"><u>Bridging Apple and Windows Calendars: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-the-seven-timeless-windows-features-of-11/"><u>Bridging Generations: The Seven Timeless Windows Features of 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-worlds-windows-meets-kali-linux/"><u>Bridging Worlds: Windows Meets Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-steam-game-icons-quickly/"><u>Bring Back Missing Steam Game Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forlorn-windows-apps-back-into-use/"><u>Bringing Forlorn Windows Apps Back Into Use</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-windows-up-to-date-key-differences-from-w10-to-w11/"><u>Bringing Windows Up to Date: Key Differences From W10 to W11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-credential-manager-lockup-in-windows/"><u>Bypass Credential Manager Lockup in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-screen-locks-for-uninterrupted-presentations/"><u>Bypass Screen Locks for Uninterrupted Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-while-opening-sound-device-in-audacity-for-windows/"><u>Bypassing Error While Opening Sound Device in Audacity for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-frozen-startup-screen-in-win-lol/"><u>Bypassing Frozen Startup Screen in Win: LOL</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-printer-busy-on-windows-11-systems/"><u>Bypassing Printer Busy on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/changing-the-time-before-next-login-attempt-on-failure/"><u>Changing the Time Before Next Login Attempt on Failure</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-bargains-come-with-hidden-risks-for-windows-users/"><u>Cheap Bargains Come with Hidden Risks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-and-windows-11-the-ultimate-synchronization-guide/"><u>Chromium & Windows 11: The Ultimate Synchronization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-setup-for-windows-11-essential-guide/"><u>Chromium Setup for Windows 11: Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/classic-conundrum-playing-vintage-games-with-dosbox-x/"><u>Classic Conundrum: Playing Vintage Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-steam-game-accomplishments/"><u>Clean Slate for Steam Game Accomplishments</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-experience-unadorned-windows-11/"><u>Clear the Clutter: Experience Unadorned Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-forbidden-errors-in-windows-os/"><u>Clearing Forbidden Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-session-verification-failure-on-your-steam-pc/"><u>Clearing Up Session Verification Failure on Your Steam PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-error-31-restoring-seamless-internet-access/"><u>Clearing Up WIN Error 31: Restoring Seamless Internet Access</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cloud-computing-coverage/"><u>Cloud Computing Coverage</u></a></li>
<li><a href="https://win11.techidaily.com/combat-non-mic-working-on-windows-headsets/"><u>Combat Non-Mic Working on Windows Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/combating-insufficient-usb-controller-support/"><u>Combating Insufficient USB Controller Support</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-how-to-search-filters-on-instagram/"><u>In 2024, How to Search Filters on Instagram</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-minimal-effort-maximum-recovery-for-deleted-posts/"><u>In 2024, Minimal Effort, Maximum Recovery for Deleted Posts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-pros-playbook-mastering-the-art-of-capturing-ps4-gaming/"><u>In 2024, The Pro's Playbook  Mastering the Art of Capturing PS4 Gaming</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-won-t-play-on-samsung-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on Samsung</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-financial-frontier-youtubes-pay-structure-at-the-1m-mark-for-2024/"><u>The Financial Frontier  Youtube's Pay Structure at the 1M Mark for 2024</u></a></li>
</ul></div>
