---
title: Instructions for Completely Getting Rid of WSL on Win 11
date: 2024-08-15T23:29:05.711Z
updated: 2024-08-16T23:29:05.711Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instructions for Completely Getting Rid of WSL on Win 11
excerpt: This Article Describes Instructions for Completely Getting Rid of WSL on Win 11
keywords: WSL Removal Guide,Windows 11 WSL Uninstall,Remove WSL From Win 11,How to Delete WSL Windows,Win 11 Disable WSL,Eliminate WSL on Win 11,Uninstall WSL Windows 11
thumbnail: https://thmb.techidaily.com/c16b1e731514b90b733ef5726536377276b9f0da4bb0ae7f591c4a5f178d3c77.jpg
---

## Instructions for Completely Getting Rid of WSL on Win 11

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-solving-sync-issues-between-cameras-and-obs/"><u>[New] 2024 Approved  Solving Sync Issues Between Cameras and OBS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-go-live-on-facebook/"><u>[New] How to Go Live on Facebook?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-seamless-integration-making-your-youtube-videos-available-on-facebook/"><u>[New] In 2024, Seamless Integration  Making Your YouTube Videos Available on Facebook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-streamline-your-thumbnail-design-journey-today/"><u>[New] Streamline Your Thumbnail Design Journey Today!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-reign-supreme-with-these-ultimate-10-innovative-ideas-for-igtv-video-content/"><u>[Updated] Reign Supreme with These Ultimate 10 Innovative Ideas for IGTV Video Content</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-13-mini-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 13 mini for Free</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-hdr-visualization-with-windows-11/"><u>Dive Deep Into HDR Visualization with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-ways-to-restore-your-dvdcd-rom-hardware-device-on-windows-11-understanding-and-fixing-configuration-error-code-19/"><u>Effective Ways to Restore Your DVD/CD-ROM Hardware Device on Windows 11: Understanding and Fixing Configuration Error (Code 19)</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-connection-issue-on-windows-os/"><u>Fixing No Connection Issue on Windows OS</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722988010055-gta-5-freezing-problems-discover-effective-fixes-and-get-back-to-high-octane-action/"><u>GTA 5 Freezing Problems? Discover Effective Fixes and Get Back to High-Octane Action</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/installation-triumph-fixed-mspm-in-windows-10/"><u>Installation Triumph: Fixed MSPM in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-s17t-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo S17t Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlock-creative-potential-top-methods-for-green-screen-filming-for-2024/"><u>Unlock Creative Potential  Top Methods for Green Screen Filming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-free-software-optimal-and-safe-options/"><u>Win-Friendly Free Software: Optimal and Safe Options</u></a></li>
<li><a href="https://win11.techidaily.com/wsl-contribution-to-linux-user-growth/"><u>WSL Contribution to Linux User Growth</u></a></li>
</ul></div>
