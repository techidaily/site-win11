---
title: How to Fix a Missing Battery Time Estimate in Windows 11
date: 2024-07-29T15:44:42.964Z
updated: 2024-07-30T15:44:42.964Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Missing Battery Time Estimate in Windows 11
excerpt: This Article Describes How to Fix a Missing Battery Time Estimate in Windows 11
keywords: Windows 11 Battery Time,Fixed Missing Battery,Restore Windows Timestamp,Estimating Battery Life,Solve Watts Time Loss,Correct Battery Duration,Unseen Power Countdown Fix
thumbnail: https://thmb.techidaily.com/0ce905cbb913b2eefe4db5c72014c9485f061b0fd3b1b129c677df4a5fe1e713.jpg
---

## How to Fix a Missing Battery Time Estimate in Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://screen-recording.techidaily.com/new-10-best-gba-emulators-for-android-you-can-find-for-2024/"><u>[New] 10 Best GBA Emulators for Android You Can Find for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-digital-broadcasting-platform-critique/"><u>[New] 2024 Approved  Digital Broadcasting Platform Critique</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-software-practices-for-transforming-pictures-into-films/"><u>[New] Best Software Practices for Transforming Pictures Into Films</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-chef-challenges-top-10-improvisational-cooking-videos-for-2024/"><u>[New] Chef Challenges  Top 10 Improvisational Cooking Videos for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-minecraft-shaping-mastery-crafting-circles-and-spheres/"><u>[New] In 2024, Minecraft Shaping Mastery  Crafting Circles & Spheres</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-leveraging-twitter-archive-for-research/"><u>[New] Leveraging Twitter Archive for Research</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-picks-crafting-mc-villages-abodes-for-2024/"><u>[New] Top Picks  Crafting MC Villages' Abodes for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-pixel-perfect-photography-excelling-in-the-best-6-4k-dslrs/"><u>[Updated] 2024 Approved  Pixel Perfect Photography  Excelling in the Best 6 4K DSLRs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-boost-your-views-optimal-hashtags-for-video-success/"><u>[Updated] Boost Your Views  Optimal Hashtags for Video Success</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-newfrontiersincameratech/"><u>[Updated] In 2024, NewFrontiersInCameraTech</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-strengthen-your-content-identity-inserting-watermarklogo-in-videos/"><u>[Updated] Strengthen Your Content Identity  Inserting Watermark/Logo in Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-tips-and-tricks-for-adding-media-in-instagram-for-2024/"><u>[Updated] Tips & Tricks for Adding Media in Instagram for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-underwater-worlds-unseen-pro-tips-for-capturing-vivid-gopro-footage-underwater/"><u>2024 Approved  Underwater Worlds Unseen  Pro Tips for Capturing Vivid GoPro Footage Underwater</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-github-desktop-adoption-in-windows-11/"><u>Best Practices for GitHub Desktop Adoption in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-budget-efficiency-windows-11-pro-discounts/"><u>Boost Budget Efficiency: Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/create-a-distinctive-color-scheme-in-wt-terminal/"><u>Create a Distinctive Color Scheme in WT Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/critics-common-grumbles-windows-11-unveiled/"><u>Critics' Common Grumbles: Windows 11 Unveiled</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-steps-for-disabling-windows-graphics/"><u>Easy Steps for Disabling Windows Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-management-navigating-through-network-tools-on-window/"><u>Effortless Management: Navigating Through Network Tools on Window</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-functional-state-in-dead-usb-ports-win-edition/"><u>Enabling Functional State in Dead USB Ports, Win Edition</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/enhance-engagement-with-these-4-looping-video-techniques-for-2024/"><u>Enhance Engagement with These 4 Looping Video Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-interaction-on-windows-discord-app/"><u>Enhancing Live Interaction on Windows Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-frozen-grammarly-app-a-windows-users-guide/"><u>Fixing Frozen Grammarly App: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/from-easy-access-to-higher-security-transitioning-your-logon-method-on-windows-11/"><u>From Easy Access to Higher Security: Transitioning Your Logon Method on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-rectify-erroneous-device-listings-in-windows/"><u>Guidelines to Rectify Erroneous Device Listings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-rectifying-confirm-pin-error-in-w11w10-setups/"><u>Guides to Rectifying Confirm PIN Error in W11/W10 Setups</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-find-x6-pro-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo Find X6 Pro Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-htc-u23-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from HTC U23</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-windows-11-search-icon-from-a-text-bar/"><u>How to Change Windows 11 Search Icon From a Text Bar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-and-retrieve-picturesvideos-from-a-water-damaged-iphone-13-pro-max-that-wont-turn-on-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix & Retrieve Pictures/Videos From a Water Damaged iPhone 13 Pro Max That Wont Turn on | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-the-quick-assist-tool-in-windows-11/"><u>How to Start the Quick Assist Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-transfer-files-on-a-network-using-a-python-server-on-windows/"><u>How to Transfer Files on a Network Using a Python Server on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-from-faces-to-films-the-mi-11s-advanced-screenshot-technology/"><u>In 2024, From Faces to Films  The Mi 11'S Advanced Screenshot Technology</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-oppo-reno-10-pro-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Oppo Reno 10 Pro 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premium-cloud-apps-for-android-the-most-reliable/"><u>In 2024, Premium Cloud Apps for Android  The Most Reliable</u></a></li>
<li><a href="https://fox-http.techidaily.com/innovative-methods-for-enhancing-testimonial-video-authenticity/"><u>Innovative Methods for Enhancing Testimonial Video Authenticity</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overmal-restarting-windows-11-software/"><u>Mastery Overmal: Restarting Windows 11 Software</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-silent-windows-headset-mic/"><u>Mending Your Silent Windows Headset Mic</u></a></li>
<li><a href="https://extra-support.techidaily.com/mirrored-moments-with-iphone-photography-expertise-for-2024/"><u>Mirrored Moments with iPhone Photography Expertise for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-permissions-management-in-w11-domains/"><u>Navigating Permissions Management in W11, Domains</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-zoom-on-chromebook-essential-advice/"><u>Navigating Zoom on Chromebook  Essential Advice</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-task-management-in-windows-11-via-enhanced-run-functionality/"><u>Optimizing Task Management in Windows 11 via Enhanced Run Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outlook-stuck-in-safe-mode-a-step-by-step-solution/"><u>Overcoming Outlook Stuck in Safe Mode: A Step-by-Step Solution</u></a></li>
<li><a href="https://win11.techidaily.com/prodigy-preparation-must-haves-from-microsoft-store/"><u>Prodigy Preparation: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-efficient-downloads-tips-from-microsofts-store/"><u>Quick and Efficient Downloads: Tips From Microsoft’s Store</u></a></li>
<li><a href="https://win11.techidaily.com/rav-antivirus-intrusion-origin-and-removal-guide/"><u>Rav Antivirus Intrusion: Origin & Removal Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/realize-your-vision-a-comprehensible-list-of-3d-animation-software-for-2024/"><u>Realize Your Vision  A Comprehensible List of 3D Animation Software for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Samsung Galaxy A34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/recover-missing-wireless-signal-a-windows-10-solution-guide/"><u>Recover Missing Wireless Signal: A Windows 10 Solution Guide</u></a></li>
<li><a href="https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/"><u>Renaissance PC: Refresh with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-help-app-failure/"><u>Resolving Windows 11 Help App Failure</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-app-management-on-windows-11-os/"><u>Speedy App Management on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-how-to-alter-file-extensions-on-windows/"><u>Step by Step: How to Alter File Extensions on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eradicating-system-call-failed-problem-in-windows-11/"><u>Steps for Eradicating System Call Failed Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-disconnection-methods-non-operational-printer-removal/"><u>Swift Disconnection Methods: Non-Operational Printer Removal</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-error-code-0x000-on-your-windows-11-devices-xbox-game-pass/"><u>Swiftly Resolving Error Code 0X000_ on Your Windows 11 Devices' Xbox Game Pass</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-steps-for-windows-sandbox-configuration-in-11/"><u>The Essential Steps for Windows Sandbox Configuration in 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-swift-way-to-access-control-panel/"><u>The Swift Way to Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-pcs-integrating-enhanced-run-utility-for-windows/"><u>Unleash Potential of PCs: Integrating Enhanced Run Utility for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-artistic-freedom-starting-microsoft-paint-on-windows-11/"><u>Unlocking Artistic Freedom: Starting Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-the-gains-from-dxvk-adoption/"><u>Windows Users - The Gains From DXVK Adoption</u></a></li>
</ul></div>
