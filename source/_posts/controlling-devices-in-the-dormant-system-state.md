---
title: Controlling Devices in the Dormant System State
date: 2024-08-15T23:51:18.690Z
updated: 2024-08-16T23:51:18.690Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Devices in the Dormant System State
excerpt: This Article Describes Controlling Devices in the Dormant System State
keywords: Dormant System Controls,Device Management Sleep,Sleep Mode Device Ops,Operating Device Standby,Systems In Low-Power Mode,Power State Device Management,Devices in Idle Stance
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## Controlling Devices in the Dormant System State

 When not in use, putting your Windows PC to sleep is an excellent way to preserve its battery life. You can wake your computer at any time by simply wiggling the mouse, pressing the power button, or pressing a key on your keyboard.

 Windows gives you complete control over devices that can wake your computer from a sleep state. In this guide, we will discuss how you can manage those devices.

## How to Check Which Devices Are Capable of Waking Your Windows PC From Sleep Mode

 Not every device connected to your system can wake Windows from sleep mode. You can use Command Prompt or Windows PowerShell to determine which of your devices supports waking the computer.

1. Press**Win + S** to open the search menu.
2. Type in**Windows PowerShell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to view a list of devices on your system that can wake Windows from any sleep state.  
`powercfg -devicequery wake_from_any`  
![Devices That Can Wake Windows From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-That-Can-Wake-Windows-From-Sleep-Mode.jpg)

 On this list, you'll see devices like your keyboard, mouse, network adapter, and more.

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to [launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above command, Windows will tell you which device or process woke your computer from sleep mode.

 If you see something like**Wake History Count - 0** , it means that Windows doesn't have a record of wake history. This can happen if you've recently rebooted your computer.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Deny a Device Permission to Wake Your Windows PC From Sleep Mode

 Once you know which devices are waking up your computer without your consent, you can take the necessary steps to prevent them from doing so.

To allow or deny a device permission to wake your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Device Manager** from the list.
3. Locate the device you want to configure. Right-click on it and select**Properties** .
4. In the Properties window, switch to the**Power Management** tab.
5. Check or uncheck the**Allow this device to wake the computer** checkbox to allow or disallow the permission.
6. Click**OK** to save the changes.  
![Allow or Disallow Device to Wake Computer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Allow-or-Disallow-Device-to-Wake-Computer-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on [how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## Manage Your Computer’s Sleep

 Now you know what devices can wake your computer from a sleep state and how to prevent them from doing so. That said, putting your computer in sleep mode may not always be the best option for your laptop. Sometimes, it’s better to shut it down completely.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-restrict-viewership-of-your-youtube-content/"><u>[New] 2024 Approved  How to Restrict Viewership of Your YouTube Content</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-alternatives-to-googles-ar-interactive-graphics/"><u>[New] Alternatives to Google's AR Interactive Graphics</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-uncovering-budget-friendly-video-conferencing-tools-for-all-systems/"><u>[New] Uncovering Budget-Friendly Video Conferencing Tools for All Systems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-mastery-in-monitoring-adding-time-based-events-to-obs/"><u>[Updated] 2024 Approved  Mastery in Monitoring  Adding Time-Based Events to OBS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dominating-the-digital-space-5-tips-for-video-visibility-victory-for-2024/"><u>[Updated] Dominating the Digital Space  5 Tips for Video Visibility Victory for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-picked-webcams-for-crystal-clear-zoom-meetings/"><u>[Updated] Expert-Picked Webcams for Crystal Clear Zoom Meetings</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-spice-up-your-feeds-text-based-meme-magic/"><u>[Updated] Spice Up Your Feeds  Text-Based Meme Magic</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-role-and-significance-of-blue-icons-in-fb-chats-for-2024/"><u>[Updated] The Role and Significance of Blue Icons in FB Chats for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-honor-magic-5-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-obs-versus-screensnapper/"><u>2024 Approved  OBS Versus ScreenSnapper</u></a></li>
<li><a href="https://win11.techidaily.com/7-game-changing-windows-11-additions-in-moment-22h2/"><u>7 Game-Changing Windows 11 Additions in Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-utilities-to-update-file-timestamps/"><u>7 Windows Utilities To Update File Timestamps</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-rectifying-mmc-snap-in-failures/"><u>A Guide to Rectifying MMC Snap-In Failures</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721267108332-act-fast-high-performance-iphone-data-salvage-kits-on-sale-now/"><u>Act Fast! High-Performance iPhone Data Salvage Kits on Sale Now</u></a></li>
<li><a href="https://article-posts.techidaily.com/avoid-being-overwhelmed-by-tiktok-drafts-edits-for-orderliness/"><u>Avoid Being Overwhelmed by TikTok Drafts  Edits for Orderliness</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-system-update-warnings/"><u>Disabling Windows System Update Warnings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/easy-relaxation-no-license-sounds/"><u>Easy Relaxation No-License Sounds</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-strategies-to-fix-gtfo-app-errors-and-crashes/"><u>Effective Strategies to Fix GTFO App Errors and Crashes</u></a></li>
<li><a href="https://games-able.techidaily.com/embrace-mobile-gaming-playing-steam-games-on-smartphones/"><u>Embrace Mobile Gaming: Playing Steam Games on Smartphones</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-choice-the-very-best-8-cameras-for-streamers/"><u>Expert Choice  The Very Best 8 Cameras For Streamers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-disabled-status-on-windows-pcs/"><u>Fixing Grammarly Disabled Status on Windows PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/from-novice-to-expert-conquering-business-vernacular/"><u>From Novice to Expert: Conquering Business Vernacular</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-xbox-games-access-error-in-windows-pcs/"><u>Guide to Correct Xbox Games Access Error in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-intel-unison-power-for-effective-pc-phone-calls/"><u>Harnessing Intel Unison Power for Effective PC Phone Calls</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-lava-blaze-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-hot-30-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Hot 30 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-and-search-features-in-windows-11-os/"><u>Mastering Highlight & Search Features in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-removing-false-device-notifications/"><u>Mastering the Art of Removing False Device Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-integrating-dynamic-desktop-backgrounds/"><u>Mastering Windows 11: Integrating Dynamic Desktop Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-computers-visual-experience-with-enhanced-vram/"><u>Optimize Your Computer's Visual Experience with Enhanced VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-makers-code-0x8007043c-issue/"><u>Overcoming Windows Media Maker's Code 0X8007043C Issue</u></a></li>
<li><a href="https://video-capture.techidaily.com/seamless-incorporation-of-virtual-boards-in-web-conferencing-mobiledesktop-methods-for-2024/"><u>Seamless Incorporation of Virtual Boards in Web Conferencing  Mobile/Desktop Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-windows-11-update-combat-error-0x30017/"><u>Smoothing Windows 11 Update: Combat Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-instructions-fully-removing-wsl/"><u>Step-By-Step Instructions: Fully Removing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-rectifying-file-history-missteps-in-windows-os/"><u>Steps for Rectifying File History Missteps in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11-cannot-open-for-writing/"><u>Steps to Overcome Windows 11: Cannot Open For Writing</u></a></li>
<li><a href="https://win11.techidaily.com/subnet-adjustment-for-win11-users/"><u>Subnet Adjustment for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-windows-based-counter-strike-play/"><u>Supercharge Windows-Based Counter-Strike Play</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-snap-open-apps-in-windows-11/"><u>Swiftly Snap Open Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-problem-code-0x800f0922/"><u>Tackling Windows Update Problem - Code 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/tech-renaissance-atlasos-for-obsolete-systems/"><u>Tech Renaissance: AtlasOS for Obsolete Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-ultimate-hawku-car-tune-up-manual/"><u>The Ultimate Hawku Car Tune-Up Manual</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1011s-aural-output-via-audacity/"><u>Troubleshooting Windows 10/11'S Aural Output, via Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-recommended-games-on-windows-11-screen/"><u>Turn Off Recommended Games on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unclouding-your-display-secrets-to-a-sharp-windows-11-screen/"><u>Unclouding Your Display: Secrets to a Sharp Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-assistance-best-free-tools-for-a-win11-revamp/"><u>Unmatched Assistance: Best Free Tools for a Win11 Revamp</u></a></li>
<li><a href="https://win11.techidaily.com/win1110-nat-transition-altering-type-effectively/"><u>Win11/10 NAT Transition: Altering Type Effectively</u></a></li>
</ul></div>
