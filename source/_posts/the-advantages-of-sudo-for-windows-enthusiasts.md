---
title: The Advantages of Sudo for Windows Enthusiasts
date: 2024-10-14T20:55:43.041Z
updated: 2024-10-15T20:00:39.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Advantages of Sudo for Windows Enthusiasts
excerpt: This Article Describes The Advantages of Sudo for Windows Enthusiasts
keywords: Windows Sudo Benefits,Sudo PowerShell Efficiency,Sudo Command Security,Sudo System Control,Advanced Windows Commands,Improved Admin Tools,Enhanced OS Command Access
thumbnail: https://thmb.techidaily.com/40db9e7f14d32360658bd45a85fa8baf591a4c12413f48e4137aa1f90c61fa60.jpg
---

## The Advantages of Sudo for Windows Enthusiasts

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
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-from-individual-to-institutional-growth-in-youtube-space-for-2024/"><u>[New] From Individual to Institutional Growth in YouTube Space for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-which-is-superior-obs-or-streamlabs-for-your-livestream-needs-in-2024/"><u>[Updated] Which Is Superior, OBS or Streamlabs for Your Livestream Needs, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-mystery-how-to-rectify-microsoft-store-error-0x80072efd/"><u>Decoding the Mystery: How to Rectify Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solution-for-windows-11-recovering-absent-pin-post-update/"><u>Solution for Windows 11: Recovering Absent PIN Post-Update</u></a></li>
<li><a href="https://win11.techidaily.com/taming-win11-wm-peakgpu-issues-7-strategies/"><u>Taming Win11 WM PeakGPU Issues (7 Strategies)</u></a></li>
<li><a href="https://buynow-info.techidaily.com/tech-savvy-saving-a-comprehensive-analysis-of-the-budget-friendly-50s425-inch-4k-tv-from-tcl/"><u>Tech Savvy Saving: A Comprehensive Analysis of the Budget-Friendly 50S425 Inch 4K TV From TCL</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-resolving-ac6-fire-of-rubicon-crashes-in-windows/"><u>Troubleshooting Guide: Resolving AC6: Fire of Rubicon Crashes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-preventing-pc-overheating-in-gamers-laptops/"><u>Understanding and Preventing PC Overheating in Gamers’ Laptops</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-roblox-outages-how-do-i-know-if-the-problem-lies-with-the-game/"><u>Understanding Roblox Outages – How Do I Know If the Problem Lies with the Game?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-impact-of-sudos-arrival/"><u>Understanding the Impact of Sudo's Arrival</u></a></li>
<li><a href="https://win11.techidaily.com/win-gaming-mastering-intel-graphics-for-live-streams/"><u>Win Gaming: Mastering Intel Graphics for Live Streams</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725290518027-uniconverter/"><u>セキュリティ面で信頼性に足りるUniConverter：実態はどうなのか？</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    