---
title: Steps to Activate Clipboard Usage in Windows 11 Edge Security
date: 2024-11-11T00:34:21.558Z
updated: 2024-11-18T02:14:58.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Activate Clipboard Usage in Windows 11 Edge Security
excerpt: This Article Describes Steps to Activate Clipboard Usage in Windows 11 Edge Security
keywords: Clipboard Edge Security,Enable Clipboard Securely,Activate Windows Clipboard,Clipboard Usage Guide (Win 11),Edge Security Key Steps,Secure Clipboard Windows 11,Activate Clipboard Windows 11
thumbnail: https://thmb.techidaily.com/5f63ba1e3593ebd7d73d1c72fb68eace0cd63a5c8a537d585a504e6de4ee75de.jpg
---

## Steps to Activate Clipboard Usage in Windows 11 Edge Security

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
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://discover-best.techidaily.com/1-top-5-alternative-tools-for-mass-video-download-compatible-with-desktop-mobile-and-web-platforms/"><u>1. Top 5 Alternative Tools for Mass Video Download: Compatible with Desktop, Mobile & Web Platforms</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-funnyframeforge-picfunnyfactory/"><u>2024 Approved FunnyFrameForge PicFunnyFactory</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-roguelikes-roots-and-their-rebirth-as-roguiles/"><u>2024 Approved Roguelikes' Roots & Their Rebirth as Roguiles</u></a></li>
<li><a href="https://win11.techidaily.com/digital-canvas-on-windows-desktops-tips-and-tricks/"><u>Digital Canvas on Windows Desktops: Tips & Tricks</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oppo-reno-11-pro-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Oppo Reno 11 Pro 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-steps-to-clear-up-steam-errors-in-games-on-windows/"><u>Immediate Steps to Clear Up Steam Errors in Games on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-gionee-f3-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Gionee F3 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/simplifying-gmail-a-comprehensive-guide-on-selecting-every-message-with-ease-and-speed/"><u>Simplifying Gmail: A Comprehensive Guide on Selecting Every Message with Ease and Speed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/ultimate-guide-to-iphone-7-screen-recording/"><u>Ultimate Guide to iPhone 7 Screen Recording</u></a></li>
</ul></div>

