---
title: Setting Specific Windows Lockdown Period
date: 2024-08-16T00:00:56.844Z
updated: 2024-08-17T00:00:56.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Specific Windows Lockdown Period
excerpt: This Article Describes Setting Specific Windows Lockdown Period
keywords: Lockdown Windows Time,Secure Window Lock,Set Windows Lock,Timed Windows Safeguard,Schedule Window Security,Lock Period Windows,Define Lockdown Window
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## Setting Specific Windows Lockdown Period

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-elevate-your-content-secrets-to-becoming-a-staff-favorite-at-vimeo/"><u>[New] 2024 Approved  Elevate Your Content  Secrets to Becoming a Staff Favorite at Vimeo</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-highlight-heroics-in-samsung-phone-games/"><u>[New] 2024 Approved  Highlight Heroics in Samsung Phone Games</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-steps-for-logging-virtual-exchanges/"><u>[New] Essential Steps for Logging Virtual Exchanges</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-youtubes-inner-workings-your-path-to-success/"><u>[New] Unlocking YouTube's Inner Workings  Your Path to Success</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-regulatory-stance-on-recording-youtube-video-content/"><u>[Updated] 2024 Approved  Regulatory Stance on Recording YouTube Video Content</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-brief-blend-of-film-blueprints/"><u>[Updated] Brief Blend of Film Blueprints</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-building-connections-online-start-with-a-facebook-account-for-2024/"><u>[Updated] Building Connections Online  Start with a Facebook Account for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-step-by-step-easy-snapchat-videos-with-multiple-snaps/"><u>[Updated] In 2024, Step-by-Step  Easy Snapchat Videos with Multiple Snaps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-affordable-overseas-vr-headsets-china/"><u>2024 Approved  Affordable Overseas VR Headsets (China)</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-plan-9-steps-to-stop-wwe-crashes-in-windows/"><u>Accelerated Action Plan: 9 Steps to Stop WWE Crashes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-menu-items-in-windows-11-desktop/"><u>Addressing Frozen Menu Items in Windows 11 Desktop</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-honor-magic-6-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/channel-creation-chronicles-the-ultimate-beauty-blogging-start-up/"><u>Channel Creation Chronicles  The Ultimate Beauty Blogging Start-Up</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatgptplus-revolutionary-tech-for-fluent-multilingualism/"><u>ChatGPT+: Revolutionary Tech for Fluent Multilingualism</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/comprehensively-ranking-free-screen-capture-tools-2023-for-2024/"><u>Comprehensively Ranking Free Screen Capture Tools 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-effective-power-indicators-in-windows/"><u>Crafting Effective Power Indicators in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-chkdsk-sfc-and-dism-for-system-repairing/"><u>Decoding CHKDSK, SFC & DISM for System Repairing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/differentiating-ar-vr-mr-and-xr-an-in-depth-comparison/"><u>Differentiating AR, VR, MR & XR: An In-Depth Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-spotify-connectivity-fails/"><u>Eliminating Windows 11'S Spotify Connectivity Fails</u></a></li>
<li><a href="https://extra-hints.techidaily.com/examining-performance-of-dji-raptor-eyewear/"><u>Examining Performance of DJI Raptor Eyewear</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-mysterious-process-abruptly-ended-error-code-1067-in-windows/"><u>Fixing the Mysterious 'Process Abruptly Ended' Error Code 1067 in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-skirt-sie-and-load-unsigned-drivers-in-windows-oses/"><u>How to Skirt SIE & Load Unsigned Drivers in Windows OSes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-honor-v-purse-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Honor V Purse to iPad | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-evolving-scripts-in-cinema-today/"><u>In 2024, Evolving Scripts in Cinema Today</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-freezing-fun-at-the-beijing-olympics-2022/"><u>In 2024, Freezing Fun at the Beijing Olympics 2022</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/master-the-art-of-file-acquisition-expert-guide-for-downloading-igtv-for-2024/"><u>Master the Art of File Acquisition  Expert Guide for Downloading IGTV for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-your-windows-stylus-device/"><u>Mastering the Art of Fixing Your Windows Stylus Device</u></a></li>
<li><a href="https://win11.techidaily.com/max-1-antivirus-for-windows-optimize-system-performance/"><u>Max 1 Antivirus for WIndows: Optimize System Performance</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-activation-failures-in-office-suite/"><u>Navigating Activation Failures in Office Suite</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-failed-0x0000011b-in-windows/"><u>Overcoming Operation Failed 0X0000011B in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-inactive-session-limit/"><u>Personalizing Windows Inactive Session Limit</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-original-look-for-discoloured-extend-volume/"><u>Reclaim Original Look for Discoloured Extend Volume</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-gaming-with-dxvk-the-windows-perspective/"><u>Revolutionizing Gaming with DXVK - The Windows Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-ui-proposing-innovations-in-windows-11-widget-design/"><u>Revolutionizing UI: Proposing Innovations in Windows 11 Widget Design</u></a></li>
<li><a href="https://win11.techidaily.com/security-alert-hacked-fingerprint-recognition-on-windows/"><u>Security Alert: Hacked Fingerprint Recognition on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unhandled-exception-strategies-to-mitigate-on-pc/"><u>Simplifying Unhandled Exception: Strategies to Mitigate on PC</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/speedy-techniques-for-converting-srt-files-into-text-format-for-2024/"><u>Speedy Techniques for Converting SRT Files Into Text Format for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/squashing-faulty-empty-directory-alert-with-0x80070091-on-windows-11/"><u>Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-systems-top-strategies-for-fixed-windows-11-wwe-games/"><u>Swift Systems: Top Strategies for Fixed Windows 11 WWE Games</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-of-readings-unveiling-these-5-ai-enhanced-recommendation-services/"><u>The Future of Readings: Unveiling These 5 AI-Enhanced Recommendation Services</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-retrieve-faded-bios-messages/"><u>Tips to Retrieve Faded BIOS Messages</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-nokia-c32-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-fixes-to-unblock-firefox-page-load-blockage/"><u>Top Windows Fixes to Unblock Firefox Page Load Blockage</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-gaming-potential-android-on-win-11-through-google-services-access/"><u>Unlock Gaming Potential: Android on Win 11 Through Google Services Access</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
</ul></div>
