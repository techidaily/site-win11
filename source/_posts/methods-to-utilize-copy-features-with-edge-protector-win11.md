---
title: Methods to Utilize Copy Features with Edge Protector, Win11
date: 2024-06-25T11:39:31.411Z
updated: 2024-06-26T11:39:31.411Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Utilize Copy Features with Edge Protector, Win11
excerpt: This Article Describes Methods to Utilize Copy Features with Edge Protector, Win11
keywords: Edge Protector Copy Techniques,Win11 Copy Enhancement Methods,EdgeGuard Copy Improvement,Win11 Text Feature Use,Advanced Copy Strategies,Optimize EdgeCopy Win11,Win11 Textual Protection
thumbnail: https://thmb.techidaily.com/c625d72d0946f66f9247899cc6c4c66eb70d8cf37963b2732e636693601b56f7.jpg
---

## Methods to Utilize Copy Features with Edge Protector, Win11

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
<li><a href="https://win11.techidaily.com/tips-for-troubleshooting-freezing-spotify-app-on-windows-11/"><u>Tips for Troubleshooting Freezing Spotify App on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-legacy-computer-for-windows-11-via-to-go-and-rufus/"><u>Optimize Your Legacy Computer for Windows 11 via To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/regulating-pcs-to-prevent-windows-11-overheats/"><u>Regulating PCs to Prevent Windows 11 Overheats</u></a></li>
<li><a href="https://win11.techidaily.com/greatest-non-microsoft-options-easy-screen-captures-without-windows/"><u>Greatest Non-Microsoft Options: Easy Screen Captures Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-sound-recording-on-windows-11/"><u>Streamline Your Sound Recording on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-recovering-windows-11s-aid-features/"><u>Steps for Recovering Windows 11'S Aid Features</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-pc-load-tips-for-managing-multimedia-tasks-on-windows/"><u>Minimize PC Load: Tips for Managing Multimedia Tasks on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-crafting-engagement-top-5-typeface-tools-to-amplify-your-tiktok-reach/"><u>[New] 2024 Approved  Crafting Engagement  Top 5 Typeface Tools to Amplify Your TikTok Reach</u></a></li>
<li><a href="https://discord-videos.techidaily.com/leading-edge-bots-in-social-chats-for-2024/"><u>Leading Edge Bots in Social Chats for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-10-live-streaming-networks-revealed-and-compared-for-2024/"><u>Prime 10 Live Streaming Networks Revealed and Compared for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-what-we-learned-the-ultimate-ogg-converter-guide/"><u>New In 2024, What We Learned The Ultimate OGG Converter Guide</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-some-of-the-top-sites-to-replace-a-sky-background-in-videos/"><u>New Some of the Top Sites to Replace a Sky Background in Videos</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-sleek-and-powerful-the-best-lightweight-video-editing-tools/"><u>2024 Approved Sleek and Powerful The Best Lightweight Video Editing Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-beat-a-thon-essential-playlists-for-tiktoks-hot-rappers/"><u>[Updated] 2024 Approved  Beat-a-Thon  Essential Playlists for TikTok's Hot Rappers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-accessing-live-spaces-on-tiktok-your-pathway/"><u>[New] In 2024, Accessing Live Spaces on TikTok  Your Pathway</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-messvid-grabber-for-social-media/"><u>In 2024, MessVid Grabber for Social Media</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-vivo-y100t-device-sim-by-drfone-android/"><u>Easily Unlock Your Vivo Y100t Device SIM</u></a></li>
</ul></div>
