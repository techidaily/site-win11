---
title: Disable Dim Display Feature via Control Panel Quick Guide
date: 2024-08-15T23:41:48.802Z
updated: 2024-08-16T23:41:48.802Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
excerpt: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
keywords: Disable Screen Low Brightness,Control Panel Light Adjustment,Reduce Display Intensity,Simple Dark Mode Turn-Off,Quick Control Panel Guide,Dim Settings Deactivation,High Contrast Display Options
thumbnail: https://thmb.techidaily.com/481d06bf1b3256f57ab62815340fcc460dfe18ec5f4531d4ca28b88dc8e90d86.jpg
---

## Disable Dim Display Feature via Control Panel Quick Guide

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-a-step-by-step-guide-to-youtube-stats-analysis-via-social-blade-platform-for-2024/"><u>[New] A Step-by-Step Guide to YouTube Stats Analysis via Social Blade Platform for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-nba-livestream-a-list-of-15-essentials/"><u>[Updated] Mastering NBA Livestream  A List of 15 Essentials</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/a-beginners-guide-to-japenese-social-etiquette/"><u>A Beginner's Guide to Japenese Social Etiquette</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-beginners-guide-printer-ready-designs-using-adobe-photoshop/"><u>A Beginner's Guide: Printer-Ready Designs Using Adobe Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/address-extra-monitor-issue-on-w11-os/"><u>Address Extra Monitor Issue on W11 OS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/apples-most-accessible-ipad-yet-a-thorough-review-of-the-latest-8th-generation-model/"><u>Apple's Most Accessible iPad Yet? A Thorough Review of the Latest 8Th Generation Model</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/attracting-watchers-discover-the-top-6-video-types-for-2024/"><u>Attracting Watchers  Discover the Top 6 Video Types for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-the-glitch-discover-the-best-8-strategies-to-keep-multiversus-running-smoothly/"><u>Beat the Glitch: Discover the Best 8 Strategies to Keep MultiVersus Running Smoothly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/best-15-tiktok-inspired-reading-picks-for-avid-readers/"><u>Best 15 TikTok-Inspired Reading Picks for Avid Readers</u></a></li>
<li><a href="https://win11.techidaily.com/dont-double-dip-the-case-against-two-antiviruses/"><u>Don't Double Dip: The Case Against Two Antiviruses</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-tick-tock-sync-your-clock/"><u>Fixing Windows' Tick-Tock: Sync Your Clock</u></a></li>
<li><a href="https://win11.techidaily.com/frame-perfecting-eliminating-lags-with-these-9-windows-strategies/"><u>Frame Perfecting: Eliminating Lags with These 9 Windows Strategies</u></a></li>
<li><a href="https://fox-http.techidaily.com/galactic-grandeur-in-hd-optimal-websites-featuring-the-sky/"><u>Galactic Grandeur in HD  Optimal Websites Featuring the Sky</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-switch-off-cortana-functionality/"><u>Guide to Switch Off Cortana Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/handling-closed-caption-setup-challenges-in-win11/"><u>Handling Closed Caption Setup Challenges in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-xbox-app-update-failures/"><u>How to Correct Xbox App Update Failures</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manage-windows-user-accounts-via-the-command-prompt/"><u>How to Manage Windows User Accounts via the Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manipulate-windows-gpu-priority-settings/"><u>How to Manipulate Windows GPU Priority Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-honor-90-pro-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Honor 90 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-windows-defender-error-0x80004004-instantly/"><u>How to Solve Windows Defender Error 0X80004004 Instantly</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-4-things-you-must-know-about-apple-iphone-se-activation-lock-by-drfone-ios/"><u>In 2024, 4 Things You Must Know About Apple iPhone SE Activation Lock</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Apple iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-techniques-to-effectively-modify-software-sizes-in-win11/"><u>Keyboard Techniques to Effectively Modify Software Sizes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/keygen-threat-explained-windows-impact-and-cleanup-tips/"><u>Keygen Threat Explained: Windows Impact and Cleanup Tips</u></a></li>
<li><a href="https://win11.techidaily.com/linuxs-rise-is-wsl-a-factor/"><u>Linux's Rise: Is WSL a Factor?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fresh-windows-11-setup/"><u>Mastering Fresh Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/merrymaking-with-gifted-windows-apps-on-xmas-day/"><u>Merrymaking with Gifted Windows Apps on Xmas Day</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-xpatch-issues-error-0x80073712/"><u>Navigating Through XPatch Issues: Error 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-file-navigation-on-windows-implementing-movecopy-actions/"><u>Optimizing File Navigation on Windows: Implementing 'Move'/'Copy' Actions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-directx-update-failure-in-windows-systems/"><u>Overcoming DirectX Update Failure in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-insufficient-rights-for-program-removal-in-win-11/"><u>Overcoming Insufficient Rights for Program Removal in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permission-barriers-in-windows-updates/"><u>Overcoming Permission Barriers in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-inaccessible-pin-unlock-routine-in-windows-11/"><u>Resetting Inaccessible Pin Unlock Routine in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-skyrim-forge-edition-launching-error-issues-easily/"><u>Resolving Skyrim Forge Edition Launching Error Issues Easily</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-hardware-requirements-for-games/"><u>Resolving Windows Hardware Requirements for Games</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hidden-wi-fi-in-the-realm-of-windows-11/"><u>Resurrecting Hidden Wi-Fi in the Realm of Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionaries-building-virtual-realms-for-2024/"><u>Revolutionaries Building Virtual Realms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-local-drive-space-in-win11-without-loss-of-files-max-156-chars/"><u>Securely Manage Local Drive Space in Win11 Without Loss of Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-protection-enable-windows-11s-controlling-access/"><u>Setting Up Protection: Enable Windows 11’S Controlling Access</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/skybound-streaming-engaging-your-audience-on-facebook-for-2024/"><u>Skybound Streaming  Engaging Your Audience on Facebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-technique-for-mkv-to-mp4-change/"><u>Step-by-Step Windows Technique for MKV to MP4 Change</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stream-problems-solved-in-windows-10-update/"><u>Stream Problems Solved in Windows 10 Update</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-gear-use-windows-widgets-for-efficiency/"><u>Streamlining Your Gear Use: Windows Widgets for Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-ascertaining-your-pcs-intel-core-gen/"><u>Techniques for Ascertaining Your PC's Intel Core Gen</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-nokia-g22-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Nokia G22 Reset Code | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-motorola-edge-2023-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Motorola Edge 2023 Device</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshoot-and-correct-black-screen-error-on-your-fallout-4-game-console/"><u>Troubleshoot and Correct Black Screen Error on Your Fallout 4 Game Console</u></a></li>
<li><a href="https://win11.techidaily.com/turning-off-google-chrome-alerts-windows-edition/"><u>Turning Off Google Chrome Alerts, Windows Edition</u></a></li>
<li><a href="https://media-tips.techidaily.com/two-cost-free-methods-for-converting-mtsm2ts-files-into-mov-format-mac-online-and-windows-solutions/"><u>Two Cost-Free Methods for Converting MTS/M2TS Files Into MOV Format: Mac, Online & Windows Solutions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/uncover-all-about-instagrams-video-cap-for-2024/"><u>Uncover All About Instagram's Video Cap for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/your-ultimate-guide-to-finding-tiktok-wallpapers-for-2024/"><u>Your Ultimate Guide to Finding TikTok Wallpapers for 2024</u></a></li>
</ul></div>
