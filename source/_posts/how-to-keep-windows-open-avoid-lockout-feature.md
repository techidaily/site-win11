---
title: "How To Keep Windows Open: Avoid Lockout Feature"
date: 2024-06-25T11:24:11.893Z
updated: 2024-06-26T11:24:11.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How To Keep Windows Open: Avoid Lockout Feature"
excerpt: "This Article Describes How To Keep Windows Open: Avoid Lockout Feature"
keywords: Keeping Windows Airy,Unlock Window Tips,Prevent Lockout Errors,Ventilate Windows Safely,Easy Window Access,Avoid Lockdown Issue,Open Windows Method
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## How To Keep Windows Open: Avoid Lockout Feature

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

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

Finally, restart your computer to see if a lock screen appears.

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
<li><a href="https://win11.techidaily.com/fixing-xc0f1103f-issue-with-geforce-now-on-windows/"><u>Fixing XC0F1103F Issue with GeForce Now on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-keyboard-method-to-resize-programs/"><u>Navigating Windows 11'S Keyboard Method to Resize Programs</u></a></li>
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-directx-update-failure-in-windows-systems/"><u>Overcoming DirectX Update Failure in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-downloads-not-working-on-win-devices/"><u>How to Resolve Downloads Not Working on Win Devices</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-swift-rescaling-perfect-mac-pixels-with-youtube/"><u>2024 Approved  Swift Rescaling  Perfect Mac Pixels with YouTube</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-find-out-what-the-flexclip-trimmer-is-its-key-features-and-how-to-use-it-to-trim-your-videos-to-remove-unwanted-parts-with-just-a-few-clicks/"><u>New Find Out What the Flexclip Trimmer Is, Its Key Features, and How to Use It to Trim Your Videos to Remove Unwanted Parts with Just a Few Clicks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/perfecting-highlight-covers-an-in-depth-insta-photography-guide-for-2024/"><u>Perfecting Highlight Covers  An In-Depth Insta Photography Guide for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-tweet-tracks-top-ranked-amazon-originals-on-twittersphere/"><u>[New] 2024 Approved  Tweet Tracks  Top-Ranked Amazon Originals on Twittersphere</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-capturing-presentations-effortlessly-a-guide-to-screen-capture-for-2024/"><u>[Updated] Capturing Presentations Effortlessly  A Guide to Screen Capture for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-create-sports-intro-and-outro-for-youtube-video/"><u>How to Create Sports Intro and Outro for YouTube Video?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-art-of-video-thumbnail-making-for-popular-content-for-2024/"><u>The Art of Video Thumbnail Making for Popular Content for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-analyzing-investment-for-video-promotion/"><u>[New] 2024 Approved  Analyzing Investment for Video Promotion</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-mac-for-iphone-7-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock on Mac For iPhone 7?</u></a></li>
</ul></div>
