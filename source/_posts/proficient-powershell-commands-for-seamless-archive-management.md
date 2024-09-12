---
title: Proficient PowerShell Commands for Seamless Archive Management
date: 2024-09-11T09:39:05.036Z
updated: 2024-09-12T09:39:05.036Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
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

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-enhance-your-fb-with-iphonesandroids-favorite-tunes-for-2024/"><u>[New] Enhance Your FB with iPhones/Androids' Favorite Tunes for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-true-story-of-youtube-earnings-and-viewer-volume-requirements/"><u>[New] The True Story of YouTube Earnings and Viewer Volume Requirements</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-steps-to-create-youtube-beginnings-and-ends-on-a-budget/"><u>[Updated] 2024 Approved Essential Steps to Create YouTube Beginnings & Ends on a Budget</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-taming-twitch-audio-for-top-notch-streaming-saves/"><u>[Updated] In 2024, Taming Twitch Audio for Top-Notch Streaming Saves</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-thankful-innovations-premium-and-budget-outro-themes/"><u>2024 Approved Thankful Innovations Premium & Budget Outro Themes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024s-prime-cameras-for-first-timers/"><u>2024'S Prime Cameras for First Timers</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-boot-up-windows-startup-with-notebooks-available/"><u>Efficient Boot-Up: Windows Startup with Notebooks Available</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-xbox-service-interruptions-in-windows-os/"><u>Eliminating Xbox Service Interruptions in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-edge-safety-integrate-microsofts-defender-aguard/"><u>Enhance Edge Safety: Integrate Microsoft's Defender Aguard</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-tips-for-getting-rid-of-the-ai-copilot-add-on-from-windows-11-computers/"><u>Expert Tips for Getting Rid of the AI Copilot Add-On From Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/five-strategies-to-rejuvenate-file-explorer/"><u>Five Strategies to Rejuvenate File Explorer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-resolving-unrecognized-hardware-problems-code-19-on-pcs/"><u>Guide to Resolving Unrecognized Hardware Problems (Code 19) on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-hidden-results-from-your-windows-1011-search-tool/"><u>Identifying Hidden Results From Your Windows 10/11 Search Tool</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-plus-online-here-are-6-easy-ways-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 8 Plus Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-vivo-t2-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Vivo T2 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-techs-leap-into-the-win11-era-a-roadmap/"><u>Legacy Tech's Leap Into the Win11 Era: A Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-compatibility-issues-in-windows-11/"><u>Mastering Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-solutions-for-create-failed-issue-windows-error-30005/"><u>Mastering Solutions for Create Failed Issue - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-error-code-0x80070570-fixes-for-broken-files-on-windows-11/"><u>Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-intricate-boot-configuration-landscape/"><u>Navigating Through Windows' Intricate Boot Configuration Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-screen-quality-resetting-graphics-in-windows-11/"><u>Optimize Screen Quality: Resetting Graphics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-self-triggered-terminal-displays-in-windows/"><u>Preventing Self-Triggered Terminal Displays in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weekend-sale-buy-now-at-612yr-with-windows-10/"><u>Prime Weekend Sale: Buy Now at $6.12/Yr with Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-the-start-page-for-windows-task-manager/"><u>Redefining the Start Page for Windows Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-gaps-between-windows-explorer-folders/"><u>Resolving Gaps Between Windows Explorer Folders</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-retro-games-achievement-integration-with-retroarch-tips/"><u>Revitalizing Retro Games: Achievement Integration with Retroarch Tips</u></a></li>
<li><a href="https://win11.techidaily.com/solving-stranded-status-on-xbox-for-pc-a-practical-approach/"><u>Solving ‘Stranded’ Status on Xbox for PC: A Practical Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/soundless-speed-heres-how-to-get-the-audio-back-in-forza-horizon-4/"><u>Soundless Speed? Here's How to Get the Audio Back in Forza Horizon ⁩4!₭</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-for-deleting-profiles-on-windows-11-with-revo-software/"><u>Step-by-Step Tutorial for Deleting Profiles on Windows 11 with Revo Software</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-error-403-in-robloxwindows/"><u>Strategies to Resolve Error 403 in Roblox/Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-to-the-not-supported-interface-error/"><u>Swift Solutions to the Not-Supported Interface Error</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-dodging-enter-credentials-message-in-windows/"><u>Tactics for Dodging 'Enter Credentials' Message in Windows</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-10-unmissable-xbox-series-xs-titles-from-the-xbox-one-library/"><u>Top 10 Unmissable Xbox Series X|S Titles From the Xbox One Library</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-honor-x9b-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Honor X9b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-full-potential-with-microsofts-copilot-key/"><u>Unlocking Windows 11'S Full Potential with Microsoft's Copilot Key</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-code-4-spotify-connection-problem-in-w10w11/"><u>Unraveling the Code 4 Spotify Connection Problem in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/whats-win32keygen-an-analysis-of-its-threats-and-remediation-processes-for-pcs/"><u>What's Win32/Keygen? An Analysis of Its Threats & Remediation Processes for PCs</u></a></li>
</ul></div>

