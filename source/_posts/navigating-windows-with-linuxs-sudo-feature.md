---
title: Navigating Windows with Linux's Sudo Feature
date: 2024-07-13T10:59:28.516Z
updated: 2024-07-14T10:59:28.516Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows with Linux's Sudo Feature
excerpt: This Article Describes Navigating Windows with Linux's Sudo Feature
keywords: Linux Sudo Use,Sudo in Linux Guide,Switching to Linux Root,Linux Admin Command,Command Line Power,Root Access Linux,Linux Superuser Privileges
thumbnail: https://thmb.techidaily.com/e0a34c7a81fb8279e0e4f8e61ff399b11932a0b059873f4809f00d7b660fc375.jpg
---

## Navigating Windows with Linux's Sudo Feature

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
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-browsing-game-master-microsoft-edge-gestures-on-windows-11/"><u>Step-Up Your Browsing Game: Master Microsoft Edge Gestures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-new-pdf-reader-as-standard/"><u>Instituting New PDF Reader as Standard</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-unlock-efficient-video-editing-top-5-free-mpeg-video-splitters-for-2024/"><u>Updated Unlock Efficient Video Editing Top 5 Free MPEG Video Splitters for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/"><u>[Updated] The Role of Youtube Images in Video Promotion and Discovery for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ideal-steadicams-for-capturing-quality-uav-visuals/"><u>[Updated] Ideal Steadicams for Capturing Quality UAV Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-exception-handling-breaking-point-strategies/"><u>Mastering Exception Handling: Breaking Point Strategies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-adopting-innovations-mask-and-filter-methods-for-google-meet/"><u>2024 Approved  Adopting Innovations  Mask & Filter Methods for Google Meet</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-online-revenue-monetizing-on-youtube-with-500plus-viewers/"><u>[Updated] Maximize Online Revenue  Monetizing on Youtube with 500+ Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-proxy-configuration-in-win-11/"><u>Mastery of Proxy Configuration in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/installing-kali-linux-effortlessly-on-a-windows-pc/"><u>Installing Kali Linux Effortlessly on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-terminal-in-quake-mode/"><u>How to Engage Terminal in Quake Mode</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-gpo-report-generation-via-gpresult/"><u>Mastering GPO Report Generation via GPResult</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/photo-refinement-essentials-expert-tips-for-efficient-background-clearance-for-2024/"><u>Photo Refinement Essentials  Expert Tips for Efficient Background Clearance for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-measures-to-mend-ms-store-malfunctions-in-windows-os/"><u>Masterful Measures to Mend MS Store Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-speed-up-download-speeds-in-utorrent-for-windows/"><u>How to Speed Up Download Speeds in uTorrent for Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-democracy-dive-deep-top-5-political-simulation-titles-for-2024/"><u>[Updated] Democracy Dive Deep  Top 5 Political Simulation Titles for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-essential-screen-recording-steps-for-perfection/"><u>[Updated] 2024 Approved  Essential Screen Recording Steps for Perfection</u></a></li>
<li><a href="https://extra-hints.techidaily.com/trendsetting-images-their-histories/"><u>Trendsetting Images  Their Histories</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-essentials-in-windows-photo-editing-keys/"><u>Mastering the Essentials in Windows Photo Editing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/silence-ended-resurrecting-dormant-slack-notifications-in-windows-11/"><u>Silence Ended? Resurrecting Dormant Slack Notifications in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/zero-price-zero-hassle-top-windowsmac-recorder-choices-for-2024/"><u>Zero Price, Zero Hassle - Top Windows/Mac Recorder Choices for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlined-method-windows-clown-fish-audio-tweaker/"><u>In 2024, Streamlined Method  Windows Clown Fish Audio Tweaker</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-easy-video-joiner-is-free-software-that-is-created-to-help-users-to-join-merge-and-combine-different-video-clips-to-form-a-single-movie-for-2024/"><u>Updated Easy Video Joiner Is Free Software that Is Created to Help Users to Join, Merge and Combine Different Video Clips to Form a Single Movie for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-visionary-6-eco-friendly-minecraft-mansions/"><u>2024 Approved  Visionary 6 Eco-Friendly Minecraft Mansions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-sony-xperia-1-v-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Sony Xperia 1 V IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stealthy-controls-for-displaying-windows-clock/"><u>Stealthy Controls for Displaying Windows Clock</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-innovative-auditory-experiences-mastering-vocal-changes-in-tiktok-videos/"><u>[Updated] 2024 Approved  Innovative Auditory Experiences  Mastering Vocal Changes in TikTok Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-iphone-lens-magic-the-ultimate-10-composition-techniques/"><u>2024 Approved  IPhone Lens Magic  The Ultimate 10 Composition Techniques</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-take-your-videos-to-the-next-level-free-sound-effects-for-final-cut-pro-for-2024/"><u>New Take Your Videos to the Next Level Free Sound Effects for Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/purify-your-pc-go-bare-with-tiny11/"><u>Purify Your PC: Go Bare with Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-smoothly-integrate-icloud-with-your-windows-machine/"><u>How to Smoothly Integrate iCloud with Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/quick-methods-to-nullify-laptops-built-in-input-device/"><u>Quick Methods to Nullify Laptop's Built-In Input Device</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-silent-audio-during-powerpoint-presentations/"><u>Solutions to Silent Audio During PowerPoint Presentations</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-poco-x6-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Poco X6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-eliminating-server-glitches-impacting-ms-store-on-win-1111/"><u>Quick Fix: Eliminating Server Glitches Impacting MS Store on Win 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/peek-inside-the-persona-machine-how-to-launch-windows-secret-self-analysis-engine/"><u>Peek Inside the Persona Machine: How to Launch Windows’ Secret Self-Analysis Engine</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-ubiquitous-blue-screen-enigma/"><u>Overcoming the Ubiquitous Blue Screen Enigma</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-your-typing-routine-9-fixes-for-broken-keyboard-commands-on-windows/"><u>Rebooting Your Typing Routine: 9 Fixes for Broken Keyboard Commands on Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-go-live-on-instagram-for-2024/"><u>[New] How to Go Live on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-post-zestful-days-of-life-on-windows-pcs/"><u>Reviving Post-Zestful Days of Life on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-automatic-network-proxy-fixes/"><u>Mastering Windows' Automatic Network Proxy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-education-elements-into-windows-ui/"><u>Infuse Education Elements Into Windows UI</u></a></li>
</ul></div>
