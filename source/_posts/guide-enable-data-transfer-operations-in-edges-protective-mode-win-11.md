---
title: "Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
date: 2024-06-25T09:57:29.686Z
updated: 2024-06-26T09:57:29.686Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
excerpt: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
keywords: Edge Security Guide,Win11 Protective Mode,Data Transfer Operations,Edge Mode Settings,Enable Data Share,Win11 Networking,Edge Secure Transfer
thumbnail: https://thmb.techidaily.com/4db798dc8e85e2daadf391573bc5ef81d7d7a8b53e675ec2733be93146fbbb0f.jpg
---

## Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
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
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

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
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-firewall-4-methods-explored/"><u>Bypassing Disabled Windows Firewall: 4 Methods Explored</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-elevate-your-virtual-presentations-with-zoom-sharing/"><u>2024 Approved  Elevate Your Virtual Presentations with Zoom Sharing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-websites-unveiled-where-you-grab-your-ringtone-favorites/"><u>[New] 2024 Approved  Websites Unveiled  Where You Grab Your Ringtone Favorites</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-lava-yuva-2-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Lava Yuva 2 Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-pixel-pandemonium-ranking-the-funniest-tiktok-game-screencaps-for-2024/"><u>[New] Pixel Pandemonium  Ranking the Funniest TikTok Game Screencaps for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-vistas-backgrounds-boosting-live-quality/"><u>In 2024, Best Vistas  Backgrounds Boosting Live Quality</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-realme-11-pro-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/10-highest-performing-business-youtube-platforms-explained/"><u>10 Highest Performing Business YouTube Platforms Explained</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-list-of-android-compatible-multitrack-digital-recorders/"><u>Updated The Ultimate List of Android-Compatible Multitrack Digital Recorders</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-top-20-youtube-friendly-facebook-video-editors/"><u>[Updated] Top 20 YouTube-Friendly Facebook Video Editors</u></a></li>
</ul></div>
