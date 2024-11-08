---
title: Steps to Activate Clipboard Features with Shielded Applications (Edge) on W11 Platform
date: 2024-11-06T22:31:24.743Z
updated: 2024-11-07T22:12:01.957Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-reducing-recording-ambiance-free-methods-and-pros/"><u>[New] 2024 Approved Reducing Recording Ambiance Free Methods and Pros</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-growth-odyssey-of-ajey-nagar-on-youtube/"><u>[New] In 2024, The Growth Odyssey of Ajey Nagar on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-touch-input-layout-on-newest-windows-os-win-11-edition/"><u>Correcting Touch Input Layout on Newest Windows OS - Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/improve-win11-notepad-through-intelligent-coach/"><u>Improve Win11 Notepad Through Intelligent Coach</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-oppo-a79-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Oppo A79 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-the-latest-alternatives-to-tiktok-that-are-making-waves/"><u>In 2024, The Latest Alternatives to TikTok That Are Making Waves</u></a></li>
<li><a href="https://common-error.techidaily.com/kb4056892-updates-for-windows-11-installed-successfully-a-comprehensive-guide/"><u>KB4056892 Updates for Windows 11 Installed Successfully – A Comprehensive Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/maximize-engagement-using-our-cookiebot-tools/"><u>Maximize Engagement Using Our Cookiebot Tools</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-interface-for-device-customization-in-windows-11/"><u>Navigating the Interface for Device Customization in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restart-and-reinstall-solutions-for-unison-problems-in-win11/"><u>Restart & Reinstall: Solutions For Unison Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-error-codes-on-windows/"><u>Steps to Tackle Error Codes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-soundflow-in-audacity-win1011s-paudio-challenge/"><u>Syncing Soundflow in Audacity, Win10/11’s PAudio Challenge</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-comprehensive-guide-to-computer-components/"><u>Tom's Tech Insights: Comprehensive Guide to Computer Components</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-8-must-have-educational-apps/"><u>Top 8 Must-Have Educational Apps</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-cortana-in-windows-11/"><u>Turn Off Cortana in Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/utilizing-chatgpt-innovative-techniques-for-tailoring-your-job-application-documents/"><u>Utilizing ChatGPT: Innovative Techniques for Tailoring Your Job Application Documents</u></a></li>
</ul></div>

