---
title: Direct Download Tactics for New Windows Users
date: 2024-07-13T10:20:18.851Z
updated: 2024-07-14T10:20:18.851Z
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
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-task-mastery-initiating-task-manager-in-win11/"><u>Administrative Task Mastery: Initiating Task Manager in Win11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-ai-advertising-wondershare-virbo-glossary-for-2024/"><u>What Is AI Advertising? | Wondershare Virbo Glossary for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-creating-windows-shortcuts-for-uwp/"><u>Accelerating Workflow: Creating Windows Shortcuts for UWP</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-maximizing-color-grading-efficiency-with-obs-and-lut-techniques-for-2024/"><u>[New] Maximizing Color Grading Efficiency with OBS and LUT Techniques for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtube-studio-monetization-check-ensure-your-channels-monetization/"><u>[Updated] YouTube Studio Monetization Check  Ensure Your Channel's Monetization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-a-critical-look-at-zd-soft-recorder-capabilities/"><u>[Updated] In 2024, A Critical Look at ZD Soft Recorder Capabilities</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quick-tips-for-overcoming-adobe-premieres-srt-export-issues/"><u>In 2024, Quick Tips for Overcoming Adobe Premiere's SRT Export Issues</u></a></li>
<li><a href="https://screen-recording.techidaily.com/5-best-screen-recorders-for-windows-11/"><u>5 Best Screen Recorders For Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clock-display-window-10-and-11-guide/"><u>Adjusting Clock Display: Window 10 & 11 Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fascinating-film-categories-to-lure-viewers/"><u>Fascinating Film Categories to Lure Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-stepping-up-your-game-understanding-mcns-and-their-impact-on-creators/"><u>[New] Stepping Up Your Game  Understanding MCNs and Their Impact on Creators</u></a></li>
<li><a href="https://extra-information.techidaily.com/beyond-limits-a-critical-look-at-panasonics-hx-a1-actionrecorder-for-2024/"><u>Beyond Limits - A Critical Look at Panasonic’s HX-A1 ActionRecorder for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-software-removal-crafting-wins-context-menu-aids/"><u>Accelerating Software Removal: Crafting Win's Context Menu Aids</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-email-checking-add-gmail-to-your-windows-side/"><u>Accelerated Email Checking: Add Gmail to Your Window's Side</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-ram-demand-of-user-service-on-platforms/"><u>Addressing High RAM Demand of User Service on Platforms</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-premier-virtual-applications-for-deciphering-clearer-soundtracks/"><u>Updated 2024 Approved Premier Virtual Applications for Deciphering Clearer Soundtracks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-vivo-y27-4g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Vivo Y27 4G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-pureaiediting-refined-photo-craftsmanship/"><u>2024 Approved  PureAiEditing  Refined Photo Craftsmanship</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-mobile-devices-for-windows-mic-input/"><u>Amplify Mobile Devices for Windows Mic Input</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-cut-down-on-hassle-with-easy-ipad-recording-methods/"><u>[Updated] Cut Down On Hassle With Easy iPad Recording Methods</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-8-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your Apple iPhone 8?</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-strategies-keeping-epic-launcher-non-freezing/"><u>Avoidance Strategies: Keeping Epic Launcher Non-Freezing</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-competitive-counter-strike-gameplay/"><u>Ace Your Competitive Counter-Strike Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disruptions-fixing-video-restart-error/"><u>Avoiding Disruptions: Fixing Video Restart Error</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-empty-folder-warning-windows/"><u>Addressing Empty Folder Warning Windows</u></a></li>
<li><a href="https://win11.techidaily.com/assess-if-your-system-qualifies-for-new-windows-11/"><u>Assess if Your System Qualifies for New Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-content-sharing-youtube-standards-vs-creative-commons/"><u>2024 Approved  Navigating Content Sharing  YouTube Standards Vs. Creative Commons</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-transfers-avoiding-sudden-speed-slumps/"><u>Accelerating Steam Transfers: Avoiding Sudden Speed Slumps</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/optimize-profitability-the-science-behind-high-roi-fb-animatons/"><u>Optimize Profitability  The Science Behind High-ROI FB Animatons</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-apple-iphone-12-pro-max-and-ipad-securely-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on Apple iPhone 12 Pro Max and iPad Securely</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-spatial-audio-setup-guide/"><u>Activating Windows 11: Spatial Audio Setup Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-complete-process-of-adding-soundtracks-to-ig/"><u>[New] 2024 Approved  The Complete Process of Adding Soundtracks to IG</u></a></li>
<li><a href="https://techidaily.com/repair-broken-or-corrupt-video-files-of-vivo-y27s-by-stellar-video-repair-mobile-video-repair/"><u>Repair broken or corrupt video files of Vivo Y27s</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-steady-yourself-against-oculus-nausea/"><u>[New] Steady Yourself Against Oculus Nausea</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-error-after-device-removal/"><u>Addressing DXGI Error After Device Removal</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamlined-techniques-to-log-and-preserve-gotomeetings-for-2024/"><u>[Updated] Streamlined Techniques to Log and Preserve GoToMeetings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/altering-monitors-order-in-windows/"><u>Altering Monitors' Order in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/boost-your-capacity-20-premier-gratis-cloud-storage-options-for-2024/"><u>Boost Your Capacity  20 Premier Gratis Cloud Storage Options for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-stay-on-top-of-your-streaks-must-try-techniques-for-2024/"><u>[Updated] Stay on Top of Your Streaks  Must-Try Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-the-call-not-invoked-issue-in-malwarebytes/"><u>Addressing and Fixing the Call Not Invoked Issue in Malwarebytes</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ilm-whiz-for-2024/"><u>NanoFilm Whiz for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-flv-editors-for-windows-11108187-easily-edit-flv-videos-on-pc/"><u>Updated In 2024, FLV Editors for Windows 11/10/8.1/8/7 Easily Edit FLV Videos on PC</u></a></li>
<li><a href="https://win11.techidaily.com/address-windows-missing-camera-mystery-in-device-manager/"><u>Address Windows' Missing Camera Mystery in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-synchronized-data-across-your-multiple-windows-desktops-with-aoemi/"><u>Achieve Synchronized Data Across Your Multiple Windows Desktops With AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-visual-storytelling-with-immersive-titles-in-ae/"><u>[Updated] Visual Storytelling with Immersive Titles in AE</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-mac-movie-making-101-choosing-the-right-software-for-you/"><u>New 2024 Approved Mac Movie Making 101 Choosing the Right Software for You</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disk-read-failures-on-your-pc/"><u>Avoiding Disk Read Failures on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/automation-bane-keep-your-windows-backdrop-steady/"><u>Automation Bane: Keep Your Windows Backdrop Steady</u></a></li>
<li><a href="https://win11.techidaily.com/acceleration-at-fingertips-3-ways-to-enhance-mouse-double-click-speed/"><u>Acceleration at Fingertips: 3 Ways to Enhance Mouse Double-Click Speed</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-phone-dialer-in-windows-11/"><u>Accessing Phone Dialer in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-samsung-galaxy-s23-fe-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Samsung Galaxy S23 FE Activity | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incorrect-profile-errors-windows-1011-guide/"><u>Addressing Incorrect Profile Errors: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-0x0-failure-in-win11-setup-procedures/"><u>Avoid 0X0 Failure in Win11 Setup Procedures</u></a></li>
</ul></div>
