---
title: Reinstating Absent CPU Cooling Directive in OS
date: 2024-08-08T13:22:12.371Z
updated: 2024-08-09T13:22:12.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Absent CPU Cooling Directive in OS
excerpt: This Article Describes Reinstating Absent CPU Cooling Directive in OS
keywords: CPU Cooling Directive Restore,OS CPU Directives Reissue,Restore OS CPU Cooling Rule,Enhancing OS CPU Temp Regulation,Reinstating OS Temperature Control,Directive Revival for CPU Cooling,OS Thermal Management Update
thumbnail: https://thmb.techidaily.com/860b3898b4af7e1c1dc6c593b5d2eb5997c8c8e6aad583a53288672db7b6ce02.jpg
---

## Reinstating Absent CPU Cooling Directive in OS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-ultimate-list-of-influential-biz-channels-online/"><u>[New] 2024 Approved  The Ultimate List of Influential Biz Channels Online</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-captivating-creatives-an-audience-centric-compilation-of-the-best-20-tiktok-captions-for-2024/"><u>[New] Captivating Creatives  An Audience-Centric Compilation of the Best 20 TikTok Captions for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-navigating-twitter-video-content-flow-to-facebook-for-2024/"><u>[New] Navigating Twitter Video Content Flow to Facebook for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-methods-to-speed-up-or-slow-down-songs-on-spotify/"><u>[New] Prime Methods to Speed Up or Slow Down Songs on Spotify</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-top-10-pc-vr-headsets/"><u>[New] Top 10 PC VR Headsets</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-breaking-down-the-fundamentals-of-mixed-reality/"><u>[Updated] Breaking Down the Fundamentals of Mixed Reality</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-music-mastery-essentials-high-quality-dj-video-samples/"><u>[Updated] Music Mastery Essentials  High-Quality DJ Video Samples</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-promoting-dialogue-enriching-conversations-in-the-youtube-community/"><u>[Updated] Promoting Dialogue  Enriching Conversations in the YouTube Community</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-quick-guide-iphones-easiest-screen-recording-method/"><u>[Updated] Quick Guide  IPhone's Easiest Screen Recording Method</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-digital-dynamos-youtubes-most-watched-videos-in-a-day/"><u>2024 Approved  Digital Dynamos  YouTube’s Most-Watched Videos in a Day</u></a></li>
<li><a href="https://win11.techidaily.com/breach-the-barrier-opening-credential-store/"><u>Breach the Barrier: Opening Credential Store</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-realme-12plus-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Realme 12+ 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-device-health-check-up-the-ultimate-guide-for-windows-11s-uptime/"><u>Dive Into Device Health Check-Up: The Ultimate Guide for Windows 11'S Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-operators-invisible-input-on-windows/"><u>Elusive Operators: Invisible Input on Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/exposed-the-hazards-of-fake-follower-purchases-on-youtube-for-2024/"><u>Exposed  The Hazards of Fake Follower Purchases on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-to-status-bar-windows-taskbar-chronology/"><u>From Start to Status Bar: Windows Taskbar Chronology</u></a></li>
<li><a href="https://win11.techidaily.com/how-are-c-and-d-drive-identities-unique/"><u>How Are C: And D: Drive Identities Unique?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-defender-antivirus-blockage/"><u>How to Bypass Windows Defender Antivirus Blockage</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-scaling-issues-for-high-dpi-screens/"><u>How to Fix Windows Scaling Issues for High DPI Screens</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-itel-p55plus-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Itel P55+ Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-effective-practices-for-device-video-capture/"><u>In 2024, Effective Practices for Device Video Capture</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-maximizing-efficiency-in-remote-group-meetings/"><u>In 2024, Maximizing Efficiency in Remote Group Meetings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-huawei-nova-y91-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Huawei Nova Y91 Device</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-foundations-of-building-your-twitter-profile/"><u>In 2024, The Foundations of Building Your Twitter Profile</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-ipad-for-time-lapse-cinematography-for-2024/"><u>Mastering iPad for Time-Lapse Cinematography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/reliability-monitor-vs-performance-monitor-comparing-two-underutilized-windows-tools/"><u>Reliability Monitor Vs. Performance Monitor: Comparing Two Underutilized Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-interruptexceptionnothandled-in-w11-bsods/"><u>Resolving INTERRUPT_EXCEPTION_NOT_HANDLED in W11 BSODs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-speakers-not-detected-issue/"><u>Resolving Windows: Speakers Not Detected Issue</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-lost-connection-fixes-for-wifi-failures-in-win11/"><u>Reviving Your Lost Connection: Fixes for Wifi Failures in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719378810676-shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-mitigate-winerror-0x80780119/"><u>Strategies to Mitigate WinError 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-microsoft-store-use-in-windows-11/"><u>Streamlining Microsoft Store Use in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/studio-2-unleashed-microsofts-near-perfect-creator-tool/"><u>Studio 2 Unleashed: Microsoft's Near-Perfect Creator Tool</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-disassembling-dism-for-image-recovery/"><u>The Art of Disassembling Dism for Image Recovery</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-art-of-leading-lines-crafting-images-on-iphones/"><u>The Art of Leading Lines  Crafting Images on iPhones</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-guide-to-founding-an-indie-review-platform-for-fashion-and-apparel-for-2024/"><u>The Ultimate Guide to Founding an Indie Review Platform for Fashion and Apparel for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-10-ae-text-styles-guide/"><u>Top 10 AE Text Styles Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-installation-sites-for-pc-apps-on-windows/"><u>Tracing Installation Sites for PC Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-eternal-delete-with-a-customized-windows-trash-bin-setup-11/"><u>Unleash Eternal Delete with a Customized Windows Trash Bin Setup (11)</u></a></li>
</ul></div>
