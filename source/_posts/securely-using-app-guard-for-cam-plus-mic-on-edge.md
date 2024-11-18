---
title: Securely Using App Guard for Cam + Mic on Edge
date: 2024-11-17T01:33:03.608Z
updated: 2024-11-18T08:49:24.757Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Using App Guard for Cam + Mic on Edge
excerpt: This Article Describes Securely Using App Guard for Cam + Mic on Edge
keywords: Edge Security Guards,Audio & Video Protection,Secure Device Encryption,Multi-Device Safeguard,Privacy Enhanced Edge,Comprehensive App Guard,Mic+Cam Security Strategy
thumbnail: https://thmb.techidaily.com/3616fb63d3712b98cc05f9583f4211869f6e4c453eb6e04c1cfde40ef70bbce3.jpg
---

## Securely Using App Guard for Cam + Mic on Edge

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002019/7443" target="_top" id="2002019">
  <img src="//a.impactradius-go.com/display-ad/7443-2002019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002019/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-step-by-step-voice-customization-on-instagram-revealed/"><u>[New] Step-by-Step Voice Customization on Instagram Revealed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-adjust-privacy-settings-for-secure-online-viewing/"><u>[Updated] 2024 Approved Adjust Privacy Settings for Secure Online Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-mystery-of-windows-parse-mishap/"><u>Decoding the Mystery of Windows' Parse Mishap</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-jumpstart-your-windows-update-process/"><u>Essential Steps to Jumpstart Your Windows Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-the-missing-link-top-9-ways-to-reconnect-bluetooth-in-win-11/"><u>How to Mend the Missing Link: Top 9 Ways to Reconnect Bluetooth in Win 11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-live-streaming-showdown-obs-vs-wirecast-faceoff/"><u>In 2024, Live Streaming Showdown OBS vs Wirecast Faceoff</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/resolving-no-security-code-on-facebook-login-attempt/"><u>Resolving No Security Code on Facebook Login Attempt</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-portaudio-glitches-in-audacity-on-windows-11/"><u>Resolving PortAudio Glitches in Audacity on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/secure-your-favorite-shows-with-losmovies-downloader-the-ultimate-free-tool-for-saving-streams/"><u>Secure Your Favorite Shows with LosMovies Downloader: The Ultimate Free Tool for Saving Streams</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reading-excel-in-windows-notepad/"><u>Solutions for Reading Excel in Windows Notepad</u></a></li>
<li><a href="https://driver-download.techidaily.com/tl-wn722n-adapter-unrecognized-on-windows-troubleshooting-guide/"><u>TL-WN722N Adapter Unrecognized on Windows - Troubleshooting Guide</u></a></li>
<li><a href="https://fox-shield.techidaily.com/top-methods-for-downloading-tiktok-content-without-a-watermark/"><u>Top Methods for Downloading TikTok Content without a Watermark</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-windows-laptop-lags-after-connecting-to-an-external-monitor/"><u>What to Do if Windows Laptop Lags After Connecting to an External Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/which-windows-fits-the-bill-analyzing-home-versus-pro-features/"><u>Which Windows Fits the Bill? Analyzing Home Versus Pro Features</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-spotify-fixing-connection-flubs-quickly/"><u>Win11 & Spotify: Fixing Connection Flubs Quickly</u></a></li>
</ul></div>

