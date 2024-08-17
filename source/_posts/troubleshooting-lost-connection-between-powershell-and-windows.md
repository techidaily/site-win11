---
title: "Troubleshooting: Lost Connection Between PowerShell and Windows"
date: 2024-08-15T23:54:04.664Z
updated: 2024-08-16T23:54:04.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Lost Connection Between PowerShell and Windows"
excerpt: "This Article Describes Troubleshooting: Lost Connection Between PowerShell and Windows"
keywords: PowerShell Connect Issue,WinXPsyConnectivity,FixPowerShellLink,RestorePSWindowsLink,RecoverPSConnection,ResolveWinPSLoss,ReestablishPSLinkage
thumbnail: https://thmb.techidaily.com/6ab11e94b8a02777808e732d5f2080be3cb5bc04d41c7f6aa8db8cb93929f141.jpg
---

## Troubleshooting: Lost Connection Between PowerShell and Windows

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see [how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on [how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on [how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.


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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-navigating-the-maze-choosing-the-right-vimeo-membership-plan/"><u>[New] 2024 Approved  Navigating the Maze  Choosing the Right Vimeo Membership Plan</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-prime-desktopmobile-communication-alternatives-to-zoom/"><u>[New] In 2024, Prime Desktop/Mobile Communication Alternatives to Zoom</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-score-big-with-these-8-no-cost-3d-videos-apps-for-windows-and-mac-os/"><u>[New] Score Big with These 8 No-Cost 3D Videos Apps for Windows & Mac OS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-analyzing-youtubes-creator-rewards-regularity/"><u>[Updated] 2024 Approved  Analyzing YouTube's Creator Rewards Regularity</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-the-craft-of-background-image-acquisition/"><u>[Updated] Mastering the Craft of Background Image Acquisition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-comprehensive-blueprint-for-vimeo-video-logging/"><u>[Updated] The Comprehensive Blueprint for Vimeo Video Logging</u></a></li>
<li><a href="https://win11.techidaily.com/4-early-stages-of-pc-failure-know-when-to-act/"><u>4 Early Stages of PC Failure, Know When To Act</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-files-and-directories-in-modern-windows/"><u>Aligning Files & Directories in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-critical-windows-c0000022-bug/"><u>Confronting the Critical Windows C0000022 Bug</u></a></li>
<li><a href="https://fox-that.techidaily.com/dealing-with-restless-noise-changes-in-your-airpods-try-disabling-audio-tracking-technology/"><u>Dealing With Restless Noise Changes In Your AirPods? Try Disabling Audio Tracking Technology</u></a></li>
<li><a href="https://games-able.techidaily.com/electrifying-aspirations-power-and-purpose/"><u>Electrifying Aspirations: Power and Purpose</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-interaction-on-windows-discord-app/"><u>Enhancing Live Interaction on Windows Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-rectifying-confirm-pin-error-in-w11w10-setups/"><u>Guides to Rectifying Confirm PIN Error in W11/W10 Setups</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-error-0xc0000001-efficiently/"><u>How To Tackle Windows Error 0xC0000001 Efficiently</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-on-iphone-8-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 On iPhone 8</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-find-x7-ultra-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo Find X7 Ultra to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-components-for-next-gen-streaming/"><u>In 2024, Premium Components for Next-Gen Streaming</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-14-pro-max-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone 14 Pro Max Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-tune-into-success-with-instagram-soundscapes/"><u>In 2024, Tune Into Success with Instagram Soundscapes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-printer-friendly-presentations-on-windows/"><u>Mastering the Art of Printer-Friendly Presentations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-top-8-troubleshooting-steps/"><u>Mastering Windows: Top 8 Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overmal-restarting-windows-11-software/"><u>Mastery Overmal: Restarting Windows 11 Software</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-silent-windows-headset-mic/"><u>Mending Your Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-permissions-management-in-w11-domains/"><u>Navigating Permissions Management in W11, Domains</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-most-effective-windows-to-do-apps/"><u>Navigating the Most Effective Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/prime-time-performance-top-5-wins-speed-up-solutions/"><u>Prime Time Performance: Top 5 Win's Speed-Up Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/prodigy-preparation-must-haves-from-microsoft-store/"><u>Prodigy Preparation: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-windows-os-issues/"><u>Quick Guide to Resolving Common Windows OS Issues</u></a></li>
<li><a href="https://win11.techidaily.com/rav-antivirus-intrusion-origin-and-removal-guide/"><u>Rav Antivirus Intrusion: Origin & Removal Guide</u></a></li>
<li><a href="https://win11.techidaily.com/redirecting-onedrive-location-in-windows-10/"><u>Redirecting OneDrive Location in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/"><u>Renaissance PC: Refresh with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease!</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-email-banners-in-windows-os/"><u>Solving Disabled Email Banners in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-for-local-admin-credentials-on-windows-11/"><u>Stealth Mode for Local Admin Credentials on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eradicating-system-call-failed-problem-in-windows-11/"><u>Steps for Eradicating System Call Failed Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-upgrade-failure-in-windows-11-error-0x800f0922/"><u>Steps to Fix Upgrade Failure in Windows 11 - Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/the-definitive-guide-on-defeating-windows-11s-0x8007045d-error/"><u>The Definitive Guide on Defeating Windows 11'S 0X8007045D Error</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-file-management-customizing-explorer-comments/"><u>Tips for Efficient File Management: Customizing Explorer Comments</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-vivo-t2-pro-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Vivo T2 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-artistic-freedom-starting-microsoft-paint-on-windows-11/"><u>Unlocking Artistic Freedom: Starting Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-device-discovery-razer-and-windows-11-compatibility/"><u>Unlocking Device Discovery: Razer and Windows 11 Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://win11.techidaily.com/ux3405-vs-macbooks-asuss-oled-showdown/"><u>UX3405 vs MacBooks: Asus's OLED Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
</ul></div>
