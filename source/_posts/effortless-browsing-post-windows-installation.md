---
title: Effortless Browsing Post-Windows Installation
date: 2024-07-13T09:55:11.659Z
updated: 2024-07-14T09:55:11.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Browsing Post-Windows Installation
excerpt: This Article Describes Effortless Browsing Post-Windows Installation
keywords: Easy Browser Setup,Windows Laptop Use,Quick Login Access,Installed PC Navigation,Seamless OS Exploration,Post-Install Browsing,User-Friendly Desktop
thumbnail: https://thmb.techidaily.com/89e14fb11e9e592fbd5c568e89cdfa2567dfefcd7e2cc4ffd1db69453f4dcbe5.jpg
---

## Effortless Browsing Post-Windows Installation

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
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-smooth-start-gradual-appearance/"><u>2024 Approved  Smooth Start  Gradual Appearance</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/guide-youtube-to-mp4-ensuring-data-security/"><u>Guide  YouTube to MP4 - Ensuring Data Security</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-system-top-tips-for-black-screen-on-win11/"><u>Jumpstart Your System: Top Tips for Black Screen on Win11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-youtubes-earnings-explained-making-money-from-ads/"><u>2024 Approved  YouTube’s Earnings Explained  Making Money From Ads</u></a></li>
<li><a href="https://extra-tips.techidaily.com/go-pro-karma-drone-review/"><u>Go Pro Karma Drone Review</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-login-after-failures/"><u>How to Reactivate Windows Login After Failures</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-superlative-picture-based-adventure-builder/"><u>[New] Superlative Picture-Based Adventure Builder</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-installs-time-mastering-grouped-deployments-with-winstall-on-windows-11/"><u>Cutting Down Installs Time: Mastering Grouped Deployments with Winstall on Windows 11</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-vivo-s18e-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Vivo S18e Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-hues-overcoming-color-issues-on-windows/"><u>Harmonizing Hues: Overcoming Color Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-site-trust-on-windows-11/"><u>Mastering Site Trust on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-excelling-at-content-creation-a-guide-to-gamers-success/"><u>In 2024, Excelling at Content Creation  A Guide to Gamers' Success</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-file-management-altering-timestamps-in-windows/"><u>Cutting-Edge File Management: Altering Timestamps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-nonexistent-devices-in-os-windows-1011/"><u>Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-with-personal-touches/"><u>Enhancing Windows 11 with Personal Touches</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-error-x800704cf-on-windows-devices/"><u>Guide to Resolving Error X800704CF on Windows Devices</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-no-spending-no-sweat-the-ultimate-list-of-six-video-to-audio-conversion-hacks/"><u>In 2024, No Spending, No Sweat The Ultimate List of Six Video to Audio Conversion Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-interruptions-during-steam-video-streaming/"><u>Preventing Interruptions During Steam Video Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-setting-updeactivating-metric-tracker-in-win11/"><u>Mastery: Setting Up/Deactivating Metric Tracker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-window-resolutions/"><u>Enhancing Your Visual Experience with Window Resolutions</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-essential-web-destinations-for-free-background-scores-bgm/"><u>In 2024, Essential Web Destinations for Free Background Scores (BGM)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-and-fixing-windows-update-issues/"><u>Mastering the Art of Finding and Fixing Windows Update Issues</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/from-ephemeral-to-everlasting-the-art-of-saving-social-media-snaps/"><u>From Ephemeral to Everlasting  The Art of Saving Social Media Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-persistent-boot-related-windows-audio-failures/"><u>Eliminate Persistent Boot-Related Windows Audio Failures</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-unlock-your-devices-full-potential-with-io-screener-for-2024/"><u>[New] Unlock Your Device's Full Potential with IO Screener for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-high-res-display-settings-in-windows/"><u>Mastering High-Res Display Settings in Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-metaverse-vs-multimeva-unveiling-their-comparative-features-for-2024/"><u>[New] Metaverse Vs. Multimeva  Unveiling Their Comparative Features for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/income-investigation-the-streamlined-3-part-method-to-assess-your-youtube-income-levels/"><u>Income Investigation  The Streamlined 3-Part Method to Assess Your YouTube Income Levels</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-demystifying-youtubes-seo-a-keyword-research-guide/"><u>2024 Approved  Demystifying YouTube's SEO  A Keyword Research Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-guiding-through-audio-transition-in-ableton-live/"><u>[New] Guiding Through Audio Transition in Ableton Live</u></a></li>
<li><a href="https://win11.techidaily.com/first-day-with-windows-11-heres-what-not-to-do-top-7-mistakes/"><u>First Day with Windows 11? Here's What Not to Do! - Top 7 Mistakes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/initiate-your-virtual-presence-with-ease-live-streaming-101-for-2024/"><u>Initiate Your Virtual Presence with Ease  Live Streaming 101 for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-how-to-edit-youtube-videos-in-adobe-premiere/"><u>[Updated] In 2024, How to Edit YouTube Videos in Adobe Premiere</u></a></li>
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-playable-media-error-xc10100bf/"><u>Overcoming Non-Playable Media Error XC10100BF</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-preventing-sudden-deletion-of-personal-videos-from-fb-for-2024/"><u>[New] Preventing Sudden Deletion of Personal Videos From FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
</ul></div>
