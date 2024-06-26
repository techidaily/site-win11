---
title: Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
date: 2024-06-25T09:49:18.638Z
updated: 2024-06-26T09:49:18.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
excerpt: This Article Describes Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11
keywords: Enable Clipboard Share,Activate Paste Functionality,Security Shield Startup,Edge Settings Access,Copy & Paste on Edge,Turn On Text Copy,Edge Shield Key Steps
thumbnail: https://thmb.techidaily.com/19760dde0975a0de0ce2cfe0db96677605f044bc91648bd3418188a2647d61d0.png
---

## Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11

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
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/pixel-perfection-embedding-zip-files-in-windows-images-unseen/"><u>Pixel Perfection: Embedding Zip Files in Windows Images Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-elevated-commands-always-access-terminal-as-admin/"><u>Mastering Elevated Commands: Always Access Terminal as Admin</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pathways-three-keys-to-gaming-files/"><u>Windows Pathways: Three Keys to Gaming Files</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-updating-halt-from-e8024002e/"><u>Eradicating Windows Updating Halt From E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-efficiently-engaging-recovery-tool/"><u>Key Steps for Efficiently Engaging Recovery Tool</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-real-time-streaming-vs-recorded-videos-twitch-vs-youtube-showdown/"><u>In 2024, Real-Time Streaming vs Recorded Videos  Twitch vs YouTube Showdown</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/best-tools-to-track-popular-tags-on-fb-twt-and-ig-networks-for-2024/"><u>Best Tools to Track Popular Tags on FB, Twt & IG Networks for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/unlock-visual-storytelling-potential-with-snapchat-edits-for-2024/"><u>Unlock Visual Storytelling Potential with Snapchat Edits for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-6s-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix iPhone 6s Unavailable Issue With Ease</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-master-levels-enhancing-steam-gameplay-videos/"><u>[New] 2024 Approved  Master Levels  Enhancing Steam Gameplay Videos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-top-5-windows-10-sound-engineers-optimal-audio-blending-experience/"><u>In 2024, Top 5 Windows 10 Sound Engineers Optimal Audio Blending Experience</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-solemn-sonatas-classic-music-selections-to-enhance-wedding-cinematography-for-2024/"><u>New Solemn Sonatas Classic Music Selections to Enhance Wedding Cinematography for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/rewind-and-play-instagrams-backwards-videos-unveiled/"><u>Rewind and Play  Instagram's Backwards Videos Unveiled</u></a></li>
<li><a href="https://extra-resources.techidaily.com/securing-privacy-with-8-advanced-photographic-editors/"><u>Securing Privacy with 8 Advanced Photographic Editors</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-zte-nubia-z60-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
</ul></div>
