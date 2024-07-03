---
title: "Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards"
date: 2024-06-25T11:25:53.623Z
updated: 2024-06-26T11:25:53.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards"
excerpt: "This Article Describes Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards"
keywords: Windows 11 Keyboard Layouts,Default Input Method Setup,Win 11 Accessibility Features,Typing Efficiency in Windows 11,Configuring Win 11 Keyboard Placement,Home Screen Optimization Win 11,Customizing Windows Keyboard Display
thumbnail: https://thmb.techidaily.com/482035835ea328d1609501451811446cad884a7a61227ca3ca092b735291d94d.jpg
---

## Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

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
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stuck-scrolling-in-excel-window-edition/"><u>Solutions for Stuck Scrolling in Excel, Window Edition</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-ceasing-wired-pc-keyboard-on-windows/"><u>Tutorial: Ceasing Wired PC Keyboard on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-10-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-heart-of-windows-11-registry-explained/"><u>Delving Into the Heart of Windows 11: Registry Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-tracking-disk-space-usage-in-windows-pcs/"><u>The Ultimate Guide to Tracking Disk Space Usage in Windows PCs</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-oppo-find-x6-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Oppo Find X6 FRP</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-7-enhancements-for-an-optimal-stardew-farming-experience-for-2024/"><u>[New] Top 7 Enhancements for an Optimal Stardew Farming Experience for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-breakthrough-in-video-production-advanced-techniques-for-uploading-360-content-on-youtube-for-2024/"><u>[Updated] Breakthrough in Video Production  Advanced Techniques for Uploading 360° Content on YouTube for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oppo-a2-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Oppo A2 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-lava-agni-2-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Lava Agni 2 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-energetic-speaker-review-iteration-viii/"><u>[New] Energetic Speaker Review - Iteration VIII</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/sonic-layers-in-reels-weaving-audio-into-visuals-for-2024/"><u>Sonic Layers in Reels  Weaving Audio Into Visuals for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/best-free-iphone-video-rotation-apps-top-picks/"><u>Best Free iPhone Video Rotation Apps Top Picks</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-motorola-edge-40-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Motorola Edge 40 Devices | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo Y100 | Dr.fone</u></a></li>
</ul></div>
