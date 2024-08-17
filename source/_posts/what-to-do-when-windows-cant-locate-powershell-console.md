---
title: What to Do When Windows Can't Locate PowerShell Console
date: 2024-08-16T00:13:36.020Z
updated: 2024-08-17T00:13:36.020Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What to Do When Windows Can't Locate PowerShell Console
excerpt: This Article Describes What to Do When Windows Can't Locate PowerShell Console
keywords: Troubleshooting PowerShell Location,Fixing PS Console Not Found,Resolving PowerShell Inexistence,Enabling PowerShell Visibility,Windows PowerShell Locate Errors,Unlocking PowerShell Accessibility,Correcting PowerShell Display Issues
thumbnail: https://thmb.techidaily.com/d66a628fa0cf48140c10b181f20d8c3673ed432efe3b9eaa0c987c81fd05af8c.jpg
---

## What to Do When Windows Can't Locate PowerShell Console

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
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

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

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 Sign in with your newly created account, and see if Windows can find PowerShell now.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-zero.techidaily.com/our-ultimate-cheat-sheet-for-seamlessly-looping-videos-on-youtube-for-2024/"><u>[New] Your Ultimate Cheat Sheet for Seamlessly Looping Videos on YouTube for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-a-gamers-guide-to-high-quality-gameplay-recordings-on-ps4/"><u>[Updated] A Gamer's Guide to High-Quality Gameplay Recordings on PS4</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-picsart-guide-discreetly-mask-faces/"><u>[Updated] Picsart Guide  Discreetly Mask Faces</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unveiling-the-seven-best-youtube-live-streaming-tools-for-iphoneandroid-for-2024/"><u>[Updated] Unveiling  The Seven Best YouTube Live Streaming Tools for iPhone/Android for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/11-superior-sound-recording-tools-of-the-year-for-2024/"><u>11 Superior Sound Recording Tools of the Year for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-easy-ways-to-merge-igtv-and-instagram-stories/"><u>2024 Approved  Easy Ways to Merge IGTV & Instagram Stories</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-the-leading-live-church-broadcast-services/"><u>2024 Approved  Navigating the Leading Live Church Broadcast Services</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-future-is-now-equip-yourself-with-these-7-devices/"><u>2024 Approved  The Future Is Now - Equip Yourself with These 7 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now!</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wacatacbml-understanding-and-neutralizing-threats-on-windows/"><u>Breaking Down Wacatac.B!ml: Understanding and Neutralizing Threats on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/converting-from-pin-to-password-a-windows-11-users-guide-for-enhanced-security/"><u>Converting From PIN to Password: A Windows 11 User's Guide for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-code-0xa00f425d-in-windows-1e11-camera/"><u>Correcting Error Code: 0XA00F425D in Windows 1E11 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winrars-summation-oversights-a-6-step-approach/"><u>Correcting WinRAR's Summation Oversights: A 6-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/digital-diaries-7-excelent-notetakers-for-pcs-and-slate/"><u>Digital Diaries: 7 Excelent Notetakers for PCs & Slate</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/edit-videos-like-a-pro-on-mac-with-mkvtoolnix/"><u>Edit Videos Like a Pro on Mac with MKVtoolnix</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-user-sign-in-after-windows-authentication-issues/"><u>Enabling User Sign-In After Windows Authentication Issues</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-root-user-access-in-the-windows-terminal/"><u>Ensuring Root User Access in the Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-syncing-your-phone-with-windows-11-via-unison/"><u>Expert Tips: Syncing Your Phone with Windows 11 via Unison</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-restoring-erased-data-in-a-microsoft-world/"><u>Expertly Restoring Erased Data in a Microsoft World</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-critical-winerror-upgrade-fault-0xc004f050/"><u>Fixing Critical WinError: Upgrade Fault #0XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/flush-your-steam-dns-data-a-windows-user-guide/"><u>Flush Your Steam DNS Data - A Windows User Guide</u></a></li>
<li><a href="https://win11.techidaily.com/from-concept-to-reality-paving-new-ways-in-windows-11-widgets/"><u>From Concept to Reality: Paving New Ways in Windows 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-invalid-label-error-on-windows-11/"><u>Guide to Rectify 'Invalid Label' Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-cutting-through-content-clutter-youtube-shorts-essentials/"><u>In 2024, Cutting Through Content Clutter  YouTube Shorts Essentials</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-nokia-g22-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Nokia G22 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-optimal-youtube-playback-adjusting-speed-settings/"><u>In 2024, Optimal YouTube Playback  Adjusting Speed Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-samsung-galaxy-s23-ultra-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Samsung Galaxy S23 Ultra Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-nullifying-windows-11s-eyes-on-you/"><u>Mastery in Nullifying Windows 11'S Eyes on You</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-windows-system-preferences-to-adjust-after-dark-mode/"><u>Mastery of Windows System Preferences to Adjust After Dark Mode</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/monetizing-your-channel-youtube-income-explained/"><u>Monetizing Your Channel  YouTube Income Explained</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-inbox-and-calendar-use-custom-images/"><u>Overhaul Your Inbox and Calendar: Use Custom Images</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Xiaomi Civi 3? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-large-group-renames-with-powertoys/"><u>Simplify Large Group Renames with PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-accurate-game-detection-failure-in-discord-windows-pc/"><u>Solutions for Accurate Game Detection Failure in Discord (Windows PC)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-embedding-app-shortcuts-in-windows-11/"><u>Step-by-Step Guide to Embedding App Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-turning-on-copy-and-paste-operations-in-edges-security-shield-w11/"><u>Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-extended-monitor-lag-in-windows/"><u>Strategies to Combat Extended Monitor Lag in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-cannot-end-task-on-your-computer/"><u>Tackling 'Cannot End Task' On Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-gamer-strategic-play-and-success-at-zero-cost/"><u>Unleash Your Inner Gamer: Strategic Play & Success at Zero-Cost</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
</ul></div>
