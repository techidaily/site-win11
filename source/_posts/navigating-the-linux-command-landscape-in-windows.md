---
title: Navigating the Linux Command Landscape in Windows
date: 2024-09-16T05:42:05.688Z
updated: 2024-09-21T19:31:37.405Z
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

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-end-sound-pumping-tools-pcs-and-smartphones/"><u>[New] 2024 Approved High-End Sound Pumping Tools PCs & Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44km44kn44ow44ox44os44k844oz44og44o844k344on44oz44gu44gf44kb44gr44k544op44kk44oj44k344on44o844ot44oh44kq44ks5yq55p6c55qe44gr57eo6zug44gz44kl5oqa6kgt44cn1/"><u>「ウェブプレゼンテーションのためにスライドショービデオを効果的に編集する技術」</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-invisible-broadcasts-anonymous-instagram-live-tips/"><u>2024 Approved Invisible Broadcasts Anonymous Instagram Live Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-rankings-top-budget-friendly-photo-editors-online/"><u>2024 Approved The Ultimate Rankings Top Budget-Friendly Photo Editors Online</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-converting-dvd-content-into-avi-format-with-minimal-hassle/"><u>A Beginner's Guide to Converting DVD Content Into AVI Format with Minimal Hassle</u></a></li>
<li><a href="https://win11.techidaily.com/alcwavmp3/"><u>ALCフォーマットを効率的にWAVやMP3に変換する方法 | ハイレゾ音質移行手順</u></a></li>
<li><a href="https://win11.techidaily.com/aviyoutube/"><u>AVI形式への無料YouTubeビデオ変換</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/essential-mobile-games-for-leisurely-indulgence/"><u>Essential Mobile Games for Leisurely Indulgence</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-motorola-moto-g34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-zte-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on ZTE Phones with/without a PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pro-tips-for-conquering-photo-and-video-importers-on-windows-10/"><u>In 2024, Pro-Tips for Conquering Photo & Video Importers on Windows 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/samsung-tv-troubleshooting-how-to-perform-a-full-reset-effectively/"><u>Samsung TV Troubleshooting: How to Perform a Full Reset Effectively</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-review-of-the-dell-g5-5090-the-ultimate-choice-for-cost-effective-high-performance-gaming-computers/"><u>Top Review of the Dell G5 5090: The Ultimate Choice for Cost-Effective, High-Performance Gaming Computers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    