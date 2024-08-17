---
title: Activate/Deactivate Fingerwriting in Windows System
date: 2024-08-15T23:20:22.406Z
updated: 2024-08-16T23:20:22.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate/Deactivate Fingerwriting in Windows System
excerpt: This Article Describes Activate/Deactivate Fingerwriting in Windows System
keywords: Activate Fingerwriting,Deactivate Fingerwriting,Windows Fingerwriting Control,Enable Handwriting on PC,Disable Windows Handwriting,Windows System Writing Feature,Handwriting Function in Windows
thumbnail: https://thmb.techidaily.com/bcabaab591bfcab705d7b78fa9328071af132a2f5e82388216c0b539cc0ef7e4.jpg
---

## Activate/Deactivate Fingerwriting in Windows System

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-blitz-photo-screening-for-windows-users/"><u>[New] 2024 Approved  Blitz Photo Screening for Windows Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-blueprint-making-inspiring-lifestyle-broadcasts-for-2024/"><u>[New] Blueprint  Making Inspiring Lifestyle Broadcasts for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-boosting-engagement-profits-with-animated-ad-success-tactics-on-fb-for-2024/"><u>[New] Boosting Engagement, Profits with Animated Ad Success Tactics on FB for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-innovations-for-elevating-your-gopro-filmmaking-skills/"><u>[New] In 2024, Innovations for Elevating Your GoPro Filmmaking Skills</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-navigating-through-video-post-errors-on-iphoneandroid-fb-chat-platform/"><u>[New] In 2024, Navigating Through Video Post Errors on iPhone/Android FB Chat Platform</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-making-moolah-the-snapchat-way/"><u>[New] Making Moolah  The Snapchat Way</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-pixie-dust-game-hours-childrens-choice-edition/"><u>[Updated] 2024 Approved  Pixie-Dust Game Hours - Children's Choice Edition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-unlock-potential-the-15-best-tools-for-transforming-fb-revenue/"><u>[Updated] 2024 Approved  Unlock Potential  The 15 Best Tools for Transforming FB Revenue</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-basic-gamers-guide-to-outstanding-video-editing-software-for-2024/"><u>[Updated] Basic Gamers' Guide to Outstanding Video Editing Software for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-best-yoga-series-online-stay-active-and-healthy/"><u>[Updated] Best Yoga Series Online - Stay Active & Healthy</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-effortless-multichannel-publishing-tweets-plus-tumbles/"><u>[Updated] Effortless Multichannel Publishing  Tweets + Tumbles</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-game-recording-mastery-utilizing-gameye-and-more/"><u>[Updated] Game Recording Mastery  Utilizing GamEye and More</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-channel-hunt-best-historical-youtubes-that-every-student-should-watch/"><u>[Updated] In 2024, Channel Hunt  Best Historical YouTubes That Every Student Should Watch</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-system-information-tool-on-windows/"><u>10 Ways to Open the System Information Tool on Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-capture-live-conversations-google-meet-on-phones/"><u>2024 Approved  Capture Live Conversations  Google Meet on Phones</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-record-to-remember-top-5-best-tools-for-virtual-meeting-capture/"><u>2024 Approved  Record to Remember  Top 5 Best Tools for Virtual Meeting Capture</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-5-best-value-camcorders-for-sports-and-stunts/"><u>2024 Approved  Top 5 Best Value Camcorders for Sports and Stunts</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-transforming-storytelling-into-cinematic-art/"><u>2024 Approved  Transforming Storytelling Into Cinematic Art</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/androids-ultimate-guide-to-best-wildlife-games/"><u>Android's Ultimate Guide to Best Wildlife Games</u></a></li>
<li><a href="https://techtrends.techidaily.com/captivating-and-trending-the-best-507-instagram-captions-to-use/"><u>Captivating and Trending: The Best 507 Instagram Captions to Use</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-cleaner-windows-11-desktop-layout/"><u>Designing a Cleaner Windows 11 Desktop Layout</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-organize-your-pcenas-7-prime-windows-photos-tools/"><u>Effortlessly Organize Your PC'enas: 7 Prime Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-windows-selection-of-best-nintendo-switch-imitators/"><u>Exclusive Windows Selection of Best Nintendo Switch Imitators</u></a></li>
<li><a href="https://youtube-help.techidaily.com/graph-gems-2017s-statistical-youtube-surprises-for-2024/"><u>Graph Gems  2017'S Statistical YouTube Surprises for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-an-overheating-windows-laptop-when-gaming/"><u>How to Fix an Overheating Windows Laptop When Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-a-step-by-step-guide-to-mastering-magix-video-pro-x/"><u>In 2024, A Step-by-Step Guide to Mastering Magix Video Pro X</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-audience-anticipation-crafting-captivating-video-content-on-social-media/"><u>In 2024, Audience Anticipation  Crafting Captivating Video Content on Social Media</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-m34-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy M34 5G</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-scaling-up-your-income-with-instagram-mastery/"><u>In 2024, Scaling Up Your Income with Instagram Mastery</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-ultimate-guide-to-ipad-time-lapse-filmmaking/"><u>In 2024, The Ultimate Guide to iPad Time-Lapse Filmmaking</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-on-mac-via-parallels/"><u>Mastering Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-reviving-copy-paste-feature-across-browsers/"><u>Quick Guide: Reviving Copy-Paste Feature Across Browsers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/ranking-the-ultimate-vr-fun-on-mobile-devices-for-2024/"><u>Ranking the Ultimate VR Fun on Mobile Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-display-technology-an-in-depth-exploration-of-windows-11s-hdr/"><u>Reimagining Display Technology: An In-Depth Exploration of Windows 11'S HDR</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-prime-audiosubtitle-malfunctions-on-windows-11-systems/"><u>Resolve Prime Audio/Subtitle Malfunctions on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-windows-audioscape-via-driver-update-steps/"><u>Revamping Windows Audioscape via Driver Update Steps</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-1110s-d3d11-gpu-woes-to-fixable-errors/"><u>Simplifying Windows 11/10'S D3D11 GPU Woes to Fixable Errors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/sims-chronicles-unplugged-innovative-techniques-to-recording-without-reliance-on-video-for-2024/"><u>Sims Chronicles Unplugged  Innovative Techniques to Recording Without Reliance on Video for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smart-zooms-on-snapchat-enhance-photo-and-video-quality-for-2024/"><u>Smart Zooms on Snapchat  Enhance Photo & Video Quality for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/solve-the-shadowy-surface-of-lenovo-portable/"><u>Solve the Shadowy Surface of Lenovo Portable</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-alter-mouse-trail-and-size-on-win11/"><u>Step-by-Step: Alter Mouse Trail & Size on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rejuvenating-stuck-windows-based-itunes/"><u>Strategies for Rejuvenating Stuck Windows-Based iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/inancial-frontier-youtubes-pay-structure-at-the-1m-mark/"><u>The Financial Frontier  Youtube's Pay Structure at the 1M Mark</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-pc-mysteries-a-step-by-step-guide-to-error-code-management-in-command-prompt/"><u>Unraveling PC Mysteries: A Step-by-Step Guide to Error Code Management in Command Prompt</u></a></li>
</ul></div>
