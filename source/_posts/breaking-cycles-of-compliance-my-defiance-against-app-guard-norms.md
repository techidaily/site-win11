---
title: "Breaking Cycles of Compliance: My Defiance Against App Guard Norms"
date: 2025-02-25T21:32:11.163Z
updated: 2025-03-05T00:09:41.009Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breaking Cycles of Compliance: My Defiance Against App Guard Norms"
excerpt: "This Article Describes Breaking Cycles of Compliance: My Defiance Against App Guard Norms"
keywords: Breaking Norms,Defiant Security,Cycle Disruption,Noncompliance Strategy,Challenge Compliance,Guard Bypassing,Rebel Tech Safeguards
thumbnail: https://thmb.techidaily.com/33139754522d3393b0a998cc016bffa1b55254150a3f5abcd672e5d0c2f8e9f3.jpg
---

## Breaking Cycles of Compliance: My Defiance Against App Guard Norms

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

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

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-youtube-sound-ripper-collection-top-17-extractors-revealed/"><u>[New] 2024 Approved Free YouTube Sound Ripper Collection Top 17 Extractors Revealed</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-youtubes-earnings-go-up-with-500-subs/"><u>[Updated] 2024 Approved YouTube's Earnings Go Up With 500 Subs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-key-techniques-for-capturing-youtube-streaming-content/"><u>[Updated] Key Techniques for Capturing YouTube Streaming Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-learn-to-sound-unique-how-to-alter-vocal-identity-on-the-battlefield-free/"><u>[Updated] Learn to Sound Unique How to Alter Vocal Identity on the Battlefield (Free)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/elusive-story-viewers-mobile-hacks/"><u>Elusive Story Viewers' Mobile Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-wsl-operation-post-windows-11-shift/"><u>Ensuring Smooth WSL Operation Post-Windows 11 Shift</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-efficient-5-top-clock-saver-programs-for-windows/"><u>Expertly Efficient: 5 Top Clock Saver Programs for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-access-control-entry-is-corrupt-error-on-windows/"><u>How to Fix the “Access Control Entry Is Corrupt” Error on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/maximize-your-gains-highest-earning-instagram-tactics-for-2024/"><u>Maximize Your Gains Highest Earning Instagram Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-voice-recorders-with-precision-using-shortcuts-in-win-11/"><u>Navigate Voice Recorders with Precision Using Shortcuts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-inactive-windows-download-section/"><u>Reviving the Inactive Windows Download Section</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-fixing-unresponsive-usb-devices/"><u>Solutions for Windows: Fixing Unresponsive USB Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-harmony-of-collaboration-brands-and-youtube-unite-for-2024/"><u>The Harmony of Collaboration Brands & YouTube Unite for 2024</u></a></li>
</ul></div>

