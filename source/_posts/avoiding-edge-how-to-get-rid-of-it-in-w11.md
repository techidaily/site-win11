---
title: "Avoiding Edge: How to Get Rid of It in W11"
date: 2024-08-15T23:18:21.608Z
updated: 2024-08-16T23:18:21.608Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoiding Edge: How to Get Rid of It in W11"
excerpt: "This Article Describes Avoiding Edge: How to Get Rid of It in W11"
keywords: W11 Edge Removal Guide,Eliminate W11 Edges,W11 Without Edges,Fit Exactly, No Edges,Pure Windows Experience W11,No-Edge W11 Tips,Complete W11 Interface
thumbnail: https://thmb.techidaily.com/5599db5b0351dfe7fe4d3ef01a51b823176684e86c63c43fb2d60eaab80af0aa.jpg
---

## Avoiding Edge: How to Get Rid of It in W11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
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

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to [edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://some-techniques.techidaily.com/new-improve-mobile-video-clarity-iphone-tips/"><u>[New] Improve Mobile Video Clarity  IPhone Tips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-execute-a-budget-friendly-youtube-seminar/"><u>[New] In 2024, How to Execute a Budget-Friendly Youtube Seminar</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-co-singers-capturing-hearts-online/"><u>[Updated] Co-Singers Capturing Hearts Online</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-rapid-routines-for-capturing-video-calls/"><u>[Updated] In 2024, Rapid Routines for Capturing Video Calls</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-speed-it-up-crafting-beautiful-timelapse-videos-on-galaxy/"><u>[Updated] Speed It Up  Crafting Beautiful Timelapse Videos on Galaxy</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-understanding-and-implementing-audio-ebb-in-premiere-pro/"><u>[Updated] Understanding and Implementing Audio Ebb in Premiere Pro</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-voice-personalization-tips-for-instagram-users-for-2024/"><u>[Updated] Voice Personalization Tips for Instagram Users for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-90-funniest-2-minute-tiktoks-ever/"><u>2024 Approved  90 Funniest 2-Minute TikToks Ever</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expertly-edit-extravagant-tiktoks-your-key-to-less-overloaded-drafts/"><u>2024 Approved  Expertly Edit Extravagant TikToks  Your Key to Less Overloaded Drafts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-mastering-high-dynamic-range-with-image-curving/"><u>2024 Approved  Mastering High Dynamic Range with Image Curving</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-microscreenmugger-assessment-report/"><u>2024 Approved  MicroScreenMugger Assessment Report</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-no-cost-mac-os-screen-tracker/"><u>2024 Approved  No-Cost Mac OS Screen Tracker</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-organizing-your-iphones-picture-collection-from-sorting-to-icloud-backing-up/"><u>2024 Approved  Organizing Your iPhone's Picture Collection  From Sorting to iCloud Backing Up</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-step-by-step-mastering-ppros-full-screen-preview/"><u>2024 Approved  Step-by-Step  Mastering PPro's Full Screen Preview</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-restore-your-usb-wi-fi-on-a-pc/"><u>7 Key Steps to Restore Your USB Wi-Fi On a PC</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-backing-up-and-restoring-notebooks/"><u>A Practical Approach: Backing Up & Restoring Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/a-walkthrough-for-transferring-old-games-to-windows-gallery/"><u>A Walkthrough for Transferring Old Games to Windows Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-software-instability-in-windows-store-purchases/"><u>Addressing Software Instability in Windows Store Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-10-and-11s-0x0000011b-faults/"><u>Addressing Windows 10 & 11'S 0X0000011B Faults</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-the-veiled-query-power-in-windows-11/"><u>Awakening the Veiled Query Power in Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/busting-through-the-ice-age-solutions-for-persistent-loading-issues-in-cold-war-scenarios-on-pcconsole/"><u>Busting Through the Ice Age: Solutions for Persistent Loading Issues in Cold War Scenarios on PC/Console</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-windows-11s-integrity-quick-checks/"><u>Confirming Windows 11'S Integrity: Quick Checks</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-group-policy-intricacies-through-gpresult/"><u>Deciphering Group Policy Intricacies Through GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-unveiled-a-deep-dive-into-w11s-core/"><u>DevHome Unveiled: A Deep Dive Into W11's Core</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-windows-steam-speed-eliminating-zero-downloads/"><u>Elevate Windows Steam Speed: Eliminating Zero-Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-energy-visibility-personalized-notifications-for-fully-charged-batteries-on-win11/"><u>Enhanced Energy Visibility: Personalized Notifications for Fully Charged Batteries on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-microsoft-ai-hub-features/"><u>Exploring Microsoft AI Hub Features</u></a></li>
<li><a href="https://extra-resources.techidaily.com/finns-funds-youtube-stars-weekly-take-home/"><u>Finn's Funds  YouTube Star’s Weekly Take-Home</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-x50-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor X50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-the-win-network-access-issue/"><u>How to Mend the WIN Network Access Issue</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-a-found-apple-iphone-12-pro-drfone-by-drfone-ios/"><u>How To Unlock A Found Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-a-complete-guide-to-downloading-and-backup-of-instagram-vids-on-pcmacos/"><u>In 2024, A Complete Guide to Downloading & Backup of Instagram Vids on PC/macOS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-itel-p40-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Itel P40</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-k11x-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo K11x Phone FRP Lock</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-list-where-to-pull-off-ringtone-files/"><u>In 2024, Ultimate List  Where To Pull Off Ringtone Files</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/masterful-mobile-and-desktop-sound-alteration-tools-for-2024/"><u>Masterful Mobile & Desktop Sound Alteration Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-bluetooth-attempt-error-in-windows/"><u>Mastering the Fix: Bluetooth Attempt Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-new-windows-11-taskbar-features/"><u>Mastering the New Windows 11 Taskbar Features</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pcs-powertoys-10-essential-tips/"><u>Mastering Windows PCs: PowerToys' 10 Essential Tips</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-ultimate-guide-to-3d-animation-software-free-paid-and-everything-in-between/"><u>New 2024 Approved Ultimate Guide to 3D Animation Software Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://win11.techidaily.com/nullify-non-compliance-notifications-in-win11/"><u>Nullify Non-Compliance Notifications in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/offline-process-for-extra-users-in-windows-11/"><u>Offline Process for Extra Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-missing-driver-issues/"><u>Overcoming Windows Error: Missing Driver Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-gpos-ensuring-compliance-on-modern-windows/"><u>Revitalizing GPOs: Ensuring Compliance on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/scrutinizing-password-ingress-windows-pass-and-no-pass-outcomes/"><u>Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-best-ispoofer-alternative-to-try-on-realme-v30-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Realme V30 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-apple-iphone-6s-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass Apple iPhone 6s Activation Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-failed-directx-graphics-driver-installations/"><u>Troubleshooting and Fixing Failed DirectX Graphics Driver Installations</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-windows-pin-entry/"><u>Troubleshooting Non-Responsive Windows PIN Entry</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-unresponsive-voice-commands/"><u>Troubleshooting Windows 11: Unresponsive Voice Commands</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/understanding-igs-evolution-reels-and-stories-for-2024/"><u>Understanding IG's Evolution  Reels and Stories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-bt-folder-functionality/"><u>Understanding Windows ~BT Folder Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-access-issues-with-these-top-5-windows-fixes-on-security-keys/"><u>Unlock Access Issues with These Top 5 Windows Fixes on Security Keys</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-importance-in-preserving-win-11-notifications/"><u>Unveiling the Importance in Preserving Win 11 Notifications</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-4-ways-to-loop-a-video-on-vimeo-for-2024/"><u>Updated 4 Ways to Loop a Video on Vimeo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-set-default-touch-input-placement/"><u>Win 11: Set Default Touch Input Placement</u></a></li>
<li><a href="https://win11.techidaily.com/yourdevice-link-assessing-risks-and-benefits-in-w10-systems/"><u>YourDevice Link - Assessing Risks and Benefits in W10 Systems</u></a></li>
</ul></div>
