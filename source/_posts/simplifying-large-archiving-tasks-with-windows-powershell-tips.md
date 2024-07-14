---
title: Simplifying Large Archiving Tasks with Windows PowerShell Tips
date: 2024-07-13T10:10:23.994Z
updated: 2024-07-14T10:10:23.994Z
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

## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

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
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-from-camera-screen-to-insta-story-editing-high-aspect-video-with-fcpx/"><u>[Updated] In 2024, From Camera Screen to Insta Story  Editing High Aspect Video with FCPX</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-magix-music-maker-2024s-features-and-benefits/"><u>[Updated] Exploring Magix Music Maker 2024'S Features & Benefits</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pajama-plots-revisited-critique-and-analysis-for-kids-slumber/"><u>2024 Approved  Pajama Plots Revisited  Critique and Analysis for Kids' Slumber</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-of-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-elite-adventurers-playground-top-10-games-revealed/"><u>In 2024, Elite Adventurers' Playground – Top 10 Games Revealed</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pioneering-applications-in-3d-animation-design-for-2024/"><u>Pioneering Applications in 3D Animation Design for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-win-11-with-nvidia-gtx-970-drivers-update/"><u>Upgrade Win 11 with Nvidia GTX 970 Drivers Update</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-efficiency-strategies-for-effective-multitasking-with-windows-11/"><u>Amplify Efficiency: Strategies for Effective Multitasking with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-quick-hacks-for-downloading-instagram-content-onto-iphone/"><u>[New] Quick Hacks for Downloading Instagram Content Onto iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-sound-controls-in-windows-os/"><u>Addressing Faulty Sound Controls in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-magix-acid-pros-successors-in-vector-editing/"><u>[Updated] Magix ACID Pro's Successors in Vector Editing</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/age-friendly-features-in-pre-windows-10-systems/"><u>Age-Friendly Features in Pre-Windows 10 Systems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-best-free-video-editing-tools-for-avi-format/"><u>New 2024 Approved The Best Free Video Editing Tools for AVI Format</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-windows-11-gamers-ultimate-playbook-top-5-record-techniques/"><u>2024 Approved  Windows 11 Gamers' Ultimate Playbook  Top 5 Record Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-sifting-through-media-options-vlc-versus-mx/"><u>2024 Approved  Sifting Through Media Options  VLC Versus MX</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-sharefake-location-on-whatsapp-for-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-one-stop-shop-for-podcast-platforms-and-directories-for-2024/"><u>The One-Stop Shop for Podcast Platforms and Directories for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-essential-steps-for-perfect-audio-capture-in-garageband/"><u>Updated Essential Steps for Perfect Audio Capture in GarageBand</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leveraging-view-counts-for-financial-freedom-online-for-2024/"><u>Leveraging View Counts for Financial Freedom Online for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-curated-collection-unrestricted-melodies-ideal-for-visual-storytelling/"><u>New Curated Collection Unrestricted Melodies Ideal for Visual Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-tips-on-how-skip-edgenuity-videos-easily/"><u>2024 Approved  Tips on How Skip Edgenuity Videos Easily</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-easy-editing-unlimited-canon-lut-choices-for-2024/"><u>[New] Easy Editing - Unlimited Canon LUT Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-quick-fix-extracting-silent-footage-from-your-iphone-for-2024/"><u>New Quick Fix Extracting Silent Footage From Your iPhone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-unique-tiktok-identity-standout-pfp-concepts-to-embrace/"><u>[New] Unique TikTok Identity  Standout PFP Concepts to Embrace</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-change-video-dimensions-quickly-and-easily/"><u>In 2024, Change Video Dimensions Quickly and Easily</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-ultimate-rankings-top-budget-friendly-photo-editors-online/"><u>[New] 2024 Approved  The Ultimate Rankings  Top Budget-Friendly Photo Editors Online</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-peeking-beyond-one-camera-limitations/"><u>[Updated] In 2024, Peeking Beyond One-Camera Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
</ul></div>
