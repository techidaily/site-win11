---
title: Restoring Missing Thermal Policy in Windows Environment
date: 2024-07-29T15:48:51.487Z
updated: 2024-07-30T15:48:51.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Missing Thermal Policy in Windows Environment
excerpt: This Article Describes Restoring Missing Thermal Policy in Windows Environment
keywords: Thermal Policy Restore,Windows Heat Settings,Policy Policy Revival,Thermal Management Fix,Window Temperature Control,Policies Recovery Guide,System Temp Regulation
thumbnail: https://thmb.techidaily.com/29d02750ad0cb057d82cf1dca19da27d5429074e0ee73dae3abc4f97673bc3bc.jpg
---

## Restoring Missing Thermal Policy in Windows Environment

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-harnessing-skypes-voice-free-mp3-exclusive/"><u>[New] 2024 Approved  Harnessing Skype's Voice - Free MP3 Exclusive</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-preferred-speech-to-text-ipad-apps-3/"><u>[New] 2024 Approved  Preferred Speech-to-Text iPad Apps #3</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-crafting-professional-visual-narratives-with-lut-usage-in-premiere/"><u>[New] Crafting Professional Visual Narratives with LUT Usage in Premiere</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-game-changing-homes-in-blocktown/"><u>[New] In 2024, Game Changing Homes in Blocktown</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-symphony-of-screenshots-incorinas-music-into-social-media-for-2024/"><u>[New] Symphony of Screenshots  Incorinas Music Into Social Media for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-essentials-of-webcam-capture-with-free2x-app/"><u>[New] The Essentials of WebCam Capture with Free2X App</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-tasteful-tactics-elevating-culinary-channel-monikers/"><u>[Updated] Tasteful Tactics  Elevating Culinary Channel Monikers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-windows-10s-premier-choice-of-video-grabber-software/"><u>[Updated] Windows 10'S Premier Choice of Video Grabber Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-podcast-apps-for-android/"><u>2024 Approved  Best Podcast Apps for Android</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-optimize-space-compelling-selection-of-20-top-free-cloud-storages-up-to-1tb/"><u>2024 Approved  Optimize Space  Compelling Selection of 20 Top FREE Cloud Storages (Up To 1TB)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-simplify-with-top-10-free-mac-tools-for-screen-recording/"><u>2024 Approved  Simplify with Top 10 Free Mac Tools for Screen Recording</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-unlocking-the-power-of-pages-top-10-social-media-optimization-tactics/"><u>2024 Approved  Unlocking the Power of Pages  Top 10 Social Media Optimization Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/a-systematic-approach-to-rejuvenating-your-media-software/"><u>A Systematic Approach to Rejuvenating Your Media Software</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-optimize-windows-powershell-script-policies/"><u>Activate and Optimize Windows PowerShell Script Policies</u></a></li>
<li><a href="https://fox-glue.techidaily.com/best-script-artisans-domain/"><u>Best Script Artisan's Domain</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhancing-click-through-high-roi-strategies-for-fb-animatons/"><u>Enhancing Click-Through  High-ROI Strategies for FB Animatons</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-eradicate-fluctuating-display-on-windows-1011/"><u>Expert Tips to Eradicate Fluctuating Display on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/freezing-wi-fi-mouse-how-to-reset-and-restore-functionality-in-windows/"><u>Freezing Wi-Fi Mouse? How to Reset and Restore Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-win1011-screen-flicker/"><u>How to Quickly Resolve WIN10/11 Screen Flicker</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-honor-x9b-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Honor X9b to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-through-the-looking-glass-decoding-the-secrets-to-a-superior-windows-11-experience/"><u>In 2024, Through the Looking Glass  Decoding the Secrets to a Superior Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-2024-approved-the-top-6-alternatives-to-twitch-for-your-streaming-needs/"><u>New 2024 Approved The Top 6 Alternatives to Twitch for Your Streaming Needs</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-free-and-paid-imovie-alternatives-for-windows-10-a-comprehensive-guide/"><u>New In 2024, Free and Paid iMovie Alternatives for Windows 10 A Comprehensive Guide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-mts-video-editor-reviews-top-5-options-compared/"><u>New MTS Video Editor Reviews Top 5 Options Compared</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-failure-codes/"><u>Overcoming Windows 10/11 Failure Codes</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-vivo-s18-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Vivo S18 Device</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
</ul></div>
