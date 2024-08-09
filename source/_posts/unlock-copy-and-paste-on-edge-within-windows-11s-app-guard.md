---
title: Unlock Copy & Paste on Edge Within Windows 11'S App Guard
date: 2024-08-08T13:17:02.042Z
updated: 2024-08-09T13:17:02.042Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Copy & Paste on Edge Within Windows 11'S App Guard
excerpt: This Article Describes Unlock Copy & Paste on Edge Within Windows 11'S App Guard
keywords: Unlock C&P Edge Security,Navigate Ctrl+C/V Edge,Bypass Edge APG Lock,Enable Copy on Windows 11,Edge's App Guard Bypass,Access Paste in Edge 11,Override APG Copy Feature
thumbnail: https://thmb.techidaily.com/f61e0cf06b5f94c52331e7280bfea34d0fc7a11feee31daa0334519a989e1892.jpg
---

## Unlock Copy & Paste on Edge Within Windows 11'S App Guard

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-recording-realities-evaluating-the-power-and-precision-of-apeaksoftware/"><u>[New] In 2024, Recording Realities – Evaluating the Power and Precision of Apeaksoftware</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-strategic-guide-to-unlocking-worlds-secrets-via-vr/"><u>[Updated] A Strategic Guide to Unlocking World's Secrets via VR</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhance-audience-reach-share-twitch-videos-on-facebook/"><u>[Updated] Enhance Audience Reach  Share Twitch Videos on Facebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-a-list-nintendo-switch-fighter-titles-max-156/"><u>[Updated] In 2024, A-List Nintendo Switch Fighter Titles (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/30-minute-guide-to-resolving-windows-onedrive-fails/"><u>30 Minute Guide to Resolving Windows OneDrive Fails</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-poco-x5-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Poco X5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-derek-walsh-phd-dr-jeffrey-l-gardiner-phd-and-david-c-muller-phd-from-their-book-understanding-the-psychology-of-religion-exploring-god-33/"><u>A Compre Written by Derek Walsh, PhD; Dr. Jeffrey L. Gardiner, PhD; and David C. Muller, PhD; From Their Book Understanding the Psychology of Religion: Exploring God Wise</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenhensive-guide-to-windows-graphics-reset-techniques/"><u>A Compreenhensive Guide to Windows Graphics Reset Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/activating-and-deactivating-the-essential-windows-key/"><u>Activating & Deactivating the Essential Windows Key</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-sevenzeronine-in-windows/"><u>Addressing Error SevenZeroNine in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-windows-programs-a-fixers-manual/"><u>Addressing Inoperative Windows Programs: A Fixer’s Manual</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-xbox-apps-audio-challenges-in-windows-1011/"><u>Addressing Xbox App's Audio Challenges in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-login-failure-threshold-step-by-step-for-windows-11-users/"><u>Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-quick-access-for-file-explorer-through-onedrive/"><u>Adjusting Quick Access for File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-with-11-troubleshooting-windows-tips/"><u>Avoid Frustration with 11 Troubleshooting Windows Tips</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-conflict-over-shared-device-camera-error-0xa00f4243/"><u>Avoiding Conflict Over Shared Device (Camera, Error 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-speed-implementing-a-smart-enhanced-run-feature/"><u>Boosting System Speed: Implementing a Smart Enhanced Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://win11.techidaily.com/1719301836134-clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now!</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/engage-in-authentic-conversations-anywhere-mondly-vr-for-language-mastery/"><u>Engage in Authentic Conversations Anywhere - Mondly VR for Language Mastery</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-teleport-your-gps-location-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-nokia-c02-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Nokia C02 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-oppo-a79-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Oppo A79 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-apple-iphone-14-pro-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass Apple iPhone 14 Pro Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-samsung-galaxy-z-flip-5-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Samsung Galaxy Z Flip 5 Phone</u></a></li>
<li><a href="https://win-answers.techidaily.com/tackling-the-issue-of-prolonged-boot-time-for-fallout-4-gamers/"><u>Tackling the Issue of Prolonged Boot Time for Fallout 4 Gamers</u></a></li>
</ul></div>
