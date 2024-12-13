---
title: Guide to Implement Clipboard Operations Within Edge's Protective Zone on Windows 11
date: 2024-12-06T09:52:45.880Z
updated: 2024-12-12T23:03:18.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Implement Clipboard Operations Within Edge's Protective Zone on Windows 11
excerpt: This Article Describes Guide to Implement Clipboard Operations Within Edge's Protective Zone on Windows 11
keywords: EdgeClipboardProtection,EdgeZoneOperations,Win11ClipboardGuide,ClipboardEdgeTips,ZoneDefenseWindows,Windows11Security,ProtectiveEdgeUse
thumbnail: https://thmb.techidaily.com/b3b1cb7d8c5c52c25843bc952abd6a00ab0cd811cafc15697aa0c13fd607a950.jpg
---

## Guide to Implement Clipboard Operations Within Edge's Protective Zone on Windows 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-ignite-views-effective-strategies-for-optimizing-youtube-collaborations/"><u>[Updated] Ignite Views Effective Strategies for Optimizing YouTube Collaborations</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-unveiling-the-power-of-vivacut/"><u>[Updated] Unveiling the Power of VivaCut</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-digital-realms-downloadable-alarm-melodies/"><u>2024 Approved Best Digital Realms Downloadable Alarm Melodies</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722960759788-get-the-latest-upgrade-for-your-dymo-4xl-label-printer-today/"><u>Get the Latest Upgrade for Your DYMO 4XL Label Printer Today</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-realme-v30t-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Realme V30T Without Password | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/leap-into-the-new-era-with-ios-15/"><u>Leap Into the New Era with iOS 15</u></a></li>
<li><a href="https://blog-min.techidaily.com/lossless-transformation-converting-hevc-files-into-high-quality-mp4-formats/"><u>Lossless Transformation: Converting HEVC Files Into High-Quality MP4 Formats</u></a></li>
<li><a href="https://discover-able.techidaily.com/multi-platform-directv-recording-tutorial-capture-content-easily-on-pcs-phones-and-televisions/"><u>Multi-Platform DirecTV Recording Tutorial: Capture Content Easily on PCs, Phones, and Televisions</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-stuttering-displays-in-windows-devices/"><u>Resolving Stuttering Displays in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-silence-in-computers-audio-output/"><u>Revitalize Silence in Computer's Audio Output</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-frozen-screensaver-options-on-pc-windows/"><u>Revitalizing Frozen Screensaver Options on PC Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-printer-unreachable-error-on-windows-11/"><u>Steps to Correct 'Printer Unreachable' Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rejuvenate-non-responding-windows-download-folder/"><u>Steps to Rejuvenate Non-Responding Windows Download Folder</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-linux-system-installing-intel-wi-fi-drivers/"><u>Streamlining Your Linux System: Installing Intel Wi-Fi Drivers</u></a></li>
<li><a href="https://win-unique.techidaily.com/top-rated-alavsoft-udemy-app-compatible-with-mac-and-windows-11-8-7-vista-learn-anytime/"><u>Top Rated Alavsoft Udemy App Compatible with MAC & WINDOWS 11, 8, 7, Vista: Learn Anytime!</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-dxgierror-device-disconnected/"><u>Troubleshooting DXGI_Error: Device Disconnected</u></a></li>
</ul></div>

