---
title: Enable Microphone & Camera via App Guard in Windows 11
date: 2024-06-25T10:09:41.100Z
updated: 2024-06-26T10:09:41.100Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Microphone & Camera via App Guard in Windows 11
excerpt: This Article Describes Enable Microphone & Camera via App Guard in Windows 11
keywords: Windows 11 Security Update,App Guard Enablement,Microphone Access Control,Camera Permission Management,Device Integration Through Apps,Windows Settings Customization,Privacy-Focused System Feature
thumbnail: https://thmb.techidaily.com/0fde8be80e602ff65625842ff908df27188b320349e0a53c08ea2eca9a5b67ed.jpg
---

## Enable Microphone & Camera via App Guard in Windows 11

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
<li><a href="https://win11.techidaily.com/typography-transition-on-windows-multilingual-scripts/"><u>Typography Transition on Windows: Multilingual Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-system-usability-in-windows-max-156/"><u>Enhancing File System Usability in Windows (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overclocked-cpus-for-gaming-users/"><u>Troubleshooting Overclocked CPUs for Gaming Users</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-essential-plugin-list-the-ultimate-selection-of-logic-pro-x-upgrades-for-2024/"><u>Updated Essential Plugin List The Ultimate Selection of Logic Pro X Upgrades for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transform-into-a-hdr-photography-wizard-via-photoshop-for-2024/"><u>Transform Into a HDR Photography Wizard via Photoshop for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-pioneering-mobile-broadcasting-mastering-obs-studio-and-android/"><u>[New] Pioneering Mobile Broadcasting  Mastering OBS Studio and Android</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-reigning-tiktoks-on-twitter-a-viral-analysis/"><u>[Updated] In 2024, Reigning TikToks on Twitter  A Viral Analysis</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-7-star-rated-apps-for-effortless-youtube-live-broadcast-from-iphone-and-android/"><u>2024 Approved  7 Star-Rated Apps for Effortless YouTube LIVE Broadcast From iPhone and Android</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-digital-sensation-watch-hot-tweets-gaining-momentum/"><u>[New] 2024 Approved  Digital Sensation Watch  Hot Tweets Gaining Momentum</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-the-easiest-way-to-download-and-use-tiktok-on-your-macbook/"><u>[New] In 2024, The Easiest Way to Download and Use TikTok on Your MacBook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-top-techniques-for-professional-looking-ig-video-content/"><u>[Updated] 2024 Approved  Top Techniques for Professional-Looking IG Video Content</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-navigating-facebooks-updated-algorithm-preparation-checklist/"><u>[New] 2024 Approved  Navigating Facebook's Updated Algorithm  Preparation Checklist</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-oneplus-nord-3-5g-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of OnePlus Nord 3 5G with Video Repair Utility on Mac?</u></a></li>
</ul></div>
