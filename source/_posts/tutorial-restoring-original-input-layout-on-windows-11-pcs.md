---
title: "Tutorial: Restoring Original Input Layout on Windows 11 PCs"
date: 2024-09-14T08:30:42.580Z
updated: 2024-09-17T01:34:52.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Restoring Original Input Layout on Windows 11 PCs"
excerpt: "This Article Describes Tutorial: Restoring Original Input Layout on Windows 11 PCs"
keywords: Windows 11 Input Guide,Restore Window 11 Layout,Laptop Input Restoration,Win11 Input Reset Tutorial,Revert Windows Input Design,PC Input Redo Steps,Launcher Display Fix Window 11
thumbnail: https://thmb.techidaily.com/2abff2026ed0f77bee3d5444a73ceb2a838092ecb3114e177d3896df7011b647.jpg
---

## Tutorial: Restoring Original Input Layout on Windows 11 PCs

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

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-10-best-history-youtube-channels-for-students-and-history-lovers/"><u>[New] 2024 Approved 10 Best History YouTube Channels for Students & History Lovers</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-mastering-the-art-of-social-media-sharing-with-convertors/"><u>[New] Mastering the Art of Social Media Sharing with Convertors</u></a></li>
<li><a href="https://win11.techidaily.com/ps3/"><u>「無料・迅速：動画をPS3用に適した形式にするテクニック」</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-constant-media-recording-specialists/"><u>2024 Approved Constant Media Recording Specialists</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Xiaomi Redmi A2? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-best-solarmovie-alternatives-watch-movies-online-for-2024/"><u>New Best SolarMovie Alternatives-Watch Movies Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-your-dvd-collection-expert-tips-on-effortlessly-switching-from-dvd-to-mp4-offline-options-included/"><u>Preserving Your DVD Collection: Expert Tips on Effortlessly Switching From DVD to MP4, Offline Options Included!</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-effective-methods-for-converting-your-wma-audio-to-wav-quality/"><u>Quick & Effective Methods for Converting Your WMA Audio to WAV Quality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-crafting-tailored-listening-sessions-with-windows-media-player/"><u>Quick Guide to Crafting Tailored Listening Sessions with Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/returning-to-basics-the-revival-of-apples-traditional-roots/"><u>Returning to Basics: The Revival of Apple's Traditional Roots</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-tutorial-learn-how-to-take-efficient-screenshots-on-any-desktop-pc/"><u>The Ultimate Tutorial: Learn How to Take Efficient Screenshots on Any Desktop PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/upgrading-your-videos-to-high-definition-or-4k-tips-for-pc-and-mac-users/"><u>Upgrading Your Videos to High Definition or 4K: Tips for PC and Mac Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

