---
title: Win11 Terminal Reset Procedure Essentials
date: 2024-06-25T09:50:13.637Z
updated: 2024-06-26T09:50:13.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win11 Terminal Reset Procedure Essentials
excerpt: This Article Describes Win11 Terminal Reset Procedure Essentials
keywords: Win11 Terminal Fix,Terminal Reset Guide,Win11 Terminal Restart,Terminus Windows Reset,Win11 Command Prompt,Terminal Procedure Basics,Win11 CmdReset Essentials
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## Win11 Terminal Reset Procedure Essentials

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

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
<li><a href="https://win11.techidaily.com/overcoming-windows-ui-instability-issues/"><u>Overcoming Windows UI Instability Issues</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-local-security-guard-off-error-message/"><u>Cure for 'Local Security Guard Off' Error Message</u></a></li>
<li><a href="https://win11.techidaily.com/banish-unfulfilled-system-criteria-marking-on-win11/"><u>Banish Unfulfilled System Criteria Marking on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/seven-keys-to-unlocking-the-full-potential-of-windows-software/"><u>Seven Keys to Unlocking the Full Potential of Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-setup-google-play-store-on-win11/"><u>Easy Steps: Setup Google Play Store on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-to-security-focused-dialogue-shortcuts/"><u>Windows 11: Guide to Security-Focused Dialogue Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-adrenaline-with-the-latest-yi-technology-for-2024/"><u>Capturing Adrenaline with the Latest Yi Technology for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-initial-guide-to-zoom-room-segregation/"><u>[New] 2024 Approved  Initial Guide to Zoom Room Segregation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-mastering-youtube-to-mp3-conversion-a-beginners-guide-for-2024/"><u>New Mastering YouTube to MP3 Conversion A Beginners Guide for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mkv-movies-on-edge-40-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Failed to play MKV movies on Edge 40</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-5-best-chrome-extensions-for-vimeo-video-downloader/"><u>In 2024, 5 Best Chrome Extensions for Vimeo Video Downloader</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-ultimate-guide-to-best-youtube-banner-size-and-channel-art-dimension/"><u>[New] Ultimate Guide to Best YouTube Banner Size and Channel Art Dimension</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-fast-forward-your-videos-a-quicktime-player-tutorial-for-2024/"><u>New Fast Forward Your Videos A QuickTime Player Tutorial for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-crafting-a-pro-sports-youtube-feed-on-macos-for-2024/"><u>[New] Crafting a Pro Sports YouTube Feed on MacOS for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-motorola-moto-g-5g-2023-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-on-iphone-14-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud on iPhone 14 Safe and Legal</u></a></li>
</ul></div>
