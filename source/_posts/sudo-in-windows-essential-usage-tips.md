---
title: "Sudo in Windows: Essential Usage Tips"
date: 2024-12-11T08:51:14.455Z
updated: 2024-12-13T07:48:59.066Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sudo in Windows: Essential Usage Tips"
excerpt: "This Article Describes Sudo in Windows: Essential Usage Tips"
keywords: Sudo Windows Guide,Sudo Use Tips,Sudo Command Help,Mastering Sudo,Sudo Best Practices,Sudo Commands Efficiency,Optimizing Sudo Usage
thumbnail: https://thmb.techidaily.com/287414ff43ab53f27880b8114eed3693184381a70cdfc416ba85990af80f04e8.jpg
---

## Sudo in Windows: Essential Usage Tips

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://novels-ebooks.techidaily.com/138577023-9781462098156-the-real-prophet-of-doom/"><u> "The Real, Prophet, of Doom "! ... (...!) | Free Book</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-speedy-shots-for-immersive-narratives/"><u>[New] 2024 Approved Speedy Shots for Immersive Narratives</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-pixel-pro-complimentary-photo-beautification-for-smartphones/"><u>[New] In 2024, Pixel Pro Complimentary Photo Beautification for Smartphones</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/treamline-your-youtube-video-process-with-faster-techniques-for-2024/"><u>[New] Streamline Your YouTube Video Process with Faster Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blank-screen-on-windows-remote-workspace/"><u>Fixing Blank Screen on Windows Remote Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-the-windows-terminal-settings-to-their-defaults-in-windows-11/"><u>How to Reset the Windows Terminal Settings to Their Defaults in Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-look-at-the-newest-ring-video-doorbell-power-solution-insights/"><u>In-Depth Look at the Newest Ring Video Doorbell Power Solution Insights</u></a></li>
<li><a href="https://win-cheats.techidaily.com/kostenlose-und-schnelle-album-freigabe-auf-dem-iphone-keine-arbeit-erforderlich/"><u>Kostenlose Und Schnelle Album-Freigabe Auf Dem iPhone: Keine Arbeit Erforderlich!</u></a></li>
<li><a href="https://solve-info.techidaily.com/mastering-modern-banking-challenges-proven-abbyy-strategies-for-thriving-through-crisis-and-beyond/"><u>Mastering Modern Banking Challenges: Proven ABBYY Strategies for Thriving Through Crisis and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-button-image-functionality/"><u>Restoring Taskbar Button Image Functionality</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/revisiting-the-old-but-gold-a-detailed-review-of-the-netgear-c3000-router/"><u>Revisiting the Old but Gold - A Detailed Review of the Netgear C3000 Router</u></a></li>
<li><a href="https://win11.techidaily.com/securely-linking-win-key-and-microsoft-identity/"><u>Securely Linking Win Key and Microsoft Identity</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/top-gratis-video-player-software-supporting-h265hevc-and-4k-quality/"><u>Top Gratis Video Player Software Supporting H.265/HEVC & 4K Quality</u></a></li>
</ul></div>

