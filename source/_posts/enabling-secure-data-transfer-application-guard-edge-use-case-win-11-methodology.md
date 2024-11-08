---
title: "Enabling Secure Data Transfer: Application Guard (Edge) Use Case, Win 11 Methodology"
date: 2024-11-04T21:11:43.091Z
updated: 2024-11-07T19:14:23.875Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling Secure Data Transfer: Application Guard (Edge) Use Case, Win 11 Methodology"
excerpt: "This Article Describes Enabling Secure Data Transfer: Application Guard (Edge) Use Case, Win 11 Methodology"
keywords: Edge Security Gateway,Win11 AppGuard,DataTransfer Safeguarding,Secure Transmission Tech,Microsoft Edge Shielding,Protected File Transfer,WinOS Encryption Methods
thumbnail: https://thmb.techidaily.com/3baf857753526582466180d3f05c500201c50c2631446be3adbac2ea8607bb00.jpg
---

## Enabling Secure Data Transfer: Application Guard (Edge) Use Case, Win 11 Methodology

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
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-enlightening-edits-top-tools-for-picture-perfection/"><u>[New] 2024 Approved Enlightening Edits Top Tools for Picture Perfection</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-fists-vs-followers-choosing-the-champion/"><u>2024 Approved Fists vs Followers Choosing the Champion</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-framing-character-arcs-on-screen/"><u>2024 Approved Framing Character Arcs on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-invalid-profile-messages-a-windows-11-solution/"><u>Correcting Invalid Profile Messages: A Windows 11 Solution</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-praey-how-to-stop-praey-for-the-gods-from-crashing-on-your-pc/"><u>Fix Praey: How to Stop Praey for the Gods From Crashing on Your PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/funny-frameworks-crafting-memes-with-ease-for-2024/"><u>Funny Frameworks Crafting Memes with Ease for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-efficientuseofyourwebcamforrecording/"><u>In 2024, EfficientUseOfYourWebcamForRecording</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovative-methods-to-access-apples-podcast-library/"><u>Innovative Methods to Access Apple's Podcast Library</u></a></li>
<li><a href="https://win11.techidaily.com/refined-clarity-in-a-click-win11-monitor-restoration-techniques/"><u>Refined Clarity in a Click: Win11 Monitor Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-optimizing-network-address-translation-on-windows/"><u>Strategies for Optimizing Network Address Translation on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-stylus-malfunctions-with-these-tips-for-windows-tablets/"><u>Streamline Stylus Malfunctions with These Tips for Windows Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-start-errors-in-windows-speech-recognition/"><u>Tackling Non-Start Errors in Windows Speech Recognition</u></a></li>
</ul></div>

