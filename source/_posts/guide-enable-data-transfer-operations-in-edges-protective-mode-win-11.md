---
title: "Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
date: 2024-06-25T11:27:09.230Z
updated: 2024-06-26T11:27:09.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
excerpt: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
keywords: Edge Security Guide,Win11 Protective Mode,Data Transfer Operations,Edge Mode Settings,Enable Data Share,Win11 Networking,Edge Secure Transfer
thumbnail: https://thmb.techidaily.com/4db798dc8e85e2daadf391573bc5ef81d7d7a8b53e675ec2733be93146fbbb0f.jpg
---

## Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

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
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

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
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-connection-issues-malwarebytes-service-errors-in-win-1011/"><u>Fixing Connection Issues: Malwarebytes' Service Errors in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-way-you-use-windows-11s-search-feature/"><u>Transforming the Way You Use Windows 11'S Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-invalid-label-error-on-windows-11/"><u>Guide to Rectify 'Invalid Label' Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/winning-fps-tools-the-top-6-counter-app-picks/"><u>Winning FPS Tools: The Top 6 Counter App Picks</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/skilled-tactics-bypassing-windows-11s-security-measures/"><u>Skilled Tactics: Bypassing Windows 11'S Security Measures</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Itel A05s? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-top-list-best-vhs-sound-effect-that-you-can-use-in-video-making/"><u>Updated In 2024, Top List Best VHS Sound Effect That You Can Use in Video Making</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-11-step-by-step-pathways-to-perfect-grading/"><u>In 2024, 11 Step by Step Pathways to Perfect Grading</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-you-play-mp4-on-edge-2023-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can you play MP4 on Edge 2023?</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-nokia-g310-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Nokia G310 FRP</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-time-is-money-learn-to-slash-youtube-video-durations/"><u>2024 Approved  Time Is Money - Learn to Slash YouTube Video Durations</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-picture-perfect-instagram-carousel/"><u>2024 Approved  Picture-Perfect Instagram Carousel</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-seamless-facial-smoothing-motion-blur-techniques-in-picsart/"><u>In 2024, Seamless Facial Smoothing  Motion Blur Techniques in Picsart</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-final-cut-pros-finest-10-iconic-movies/"><u>New 2024 Approved Final Cut Pros Finest 10 Iconic Movies</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-vivo-y27s-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Vivo Y27s</u></a></li>
</ul></div>
