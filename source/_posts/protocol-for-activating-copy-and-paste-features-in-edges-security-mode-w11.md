---
title: Protocol for Activating Copy & Paste Features in Edge's Security Mode W11
date: 2024-11-22T03:34:27.432Z
updated: 2024-11-28T04:29:55.067Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-loop-youtube-videos-on-tv/"><u>[New] In 2024, How to Loop YouTube Videos on TV</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-your-youtube-presence-filmmaking-with-filmora/"><u>2024 Approved Elevate Your YouTube Presence Filmmaking with Filmora</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-enhance-your-videos-with-dynamic-camera-movements-camtasa-guide/"><u>2024 Approved Enhance Your Videos with Dynamic Camera Movements - Camtasa Guide</u></a></li>
<li><a href="https://win11.techidaily.com/digital-artistic-solutions-like-procreate-for-windows/"><u>Digital Artistic Solutions Like Procreate For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ease-of-disk-management-access-on-win-1011/"><u>Discover the Ease of Disk Management Access on Win 10/11</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-update-guide-for-hp-officejet-pro-asterisk-8610-driver-on-windows-os-7-vista-xp-8-and-10/"><u>Download & Update Guide for HP Officejet Pro Asterisk 8610 Driver on Windows OS (7, Vista, XP, 8, and 10)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-xiaomi-redmi-13c-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Xiaomi Redmi 13C Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adjust-administrative-controlled-options-in-windows-11-os/"><u>How to Adjust Administrative Controlled Options in Windows 11 OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-proven-tactics-increasing-your-instagram-video-traffic/"><u>In 2024, Proven Tactics Increasing Your Instagram Video Traffic</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-facebook-messages-overcoming-window-snags/"><u>Mastering Facebook Messages: Overcoming Window Snags</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-tool-accessibility-settings/"><u>Mastering Windows 11'S Tool Accessibility Settings</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pathways-to-windows-performance-reports/"><u>Quick Pathways to Windows Performance Reports</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-scripture-melodies-on-your-phone-for-2024/"><u>Step-by-Step Scripture Melodies on Your Phone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/thaw-frozen-handbrake-on-windows/"><u>Thaw Frozen HandBrake on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-essential-qanda-on-quantum-hdr-technology/"><u>The Essential Q&A on Quantum HDR Technology</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-meizu-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Meizu</u></a></li>
<li><a href="https://win11.techidaily.com/workspace-efficiency-attach-gmail-to-desktop-border/"><u>Workspace Efficiency: Attach Gmail to Desktop Border</u></a></li>
</ul></div>

