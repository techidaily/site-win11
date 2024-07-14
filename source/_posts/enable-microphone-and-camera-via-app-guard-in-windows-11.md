---
title: Enable Microphone & Camera via App Guard in Windows 11
date: 2024-07-13T10:16:10.339Z
updated: 2024-07-14T10:16:10.339Z
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
<li><a href="https://extra-support.techidaily.com/in-2024-leading-12-free-video-trimming-apps-for-android-users/"><u>In 2024, Leading 12 Free Video Trimming Apps for Android Users</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-approaches-to-disable-audio-elements-within-a-video-for-2024/"><u>Updated Approaches to Disable Audio Elements Within a Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-potential-a-complete-walkthrough-of-wpm-on-windows-os/"><u>Unlock Full Potential: A Complete Walkthrough of WPM on Windows OS</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-reality-redefined-exploring-virtualitys-kin-vr-ar-and-mr/"><u>In 2024, Reality Redefined  Exploring Virtuality’s Kin - VR, AR, & MR</u></a></li>
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-keyboard-method-to-resize-programs/"><u>Navigating Windows 11'S Keyboard Method to Resize Programs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-elite-group-of-high-speed-video-snapshot-apps/"><u>[New] In 2024, Elite Group of High-Speed Video Snapshot Apps</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-fresh-ideas-to-talk-about-in-daily-vlogging-for-2024/"><u>[Updated] Fresh Ideas to Talk About in Daily Vlogging for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-quick-fixes-for-five-common-defender-disruptions/"><u>Troubleshooting Guide: Quick Fixes For Five Common Defender Disruptions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensive-guide-to-idevices-recording-tools-for-2024/"><u>Comprehensive Guide to iDevices Recording Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-approach-to-sound-channel-division/"><u>Understanding Windows’ Approach to Sound Channel Division</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-the-ultimate-guide-selecting-the-highest-rated-mp3-recorders-windowsmac/"><u>2024 Approved The Ultimate Guide Selecting the Highest-Rated MP3 Recorders (Windows/Mac)</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-xbox-game-pass-x8007e9-error-in-windows/"><u>Solutions for Xbox Game Pass X8007E9 Error in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-techniques-for-concurrent-webcam-and-screen-recordings/"><u>2024 Approved  Techniques for Concurrent Webcam & Screen Recordings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-tips-for-high-quality-mac-cam-videos/"><u>[Updated] Top Tips for High-Quality Mac Cam Videos</u></a></li>
<li><a href="https://win11.techidaily.com/antimalware-resource-hog-turn-it-off-for-better-performance/"><u>Antimalware Resource Hog: Turn It Off for Better Performance</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-absence-of-dxgidll-in-windows-11/"><u>How to Rectify the Absence of Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-silent-tab-disabling-in-windows-11/"><u>Navigating to Silent Tab Disabling in Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-reel-in-riches-a-guide-to-earning-on-youtube-shorts/"><u>[Updated] Reel In Riches  A Guide to Earning on YouTube Shorts</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-cataloging-the-symphony-of-crickets-an-acoustic-collection/"><u>In 2024, Cataloging the Symphony of Crickets An Acoustic Collection</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-windows-11-photos-incorporating-filters-and-tunes/"><u>Mastering Windows 11 Photos  Incorporating Filters & Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/top-notch-windows-11-skins-no-one-knows/"><u>Top-Notch Windows 11 Skins No One Knows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-wsl-registration-failure-with-error-x80370102/"><u>Mastering The Fix: WSL Registration Failure with Error X80370102</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-inside-outlooks-of-instagram-stories-consumers/"><u>[Updated] 2024 Approved  Inside Outlooks of Instagram Stories Consumers</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-efficient-recorders-guide-identifying-the-top-8-online-gratis-voice-capture-tools/"><u>In 2024, The Efficient Recorders Guide Identifying the Top 8 Online, Gratis Voice Capture Tools</u></a></li>
<li><a href="https://win11.techidaily.com/inside-the-windows-world-crafting-and-examining-system-data/"><u>Inside the Windows World: Crafting and Examining System Data</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-disconnected-remote-resources-in-windows/"><u>Strategies to Address Disconnected Remote Resources in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-program-format-pe/"><u>Demystifying Windows Program Format (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-windows-11s-voice-recorder-usability-via-shortcut-guide/"><u>Elevating Windows 11'S Voice Recorder Usability via Shortcut Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-elevating-roi-in-facebooks-animated-advertising-arena/"><u>In 2024, Elevating ROI in Facebook's Animated Advertising Arena</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-eradicating-predominant-anomalies-with-anydesk-on-windows/"><u>Key Techniques: Eradicating Predominant Anomalies with AnyDesk on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-autonomous-command-line-openings/"><u>How to Disable Autonomous Command Line Openings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-cost-free-text-animations-onlineoff/"><u>2024 Approved  Guide to Cost-Free Text Animations (Online/Off)</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-windows-11-workspace-in-minutes/"><u>Tidy Up Windows 11 Workspace in Minutes</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-secure-your-space-top-10-free-security-camera-programs-for-2024/"><u>New Secure Your Space Top 10 Free Security Camera Programs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/linux-perfection-bypassing-wsl/"><u>Linux Perfection: Bypassing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-freezing-and-black-steam-in-winos/"><u>Troubleshooting Freezing & Black Steam in WinOS</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-avoiding-the-common-path-the-route-to-unique-streamer-identities/"><u>[Updated] 2024 Approved  Avoiding the Common Path  The Route to Unique Streamer Identities</u></a></li>
<li><a href="https://win11.techidaily.com/5-effective-strategies-to-fix-rpc-issues-in-win/"><u>5 Effective Strategies to Fix RPC Issues in Win</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-fix-route-no-current-nvidia-output/"><u>Direct Fix Route: No Current NVIDIA Output</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-your-windows-11-screen/"><u>Breathing Life Into Your Windows 11 Screen</u></a></li>
</ul></div>
