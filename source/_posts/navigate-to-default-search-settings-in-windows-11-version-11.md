---
title: Navigate to Default Search Settings in Windows 11, Version 11
date: 2024-08-16T00:54:29.149Z
updated: 2024-08-17T00:54:29.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to Default Search Settings in Windows 11, Version 11
excerpt: This Article Describes Navigate to Default Search Settings in Windows 11, Version 11
keywords: Windows 11 Default Search,Setting Window's Default Search,Search Config Window 11,Adjusting Windows 11 Search Settings,Windows Search Default Options,Navigate Win11 Default Searches,Change Default Search in Windows 11
thumbnail: https://thmb.techidaily.com/9b9110ec4a61375e331a8801ee2c3323c1b29e5d640a76c9d9df4c625ff11a27.jpg
---

## Navigate to Default Search Settings in Windows 11, Version 11

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-wirecast-critique-and-comparisons/"><u>[New] 2024 Approved  WireCast Critique & Comparisons</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-discovering-the-ultimate-mobile-photo-experience-ios-11/"><u>[New] Discovering the Ultimate Mobile Photo Experience  IOS 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-eye-catching-thumbnails-select-the-best-fonts/"><u>[New] In 2024, Eye-Catching Thumbnails  Select the Best Fonts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-snapchat-tips-uploading-twitter-videos-for-max-impact-for-2024/"><u>[New] SnapChat Tips  Uploading Twitter Videos for Max Impact for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-ultimate-unboxing-logitechs-professional-4k-pro-webcam/"><u>[Updated] 2024 Approved  Ultimate Unboxing  Logitech's Professional 4K Pro Webcam</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-evaluating-rival-tools-to-superior-sharex/"><u>[Updated] Evaluating Rival Tools to Superior ShareX</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-expert-picks-of-premium-timelapse-capture-software-for-2024/"><u>[Updated] Expert Picks of Premium Timelapse Capture Software for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-leading-non-zoom-remote-work-solutions-for-pc-and-mobile-for-2024/"><u>[Updated] Leading Non-Zoom Remote Work Solutions for PC & Mobile for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-height-final-cut-pro-x-techniques-for-instagram-video/"><u>[Updated] Mastering the Height  Final Cut Pro X Techniques for Instagram Video</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-ultimate-list-8-best-hidden-video-downloader-apps-2023-for-2024/"><u>[Updated] The Ultimate List  8 Best Hidden-Video Downloader Apps, 2023 for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfect-classic-vacation-flicks-top-10-for-summer-fun/"><u>2024 Approved  Perfect Classic Vacation Flicks  Top 10 for Summer Fun</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-top-tunes-palette-for-video-storytelling/"><u>2024 Approved  Top Tunes Palette for Video Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-security-patches/"><u>Demystifying Windows Security Patches</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-infinix-note-30-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Infinix Note 30</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevate-your-fb-video-game-11-winning-strategies-for-2024/"><u>Elevate Your FB Video Game  11 Winning Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-change-installing-and-utilizing-themes-from-the-ms-store/"><u>Embracing Change: Installing and Utilizing Themes From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-programming-with-a-newly-installed-jdk-in-windows-11/"><u>Enhance Your Programming with a Newly Installed JDK in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-winning-video-coders-for-editing/"><u>Expert Tips: Winning Video Coders for Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-virtual-memory-in-windows-11-for-maximum-performance/"><u>Fine-Tuning Virtual Memory in Windows 11 for Maximum Performance</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-adobe-photoshop-in-windows-11-and-11/"><u>Fixing Unresponsive Adobe Photoshop in Windows 11 & 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-forward-to-reverse-mastering-video-reversal-in-final-cut-pro-for-2024/"><u>From Forward to Reverse Mastering Video Reversal in Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-concepts-in-windows-display-idleness/"><u>Fundamental Concepts in Windows Display Idleness</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/googles-ar-sticker-innovation-an-inside-look-and-alternatives-for-2024/"><u>Google's AR Sticker Innovation  An Inside Look & Alternatives for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-preserving-and-reviewing-your-chatgpt-conversations-on-demand/"><u>Guide: Preserving and Reviewing Your ChatGPT Conversations on Demand</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-time-and-date-on-win-11-ui-bar/"><u>Hiding or Showing Time & Date on Win 11 UI Bar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-failed-vms-from-vmware-in-windows-11/"><u>How to Resolve Failed VMs From VMware in Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-officejet-pro-6968/"><u>HP OfficeJet Pro 지도(6968)의 운영자 다ウン로드하기</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-realme-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Realme</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Vivo Y27s? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-oppo-k11x-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Oppo K11x FRP?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-oneplus-nord-ce-3-lite-5g-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your OnePlus Nord CE 3 Lite 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-gaming-with-playnite-and-emulators/"><u>Maximizing Windows Gaming with Playnite and Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/muting-file-explorer-tabs-in-windows-11-guide/"><u>Muting File Explorer Tabs in Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-active-directory-printer-failures/"><u>Navigating and Resolving Active Directory Printer Failures</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-for-rapid-epic-games-access/"><u>Optimizing Windows for Rapid Epic Games Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-store-access-blockades/"><u>Overcoming Microsoft Store Access Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-file-updates-on-windows-error-code-0x80070003/"><u>Quick Fix for Missing File Updates on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-error-262-in-roblox-games/"><u>Quick-Fix Strategies for Error 262 in Roblox Games</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-11s-system-tray-secrets/"><u>Revealing Windows 11'S System Tray Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-sticky-windows-credential-puzzle/"><u>Reversing Sticky Windows Credential Puzzle</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-keys-in-windows-10-and-11-with-7-hacks/"><u>Speeding Up Keys in Windows 10 & 11 with 7 Hacks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/speedy-switching-spree-from-srt-to-txt-files-done-quickly/"><u>Speedy Switching Spree  From SRT to TXT Files Done Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-stuck-scrollbar-and-freezing-pages-in-microsoft-excel-on-windows/"><u>Stop Stuck Scrollbar & Freezing Pages in Microsoft Excel on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-storage-efficiently-identifying-large-disk-users/"><u>Streamline Your Storage: Efficiently Identifying Large Disk Users</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-shortcuts-for-rapid-insertion-of-pre-defined-text-snippets/"><u>Tailored Shortcuts for Rapid Insertion of Pre-Defined Text Snippets</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-windows-11-interface-for-maximum-comfort/"><u>Tailoring Your Windows 11 Interface for Maximum Comfort</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-local-users-and-groups-on-win1110/"><u>The Complete Guide to Local Users and Groups on WIN11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unseen-drives-in-windows/"><u>Troubleshooting: Unseen Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-vac-refusal-on-windows/"><u>Understanding and Rectifying VAC Refusal on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-microsofts-copilot-key-insights-for-windows-11-users/"><u>Unlocking Microsoft's Copilot Key: Insights for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-successful-oculus-installer-on-ws11ws10/"><u>Unlocking Successful Oculus Installer on WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-of-windows-error-0xca00a009/"><u>Unpacking the Mystery of Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-control-panel-customizing-made-simple/"><u>Win11's Control Panel: Customizing Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-custom-shortcut-for-safe-hardware-disconnect/"><u>Windows 11: Custom Shortcut for Safe Hardware Disconnect</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-explore-these-8-great-video-editors/"><u>Windows Users, Explore These 8 Great Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/winstall-workflows-for-smooth-windows-11-app-installation/"><u>Winstall Workflows for Smooth Windows 11 App Installation</u></a></li>
</ul></div>
