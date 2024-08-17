---
title: "Erasing Email on Windows Sign-In: A Guide"
date: 2024-08-15T23:36:09.126Z
updated: 2024-08-16T23:36:09.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Erasing Email on Windows Sign-In: A Guide"
excerpt: "This Article Describes Erasing Email on Windows Sign-In: A Guide"
keywords: Erase Email Login,Wipe Sign-In Info,Remove Account Details,Clear Windows Passwords,Delete Email Credentials,Forget Windows ID,Purging Sign-In Data
thumbnail: https://thmb.techidaily.com/b1557e3d9700a9810b8b9bbec88362c53ba5a3f98f5f309c7652fc768db4746d.jpg
---

## Erasing Email on Windows Sign-In: A Guide

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-iphone-and-android-photo-and-video-capture-applications-reviewed/"><u>[New] 2024 Approved  Best iPhone & Android Photo & Video Capture Applications Reviewed</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-mics-on-mission-find-the-best-for-your-youtube-channels-vision-and-voice/"><u>[New] Mics on Mission  Find the Best for Your YouTube Channel’s Vision & Voice</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-digital-detailing-at-your-command/"><u>2024 Approved  Digital Detailing at Your Command</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-leveraging-vr-to-shape-modern-business-practices/"><u>2024 Approved  Leveraging VR to Shape Modern Business Practices</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-boot-blockers-top-windows-troubleshooting-steps/"><u>Breaking Through Boot Blockers: Top Windows Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-back-into-disconnected-adapters-a-six-step-guide-on-winos/"><u>Breathing Life Back Into Disconnected Adapters: A Six-Step Guide on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-apple-and-windows-calendars-a-comprehensive-guide/"><u>Bridging Apple and Windows Calendars: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-the-seven-timeless-windows-features-of-11/"><u>Bridging Generations: The Seven Timeless Windows Features of 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-worlds-windows-meets-kali-linux/"><u>Bridging Worlds: Windows Meets Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-missing-steam-game-icons-quickly/"><u>Bring Back Missing Steam Game Icons Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-windows-up-to-date-key-differences-from-w10-to-w11/"><u>Bringing Windows Up to Date: Key Differences From W10 to W11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-credential-manager-lockup-in-windows/"><u>Bypass Credential Manager Lockup in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-while-opening-sound-device-in-audacity-for-windows/"><u>Bypassing Error While Opening Sound Device in Audacity for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-frozen-startup-screen-in-win-lol/"><u>Bypassing Frozen Startup Screen in Win: LOL</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-printer-busy-on-windows-11-systems/"><u>Bypassing Printer Busy on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/changing-the-time-before-next-login-attempt-on-failure/"><u>Changing the Time Before Next Login Attempt on Failure</u></a></li>
<li><a href="https://win11.techidaily.com/cheap-bargains-come-with-hidden-risks-for-windows-users/"><u>Cheap Bargains Come with Hidden Risks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-and-windows-11-the-ultimate-synchronization-guide/"><u>Chromium & Windows 11: The Ultimate Synchronization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/chromium-setup-for-windows-11-essential-guide/"><u>Chromium Setup for Windows 11: Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/classic-conundrum-playing-vintage-games-with-dosbox-x/"><u>Classic Conundrum: Playing Vintage Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-clutter-experience-unadorned-windows-11/"><u>Clear the Clutter: Experience Unadorned Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-forbidden-errors-in-windows-os/"><u>Clearing Forbidden Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-session-verification-failure-on-your-steam-pc/"><u>Clearing Up Session Verification Failure on Your Steam PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-error-31-restoring-seamless-internet-access/"><u>Clearing Up WIN Error 31: Restoring Seamless Internet Access</u></a></li>
<li><a href="https://win11.techidaily.com/combat-non-mic-working-on-windows-headsets/"><u>Combat Non-Mic Working on Windows Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/combating-insufficient-usb-controller-support/"><u>Combating Insufficient USB Controller Support</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-excel-2010-files-stellar-by-stellar-guide/"><u>How to Repair Corrupt Excel 2010 Files | Stellar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-a78-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo A78 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-sony-xperia-1-v-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Sony Xperia 1 V PC | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-your-oppo-reno-8t-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Oppo Reno 8T Lock Screen Password</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-meizu-21-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Meizu 21 FRP Without Computer</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-spark-20-pro-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Spark 20 Pro Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleashing-memories-above-ground-top-tier-cloud-options-reviewed-for-2024/"><u>Unleashing Memories Above Ground  Top-Tier Cloud Options Reviewed for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Lava Blaze Pro 5G? | Dr.fone</u></a></li>
</ul></div>
