---
title: "Secure Content Transfer: Enable Copy & Paste in Edge's Guardspace W11"
date: 2024-09-28T22:43:37.567Z
updated: 2024-10-03T19:38:35.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Content Transfer: Enable Copy & Paste in Edge's Guardspace W11"
excerpt: "This Article Describes Secure Content Transfer: Enable Copy & Paste in Edge's Guardspace W11"
keywords: Edge Guards Copy Secure,Secure Clippaste Edge,Safe Paste Guardspace,EdgeSpace Secure Transfer,ClipSecure EdgeGuard,W11 GuardedCopying,EdgeSafePastingW11
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Secure Content Transfer: Enable Copy & Paste in Edge's Guardspace W11

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
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902324/19272" target="_top" id="1902324">
  <img src="//a.impactradius-go.com/display-ad/19272-1902324" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902324/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-innovative-split-screen-videos-for-youtube-sharing/"><u>[New] Innovative Split-Screen Videos for YouTube Sharing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-making-an-impact-integrating-individual-thumbnails-in-videos/"><u>[New] Making an Impact Integrating Individual Thumbnails in Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-tips-to-navigate-the-world-of-free-iphoneipad-edits/"><u>[Updated] In 2024, Tips to Navigate the World of Free iPhone/iPad Edits</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-essence-of-uavs-understanding-their-mechanics-and-use/"><u>2024 Approved The Essence of UAVs Understanding Their Mechanics & Use</u></a></li>
<li><a href="https://techtrends.techidaily.com/expand-your-soundscape-simultaneously-connecting-multiple-bluetooth-audio-devices/"><u>Expand Your Soundscape: Simultaneously Connecting Multiple Bluetooth Audio Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-update-failure-error-code-0x80242016/"><u>Fixing Windows Update Failure: Error Code 0X80242016</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-12-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 12 Pro Max Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-cross-platform-iptv-capture/"><u>In 2024, Cross-Platform IPTV Capture</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-oppo-a1x-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Oppo A1x 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/installation-procedures-for-powertoys-in-win11/"><u>Installation Procedures for PowerToys in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-removal-on-windows-1011/"><u>Mastering Printer Removal on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-roblox-errors-demanding-shutdown/"><u>Resolving Windows Roblox Errors Demanding Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/seven-steps-to-unlocking-windows-11-memory-safety/"><u>Seven Steps to Unlocking Windows 11 Memory Safety</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-recover-missing-alerts-from-phone-link-app/"><u>Solutions to Recover Missing Alerts From Phone Link App</u></a></li>
<li><a href="https://win11.techidaily.com/top-priority-notes-techniques-for-enhanced-productivity-in-windows/"><u>Top Priority Notes Techniques for Enhanced Productivity in Windows</u></a></li>
</ul></div>

