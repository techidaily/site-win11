---
title: "Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
date: 2024-12-04T10:18:48.614Z
updated: 2024-12-07T08:59:08.666Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
excerpt: "This Article Describes Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
keywords: Win11 EdgeAppGuard ContentTransfer,Activate EdAppGuard Shielding,Enable Windows 11 TransferMode,TurnOn AppGuard Mode Shield,StepWin11 ContentTransferShield,Initiate Shielded EdgeContent,StartEdgeGuard Transfers
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

## Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook.techidaily.com/ethereum-explorer-facebook-ceos-curious-goat-nickname/"><u>'Ethereum Explorer': Facebook CEO's Curious Goat Nickname.</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-elevate-your-videos-discoverability-mastering-tags/"><u>[New] In 2024, Elevate Your Video's Discoverability - Mastering Tags</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastering-live-broadcasts-a-step-by-step-guide-for-fb-users/"><u>[New] In 2024, Mastering Live Broadcasts A Step-by-Step Guide for FB Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-perfecting-sound-integrating-music-into-vimeo-video-projects/"><u>[New] Perfecting Sound Integrating Music Into Vimeo Video Projects</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-vr-liftoff-top-peripherals-and-their-impacts/"><u>[Updated] In 2024, VR Liftoff - Top Peripherals & Their Impacts</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-optimizing-profits-on-youtube-studio-for-all-device-users/"><u>2024 Approved Optimizing Profits on YouTube Studio for All-Device Users</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-untapped-capabilities-in-windows-monitors/"><u>Deciphering Untapped Capabilities in Windows Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-defenders-historical-data-clean-secure-windows-pcs/"><u>Eliminate Defender's Historical Data - Clean, Secure Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-reconnecting-steam-to-online-content-servers/"><u>Guidelines for Reconnecting Steam to Online Content Servers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-the-duration-of-windows-11-shutdown-during-running-operations/"><u>How to Extend the Duration of Windows 11 Shutdown During Running Operations</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-v30-lite-5g-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted V30 Lite 5G Contacts An Easy Method Explained.</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-poms-the-ultimate-list-of-winning-timers/"><u>Mastering Poms: The Ultimate List of Winning Timers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-for-windows-blue-screen-0x8007007e/"><u>Mastering the Fix for Windows Blue Screen 0X8007007E</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-easy-instructions-to-download-and-update-epson-et-3760-printer-software-for-microsoft-windows/"><u>Quick & Easy Instructions to Download & Update Epson ET-3760 Printer Software for Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-precision-in-your-presentations-prints-9-steps-with-powerpoint-and-pcs/"><u>Securing Precision in Your Presentations' Prints: 9 Steps with PowerPoint & PCs</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-lsa-failure-causes-fixes-for-windows/"><u>Understanding LSA Failure Causes, Fixes for Windows</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/unveiling-of-microsofts-windows-11-se-and-affordable-250-surface-laptop-se-targeting-educators-zdnet-update/"><u>Unveiling of Microsoft's Windows 11 SE and Affordable $250 Surface Laptop SE Targeting Educators – ZDNet Update</u></a></li>
</ul></div>

