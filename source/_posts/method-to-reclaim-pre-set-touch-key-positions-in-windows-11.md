---
title: Method to Reclaim Pre-Set Touch Key Positions in Windows 11
date: 2024-11-30T23:43:29.087Z
updated: 2024-12-07T11:26:56.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method to Reclaim Pre-Set Touch Key Positions in Windows 11
excerpt: This Article Describes Method to Reclaim Pre-Set Touch Key Positions in Windows 11
keywords: Win11 Touch Position Fixing,Reinstating Default Touch Gestures,Windows 11 Keyboard Layout Restore,Reclaim Touch Control Positions,Adjusting Touch Keys in Win11,Resetting Windows 11 Touch Settings,Correcting Key Position Errors
thumbnail: https://thmb.techidaily.com/0b17306a3ff43a3354c035a000988ea5867c75fb650ef14b9ada7d7d6b9ca442.jpg
---

## Method to Reclaim Pre-Set Touch Key Positions in Windows 11

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-guide-tackling-youtube-shorts-issues/"><u>[New] The Ultimate Guide Tackling YouTube Shorts Issues</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-digitally-liberated-fb-tunes/"><u>[Updated] In 2024, Digitally Liberated FB Tunes</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-ultimate-method-for-adding-high-quality-srt-to-mp4-videos/"><u>2024 Approved The Ultimate Method for Adding High-Quality SRT to MP4 Videos</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-on-decorative-images-in-win-search/"><u>Cutting Down on Decorative Images in Win Search</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dilemnas-windows-fingerprint-hacking-concerns-rising/"><u>Digital Dilemnas: Windows Fingerprint Hacking Concerns Rising</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/germanys-language-milestone-with-mondly-as-the-leader/"><u>Germany's Language Milestone with Mondly as the Leader</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-apple-iphone-14-pro-imei-checker-by-drfone-ios/"><u>In 2024, Best Free Apple iPhone 14 Pro IMEI Checker</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-s23-fe-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy S23 FE Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-changefake-your-tecno-camon-20-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Tecno Camon 20 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-fixing-dxgierror-zerodx887a0006-in-win11/"><u>Quick Guide to Fixing DXGIError ZeroDX887A0006 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-older-features-of-photo-viewer-with-this-guide-for-win11/"><u>Reviving Older Features of Photo Viewer with This Guide for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-epic-launcher-sign-in-woes-on-pc/"><u>Tackling the Epic Launcher Sign-In Woes on PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-safe-harbor-understanding-s-mode/"><u>Windows 11'S Safe Harbor: Understanding S Mode</u></a></li>
</ul></div>

