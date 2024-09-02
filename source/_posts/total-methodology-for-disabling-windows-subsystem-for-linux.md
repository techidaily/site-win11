---
title: Total Methodology for Disabling Windows Subsystem for Linux
date: 2024-09-01T04:39:01.791Z
updated: 2024-09-02T04:39:01.791Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Total Methodology for Disabling Windows Subsystem for Linux
excerpt: This Article Describes Total Methodology for Disabling Windows Subsystem for Linux
keywords: Disable WSL (Windows Subsystem),Turn Off Windows Subsystem for Linux,Stop Windows Subsystem Functionality,Cease WSL Operations in Windows,Inhibit Linux Subsystem on Windows OS,End Windows Subsystem Service,Terminate WSL Activation Windows-Wise
thumbnail: https://thmb.techidaily.com/ea90287aad1128dcf73001caefa47ec3f1c16bb10f0ed6607a3b7c4f98575dff.jpg
---

## Total Methodology for Disabling Windows Subsystem for Linux

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-unique-thumbnails-for-youtube-content/"><u>[New] 2024 Approved  Crafting Unique Thumbnails for YouTube Content</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instantaneously-ingesting-imagery-google-collage-basics/"><u>[New] Instantaneously Ingesting Imagery  Google Collage Basics</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nlock-premium-image-quality-through-youtubes-av1-settings-for-2024/"><u>[New] Unlock Premium Image Quality Through YouTube's AV1 Settings for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-android-video-brilliance-easy-procedures/"><u>[New] Unlocking Android Video Brilliance - Easy Procedures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-year-of-unboxing-the-worlds-hottest-yt-channels-listed/"><u>[Updated] 2024 Approved  Year of Unboxing  The World’s Hottest YT Channels Listed</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-academic-history-lovers-guide-to-top-yt-content-for-2024/"><u>[Updated] Academic History Lovers' Guide to Top YT Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-capture-clarity-high-quality-screen-recordings-for-youtubers-pcmac/"><u>[Updated] In 2024, Capture Clarity  High-Quality Screen Recordings for YouTubers (PC/Mac)</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-mastering-mobile-technology-for-dji-visual-storytelling/"><u>[Updated] In 2024, Mastering Mobile Technology for DJi Visual Storytelling</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-innovators-to-watch-leading-av-and-acoustic-artisans-for-2024/"><u>[Updated] Innovators to Watch  Leading Av & Acoustic Artisans for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-peering-through-the-lens-an-in-depth-review-of-polaroid-cubeplus/"><u>[Updated] Peering Through the Lens  An In-Depth Review of Polaroid Cube+</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/best-camcorder-tech-for-shooting-sports-for-2024/"><u>Best Camcorder Tech for Shooting Sports for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-error-code-0xc00000f-in-windows/"><u>Deciphering and Resolving Error Code 0xC00000F in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-the-social-scene-expat-groups-on-facebook/"><u>Decoding the Social Scene: Expat Groups on Facebook</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dissecting-the-dynamics-of-aurora-high-quality-outputs/"><u>Dissecting the Dynamics of Aurora High-Quality Outputs</u></a></li>
<li><a href="https://win11.techidaily.com/ease-into-windows-11-troubleshooting-update-issue-0x30017/"><u>Ease Into Windows 11: Troubleshooting Update Issue #0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/easing-expiry-headache-fixing-windows-license-alarms/"><u>Easing Expiry Headache: Fixing Windows License Alarms</u></a></li>
<li><a href="https://win-amazing.techidaily.com/expert-tips-and-tricks-upgrading-your-use-of-seagate-backup-plus-in-the-new-year/"><u>Expert Tips and Tricks: Upgrading Your Use of Seagate Backup Plus in the New Year</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-best-of-linux-ditch-wsl/"><u>Get the Best of Linux - Ditch WSL</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-most-out-of-windows-11-essential-settings-for-upgraded-speed/"><u>Get the Most Out of Windows 11: Essential Settings for Upgraded Speed</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-conceal-dim-display-feature-in-win-os-control-panel/"><u>Guide to Conceal Dim Display Feature in Win OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-random-console-window-flashes/"><u>How to Prevent Random Console Window Flashes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-15-pro-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone 15 Pro Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-x100-pro-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo X100 Pro Is Unlocked</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-handle-previewed-activities-on-facebook/"><u>In 2024, How to Handle Previewed Activities on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-tasks-with-these-excellent-8-windows-timer-apps/"><u>Master Your Tasks with These Excellent 8 Windows Timer Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-minecrafts-geometric-forms-circular-and-spherical-creation/"><u>Mastering Minecraft's Geometric Forms  Circular & Spherical Creation</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-visual-smoothness-with-custom-variable-refresh-rate-on-series-console/"><u>Mastering Visual Smoothness with Custom Variable Refresh Rate on Series Console</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-barriers-on-windows-11/"><u>Overcoming File Access Barriers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-spotify-crash-in-windows-11-without-it-help/"><u>Overcoming Spotify Crash in Windows 11 without IT Help</u></a></li>
<li><a href="https://win11.techidaily.com/premium-choices-top-windows-platforms-for-dsswitch-experience/"><u>Premium Choices: Top Windows Platforms for DS/Switch Experience</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/proven-techniques-to-store-your-mov-videos-on-windows-10/"><u>Proven Techniques to Store Your .mov Videos on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/quantifying-storage-quotient-for-windows-programs/"><u>Quantifying Storage Quotient for Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-stopping-windows-11-from-running/"><u>Quick Fixes: Stopping Windows 11 From Running</u></a></li>
<li><a href="https://win11.techidaily.com/rediscover-lost-control-panel-configurations-in-win11/"><u>Rediscover Lost Control Panel Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-vintage-windows-pcs-for-elders/"><u>Reimagining Vintage Windows PCs for Elders</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-non-existent-camera-issue-in-windows-device-hub/"><u>Resolve Non-Existent Camera Issue in Windows Device Hub</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steams-unavailable-content-servers-issue-on-pc/"><u>Resolving Steam's Unavailable Content Servers Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/separating-the-sincere-from-the-spoof-in-the-windows-store/"><u>Separating the Sincere From the Spoof in the Windows Store</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-eliminate-autominimize-effects/"><u>Streamlining Windows: Eliminate AutoMinimize Effects</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-clock-and-dates-windows-1011-guide/"><u>Tailor Your Clock and Dates: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-mind-maps-organizing-notes-using-obsidian-canvas/"><u>The Art of Mind Maps: Organizing Notes Using Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-for-efficient-browsing-ram-friendly-windows-applications-ranked/"><u>The Quest for Efficient Browsing: RAM-Friendly Windows Applications Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-22h2-moment-update-could-bring-7-exciting-features/"><u>The Windows 11 22H2 Moment Update Could Bring 7 Exciting Features</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/top-eight-collections-for-graffiti-letters/"><u>Top Eight Collections for Graffiti Letters</u></a></li>
<li><a href="https://win11.techidaily.com/track-down-and-fix-gone-data-devices-on-pc/"><u>Track Down and Fix Gone Data Devices on PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-guide-how-to-fix-unresponsive-computer-audio-devices/"><u>Ultimate Guide: How to Fix Unresponsive Computer Audio Devices</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-your-win11-status-key-indicators-and-checks-for-uptime/"><u>Understanding Your Win11 Status: Key Indicators and Checks for Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-code-mastery-reclaiming-your-windows-1011-key/"><u>Unlock Code Mastery: Reclaiming Your Windows 10/11 Key</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-webcam-visibility-alerts-in-win11/"><u>Unlocking Webcam Visibility Alerts in Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-wevideo-your-go-to-platform-for-online-video-editing/"><u>Updated WeVideo Your Go-To Platform for Online Video Editing</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/worldwide-films-that-elevate-language-mastery/"><u>Worldwide Films That Elevate Language Mastery</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>