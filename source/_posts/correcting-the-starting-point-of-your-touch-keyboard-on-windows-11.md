---
title: Correcting the Starting Point of Your Touch Keyboard on Windows 11
date: 2024-10-23T04:55:23.936Z
updated: 2024-10-27T00:43:22.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting the Starting Point of Your Touch Keyboard on Windows 11
excerpt: This Article Describes Correcting the Starting Point of Your Touch Keyboard on Windows 11
keywords: Win11 Startup Fix,TouchKeyboard Correction,Windows Input Repair,Ergonomic Typing Setup,Keyboard Position Adjust,Windows 11 Text Input,Correct Keyboard Layout
thumbnail: https://thmb.techidaily.com/c74a6f4cbc3131991d1108cc0cd3851c9f4624d9f7132bc54e3318b3d6ad9b70.jpg
---

## Correcting the Starting Point of Your Touch Keyboard on Windows 11

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-archive-storing-your-iphone-images-and-videos/"><u>[Updated] Instagram Archive Storing Your iPhone Images and Videos</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-essential-guide-pick-from-8-great-free-android-mp3-clients/"><u>2024 Approved Essential Guide Pick From 8 Great Free Android MP3 Clients</u></a></li>
<li><a href="https://fox-that.techidaily.com/guide-to-solve-iphone-error-4013-during-software-updaterestoration/"><u>Guide to Solve iPhone Error 4013 During Software Update/Restoration</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-everything-you-need-to-succeed-with-youtube-short-videos/"><u>In 2024, Everything You Need to Succeed with YouTube Short Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-making-mp3-from-instagram-visual-content/"><u>In 2024, Making MP3 From Instagram Visual Content</u></a></li>
<li><a href="https://win11.techidaily.com/launching-the-speedy-assistance-mechanism-in-w11/"><u>Launching the Speedy Assistance Mechanism in W11</u></a></li>
<li><a href="https://article-helps.techidaily.com/maximize-your-laptops-dvd-potential-easily-for-2024/"><u>Maximize Your Laptop's DVD Potential Easily for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/noise-reduction-for-better-video-experiences-on-youtube-for-2024/"><u>Noise Reduction for Better Video Experiences on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-black-window-after-system-ignition/"><u>Remedying Black Window After System Ignition</u></a></li>
<li><a href="https://buynow-info.techidaily.com/tablet-face-off-analyzing-the-distinctions-between-ipad-pro-and-microsoft-surface-pro/"><u>Tablet Face-Off: Analyzing the Distinctions Between iPad Pro and Microsoft Surface Pro</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-building-an-immaculate-desktop-computer-with-top-notch-performance/"><u>Ultimate Guide: Building an Immaculate Desktop Computer with Top-Notch Performance</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pcs-full-potential-in-games-the-win-11-master-plan-of-7-actions/"><u>Unlock Your PC's Full Potential in Games: The Win 11 Master Plan of 7 Actions</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-solutions-the-ultimate-guide-to-fixing-e84-in-steam/"><u>Unwrapping Solutions: The Ultimate Guide to Fixing E84 in Steam</u></a></li>
</ul></div>

