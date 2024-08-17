---
title: Simplifying Large Archiving Tasks with Windows PowerShell Tips
date: 2024-08-16T00:24:32.917Z
updated: 2024-08-17T00:24:32.917Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplifying Large Archiving Tasks with Windows PowerShell Tips
excerpt: This Article Describes Simplifying Large Archiving Tasks with Windows PowerShell Tips
keywords: Archive Simplification,PowerShell Tips,Windows Scripting,Data Management,Efficient Storage,System Automation,Large File Handling
thumbnail: https://thmb.techidaily.com/71f657792ad13f84286b1544671aaf8455260b87c02f1f22e6d755ac15543040.jpg
---

## Simplifying Large Archiving Tasks with Windows PowerShell Tips

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## How to Zip Files Using Windows PowerShell

 There are several viable ways to [create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://youtube-data.techidaily.com/024-approved-budget-conscious-filmmakers-essential-video-gear-list/"><u>[New] 2024 Approved  Budget-Conscious Filmmaker's Essential Video Gear List</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-youtube-studio-validating-earnings-flow/"><u>[New] 2024 Approved  YouTube Studio  Validating Earnings Flow</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-engaging-live-streamed-gaming-experiences-for-2024/"><u>[New] Crafting Engaging Live-Streamed Gaming Experiences for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-accelerate-your-retro-play-with-best-ps2-android-emulators/"><u>[Updated] 2024 Approved  Accelerate Your Retro Play with Best Ps2 Android Emulators</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-camera-essentials-for-adventure-videographers/"><u>[Updated] Camera Essentials for Adventure Videographers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-instagram-influencer-blueprint-from-few-to-a-thousand-fans/"><u>[Updated] In 2024, The Instagram Influencer Blueprint  From Few to a Thousand Fans</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-interactive-photography-sharing-immersive-360-photos-via-mobile-devices/"><u>[Updated] Interactive Photography  Sharing Immersive 360 Photos via Mobile Devices</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-no-money-down-best-free-video-chat-platforms-for-2024/"><u>[Updated] No Money Down? Best Free Video Chat Platforms for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-reviewers-guide-to-yuneec-typhoon-h-performance/"><u>[Updated] Reviewer’s Guide to Yuneec Typhoon H Performance</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-six-visionaries-revolutionizing-the-nft-art-scene/"><u>[Updated] Six Visionaries Revolutionizing the NFT Art Scene</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-spectacularly-in-3d-apt-selection-of-top-decks/"><u>[Updated] Spectacularly in 3D  Apt Selection of Top Decks</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-achieve-the-perfect-look-youtubes-guide-to-video-aspect-ratios/"><u>2024 Approved  Achieve the Perfect Look  YouTube's Guide to Video Aspect Ratios</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-composing-captivating-cinema-trailers/"><u>2024 Approved  Composing Captivating Cinema Trailers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-crafting-content-that-captivates-easy-to-try-videos/"><u>2024 Approved  Crafting Content That Captivates  Easy-to-Try Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-top-10-steps-to-youtube-to-mpeg-conversion/"><u>2024 Approved  Top 10 Steps to YouTube-to-MPEG Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-cryptography-tools-for-windows-users-146-chars/"><u>7 Essential Cryptography Tools for Windows Users (146 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/a-handy-guide-to-resolving-windows-filesystem-problems/"><u>A Handy Guide to Resolving Windows Filesystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-overcoming-wwe-2k23-freezes-in-windows/"><u>Accelerated Action: Overcoming WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-valorant-playthrough-with-optimized-pc-settings/"><u>Achieve Peak Valorant Playthrough with Optimized PC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-problems-with-windows-hello-fingerprint-detection/"><u>Addressing Common Problems with Windows Hello Fingerprint Detection</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-headphone-and-speaker-non-detection-in-windows-os/"><u>Addressing Headphone & Speaker Non-Detection in WINDOWS OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inability-to-load-steamui-dll/"><u>Addressing Inability to Load SteamUI DLL</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-configuration-backup-by-nvidia-cp/"><u>Addressing Missing Configuration Backup by Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-gadget-alert-in-windows-11/"><u>Addressing Non-Functional Gadget Alert in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-opengl-failure-code-3-on-win11/"><u>Addressing NVIDIA OpenGL Failure Code 3 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-surge-in-cpu-usage-by-wlanext/"><u>Addressing the Surge in CPU Usage by WLANEXT</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-code-0xca00a009/"><u>Addressing Windows Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-monitor-settings-quickly/"><u>Adjusting Monitor Settings Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-user-management-via-windows-terminal/"><u>Advanced User Management via Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/alter-display-angle-in-windows-settings/"><u>Alter Display Angle in Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-age-old-directx-experience-via-dxvk-compatibility/"><u>Amplifying Age-Old DirectX Experience via DXVK Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-game-access-blocks-fixing-unreachable-errors/"><u>Avoiding Game Access Blocks: Fixing Unreachable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-windows-overload-7-ways-to-fix-too-many-requests-error/"><u>Beating Back Window's Overload: 7 Ways to Fix Too Many Requests Error</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-add-software-icons-to-windows-desktop/"><u>Boost Productivity: Add Software Icons to Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-excels-speed-on-windows-pcs/"><u>Boost Your Excel's Speed on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-protection-expanding-context-menus-for-firewall/"><u>Boosting Windows Protection: Expanding Context Menus for Firewall</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/elevating-vlogging-to-new-heights-yi-hero-reviewed-for-2024/"><u>Elevating Vlogging to New Heights  Yi Hero Reviewed for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-techniques-in-capturing-live-sports-on-camera-for-2024/"><u>Essential Techniques in Capturing Live Sports on Camera for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-itel-a60s-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Itel A60s Phones with/without a PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-how-to-download-vlc-player-for-free-and-safe-on-macstep-by-step/"><u>In 2024, How to Download VLC Player for Free and Safe on Mac?[Step-by-Step]</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcome-window-woes-with-our-guide-troubleshooting-call-of-duty-wwiis-dark-screens/"><u>Overcome Window Woes with Our Guide: Troubleshooting Call of Duty: WWII's Dark Screens</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ess-youtube-experience-on-apple-gear-downloading-made-easy-for-2024/"><u>Seamless Youtube Experience on Apple Gear  Downloading Made Easy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719338015239-team-share-dilemma-heres-the-solution/"><u>Team Share Dilemma? Here's the Solution</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshoot-and-eliminate-persistent-crashes-in-your-steam-applications/"><u>Troubleshoot and Eliminate Persistent Crashes in Your Steam Applications</u></a></li>
<li><a href="https://win-blog.techidaily.com/understanding-and-solving-the-unautnhorized-access-detected-error-in-games/"><u>Understanding & Solving the 'Unautnhorized Access Detected' Error in Games</u></a></li>
<li><a href="https://win11.techidaily.com/1719371064101-windows-11-ready-embrace-google-chrome-now/"><u>Windows 11 Ready? Embrace Google Chrome Now</u></a></li>
</ul></div>
