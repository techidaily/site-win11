---
title: "Breaking Through Boot Blockers: Top Windows Troubleshooting Steps"
date: 2024-07-29T15:54:02.796Z
updated: 2024-07-30T15:54:02.796Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breaking Through Boot Blockers: Top Windows Troubleshooting Steps"
excerpt: "This Article Describes Breaking Through Boot Blockers: Top Windows Troubleshooting Steps"
keywords: Win Troubleshoot Guide,Boot Error Solving,Overcoming OS Hurdles,Boot Failure Fixes,Resolve Windows Blocks,Boot System Repair,Eliminate Boot Issues
thumbnail: https://thmb.techidaily.com/91e7f02bd957e18d2516616e2ae6cdb5e18d026273686f4e3b0840225091d98b.jpg
---

## Breaking Through Boot Blockers: Top Windows Troubleshooting Steps

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
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
![Secure Boot State in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Secure-Boot-State.jpg)

 If the Secure Boot status is **Off**, you'll have to enable it through your BIOS. To do that, follow the instructions:

1. Open the Settings menu by pressing the Win + I hotkey, and navigate to **System** \> **Recovery.**
2. Click **Restart now** next to **Advanced startup.** It'll restart your computer.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![Restart Now option next to Advanced Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Now-option.jpg)
3. In the Advanced startup mode, choose **Troubleshoot** and then **Advanced options.**
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![System configuration window on desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-configuration-window.jpg)

 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-best-youtube-title-generator/"><u>[New] 2024 Approved  Best YouTube Title Generator</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-definitive-guide-to-android-mobas-10-winners/"><u>[New] 2024 Approved  The Definitive Guide to Android MOBAs  #10 Winners</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-streamline-success-blending-obs-zoom-made-easy/"><u>[New] In 2024, Streamline Success  Blending OBS, Zoom Made Easy</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-the-experts-list-of-tools-for-accelerating-your-facebook-vids/"><u>[Updated] 2024 Approved  The Expert's List of Tools for Accelerating Your Facebook Vids</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-leveraging-windows-11-features-for-top-notch-gaming-capture/"><u>[Updated] In 2024, Leveraging Windows 11 Features for Top-Notch Gaming Capture</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-global-scoreboard-the-premier-six-of-video-downloads/"><u>2024 Approved  Global Scoreboard  The Premier Six of Video Downloads</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-shorts-your-comprehensible-journey-starts-here/"><u>2024 Approved  YouTube Shorts  Your Comprehensible Journey Starts Here</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-power-drain-windows-extender-optimization/"><u>Decreasing Power Drain: Windows Extender Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-guide-windows-obs-not-starting-issue-resolution/"><u>Detailed Guide: Windows OBS Not Starting Issue Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/direct-paths-unveiling-windows-11-calculator/"><u>Direct Paths: Unveiling Windows 11 Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-identifying-high-space-usage-windows/"><u>Effective Strategies for Identifying High-Space Usage Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-integrating-spotlight-images-into-wallpaper/"><u>Elevate Your Workspace: Integrating Spotlight Images Into Wallpaper</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-package-unopenable-error-on-win11-10-oses/"><u>Eliminating the 'Package Unopenable' Error on Win11, 10 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-and-configuring-windows-sandbox-in-win-11/"><u>Enabling and Configuring Windows Sandbox in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-taskbar-clarity-with-w11-tricks/"><u>Enhancing Your Taskbar Clarity with W11 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/expert-methods-purging-directdraw-problems-from-win1011-systems/"><u>Expert Methods: Purging DirectDraw Problems From WIN10/11 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/fine-tuning-focus-a-compreeher-guide-for-videoleap-users/"><u>Fine-Tuning Focus  A Compreeher Guide for Videoleap Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-realme-10t-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Realme 10T 5G FRP Locks</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fundamentals-of-visual-communication-through-motion-for-2024/"><u>Fundamentals of Visual Communication Through Motion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-wmp-playback-issues/"><u>Guide to Overcoming WMP Playback Issues</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-efficiently-manage-amd-drivers-updates/"><u>How to Efficiently Manage AMD Drivers Updates</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-depth-examination-samsung-gear-360-virtual-reality-lens/"><u>In 2024, In-Depth Examination  Samsung Gear 360 Virtual Reality Lens</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-lightning-fast-windows-data-analysis-guide/"><u>In 2024, Lightning-Fast Windows Data Analysis Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/integrating-zoom-into-your-inbox-experience-for-2024/"><u>Integrating Zoom Into Your Inbox Experience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/multitasking-made-simple-windows-1110-window-cascade-guide/"><u>Multitasking Made Simple: Windows 11/10 Window Cascade Guide</u></a></li>
<li><a href="https://win11.techidaily.com/premium-laptops-highlighted-at-ifa-2023/"><u>Premium Laptops Highlighted at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-disconnecting-printers-in-windows/"><u>Quick Fixes for Disconnecting Printers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-addressing-windows-onedrive-errors-and-restoring-folder-integration/"><u>Quick Guide: Addressing Windows OneDrive Errors and Restoring Folder Integration</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-cameras-to-device-manager-display/"><u>Reintroduce Missing Cameras to Device Manager Display</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-0x00000001-restoring-xbox-playability/"><u>Remedy for 0X00000001: Restoring Xbox Playability</u></a></li>
<li><a href="https://screen-recording.techidaily.com/screenscapes-saved-high-quality-online-tv-recordings/"><u>Screenscapes Saved  High-Quality Online TV Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-tasks-using-supercharged-run-tool-in-windows-1011/"><u>Streamline Tasks Using Supercharged Run Tool in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-critical-failures-in-windows-with-error-code-c0000022/"><u>Tackling Critical Failures in Windows with Error Code C0000022</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenient-path-to-iis-manager-entry-point/"><u>The Convenient Path to IIS Manager Entry Point</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-v29-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo V29 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-an-improved-taskbar-on-windows-11/"><u>Tips for an Improved Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-office-overcoming-activation-failures/"><u>Troubleshooting Office: Overcoming Activation Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-efficiency-getting-acquainted-with-window-11s-search-tool/"><u>Unleash Efficiency: Getting Acquainted With Window 11’S Search Tool</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>