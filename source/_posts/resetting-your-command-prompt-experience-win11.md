---
title: Resetting Your Command Prompt Experience (Win11)
date: 2024-06-25T11:35:05.512Z
updated: 2024-06-26T11:35:05.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Your Command Prompt Experience (Win11)
excerpt: This Article Describes Resetting Your Command Prompt Experience (Win11)
keywords: Win11 CmdPrompt Reset Guide,Reset Windows Terminal,Cleaner CMD Environment,Update Command Prompt,Enhance PC Cmd Experience,Fix Command Errors,Streamline CMD Settings
thumbnail: https://thmb.techidaily.com/b60c76ffc589ae0e04ed8d9626d309109b105480cf9bd2a5898ac2cac1fa41f0.jpg
---

## Resetting Your Command Prompt Experience (Win11)

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
<li><a href="https://win11.techidaily.com/the-perfect-blend-excelling-at-classic-games-in-hd-clarity-through-scummvm-on-windows/"><u>The Perfect Blend: Excelling at Classic Games in HD Clarity Through ScummVM on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-gpu-settings-on-windows-11-pcs/"><u>Revitalize GPU Settings on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/handling-unable-to-open-file-for-writing-error-in-win-11/"><u>Handling Unable to Open File for Writing Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-lock-screen-timeout-stops-working-on-windows/"><u>What to Do if the Lock Screen Timeout Stops Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-rdc-launches-windows-11-guide/"><u>Effortless RDC Launches - Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-rapid-system-restart-windows-11-edition/"><u>Unlocking the Secrets of Rapid System Restart: Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-context-menu-choices-with-automatic-patch-information/"><u>Enriching Context Menu Choices with Automatic Patch Information</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-looking-for-permission-to-view-friends-entirely-shared-media/"><u>[New] Looking for Permission to View Friend’s Entirely Shared Media</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-best-video-editing-software-for-windows-10-imovie-alternatives/"><u>2024 Approved Best Video Editing Software for Windows 10 IMovie Alternatives</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-direct-linkage-bridging-youtube-and-imovie-with-music/"><u>[New] 2024 Approved  Direct Linkage  Bridging YouTube and iMovie with Music</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-directing-content-flow-uploading-imovie-films-to-youtube-for-2024/"><u>[New] Directing Content Flow  Uploading IMovie Films to YouTube for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-elevate-your-storytelling-easy-online-video-creation-with-wevideo/"><u>In 2024, Elevate Your Storytelling Easy Online Video Creation with WeVideo</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-ultimate-tips-for-exceptional-vr-gaming-video-quality/"><u>[New] Ultimate Tips for Exceptional VR Gaming Video Quality</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-xiaomi-redmi-12-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Xiaomi Redmi 12 5G Activity | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-top-rated-free-video-editors-for-newbies/"><u>2024 Approved Top-Rated Free Video Editors for Newbies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/youtube-monetization-carryminati-ajey-nagar-youtube-income/"><u>YouTube Monetization  CarryMinati (Ajey Nagar) YouTube Income</u></a></li>
</ul></div>
