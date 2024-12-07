---
title: Protocol for Activating Copy & Paste Features in Edge's Security Mode W11
date: 2024-12-01T00:22:48.307Z
updated: 2024-12-06T18:19:09.580Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Protocol for Activating Copy & Paste Features in Edge's Security Mode W11
excerpt: This Article Describes Protocol for Activating Copy & Paste Features in Edge's Security Mode W11
keywords: Edge Security Copy Activation,Edge W11 Paste Function,Edge Paste Enable Mode,Edge Security Copy Feature,Edge W11 Security Paste,Paste in Edge W11 Mode,Enabling Copy & Paste Edge 11
thumbnail: https://thmb.techidaily.com/07d8502ce17333e6cd775d39369b0980ba5462f8a32cd1145e8a4d708fb6bf52.png
---

## Protocol for Activating Copy & Paste Features in Edge's Security Mode W11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-unlocking-home-design-potential-in-minecraft/"><u>[Updated] In 2024, Unlocking Home Design Potential in Minecraft</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-expanding-minds-virtualizing-classrooms/"><u>2024 Approved Expanding Minds, Virtualizing Classrooms</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-huawei-nova-y91-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Huawei Nova Y91 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/clean-slate-deleting-ps5-login-details/"><u>Clean Slate: Deleting PS5 Login Details</u></a></li>
<li><a href="https://discover-able.techidaily.com/displaying-mobi-book-formats-on-your-kindle-fire-device-a-comprehensive-guide/"><u>Displaying MOBI Book Formats on Your Kindle Fire Device – A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-fn-key-usage-in-windows-1011-pcs/"><u>Enhancing FN Key Usage in Windows 10/11 PCs</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-capturing-brilliance-essential-angles-in-iphone-photography/"><u>In 2024, Capturing Brilliance Essential Angles in iPhone Photography</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-past-no-start-virtual-machines-in-vmwarewin11/"><u>Navigate Past No-Start Virtual Machines in VMware/Win11</u></a></li>
<li><a href="https://solve-lab.techidaily.com/quick-and-simple-guide-how-to-change-your-kobo-ebooks-into-pdf-format/"><u>Quick & Simple Guide: How To Change Your Kobo eBooks Into PDF Format</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-order-to-mouse-wheels-on-pcs/"><u>Restoring Order to Mouse Wheels on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-ps4-remote-with-a-stable-win-based-link/"><u>Reviving Your PS4 Remote with a Stable Win-Based Link</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-process-of-activating-system-restore-in-windows-11/"><u>Simplifying the Process of Activating System Restore in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-correcting-ps4-network-address-translation-errors/"><u>Step-by-Step Solutions for Correcting PS4 Network Address Translation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-recovering-from-outlook-crashes/"><u>The Complete Guide to Recovering From Outlook Crashes</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-picks-for-your-pc-build-insights-from-toms-hardware-experts/"><u>Top Picks for Your PC Build: Insights From Tom's Hardware Experts</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-playnite-adopting-emulated-game-titles/"><u>Transforming Playnite: Adopting Emulated Game Titles</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-restoring-original-input-layout-on-windows-11-pcs/"><u>Tutorial: Restoring Original Input Layout on Windows 11 PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-xiaomi-redmi-a2-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Xiaomi Redmi A2 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-lost-screens-reopen-windows-10-and-11-effortlessly/"><u>Unearthing Lost Screens: Reopen Windows 10 & 11 Effortlessly</u></a></li>
</ul></div>

