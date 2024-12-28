---
title: How to Regain Original Settings in Win11 Terminal
date: 2024-12-21T18:31:30.368Z
updated: 2024-12-28T00:57:47.665Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-maximize-content-experience-with-these-top-6-youtube-shorts-downloader-apps/"><u>[New] Maximize Content Experience with These Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-understanding-income-dynamics-from-trending-youtube-shorts/"><u>[New] Understanding Income Dynamics From Trending YouTube Shorts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-mastering-the-art-of-editing-with-final-cut-pro/"><u>[Updated] In 2024, Mastering the Art of Editing with Final Cut Pro</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlining-the-photo-date-addition-process/"><u>[Updated] Streamlining the Photo Date-Addition Process</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-ultimate-laptop-screencapture-techniques-reviewed/"><u>2024 Approved Ultimate Laptop ScreenCapture Techniques Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-user-biometrics-in-windows-11-for-domains/"><u>Configuring User Biometrics in Windows 11 for Domains</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-disabled-warning-unverified-adobe-in-windows/"><u>Eliminate Disabled Warning: Unverified Adobe in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/executing-a-pristine-windows-11-reboot/"><u>Executing a Pristine Windows 11 Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-and-change-keyboard-layouts-in-windows-11/"><u>How to Add and Change Keyboard Layouts in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/ignite-industry-insights-via-mastery-of-business-jargon/"><u>Ignite Industry Insights via Mastery of Business Jargon</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-auto-color-management-in-win11/"><u>Navigating Through Auto Color Management in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/new-laptops-that-will-take-your-breath-away-ifa-2023/"><u>New Laptops That Will Take Your Breath Away - IFA 2023</u></a></li>
<li><a href="https://win-blog.techidaily.com/no-more-stops-tips-to-prevent-your-pathfinder-game-from-haltinng-in-the-midst-of-battle-on-computer/"><u>No More Stops: Tips to Prevent Your Pathfinder Game From Haltinng in the Midst of Battle on Computer</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-mouse-sensitivity-for-fps-gaming-which-ones-best/"><u>Perfect Mouse Sensitivity for FPS Gaming: Which One's Best?</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-radeon-driver-transitions-on-new-windows-11-laptops/"><u>Smooth Radeon Driver Transitions on New Windows 11 Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-invisible-gadget-issue-in-windows-os/"><u>Tackling Invisible Gadget Issue in Windows OS</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210622592-9798986162836-the-flourish-experience/"><u>The Flourish Experience | Free Book</u></a></li>
<li><a href="https://win-net.techidaily.com/transferring-iphone-data-to-an-outside-hard-disk-3-effective-methods/"><u>Transferring iPhone Data to an Outside Hard Disk: 3 Effective Methods</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-automating-the-openness-of-emails-in-words-reading-area/"><u>Tutorial: Automating the Openness of Emails in Word's Reading Area</u></a></li>
</ul></div>

