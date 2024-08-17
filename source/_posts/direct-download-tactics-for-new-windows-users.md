---
title: Direct Download Tactics for New Windows Users
date: 2024-08-16T00:13:48.686Z
updated: 2024-08-17T00:13:48.686Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Download Tactics for New Windows Users
excerpt: This Article Describes Direct Download Tactics for New Windows Users
keywords: Win Users Direct Download,Downloading OS X,Direct Windows Install,New PC Direct Installs,Save Windows Setup,Fast Windows Download,Easy Windows Transfer
thumbnail: https://thmb.techidaily.com/e271cbb6eb6a65ff2648f6dddd1fc0c078a843660eba98a715724fa951b431ee.jpg
---

## Direct Download Tactics for New Windows Users

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by [launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-paving-way-to-success-premier-video-gatherings-post-vidcon/"><u>[New] 2024 Approved  Paving Way to Success  Premier Video Gatherings (Post-VidCon)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-avoiding-edgenuitys-grasp-tips-for-quickly-skipping-video-lessons/"><u>[New] Avoiding Edgenuity's Grasp  Tips for Quickly Skipping Video Lessons</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-effortless-guide-never-see-youtube-shorts-again/"><u>[Updated] 2024 Approved  Effortless Guide  Never See YouTube Shorts Again</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-top-4-techniques-for-effective-hp-laptop-screen-capture/"><u>[Updated] Top 4 Techniques for Effective HP Laptop Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-alternative-methods-in-windows-exploration-no-ls/"><u>Deciphering Alternative Methods in Windows Exploration (No LS)</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-clipboard-problems-in-windows-11/"><u>Diagnosing Clipboard Problems in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/dive-deep-into-the-digital-world-adding-panoramic-photos-to-your-feed-for-2024/"><u>Dive Deep Into the Digital World  Adding Panoramic Photos to Your Feed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-chromecast-sound-problems-a-comprehensive-guide-for-users/"><u>Fixing Chromecast Sound Problems: A Comprehensive Guide for Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-runtime-broker-enhances-system-efficiency-and-security/"><u>How Runtime Broker Enhances System Efficiency & Security</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-display-not-available-error-in-windows-11/"><u>How to Correct 'Display Not Available' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-14-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi 14 Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-print-functions-in-microsofts-security-shield/"><u>Implementing Print Functions in Microsoft's Security Shield</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-abbreviated-action-sequences-script/"><u>In 2024, Abbreviated Action Sequences Script</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-expert-techniques-for-ps4-gameplay-documentation/"><u>In 2024, Expert Techniques for PS4 Gameplay Documentation</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mobile-laughs-and-memes/"><u>In 2024, Mobile Laughs & Memes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-forefront-ai-the-future-comparing-it-against-chatgpt-in-detail/"><u>Is Forefront AI the Future? Comparing It Against ChatGPT in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://win11.techidaily.com/locate-vanished-settings-a-guide-to-finding-them-on-win11/"><u>Locate Vanished Settings: A Guide to Finding Them on Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-apple-iphone-11-pro-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your Apple iPhone 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-freeze-issues-photoshopping-onoff-windows-11-versions-2023/"><u>Overcoming Freeze Issues: Photoshopping On/Off Windows 11, Versions 2023</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-0x80072efd-on-windows-devices/"><u>Quick Guide to Resolve 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-ram-overcoming-obstacles-in-windows/"><u>Reigniting RAM: Overcoming Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-averting-crashes-of-epic-games-launcher/"><u>Strategies for Averting Crashes of Epic Games Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peace-sleep-mode-strategies/"><u>The Path to Peace: Sleep Mode Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
</ul></div>
