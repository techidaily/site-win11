---
title: How to Regain Original Settings in Win11 Terminal
date: 2025-02-28T00:07:52.115Z
updated: 2025-03-04T18:26:27.469Z
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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-influencers-secrets-top-10-video-editing-apps-for-ig-success/"><u>[Updated] 2024 Approved Influencers' Secrets Top 10 Video Editing Apps for IG Success</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-essential-guide-leading-video-editing-tools-androidpc-for-2024/"><u>[Updated] Essential Guide Leading Video Editing Tools (Android/PC) for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/automated-consent-management-with-cookiebot-solutions/"><u>Automated Consent Management with Cookiebot Solutions</u></a></li>
<li><a href="https://win-rankings.techidaily.com/como-reparar-errores-de-unidad-que-obligan-a-restablecer-windows-10-con-5-soluciones-sencillas/"><u>Cómo Reparar Errores De Unidad Que Obligan a Restablecer Windows 10 Con 5 Soluciones Sencillas</u></a></li>
<li><a href="https://win-dash.techidaily.com/cost-free-hp-laserjet-printer-drivers-download-for-optimal-windows-7-compatibility/"><u>Cost-Free HP LaserJet Printer Drivers Download for Optimal Windows 7 Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-google-play-through-windows-11/"><u>Enabling Google Play Through Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-efficiency-reducing-memorycpu-load-in-windows-10/"><u>Enhance Efficiency: Reducing Memory/CPU Load in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-halt-default-launch-of-windows-11s-snipping-tool-by-pressing-prtscn/"><u>How to Halt Default Launch of Windows 11'S Snipping Tool by Pressing PrtScn</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-capture-with-clarity-advanced-tips-for-gopro-hero5-black/"><u>In 2024, Capture with Clarity Advanced Tips for GoPro Hero5 Black</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-note-12-4g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi Note 12 4G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-assessment-discover-what-makes-truecaller-stand-out/"><u>In-Depth Assessment: Discover What Makes Truecaller Stand Out</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-scheduling-the-complete-windows-11-calendar-handbook/"><u>Mastering Scheduling: The Complete Windows 11 Calendar Handbook</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-file-selection-activating-windows-11-checkboxes/"><u>Maximize File Selection: Activating Windows 11 Checkboxes</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-progress-mastering-the-save-file-security-in-epic-launcher/"><u>Permanent Progress: Mastering the Save File Security in Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-multilingual-navigation-on-windows-1011-with-keys/"><u>Speedy Multilingual Navigation on Windows 10/11 with Keys</u></a></li>
</ul></div>

