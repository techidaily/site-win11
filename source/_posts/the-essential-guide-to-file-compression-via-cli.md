---
title: The Essential Guide to File Compression via CLI
date: 2024-07-13T10:56:46.071Z
updated: 2024-07-14T10:56:46.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to File Compression via CLI
excerpt: This Article Describes The Essential Guide to File Compression via CLI
keywords: FileCompress CLI,DataPackCLI,ZipCLIGuide,ArchiveCmds,MinifyFilesCLI,CompressionTechniques,CommandLineArchiving
thumbnail: https://thmb.techidaily.com/770723973e178e7a8930f29e3f500f2a61aa4b3ccf5eb07317cde4aac3003016.jpg
---

## The Essential Guide to File Compression via CLI

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
<li><a href="https://on-screen-recording.techidaily.com/new-prioritize-privacy-in-conversations-the-best-10-free-secure-mobile-calling-apps-for-iosandroid-for-2024/"><u>[New] Prioritize Privacy in Conversations – The Best 10 Free, Secure Mobile Calling Apps for iOS/Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenient-path-to-iis-manager-entry-point/"><u>The Convenient Path to IIS Manager Entry Point</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-monitoring-your-instagram-exit-strategy/"><u>[New] In 2024, Monitoring Your Instagram Exit Strategy</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-honor-x8b-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Honor X8b to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/proven-windows-11-ways-to-boost-workflow-and-productivity-45/"><u>Proven Windows 11 Ways to Boost Workflow and Productivity (45)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-disconnecting-printers-in-windows/"><u>Quick Fixes for Disconnecting Printers in Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/leading-the-charge-8-innovative-apps-revolutionizing-sound-recording/"><u>Leading the Charge 8 Innovative Apps Revolutionizing Sound Recording</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-honor-play-40c-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Honor Play 40C Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-microsoft-store-eradicating-code-0x80072f30/"><u>Mastering the Microsoft Store: Eradicating Code 0X80072F30</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-unfreezing-frozen-obs-stream-input/"><u>2024 Approved  Unfreezing Frozen OBS Stream Input</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-iphone-se-2022-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From iPhone SE (2022) Online</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamlessly-updated-pro-6-system-drivers/"><u>Seamlessly Updated Pro 6 System Drivers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-online-junctions-providing-free-high-end-vector-artworks-and-graphics/"><u>Best Online Junctions Providing Free, High-End Vector Artworks & Graphics</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Honor 70 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-addressing-windows-onedrive-errors-and-restoring-folder-integration/"><u>Quick Guide: Addressing Windows OneDrive Errors and Restoring Folder Integration</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-wows-unexpected-crash-in-windows-1111/"><u>How to Tackle WoW’s Unexpected Crash in Windows 11/11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-does-youtube-work-after-a-video-is-uploaded/"><u>[New] 2024 Approved  How Does YouTube Work After a Video Is Uploaded</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-elevate-your-content-with-the-best-free-video-translator-apps/"><u>Updated 2024 Approved Elevate Your Content with the Best Free Video Translator Apps</u></a></li>
<li><a href="https://win11.techidaily.com/no-illusions-allowed-true-tales-of-unmasking-windows-ploys/"><u>No Illusions Allowed: True Tales of Unmasking Windows Ploys</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-uncovering-thrilling-soundtracks-components/"><u>New 2024 Approved Uncovering Thrilling Soundtracks Components</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-10-creative-overlays-for-video-content-for-2024/"><u>Top 10 Creative Overlays for Video Content for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-masterful-designers-top-insta-hlv-page-builders/"><u>[Updated] In 2024, Masterful Designers  Top Insta HLV Page Builders</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lost-connection-between-powershell-and-windows/"><u>Troubleshooting: Lost Connection Between PowerShell and Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-poco-f5-pro-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Poco F5 Pro 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-productivity-easy-office-setup-for-windows-1011/"><u>Enhance Productivity: Easy Office Setup for Windows 10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-vivo-t2-pro-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Vivo T2 Pro 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc00d36b4-in-windows-11/"><u>Troubleshooting Error Code 0xC00D36B4 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/re-activate-your-pc-addressing-error-code-22-in-windows-11/"><u>Re-Activate Your PC: Addressing Error Code 22 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/growth-plans-for-windows-hard-drive-without-data-loss/"><u>Growth Plans for Windows Hard Drive without Data Loss</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-oppo-a58-4g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Oppo A58 4G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-best-full-screen-recorders-windows-and-macos-version/"><u>[Updated] 2024 Approved  Best Full-Screen Recorders - Windows & macOS Version</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-an-improved-taskbar-on-windows-11/"><u>Tips for an Improved Taskbar on Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-pocket-sized-mac-viewer-absolutely-free/"><u>In 2024, Pocket-Sized Mac Viewer - Absolutely Free</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-time-on-mass-file-naming-with-powertools/"><u>Cut Down Time on Mass File Naming with PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-display-issues-in-modern-windows-versions/"><u>Overcoming Common Display Issues in Modern Windows Versions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-6-plus-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone 6 Plus i Do? Get Answers here</u></a></li>
<li><a href="https://win11.techidaily.com/multitasking-made-simple-windows-1110-window-cascade-guide/"><u>Multitasking Made Simple: Windows 11/10 Window Cascade Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-best-spotify-ripper-how-to-rip-music-from-spotify/"><u>New In 2024, Best Spotify Ripper How to Rip Music From Spotify?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-content-revenue-route-map-comparing-the-best-streaming-platforms/"><u>[New] In 2024, Content Revenue Route Map  Comparing the Best Streaming Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/guide-dealing-with-invalid-app-installs-on-windows/"><u>Guide: Dealing with Invalid App Installs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/premium-laptops-highlighted-at-ifa-2023/"><u>Premium Laptops Highlighted at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-performance-of-a-non-responsive-windows-folder/"><u>Strategies to Improve Performance of a Non-Responsive Windows Folder</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Itel P55T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-cameras-to-device-manager-display/"><u>Reintroduce Missing Cameras to Device Manager Display</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-easy-peasy-youtube-tutorials-making-content-that-works-for-all/"><u>[Updated] Easy-Peasy YouTube Tutorials  Making Content That Works for All</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-tasks-using-supercharged-run-tool-in-windows-1011/"><u>Streamline Tasks Using Supercharged Run Tool in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unlinked-files-and-absence-of-assigned-apps-win/"><u>Resolving Unlinked Files and Absence of Assigned Apps (Win)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-conquer-youtubes-copy-paste-loop-mastery-essentials/"><u>[Updated] 2024 Approved  Conquer YouTube's Copy-Paste  Loop Mastery Essentials</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-fixing-intermittent-frames-in-obs-recordings/"><u>[New] Fixing Intermittent Frames in OBS Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-efficiency-getting-acquainted-with-window-11s-search-tool/"><u>Unleash Efficiency: Getting Acquainted With Window 11’S Search Tool</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-wmp-playback-issues/"><u>Guide to Overcoming WMP Playback Issues</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-how-to-create-youtube-intro-animation-like-a-pro/"><u>2024 Approved How to Create YouTube Intro Animation Like a Pro</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-heaviest-airborne-haulers-drone-selection-insights/"><u>[Updated] Heaviest Airborne Haulers  Drone Selection Insights</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-sculpting-soundscapes-advanced-methods-for-isolating-lyrics-from-harmonized-tunes/"><u>In 2024, Sculpting Soundscapes Advanced Methods for Isolating Lyrics From Harmonized Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-outlook-app-not-syncing-on-windows-heres-how-to-fix-it/"><u>Is the Outlook App Not Syncing on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-text-inconsistency-ms-resouce-error-win11/"><u>Addressing Text Inconsistency: Ms-Resouce Error, Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/professional-video-quality-at-your-fingertips-ois-powered-choices/"><u>Professional Video Quality at Your Fingertips  OIS-Powered Choices</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-0x00000001-restoring-xbox-playability/"><u>Remedy for 0X00000001: Restoring Xbox Playability</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-office-overcoming-activation-failures/"><u>Troubleshooting Office: Overcoming Activation Failures</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-critical-failures-in-windows-with-error-code-c0000022/"><u>Tackling Critical Failures in Windows with Error Code C0000022</u></a></li>
</ul></div>
