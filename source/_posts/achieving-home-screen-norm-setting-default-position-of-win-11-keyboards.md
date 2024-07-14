---
title: "Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards"
date: 2024-07-13T09:57:05.667Z
updated: 2024-07-14T09:57:05.667Z
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
<li><a href="https://win11.techidaily.com/what-to-do-if-the-lock-screen-timeout-stops-working-on-windows/"><u>What to Do if the Lock Screen Timeout Stops Working on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-nubia-z50s-pro-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Nubia Z50S Pro? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-struggles-lack-of-drive-letters-explained-and-cured/"><u>Windows Struggles: Lack of Drive Letters Explained & Cured</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/silence-windows-software-update-messages/"><u>Silence Windows Software Update Messages</u></a></li>
<li><a href="https://win11.techidaily.com/suppress-sound-enhancement-in-windows-os/"><u>Suppress Sound Enhancement in Windows OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-toggle-off-instagram-tv-feature/"><u>2024 Approved  Toggle Off Instagram TV Feature</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-textual-form-from-vocal-input-in-windows-via-whisper/"><u>Unlock Textual Form From Vocal Input in Windows via Whisper</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-stepwise-voice-transformation-techniques-for-tiktokers/"><u>[New] Stepwise Voice Transformation Techniques for TikTokers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-hidden-network-sight-fixing-windows-issue/"><u>Reviving Hidden Network Sight: Fixing Windows Issue</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10plus-users-unlocking-the-secrets-of-your-ram-type/"><u>Windows 10+ Users: Unlocking the Secrets of Your RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-making-ai-images-with-paint-tool-sai/"><u>Transform Windows 11: Making AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-explore-the-most-reliable-photo-background-alternation-apps/"><u>[New] Explore the Most Reliable Photo-Background Alternation Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-inside-track-becoming-an-expert-in-srt-technology/"><u>[New] Inside Track  Becoming an Expert in SRT Technology</u></a></li>
<li><a href="https://win11.techidaily.com/ace-file-moves-with-advanced-auto-transfer-techniques-on-win-11/"><u>Ace File Moves with Advanced Auto-Transfer Techniques on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-creativity-personalizing-windows-1011-screens/"><u>Unleash Creativity: Personalizing Windows 10/11 Screens</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-managing-directories-without-renaming-feature-in-win-11/"><u>The Ultimate Guide to Managing Directories Without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-steps-to-elevate-account-type/"><u>Swift Steps To Elevate Account Type</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-how-to-reset-final-cut-pro-x-to-troubleshoot-issues/"><u>Updated 2024 Approved How to Reset Final Cut Pro X to Troubleshoot Issues?</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mitigate-application-crashes-unhandled-exception-error/"><u>Steps to Mitigate Application Crashes: Unhandled Exception Error</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-ranking-the-top-avchd-video-editors/"><u>New Ranking the Top AVCHD Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-semaphore-timeout-period-ended-in-windows-1011/"><u>Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-microsoft-store-error-x00000000-in-win-11/"><u>Addressing the Microsoft Store Error X00000000 in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719358014112-chrome-woes-on-windows-11-a-fixers-guide-to-reopening-it/"><u>Chrome Woes on Windows 11: A Fixer’s Guide to Reopening It.</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-home-view-in-windows-11-settings/"><u>Unlock Home View in Windows 11 Settings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-flip-side-of-perspectives-crafting-engaging-images-with-angled-spins-on-instagram-sites/"><u>[New] The Flip-Side of Perspectives  Crafting Engaging Images with Angled Spins on Instagram Sites</u></a></li>
<li><a href="https://win11.techidaily.com/why-excel-fails-to-open-in-windows-notepad/"><u>Why Excel Fails to Open in Windows Notepad?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-tweeting-with-videos-a-quick-tutorial/"><u>[New] In 2024, Tweeting with Videos  A Quick Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-blue-screen-errors-with-vmware-on-win11/"><u>Strategies to Address Blue Screen Errors with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/screen-notes-made-easy-winning-sticky-pad-solutions-for-pc/"><u>Screen Notes Made Easy: Winning Sticky Pad Solutions for PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/evaluating-the-tech-behind-your-memories-the-mycam-cam-reviewed-for-2024/"><u>Evaluating the Tech Behind Your Memories  The MyCam Cam Reviewed for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-your-roadmap-to-earning-on-tiktok-discover-these-top-8-approaches/"><u>2024 Approved  Your Roadmap to Earning on TikTok  Discover These Top 8 Approaches</u></a></li>
</ul></div>
