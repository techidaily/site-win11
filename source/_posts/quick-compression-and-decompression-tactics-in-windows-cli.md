---
title: Quick Compression & Decompression Tactics in Windows CLI
date: 2024-08-15T23:29:07.795Z
updated: 2024-08-16T23:29:07.795Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Compression & Decompression Tactics in Windows CLI
excerpt: This Article Describes Quick Compression & Decompression Tactics in Windows CLI
keywords: WinCLICompressTips,DecompWinCLI,QuickWinCompDecom,CompDecomTactics,CompressionToolsWin,CLICompressionMethods,WindowsDecompOptions
thumbnail: https://thmb.techidaily.com/8c939daafbcd042f39c237e82182653fc156f3f064bef6cc6988deae36a1c0c9.jpg
---

## Quick Compression & Decompression Tactics in Windows CLI

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
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Zip Files Using Windows PowerShell

 There are several viable ways to [create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-directing-youtube-and-twitter-videos-via-whatsapp-messages/"><u>[New] 2024 Approved  Directing YouTube & Twitter Videos via WhatsApp Messages</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-building-a-compelling-cinematic-snippet/"><u>[New] Building a Compelling Cinematic Snippet</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-essential-tips-to-avoid-obs-framing-errors-for-2024/"><u>[New] Essential Tips to Avoid OBS Framing Errors for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-achieve-financial-success-on-youtube-start-at-500-views/"><u>[New] In 2024, Achieve Financial Success on YouTube  Start at 500 Views</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-digital-video-capturing-for-professionals-stepwise-process/"><u>[New] In 2024, Digital Video Capturing for Professionals - Stepwise Process</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-the-ultimate-srt-resource-for-complete-understanding/"><u>[New] In 2024, The Ultimate SRT Resource for Complete Understanding</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-wirecast-strategies-for-successful-social-media-livestreams/"><u>[New] Wirecast Strategies for Successful Social Media Livestreams</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-screen-recording-made-simple-methodical-guidebook/"><u>[Updated] 2024 Approved  Screen Recording Made Simple  Methodical Guidebook</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-exploring-and-locating-videos-on-facebook-platform-for-2024/"><u>[Updated] Exploring and Locating Videos on Facebook Platform for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-secrets-to-seamless-overwatch-game-captures-unveiled/"><u>[Updated] Secrets to Seamless Overwatch Game Captures Unveiled</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-master-the-conversion-avi-files-become-gifs-using-filmora-software-windowsmac/"><u>2024 Approved  Master the Conversion  AVI Files Become GIFs Using Filmora Software (Windows/Mac)</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-elite-collection-top-10-sites-for-professional-icons/"><u>2024 Approved  The Elite Collection  Top 10 Sites for Professional Icons</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-unveiling-the-secrets-to-efficient-recording/"><u>2024 Approved  Unveiling the Secrets to Efficient Recording</u></a></li>
<li><a href="https://win11.techidaily.com/4-proven-strategies-for-enhancing-window-shot-taking-on-windows-os/"><u>4 Proven Strategies for Enhancing Window Shot Taking on Windows OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/amplify-your-messages-a-guide-to-effective-telegram-advertising-for-2024/"><u>Amplify Your Messages  A Guide to Effective Telegram Advertising for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-fatal-windows-errors-the-0xf0831-guide/"><u>Avoiding Fatal Windows Errors: The 0xF0831 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-dxgierror-windows-devices-reattached/"><u>Combat the DXGI_ERROR: Windows Devices Reattached</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-classics-windows-11s-pathway-to-photos-folder/"><u>Connecting Classics: Windows 11'S Pathway to Photos Folder</u></a></li>
<li><a href="https://tech-revival.techidaily.com/conquer-web-design-complexities-using-gpts-fourfold-methodology/"><u>Conquer Web Design Complexities Using GPT’s Fourfold Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-between-standby-and-complete-shutdown/"><u>Deciding Between Standby and Complete Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-steam-sync-problems/"><u>Deciphering and Fixing Steam Sync Problems</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-pcs-core-generating-and-reviewing-data/"><u>Deciphering Your PC’s Core: Generating & Reviewing Data</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-latest-version-of-toshibas-bluetooth-drivers-for-optimal-device-syncing/"><u>Download the Latest Version of Toshiba’s Bluetooth Drivers for Optimal Device Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-the-past-amplifying-vintage-games-with-shaders/"><u>Echoes of the Past: Amplifying Vintage Games with Shaders</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-colour-mismanagement-issues/"><u>Eliminate Windows Colour Mismanagement Issues</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-cannot-locate-gpeditmsc-windows-problems/"><u>Essential Fixes for Cannot Locate Gpedit.msc Windows Problems</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-into-windows-booting-system-customization/"><u>Expert Insights Into Windows Booting System Customization</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-x-flip-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo X Flip Quickly | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-printer-in-the-os-environment/"><u>Fixing a Non-Functional Printer in the OS Environment</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-iphone-6-plus-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and iPhone 6 Plus The Right Way</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-fatal-glitches-fixing-xbox-game-pass-error-0x00000001-in-windows-11/"><u>How to Eliminate Fatal Glitches: Fixing Xbox Game Pass Error 0X00000001 in Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-oneplus-nord-n30-se-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-files-writable-stop-read-only/"><u>How to Make Windows Files Writable: Stop Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-sleep-state-in-windows-11s-usb-cores/"><u>How to Prevent Sleep State in Windows 11'S USB Cores</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-enhancing-videos-with-camtasias-ken-burns-trick/"><u>In 2024, Enhancing Videos with Camtasia's Ken Burns Trick</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-apple-iphone-xs-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From Apple iPhone XS? Heres the Best Fixes</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-journey-to-the-best-online-shopping-spots-for-enigmatic-boxes/"><u>In 2024, Journey to the Best Online Shopping Spots for Enigmatic Boxes</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-nokia-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Nokia FRP</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-art-of-resetting-a-dell-computer-from-laptops-to-workstations/"><u>Master the Art of Resetting a Dell Computer: From Laptops to Workstations</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mastering-stem-skills-in-depth-look-at-the-makeblock-mbot-programmable-robot-kit-for-enthusiastic-makers/"><u>Mastering STEM Skills: In-Depth Look at the Makeblock MBot Programmable Robot Kit for Enthusiastic Makers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-schedule-with-winning-windows-to-dos/"><u>Mastering Your Schedule with Winning Windows To-Dos</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-mac-os-slideshow-creator-turn-memories-into-stunning-videos-for-2024/"><u>New Mac OS Slideshow Creator Turn Memories Into Stunning Videos for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-blank-window-in-windows-10/"><u>Overcoming Blank Window in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-access-errors-in-windows-environment/"><u>Overcoming Unauthorized Access Errors in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-ui-instability-issues/"><u>Overcoming Windows UI Instability Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-unsynchronized-google-drive-on-pc/"><u>Quick Remedies for Unsynchronized Google Drive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-error-code-0x0000011b/"><u>Resolving Windows 11 Error Code: 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://win11.techidaily.com/secure-uniqueness-5-ways-to-avoid-local-name-clashes-on-windows/"><u>Secure Uniqueness: 5 Ways to Avoid Local Name Clashes on Windows</u></a></li>
<li><a href="https://techidaily.com/solutions-to-open-excel-2019-read-only-documents-stellar-by-stellar-guide/"><u>Solutions to open Excel 2019 Read Only Documents | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/stepwise-guide-to-installing-hp-designjet-g750x-series-print-shop-setup/"><u>Stepwise Guide to Installing HP DesignJet G750X Series Print Shop Setup</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-update-pushes-instantly-with-these-methods/"><u>Stop Windows Update Pushes Instantly With These Methods</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-windows-settings-for-cpu-states/"><u>Tapping Into Windows Settings for CPU States</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/transformative-techniques-to-mute-background-noise/"><u>Transformative Techniques to Mute Background Noise</u></a></li>
<li><a href="https://win11.techidaily.com/why-are-other-processes-aligned-with-edge/"><u>Why Are Other Processes Aligned with Edge?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-changing-picture-preview-size/"><u>Windows 11: Changing Picture Preview Size</u></a></li>
<li><a href="https://win11.techidaily.com/windows-revenue-strategies-for-microsofts-profits/"><u>Windows Revenue Strategies for Microsoft's Profits</u></a></li>
</ul></div>
