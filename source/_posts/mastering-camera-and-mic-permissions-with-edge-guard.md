---
title: Mastering Camera & Mic Permissions with Edge Guard
date: 2024-10-06T17:33:31.451Z
updated: 2024-10-09T11:37:28.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Camera & Mic Permissions with Edge Guard
excerpt: This Article Describes Mastering Camera & Mic Permissions with Edge Guard
keywords: Edge Guard Permissions,Camera Control Security,Microphone Accessibility,Secure Device Recording,Manage App Permissions,Privacy-Focused Access,Restrict Unauthorized Use
thumbnail: https://thmb.techidaily.com/0313aeb6801c4ad054aee4b20ba488ff337dac52c595922f616f6d67ab2cd3c7.jpg
---

## Mastering Camera & Mic Permissions with Edge Guard

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
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-essential-auditory-collection-top-1e-spotify-sound-capturers/"><u>[New] Essential Auditory Collection Top 1E Spotify Sound Capturers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-evolving-strategies-the-forecast-for-fb-advertising/"><u>[New] In 2024, Evolving Strategies The Forecast for FB Advertising</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-9-essential-apps-for-pulling-youtube-videos-android-for-2024/"><u>[Updated] 9 Essential Apps for Pulling YouTube Videos (Android) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-hibernate-depression-in-windows/"><u>Combatting Hibernate Depression in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-corrupted-filesystems-in-windows-11/"><u>Correcting Corrupted Filesystems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-file-access-failures-in-windows/"><u>Correcting File Access Failures in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-exciting-new-functions-arriving-with-certain-apple-airpods-models-this-fall-according-to-zdnet/"><u>Discover the Exciting New Functions Arriving with Certain Apple AirPods Models This Fall, According to ZDNet</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/filter-not-working-error-in-excel-2023-fix-2024-by-stellar-guide/"><u>Filter Not Working Error in Excel 2023 Fix 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instant-use-of-snipping-tool-on-modern-windows-os/"><u>Instant Use of Snipping Tool on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-the-load-on-your-pc-with-efficient-wlanextexe/"><u>Lowering the Load on Your PC with Efficient Wlanext.exe</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/cover-film-noir-creating-vintage-scenes/"><u>Rediscover Film Noir Creating Vintage Scenes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-restoring-sound-functionality-on-windows-11/"><u>Step-by-Step Guide to Restoring Sound Functionality on Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-art-of-perfect-sound-recording-zooming-into-excellence-for-podcasts/"><u>The Art of Perfect Sound Recording Zooming Into Excellence for Podcasts</u></a></li>
</ul></div>

