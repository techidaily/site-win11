---
title: Overcoming ALT Code Not Responding on Windows PC
date: 2024-06-25T11:34:19.577Z
updated: 2024-06-26T11:34:19.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming ALT Code Not Responding on Windows PC
excerpt: This Article Describes Overcoming ALT Code Not Responding on Windows PC
keywords: Fix Alt Code Error,Resolve ALT 255,Overcome Windows Alt Failure,Correct AltCode Response Issue,Stop ALT 255 Not Working,Prevent Windows Alt Code Non-Response,Heal Windows Alt Not Responding
thumbnail: https://thmb.techidaily.com/efbab3d097792aa66f0bd2cf2071c3ef92d9d9dc79fa36684145aac317075ce9.jpg
---

## Overcoming ALT Code Not Responding on Windows PC

 ALT codes are a great way to quickly enter special characters, symbols, and letters into your documents or other text fields. However, sometimes they don't work as expected and can be difficult to troubleshoot.

 If you are experiencing problems with ALT codes on your Windows system, there are several steps you can take to try and get them working again. This guide will explain what causes this problem and how to fix it.

## What Causes Windows ALT Codes to Not Work?

 ALT codes are characters that you can use to create various symbols and special characters on your computer, but they may not always work on Windows. If you're having trouble getting ALT codes to work, there are a few potential causes that could be behind the issue.

 The most common reason for ALT codes not working is that the number lock setting has been turned off. This setting controls how numbers on the numeric keypad function, so check it if you're having trouble with your ALT codes.

 Another cause of this problem is incorrect language settings on Windows. If your language settings don't match the keyboard layout you're using, then it's possible your input won't be interpreted properly by Windows.

 The problem may also occur due to conflicting background programs, outdated software drivers, or hardware compatibility glitches. If you are experiencing this issue, here are some tips for resolving it.

## 1\. Turn On Mouse Keys

 If you need to use ALT codes on Windows but find that they are not working, you might want to enable Mouse Keys when NUM LOCK is ON. This is an easy fix for many ALT code problems.

 The method involves pressing the**left ALT + left SHIFT + NUM LOCK** keys simultaneously on your keyboard. In the popup menu that appears, click**Yes** and Mouse Keys will be enabled.

 Doing this should allow you to use ALT codes again, as it will enable you to type characters by clicking the numeric keypad with the mouse cursor. This is especially useful if your laptop does not have a separate number pad or if you’re using a smaller keyboard without one.

## 2\. Modify the System Settings

 If the above solution does not work, it means the keyboard shortcut is disabled in the Ease of Access Centre. In such a case, you can manually make the changes either through the Control Panel or via Windows Settings. Here's how to do it:

1. Press**Win + I** on your keyboard to[launch the Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select the**Accessibility** tab in the left pane.
3. On the right side, click**Mouse** under the Interaction section.
4. Click the toggle to enable the**Mouse keys** .  
![Turn On the Mouse keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-on-the-mouse-keys.jpg)
5. Check the box next to**Only use mouse keys when Num lock is on** .

 After performing the steps above, close the window and restart your computer. At the next system startup, try using ALT codes again to see if it resolves the issue.

## 3\. Tweak the Registry Editor

 If the above solutions do not work, it seems that your registry has an entry that prevents you from adding Unicode characters. In that case, you may need to enable Unicode character input.

 This is a more advanced solution and requires some familiarity with the Windows registry editor.

 If you are uncomfortable working with your computer's registry, get professional assistance. You should also[back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

To get started, follow these steps:

1. Press**Win + R** on your keyboard to[open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type "regedit" and press Enter or click the**OK** button.
3. When a UAC window appears on the screen, click**Yes** .  
![Enable HexNumpad in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-hexnumpad-in-registry.jpg)
4. After opening the Registry Editor, navigate to the following directory. Alternatively, you can copy and paste the given location in the registry address field and hit**Enter** on your keyboard:  
HKEY_CURRENT_USER\Control Panel\Input Method
5. Now right-click on**Input Method** and choose**New > String Value** .
6. Once you have created the string value, name it**EnableHexNumpad** and press**Enter** to save it.
7. Double-click on EnableHexNumpad, and a pop-up window will appear.
8. In the Value data field, set**1** and click**OK** to save your changes.

 Once you've completed the above steps, close Registry Editor and restart your computer. Upon restarting, hold down the right Alt key and press the + (plus) key on your numeric keypad. Then enter the hex code, and release the Alt key to enter any character.

## 4\. Remove the Problematic Application

 If you have installed any third-party applications that might be causing problems with the ALT codes, then uninstalling them could also help fix this issue. To do this, follow these steps:

1. Press**Win + X** and select**Installed apps** from the top of the list.
2. Look for the program that is causing the error.
3. Once you find it, click the three dots and click**Uninstall** .
4. Then follow the onscreen instructions to complete the process.

## 5\. Try a Different Keyboard Layout

 If you’re still having issues with ALT codes, you can try switching to a different keyboard layout. Here's how to do it:

1. Open the Control Panel (see[how to open the Control Panel on Windows](https://www.makeuseof.com/windows-11-open-control-panel/) ).
2. Then go to**Clock and Region > Region** . Alternatively, type**intl.cpl** in the Run dialog box and press**Enter** .  
![Try a Different Keyboard Layout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/try-a-different-keyboard-layout.jpg)
3. Under the**Formats** tab, select a different language from the list.

 After selecting one, click**Apply** , then**OK** , and restart your computer. Now try using ALT codes again to see if they work now.

## 6\. Troubleshoot With a Clean Boot

 If none of the above solutions work, you can try[performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will start your computer with only essential services and programs running, which can help identify any potential conflicts or issues with startup items that may be causing ALT codes to malfunction.

1. Open the MSConfig tool (see[how to open MSConfig on Windows](https://www.makeuseof.com/windows-11-open-msconfig/) ) and select the**General** tab.
2. Check the**Selective startup** box.
3. Make sure that the box**Load startup items** is unchecked.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. The next step is to click on the**Services** tab.
5. Click**Hide all Microsoft services** , then click**Disable all** .  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Click the**Apply** button to save the changes.
7. Go to the**Startup** tab and click**Open Task Manager** .
8. On the Startup tab, right-click each service and disable it.
9. After making changes to System Configuration, click**OK** .

## Troubleshooting Windows ALT codes

 ALT codes are a useful tool to have when it comes to typing special characters, but outdated software drivers or conflicting background programs may prevent it from working properly. In this case, you can rely on the information above to help you resolve the problem.


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
<li><a href="https://win11.techidaily.com/unlinked-file-program-resolution-for-windows-pc-users/"><u>Unlinked File Program Resolution for Windows PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-low-resource-utilization-wlanextexe/"><u>Mastering Low Resource Utilization: Wlanext.EXE</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-app-migration-tips-to-fix-windows-task-manager-positions/"><u>Avoid App Migration: Tips to Fix Windows Task Manager Positions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-with-windows-printmanagement-msc-errors/"><u>Overcoming Obstacles with Windows 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-distant-devices-a-guide-for-windows-users/"><u>Reconciling Distant Devices: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-dedicated-video-ram-vram-in-windows-11-and-11/"><u>How to Increase Dedicated Video RAM (VRAM) in Windows 11 and 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-macs-screenflow-insights-complete-coverage/"><u>[Updated] In 2024, Mac's ScreenFlow Insights - Complete Coverage</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-maximizing-chances-to-engage-premier-filmmakers/"><u>[Updated] 2024 Approved  Maximizing Chances to Engage Premier Filmmakers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-on-your-iphone-se-2022-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock on your iPhone SE (2022) and iPad?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/windows-10-screen-grabber-roundup-top-15-for-2024/"><u>Windows 10 Screen Grabber Roundup - Top 15 for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-refurbished-apple-iphone-12-pro-max-everything-you-need-to-know-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Refurbished Apple iPhone 12 Pro Max Everything You Need to Know | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-audioarchive-compiler-download-playback-and-test/"><u>[Updated] 2024 Approved  AudioArchive Compiler  Download, Playback & Test</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-beginners-guide-to-understanding-youtube-responses/"><u>In 2024, A Beginner's Guide to Understanding YouTube Responses</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-hdr-shifts-the-paradigm-of-video-quality-standards/"><u>How HDR Shifts the Paradigm of Video Quality Standards</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-viewer-discussions-on-youtube/"><u>[New] Mastering Viewer Discussions on YouTube</u></a></li>
</ul></div>
