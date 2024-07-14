---
title: Advanced Zipping with Command Prompt, Step by Step
date: 2024-07-13T10:48:05.131Z
updated: 2024-07-14T10:48:05.131Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Zipping with Command Prompt, Step by Step
excerpt: This Article Describes Advanced Zipping with Command Prompt, Step by Step
keywords: Command Prompt Zip,Advanced Zip CLI,Zip Prompt Guide,Compress Files CLI,Batch File Zipping,Quick Zip Commands,Zip Tasks Windows
thumbnail: https://thmb.techidaily.com/3da56b4dd62c9d29faa422fa86eb533c5fdaa7995cd6fe5de9f6ecf749c3b6f7.jpg
---

## Advanced Zipping with Command Prompt, Step by Step

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
<li><a href="https://win11.techidaily.com/bypassing-zero-x-error-in-the-mail-application-of-windows-11/"><u>Bypassing Zero X Error in the Mail Application of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ethernet-efficiency-top-tips-to-test-your-networks-pace-on-windows/"><u>Ethernet Efficiency: Top Tips to Test Your Network's Pace on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-inactive-windows-lock-screen-timer/"><u>Troubleshooting Inactive Windows Lock Screen Timer</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-future-skies-top-weather-apps-for-pc/"><u>A Window Into Future Skies: Top Weather Apps for PC</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-savor-the-hype-the-best-of-the-best-15-culinary-creations-from-tiktoks-food-influencers/"><u>[Updated] Savor the Hype  The Best of the Best 15 Culinary Creations From TikTok’s Food Influencers</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-selecting-android-and-ios-clocks-for-weddings/"><u>[Updated] The Ultimate Guide to Selecting Android and iOS Clocks for Weddings</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-digital-persona-username-overhaul-guide/"><u>Upgrading Your Digital Persona: UserName Overhaul Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-upconversion-unveiled-sdr-to-hdri-a-complete-guide/"><u>In 2024, Upconversion Unveiled  SDR to HDRI - A Complete Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/gamers-blueprint-for-money-making/"><u>Gamer’s Blueprint for Money-Making</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-blue-screen-essential-fixes-for-win10/"><u>Troubleshoot Blue Screen: Essential Fixes for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-e1-in-w10w11-devices/"><u>Tackling Error Code: E1 in W10/W11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-secure-boot-the-ultimate-rufus-guidebook/"><u>Conquering Secure Boot: The Ultimate Rufus Guidebook</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-apple-iphone-15-pro-max-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 15 Pro Max With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-textual-amplification-for-igtv-broadcasts/"><u>In 2024, Textual Amplification for IGTV Broadcasts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-winning-software-to-capture-your-display-on-windows-10/"><u>[New] 2024 Approved  Winning Software to Capture Your Display on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-with-our-top-5-budget-drivers-for-pcs/"><u>Unleash Potential with Our Top 5 Budget Drivers for PCs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-ultimate-tiktok-toolkit-increase-views-and-engagement/"><u>[New] The Ultimate TikTok Toolkit  Increase Views and Engagement</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-10-best-windows-movie-makers-of-the-year/"><u>2024 Approved 10 Best Windows Movie Makers of the Year</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-guide-to-navigating-stardews-ginger-island-for-2024/"><u>[Updated] The Ultimate Guide to Navigating Stardew’s Ginger Island for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-biometrics-permissions/"><u>Configuring Windows 11 Biometrics Permissions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-top-10-online-stores-for-personalized-box-designs/"><u>In 2024, Top 10 Online Stores for Personalized Box Designs</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-windows-chrome-problems/"><u>Unclogging Windows Chrome Problems</u></a></li>
<li><a href="https://fox-blue.techidaily.com/unveiling-how-luts-transform-visual-elements-in-photos-for-2024/"><u>Unveiling How LUTs Transform Visual Elements in Photos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-password-managers-for-windows-11-unleashing-your-digital-fortresses/"><u>Best Password Managers for Windows 11: Unleashing Your Digital Fortresses</u></a></li>
<li><a href="https://win11.techidaily.com/chocolatey-vs-windows-package-manager-which-is-the-better-tool-to-download-software-on-windows/"><u>Chocolatey Vs. Windows Package Manager: Which Is the Better Tool to Download Software on Windows?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-easy-steps-for-achieving-facebooks-prestigious-blue-badge-for-2024/"><u>[Updated] Easy Steps for Achieving Facebook's Prestigious Blue Badge for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-streamlined-strategy-for-igtv-and-instagram-story-integration/"><u>In 2024, Streamlined Strategy for IGTV & Instagram Story Integration</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-legality-of-recording-on-youtube-platform/"><u>[New] 2024 Approved  Legality of Recording on YouTube Platform?</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-store-access-on-windows-11/"><u>Troubleshooting Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-fatal-javascript-issue-on-windows-11s-discord-app/"><u>Easing the Fatal Javascript Issue on Windows 11'S Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-11-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 11 & 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-monetary-map-mr-beasts-financials-uncovered/"><u>In 2024, The Monetary Map  Mr. Beast’s Financials Uncovered</u></a></li>
<li><a href="https://win11.techidaily.com/twinkling-tokens-gifting-windows-games-via-mstore/"><u>Twinkling Tokens: Gifting Windows Games via MSTORE</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-infusing-fun-in-feeds-animating-instagram-text-on-stories/"><u>2024 Approved  Infusing Fun in Feeds  Animating Instagram Text on Stories</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-websites-that-work-on-your-windows-pc/"><u>Crafting Websites That Work on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-speed-up-pc-games-the-ultimate-speed-controller-selection/"><u>[New] 2024 Approved  Speed Up PC Games  The Ultimate Speed Controller Selection</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-digital-sketching-with-microsoft-paint-updates/"><u>Elevating Digital Sketching with Microsoft Paint Updates</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-navigating-network-needs-for-natural-growth-in-youtube-numbers/"><u>[New] 2024 Approved  Navigating Network Needs for Natural Growth in Youtube Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-not-enough-privileges-error-during-installation-on-windows/"><u>Eliminating Not Enough Privileges Error During Installation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-erroneous-temporary-folders-in-windows-11/"><u>Troubleshooting Erroneous Temporary Folders in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dynamic-palette-skills-in-color-adjustment/"><u>Dynamic Palette  Skills in Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/combat-windows-11-lags-top-strategies-to-boost-speed/"><u>Combat Windows 11 Lags: Top Strategies to Boost Speed</u></a></li>
<li><a href="https://extra-resources.techidaily.com/detailed-process-for-creating-professional-voice-recordings/"><u>Detailed Process for Creating Professional Voice Recordings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-laughing-alongside-the-metaverse-diy-humor-tips-and-tricks/"><u>In 2024, Laughing Alongside the Metaverse  DIY Humor Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-xiaomi-redmi-13c-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Xiaomi Redmi 13C Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
</ul></div>
