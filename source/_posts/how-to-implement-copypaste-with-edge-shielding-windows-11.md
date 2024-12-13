---
title: How to Implement Copy/Paste with Edge Shielding, Windows 11
date: 2024-12-07T08:14:39.348Z
updated: 2024-12-12T17:46:09.488Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Implement Copy/Paste with Edge Shielding, Windows 11
excerpt: This Article Describes How to Implement Copy/Paste with Edge Shielding, Windows 11
keywords: Edge Shield Paste Tech,Win11 SafeCopy Method,Copy Shield in Windows 11,SecurePasting Win11,EdgeGuard Paste Strategy,Protected Pasting Edge,Window Safeguard Copy
thumbnail: https://thmb.techidaily.com/b940b6b0f5ea7e32cad1821c53c7dd63eece1d15c1851d2a65f8ffeb1e28c4c2.jpg
---

## How to Implement Copy/Paste with Edge Shielding, Windows 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-elevating-visual-engagement-transferring-twitter-videos-on-snapchat-for-2024/"><u>[New] Elevating Visual Engagement Transferring Twitter Videos on Snapchat for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-cutting-edge-approaches-to-crafting-top-fb-cover-videos-for-2024/"><u>[Updated] Cutting-Edge Approaches to Crafting Top FB Cover Videos for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-refining-reality-close-up-creations-in-minecraft/"><u>[Updated] Refining Reality Close-Up Creations in Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-10-product-keys-for-optimal-pricing/"><u>Deciphering Windows 10 Product Keys for Optimal Pricing</u></a></li>
<li><a href="https://media-tips.techidaily.com/easy-steps-to-make-your-movies-compatible-with-psp-universal-video-conversion-tool/"><u>Easy Steps to Make Your Movies Compatible with PSP - Universal Video Conversion Tool</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-getting-winget-back-to-life-on-w11/"><u>Effective Techniques: Getting Winget Back to Life on W11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-strategies-quieting-down-background-programs/"><u>Essential Strategies: Quieting Down Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-password-safety-into-windows-file-systems/"><u>Integrating Password Safety Into Windows File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-overwatch-2-graphics-loss-on-windows/"><u>Quick Guide: Fixing Overwatch 2 Graphics Loss on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-troubleshooting-steps-for-windows-users-with-non-loading-firefox-pages/"><u>Top 7 Troubleshooting Steps for Windows Users With Non-Loading Firefox Pages</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-resolve-your-msstfmtdll-is-missing-error-today/"><u>Troubleshooting: Resolve Your 'msstfmt.dll Is Missing' Error Today</u></a></li>
<li><a href="https://fox-links.techidaily.com/twitch-vs-youtube-an-in-depth-comparative-analysis/"><u>Twitch Vs. YouTube An In-Depth Comparative Analysis</u></a></li>
</ul></div>

