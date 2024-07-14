---
title: Unveiling a Strategy to Resolve Locked Windows Update
date: 2024-07-13T10:34:46.024Z
updated: 2024-07-14T10:34:46.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling a Strategy to Resolve Locked Windows Update
excerpt: This Article Describes Unveiling a Strategy to Resolve Locked Windows Update
keywords: Fixing Window's Update Issue,Resolving Locked Updates,Unlock Windows Patch,Update Problem Solution,Streamline Windows Update,End Windows Lockdown,Optimize Windows Patching
thumbnail: https://thmb.techidaily.com/fa206782af9b714e31a62f7ae5d0a20ed9b7932652ed0826ec0104cd05df9774.jpg
---

## Unveiling a Strategy to Resolve Locked Windows Update

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out [how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the [many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  
![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to [know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still [access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

To edit and enable the Scripted Diagnostics policy:

1. Press the**Windows** +**R** keys together to open the**Run** box.
2. Type**gpedit.msc** in the navigation bar and click**Enter** .  
![Open Group Policy Editor Via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-group-policy-editor-via-run.jpg)
3. Click**Yes** on the UAC prompt. The**Group Policy Editor** will open.
4. In the**Group Policy Editor** , navigate to**Scripted Diagnostics** using the following path:  
`Computer Configuration > Administrative Templates > System > Troubleshooting and Diagnostics > Scripted Diagnostics`
5. In the left pane, click on**Scripted Diagnostics** to open its three items.  
![Open Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-scripted-diagnostics-policy.jpg)
6. Double-click on the first item and select the**Enable** option in the window that opens.  
![Enable Each Item in Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-items-of-scripted-diagnostics-policy.jpg)
7. Finally, tap on**Apply** and then**OK** .
8. Repeat steps 5 and 6 for the other two items of Scripted Diagnostics.

 Now close the Group Policy Editor and run the Windows Update Troubleshooter.

## Get the Windows Update Troubleshooter Working Again to Fix Update Errors

 It's important to have the Windows Update Troubleshooter running fine. Try the above fixes if it ever gets stuck or stops working. And ensure you can install essential updates to enjoy a smooth and secure Windows experience.

 You can also know more about security updates and why it makes sense to install them quickly.

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
<li><a href="https://win11.techidaily.com/navigating-group-policy-changes-on-a-windows-system/"><u>Navigating Group Policy Changes on a Windows System</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfecting-iphone-photography-for-vr-spheres/"><u>[Updated] Perfecting iPhone Photography for VR Spheres</u></a></li>
<li><a href="https://extra-information.techidaily.com/skydrives-frugal-option-minimal-price-maximum-space/"><u>Skydrive's Frugal Option  Minimal Price, Maximum Space</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-insufficient-storage-warning-in-vmware-hosts/"><u>Dealing with Insufficient Storage Warning in VMware Hosts</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-google-pixel-8-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Google Pixel 8 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ignoring-the-windows-lsa-protection-deactivation/"><u>Ignoring the Windows LSA Protection Deactivation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/captivating-spokesperson-appraisal-8th-analysis-for-2024/"><u>Captivating Spokesperson Appraisal 8Th Analysis for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-quick-and-reliable-image-captures-pcs-top-5-apps/"><u>[New] In 2024, Quick and Reliable Image Captures  PC's Top 5 Apps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-oppo-find-n3-flip-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Oppo Find N3 Flip to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-xiaomi-redmi-k70e-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Xiaomi Redmi K70E Phone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-strategies-for-resolving-password-hash-misalignment-on-windows/"><u>Essential Strategies for Resolving Password Hash Misalignment on Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-rhythm-rulebook-seamlessly-mixing-music-into-instagram-posts/"><u>[Updated] 2024 Approved  The Rhythm Rulebook  Seamlessly Mixing Music Into Instagram Posts</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/top-rated-motion-graphics-software-for-text-tracking-for-2024/"><u>Top-Rated Motion Graphics Software for Text Tracking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-a-closed-captioning-guru-windows-10-insights/"><u>Becoming a Closed Captioning Guru: Windows 10 Insights</u></a></li>
<li><a href="https://win11.techidaily.com/cleaning-slates-in-windows-the-3-reset-routes/"><u>Cleaning Slates in Windows: The 3 Reset Routes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-delving-into-discord-nitro-high-quality-features-and-how-to-obtain-them/"><u>[Updated] In 2024, Delving Into Discord Nitro - High-Quality Features & How to Obtain Them</u></a></li>
<li><a href="https://techidaily.com/solved-microsoft-excel-2019-file-error-the-document-cannot-be-saved-stellar-by-stellar-guide/"><u>Solved Microsoft Excel 2019 File Error The document cannot be saved | Stellar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/halo-series-screen-grabs-made-simple-for-2024/"><u>Halo Series Screen Grabs Made Simple for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-maximizing-visual-variety-with-b-roll-elements/"><u>2024 Approved  Maximizing Visual Variety with B Roll Elements</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-copy-paste-with-predefined-text-in-w10w11/"><u>Efficient Copy-Paste with Predefined Text in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-thumbnails-dimensions-on-desktop/"><u>Personalize Thumbnails: Dimensions on Desktop</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/inaugural-vision-preservation-review-and-alternate-suggestions-for-2024/"><u>Inaugural Vision Preservation Review & Alternate Suggestions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/five-keys-to-a-streamlined-firewall-configuration/"><u>Five Keys to a Streamlined Firewall Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/ultimate-watchlist-youtubes-greatest-hits-for-2024/"><u>Ultimate Watchlist  YouTube's Greatest Hits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/safeguarding-personal-info-with-nintendo-switch-accounts/"><u>Safeguarding Personal Info with Nintendo Switch Accounts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/incorporating-sound-effects-into-presentations-with-powerpoint-strategies-for-both-windows-and-apple-systems/"><u>Incorporating Sound Effects Into Presentations with PowerPoint Strategies for Both Windows and Apple Systems</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-dive-into-the-world-of-expertise-with-youtubes-top-10-makeup-vloggers-for-2024/"><u>[New] Dive Into the World of Expertise with YouTube's Top 10 Makeup Vloggers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-biometric-settings-of-w11-for-domains/"><u>Mastering the Biometric Settings of W11 for Domains</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-variability-between-offline-and-online-windows-installation-processes/"><u>Delving Into Variability Between Offline and Online Windows Installation Processes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-earning-potential-unveiled-youtube-adsense-earning-per-thousand-video-observations/"><u>[Updated] In 2024, Earning Potential Unveiled  YouTube AdSense Earning per Thousand Video Observations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-samsung-flow-linking-winpc-and-galaxy-device/"><u>Mastering Samsung Flow: Linking WinPC & Galaxy Device</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-startup-item-disappearance/"><u>Identifying & Fixing Startup Item Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-galaxy-performance-through-seamless-integration-in-windows-11/"><u>Optimizing Galaxy Performance Through Seamless Integration in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-sequential-image-storytelling-on-ig-for-2024/"><u>[New] Sequential Image Storytelling on IG for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-volume-adjustment-issues-in-windows-os/"><u>Mastering Volume Adjustment Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-11-shine-a-holiday-system-guide/"><u>Make Windows 11 Shine: A Holiday System Guide</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-console-collapse-avoiding-sudden-df-closures/"><u>Counteracting Console Collapse: Avoiding Sudden DF Closures</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-impact-do-widgets-streamline-win-11s-usage/"><u>Assessing the Impact: Do Widgets Streamline Win 11'S Usage?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-nine-essential-live-gaming-services-for-2024/"><u>Best Nine  Essential Live Gaming Services for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-seamless-content-propagation-beyond-youtube-and-facebook/"><u>[Updated] 2024 Approved  Seamless Content Propagation  Beyond YouTube and Facebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-ranked-choices-ideal-online-spots-for-grab-snapchat-ringtone/"><u>[New] High-Ranked Choices  Ideal Online Spots for Grab Snapchat Ringtone</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-everlasting-trash-can-icon-for-windows-1011/"><u>Crafting an Everlasting Trash Can Icon for Windows 10/11</u></a></li>
</ul></div>
