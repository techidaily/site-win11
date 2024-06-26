---
title: Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge
date: 2024-06-25T11:41:19.294Z
updated: 2024-06-26T11:41:19.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge
excerpt: This Article Describes Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge
keywords: Activate W11 COPY/PASTE Security,W11 Edge Paste Mode Enable,Edge Security Copy Function,Edge Mode Copy Activation,Enable Copy in W11 Edge,Pasting Safely in W11 Edge,Secure Copy/Paste in Windows 11
thumbnail: https://thmb.techidaily.com/7c98b3aa443d56db5acb03366d8aa2c1ee75e1644b06d32e3fca560857ba5e46.jpg
---

## Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge

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
<li><a href="https://win11.techidaily.com/fix-slow-download-issues-in-steam-on-windows-platform/"><u>Fix Slow Download Issues in Steam on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-closed-caption-mishaps-in-windows-10/"><u>Resolving Closed Caption Mishaps in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/verifying-your-version-three-ways-for-windows-11/"><u>Verifying Your Version: Three Ways for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-missing-windows-phone-link-notifications/"><u>Steps to Reactivate Missing Windows Phone Link Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-issues-with-winservicesexe-on-windows/"><u>Fixing Common Issues with Winservices.exe on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-install-the-microsoft-pc-manager-on-windows-try-these-7-fixes/"><u>Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-tech-tutorial-saving-screen-movies-from-your-gadgets/"><u>[New] Tech Tutorial  Saving Screen Movies From Your Gadgets</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-vivo-y28-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-splitscreen-designer/"><u>[New] SplitScreen Designer</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prime-tools-and-techniques-image-to-video-conversion/"><u>[New] Prime Tools and Techniques  Image-to-Video Conversion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-best-microphone-for-youtuber/"><u>[New] In 2024, Best Microphone for YouTuber</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-top-10-hilarious-and-heartfelt-instagram-memes-hubs/"><u>[New] In 2024, Top 10 Hilarious & Heartfelt Instagram Memes Hubs</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-mastering-nvidia-screenshot-capture/"><u>In 2024, Mastering NVIDIA Screenshot Capture</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-evaluating-live-stream-giants-twitch-and-youtube/"><u>2024 Approved  Evaluating Live Stream Giants  Twitch & YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/techniques-for-more-watches-on-your-insta-vids/"><u>Techniques for More Watches on Your Insta Vids</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-maximize-your-mobile-top-10-free-image-enhancement-tools/"><u>[New] Maximize Your Mobile  Top 10 Free Image Enhancement Tools</u></a></li>
</ul></div>
