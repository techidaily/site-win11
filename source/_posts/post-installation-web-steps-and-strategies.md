---
title: "Post-Installation Web: Steps and Strategies"
date: 2025-01-29T21:30:12.838Z
updated: 2025-02-04T10:13:04.962Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Post-Installation Web: Steps and Strategies"
excerpt: "This Article Describes Post-Installation Web: Steps and Strategies"
keywords: Post-Install SEO,Web Optimization,Installation Success,Web Enhancement,Setup Boosting,Online Growth,Strategy Improvement
thumbnail: https://thmb.techidaily.com/b2d913b57df62249e08cf6aa2213e0e218bf0ce45d452041bd7c83bf359b02fd.jpg
---

## Post-Installation Web: Steps and Strategies

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and[Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose[Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once the process is complete, you can start using the new browser.

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by[launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-in-2024-phantom-3-face-off-apparition-4-unveiled/"><u>[New] In 2024, Phantom 3 Face-Off Apparition 4 Unveiled</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-transition-to-darkness-premiere-pro-techniques/"><u>[New] In 2024, Transition to Darkness Premiere Pro Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-ultimate-mac-visuals-plus-acoustics-scribing-tool/"><u>[New] In 2024, Ultimate Mac Visuals + Acoustics Scribing Tool</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-rights-overload-immediate-content-scrapping/"><u>[Updated] In 2024, Rights Overload Immediate Content Scrapping</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-periscope-unveiled-free-access-benefits-and-signing-up-guide/"><u>[Updated] Periscope Unveiled Free Access, Benefits & Signing Up Guide</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-control-of-deletion-popups-in-windows/"><u>Convenient Control of Deletion Popups in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-11-error-code-0xc1900101/"><u>Decoding Windows 11 Error Code: 0XC1900101</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-11-disruptions-with-simple-fixes/"><u>Easing WINDOWS 11 Disruptions with Simple Fixes</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-apple-iphone-13-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On Apple iPhone 13</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-how-to-write-a-script-for-a-youtube-video/"><u>In 2024, How to Write a Script for a YouTube Video</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-note-12-4g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi Note 12 4G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-energy-monitors-set-up-fully-charged-notifications-in-win11/"><u>Mastering Energy Monitors: Set Up Fully Charged Notifications in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-assertion-of-an-unempty-directory-error-x80070091/"><u>Remedying Windows' Assertion of an Unempty Directory (Error X80070091)</u></a></li>
<li><a href="https://win11.techidaily.com/solving-other-application-interference-with-pc-audio/"><u>Solving Other Application Interference with PC Audio</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-freezing-issues-with-steam-and-games-on-windows/"><u>Tackling Common Freezing Issues with Steam and Games on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-win-1011-installer-success/"><u>Unlocking the Secrets of Win 10/11 Installer Success</u></a></li>
<li><a href="https://win11.techidaily.com/victory-over-visual-vexations-solve-sonic-adventures-full-screen-crash-issues-in-windows-11/"><u>Victory over Visual Vexations: Solve Sonic Adventure's Full-Screen Crash Issues in Windows 11</u></a></li>
<li><a href="https://techidaily.com/why-can-t-i-play-mp4-files-on-my-motorola-moto-g84-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Why can’t I play MP4 files on my Motorola Moto G84 5G?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/youtubemp4/"><u>YouTubeへの高解像度MP4映像アップロード手順</u></a></li>
</ul></div>

