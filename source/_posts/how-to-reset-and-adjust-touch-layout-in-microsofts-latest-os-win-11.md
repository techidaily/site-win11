---
title: How to Reset and Adjust Touch Layout in Microsoft's Latest OS, Win 11
date: 2024-12-06T04:23:45.898Z
updated: 2024-12-06T17:55:53.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset and Adjust Touch Layout in Microsoft's Latest OS, Win 11
excerpt: This Article Describes How to Reset and Adjust Touch Layout in Microsoft's Latest OS, Win 11
keywords: Windows 11 Touch Customization,Resetting Win 11 Settings,Win 11 Display Adjustment,Microsoft OS Layout Tweaks,Touch Screen Configuration Win 11,Optimize Win 11 UI,Reset & Tweak Windows 11
thumbnail: https://thmb.techidaily.com/f86055b0c210c48b3bc87c8b80af070af1138eb8ba02388288320b33c5951f16.jpeg
---

## How to Reset and Adjust Touch Layout in Microsoft's Latest OS, Win 11

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725289717112-winxdvd-dvd/"><u>搭配 WinXDVD 協力破解 DVD 密碼</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-ram-analysis-ranking-7-efficient-browsers/"><u>Comprehensive Ram Analysis: Ranking 7 Efficient Browsers</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723011297941-how-to-fix-persistent-screen-flickering-in-call-of-duty-warzone/"><u>How to Fix Persistent Screen Flickering in Call of Duty: Warzone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-error-code-0x80072f8f-0x20000-on-windows/"><u>How to Fix the Error Code 0X80072f8f - 0X20000 on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-13-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 13 Pro Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windows-11-multi-tasking-like-a-pro/"><u>Navigating the World of Window's 11 Multi-Tasking Like a Pro</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-the-step-by-step-guide-to-mastering-voice-change-with-voice-changer-plus-on-your-iphone/"><u>New In 2024, The Step-by-Step Guide to Mastering Voice Change with Voice Changer Plus on Your iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-microsoft-teams-freeze-in-wins-11-and-10/"><u>Preventive Measures for Microsoft Teams Freeze in Wins 11 & 10</u></a></li>
</ul></div>

