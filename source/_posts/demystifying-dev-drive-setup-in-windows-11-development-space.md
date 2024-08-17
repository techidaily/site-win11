---
title: Demystifying Dev Drive Setup in Windows 11 Development Space
date: 2024-08-15T23:31:20.831Z
updated: 2024-08-16T23:31:20.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Dev Drive Setup in Windows 11 Development Space
excerpt: This Article Describes Demystifying Dev Drive Setup in Windows 11 Development Space
keywords: Win11 Dev Setup Guide,Dev Drive Config Steps,Windows 11 Developer Kit,Unveiling DevDrive,Windows 11 Development Space,Setting up DevDrive,W11 SDK Configuration
thumbnail: https://thmb.techidaily.com/92ce41ef8b05767b09e5cccf1de47f0c1a1c9c1b0cd1ef1d90d54872beba93f1.jpg
---

## Demystifying Dev Drive Setup in Windows 11 Development Space

 Microsoft initially announced Dev Drive as a part of Build 2023\. During the event, the Redmond giant unveiled Dev Home and Dev Drive to improve developer productivity and performance. Dev Drive is a new specialized storage volume that significantly boosts security and efficiency for key developer workloads.

 Read on as we explain what Dev Drive is and how developers can get started with it.

## What Is Dev Home and the Dev Drive on Windows 11?

[Dev Home](https://www.makeuseof.com/dev-home-windows-11-introduction/) is the control center that simplifies typical developer workflows on Windows 11\. It’s aimed to help users boost their productivity and performance by allowing developers to focus more on the development itself rather than worrying about the dev environment. It was announced alongside Dev Drive on the [Windows Developer Blog](https://blogs.windows.com/windowsdeveloper/2023/05/23/bringing-the-power-of-ai-to-windows-11-unlocking-a-new-era-of-productivity-for-customers-and-developers-with-windows-copilot-and-dev-home/) in May 2023\.

 Dev Home can help developers ensure the project is set up correctly without stressing over package and dependency issues. The newly announced control center has several essential features, such as enhanced GitHub integration, customized widgets for your dashboard, and a new storage volume–the Dev Drive.

 As a developer using Dev Home, you no longer need to constantly switch between different apps, navigate to the relevant file system directories repeatedly, and juggle multiple sign-in identities to get the job done.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## How to Use Dev Drive on Windows 11

 At the time of writing, Dev Drive is in preview to Windows Insiders only. If you’re on the Dev Channel of the Windows Insider Program, you can immediately start using Dev Drive on Windows 11\. Otherwise, you’ll have to wait for Microsoft to ship Dev Drive with the next major Windows 11 update.

 Microsoft also requires at least 50GB of available storage and at least 8GB of RAM (although Microsoft recommends 16GB for optimum performance).

 There are three main setup options for creating a Dev Drive. You can create the volume on a new [virtual hard disk (VHD)](https://www.makeuseof.com/what-is-a-vhd-virtual-hard-drive-file/) or a new volume from your existing storage disk. If you already have an unallocated volume on your disk, you can also use that to create a Dev Drive.

 For the purpose of this guide, we’re going to focus on resizing our existing disk to create the Dev Drive. To create a new Dev Drive volume on Windows 11:

1. Navigate to **Settings > Storage > Advanced Storage Settings > Disks & volumes**, and select **Create Dev Drive**. Alternatively, you can also launch **Dev Home** and choose **Create Dev Drive**.  
![create dev drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/dev-drive-create-1.jpg)  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Image Credit: [Microsoft](https://learn.microsoft.com/en-us/windows/dev-drive/)
2. Select **Resize an existing volume** and choose the volume you want to split to make space for a new Dev Drive. You’ll need to ensure the volume you select has at least 50GB of available storage (the minimum capacity of a Dev Drive) and click on **Next**.  
![dev drive choose location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/dev-drive-choose-location-1.jpg)  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Image Credit: [Microsoft](https://learn.microsoft.com/en-us/windows/dev-drive/)
3. When asked to enter the size of your new volume, enter the required size based on your project requirements and click on **Next**.  
![new drive drive size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/dev-drive-new-1.jpg)  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Image Credit: [Microsoft](https://learn.microsoft.com/en-us/windows/dev-drive/)
4. You now need to give the Dev Drive volume a label and a drive letter. Once again, also enter the size you want to allocate to the newly created Dev Drive. Finally, click on **Format** to finish setting up your Dev Drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## What Should You Use Dev Drive For?

 Microsoft recommends using Dev Drive to store source code repositories, project files, package caches, and the required build files. You shouldn’t use Dev Drive to install IDEs or dev tools such as Visual Studio, Windows SDKs, etc. Microsoft recommends housing these tools on your primary drive.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Your Dream Developer PC With Windows 11

 With the comvbination of Dev Home and Dev Drive, Windows 11 is a powerful tool for developers. Now you know what Dev Drive is and how it works.

 Read on as we explain what Dev Drive is and how developers can get started with it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-streamlining-your-mac-5-best-screen-shot-approaches/"><u>[New] 2024 Approved  Streamlining Your Mac  5 Best Screen Shot Approaches</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-minimizing-film-length-mac-solutions-for-instagram-posting-for-2024/"><u>[New] Minimizing Film Length  Mac Solutions for Instagram Posting for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-stream-your-podcast-with-one-move-only/"><u>[New] Stream Your Podcast with One Move Only</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-speed-demons-win-10-and-11-internet-takedown/"><u>[SOLVED] Speed Demons: WIN 10 & 11 Internet Takedown</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-behind-the-scenes-of-lol-top-3-broadcast-techniques-for-2024/"><u>[Updated] Behind the Scenes of LOL - Top 3 Broadcast Techniques for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-masterful-nintendo-switch-fighting-game-collection-max-156/"><u>[Updated] In 2024, Masterful Nintendo Switch Fighting Game Collection (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-windows-platform-bittorrent-apps/"><u>5 Superior Windows Platform BitTorrent Apps</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-on-using-w11s-automated-hdr-feature/"><u>A Complete Guide on Using W11's Automated HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-roadmap-to-your-computers-heart-mouse-prop/"><u>A Step-by-Step Roadmap to Your Computer's Heart - Mouse Prop</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-typing-mastering-windows-powertoys/"><u>Accelerate Typing: Mastering Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-files-in-steam-library/"><u>Addressing Disconnected Files in Steam Library</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-30015-26-in-m365-software-for-pcs/"><u>Addressing Error Code 30015-26 in M365 Software for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-mfc71udll-disappearance-on-pcs/"><u>Addressing Mfc71u.dll Disappearance on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-password-recall-issue-on-w10w11/"><u>Addressing the “Password Recall Issue on W10/W11”</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-update-problem-code-0x8024800c/"><u>Addressing Windows Update Problem: Code 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-isolating-subjects-in-photography/"><u>Advanced Tips for Isolating Subjects in Photography</u></a></li>
<li><a href="https://win11.techidaily.com/averting-the-def5-blunder-in-onedrive-w11-issues/"><u>Averting the Def5 Blunder in OneDrive W11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unauthorized-user-error-on-windows-11-and-11/"><u>Avoiding Unauthorized User Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-flickering-screens-a-windows-11-guide/"><u>Banish Flickering Screens: A Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-zoom-crashes-windows-error-1132-fix/"><u>Banishing Zoom Crashes: Windows Error 1132 Fix</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/become-the-star-with-your-own-stories-guidelines-for-crafting-over-120-creative-snap-tales/"><u>Become the Star with Your Own Stories  Guidelines for Crafting over 120 Creative Snap Tales</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-kid-approved-drones-for-beginning-pilots/"><u>Best Kid-Approved Drones for Beginning Pilots</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-minipc-storage-space-speeds-still-sparse/"><u>Blackview MiniPC: Storage Space - Speeds Still Sparse</u></a></li>
<li><a href="https://win11.techidaily.com/blending-email-services-adding-gmail-to-the-outlook-app-in-windows/"><u>Blending Email Services: Adding Gmail to the Outlook App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boost-note-visibility-for-effective-productivity/"><u>Boost Note Visibility for Effective Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/boot-security-errors-squashed-in-5-easy-steps-for-windows-users/"><u>Boot Security Errors Squashed in 5 Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bound-windows-login-with-ms-account-essentials/"><u>Bound Windows Login with MS Account Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-essential-steps-to-game-folder-opening/"><u>Break the Code: Essential Steps to Game Folder Opening</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-adjusting-immovable-gif-sizes-for-windows-users-of-discord/"><u>Breaking Free: Adjusting Immovable GIF Sizes for Windows Users of Discord</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://win-blog.techidaily.com/combat-game-lag-boost-frame-rates-and-eliminate-stutters-in-splitgate/"><u>Combat Game Lag - Boost Frame Rates & Eliminate Stutters in Splitgate</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-audio-identity-the-art-of-adding-your-own-tones-to-android-for-2024/"><u>Crafting Audio Identity  The Art of Adding Your Own Tones to Android for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-latest-nvidia-graphics-drivers-compatible-with-windows-10-7-and-8/"><u>Download the Latest Nvidia Graphics Drivers: Compatible with Windows 10, 7 & 8</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-for-lowering-god-of-war-games-cpu-demand/"><u>Effective Solutions for Lowering God of War Game's CPU Demand</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-setup-hp-officejet-pro-8710-windows-printer-drivers-available-here/"><u>Effortless Setup: HP OfficeJet Pro 8710 Windows Printer Drivers Available Here</u></a></li>
<li><a href="https://win11.techidaily.com/1719362972502-enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today!</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-tecno-camon-20-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-a-broken-facial-recognition-top-14-tips-for-reactivating-iphones-face-id/"><u>Fixing a Broken Facial Recognition: Top 14 Tips for Reactivating iPhone's Face ID</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-xiaomi-redmi-note-12-pro-5g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Xiaomi Redmi Note 12 Pro 5G?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-install-and-update-linksys-ea9700-drivers-a-step-by-step-tutorial/"><u>How to Install and Update Linksys EA9700 Drivers: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-docx-document-with-electronic-digital-signature-tutorial-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign .docx document with Electronic Digital Signature - (Tutorial)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-samsung-galaxy-s23-tactical-edition-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Samsung Galaxy S23 Tactical Edition Phone Password Using Emergency Call</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovate-impress-and-captivate-in-solo-podcasting/"><u>In 2024, Innovate, Impress, and Captivate in Solo Podcasting</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-oppo-reno-11f-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Oppo Reno 11F 5G</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-5-best-free-wmv-video-editors/"><u>New In 2024, Top 5 Best Free WMV Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/1719218034374-provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships</u></a></li>
<li><a href="https://win11.techidaily.com/1719224494525-revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/silent-infinity-cuda-diagnosed/"><u>Silent Infinity CUDA Diagnosed</u></a></li>
<li><a href="https://win11.techidaily.com/1719350686194-unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues</u></a></li>
</ul></div>
