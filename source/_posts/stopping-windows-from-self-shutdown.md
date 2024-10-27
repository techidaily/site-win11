---
title: Stopping Windows From Self-Shutdown
date: 2024-10-22T19:17:30.074Z
updated: 2024-10-27T06:41:05.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Windows From Self-Shutdown
excerpt: This Article Describes Stopping Windows From Self-Shutdown
keywords: Preventing Windows Shutdown,Stop Windows AutoRestart,Windows Safeguard Against Turnoff,Avoid PC Automatic Off,Halt Windows Self-Closure,Disable Windows Shutdown Feature,Control Windows Power Off
thumbnail: https://thmb.techidaily.com/5a836c04a4d923a2e47e122afc97ffb5e93afa98d18b4563b5a8924a658295ed.jpg
---

## Stopping Windows From Self-Shutdown

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Finally, restart your computer to see if a lock screen appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-boosting-your-channels-viewer-count-12-must-try-approaches-for-2024/"><u>[New] Boosting Your Channel's Viewer Count - 12 Must-Try Approaches for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-the-ultimate-pathway-to-successful-uploads-on-youtube/"><u>[New] In 2024, The Ultimate Pathway to Successful Uploads on YouTube</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-beyond-the-veil-of-space-time-the-greatest-sci-fi-films-experiences/"><u>[Updated] 2024 Approved Beyond the Veil of Space-Time The Greatest Sci-Fi Films' Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-error-x70-your-path-to-data-recovery/"><u>Demystifying Windows Error X70: Your Path to Data Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/digital-guardrails-7-practices-to-halt-uac-breaches/"><u>Digital Guardrails: 7 Practices to Halt UAC Breaches</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-instagram-video-restrictions-what-you-must-know/"><u>In 2024, Instagram Video Restrictions What You Must Know</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-poco-m6-pro-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Poco M6 Pro 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/maximizing-engagement-a-pathway-to-higher-subscriber-numbers-for-2024/"><u>Maximizing Engagement A Pathway to Higher Subscriber Numbers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-functionality-with-win11s-widget-bar/"><u>Maximizing Functionality with Win11's Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-disrupted-windows-update-on-discord/"><u>Navigating a Disrupted Windows Update on Discord</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/oodle-delivers-top-notch-community-offers-dive-into-our-extensive-selection-of-costless-listings/"><u>Oodle Delivers Top-Notch Community Offers - Dive Into Our Extensive Selection of Costless Listings</u></a></li>
<li><a href="https://win11.techidaily.com/self-sufficient-storage-duplication-techniques/"><u>Self-Sufficient Storage Duplication Techniques</u></a></li>
<li><a href="https://youtube-web.techidaily.com/thy-search-strategies-for-elusive-youtube-videos/"><u>Stealthy Search Strategies for Elusive YouTube Videos</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-ultimate-guide-to-overcoming-the-cannot-open-game-error-in-league-of-legends/"><u>The Ultimate Guide to Overcoming the 'Cannot Open Game' Error in League of Legends</u></a></li>
</ul></div>

