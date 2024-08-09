---
title: How to Delete Microsoft Edge in W11 OS
date: 2024-08-08T13:19:56.487Z
updated: 2024-08-09T13:19:56.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Delete Microsoft Edge in W11 OS
excerpt: This Article Describes How to Delete Microsoft Edge in W11 OS
keywords: Delete Microsoft Edge W11,Remove Edge Browser W11,Uninstall Edge W11,Wipe Microsoft Edge,Disable Edge W11,Turn Off Edge OS W11,Clear Microsoft Edge W11
thumbnail: https://thmb.techidaily.com/56f4900e7c7d867bb901f7b64e907d973f9debc0b4d9e6ff3cf0e83ec62a7ce4.jpg
---

## How to Delete Microsoft Edge in W11 OS

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://youtube-data.techidaily.com/024-approved-access-your-favorites-anytime-the-leading-6-free-video-downloaders/"><u>[New] 2024 Approved  Access Your Favorites Anytime  The Leading 6 Free Video Downloaders</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-daily-digest-downloader/"><u>[Updated] 2024 Approved  Daily Digest Downloader</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-meetings-to-media-how-zoom-powers-fb-live-content/"><u>[Updated] From Meetings to Media  How Zoom Powers FB Live Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-optimal-video-recording-for-instructors/"><u>[Updated] Optimal Video-Recording for Instructors</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://facebook.techidaily.com/breathe-life-back-into-vanished-facebook-interactions/"><u>Breathe Life Back Into Vanished Facebook Interactions</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-bricked-windows-update-fix/"><u>Bypassing a Bricked Windows Update Fix</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://extra-tips.techidaily.com/create-unique-instagram-ringtone-at-home-for-2024/"><u>Create Unique Instagram Ringtone at Home for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-linux-software-best-choices-for-snaps-and-shots-for-2024/"><u>Essential Linux Software  Best Choices for Snaps & Shots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-effective-batch-conversion-of-heic-to-jpeg-in-windows/"><u>Expert Tips for Effective Batch Conversion of HEIC to JPEG in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-open-issues-windows-11s-mail-and-calendar-hiccup/"><u>Fixing Open Issues: Windows 11'S Mail & Calendar Hiccup</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-oppo-reno-11f-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-video-buffer-issues-streamlined-vlc-on-pc/"><u>Fixing Video Buffer Issues: Streamlined VLC on PC</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-infinix-smart-7-hd-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reestablish-network-connection-after-failure-in-windows-11/"><u>How to Reestablish Network Connection After Failure in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-recovered-excel-file-that-wont-open-stellar-by-stellar-guide/"><u>How to repair recovered Excel file that wont open | Stellar</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/keeping-content-copyright-compliant-with-instra-watermarking-for-2024/"><u>Keeping Content Copyright-Compliant with Instra Watermarking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-fixes-in-windows-10-and-11/"><u>Mastering DirectDraw Fixes in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-for-a-macos-feel-in-windows/"><u>Mastering Window Customization for a macOS Feel in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-administrator-settings-in-windows-security/"><u>Navigating Administrator Settings in Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-previous-windows-configurations/"><u>Quick Guide to Restoring Previous Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-over-silent-slack-alerts-in-win-11/"><u>Regain Control Over Silent Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-no-connection-found-on-win-810/"><u>Remedying No Connection Found on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vmware-freeze-up-in-windows-11/"><u>Resolving VMware Freeze-Up in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-microsofts-speech-recognition-in-windows-11/"><u>Restoring Microsoft's Speech Recognition in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-snaps-windows-strategies-for-sticky-notes/"><u>Secure Your Snaps: Windows Strategies for Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-alternative-pdf-printer-in-windows/"><u>Setting Alternative PDF Printer in Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/step-into-better-imaging-with-these-gopro-extras-for-2024/"><u>Step Into Better Imaging with These GoPro Extras for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/strategic-hashtag-application-for-greater-instagram-traction/"><u>Strategic Hashtag Application for Greater Instagram Traction</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-faulty-microsoft-store-eradicate-0x80072efd/"><u>Tackling Faulty Microsoft Store: Eradicate 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-androidpc-junctioning/"><u>The Ultimate Guide to Android/PC Junctioning</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-the-dbghelpdll-not-detected-a-comprehensive-guide/"><u>Troubleshooting the 'dBghelp.dll' Not Detected - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-shouldnt-use-ai-chatbots-to-generate-windows-11-keys/"><u>Why You Shouldn’t Use AI Chatbots to Generate Windows 11 Keys</u></a></li>
</ul></div>
