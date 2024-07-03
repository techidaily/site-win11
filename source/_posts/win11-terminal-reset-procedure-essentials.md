---
title: Win11 Terminal Reset Procedure Essentials
date: 2024-06-25T11:24:51.828Z
updated: 2024-06-26T11:24:51.828Z
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
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/directx-installation-guide-easy-downloads-and-updates/"><u>DirectX Installation Guide: Easy Downloads & Updates</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://win11.techidaily.com/regain-missing-windows-storage-access/"><u>Regain Missing Windows Storage Access</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-grant-write-access-for-steam-folders-in-win-11/"><u>Techniques to Grant Write Access for Steam Folders in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-unwanted-files-from-your-c-drive/"><u>Banishing Unwanted Files From Your C: Drive</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-windows-experience-the-significance-of-16gb-ram/"><u>Advancing Windows Experience: The Significance of 16GB RAM</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-photo-slideshows-and-spot-corrections-on-win11s-gallery/"><u>Mastering Photo Slideshows & Spot Corrections on Win11's Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-in-windows-11-dissecting-update-wxxs-additions/"><u>New Horizons in Windows 11: Dissecting Update W.x.x's Additions</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-above-and-beyond-the-ultimate-guide-to-mavic-pro/"><u>2024 Approved  Above and Beyond - The Ultimate Guide to Mavic Pro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-inside-look-the-future-of-home-cam-recordings/"><u>[New] In 2024, Inside Look  The Future of Home Cam Recordings</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-tecno-spark-10c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-30-marketing-moments-that-can-transform-your-fb-game/"><u>[Updated] The 30 Marketing Moments That Can Transform Your FB Game</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-your-message-memes-on-kapwing-pro/"><u>2024 Approved  Master Your Message  Memes on Kapwing Pro</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-oppo-find-x7-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Oppo Find X7 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-y27s-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo Y27s Screen | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Honor Magic Vs 2 | Dr.fone</u></a></li>
</ul></div>
