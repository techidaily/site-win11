---
title: How to Regain Original Settings in Win11 Terminal
date: 2025-02-11T16:17:20.981Z
updated: 2025-02-15T17:37:07.988Z
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

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-unseen-strategies-how-to-tap-into-your-facebook-message-library/"><u>[New] 2024 Approved Unseen Strategies How to Tap Into Your Facebook Message Library</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-streamlining-your-edit-with-jump-cut-tips/"><u>[New] Streamlining Your Edit with Jump Cut Tips</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-picturemosaic-maker-blend-videos-and-pics-macos/"><u>[Updated] PictureMosaic Maker Blend Videos & Pics macOS</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-command-control-always-open-terminal-as-administrator/"><u>Enhanced Command Control: Always Open Terminal as Administrator</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-mythical-device-spec-error-in-windows-11/"><u>Fixing Mythical Device Spec Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-help-for-windows-11-login-failures/"><u>Immediate Help for Windows 11 Login Failures</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-master-your-favorite-games-with-obs-streaming-tips/"><u>In 2024, Master Your Favorite Games with OBS Streaming Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/installing-windows-11-with-a-disallowed-cpu-step-by-step-guide/"><u>Installing Windows 11 with a Disallowed CPU: Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pinnacle-enterprise-data-vaulting/"><u>Pinnacle Enterprise Data Vaulting</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/pro-grade-video-stabilization-in-fcpx-a-step-by-step-guide/"><u>Pro-Grade Video Stabilization in FCPX A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-buying-and-installing-adobe-reader/"><u>Stepwise Guide to Buying and Installing Adobe Reader</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-log-inspection-and-mainten-point-tips-to-review-and-clear-windows-10-activity-record/"><u>Streamlining Windows 10 Log Inspection & Mainten Point: Tips to Review and Clear Windows 10 Activity Record</u></a></li>
<li><a href="https://win11.techidaily.com/technique-to-turn-off-keyboard-for-your-win-run-devices/"><u>Technique to Turn Off Keyboard for Your Win-Run Devices</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-picks-unbeatable-headphone-offers-in-march-2023/"><u>Top Picks: Unbeatable Headphone Offers in March 2023</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-8-plus-without-passcode-easily-by-drfone-ios/"><u>Unlock iPhone 8 Plus Without Passcode Easily</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-full-potential-restoring-windows-photo-viewer-features-on-win11/"><u>Unlock the Full Potential: Restoring Windows Photo Viewer Features on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-autodelete-a-compreenas-guide-to-disk-management/"><u>Win11's Autodelete: A Compreenas Guide to Disk Management</u></a></li>
</ul></div>

