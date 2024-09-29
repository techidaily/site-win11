---
title: How To Simplify Terminal Settings in Win11
date: 2024-09-25T19:14:30.538Z
updated: 2024-09-28T21:05:27.520Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Simplify Terminal Settings in Win11
excerpt: This Article Describes How To Simplify Terminal Settings in Win11
keywords: Win11 Terminal Setup,Terminal Customization Windows,Simplify Win Terminal,Adjust Terminal Windows,Win Terminal Configurations,Simplified Terminal Settings,Optimize Terminal Options
thumbnail: https://thmb.techidaily.com/5e4f2e08bc06e83ddb45587d928cf61d9245bd50e484b6c6cc6059c7ac856aae.jpg
---

## How To Simplify Terminal Settings in Win11

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
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-learn-to-initiate-harmonious-group-conversations-on-skype-for-both-pc-and-mac-users/"><u>[Updated] In 2024, Learn to Initiate Harmonious Group Conversations on Skype for Both PC & Mac Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-secrets-to-flawless-ppt-video-transcriptions/"><u>[Updated] Secrets to Flawless PPT Video Transcriptions</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-vivo-y36i-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Vivo Y36i</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-audio-liberation-from-youtube-three-safe-methods/"><u>In 2024, Audio Liberation From YouTube Three Safe Methods</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-on-mending-windows-1011-corrupted-recycle-bin/"><u>Masterclass on Mending Windows 10/11 Corrupted Recycle Bin</u></a></li>
<li><a href="https://extra-information.techidaily.com/probing-deep-into-inshots-editing-capabilities/"><u>Probing Deep Into InShot's Editing Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-setup-for-icloud-users-with-windows-pcs/"><u>Seamless Setup for iCloud Users with Windows PCs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/snap-with-a-single-purpose-remove-bg-using-affinity/"><u>Snap with a Single Purpose - Remove Bg Using Affinity</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-telnet-enablement-in-win11/"><u>Step-by-Step: Telnet Enablement in Win11</u></a></li>
<li><a href="https://win-dash.techidaily.com/streamline-your-pc-with-quick-and-easy-intel-iris-540-driver-upgrades/"><u>Streamline Your PC with Quick & Easy Intel Iris 540 Driver Upgrades</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-complete-guide-to-transforming-your-footages-hue-for-2024/"><u>The Complete Guide to Transforming Your Footage's Hue for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-the-ultimate-list-video-makers-with-music-for-android-iphone-and-ipad/"><u>Updated In 2024, The Ultimate List Video Makers with Music for Android, iPhone, and iPad</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
</ul></div>

