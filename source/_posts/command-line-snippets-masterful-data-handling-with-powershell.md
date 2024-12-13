---
title: "Command Line Snippets: Masterful Data Handling with PowerShell"
date: 2024-12-08T04:55:12.447Z
updated: 2024-12-13T09:38:40.609Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Snippets: Masterful Data Handling with PowerShell"
excerpt: "This Article Describes Command Line Snippets: Masterful Data Handling with PowerShell"
keywords: PowerShell Scripts,Command Line Tools,Data Manipulation PS,Advanced CLI Tips,Efficient Data Processing,Automated Task Execution,Powerful Snippet Examples
thumbnail: https://thmb.techidaily.com/3c3e9aebd6b49c0af91473b8783124a08a04e227f020283ad8022a46d57974e6.jpg
---

## Command Line Snippets: Masterful Data Handling with PowerShell

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-skype-groups-setting-up-windowsmac-conversations/"><u>[New] In 2024, Skype Groups Setting Up Windows/Mac Conversations</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-expert-tips-top-6-apps-that-make-storing-linkedin-videos-simple/"><u>[Updated] In 2024, Expert Tips Top 6 Apps That Make Storing LinkedIn Videos Simple</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-unlocking-financial-potential-how-to-earn-with-youtube-shorts/"><u>2024 Approved Unlocking Financial Potential How to Earn with YouTube Shorts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/affordable-electric-vehicles-the-end-of-americas-lowest-priced-option/"><u>Affordable Electric Vehicles: The End of America's Lowest-Priced Option</u></a></li>
<li><a href="https://blog-min.techidaily.com/dvdandpc/"><u>DVDダウンロード&コピー手順：スマホ・タブレットからPC/ゲーム機まで対応ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-file-management-with-self-extraction-techniques-in-win11/"><u>Elevating File Management with Self-Extraction Techniques in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-2s-errortoomanypatterns-a-step-by-step-solution/"><u>Eliminating WSL 2'S ERROR_TOO_MANY_PATTERNS: A Step-by-Step Solution</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/experience-unmatched-endurance-with-the-moto-g-power-a-comprehensive-review/"><u>Experience Unmatched Endurance with the Moto G Power - A Comprehensive Review</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/free-voice-modification-tools-enhance-your-auditory-presentation/"><u>Free Voice Modification Tools – Enhance Your Auditory Presentation</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolve-error-0xc0000001-in-windows-os/"><u>Guide to Resolve Error 0XC0000001 in Windows OS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-nokia-c12-is-unlocked-by-drfone-android/"><u>How To Check if Your Nokia C12 Is Unlocked</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/in-depth-aomei-backupper-support-qanda-for-troubleshooting-and-solutions/"><u>In-Depth AOMEI Backupper Support Q&A for Troubleshooting and Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-windows-tools-for-easy-cr2-image-conversion/"><u>Leveraging Windows Tools for Easy CR2 Image Conversion</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/nikon-z7-review-a-top-tier-mirrorless-that-gets-nearly-everything-right/"><u>Nikon Z7 Review: A Top-Tier Mirrorless That Gets Nearly Everything Right</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-disabling-office-updates-on-pc/"><u>Quick Guide to Disabling Office Updates on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unsuccessful-file-creation-in-error-30005-on-windows/"><u>Tackling Unsuccessful File Creation in Error 30005 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/virtualizing-windows-11-with-vmware-workstation-17-player/"><u>Virtualizing Windows 11 with VMWare Workstation 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/winterize-windows-holiday-customization-steps/"><u>Winterize Windows: Holiday Customization Steps</u></a></li>
<li><a href="https://win11.techidaily.com/yuletide-yumminess-wrapping-apps-in-christmas-joy/"><u>Yuletide Yumminess: Wrapping Apps in Christmas Joy</u></a></li>
</ul></div>

