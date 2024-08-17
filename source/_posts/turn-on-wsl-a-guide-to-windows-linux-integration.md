---
title: "Turn on WSL: A Guide to Windows' Linux Integration"
date: 2024-08-15T23:43:19.932Z
updated: 2024-08-16T23:43:19.932Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Turn on WSL: A Guide to Windows' Linux Integration"
excerpt: "This Article Describes Turn on WSL: A Guide to Windows' Linux Integration"
keywords: Windows WSL,Linux WSL,Turning WSL On,Linux on WSLEnv,Enable Linux Bash,Windows Integrated Linux,Start Windows Linux
thumbnail: https://thmb.techidaily.com/c614df743851cde902b9dc7b624e356646f565efb6b83602d7f5ffd347873428.jpg
---

## Turn on WSL: A Guide to Windows' Linux Integration

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-accelerating-vimeo-content-streams/"><u>[New] In 2024, Accelerating Vimeo Content Streams</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-reclaim-the-loss-10-essential-iphone-x-techniques-for-2024/"><u>[New] Reclaim The Loss  10 Essential iPhone X Techniques for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-ancestral-aesthetics-art-without-restrictive-rights-for-2024/"><u>[Updated] Ancestral Aesthetics  Art Without Restrictive Rights for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-cross-platform-video-tutorial-twitter-to-instagram/"><u>[Updated] Cross-Platform Video Tutorial  Twitter to Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-expert-tips-on-seamless-multisnapping-videos-in-snapchat/"><u>[Updated] Expert Tips on Seamless Multisnapping Videos in Snapchat</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-visibility-on-youtube-the-ultimate-guide-to-featured-channel-placement/"><u>[Updated] In 2024, Crafting Visibility on YouTube  The Ultimate Guide to Featured Channel Placement</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-get-people-to-subscribe-by-asking-the-right-way/"><u>[Updated] In 2024, How to Get People to Subscribe by Asking the Right Way</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-mastering-the-art-of-using-cc-copyrights-wisely/"><u>[Updated] In 2024, Mastering the Art of Using CC Copyrights Wisely</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-honor-80-pro-straight-screen-edition-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Honor 80 Pro Straight Screen Edition to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-achieving-seamless-group-discussions-in-google-chat/"><u>2024 Approved  Achieving Seamless Group Discussions in Google Chat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-high-performance-windows-editing-tools-roundup-reviewed/"><u>2024 Approved  High Performance Windows Editing Tools Roundup Reviewed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-maximizing-earnings-on-snapchat-platforms/"><u>2024 Approved  Maximizing Earnings on Snapchat Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-step-by-step-guide-mastering-ez-grabber/"><u>2024 Approved  Step-by-Step Guide  Mastering EZ Grabber</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-prevent-unauthorized-access-on-windows/"><u>7 Ways to Prevent Unauthorized Access on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-deep-examination-of-androids-photo-editing-tool-lightroom/"><u>A Deep Examination of Android's Photo Editing Tool, Lightroom</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-windows-lockscreen-for-user-preferences/"><u>Adapting Windows Lockscreen for User Preferences</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-of-the-best-trivia-channels/"><u>Best of the Best  Trivia Channels</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-process-termination-errors-effortlessly/"><u>Bypassing Process Termination Errors Effortlessly</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/capturing-and-crafting-your-essential-guide-to-gopro-4k-edits-for-2024/"><u>Capturing and Crafting  Your Essential Guide to GoPro 4K Edits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unexpected-reference-to-token-in-win10win11/"><u>Correcting Unexpected Reference to Token in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-cloud-file-retrieval-methods/"><u>Cross-Platform Cloud File Retrieval Methods</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-microsoft-edges-heavy-background-tasks/"><u>Curbing Microsoft Edge's Heavy Background Tasks</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/cutting-edge-from-srt-to-subtitle-system/"><u>Cutting Edge From SRT to Subtitle System</u></a></li>
<li><a href="https://win-amazing.techidaily.com/downloadable-pci-card-drivers-compatible-with-various-windows-versions-win11-win10-win8-win7/"><u>Downloadable PCI Card Drivers Compatible with Various Windows Versions (Win11, Win10, Win8, Win7)</u></a></li>
<li><a href="https://win11.techidaily.com/1719347376759-efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7.</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-tecno-pova-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-basic-procedures-for-saving-screen-talks/"><u>In 2024, Basic Procedures for Saving Screen Talks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-branded-content-collaborations-on-streaming-services/"><u>In 2024, Branded Content Collaborations on Streaming Services</u></a></li>
<li><a href="https://win11.techidaily.com/in-a-nutshell-how-to-spot-your-pcs-ram-quickly/"><u>In a Nutshell: How to Spot Your PC's RAM Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://extra-hints.techidaily.com/insta-pros-guide-accelerate-your-path-to-social-media-stardom/"><u>Insta Pro's Guide  Accelerate Your Path to Social Media Stardom</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-activating-windows-recovery-software/"><u>Key Steps for Activating Windows Recovery Software</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users.</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-fixing-audacitys-failed-sound-device-openings-on-win-os/"><u>Methods for Fixing Audacity's Failed Sound Device Openings on Win OS</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondly-collaborates-with-pearson-study-network/"><u>Mondly Collaborates With Pearson Study Network</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-code-0xc00ce556/"><u>Navigating Windows Error Code: 0XC00CE556</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-cutting-edge-4k-video-editing-software-and-beyond/"><u>New In 2024, Cutting-Edge 4K Video Editing Software and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/nine-best-window-timers-enhancing-pomodoro-productivity/"><u>Nine Best Window Timers Enhancing Pomodoro Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-devices-aesthetics-using-microsoft-store-themes/"><u>Optimizing Your Device's Aesthetics Using Microsoft Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/passfab-iphone-15-plus-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>PassFab iPhone 15 Plus Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pc-revival-unearthing-windows-best-eight-methods/"><u>Quick PC Revival: Unearthing Windows' Best Eight Methods</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-detection-of-razer-devices-by-synapse-software/"><u>Reinstating Detection of Razer Devices by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise:</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://facebook.techidaily.com/seeking-truth-in-hate-for-global-network-engagement-tools/"><u>Seeking Truth in Hate for Global Network Engagement Tools</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-11-from-self-restarting-frequently/"><u>Stop Windows 11 From Self-Restarting Frequently</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-repeated-edge-desktop-additions/"><u>Stopping Repeated Edge Desktop Additions</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-revive-windows-11s-essential-directories/"><u>Tailored Guide to Revive Windows 11'S Essential Directories</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-swift-solutions-for-adding-a-folder-to-onedrive-successfully/"><u>Troubleshooting Guide: Swift Solutions for Adding a Folder to OneDrive Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-chrome-profile-errors-for-windows-users/"><u>Unraveling Chrome Profile Errors for Windows Users</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-fcpx-plugin-problems-heres-how-to-get-them-working-again/"><u>Updated In 2024, FCPX Plugin Problems? Heres How to Get Them Working Again</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-a-runtime-broker-unpacking-its-importance-for-pcs/"><u>What Is a Runtime Broker? Unpacking Its Importance for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-original-icon-placement/"><u>Winning Back Original Icon Placement</u></a></li>
</ul></div>
