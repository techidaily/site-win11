---
title: "Quick Guide: How To Mask After Dim Setting on Windows"
date: 2024-11-17T00:57:58.976Z
updated: 2024-11-17T23:02:26.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: How To Mask After Dim Setting on Windows"
excerpt: "This Article Describes Quick Guide: How To Mask After Dim Setting on Windows"
keywords: WIN Dimming Mask Tips,Window Settings Guide,Post-Dim Brightness Hide,Masking Windows Lightning,Dim To Conceal Afterset,Quick Windows Darken Tricks,Hiding Windows Brightness
thumbnail: https://thmb.techidaily.com/494747ec004285de2aadee4c9fc771562b4f42ca29ed6aecefce800cf9eedde4.jpg
---

## Quick Guide: How To Mask After Dim Setting on Windows

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-key-elements-in-asmr-video-content/"><u>[Updated] Key Elements in ASMR Video Content</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-calculating-viewing-time-for-a-20mb-video/"><u>2024 Approved Calculating Viewing Time for a 20Mb Video</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-optimize-cpu-load-from-tiworkerexe/"><u>Approaches to Optimize CPU Load From TiWorker.exe</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win-able.techidaily.com/cyberpunk-2077-and-the-challenge-of-error-code-2024-solutions-inside/"><u>Cyberpunk 2077 and the Challenge of Error Code 2024 - Solutions Inside</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-directx-protocols-for-your-gaming-system/"><u>Effortless DirectX Protocols for Your Gaming System</u></a></li>
<li><a href="https://program-issues.techidaily.com/fix-how-to-resolve-lack-of-audio-during-twitch-live-broadcasts/"><u>Fix: How to Resolve Lack of Audio During Twitch Live Broadcasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fuhre-deinen-dvd-player-in-einer-minute-auf-den-neuesten-stand-komplette-anleitungsserie/"><u>Führe Deinen DVD-Player in Einer Minute Auf Den Neuesten Stand - Komplette Anleitungsserie</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-chatgpt-is-at-capacity-right-now-error-on-windows/"><u>How to Fix the ChatGPT Is at Capacity Right Now Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-update-your-amd-radeon-graphics-drivers-on-windows-11/"><u>How to Update Your AMD Radeon Graphics Drivers on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-notable-book-trailers-showcasing-stories/"><u>In 2024, Notable Book Trailers Showcasing Stories</u></a></li>
<li><a href="https://win11.techidaily.com/managing-failed-app-verifications-in-windows-os/"><u>Managing Failed App Verifications in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/master-subtitles-management-with-prime-and-windows-11/"><u>Master Subtitles Management with Prime and Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-screen-snafus-with-sonic-frontiers-securing-smooth-play-on-w11/"><u>Navigating Screen Snafus with Sonic Frontiers - Securing Smooth Play on W11</u></a></li>
<li><a href="https://some-skills.techidaily.com/predictive-magic-with-linux-unlocking-fortune-telling-scripts-in-terminal/"><u>Predictive Magic with Linux: Unlocking Fortune-Telling Scripts in Terminal</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205500214-razer-keyboard-issues-why-isnt-it-lights-up-solutions-inside/"><u>Razer Keyboard Issues - Why Isn't It Lights Up? Solutions Inside</u></a></li>
<li><a href="https://win-able.techidaily.com/sony-vegas-stability-solutions-how-to-prevent-unexpected-software-shutdowns/"><u>Sony Vegas Stability Solutions: How To Prevent Unexpected Software Shutdowns</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-free-dvd-ripping-software-for-windows-10-and-11-complete-downloads-revealed/"><u>Top Free DVD Ripping Software for Windows 10 & 11: Complete Downloads Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/windows-history-top-removed-and-evolved-characteristics/"><u>Windows History: Top Removed and Evolved Characteristics</u></a></li>
</ul></div>

