---
title: Maximizing System Efficiency Through CPU Settings
date: 2024-08-16T00:49:01.593Z
updated: 2024-08-17T00:49:01.593Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maximizing System Efficiency Through CPU Settings
excerpt: This Article Describes Maximizing System Efficiency Through CPU Settings
keywords: CPU Performance Optimization,Enhance CPU Speed,Boost Processor Efficiency,Optimal CPU Config,High-Performance CPUs,Efficient CPU Settings,CPU Efficiency Maximization
thumbnail: https://thmb.techidaily.com/6612d7a6b7e8b44ce845a24c9c71af5e69ea9f37b5bedb688c03953f127445f3.jpg
---

## Maximizing System Efficiency Through CPU Settings

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unveiling-premium-screen-recorders-in-tech/"><u>[Updated] In 2024, Unveiling Premium Screen Recorders in Tech</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-complete-review-for-samsung-gear-360-camera/"><u>2024 Approved  Complete Review for Samsung Gear 360 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-0x800704b3-on-windows-pcs/"><u>Addressing Error Code 0X800704B3 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-credential-entry-attempts/"><u>Analyzing Windows Credential Entry Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-losses-commit-to-daily-windows-data-archiving/"><u>Avoid Losses: Commit to Daily Windows Data Archiving</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-oneplus-nord-ce-3-5g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on OnePlus Nord CE 3 5G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-error-code-0xc0000001-on-windows/"><u>Decoding and Fixing Error Code 0XC0000001 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-audio-excellence-with-5-free-windows-apps/"><u>Elevate Audio Excellence with 5 Free Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-connection-stop-usb-sleep-in-win-11/"><u>Ensuring Continuous Connection: Stop USB Sleep in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/frontier-fantasies-selecting-the-most-impressive-titles-for-2024/"><u>Frontier Fantasies  Selecting the Most Impressive Titles for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-fix-non-opening-photoshop-on-latest-windows-11/"><u>Guides to Fix Non-Opening Photoshop on Latest Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-problem-of-the-discontinued-print-driver-service-for-legacy-apps/"><u>How to Fix the Problem of the Discontinued Print Driver Service for Legacy Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-iphone-11-pro-max-from-backup-when-itunes-backup-is-corrupt-or-not-compatible-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Restore iPhone 11 Pro Max from Backup when iTunes Backup is Corrupt or not compatible | Stellar</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-12r-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock OnePlus 12R Phone with Broken Screen</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-joining-the-party-your-guide-to-tiktok-livestreams/"><u>In 2024, Joining the Party  Your Guide to TikTok Livestreams</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professionals-guide-to-iphoneandroiddslr-stabilized-gimbal-leaders/"><u>In 2024, Professional's Guide to iPhone/Android/DSLR Stabilized Gimbal Leaders</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-xiaomi-redmi-note-12-4g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Xiaomi Redmi Note 12 4G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-space-windows-11s-disk-defragmentation-guide/"><u>Maximizing Space: Windows 11'S Disk Defragmentation Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/st-to-you-heres-a-list-of-7-free-editing-apps-for-2024/"><u>No Cost to You? Here's a List of 7 Free Editing Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-code-4-spotify-error-on-w10w11-systems/"><u>Overcoming the Code 4 Spotify Error on W10/W11 Systems</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Planning to Use a Pokemon Go Joystick on Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reinvigorating-the-stuck-windows-start-menu-symbol/"><u>Reinvigorating the Stuck Windows Start Menu Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-x0001-with-nvidia-experience-w11/"><u>Remedying Error X0001 with Nvidia Experience, W11</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-microsoft-store-crash-0x80073d26/"><u>Strategies to Overcome Microsoft Store Crash: 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-dynamic-walls-in-windows-11-for-enhanced-aesthetics/"><u>The Art of Dynamic Walls in Windows 11 for Enhanced Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-alt-codes-in-windows/"><u>Troubleshooting Non-Responsive ALT Codes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-threshold-post-failed-access-on-w10w11/"><u>Tweaking the Lockout Threshold Post-Failed Access on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadows-tackling-wacatacbml-on-microsoft-windows/"><u>Unveiling the Shadows: Tackling Wacatac.B!ml on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-advanced-taskbar-attachments/"><u>Windows 11: Advanced Taskbar Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/1719338109987-windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony</u></a></li>
</ul></div>
