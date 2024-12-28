---
title: "Sudo and Windows: A Symbiotic Relationship Unveiled"
date: 2024-12-26T19:33:49.522Z
updated: 2024-12-28T07:00:55.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sudo and Windows: A Symbiotic Relationship Unveiled"
excerpt: "This Article Describes Sudo and Windows: A Symbiotic Relationship Unveiled"
keywords: Sudo & Windows SEO,Windows Security Keywords,Sudo Usage Tips,PowerShell in Windows,Admin Privilege Management,Enhanced Windows Performance,Secure System Operations
thumbnail: https://thmb.techidaily.com/c4f624b3f2bccad5b6da118fee2e7df55a3a172015085fad0a0d2520bcd157aa.jpg
---

## Sudo and Windows: A Symbiotic Relationship Unveiled

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/2024-approved-top-8-digital-collage-crafting-software/"><u>2024 Approved TOP 8 Digital Collage Crafting Software</u></a></li>
<li><a href="https://fox-http.techidaily.com/best-webcam-tripods-flex-neck-and-stands/"><u>Best Webcam Tripods, Flex-Neck and Stands</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-discord-overlay-failure-a-step-by-step-guide/"><u>Fixing Windows Discord Overlay Failure: A Step-by-Step Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Vivo V27? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-watch-live-tv-on-kodi/"><u>How to Watch Live TV on Kodi</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/premiere-audio-to-text-converters-for-2024/"><u>Premiere Audio-To-Text Converters for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/propelling-linux-with-powerful-windows-integration/"><u>Propelling Linux with Powerful Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-diagnostics-error-on-pc/"><u>Solutions for Fixing 'Diagnostics Error' On PC</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168126928-space-saving-systems-vs-traditional-workstations-make-your-choice/"><u>Space-Saving Systems Vs. Traditional Workstations: Make Your Choice!</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-journey-through-original-diablo/"><u>Step-by-Step Journey Through Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-ditch-integrated-video-on-windows/"><u>Why and How to Ditch Integrated Video on Windows</u></a></li>
</ul></div>

