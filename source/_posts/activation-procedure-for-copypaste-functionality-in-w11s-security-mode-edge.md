---
title: Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge
date: 2024-07-13T10:52:03.240Z
updated: 2024-07-14T10:52:03.240Z
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

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
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
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-play-40c-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-achieve-balance-in-visuals-through-aspect-choices/"><u>2024 Approved  Achieve Balance in Visuals Through Aspect Choices</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/two-ways-to-track-my-boyfriends-apple-iphone-12-without-him-knowing-drfone-by-drfone-virtual-ios/"><u>Two Ways to Track My Boyfriends Apple iPhone 12 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-the-iphone-11-pro-max-sim-lock-4-easy-methods-by-drfone-ios/"><u>How To Unlock The iPhone 11 Pro Max SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-access-to-system-fixes-windows-10-and-11-key-setups/"><u>Strategic Access to System Fixes: Windows 10 & 11 Key Setups</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-virtual-impression-sculpting-a-playful-digital-identity-for-2024/"><u>[Updated] Virtual Impression  Sculpting a Playful Digital Identity for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-goofy-flick-an-analysis-of-the-goofy-movie/"><u>[New] In 2024, Goofy Flick  An Analysis of 'The Goofy Movie'</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-art-of-ad-free-earning-on-youtube-strategies-for-self-reliance-creators/"><u>In 2024, The Art of Ad-Free Earning on YouTube  Strategies for Self-Reliance Creators</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-nailing-the-technique-for-snapchat-screen-time-lapses/"><u>In 2024, Nailing the Technique for Snapchat Screen Time-Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-instantaneous-aspect-alteration-for-visual-content/"><u>In 2024, Instantaneous Aspect Alteration for Visual Content</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-mac-enthusiasts-take-on-screenflow-software-review/"><u>[Updated] 2024 Approved  Mac Enthusiast's Take on ScreenFlow Software Review</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-honor-magic-5-lite-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Honor Magic 5 Lite Phone Screen?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-loilo-game-recorder-complete-review-for-2024/"><u>The LoiLo Game Recorder [Complete Review] for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-audio-output-on-microsofts-read-aloud-functionality/"><u>Resetting Audio Output on Microsoft's Read Aloud Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Xiaomi Redmi Note 13 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-14-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 14 To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-art-of-video-symbolism-6-websites-where-creativity-thrives/"><u>2024 Approved  The Art of Video Symbolism  6 Websites Where Creativity Thrives</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-samsung-galaxy-a54-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Samsung Galaxy A54 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-the-pathway-to-professional-pc-livestreams-with-tiktok/"><u>[Updated] The Pathway to Professional PC Livestreams with TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-stream-to-screen-how-to-download-youtube-on-iphoneipad/"><u>[Updated] 2024 Approved  From Stream to Screen  How to Download Youtube on iPhone/iPad</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-reno-11f-5g-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo Reno 11F 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-5-best-free-online-video-editors-similar-to-imovie-updated-2023/"><u>New 5 Best Free Online Video Editors Similar to iMovie (Updated 2023)</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
</ul></div>
