---
title: Mitigating Unsupported Windows Package Install Errors
date: 2024-11-05T18:55:32.836Z
updated: 2024-11-07T19:54:14.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating Unsupported Windows Package Install Errors
excerpt: This Article Describes Mitigating Unsupported Windows Package Install Errors
keywords: Fix Windows Installs,Resolve Install Issues,Overcome Package Errors,Stop Uninstall Failures,Address Windows Install Flaws,Correct Pack Installation,Prevent OS Update Errors
thumbnail: https://thmb.techidaily.com/9878ff62b08356ff78ffb4d4ce5fd0c27ab1ffdc4dd530f388b0fa3845feed6f.jpg
---

## Mitigating Unsupported Windows Package Install Errors

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.

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
<li><a href="https://eaxpv-info.techidaily.com/updated-from-template-to-trendsetter-gamer-channel-banners-guide-for-2024/"><u>[Updated] From Template to Trendsetter Gamer Channel Banners Guide for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-unleash-your-adventure-with-panasonics-cutting-edge-hx-a1-cam-for-2024/"><u>[Updated] Unleash Your Adventure with Panasonic's Cutting-Edge HX-A1 Cam for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-optimal-practices-for-archiving-interactive-online-workshops/"><u>2024 Approved Optimal Practices for Archiving Interactive Online Workshops</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-win-error-messages-your-step-by-step-solution/"><u>Decoding Win Error Messages - Your Step-by-Step Solution</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/elevate-your-business-acumen-with-essential-ai-innovations/"><u>Elevate Your Business Acumen with Essential AI Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-system-installation-guide-for-pc-manager-w11/"><u>Elevate Your System - Installation Guide for PC Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-clearing-printer-connection-errors/"><u>Expert Guide to Clearing Printer Connection Errors</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/garmins-vivomove-hr-smartwatch-reviewed-the-sleekest-wearable-for-daily-fitness-routines/"><u>Garmin's Vivomove HR Smartwatch Reviewed: The Sleekest Wearable for Daily Fitness Routines</u></a></li>
<li><a href="https://win-forum.techidaily.com/harnessing-the-power-of-major-social-channels-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Harnessing the Power of Major Social Channels: A Guide to Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-random-opens-in-microsoft-shop-app/"><u>How to Stop Random Opens in Microsoft Shop App</u></a></li>
<li><a href="https://win-trending.techidaily.com/how-to-switch-your-flipbuilder-apps-interface-from-english-to-your-local-language/"><u>How to Switch Your FlipBuilder App's Interface From English to Your Local Language</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do I Stop Someone From Tracking My Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-14-plus-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone 14 Plus?</u></a></li>
<li><a href="https://win11.techidaily.com/leap-from-batch-processing-to-executables-in-windows/"><u>Leap From Batch Processing to Executables in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mastering-bokeh-the-best-mobile-apps-for-ios-and-android-photographers-for-2024/"><u>Mastering Bokeh The Best Mobile Apps for iOS and Android Photographers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/migrating-user-defined-powertoys-settings/"><u>Migrating User-Defined PowerToys Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-utorrent-installation-failures-in-windows-108/"><u>Mitigating uTorrent Installation Failures in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-each-window-11-screen-with-distinct-wallpapers/"><u>Personalize Each Window 11 Screen with Distinct Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-service-not-responding-error-in-windows/"><u>Steps to Overcome Service Not Responding Error in Windows</u></a></li>
</ul></div>

