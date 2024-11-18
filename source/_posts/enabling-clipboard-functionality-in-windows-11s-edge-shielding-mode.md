---
title: Enabling Clipboard Functionality in Windows 11'S Edge Shielding Mode
date: 2024-11-15T19:28:10.396Z
updated: 2024-11-18T02:29:57.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Clipboard Functionality in Windows 11'S Edge Shielding Mode
excerpt: This Article Describes Enabling Clipboard Functionality in Windows 11'S Edge Shielding Mode
keywords: Windows 11 Edge Protect,Copy-Paste Capability,Edgeshield Mode Clip,Clipboard Enablement W11,Windows Edge Security,Edge Shielding Feature,Clipboard in W11 Mode
thumbnail: https://thmb.techidaily.com/c2256048fdba19e150d130af22fa0ee9a49a1cc871ecb123979c39c8bac9ef09.jpg
---

## Enabling Clipboard Functionality in Windows 11'S Edge Shielding Mode

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
<a href="https://aligracehair.sjv.io/c/5597632/1972698/19272" target="_top" id="1972698">
  <img src="//a.impactradius-go.com/display-ad/19272-1972698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-helps.techidaily.com/new-in-2024-streaming-success-implementing-green-screen-innovations/"><u>[New] In 2024, Streaming Success Implementing Green Screen Innovations</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ultimate-gaming-lineup-bike-titles/"><u>[New] Ultimate Gaming Lineup Bike Titles</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-secrets-of-professional-level-iptv-capturing/"><u>[Updated] In 2024, Secrets of Professional-Level IPTV Capturing</u></a></li>
<li><a href="https://win11.techidaily.com/dialing-back-after-a-wave-of-vigor-on-windows-systems/"><u>Dialing Back After a Wave of Vigor on Windows Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-to-make-your-ipod-video-friendly-the-power-of-winx-ipod-video-converter-mac-edition/"><u>Easy Steps to Make Your iPod Video-Friendly: The Power of WinX iPod Video Converter (Mac Edition)</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-on-iphone-14-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID On iPhone 14 Making It Possible</u></a></li>
<li><a href="https://win-blog.techidaily.com/insurgency-sandstorm-update-causes-persistent-game-crashes-solved/"><u>Insurgency: Sandstorm Update Causes Persistent Game Crashes - Solved</u></a></li>
<li><a href="https://techtrends.techidaily.com/macx-pro-premium-video-transcoding-software-purchase-and-enhance-your-multimedia-projects/"><u>MacX Pro: Premium Video Transcoding Software – Purchase and Enhance Your Multimedia Projects</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-auto-deletion-windows-1011-file-management/"><u>Mastering Auto-Deletion: Windows 10/11 File Management</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-operating-systems-with-ai-integration/"><u>Redefining Operating Systems with AI Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-cannot-open-error-on-closed-folders-in-microsoft-mail-for-pc/"><u>Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-auditory-service-auto-restart-fix-guide/"><u>Reviving Windows Auditory Service: Auto Restart Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-settings-for-programs-on-win11/"><u>Tailoring Screen Settings for Programs on Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Xiaomi 13 Ultra | Dr.fone</u></a></li>
</ul></div>

