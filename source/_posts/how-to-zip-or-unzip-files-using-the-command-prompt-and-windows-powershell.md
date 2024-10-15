---
title: How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell
date: 2024-10-12T18:53:04.560Z
updated: 2024-10-15T16:19:39.743Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell
excerpt: This Article Describes How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell
keywords: Command Prompt File Compression,ZIP Extraction Command,PowerShell File Archiving,Unzipping Files CLI,Command Line Decompress,Windows Utilities for Zipping,Execute Zip Operations MS
thumbnail: https://thmb.techidaily.com/a02a9911f50368d686754fe93fbecd3af42fa753760f192f422f0660350e151b.jpg
---

## How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-dissecting-the-ispring-screencap-magic/"><u>[New] 2024 Approved Dissecting the iSpring Screencap Magic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-podcast-perfection-best-timing-strategy/"><u>2024 Approved Podcast Perfection Best Timing Strategy</u></a></li>
<li><a href="https://win-web3.techidaily.com/1728489230061-ssd/"><u>高速ディザスタリカバリ: ベストのソフトでSSD間で効果的クローン化</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-plus-revolutionizing-the-way-you-learn-a-new-language/"><u>ChatGPT Plus: Revolutionizing the Way You Learn a New Language</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-unregistered-photos-package-issue-in-windows-os/"><u>Fixing the Unregistered Photos Package Issue in Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-on-iphone-6s-plus-5-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover deleted pictures on iPhone 6s Plus? 5 Best Solutions | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-sonics-crashes-fix-fullscreen-fails-on-windows-11/"><u>Navigating the Maze of Sonic's Crashes: Fix Fullscreen Fails on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/precision-and-productivity-top-8-window-pomodoro-timers-reviewed/"><u>Precision and Productivity: Top 8 Window Pomodoro Timers Reviewed</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-relay-youtube-playlists-to-the-public-for-2024/"><u>Rapid Relay Youtube Playlists to the Public for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-shockwave-flash-now-compatible-with-google-chrome/"><u>Resolved: Shockwave Flash Now Compatible with Google Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/start-windows-file-explorer-using-onedrive-pathway/"><u>Start Windows File Explorer Using OneDrive Pathway</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/ultimate-tutorial-mastering-seagate-backup-manager-in-windows-11/"><u>Ultimate Tutorial: Mastering Seagate Backup Manager in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/your-new-pcs-best-friend-10-indispensable-windows-apps/"><u>Your New PC's Best Friend: 10 Indispensable Windows Apps</u></a></li>
</ul></div>

