---
title: Navigating the Linux Command Landscape in Windows
date: 2024-09-30T18:11:17.547Z
updated: 2024-10-03T19:56:37.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Linux Command Landscape in Windows
excerpt: This Article Describes Navigating the Linux Command Landscape in Windows
keywords: Linux Commands for PC,Linux on Windows Guide,Windows & Linux CLI Use,Learn Linux Cmd Windows,Execute Linux Commands WIndows,Linux Bash in Windows,Command Line Tools LinuxPC
thumbnail: https://thmb.techidaily.com/a691a544cb7cde4aeceab56e4cf68f393a99f1feb2da71ac3ca94b7300f4d4b3.jpg
---

## Navigating the Linux Command Landscape in Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068417/7443" target="_top" id="2068417">
  <img src="//a.impactradius-go.com/display-ad/7443-2068417" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068417/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-making-an-impression-professional-pc-editing-strategies-for-youtube/"><u>[New] 2024 Approved Making an Impression Professional PC Editing Strategies for YouTube</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-ultimate-utilities-free-and-paid-macpc-bd-software-compared/"><u>[Updated] In 2024, Ultimate Utilities Free & Paid Mac/PC BD Software Compared</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-vimeo-to-mp4-conversion-made-simple/"><u>[Updated] In 2024, Vimeo to MP4 Conversion Made Simple</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-advanced-methodologies-for-backdrop-purification-in-figma-design/"><u>2024 Approved Advanced Methodologies for Backdrop Purification in Figma Design</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-nubia-red-magic-9-proplus-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Nubia Red Magic 9 Pro+ FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/combating-the-deadly-windows-10-fatality-code-c0000022/"><u>Combating the Deadly Windows 10 Fatality Code C0000022</u></a></li>
<li><a href="https://win11.techidaily.com/create-order-in-chaos-master-these-5-advanced-window-folder-tactics/"><u>Create Order in Chaos: Master These 5 Advanced Window Folder Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-the-iomap64-syscall-failure-blue-screen/"><u>Deciphering and Fixing the IOMap64 Syscall Failure Blue Screen</u></a></li>
<li><a href="https://tech-haven.techidaily.com/google-unveils-bard-its-latest-ai-tool-poised-to-vie-with-chatgpt/"><u>Google Unveils Bard - Its Latest AI Tool Poised to Vie with ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-no-device-drivers-were-found-error-while-installing-windows/"><u>How to Fix the No Device Drivers Were Found Error While Installing Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-lava-blaze-2-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Lava Blaze 2 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-seven-ways-to-bridge-obs-studios-network-gap-in-windows/"><u>Quick Guide: Seven Ways to Bridge OBS Studio's Network Gap in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-methods-refreshing-windows-pc-eightfold/"><u>Reboot Methods: Refreshing Windows PC Eightfold</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-rectify-non-previewable-documents-in-outlook/"><u>Strategies to Rectify Non-Previewable Documents In Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-issue-0x800704b3-in-windows/"><u>Tackling Network Issue 0X800704B3 in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-cinemagraph-guide-top-5-must-know-tactics/"><u>The Ultimate Cinemagraph Guide - Top 5 Must-Know Tactics</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-walkthrough-how-to-erase-your-yahoo-mail-presence-forever/"><u>The Ultimate Walkthrough: How To Erase Your Yahoo Mail Presence Forever</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-t2-pro-5g-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on T2 Pro 5G without backup.</u></a></li>
<li><a href="https://win11.techidaily.com/win11-activating-new-widget-selection-interface/"><u>Win11: Activating New Widget Selection Interface</u></a></li>
</ul></div>

