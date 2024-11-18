---
title: Steps to Activate Clipboard Features with Shielded Applications (Edge) on W11 Platform
date: 2024-11-10T17:48:17.663Z
updated: 2024-11-17T20:28:44.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Activate Clipboard Features with Shielded Applications (Edge) on W11 Platform
excerpt: This Article Describes Steps to Activate Clipboard Features with Shielded Applications (Edge) on W11 Platform
keywords: Edge Clipboard Enable,W11 Clipboard Step-by-Step,Activate Edge Save Feature,Shielded Apps Clipboard Use,Windows W11 Clipboard Hack,Accessing Clipboard in Edge,Enable Clipboard on W11
thumbnail: https://thmb.techidaily.com/05054cfe506491b99a35f8cf834debaebdbdb9bad3863dd1f8be14d01cc17569.jpg
---

## Steps to Activate Clipboard Features with Shielded Applications (Edge) on W11 Platform

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
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-deciphering-high-speed-video-with-yi-4k/"><u>[Updated] 2024 Approved Deciphering High-Speed Video with Yi 4K</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-the-year-2024-how-to-follow-sourav-joshi-on-youtube-income/"><u>[Updated] In the Year 2024, How to Follow Sourav Joshi on YouTube Income</u></a></li>
<li><a href="https://extra-hints.techidaily.com/harmonious-blends-using-fades-in-logic-pro-x/"><u>Harmonious Blends Using Fades in Logic Pro X</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-nubia-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Nubia Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/lower-lag-higher-frames-optimizing-your-roblox-experience/"><u>Lower Lag, Higher Frames: Optimizing Your Roblox Experience</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-computer-gear-with-tom-in-depth-reviews-from-toms-hardware-experts/"><u>Navigating Computer Gear with Tom: In-Depth Reviews From Tom's Hardware Experts</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/new-data-usage-provisions-explanation/"><u>New Data Usage Provisions Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-after-print-management-failure-on-windows/"><u>Restoring Functionality After Print Management Failure on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/skip-power-saving-customize-usb-suspend-settings/"><u>Skip Power Saving: Customize USB Suspend Settings</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-removing-unwanted-applications-from-your-samsung-smart-tv/"><u>Ultimate Guide: Removing Unwanted Applications From Your Samsung Smart TV</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-to-full-os-install-windows-steam-deck/"><u>Upgrading to Full OS: Install Windows Steam Deck</u></a></li>
<li><a href="https://extra-resources.techidaily.com/wheres-the-community-twitch-and-youtube-side-by-side/"><u>Where's the Community? Twitch & YouTube Side by Side</u></a></li>
</ul></div>

