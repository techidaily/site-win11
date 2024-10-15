---
title: "Windows & Sudo: A Powerful Combination"
date: 2024-10-13T17:41:18.443Z
updated: 2024-10-15T16:35:42.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows & Sudo: A Powerful Combination"
excerpt: "This Article Describes Windows & Sudo: A Powerful Combination"
keywords: Windows Security Tips,Sudo Commands Guide,Power Linux Panel,Admin Privilege Basics,Secure OS Management,Effective Command Usage,System Control Strategies
thumbnail: https://thmb.techidaily.com/94567bf4df3b715033d93123bd31d8eb4bb0ab79d545d1676a1f32d06cb990c5.jpg
---

## Windows & Sudo: A Powerful Combination

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151873/7443" target="_top" id="2151873">
  <img src="//a.impactradius-go.com/display-ad/7443-2151873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-mastering-the-art-of-uploading-youtube-shorts-on-devices/"><u>[New] 2024 Approved Mastering the Art of Uploading YouTube Shorts on Devices</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-unleash-stunning-visuals-top-10-high-resolution-displays-for-mac-for-2024/"><u>[New] Unleash Stunning Visuals - Top 10 High-Resolution Displays for Mac for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-quickly-uncover-lately-watched-facebook-videos/"><u>[Updated] In 2024, Quickly Uncover Lately Watched Facebook Videos</u></a></li>
<li><a href="https://facebook.techidaily.com/curbing-the-ban-facebook-board-assessment-of-executive-decision/"><u>Curbing the Ban: Facebook Board Assessment of Executive Decision.</u></a></li>
<li><a href="https://win-able.techidaily.com/easy-conversion-tutorial-turn-your-mov-file-into-an-mp4-with-solutions-for-pc-and-mac-users/"><u>Easy Conversion Tutorial: Turn Your MOV File Into an MP4 with Solutions for PC and Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-removing-windows-defender-history-logs/"><u>Efficient Methods for Removing Windows' Defender History Logs</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-writing-skills-on-a-windows-machine/"><u>Elevate Your Writing Skills on a Windows Machine</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solidify-remote-access-with-stable-vpn-connection/"><u>How to Solidify Remote Access with Stable VPN Connection</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-it-possible-to-reach-chatgpt-through-a-virtual-private-network-vpn/"><u>Is It Possible to Reach ChatGPT Through a Virtual Private Network (VPN)?</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gameplay-essential-upgrades-for-win-11-gamers/"><u>Maximizing Gameplay: Essential Upgrades for Win 11 Gamers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/probing-into-the-integration-of-real-and-digital-in-mixed-reality/"><u>Probing Into the Integration of Real and Digital in Mixed Reality</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-mcuicntexe-execution-issue-on-pcs/"><u>Resolving McUICnt.exe Execution Issue on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rectifying-rdp-errors-in-windows-11/"><u>Strategies for Rectifying RDP Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-alternatives-to-directly-renaming-folders-in-win-11/"><u>The Ultimate List of Alternatives to Directly Renaming Folders in Win 11</u></a></li>
</ul></div>

