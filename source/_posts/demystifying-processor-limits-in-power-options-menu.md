---
title: Demystifying Processor Limits in Power Options Menu
date: 2024-08-16T00:01:34.556Z
updated: 2024-08-17T00:01:34.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Processor Limits in Power Options Menu
excerpt: This Article Describes Demystifying Processor Limits in Power Options Menu
keywords: CPU Thresholds Explained,Power Limit Insights,Optimal Battery Settings,Performance Curve Analysis,Processor Capability Guide,Energy Efficiency Controls,Maxing Out Devices
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## Demystifying Processor Limits in Power Options Menu

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-videos.techidaily.com/new-drafting-dynamic-news-endings/"><u>[New] Drafting Dynamic News Endings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-in-game-film-mastery-using-fbx-recorder/"><u>[New] In 2024, In-Game Film Mastery Using FBX Recorder</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-instagram-copyright/"><u>[New] Navigating Instagram Copyright</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-android-and-ios-leaders-in-asmr-content/"><u>[Updated] In 2024, Android & iOS Leaders in ASMR Content</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-step-into-tomorrow-secure-these-7-devices-for-metaverse-life/"><u>[Updated] In 2024, Step Into Tomorrow  Secure These 7 Devices for Metaverse Life</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-multitask-mastery-in-media-co-watching-channels-with-ease/"><u>2024 Approved  Multitask Mastery in Media  Co-Watching Channels with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-top-5-featherweight-camcorders-for-adventures/"><u>Best Top 5 Featherweight Camcorders for Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-bandwidth-gap-between-laptops-phones/"><u>Bridging the Bandwidth Gap Between Laptops, Phones</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-capability-in-mixing-drinks/"><u>ChatGPT's Capability in Mixing Drinks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/copilot-your-key-to-unlocking-the-full-power-of-free-gpt-4-turbo/"><u>Copilot: Your Key to Unlocking the Full Power of Free GPT-4 Turbo</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhancing-chats-adding-tunes-via-whatsapp-status/"><u>Enhancing Chats  Adding Tunes via WhatsApp Status</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exploring-nature-garmin-virb-ultra-30-cam-review/"><u>Exploring Nature  Garmin VIRB Ultra 30 Cam Review</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-blue-screen-wins-unhandled-exception/"><u>How to Address Blue Screen: Win's Unhandled Exception</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-itel-a05s-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Itel A05s | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-mini-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 mini To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-realme-narzo-n53-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Realme Narzo N53 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-5-low-cost-drones-maximum-performance-on-a-shoestring/"><u>In 2024, 5 Low-Cost Drones  Maximum Performance on a Shoestring</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/investigating-the-return-on-investment-in-wireless-meshes/"><u>Investigating the Return on Investment in Wireless Meshes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-issue-0xca00a009/"><u>Overcoming Windows Update Issue #0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-techniques-for-effective-qr-scanning-on-pcs/"><u>Pioneering Techniques for Effective QR Scanning on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-xiaomi-redmi-k70e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-curbing-virtual-disk-service-malfunction/"><u>Strategies: Curbing Virtual Disk Service Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-scheduler-issues-restore-smoothness/"><u>Tackle Windows Scheduler Issues, Restore Smoothness</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-grant-write-access-for-steam-folders-in-win-11/"><u>Techniques to Grant Write Access for Steam Folders in Win 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-htc-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 HTC Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11.techidaily.com/unique-visuals-for-your-window-terminal/"><u>Unique Visuals for Your Window Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-post-update-linux-subsystem-challenges-on-windows-11/"><u>Unraveling Post-Update Linux Subsystem Challenges on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
<li><a href="https://win11.techidaily.com/windows-unseen-the-emergence-of-ai-futures/"><u>Windows Unseen: The Emergence of AI Futures</u></a></li>
</ul></div>
