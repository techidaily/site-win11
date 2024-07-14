---
title: "Win 11: Set Default Touch Input Placement"
date: 2024-07-13T10:50:59.870Z
updated: 2024-07-14T10:50:59.870Z
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

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

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
<li><a href="https://tiktok-clips.techidaily.com/intuitive-camera-roll-consolidation-step-by-step-snapchat-guide/"><u>Intuitive Camera Roll Consolidation  Step-by-Step Snapchat Guide</u></a></li>
<li><a href="https://win11.techidaily.com/7-expert-moves-for-restoring-the-functionality-of-windows-services-control-panel/"><u>7 Expert Moves for Restoring the Functionality of Windows Services Control Panel</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-action-cam-war-gopros-hero5-versus-garmin-virb/"><u>2024 Approved  Action Cam War  GoPro's Hero5 Versus Garmin VIRB</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-shielding-game-data/"><u>A Step-by-Step Guide to Shielding Game Data</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/virtual-birdsongs-library-download/"><u>Virtual Birdsongs Library Download</u></a></li>
<li><a href="https://win11.techidaily.com/1719367006018-need-windows-help-find-support-tips-and-solutions/"><u>Need Windows Help? Find Support Tips & Solutions!</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sj7s-latest-4k-star-cam-a-revolutionary-action-recorder/"><u>2024 Approved  SJ7's Latest 4K Star Cam - A Revolutionary Action Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-the-windows-snip-and-sketch-tool-wont-screenshot-the-entire-screen/"><u>4 Fixes to Try if the Windows Snip & Sketch Tool Won’t Screenshot the Entire Screen</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-snickel-and-snicker-5-best-meme-generating-apps/"><u>[Updated] Snickel & Snicker  5 Best Meme Generating Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-from-boring-to-brilliant-10-animated-text-converters-youll-love/"><u>Updated In 2024, From Boring to Brilliant 10 Animated Text Converters Youll Love</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-next-gen-platform-for-12-hourly-live-broadcasts/"><u>In 2024, Next-Gen Platform for 12 Hourly Live Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-find-the-mac-address-on-windows-11/"><u>4 Ways to Find the MAC Address on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenhensive-guide-to-windows-graphics-reset-techniques/"><u>A Compreenhensive Guide to Windows Graphics Reset Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/1719370462941-understanding-power-settings-save-charges/"><u>Understanding Power Settings - Save Charges</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-poco-x6-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Poco X6 Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-changing-esd-into-an-iso-for-windows-pcs/"><u>A Beginner's Guide to Changing ESD Into an ISO for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-the-windows-startup-settings/"><u>A Complete Guide to the Windows Startup Settings</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-frameforge-review-the-ultimate-guide-to-capturing-tech/"><u>[New] 2024 Approved  FrameForge Review  The Ultimate Guide to Capturing Tech</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-for-restoring-windows-hello-fingerprint-functionality/"><u>7 Key Steps for Restoring Windows Hello Fingerprint Functionality</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-superior-smartphone-apps-the-best-for-gopro-editing/"><u>In 2024, Superior Smartphone Apps  The Best for GoPro Editing</u></a></li>
<li><a href="https://win11.techidaily.com/6-disappearing-windows-traits-explained/"><u>6 Disappearing Windows Traits Explained</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fiscal-landmarks-understanding-mr-beasts-financial-growth/"><u>[Updated] In 2024, Fiscal Landmarks  Understanding Mr. Beast’s Financial Growth</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/1719371064101-windows-11-ready-embrace-google-chrome-now/"><u>Windows 11 Ready? Embrace Google Chrome Now</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-make-windows-11-start-up-faster/"><u>3 Ways to Make Windows 11 Start Up Faster</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/fine-tune-video-quality-for-instagram-excellence-for-2024/"><u>Fine-Tune Video Quality for Instagram Excellence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719329356847-chrome-freezing-woes-on-win11-try-these-swift-solutions/"><u>Chrome Freezing Woes on Win11? Try These Swift Solutions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-smooth-visual-journeys-master-fades-in-a-flash-for-2024/"><u>[Updated] Smooth Visual Journeys  Master Fades in a Flash for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-change-themes-on-windows-11/"><u>9 Ways to Change Themes On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-local-device-name-is-already-in-use-error-on-windows/"><u>5 Ways to Fix the Local Device Name Is Already in Use Error on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/capturing-photographs-from-movies-in-windows-photos-app-for-savvy-users-for-2024/"><u>Capturing Photographs From Movies in Windows Photos App for Savvy Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-tecno-pova-5-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Tecno Pova 5 phone? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/excellence-in-gaming-graphics-at-4k-speeds-for-2024/"><u>Excellence in Gaming Graphics at 4K Speeds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-guide-to-infusing-personality-into-your-calendar/"><u>A Window's Guide to Infusing Personality Into Your Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/1719367274054-overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-windows-tasks-with-top-5-car-drivers/"><u>Accelerate Windows Tasks with Top 5 Car Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/a-visionary-approach-to-taskbar-design-essential-improvements-for-microsofts-new-release/"><u>A Visionary Approach to Taskbar Design: Essential Improvements for Microsoft's New Release</u></a></li>
<li><a href="https://review-topics.techidaily.com/mov-to-galaxy-z-flip-5-converter-convert-mov-files-for-galaxy-z-flip-5-by-aiseesoft-video-converter-play-mov-on-android/"><u>MOV to Galaxy Z Flip 5 converter-convert .mov files for Galaxy Z Flip 5</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-video-editing-mastery-a-beginners-guide-to-online-download-and-editing/"><u>Updated 2024 Approved Video Editing Mastery A Beginners Guide to Online Download and Editing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-locked-xiaomi-redmi-note-12t-pro-phone-by-drfone-android/"><u>How to Reset a Locked Xiaomi Redmi Note 12T Pro Phone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-optimizing-video-focus-in-virtual-collaboration-spaces-google-meet-edition/"><u>In 2024, Optimizing Video Focus in Virtual Collaboration Spaces  Google Meet Edition</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-revolutionary-gameplay-preservation-with-advanced-fbx-recording/"><u>In 2024, Revolutionary Gameplay Preservation with Advanced FBX Recording</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-narzo-60-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme Narzo 60 5G Phones with/without a PC</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-navigating-picture-in-picture-mode-with-ease-in-microsoft-edge-for-2024/"><u>[Updated] Navigating Picture-In-Picture Mode with Ease in Microsoft Edge for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-sign-in-method-youre-trying-to-use-isnt-allowed-error-on-windows/"><u>8 Ways to Fix The Sign-In Method You're Trying to Use Isn't Allowed Error on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/start-shooting-smart-top-15-shot-techniques-for-beginners/"><u>Start Shooting Smart  Top 15 Shot Techniques for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/7-exciting-additions-on-the-horizon-for-windows-11s-moment-22h2/"><u>7 Exciting Additions on the Horizon for Windows 11'S Moment #22H2</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-top-7-best-waterproof-action-camera/"><u>[Updated] Top 7 Best Waterproof Action Camera</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ten-practices-to-avoid-vr-motion-sickness/"><u>[New] Ten Practices to Avoid VR Motion Sickness</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-accessing-windows-fix/"><u>A Comprehensible Guide to Accessing Windows Fix</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-remedy-onedrives-blob-tag-inaccuracy-error/"><u>A Guide to Remedy OneDrive's Blob Tag Inaccuracy Error</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-intel-wi-fi-6-ax201-160-mhz-driver-is-not-working-error-on-windows/"><u>8 Ways to Fix “The Intel Wi-Fi 6 AX201 160 MHz Driver Is Not Working” Error on Windows</u></a></li>
</ul></div>
