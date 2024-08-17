---
title: "Reviving Winget: A Guide for Windows 11 Users"
date: 2024-08-16T00:41:55.064Z
updated: 2024-08-17T00:41:55.064Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Winget: A Guide for Windows 11 Users"
excerpt: "This Article Describes Reviving Winget: A Guide for Windows 11 Users"
keywords: Windows 11 Winget,Reviving Winget,Winget Tips,Update Winget,Windows 11 Tooling,New Winget Guide,Enhance Winget Usage
thumbnail: https://thmb.techidaily.com/93116893fd34c4239c7adfcfb1ed2eb9afdd0b3ec4eb0ecc53392c491facd138.png
---

## Reviving Winget: A Guide for Windows 11 Users

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
4. Click on the **OK** button. Restart your PC.
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-navigating-youtube-strikes-understanding-and-resolving-copyright-issues/"><u>[New] 2024 Approved  Navigating YouTube Strikes  Understanding and Resolving Copyright Issues</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-steps-for-recording-captivate-videos/"><u>[New] Essential Steps for Recording Captivate Videos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-get-top-quality-gifs-on-your-mac-instantly-for-2024/"><u>[New] Get Top-Quality GIFs on Your Mac Instantly for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-rise-to-stardom-on-instagram-adopting-tiktoks-winning-strategies/"><u>[New] In 2024, Rise to Stardom on Instagram  Adopting TikTok's Winning Strategies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-meme-magic-for-laughter/"><u>[New] Mastering Meme Magic for Laughter</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-high-speed-replicas-best-racing-games/"><u>[Updated] In 2024, High-Speed Replicas  Best Racing Games</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-achieve-marketing-excellence-the-top-10-steps-to-mastering-smm/"><u>2024 Approved  Achieve Marketing Excellence  The Top 10 Steps to Mastering SMM</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-comparing-streamlabs-with-obs-for-professional-broadcasts/"><u>2024 Approved  Comparing Streamlabs with OBS for Professional Broadcasts</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-navigating-the-world-of-windows-11s-in-built-high-dynamic-range-feature/"><u>2024 Approved  Navigating the World of Windows 11'S In-Built High Dynamic Range Feature</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/apple-watch-series-9-versus-fitbit-charge-6-a-comprehensive-showdown/"><u>Apple Watch Series 9 Versus Fitbit Charge 6: A Comprehensive Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-security-patches/"><u>Demystifying Windows Security Patches</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-approach-nullifying-onedrive-presence-on-explore/"><u>Efficient Approach: Nullifying OneDrive Presence on Explore</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-navigation-in-files-windows-11s-tab-system/"><u>Effortless Navigation in Files: Windows 11'S Tab System</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-real-time-performance-of-yuzu-emulator/"><u>Enhance Real-Time Performance of Yuzu Emulator</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-winning-video-coders-for-editing/"><u>Expert Tips: Winning Video Coders for Editing</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-poco-m6-pro-5g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Poco M6 Pro 5G?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-iphone-xr-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your iPhone XR Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-v27e-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo V27e</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-on-apple-iphone-13-mini-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock On Apple iPhone 13 mini? How to Fix it?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-horizon-capture-setup-vr/"><u>In 2024, Horizon Capture Setup VR</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-vivo-y78plus-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Vivo Y78+ Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-14-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi 14 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pot-player-review/"><u>In 2024, POT Player Review</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-your-content-youtube-to-dailymotion-shift/"><u>In 2024, Streamline Your Content  YouTube to Dailymotion Shift</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-top-rated-switch-capture-cards-revealed/"><u>In 2024, Top-Rated Switch Capture Cards Revealed</u></a></li>
<li><a href="https://extra-information.techidaily.com/leading-choices-no-fee-versatile-live-streaming-tools-for-every-device/"><u>Leading Choices  No-Fee, Versatile Live Streaming Tools for Every Device</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-adobe-premiere-pro-2023-import-organize-and-export-your-video-projects-like-a-pro/"><u>New In 2024, Adobe Premiere Pro 2023 Import, Organize, and Export Your Video Projects Like a Pro</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cross-device-use-harnessing-the-power-of-dex/"><u>Optimizing Cross-Device Use: Harnessing the Power of DeX</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-the-account-lockout-threshold-post-failed-attempts-win-11/"><u>Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-systemtray-to-showcase-number-keys/"><u>Personalizing SystemTray to Showcase Number Keys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-opening-mouse-properties-in-win11/"><u>Quick and Easy: Opening Mouse Properties in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-file-updates-on-windows-error-code-0x80070003/"><u>Quick Fix for Missing File Updates on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-error-262-in-roblox-games/"><u>Quick-Fix Strategies for Error 262 in Roblox Games</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-found-rockalldlldll-on-windows/"><u>Rectifying 'Not Found' Rockalldll.dll on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-onedrive-access-issue-in-windows-os-quickly/"><u>Resolve OneDrive Access Issue in Windows OS Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-windows-camera-loss-of-media/"><u>Strategies to Combat Windows Camera Loss of Media</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-failed-task-execution-in-windows-with-error-0x8007000f/"><u>Tackling Failed Task Execution in Windows with Error 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-shortcuts-for-rapid-insertion-of-pre-defined-text-snippets/"><u>Tailored Shortcuts for Rapid Insertion of Pre-Defined Text Snippets</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-for-resolving-widespread-rainmeter-challenges/"><u>The Ultimate Guide for Resolving Widespread Rainmeter Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/transform-data-handling-visual-analyzer-for-disk-storage-on-windows/"><u>Transform Data Handling: Visual Analyzer for Disk Storage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-dealing-with-unyielding-power-controls-in-windows-11/"><u>Tricks for Dealing with Unyielding Power Controls in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-windows-11s-subdued-bar-scanner/"><u>Unearthing Windows 11'S Subdued Bar Scanner</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11-sefx-archive-techniques/"><u>Unlocking Win11 SEFx Archive Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/visualizing-data-footprint-in-windows-os/"><u>Visualizing Data Footprint in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-control-panel-customizing-made-simple/"><u>Win11's Control Panel: Customizing Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10s-best-encryption-software-compared-153-chars/"><u>Windows 10'S Best Encryption Software, Compared (153 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-explore-these-8-great-video-editors/"><u>Windows Users, Explore These 8 Great Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/your-way-your-window-customize-windows-11-today/"><u>Your Way, Your Window: Customize Windows 11 Today</u></a></li>
</ul></div>
