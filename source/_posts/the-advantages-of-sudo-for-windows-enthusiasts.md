---
title: The Advantages of Sudo for Windows Enthusiasts
date: 2024-10-20T06:01:25.721Z
updated: 2024-10-21T11:43:51.745Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-discovering-those-who-left-my-instagram-circle-for-2024/"><u>[New] Discovering Those Who Left My Instagram Circle for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-architectural-marvels-for-your-blocky-oasis-for-2024/"><u>[Updated] Architectural Marvels for Your Blocky Oasis for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-surf-in-focus-cutting-edge-action-cameras/"><u>[Updated] Surf in Focus Cutting-Edge Action Cameras</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-brush-up-skills-unveiling-the-ultimate-8-iphone-drawing-tools/"><u>2024 Approved Brush Up Skills Unveiling the Ultimate 8 iPhone Drawing Tools</u></a></li>
<li><a href="https://win11.techidaily.com/easy-access-mastering-folders-and-files-props/"><u>Easy Access: Mastering Folders and Files Props</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-taskbar-tweaks-in-windows-11/"><u>Expert Guide to Taskbar Tweaks in Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-honor-x50-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Honor X50</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-usage-positioning-shortcuts-adjacent-to-power-button/"><u>Innovative Usage: Positioning Shortcuts Adjacent to Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-printer-friendly-presentations-on-windows/"><u>Mastering the Art of Printer-Friendly Presentations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-elusive-theme-options-through-registry/"><u>Mastering Windows 11'S Elusive Theme Options Through Registry</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-prevent-windows-control-center-crashes/"><u>Quick-Fix Guide to Prevent Windows Control Center Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-vms-from-windows-host-to-linux-guest-with-hyper-v/"><u>Setting Up VMs: From Windows Host to Linux Guest with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-file-management-customizing-explorer-comments/"><u>Tips for Efficient File Management: Customizing Explorer Comments</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-7-solutions-how-to-restore-sync-for-icloud-pictures-on-iphone/"><u>Top 7 Solutions: How To Restore Sync For iCloud Pictures On iPhone</u></a></li>
<li><a href="https://win-cheats.techidaily.com/troubleshooting-guide-solving-issues-with-apple-musics-family-sharing-feature/"><u>Troubleshooting Guide: Solving Issues with Apple Music's Family Sharing Feature</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/uniting-social-media-and-television-with-fb-live/"><u>Uniting Social Media & Television with FB Live</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
</ul></div>

