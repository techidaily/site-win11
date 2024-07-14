---
title: Post-Install Windows? Here's How to Get Online
date: 2024-07-13T11:03:17.818Z
updated: 2024-07-14T11:03:17.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Post-Install Windows? Here's How to Get Online
excerpt: This Article Describes Post-Install Windows? Here's How to Get Online
keywords: Post-Win Setup Guide,Getting Online After Install,Installing Win, Start Internet,Windows Setup Complete, Connect,Initial Windows Use Tips,New Windows, Go Online Now,Windows Setup, Access Web
thumbnail: https://thmb.techidaily.com/57ebcefbd038d5518117756c100dd6989f85e0e6cff4615a7e12084a4473983a.jpg
---

## Post-Install Windows? Here's How to Get Online

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and [Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose [Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

Once the process is complete, you can start using the new browser.

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by [launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

## Start Browsing on Your Fave Browser From Day One

 Hopefully, you were able to download a browser and install it using one of these methods. Windows offers a ton of options to get things done. Take your pick when installing a browser without a browser. What matters is installing a browser you think best suits your needs.


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
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-this-article-will-focus-on-understanding-the-secret-tips-in-wondershare-filmora-that-you-can-use-to-edit-videos-faster-and-more-efficiently./"><u>Updated In 2024, This Article Will Focus on Understanding the Secret Tips in Wondershare Filmora that You Can Use to Edit Videos Faster and More Efficiently</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/symphony-of-screenshots-incorinas-music-into-social-media-for-2024/"><u>Symphony of Screenshots  Incorinas Music Into Social Media for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-essential-guide-to-free-attractive-youtube-intros/"><u>The Essential Guide to Free, Attractive YouTube Intros</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-vivo-y36-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Vivo Y36 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instagrammable-pcs-how-to-add-your-chosen-weather-image-in-windows-11-status-bar/"><u>Instagrammable PCs: How to Add Your Chosen Weather Image in Windows 11 Status Bar</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-xiaomi-13t-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Xiaomi 13T Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-on-mending-windows-1011-corrupted-recycle-bin/"><u>Masterclass on Mending Windows 10/11 Corrupted Recycle Bin</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-long-start-ups-in-windows-11-easily-and-swiftly/"><u>Conquering Long Start-Ups in Windows 11 Easily and Swiftly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/step-up-vfx-game-discover-these-8-sites-for-free-backdrops-and-footage-for-2024/"><u>Step Up VFX Game - Discover These 8 Sites for FREE Backdrops & Footage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-private-character-editor-in-windows/"><u>How to Open the Private Character Editor in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-crafting-seamless-virtual-gatherings-with-google-meet/"><u>[Updated] Crafting Seamless Virtual Gatherings with Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-internet-connections-a-guide-for-steam-on-windows/"><u>Fixing Internet Connections: A Guide for Steam on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-frame-by-frame-flow-essential-tactics-to-combat-video-lag-windows/"><u>Mastering Frame-by-Frame Flow: Essential Tactics to Combat Video Lag Windows</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-visual-upgrades-with-themes-from-microsoft-store/"><u>Harnessing Visual Upgrades with Themes From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-os-alerts-utilizing-command-prompt-to-identify-and-resolve-windows-issues/"><u>Interpreting OS Alerts: Utilizing Command Prompt to Identify and Resolve Windows Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-error-e8024002e-for-smooth-updates/"><u>Overcoming Error E:8024002E for Smooth Updates</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-elite-performers-top-picks-from-skate-highlights/"><u>[New] 2024 Approved  Elite Performers  Top Picks From Skate Highlights</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ting-privacy-share-exclusive-youtube-clips-through-gmail-for-2024/"><u>Elevating Privacy  Share Exclusive YouTube Clips Through Gmail for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-buzzing-the-net-with-humor-your-comprehensive-guide-to-9gag/"><u>[New] Buzzing the Net with Humor  Your Comprehensive Guide to 9GAG</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-reverse-engineering-how-to-reverse-video-clips-in-final-cut-pro-for-2024/"><u>Updated Reverse Engineering How to Reverse Video Clips in Final Cut Pro for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-best-time-lapse-tools-and-techniques-no5/"><u>[New] 2024 Approved  Best Time-Lapse Tools & Techniques - No.5</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disconnect-fixing-gif-size-problems-in-discord-on-windows/"><u>Overcoming Disconnect: Fixing GIF Size Problems in Discord on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exploring-hues-from-textbooks-to-canvas/"><u>Exploring Hues  From Textbooks to Canvas</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-and-craft-of-podcast-storytelling/"><u>[New] The Art and Craft of Podcast Storytelling</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-visual-ventures-free-themes-to-elevate-your-channel/"><u>In 2024, Visual Ventures  FREE Themes to Elevate Your Channel</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-file-systems-better-with-diskspace-added-to-windows-menu/"><u>Discover File Systems Better with Diskspace Added to Windows Menu</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-resolve-audacitys-device-open-error-on-pc/"><u>Method to Resolve Audacity's Device Open Error on PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unrequested-file-explorer-startups/"><u>Addressing Unrequested File Explorer Startups</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-ideal-virtual-sets-crafting-excellent-google-meet-backdrops/"><u>In 2024, Ideal Virtual Sets  Crafting Excellent Google Meet Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/proven-methods-to-elevate-your-filmora-editing-skills/"><u>Proven Methods to Elevate Your Filmora Editing Skills</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-oppo-a18-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Oppo A18 to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-and-changing-login-credentials-in-win-11/"><u>Guide to Resetting and Changing Login Credentials in Win 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-revolutionize-unboxing-on-instagram-a-guide-to-popularity/"><u>In 2024, Revolutionize Unboxing on Instagram  A Guide to Popularity</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-windows-programming-file-layout-pe/"><u>Deciphering the Windows Programming File Layout (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-imessage-for-windows-expert-techniques-revealed/"><u>Leveraging iMessage for Windows: Expert Techniques Revealed</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-bridging-aiff-and-mp3-techniques-for-high-quality-audio-conversion/"><u>Updated 2024 Approved Bridging AIFF and MP3 Techniques for High-Quality Audio Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-files-vanish-permanently-in-your-desktop-trash-bin-windows-11/"><u>How to Make Files Vanish Permanently in Your Desktop Trash Bin (Windows 11)</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-realme-11-proplus-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Realme 11 Pro+ Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-essential-tips-for-evaluating-the-best-sound-editing-talent-of-our-time/"><u>Updated Essential Tips for Evaluating the Best Sound Editing Talent of Our Time</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ms-store-downloads-techniques-and-tips/"><u>Boosting MS Store Downloads: Techniques and Tips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/leveraging-likes-and-shares-for-financial-gain-on-snapchat/"><u>Leveraging Likes and Shares for Financial Gain on Snapchat</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-cant-connect-nvidia-error-on-win-11-devices/"><u>Bypassing the Can't Connect Nvidia Error on Win 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://driver-install.techidaily.com/methodical-update-for-modern-windows-and-intell-drivers/"><u>Methodical Update for Modern Windows & Intell Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-manage-files-and-tabs-windows-11/"><u>Expert Strategies to Manage Files and Tabs (Windows 11)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-transforming-conversations-with-discords-powerful-graphics-library/"><u>[Updated] 2024 Approved  Transforming Conversations with Discord's Powerful Graphics Library</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-realme-gt-3-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Realme GT 3 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top-10-best-websites-like-omegle-for-2024/"><u>New Top 10 Best Websites Like Omegle for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x80780119-on-system-image/"><u>Addressing Windows Error 0X80780119 on System Image</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/vivo-y27-4g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Vivo Y27 4G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-on-computing-power-spent-by-malware-scanners/"><u>Cut Down on Computing Power Spent by Malware Scanners</u></a></li>
<li><a href="https://win11.techidaily.com/from-problem-to-perfection-tactics-to-install-missing-features-in-windows-11-and-11-pro/"><u>From Problem to Perfection: Tactics to Install Missing Features in Windows 11 & 11 Pro</u></a></li>
</ul></div>
