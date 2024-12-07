---
title: How to Reset the Windows Terminal Settings to Their Defaults in Windows 11
date: 2024-12-02T03:48:46.002Z
updated: 2024-12-06T19:01:45.767Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset the Windows Terminal Settings to Their Defaults in Windows 11
excerpt: This Article Describes How to Reset the Windows Terminal Settings to Their Defaults in Windows 11
keywords: Reset Win Terminal,Default Win Terminal,Reset Terminal Settings,Win Terminal Basics,Windows 11 Terminal,Terminal Settings Defaults,Restore Terminal Options
thumbnail: https://thmb.techidaily.com/8fb2d0d577922e31978350cb180e7bc0e8d3ea4b5792db82388ad0c79872b3d3.jpg
---

## How to Reset the Windows Terminal Settings to Their Defaults in Windows 11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-enhancing-tiktok-video-viewership-through-zoom-for-2024/"><u>[New] Enhancing TikTok Video Viewership Through Zoom for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-total-kinetic-analysis-exploration/"><u>[New] In 2024, Total Kinetic Analysis Exploration</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-watch-what-you-liked-no-more-unveiling-yt-deletions-online/"><u>[Updated] Watch What You Liked No More Unveiling YT Deletions Online</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-connectivity-mastering-the-use-of-winnettools/"><u>Enhance Connectivity: Mastering the Use of WinNetTools</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-no-internet-access-on-an-ethernet-connection-on-windows/"><u>How to Fix No Internet Access on an Ethernet Connection on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-nubia-z50-ultra-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Nubia Z50 Ultra Phone Password Using Emergency Call</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-step-by-step-record-and-save-facebook-chats-effectively/"><u>In 2024, Step-By-Step Record and Save Facebook Chats Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-custom-key-combinations-on-windows-11/"><u>Mastering Custom Key Combinations on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-crashes-and-freezes-with-vmware-in-windows-11/"><u>Overcoming Crashes & Freezes with VMware in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-where-win11-stores-window-picture-files/"><u>Pinpoint Where Win11 Stores Window Picture Files</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-missing-windows-6-essential-tactics-in-win11/"><u>Reactivating Missing Windows: 6 Essential Tactics in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-display-driver-startup-fails-issue-on-windows-11/"><u>Rectifying Display Driver Startup Fails Issue on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-14-herramientas-de-creacion-de-powerpoint-para-windows-11-elite-software-del-ano-2amo/"><u>Top 14 Herramientas De Creación De PowerPoint Para Windows 11 - Elite Software Del Año 2Amo</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleashing-musical-talent-with-magix-studio/"><u>Unleashing Musical Talent with Magix Studio</u></a></li>
</ul></div>

