---
title: Tapping Into Windows Settings for CPU States
date: 2024-08-16T00:27:48.422Z
updated: 2024-08-17T00:27:48.422Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tapping Into Windows Settings for CPU States
excerpt: This Article Describes Tapping Into Windows Settings for CPU States
keywords: Windows CPUSet,CPU States Control,Manage Windows Cpu,Accessing Windows Cpustates,Optimizing Windows CPUs,Cpu Settings Window,Windows CPU Management
thumbnail: https://thmb.techidaily.com/e663bf23b6887cb8279b82d66477ecb71e4a937f5292de883673cace9e11db92.jpg
---

## Tapping Into Windows Settings for CPU States

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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-2023-online-facebook-video-to-mp3-converters/"><u>[New] 2024 Approved  2023 Online Facebook Video to MP3 Converters</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-top-10-undiscovered-memelists-on-facebook/"><u>[New] 2024 Approved  Top 10 Undiscovered Memelists on Facebook</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-unleash-your-creative-brand-selecting-one-of-a-kind-channel-titles/"><u>[New] 2024 Approved  Unleash Your Creative Brand  Selecting One-of-a-Kind Channel Titles</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-top-group-video-chat-apps-you-should-know-for-video-conferences-and-meetings/"><u>[New] In 2024, Top Group Video Chat Apps You Should Know [For Video Conferences and Meetings]</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-science-of-perfectly-timed-episodes/"><u>[New] The Science of Perfectly Timed Episodes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-adopting-a-simple-yet-powerful-approach-to-advertising-content/"><u>[Updated] Adopting a Simple Yet Powerful Approach to Advertising Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-frolic-in-fun-the-best-comedy-centric-concepts-for-shorter-videos-for-2024/"><u>[Updated] Frolic in Fun  The Best Comedy-Centric Concepts for Shorter Videos for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-chuckles-and-cheers-top-tweets-saver-with-gif/"><u>[Updated] In 2024, Chuckles & Cheers  Top Tweets Saver with GIF</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-unbox-the-ultimate-experience-master-windows-pc-screen-capturing-and-editing/"><u>[Updated] In 2024, Unbox the Ultimate Experience  Master Windows PC Screen Capturing and Editing</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-premium-online-streams-convert-youtube-to-mp3-instantly-in-2024/"><u>[Updated] Premium Online Streams  Convert YouTube to MP3 Instantly, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-laughter-logic-lab/"><u>2024 Approved  Laughter Logic Lab</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011-ad-ds-printer-errors-effectively-and-efficiently/"><u>Addressing Win 10/11 AD DS Printer Errors Effectively and Efficiently</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-on-apple-iphone-se-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock On Apple iPhone SE? How to Fix it?</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-cmd-skills-with-these-20-must-learn-commands/"><u>Boost Your CMD Skills with These 20 Must-Learn Commands</u></a></li>
<li><a href="https://review-topics.techidaily.com/change-location-on-yik-yak-for-your-vivo-v30-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Vivo V30 Pro to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-frozen-discord-overlay-on-your-windows-system/"><u>Combat the Frozen Discord Overlay on Your Windows System</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-guide-for-apple-iphone-15-pro-lock-screen-drfone-by-drfone-ios/"><u>Complete Guide For Apple iPhone 15 Pro Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-pc-hardware-mismatch-in-windows-captures/"><u>Correcting PC Hardware Mismatch in Windows Captures</u></a></li>
<li><a href="https://win11.techidaily.com/creating-harmony-between-android-tablets-and-windows-11-desktops/"><u>Creating Harmony Between Android Tablets and Windows 11 Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/dual-display-designs-crafting-individual-monitor-ambiance-in-win-1011/"><u>Dual Display Designs: Crafting Individual Monitor Ambiance in WIN 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-developer-setup-5-core-wsl-2-best-practices/"><u>Elevate Your Developer Setup: 5 Core WSL 2 Best Practices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/essential-guide-sync-your-screen-to-facebook-streams-for-2024/"><u>Essential Guide  Sync Your Screen to Facebook Streams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-comic-archives-with-windows-11-interface/"><u>Exploring Comic Archives with Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/finding-the-absent-hypervisor-fix-for-xc0351000-error/"><u>Finding the Absent Hypervisor - Fix for XC0351000 Error</u></a></li>
<li><a href="https://win11.techidaily.com/from-here-to-innovation-the-post-11-windows-journey/"><u>From Here to Innovation: The Post-11 Windows Journey</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Itel A60s? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-use-windows-11s-home-space/"><u>How to Access and Use Windows 11'S Home Space</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bridge-the-disconnect-gap-windows-11-and-printers/"><u>How to Bridge the Disconnect Gap: Windows 11 & Printers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-latest-realtek-asio-driver-for-enhanced-audio-on-windows-11/"><u>How to Get the Latest Realtek Asio Driver for Enhanced Audio on Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-tecno-spark-10c-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-motorola-moto-g-stylus-5g-2023-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Motorola Moto G Stylus 5G (2023) FRP Bypass With Best Methods</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-honor-magic-vs-2-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Honor Magic Vs 2 FRP?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-add-radial-blur-effect-to-photos-in-photoshop/"><u>In 2024, How to Add Radial Blur Effect to Photos in Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-windows-11-admin-interface/"><u>In-Depth Look at Windows 11 Admin Interface</u></a></li>
<li><a href="https://win11.techidaily.com/learn-mouse-gesture-tricks-in-microsofts-modern-edge-browser/"><u>Learn Mouse Gesture Tricks in Microsoft's Modern Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-service-failures-fixing-steam-errors-on-windows-11/"><u>Mastery Over Service Failures: Fixing Steam Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-the-primary-web-portal-on-w11/"><u>Modifying the Primary Web Portal on W11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-0x80860010-a-guide-to-fixes-for-windows/"><u>Navigating Through The 0X80860010: A Guide to Fixes for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-photo-workflow-with-keys/"><u>Optimizing Your Windows Photo Workflow with Keys</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-hover-over-sensitivity-and-trail-in-windows-11/"><u>Perfect Your Hover Over Sensitivity and Trail in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-non-genuine-adobe-app-warning/"><u>Prevent Non-Genuine Adobe App Warning</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-external-access-to-insider-developer-sets/"><u>Preventing External Access to Insider Developer Sets</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-missing-phone-link-notifications-on-pc/"><u>Restoring Functionality to Missing Phone Link Notifications on PC</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-add-on-of-portable-software-to-windows-oses/"><u>Seamless Add-On of Portable Software to Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-limit-microsoft-edge-processes/"><u>Strategies to Limit Microsoft Edge Processes</u></a></li>
<li><a href="https://win11.techidaily.com/tech-convergence-ios-ipados-mac-and-windows-operating-systems-tie/"><u>Tech Convergence: IOS, iPadOS, Mac & Windows Operating Systems Tie</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-comprehensive-guide-to-farming-on-ginger-islet/"><u>The Comprehensive Guide to Farming on Ginger Islet</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ultimate-low-cost-smart-home-devices-for-gaming/"><u>Ultimate Low-Cost Smart Home Devices for Gaming</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/uniting-conversations-across-platforms-twitter-vids-on-whatsapp/"><u>Uniting Conversations Across Platforms  Twitter Vids on WhatsApp</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tablets-enhancing-user-experience-with-a-taskbar/"><u>Windows 11 Tablets: Enhancing User Experience with a Taskbar</u></a></li>
</ul></div>
