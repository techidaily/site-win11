---
title: "Win 11: Set Default Touch Input Placement"
date: 2024-06-25T11:40:39.539Z
updated: 2024-06-26T11:40:39.539Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Set Default Touch Input Placement"
excerpt: "This Article Describes Win 11: Set Default Touch Input Placement"
keywords: Win 11 Quickset,Win 11 Touchplacement,Win 11 DefaultInput,AdjustWinTouchInput,ChangeDefaultPlacement,Win11TouchSettings,InputPlacementWin11
thumbnail: https://thmb.techidaily.com/7e37922976a0cd02bd45d34c10fef6f069d63ae07942af07cd489ff374cb4abd.png
---

## Win 11: Set Default Touch Input Placement

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
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://win11.techidaily.com/10-effective-command-line-steps-for-info-exploration/"><u>10 Effective Command-Line Steps for Info Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-recommended-games-on-windows-11-screen/"><u>Turn Off Recommended Games on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-update-failure-0x800f0845-error/"><u>Resolving Windows Update Failure: 0X800F0845 Error</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-photoshopping-in-windows-11-without-hurdles/"><u>Enabling Photoshopping in Windows 11 Without Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-package-unopenable-error-on-win11-10-oses/"><u>Eliminating the 'Package Unopenable' Error on Win11, 10 OSes</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-tips-to-add-audio-to-video-in-premiere-pro/"><u>Updated Tips to Add Audio to Video in Premiere Pro</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mint-magic-in-depth-analysis-and-instructions-for-ice-cream-cam/"><u>[Updated] Mint Magic  In-Depth Analysis & Instructions for Ice Cream Cam</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-high-resolution-revelations-comparing-ultrawide-and-uhd-4k-screens/"><u>[Updated] 2024 Approved  High-Resolution Revelations  Comparing UltraWide and UHD 4K Screens</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/androidplusios-ai-curated-instavideo-mosaic-for-2024/"><u>Android+iOS  AI-Curated InstaVideo Mosaic for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-rejuvenated-dialogue-ideas-to-hook-listeners/"><u>[New] Rejuvenated Dialogue Ideas to Hook Listeners</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-accessible-visual-aids-for-youtube-videos/"><u>[New] 2024 Approved  Accessible Visual Aids for YouTube Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-most-downloaded-android-apps-of-the-month/"><u>New In 2024, Most-Downloaded Android Apps of the Month</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/visual-wonders-the-10-list-of-exceptional-4k-for-macs/"><u>Visual Wonders  The #10 List of Exceptional 4K for Macs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-4-ways-how-to-download-videos-from-facebook-messenger/"><u>[Updated] In 2024, 4 Ways | How to Download Videos From Facebook Messenger?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mirthful-montage-mastering-7-comical-video-vignettes-for-2024/"><u>Mirthful Montage  Mastering 7 Comical Video Vignettes for 2024</u></a></li>
</ul></div>
