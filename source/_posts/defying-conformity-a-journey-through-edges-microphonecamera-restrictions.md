---
title: "Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
date: 2024-09-09T17:30:41.036Z
updated: 2024-09-17T05:32:08.708Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
excerpt: "This Article Describes Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions"
keywords: Defying Standards,Camera Microphone Limits,Edge Device Control,Audio Tech Constraints,Non-Conforming Devices,Restrictive Hardware Use,Innovative Recording Boundaries
thumbnail: https://thmb.techidaily.com/59a195ec28420319fea5f3f07d0383273230910a4a9660ef6c59333c64bce5cd.jpg
---

## Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions

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

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

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
<li><a href="https://fox-access.techidaily.com/new-innovative-rhythms-with-the-magix-groove-master-suite-for-2024/"><u>[New] Innovative Rhythms with the Magix Groove Master Suite for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-transforming-patience-into-speed-with-apps/"><u>[Updated] In 2024, Transforming Patience Into Speed with Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-vivo-x100-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Vivo X100 Phone? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-the-art-of-describing-your-podcast-with-flair/"><u>In 2024, The Art of Describing Your Podcast with Flair</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-asus-rog-phone-7-ultimate-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Asus ROG Phone 7 Ultimate Device</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/seamless-timelapse-footage-with-ios-technology-for-2024/"><u>Seamless Timelapse Footage with iOS Technology for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-on-downloading-snappea-software-for-your-windows-computer/"><u>Step-by-Step Guide on Downloading Snappea Software for Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-dvd-collection-into-common-video-formats-like-mp4-mkv-and-more/"><u>Step-by-Step Guide: Converting Your DVD Collection Into Common Video Formats Like MP4, MKV & More</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-entire-itunes-library-into-high-quality-mp3-format/"><u>Step-by-Step Guide: Converting Your Entire iTunes Library Into High-Quality MP3 Format</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-motorola-moto-g34-5g-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Motorola Moto G34 5G</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

