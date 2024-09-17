---
title: Proficient PowerShell Commands for Seamless Archive Management
date: 2024-09-16T06:22:36.568Z
updated: 2024-09-17T05:43:23.453Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proficient PowerShell Commands for Seamless Archive Management
excerpt: This Article Describes Proficient PowerShell Commands for Seamless Archive Management
keywords: PowerShell Archive Optimization,Efficient PowerShell Tools,Streamline Backup Scripts,Enhanced File Handling,Archiving with PowerShell,PowerShell Data Management,Secure File Syncing Protocols
thumbnail: https://thmb.techidaily.com/8605278b5d648a8e727674b42f156215fdccc4c56056b931eaef077a91501e84.jpg
---

## Proficient PowerShell Commands for Seamless Archive Management

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

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-legal-framework-the-fine-print-for-facebook-video-postings/"><u>[New] In 2024, Legal Framework The Fine Print for Facebook Video Postings</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-softening-volume-windowsmac-audio-tips/"><u>[New] Softening Volume Windows/Mac Audio Tips</u></a></li>
<li><a href="https://win11.techidaily.com/1726027145566-iso/"><u>「細切りのISOファイルをひも解ける完全ガイド - ビデオチュートリアル」</u></a></li>
<li><a href="https://win11.techidaily.com/2024-flv-windows-10/"><u>2024年版 FLV ビデオプレイヤーの復活！Windows 10用トップテクニックリスト公開</u></a></li>
<li><a href="https://win11.techidaily.com/5oiq5lq65zcr44gr44ot44oh44kq44ks44kt44oj44ox44ob44oj44gz44kl5yq55p6c55qe44gq44og44kv44ol44od44kv/"><u>成人向けビデオをキャプチャする効果的なテクニック</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-cost-free-options-with-microsoft-word-a-comprehensive-guide/"><u>Exploring Cost-Free Options with Microsoft Word: A Comprehensive Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-get-the-official-seal-of-approval-on-x-a-complete-guide/"><u>How To Get The Official Seal of Approval On X - A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-excessive-cpu-consumption-by-msmpengine-in-windows-10/"><u>How to Stop Excessive CPU Consumption by MsMpEngine in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-error-unable-to-access-windows-installer-issues/"><u>Step-by-Step Solution for Error: Unable to Access Windows Installer Issues</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-psychology-of-crafting-engaging-podcast-intros-for-2024/"><u>The Psychology of Crafting Engaging Podcast Intros for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/unveiling-the-secrets-of-sdr-to-hdr-enhancement-techniques-for-2024/"><u>Unveiling the Secrets of SDR-to-HDR Enhancement Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/44kz44o844oh44od44kv5lin6laz44gr44ki44kl5yuv55s75yan55sf6zqc5a6z44ks5zue6yg44gz44kl5pa55rov/"><u>コーデック不足による動画再生障害を回避する方法</u></a></li>
<li><a href="https://win11.techidaily.com/44ot44oh44kq44gu5lit44gr44og44kt44k544oi44k144ow44k44kk44oi44or6lplus95yqg5oml6acg6zug/"><u>ビデオの中にテキストサブタイトル追加手順集</u></a></li>
</ul></div>

