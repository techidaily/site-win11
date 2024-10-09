---
title: "Tutorial: Restoring Original Input Layout on Windows 11 PCs"
date: 2024-10-06T04:18:58.807Z
updated: 2024-10-09T10:06:40.417Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-datasafe-experts-assessment/"><u>[New] 2024 Approved DataSafe Experts Assessment</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-your-top-tools-for-facebook-video-retrieval-revealed/"><u>[New] Your Top Tools for Facebook Video Retrieval Revealed</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-top-tips-for-creating-instagrammable-unboxing-highlights/"><u>2024 Approved Top Tips for Creating Instagrammable Unboxing Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-create-a-mobile-internet-access-point-with-windows-11/"><u>Effortlessly Create a Mobile Internet Access Point with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-app-fixes-to-perfect-your-windows-experience/"><u>Essential App Fixes to Perfect Your Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-n-editions-it-perspective/"><u>Exploring Windows N Editions: IT Perspective</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-non-functional-hotspot-on-windows-11-devices/"><u>How To Fix a Non-Functional Hotspot on Windows 11 Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-honor-80-pro-straight-screen-edition-by-drfone-android/"><u>How to Show Wi-Fi Password on Honor 80 Pro Straight Screen Edition</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Vivo Y28 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-thorough-examination-of-dji-inspire-1/"><u>In 2024, Thorough Examination of DJI Inspire 1</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-frozen-wow-63-patch/"><u>Jumpstart Your Frozen WoW 6.3 Patch</u></a></li>
<li><a href="https://extra-support.techidaily.com/key-methods-to-change-music-speedplay-on-spotify-for-2024/"><u>Key Methods to Change Music Speedplay on Spotify for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/per-screen-prowess-custom-themes-for-every-monitor-in-win-1011/"><u>Per-Screen Prowess: Custom Themes for Every Monitor in WIN 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-initiating-mouse-gestures-in-microsoft-edge-windows-11/"><u>Quick Guide: Initiating Mouse Gestures in Microsoft Edge, Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/steps-to-change-ebooks-in-audible-aa-format-into-a-playable-mp3-version/"><u>Steps to Change Ebooks in Audible .aa Format Into a Playable MP3 Version</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-oppo-a58-4g-by-drfone-android/"><u>Three Ways to Sim Unlock Oppo A58 4G</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pcs-control-center-on-windows-11/"><u>Unlocking Your PC's Control Center on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/vintage-visuals-redefined-employing-retroarchs-modern-shaders/"><u>Vintage Visuals Redefined: Employing RetroArch’s Modern Shaders</u></a></li>
</ul></div>

