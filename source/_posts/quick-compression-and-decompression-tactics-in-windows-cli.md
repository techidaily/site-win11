---
title: Quick Compression & Decompression Tactics in Windows CLI
date: 2024-06-25T11:45:20.747Z
updated: 2024-06-26T11:45:20.747Z
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

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

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

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

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
<li><a href="https://win11.techidaily.com/windows-wizardry-entering-control-panel-quickly/"><u>Windows Wizardry: Entering Control Panel Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/6-tips-to-improve-your-wsl-2-docker-experience-on-windows/"><u>6 Tips to Improve Your WSL 2 Docker Experience on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-methods-to-resolve-error-1-in-games/"><u>Win-Friendly Methods to Resolve Error 1 in Games</u></a></li>
<li><a href="https://win11.techidaily.com/essential-reasons-why-pcs-outshine-macs-9/"><u>Essential Reasons Why PCs Outshine Macs (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://win11.techidaily.com/cease-auditory-gain-on-windows-operating-system/"><u>Cease Auditory Gain on Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-impact-on-performance-the-unseen-effect-of-disguised-software/"><u>Hidden Impact on Performance: The Unseen Effect of Disguised Software</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-stalled-resource-monitors-procedure-in-windows-11/"><u>Streamlining Stalled Resource Monitors: Procedure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-task-management-easy-run-tool-integration-on-windows/"><u>Upgrade Your Task Management: Easy Run Tool Integration on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/ending-echoes-reconnecting-audio-to-obs/"><u>Ending Echoes  Reconnecting Audio to OBS</u></a></li>
<li><a href="https://animation-videos.techidaily.com/tips-for-gif-to-animated-png/"><u>Tips for GIF to Animated PNG</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-samsung-galaxy-s23-ultra-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Samsung Galaxy S23 Ultra.</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-xiaomi-11-series-a-visual-journey-through-precision-recording/"><u>[Updated] In 2024, Xiaomi 11 Series  A Visual Journey Through Precision Recording</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-streaming-wars-recap-fb-live-yt-live-and-twitter-spaces/"><u>[New] Streaming Wars Recap  FB LIVE, YT Live & Twitter Spaces</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-xiaomi-13t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-best-zero-cost-wmv-video-editors-a-comprehensive-review/"><u>Updated In 2024, Best Zero-Cost WMV Video Editors A Comprehensive Review</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-create-transparent-background-on-picsart-for-2024/"><u>How To Create Transparent Background On Picsart for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-lava-blaze-2-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Lava Blaze 2? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-hot-snapshots-eye-catching-filters-and-lenses-explored/"><u>2024 Approved  Hot Snapshots  Eye-Catching Filters & Lenses Explored</u></a></li>
</ul></div>
