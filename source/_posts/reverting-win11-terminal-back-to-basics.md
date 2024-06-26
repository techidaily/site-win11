---
title: Reverting Win11 Terminal Back to Basics
date: 2024-06-25T11:33:47.899Z
updated: 2024-06-26T11:33:47.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting Win11 Terminal Back to Basics
excerpt: This Article Describes Reverting Win11 Terminal Back to Basics
keywords: Basic Win11 Command Line,Win11 Terminal Essentials,Fundamentals of Win11 Cmd,Learn Win11 Terminal Basics,Mastering Win11 Terminal,Understanding Win11 CMD,Revert to Win11 Basic Usage
thumbnail: https://thmb.techidaily.com/8fe3e4daa8d42d226ab99d6ad95d4825a0edf9f54adc2ff54b0e8f531a27fde7.jpg
---

## Reverting Win11 Terminal Back to Basics

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
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-organized-print-setup-in-windows-systems/"><u>The Key to Organized Print Setup in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/winupgrade-hurdles-overcoming-error-code-xc004f050/"><u>WinUpgrade Hurdles: Overcoming Error Code Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-windows-automatic-deletion/"><u>Revolutionize File Management with Windows' Automatic Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-regain-control-over-non-operational-media-playback/"><u>Strategies to Regain Control Over Non-Operational Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-ram-overcoming-obstacles-in-windows/"><u>Reigniting RAM: Overcoming Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/whats-in-store-for-windows-11-with-update-22h2/"><u>What's in Store for Windows 11 with Update #22H2?</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-safest-free-software-download-sites-for-windows/"><u>The 10 Safest Free Software Download Sites for Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-prime-free-tools-to-sketch-unique-discord-icons/"><u>[Updated] Prime Free Tools to Sketch Unique Discord Icons</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-xiaomi-redmi-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-master-classroom-optimal-video-edits-on-vimeo/"><u>In 2024, Master Classroom  Optimal Video Edits on Vimeo</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-change-photo-color-like-a-pro/"><u>[New] How to Change Photo Color Like A Pro?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-the-complete-guide-to-converting-gif-to-svg-with-ease/"><u>In 2024, The Complete Guide to Converting GIF to SVG With Ease</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-11-pro-without-swiping-up-6-ways-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 11 Pro Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://fox-blue.techidaily.com/perfecting-date-placement-on-visual-memories/"><u>Perfecting Date Placement on Visual Memories</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-have-you-seen-the-facebook-cartoon-app-everyones-using-recently/"><u>New 2024 Approved Have You Seen the Facebook Cartoon App Everyones Using Recently</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-direct-from-twitter-posting-engaging-video-content-on-snapchat/"><u>[Updated] Direct From Twitter  Posting Engaging Video Content on Snapchat</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-oneplus-nord-3-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your OnePlus Nord 3 5G to Other Android devices | Dr.fone</u></a></li>
</ul></div>
