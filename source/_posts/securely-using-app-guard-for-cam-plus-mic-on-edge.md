---
title: Securely Using App Guard for Cam + Mic on Edge
date: 2024-11-03T19:02:12.343Z
updated: 2024-11-07T16:17:50.124Z
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
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-initial-steps-in-kinetic-illustration-techniques/"><u>[New] Initial Steps in Kinetic Illustration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-rounded-corners-in-windows-desktop/"><u>Cutting Rounded Corners in Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-through-the-conundrum-fixer-blocked-not-broken/"><u>Cutting Through the Conundrum: Fixer Blocked, Not Broken</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-windows-n-suites-which-ones-best/"><u>Dissecting Windows N Suites: Which One's Best?</u></a></li>
<li><a href="https://fox-http.techidaily.com/easy-plot-development-basics-for-2024/"><u>Easy Plot Development Basics for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-bluetooth-disturbance-in-win10/"><u>End Bluetooth Disturbance in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/finding-alternative-processes-to-start-your-programs-on-windows/"><u>Finding Alternative Processes to Start Your Programs on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-and-fantastic-the-top-10-lut-sources-for-2024/"><u>Free & Fantastic The Top 10 LUT Sources for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-disconnect-errors-in-windows-discord/"><u>Solutions to Disconnect Errors in Windows Discord</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-error-for-non-existent-mfc71udll/"><u>Steps to Fix: Windows Error for Non-Existent Mfc71u.dll</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-xbox-service-disconnect-error/"><u>Steps to Overcome Xbox Service Disconnect Error</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-screen-with-smooth-window-10-captions/"><u>Streamline Your Screen with Smooth Window 10 Captions</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/the-future-of-presentations-text-conversion-powered-by-speech-for-2024/"><u>The Future of Presentations Text Conversion Powered by Speech for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-great-debate-sony-vegas-pro-vs-adobe-premiere-pro-for-professional-video-editing/"><u>The Great Debate Sony Vegas Pro vs Adobe Premiere Pro for Professional Video Editing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-emerging-cybersecurity-developments-insights-and-forecasts/"><u>Top 7 Emerging Cybersecurity Developments: Insights & Forecasts</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-beatmaking-breakdown-top-8-digital-audio-workstations-daws-for-mac-and-pc-enthusiasts/"><u>Updated In 2024, Beatmaking Breakdown Top 8 Digital Audio Workstations (DAWs) For Mac & PC Enthusiasts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-muting-zoom-a-step-by-step-guide-for-quiet-calls-on-laptops-and-phones-for-2024/"><u>Updated Muting Zoom A Step-by-Step Guide for Quiet Calls on Laptops & Phones for 2024</u></a></li>
</ul></div>

