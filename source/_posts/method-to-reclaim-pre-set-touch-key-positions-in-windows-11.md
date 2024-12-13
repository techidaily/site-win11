---
title: Method to Reclaim Pre-Set Touch Key Positions in Windows 11
date: 2024-12-07T06:50:32.746Z
updated: 2024-12-12T23:29:15.468Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/ed-best-practices-in-youtube-keyword-selection-for-2024/"><u>[Updated] Best Practices in YouTube Keyword Selection for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-how-to-respond-to-unexpected-content-rejections-by-fb-platform/"><u>2024 Approved How to Respond to Unexpected Content Rejections by FB Platform</u></a></li>
<li><a href="https://win11.techidaily.com/easy-sticknotes-setup-for-optimal-note-taking-in-win11win10/"><u>Easy StickNotes Setup for Optimal Note-Taking in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-cure-for-windows-11-drag-glitches/"><u>Immediate Cure for Windows 11 Drag Glitches</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-hone-your-message-effective-use-of-templates-for-shorts/"><u>In 2024, Hone Your Message Effective Use of Templates for Shorts</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-apple-iphone-6s-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the Apple iPhone 6s Without Previous Owner?</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-win-rpc-failures-five-essential-steps/"><u>Preventing Win RPC Failures: Five Essential Steps</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-sluggishness-in-microsoft-edge-win10w11/"><u>Solutions for Sluggishness in Microsoft Edge, Win10/W11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/the-art-of-podcast-storytelling-writing-tips-and-example-guides/"><u>The Art of Podcast Storytelling Writing Tips & Example Guides</u></a></li>
<li><a href="https://win11.techidaily.com/the-new-frontier-of-programming-with-microsoft-copilot/"><u>The New Frontier of Programming with Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-power-5-must-try-apps-to-supercharge-windows-productivity/"><u>Unleashing Power: 5 Must-Try Apps to Supercharge Windows Productivity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/webcam-safety-starts-here-the-10-best-shields/"><u>Webcam Safety Starts Here - The 10 Best Shields</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-11-audio-restoration-how-to-bring-back-the-buzz-and-boom/"><u>Windows 11 Audio Restoration: How to Bring Back the Buzz and Boom</u></a></li>
<li><a href="https://win11.techidaily.com/winrar-integrity-restoration-6-summation-error-solutions/"><u>WinRAR Integrity Restoration: 6 Summation Error Solutions</u></a></li>
</ul></div>

