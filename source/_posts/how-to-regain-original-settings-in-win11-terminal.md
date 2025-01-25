---
title: How to Regain Original Settings in Win11 Terminal
date: 2025-01-21T23:03:49.926Z
updated: 2025-01-25T06:05:42.520Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-the-creators-currency-how-to-turn-streams-into-dollars/"><u>[New] In 2024, The Creator’s Currency How To Turn Streams Into Dollars</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-add-ons-the-best-new-filmmakers-starter-list/"><u>[New] Prime Add-Ons The Best New Filmmaker’s Starter List</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-navigating-twitters-video-content-aspect-ratios-included/"><u>[Updated] 2024 Approved Navigating Twitter’s Video Content Aspect Ratios Included</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-biz-vr-innovations-new-frontiers-in-virtual-workspaces-for-2024/"><u>[Updated] Biz-VR Innovations New Frontiers in Virtual Workspaces for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-brush-up-skills-unveiling-the-ultimate-8-iphone-drawing-tools/"><u>[Updated] In 2024, Brush Up Skills Unveiling the Ultimate 8 iPhone Drawing Tools</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-directdraw-errors-effective-remedies-for-modern-microsoft-oses/"><u>Decoding DirectDraw Errors: Effective Remedies for Modern Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/defining-fresh-default-for-windows-pdf-files/"><u>Defining Fresh Default for Windows PDF Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-download-issues-during-steam-platform-updates/"><u>Effective Solutions for Download Issues During Steam Platform Updates</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-a-list-android-3d-viewing-tools/"><u>In 2024, A-List Android 3D Viewing Tools</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/instant-setup-guide-how-to-install-the-canon-pro-100-driver-for-your-windows-pc/"><u>Instant Setup Guide: How to Install the Canon PRO 100 Driver for Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/master-rdc-start-ups-with-these-10-tips/"><u>Master RDC Start-Ups with These 10 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-apexs-windows-server-issues-(156-chars/"><u>Mastering Apex's Windows Server Issues (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-transitioning-your-workspace-from-concentration-to-normal-on-terminal/"><u>Mastery over Transitioning Your Workspace: From Concentration to Normal on Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11s-narrator-command-efficiency/"><u>Unlocking Win11's Narrator Command Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/win11-icons-how-to-ditch-the-focused-wallpaper-symbol/"><u>Win11 Icons: How to Ditch the Focused Wallpaper Symbol</u></a></li>
</ul></div>

