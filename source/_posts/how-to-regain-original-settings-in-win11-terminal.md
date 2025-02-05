---
title: How to Regain Original Settings in Win11 Terminal
date: 2025-01-28T09:29:44.429Z
updated: 2025-02-04T02:59:19.781Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Regain Original Settings in Win11 Terminal
excerpt: This Article Describes How to Regain Original Settings in Win11 Terminal
keywords: Win11 Settings Restore,Terminal Original Setup,Win11 Terminal Reset,Reclaim Win11 Config,Win11 Command Line Fix,Termux Default Options,Win11 Prompt Defaults,Win Terminal Config Restore,Win 11 Terminal Defaults,Reset Win 11 Command Prompt,Restore Win11 Settings Panel,Win 11 Cmd Reset Guide,Setup Original Windows Terminal,Defaults in Win 11 PowerShell
thumbnail: https://thmb.techidaily.com/4a8a85a143c0d3d9775ca5a0e81916a22ae62d07a1551bf0ada3f1e75697ff38.jpg
---

## How to Regain Original Settings in Win11 Terminal

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-complete-zoomers-guide-achieving-exceptional-video-and-audio-recordings-on-zoom/"><u>[New] In 2024, The Complete Zoomer's Guide Achieving Exceptional Video & Audio Recordings on Zoom</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-the-potential-of-multi-stream-video-on-microsoft-edge/"><u>2024 Approved Unlocking the Potential of Multi-Stream Video on Microsoft Edge</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/decoding-the-process-your-comprehensive-guide-to-filing-a-dispute-report-on-discord/"><u>Decoding the Process Your Comprehensive Guide to Filing a Dispute Report on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-operation-of-microsoft-nearby-share/"><u>Ensuring Smooth Operation of Microsoft Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-screensaver-adjustment/"><u>Fast Track: Windows Screensaver Adjustment</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-hobbyist-to-pro-the-audacity-journey/"><u>From Hobbyist to Pro The Audacity Journey</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-11x-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Realme 11X 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/methoden-zur-wiederherstellung-nicht-gespeicherter-dateien-in-wordpad/"><u>Methoden Zur Wiederherstellung Nicht Gespeicherter Dateien in WordPad</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimizing-audacity-a-guide-to-premium-sound-capture-for-2024/"><u>Optimizing Audacity A Guide to Premium Sound Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedies-for-click-anomalies-in-the-latest-windows-version/"><u>Remedies for Click Anomalies in the Latest Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/set-up-your-pc-for-win-11-ease-create-bootable-media-in-3-steps/"><u>Set Up Your PC for Win 11 Ease: Create Bootable Media in 3 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/simultaneous-wi-fi-and-ethernet-use-guide-for-windows-pcs/"><u>Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/six-simple-steps-to-engage-your-ps5-console/"><u>Six Simple Steps To Engage Your PS5 Console</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-cutting-down-on-browsers-load-time/"><u>Strategies for Cutting Down on Browsers Load Time</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-sony-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Sony FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/unknown-subjects-under-edge-in-tasker/"><u>Unknown Subjects Under Edge in Tasker</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/"><u>What Is the System Cooling Policy on Windows and How Do You Set It?</u></a></li>
</ul></div>

