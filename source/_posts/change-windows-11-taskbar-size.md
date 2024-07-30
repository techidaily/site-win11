---
title: Change Windows 11 Taskbar Size
date: 2024-07-29T15:56:03.227Z
updated: 2024-07-30T15:56:03.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Change Windows 11 Taskbar Size
excerpt: This Article Describes Change Windows 11 Taskbar Size
keywords: Win11 Taskbar Resize,Change Win11 BarSize,Windows 11 AdjustBar,Modify Win11 Controls,Set Win11 Taskbar,Alter Win11 Layout,Customize Win11 UI
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## Change Windows 11 Taskbar Size

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-mastering-desktop-merging-images-seamlessly/"><u>[New] 2024 Approved  Mastering Desktop  Merging Images Seamlessly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-tech-gurus-rate-them-all-unveiling-apeaksofts-screen-recording-capabilities/"><u>[New] 2024 Approved  Tech Gurus Rate Them All  Unveiling Apeaksoft’s Screen Recording Capabilities</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-apeaksofts-game-changing-recording-technology-review/"><u>[New] Apeaksoft's Game-Changing Recording Technology Review</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-a-guide-to-the-finest-apps-for-instagram-reel-creation/"><u>[New] In 2024, A Guide to the Finest Apps for Instagram Reel Creation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-yourself-with-top-4-applications-for-youtube-to-wav-conversion/"><u>[New] In 2024, Free Yourself with Top 4 Applications for YouTube-to-WAV Conversion</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-photo-editing-unveiling-clear-images-with-photopea/"><u>[New] Mastering Photo Editing  Unveiling Clear Images with Photopea</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-olympic-zenith-highlighting-snowboard-x-races/"><u>[New] Olympic Zenith  Highlighting Snowboard X Races</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-top-5-platforms-for-active-engagement-outside-of-twitter/"><u>[Updated] 2024 Approved  Top 5 Platforms For Active Engagement Outside of Twitter</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-blissful-movie-moments-your-summertime-classic-list/"><u>[Updated] Blissful Movie Moments  Your Summertime Classic List</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-innovative-downloaders-unveiled-top-8-of-2023/"><u>[Updated] Innovative Downloaders Unveiled  Top 8 of 2023</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-prime-selections-the-best-free-screencasting-apps-for-2024/"><u>[Updated] Prime Selections  The Best Free Screencasting Apps for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ultimate-windows-10-camera-software-review-top-10/"><u>[Updated] Ultimate Windows 10 Camera Software Review - Top 10</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-essential-gb-games-selecting-pc-emulators-to-simulate-gba-perfectly/"><u>2024 Approved  Essential GB Games  Selecting PC Emulators to Simulate GBA Perfectly</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-translating-trust-the-importance-of-client-endorsements/"><u>2024 Approved  Translating Trust  The Importance of Client Endorsements</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-ultimate-list-of-3d-typographic-sites/"><u>2024 Approved  Ultimate List of 3D Typographic Sites</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/address-mobile-devices-stalled-fb-videos/"><u>Address Mobile Devices  Stalled FB Videos</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-failure-in-updates-due-to-0x800f0845/"><u>Avoiding Failure in Updates Due to 0X800f0845</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-restore-microsofts-pc-manager-on-win/"><u>Breakthrough: Restore Microsoft's PC Manager on Win</u></a></li>
<li><a href="https://win11.techidaily.com/bring-forward-elusive-cameras-in-device-management/"><u>Bring Forward Elusive Cameras in Device Management</u></a></li>
<li><a href="https://win11.techidaily.com/browsers-efficiency-ranking-ram-and-cpu-usage-across-oses/"><u>Browsers' Efficiency Ranking: RAM & CPU Usage Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-upgrade-issue-error-xc004f050-on-windows-os/"><u>Bypassing Upgrade Issue: Error XC004f050 on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls</u></a></li>
<li><a href="https://win11.techidaily.com/correct-misplaced-second-display-on-windows-11/"><u>Correct Misplaced Second Display on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-mixed-user-microsoft-login-issues/"><u>Dealing with Mixed-User Microsoft Login Issues</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-windows-11-a-guide-to-taskbar-search-functionality/"><u>Dive Into Windows 11: A Guide to Taskbar Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-dns-flushing-in-modern-windows-os/"><u>Efficient Techniques for DNS Flushing in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/entrusting-administration-to-command-line/"><u>Entrusting Administration to Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-handle-printmanagement-service-failure/"><u>Essential Tips to Handle 'PrintManagement' Service Failure</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-sticker-free-video-creation-on-tiktok/"><u>Expert Sticker-Free Video Creation on TikTok</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/favorite-frames-socials-1-8-vids/"><u>Favorite Frames  Social's #1-#8 Vids</u></a></li>
<li><a href="https://win11.techidaily.com/file-sharing-mastery-constructing-python-servers-in-windows/"><u>File Sharing Mastery: Constructing Python Servers in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-asus-rog-phone-7-ultimate-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Asus ROG Phone 7 Ultimate Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fix-inflexible-scrollbar-issue-in-microsoft-excel-2016/"><u>Fix Inflexible Scrollbar Issue in Microsoft Excel 2016</u></a></li>
<li><a href="https://win11.techidaily.com/fix-steams-inaccessible-game-content-on-latest-windows-11/"><u>Fix Steam's Inaccessible Game Content on Latest Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-printer-in-the-os-environment/"><u>Fixing a Non-Functional Printer in the OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overscan-in-windows-enhance-screen-fit/"><u>Fixing Overscan in Windows - Enhance Screen Fit</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-immediate-assist-feature-windows-11/"><u>How to Engage Immediate Assist Feature: Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-iphone-12-pro-could-not-be-activatedreached-issue-by-drfone-ios/"><u>How To Fix iPhone 12 Pro Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-sign-out-of-apple-id-on-iphone-6s-plus-without-password-by-drfone-ios/"><u>How to Sign Out of Apple ID On iPhone 6s Plus without Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-tecno-spark-20-proplus-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Tecno Spark 20 Pro+ Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-realme-gt-neo-5-se-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-gionee-f3-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Gionee F3 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-proven-steps-for-effortless-creation-of-youtube-shorts-credits/"><u>In 2024, Proven Steps for Effortless Creation of YouTube Shorts Credits</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-superior-supplements-to-enhance-gopro/"><u>In 2024, Superior Supplements to Enhance GoPro</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-meme-making-method-unveiling-6-crucial-gif-production-strategies/"><u>In 2024, The Meme-Making Method  Unveiling 6 Crucial GIF Production Strategies</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-apple-iphone-6s-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your Apple iPhone 6s on MetroPCS</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-windows-update-stuck-at-100-here-are-6-fixes/"><u>Is Your Windows Update Stuck at 100%%? Here Are 6 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/launching-quake-mode-using-windows-terminal/"><u>Launching Quake Mode: Using Windows Terminal</u></a></li>
<li><a href="https://fix-guide.techidaily.com/lava-blaze-2-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Lava Blaze 2 Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-clickers-the-best-auto-click-cars-and-keys/"><u>Masterful Clickers: The Best Auto Click Cars & Keys</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-solve-frozen-shift-problems/"><u>Navigate and Solve Frozen Shift Problems.</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-dual-boot-like-a-pro-linux-and-chrome-os-on-one-device/"><u>New In 2024, Dual-Boot Like a Pro Linux and Chrome OS on One Device</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-barriers-reviving-spotify-streams/"><u>Overcoming Network Barriers: Reviving Spotify Streams</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-no-fingerprint-detection-error-on-windows/"><u>Overcoming the No Fingerprint Detection Error on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pursuing-passion-professionally-a-guide-for-aspiring-designers/"><u>Pursuing Passion Professionally  A Guide for Aspiring Designers</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-activate-windows-media-player/"><u>Simplified Steps to Activate Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-up-to-full-operating-system-windows-for-steam-deck/"><u>Stepping Up to Full Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-stopping-bsod-from-vmware-on-windows-11/"><u>Strategies for Stopping BSOD From VMware on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-windows-settings-for-cpu-states/"><u>Tapping Into Windows Settings for CPU States</u></a></li>
<li><a href="https://facebook.techidaily.com/tips-for-erasing-your-fb-browsing-log/"><u>Tips for Erasing Your FB Browsing Log</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x8007007e/"><u>Troubleshooting Windows Error 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-low-power-modes/"><u>Understanding Windows' Low-Power Modes</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-your-hardware-drivers-in-windows-11-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated your hardware drivers in Windows 11</u></a></li>
</ul></div>
