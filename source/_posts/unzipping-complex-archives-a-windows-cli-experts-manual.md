---
title: "Unzipping Complex Archives: A Windows CLI Expert's Manual"
date: 2024-08-15T23:33:48.305Z
updated: 2024-08-16T23:33:48.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unzipping Complex Archives: A Windows CLI Expert's Manual"
excerpt: "This Article Describes Unzipping Complex Archives: A Windows CLI Expert's Manual"
keywords: Unzip Windows Files,CLI Archive Handling,Zipping Windows Utilities,Command Line Data Extraction,Advanced File Compression,Windows CLI Archival Guide,Mastering Archive Management
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Unzipping Complex Archives: A Windows CLI Expert's Manual

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
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
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhance-videos-naturally-free-9-youtube-thumbnail-crafting-tips/"><u>[New] 2024 Approved  Enhance Videos Naturally - Free 9 YouTube Thumbnail Crafting Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-secrets-for-hd-streaming-on-the-worlds-largest-social-network/"><u>[New] 2024 Approved  Secrets for HD Streaming on the World's Largest Social Network</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-stock-insights-unleashed-top-15-youtube-experts/"><u>[New] Stock Insights Unleashed  Top 15 YouTube Experts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-integrate-sound-and-sight-web-studio/"><u>[Updated] Integrate Sound & Sight Web Studio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-seamless-audio-transitions-in-audacity/"><u>[Updated] Mastering Seamless Audio Transitions in Audacity</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hairstyles-for-visual-gurus/"><u>2024 Approved  Hairstyles for Visual Gurus</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-practical-steps-for-farewell-in-a-discord-environment/"><u>2024 Approved  Practical Steps for Farewell in a Discord Environment</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-insiders-edge-to-editing-your-look-back-story/"><u>2024 Approved  The Insider's Edge to Editing Your Look Back Story</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-truckers-audio-companion-bluetooth-hearing-device-explored/"><u>Affordable Truckers' Audio Companion: Bluetooth Hearing Device Explored</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-confusion-five-windows-cures-to-unsupported-boots/"><u>Clearing Up the Confusion: Five Windows Cures to Unsupported Boots</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/commanders-conclave-celebrating-the-best-of-7-total-wars-for-2024/"><u>Commanders' Conclave  Celebrating the Best of 7 Total Wars for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elite-screen-grabbers-5-non-windows-counterparts-to-snipping-tool/"><u>Elite Screen Grabbers: 5 Non-Windows Counterparts to Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/enjoy-family-cinema-night-with-these-6-amazing-free-movie-sites-for-kids/"><u>Enjoy Family Cinema Night with These 6 Amazing Free Movie Sites for Kids</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
<li><a href="https://win11.techidaily.com/from-simple-logon-to-strong-authentication-changing-your-windows-11-login-habit/"><u>From Simple Logon to Strong Authentication: Changing Your Windows 11 Login Habit</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-restore-cellular-data-functionality-on-your-iphone-top-10-tips/"><u>How to Restore Cellular Data Functionality on Your iPhone: Top 10 Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-poco-c65-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Poco C65</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-13-mini-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 13 mini with IMEI Code?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-video-content-for-budding-vloggers/"><u>In 2024, Innovative Video Content for Budding Vloggers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-quick-clip-creations-role-and-music-tango/"><u>In 2024, Quick Clip Creations  Role & Music Tango</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-viral-cellphone-alert-songs-you-cant-ignore/"><u>In 2024, Viral Cellphone Alert Songs You Cant Ignore</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-delaying-windows-10-shutdown-processes/"><u>Mastering the Art of Delaying Windows 10 Shutdown Processes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-windows-essence-crafting-and-evaluating-system-data/"><u>Peering Into Windows Essence: Crafting & Evaluating System Data</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-video-memory-crashes-in-hogwarts-legacy-windows-edition/"><u>Remedying Video Memory Crashes in 'Hogwarts: Legacy' Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/reorient-your-windows-a-guide-to-90-degree-display-adjustment/"><u>Reorient Your Windows: A Guide to 90-Degree Display Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/skilled-tactics-bypassing-windows-11s-security-measures/"><u>Skilled Tactics: Bypassing Windows 11'S Security Measures</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-mastering-the-setup-of-your-smart-device-with-any-universal-remote/"><u>Step-by-Step Guide: Mastering the Setup of Your Smart Device with Any Universal Remote</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80040610-restoring-smooth-functionality-to-outlook/"><u>Tackling Error 0X80040610: Restoring Smooth Functionality to Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-windows-compatible-webp-viewer-tools/"><u>Top 4 Windows-Compatible WebP Viewer Tools</u></a></li>
<li><a href="https://win11.techidaily.com/transformational-taskbar-update-windows-system-resources-in-view/"><u>Transformational Taskbar Update: Windows System Resources in View</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-or-enable-smartfilter-on-modern-windows-os/"><u>Turn Off or Enable SmartFilter on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-defenders-error-code-0x80004004/"><u>Unveiling Fixes for Defender’s Error Code: 0X80004004</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/weaving-a-web-of-sound-youtube-music-and-video-integration-guide/"><u>Weaving a Web of Sound  YouTube Music & Video Integration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-settings-app-overview/"><u>Windows 11 Settings App Overview</u></a></li>
<li><a href="https://win11.techidaily.com/yourphone-in-windows-98-should-you-exercranize-it/"><u>YourPhone in Windows 9/8: Should You Exercranize It?</u></a></li>
</ul></div>
