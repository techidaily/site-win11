---
title: Direct Download Approaches for New Users
date: 2025-01-20T02:52:34.405Z
updated: 2025-01-25T05:56:21.159Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Download Approaches for New Users
excerpt: This Article Describes Direct Download Approaches for New Users
keywords: Direct Download Tips,Newbie Download Guide,Easy File Access,Immediate Content Acquisition,Quick File Retrieval,Direct Media Downloads,User-Friendly Files
thumbnail: https://thmb.techidaily.com/7f563c6cc49d9e48b9aa551214712c5134f2db5185be39a48c0e895d012e0af9.jpg
---

## Direct Download Approaches for New Users

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once the process is complete, you can start using the new browser.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by[launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-ice-prowess-unleashed-2022-olympics-sprinting-spectacles/"><u>[New] 2024 Approved Ice Prowess Unleashed 2022 Olympics Sprinting Spectacles</u></a></li>
<li><a href="https://article-files.techidaily.com/new-begin-your-journey-into-xps-video-editing-world-for-2024/"><u>[New] Begin Your Journey Into Xp's Video Editing World for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-basic-screen-capture-windows-10-version/"><u>[Updated] Basic Screen Capture, Windows 10 Version</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unrivaled-video-tech-for-apple-phones/"><u>2024 Approved Unrivaled Video Tech for Apple Phones</u></a></li>
<li><a href="https://screen-capture.techidaily.com/detailed-insights-into-camstudio-capture-functionality-for-2024/"><u>Detailed Insights Into CamStudio Capture Functionality for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-windows-help-top-5-routes-uncovered/"><u>Fast Track to Windows Help - Top 5 Routes Uncovered</u></a></li>
<li><a href="https://blog-min.techidaily.com/gratuit-konvertentie-wav-naar-m4a-online-movavi/"><u>Gratuit Konvertentie Wav Naar M4a Online - Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-edge-off-windows-11-shapes/"><u>How to Edge Off: Windows 11 Shapes</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-discovering-the-leading-6-head-mounted-gopro-systems-for-capturing-life/"><u>In 2024, Discovering the Leading 6 Head-Mounted GOPRO Systems for Capturing Life</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-compatibility-woes-fix-your-programs-in-windows/"><u>No More Compatibility Woes: Fix Your Programs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/propel-your-productivity-top-5-must-have-windows-11-apps/"><u>Propel Your Productivity: Top 5 Must-Have Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-missing-windows-quick-fixes-for-windows-1011/"><u>Reviving Missing Windows: Quick Fixes for Windows 10/11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-affordable-bluetooth-speakers-of-2022-your-ultimate-guide-to-summer-soundtracks/"><u>Top Affordable Bluetooth Speakers of 2022 - Your Ultimate Guide to Summer Soundtracks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-simple-techniques-for-amazing-slow-motion-footage-in-android-for-2024/"><u>Unveiling Simple Techniques for Amazing Slow-Motion Footage in Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-size-spectrum-of-your-windows-apps/"><u>Unveiling the Size Spectrum of Your Windows Apps</u></a></li>
</ul></div>

