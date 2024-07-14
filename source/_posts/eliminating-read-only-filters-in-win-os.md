---
title: Eliminating Read-Only Filters in Win OS
date: 2024-07-13T10:20:20.943Z
updated: 2024-07-14T10:20:20.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Read-Only Filters in Win OS
excerpt: This Article Describes Eliminating Read-Only Filters in Win OS
keywords: Windows Read-Only Removal,Read-Only Filter Elimination,Remove Read-Only Windows,Fixing Read-Only Errors,Disabling File Locks (Win),Overcoming Win OS Restrictions,Enable Write Access Windows
thumbnail: https://thmb.techidaily.com/fed3ffae9229ff3a7d3580519bb324f0e6bad8a6cd96fa55cbded24321f049a3.jpg
---

## Eliminating Read-Only Filters in Win OS

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://tiktok-clips.techidaily.com/professional-tiktok-video-downloader-for-mp4-format-for-2024/"><u>Professional TikTok Video Downloader for MP4 Format for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-with-11-troubleshooting-windows-tips/"><u>Avoid Frustration with 11 Troubleshooting Windows Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-tackling-problems-with-instagrams-video-feature/"><u>[Updated] In 2024, Tackling Problems with Instagram's Video Feature</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-achieve-crystal-clear-sound-without-background-ruckus-in-audacity/"><u>How to Achieve Crystal Clear Sound Without Background Ruckus in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-for-capturing-uac-alerts/"><u>Advanced Techniques for Capturing UAC Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/activating-local-administrator-tools-in-windows-1110-home/"><u>Activating Local Administrator Tools in Windows 11/10 Home</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-empty-directory-issue-in-windows-11-error-0x80070091/"><u>Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/access-gpos-securely-a-guide-to-win11s-tools/"><u>Access GPOs Securely: A Guide to Win11's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/access-windows-greatness-through-microsoft-store/"><u>Access Windows Greatness Through Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/ai-driven-windows-11-an-inevitable-shift/"><u>AI-Driven Windows 11: An Inevitable Shift</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-memory-use-by-edges-view2-process/"><u>Addressing Excessive Memory Use by Edge's View2 Process</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-software-operation-with-4-key-pcts/"><u>Achieve Seamless Software Operation with 4 Key PCTs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-laptop-touchpad-sensitivity-guide/"><u>Adjusting Windows 11 Laptop Touchpad Sensitivity Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-80-pro-straight-screen-edition-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor 80 Pro Straight Screen Edition Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-problems-with-windows-hello-fingerprint-detection/"><u>Addressing Common Problems with Windows Hello Fingerprint Detection</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ient-tagging-techniques-to-boost-your-youtube-traffic/"><u>Efficient Tagging Techniques to Boost Your Youtube Traffic</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-digital-broadcast-face-off-facebook-vs-youtube-and-tweetstreams/"><u>[New] In 2024, Digital Broadcast Face-Off  FACEbook Vs. YOUTube & TweetStreams</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-configuration-of-win11-connectivity-options/"><u>Accessible Configuration of Win11 Connectivity Options</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-data-breaches-proper-password-addition-in-windows/"><u>Avoiding Data Breaches: Proper Password Addition in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-make-windows-11-search-invisible/"><u>Advanced Tactics: Make Windows 11 Search Invisible</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-compression-and-archiving-tools/"><u>Activating Windows Compression & Archiving Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-essential-online-capture-for-tech-enthusiasts/"><u>[Updated] Essential Online Capture for Tech Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/automate-app-colors-with-the-help-of-windows-11-features/"><u>Automate App Colors with the Help of Windows 11 Features</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-excellent-record-maker-chromebook-edition/"><u>[New] Excellent Record Maker  Chromebook Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-keystrokes-mastery-via-typingaid/"><u>Accelerating Keystrokes: Mastery via TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-printouts-from-powerpoint-in-windows-9-top-fixes-unveiled/"><u>Accurate Printouts From PowerPoint in Windows: 9 Top Fixes Unveiled</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-what-is-ai-voice-over/"><u>In 2024, What Is AI Voice Over?</u></a></li>
<li><a href="https://win11.techidaily.com/activation-protocol-engaging-modernized-widget-pickers-toolset/"><u>Activation Protocol: Engaging Modernized Widget Pickers Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-usage-issues-of-unrealcefsubprocess-on-windows-machines/"><u>Addressing High Usage Issues of UnrealCEFSubprocess on Windows Machines</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-funnyframe-easy-memes-no-stress/"><u>[Updated] FunnyFrame  Easy Memes, No Stress</u></a></li>
</ul></div>
