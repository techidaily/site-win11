---
title: What to Do When Windows Can't Locate PowerShell Console
date: 2024-07-13T10:22:12.495Z
updated: 2024-07-14T10:22:12.495Z
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

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

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
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-admin-blocked-application-issue/"><u>Troubleshooting Admin-Blocked Application Issue</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-ce-3-lite-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord CE 3 Lite 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-11-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 11 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-lightweightscreencapture-no-fuss-just-fun/"><u>[New] 2024 Approved  LightweightScreenCapture - No Fuss, Just Fun</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlock-your-pcs-potential-exciting-new-windows-10-games/"><u>[Updated] 2024 Approved  Unlock Your PC’s Potential  Exciting New Windows 10 Games</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-y78-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo Y78 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/escape-from-ennui-with-humor-top-20-funny-faces-in-social-media-jail/"><u>Escape From Ennui with Humor  Top 20 Funny Faces in Social Media Jail</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-the-ultimate-mac-video-maker-guide-simplify-your-video-creation/"><u>New The Ultimate Mac Video Maker Guide Simplify Your Video Creation</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-non-operational-wsresetexe-in-windows/"><u>Troubleshooting: Resolving Non-Operational WSReset.exe in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-unveiling-our-exclusive-package-of-free-youtube-adornments/"><u>2024 Approved  Unveiling Our Exclusive Package of Free YouTube Adornments!</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-new-potentials-with-macos-11-big-sur/"><u>Unlocking New Potentials with macOS 11 Big Sur</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-screencaptureelite-the-5-star-apeaksoft-evaluation-for-2024/"><u>[New] ScreenCaptureElite – The 5-Star Apeaksoft Evaluation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/top-5plus-windows-1011-productivity-boosters-for-maximum-output/"><u>Top 5+ Windows 10/11 Productivity Boosters for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-metered-connection-for-wifi-networks-on-win11/"><u>Configuring Metered Connection for Wifi Networks on Win11</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-ultimate-guide-to-selecting-9-superior-streamscape-filters/"><u>[Updated] The Ultimate Guide to Selecting 9 Superior Streamscape Filters</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-captivate-with-voice-intros-that-intrigue/"><u>2024 Approved  Captivate with Voice  Intros That Intrigue</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-proven-methods-for-downloading-multiple-tiktok-videos-for-2024/"><u>[Updated] Proven Methods for Downloading Multiple TikTok Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-methods-to-resolve-error-1-in-games/"><u>Win-Friendly Methods to Resolve Error 1 in Games</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-introducing-effortless-group-image-assembling-via-picshot/"><u>2024 Approved  Introducing Effortless Group Image Assembling via Picshot</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-look-at-adobes-cloud-and-comparable-services/"><u>[New] In-Depth Look at Adobe's Cloud & Comparable Services</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oneplus-11r-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On OnePlus 11R? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-zte-nubia-flip-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on ZTE Nubia Flip 5G</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-best-at-memes-app-version-for-2024/"><u>The Best at Memes (App Version) for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-6-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock On Apple iPhone 6 Online</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-on-apple-iphone-8-plus-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID On Apple iPhone 8 Plus without Password?</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-gionee-f3-pro-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-infinix-hot-30-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Infinix Hot 30 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prime-choices-in-cinema-cameras-from-newbies-to-professionals/"><u>Prime Choices in Cinema Cameras  From Newbies to Professionals</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-the-most-user-friendly-video-editing-apps/"><u>Updated 2024 Approved The Most User-Friendly Video Editing Apps</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-overlooked-windows-extras-a-step-by-step-manual/"><u>Enabling Overlooked Windows Extras: A Step-by-Step Manual</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discounted-artisan-logos-best-free-emblem-tools/"><u>[New] 2024 Approved  Discounted Artisan Logos  Best Free Emblem Tools</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-special-traits-of-ai-machines/"><u>Understanding the Special Traits of AI Machines</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
</ul></div>
