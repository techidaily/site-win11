---
title: How to Regain Original Settings in Win11 Terminal
date: 2025-01-05T19:11:44.525Z
updated: 2025-01-06T18:59:20.547Z
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

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-zte-nubia-z60-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-lab.techidaily.com/can-you-use-wd-anywhere-backup-on-windows-11-comprehensive-guide/"><u>Can You Use WD Anywhere Backup on Windows 11? Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-instructions-for-booting-up-windows-10-on-your-new-pcs-drive/"><u>Easy Instructions for Booting Up Windows 10 on Your New PC's Drive</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/mical-audience-expansion-buy-subscribers-not-time/"><u>Economical Audience Expansion Buy Subscribers, Not Time</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-memdump-reports-from-blue-screen-errors/"><u>Exploring Memdump Reports From Blue Screen Errors</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-xiaomi-14-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-oppo-find-x6-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Oppo Find X6 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-the-same-wallpaper-on-windows-11-always/"><u>Keeping the Same Wallpaper on Windows 11 Always</u></a></li>
<li><a href="https://win11.techidaily.com/quickening-download-pace-tips-for-steam-and-windows-integration/"><u>Quickening Download Pace: Tips for Steam and Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-silenced-pc-audio-sound-restoration-tips/"><u>Reactivate Silenced PC Audio – Sound Restoration Tips</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/seamless-screen-stretch-cycle-youtube-on-television-display/"><u>Seamless Screen Stretch Cycle YouTube on Television Display</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-smoothing-out-windows-update-problems/"><u>Strategies for Smoothing Out Windows Update Problems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-10-enterprise-cloud-options/"><u>Top 10 Enterprise Cloud Options</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-the-shadows-of-window-11s-interface/"><u>Uncovering the Shadows of Window 11'S Interface</u></a></li>
<li><a href="https://fox-access.techidaily.com/visual-harmony-how-m1-chips-enhance-editing-speed-and-precision-for-2024/"><u>Visual Harmony How M1 Chips Enhance Editing Speed and Precision for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-error-files-without-preview-thumbnails/"><u>Windows 11 Error: Files Without Preview Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-gains-additional-lifespan-with-new-yearly-patches/"><u>Windows 11 Gains Additional Lifespan with New Yearly Patches</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-notes-made-simple-no-software-required/"><u>Windows 11 Notes Made Simple, No Software Required</u></a></li>
</ul></div>

