---
title: "Command Line Utility Mastery: Handling Zipped Data with Ease"
date: 2024-11-03T21:25:07.940Z
updated: 2024-11-07T22:07:06.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Utility Mastery: Handling Zipped Data with Ease"
excerpt: "This Article Describes Command Line Utility Mastery: Handling Zipped Data with Ease"
keywords: CommandLineUtilities,ZipHandlingTips,FileDecompression,DataUnzippingGuide,MasteryCommandTools,EasyZipDataProcessing,ProficientZippingSkills
thumbnail: https://thmb.techidaily.com/c72f65d6cf6eccfb8dd0cd66944cb2172744b7375f3b2c967f4222ce690bc4fc.jpg
---

## Command Line Utility Mastery: Handling Zipped Data with Ease

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
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/new-in-2024-kickstart-a-successful-charity-contest-via-social-media/"><u>[New] In 2024, Kickstart a Successful Charity Contest via Social Media</u></a></li>
<li><a href="https://fox-direct.techidaily.com/discover-best-8-3d-realms-with-glossy-text-effects-for-2024/"><u>Discover Best 8 3D Realms with Glossy Text Effects for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-motorola-razr-40-ultra-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Motorola Razr 40 Ultra support AVCHD video?</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-taskbar-add-capslock-and-numlock-icons-on-win11/"><u>Enhance Taskbar: Add CapsLock & NumLock Icons on Win11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/experience-unmatched-control-and-mobility-the-ultimate-precision-gaming-with-a-cordless-sabrent-travel-mouse/"><u>Experience Unmatched Control and Mobility: The Ultimate Precision Gaming with a Cordless Sabrent Travel Mouse</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Poco C65 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/logitech-g-pro-x-microphone-problems-resolved-expert-tips-and-tricks/"><u>Logitech G Pro X Microphone Problems Resolved: Expert Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-new-widget-chooser-in-microsoft-windows-11/"><u>Mastering New Widget Chooser in Microsoft Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsoft-offices-error-0x80041015/"><u>Navigating Through Microsoft Office's Error 0X80041015</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-mouse-settings-to-enhance-accessibility-in-windows-11/"><u>Navigating Through Mouse Settings to Enhance Accessibility in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/sparking-interest-with-the-top-8-most-effective-youtube-thumbnails-for-2024/"><u>Sparking Interest with the Top 8 Most Effective YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-the-world-of-command-line-alias-names/"><u>Tapping Into the World of Command Line Alias Names</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-to-utilizing-hdr-on-windows-11-systems/"><u>Ultimate Guide to Utilizing HDR on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-methodology-to-split-audiosystems/"><u>Unpacking Windows’ Methodology to Split Audiosystems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/zero-fee-texting-services-optimized-for-iphone-and-ipod-touch-systems/"><u>Zero Fee Texting Services Optimized for iPhone and iPod Touch Systems</u></a></li>
</ul></div>

