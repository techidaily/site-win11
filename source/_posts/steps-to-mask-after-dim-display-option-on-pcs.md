---
title: Steps to Mask After Dim Display Option on PCs
date: 2024-08-15T23:28:50.603Z
updated: 2024-08-16T23:28:50.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Mask After Dim Display Option on PCs
excerpt: This Article Describes Steps to Mask After Dim Display Option on PCs
keywords: Dim Screen Mask Tips,Post-Display Darkening Guide,PC Display Shade Steps,Hide Behind Glass Effect,Low Brightness Mode Advice,Reduce Reflections Techniques,Eye Comfort After Dimming
thumbnail: https://thmb.techidaily.com/029b0eb85077c27446243e8d1c815878a76764b760390b18a7b33382115f2d0b.jpg
---

## Steps to Mask After Dim Display Option on PCs

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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-creating-engaging-haul-videos-techniques-and-tips-for-2024/"><u>[New] Creating Engaging Haul Videos  Techniques & Tips for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-realms-unchained-guide-to-the-best-of-no-cost-mmos-for-2024/"><u>[New] Realms Unchained  Guide to the Best of No-Cost MMOs for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-editors-pathway-for-diminishing-sound-levels/"><u>[New] The Editor's Pathway for Diminishing Sound Levels</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-concept-to-screen-channel-yt-for-pioneering-filmmaking-techniques/"><u>[Updated] 2024 Approved  From Concept to Screen  Channel YT for Pioneering Filmmaking Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-the-upside-down-world-of-instagram-videos/"><u>[Updated] Exploring the Upside-Down World of Instagram Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-best-6-modern-homes-for-minecraft-enthusiasts/"><u>[Updated] In 2024, Best 6 Modern Homes for Minecraft Enthusiasts</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-navigating-spotifys-advertising-landscape/"><u>[Updated] In 2024, Navigating Spotify's Advertising Landscape</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-personalizing-your-profile-with-fb-slideshow-content/"><u>[Updated] In 2024, Personalizing Your Profile with FB Slideshow Content</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-iphone-and-android-compared-top-youtube-app-analysis-for-2024/"><u>[Updated] IPhone & Android Compared  Top YouTube App Analysis for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-understanding-facebooks-chat-language-through-its-blue-signature-marker/"><u>[Updated] Understanding Facebook's Chat Language Through Its Blue Signature Marker</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/beyond-acid-pro-innovative-vector-editors-reviewed/"><u>Beyond ACID Pro  Innovative Vector Editors Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/cheapest-alternatives-to-androids-facetime/"><u>Cheapest Alternatives to Android's FaceTime</u></a></li>
<li><a href="https://screen-capture.techidaily.com/chuckles-and-challenges-best-fun-for-young-minds/"><u>Chuckles & Challenges - Best Fun for Young Minds</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/crystal-clear-play-premium-cards-for-4k/"><u>Crystal Clear Play  Premium Cards for 4K</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-lenovo-x220-drivers-instantly-seamless-setup-guide/"><u>Download Lenovo X220 Drivers Instantly: Seamless Setup Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-reverting-customized-windows-configurations/"><u>Effective Methods: Reverting Customized Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-user-experience-tailoring-windows-via-alomware-applications/"><u>Elevate User Experience: Tailoring Windows via AlomWare Applications</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-in-windows-11-os/"><u>Ensuring a Valid Temp Directory in Windows 11 OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exposing-effective-promotions-for-2024/"><u>Exposing Effective Promotions for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/from-frantic-movements-to-leisurely-views-crafting-spectacular-slow-motion-videos-for-instragram/"><u>From Frantic Movements to Leisurely Views  Crafting Spectacular Slow Motion Videos for Instragram</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-right-drivers-for-your-epson-scanner-free-downloads-available/"><u>Get the Right Drivers for Your Epson Scanner - Free Downloads Available</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/harmonics-high-flyers-top-5-programs-for-surpassing-windows-maxed-sound-level/"><u>Harmonics High-Flyers: Top 5 Programs for Surpassing Windows' Maxed Sound Level</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-connect-remote-desktop-without-a-password-in-windows-11/"><u>How to Connect Remote Desktop Without a Password in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-display-not-available-error-in-windows-11/"><u>How to Correct 'Display Not Available' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-print-functions-in-microsofts-security-shield/"><u>Implementing Print Functions in Microsoft's Security Shield</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-best-practices-for-inserting-text-on-youtube-videos-effectively/"><u>In 2024, Best Practices for Inserting Text on YouTube Videos Effectively</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-facebook-video-wizardry-mp4-download-spell/"><u>In 2024, Facebook Video Wizardry - MP4 Download Spell</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-finding-the-best-meme-ideas-to-create-viral-content/"><u>In 2024, Finding the Best Meme Ideas to Create Viral Content</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Nokia Phone without Any Data Loss</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/iphone-15-pro-max-vs-samsung-galaxy-s2n-ultra-showdown-analyzing-the-key-differences/"><u>IPhone 15 Pro Max Vs. Samsung Galaxy S2n Ultra Showdown: Analyzing the Key Differences</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/navigate-with-precision-top-mac-devices-for-seamless-mouse-control/"><u>Navigate with Precision: Top Mac Devices for Seamless Mouse Control</u></a></li>
<li><a href="https://win11.techidaily.com/organize-like-a-pro-5-must-try-windows-folder-tricks/"><u>Organize Like a Pro: 5 Must-Try Windows Folder Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-freeze-issues-photoshopping-onoff-windows-11-versions-2023/"><u>Overcoming Freeze Issues: Photoshopping On/Off Windows 11, Versions 2023</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pros-choice-9-premium-streaming-services-for-2024/"><u>Pro's Choice  9 Premium Streaming Services for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/propel-power-5-best-windows-optimization-strategies/"><u>Propel Power: 5 Best Windows Optimization Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-0x80072efd-on-windows-devices/"><u>Quick Guide to Resolve 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-ram-overcoming-obstacles-in-windows/"><u>Reigniting RAM: Overcoming Obstacles in Windows</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-vivo-y27-4g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Vivo Y27 4G</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sudden-freeze-and-blackout-with-steam/"><u>Resolving Sudden Freeze & Blackout with Steam</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-account-transitioning-from-pin-to-password-in-windows-11/"><u>Secure Your Account: Transitioning From PIN to Password in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-retrieving-sent-messages-from-your-inbox-in-microsoft-outlook/"><u>Step-by-Step Guide: Retrieving Sent Messages From Your Inbox in Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-averting-crashes-of-epic-games-launcher/"><u>Strategies for Averting Crashes of Epic Games Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-mbs-unable-to-link-error-on-win11/"><u>Strategies to Resolve MB's Unable to Link Error on Win11</u></a></li>
<li><a href="https://win-dash.techidaily.com/streamlined-setup-how-to-download-and-install-arduino-mega-2560-drivers-efficiently/"><u>Streamlined Setup: How to Download & Install Arduino Mega 2560 Drivers Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-importance-of-consistent-windows-data-saves/"><u>The Importance of Consistent Windows Data Saves</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peace-sleep-mode-strategies/"><u>The Path to Peace: Sleep Mode Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-printer-commands-using-windows-11-edge-shield-mode/"><u>Triggering Printer Commands Using Windows 11 Edge Shield Mode</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-ftdibussys-and-windows-memory-standards/"><u>Unlocking the Secrets of ftdibus.sys & Windows Memory Standards</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-cause-behind-error-0x80370102-in-wsl-distribution/"><u>Unraveling the Cause Behind Error 0X80370102 in WSL Distribution</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/user-choice-top-free-streaming-sites-for-sports/"><u>User Choice Top Free Streaming Sites for Sports</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/viral-visionaries-twitters-10-hotest-content-threads-today-for-2024/"><u>Viral Visionaries  Twitter's 10 Hotest Content Threads Today for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://iphone-location.techidaily.com/why-does-itools-virtual-location-not-work-for-apple-iphone-14ipad-solved-drfone-by-drfone-virtual-ios/"><u>Why Does iTools Virtual Location Not Work For Apple iPhone 14/iPad? Solved | Dr.fone</u></a></li>
</ul></div>
