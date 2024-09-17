---
title: Techniques to Prevent Automatic Shutdown Timer
date: 2024-09-15T01:58:25.559Z
updated: 2024-09-17T02:27:18.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Prevent Automatic Shutdown Timer
excerpt: This Article Describes Techniques to Prevent Automatic Shutdown Timer
keywords: Stop Shutdown Alerts,Prevent Power Off,Avoid System Clock,Stay Online Safety,Halt Auto-Shutdown,Stop Timer Shutdown,Disable Automatic Timeout
thumbnail: https://thmb.techidaily.com/e83f983f9af6b6adf732e263161638d4efc710da8fc4b32e0850fa910996aed9.jpg
---

## Techniques to Prevent Automatic Shutdown Timer

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Is Windows 10 Automatically Locking Itself?

 Windows automatically locks itself for one simple reason: to protect your privacy.

 Imagine a scenario where you have to leave your computer unattended for an extended period. If there is no auto-lock on Windows, anyone can use your PC for any reason without any repercussions.

 By locking itself automatically once your PC goes into sleep mode, Windows ensures that your data stays private and nobody except you has access to your computer.

## How to Stop Windows From Automatically Locking Itself

You can stop Windows from automatically locking itself by:

* Disabling Windows sign-in.
* Disabling sleep mode and screen saver.
* Editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to disable auto-locking.

Now that we know how to do it, let's dive into the steps.

### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

### Editing Windows Registry to Disable Auto-Locking

 Finally, you can also edit Windows Registry to stop Windows from automatically locking itself. Before we show you how to do this, make sure you understand that editing Windows Registry can make your system unstable requiring you to restart or even[perform a fresh Windows install](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) for your PC to work properly again.

So, edit Windows Registry only when nothing else works.

* Hit the Windows keys, type “registry”, right-click on**Registry Editor** , and select**Run as administrator** .
* In Registry Editor, navigate to**HKEY\_LOCAL\_MACHINE** \>**Software** \>**Policies** \>**Microsoft** .
* Next, right-click on**Windows** , select**New** , and choose**Key** to define a new key/create a new folder in Windows Registry. Name the new folder something like “Disable autoLock”.
* Now, right-click on the folder you just created, place the mouse cursor over**New** , and select**DWORD (32-bit) Value** . Change the name of this new element to “NoLockScreen”.
* Open**NoLockScreen** and set the Value data to 1\. Press ok to finish the process.

![Disable auto-lock from Windows Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-auto-lock-registry.JPG)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115926/19272" target="_top" id="2115926">
  <img src="//a.impactradius-go.com/display-ad/19272-2115926" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115926/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Finally, restart your computer to see if a lock screen appears.

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Use Windows Hello to Make Windows’ Auto-Locking Bearable

 If your PC or notebook has facial recognition or a fingerprint reader, you can set up Windows Hello to make sign-ins a breeze.

 On supported computers, Windows Hello can instantly recognize your face/fingerprint to log you in, taking the hassle out of typing a password in case of Windows auto-locking itself.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-how-to-charm-your-way-into-a-friends-tiktok-show/"><u>[New] How to Charm Your Way Into a Friend’s TikTok Show</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-streamlined-coordination-the-best-facebook-timetellers-ranked/"><u>[Updated] 2024 Approved Streamlined Coordination The Best Facebook Timetellers Ranked</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-expertise-for-changing-meet-usernames-laptopmobile-for-2024/"><u>[Updated] Expertise for Changing Meet Usernames (Laptop/Mobile) for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-the-maze-of-zoom-broadcasting-tools/"><u>2024 Approved Navigating the Maze of Zoom Broadcasting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/windows-and-mac4/"><u>動画画角トリミング: Windows & Macで実行可能な4手法</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/compatible-drivers-for-your-epson-xp-640-finding-and-installing-updates-on-windows/"><u>Compatible Drivers for Your Epson XP-640: Finding and Installing Updates on Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-move-custom-ringtones-from-apple-iphone-12-to-android-drfone-by-drfone-transfer-from-ios/"><u>How to Move Custom Ringtones from Apple iPhone 12 to Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-harnessing-hdr-in-post-top-4-youtube-guides-with-complimentary-green-screen-effects/"><u>In 2024, Harnessing HDR in Post Top 4 YouTube Guides with Complimentary Green Screen Effects</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-on-transforming-diverse-media-formats-videos-and-audios-simplified/"><u>Ultimate Tutorial on Transforming Diverse Media Formats - Videos & Audios Simplified</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-on-transforming-vcd-audio-tracks-into-mp3-format/"><u>Ultimate Tutorial on Transforming VCD Audio Tracks Into MP3 Format</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/uncovering-all-shared-visuals-in-a-message-thread/"><u>Uncovering All Shared Visuals in a Message Thread</u></a></li>
<li><a href="https://win11.techidaily.com/uno-bindas-download-de-videos-de-aerobic-una-guia-completa-para-el-usuario-promedio/"><u>Uno Bindas Download De Vídeos De Aerobic: Una Guía Completa Para El Usuario Promedio</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-image-cropping-in-fcpx-essential-techniques-for-editors-for-2024/"><u>Updated Image Cropping in FCPX Essential Techniques for Editors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-dvd-8/"><u>Windows 11対応 DVD コピープロテクトを解除するための無料ツール、ベスト8推薦</u></a></li>
</ul></div>

