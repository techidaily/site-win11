---
title: "Step-by-Step Guide: Mass Folder Creation Made Simple for Windows Users"
date: 2024-09-11T09:39:46.605Z
updated: 2024-09-12T09:39:46.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Mass Folder Creation Made Simple for Windows Users"
excerpt: "This Article Describes Step-by-Step Guide: Mass Folder Creation Made Simple for Windows Users"
keywords: Windows Folder Organization,Simplified Folder Setup,Mass Folder Creation Guide,Easy Folders in Windows,Streamline File Management,Windows User Folder Tips,Quick Folder Making Pro
thumbnail: https://thmb.techidaily.com/e36d4a2a6c674cd6677ba6814b8c312dcb4a11aef63558c23c156a0dfc593865.jpg
---

## Step-by-Step Guide: Mass Folder Creation Made Simple for Windows Users

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Command Prompt to Create Multiple Folders at Once

 In this first method, we will be using a command-line utility called Command Prompt in Windows. Unless you are very tech-savvy, you may not have noticed it anywhere in Windows, but it has been around for quite a long time.

 Typically, administrators use it to make advanced-level changes throughout the system. You can enter text-based commands to automate a bunch of tasks.

 Below, we have listed detailed steps for using Command Prompt to create multiple folders at once. Make sure you are signed in to Windows as an administrator before you proceed:

1. Type **Command Prompt** in Windows search and click on **Run as administrator**.
2. Alternatively, you can also open Run by pressing **Win** \+ **R** and type **cmd** in the text field. Press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.  
![Run dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/accessing-cmd-through-run-box.jpg)
3. Click **Yes** in the User Account Control prompt.
4. Type the following command in the Command Prompt window and hit **Enter** to execute it. Make sure to replace the \[location\] with the location where you want to create multiple folders.  
`cd /d [location]`
5. For instance, if we want to create folders in the C:\\users\\hp\\documents folder, we will execute the command like cd /d C:\\users\\hp\\documents.  
![Location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-cd-d-location-1.jpg)
6. Then, type **md** following the names of the folders in one command and execute it. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md january february march april`  
![Command with file names](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-md-files.jpg)
7. Once done, close the Command Prompt window and visit the location of folders in File Explorer to see if the folders have been created.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If for some reason using the Command Prompt does not work for you, you can use Windows Powershell (Admin) to perform the same steps. The Powershell works almost the same as Command Prompt, but it is much more powerful than cmd.

 To use Powershell, follow these steps:

1. Right-click on the **Windows icon** on your taskbar and choose **Powershell (Admin)**.  
![Windows Terminal (Admin)](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windows-terminal.jpg)
2. Select Yes in the UAC prompt.  
![UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-uac.jpg)
3. Now, execute the command mentioned below and change the \[Location\] with your targeted location for creating the folders.  
`cd [Location]`
4. We want to create the sub-folders in the document folders, so we will be executing the following command:  
`cd C:\users\hp\documents`  
![Execute location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-cd-d-location.jpg)
5. Once done, execute the following command. Replace the \[foldername\] with the names you want to give the folders.  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`md "[foldername]", "[foldername]", "[foldername]", "[foldername]"`
6. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md "january", "february", "march", "april"`  
![File names command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-md-files.jpg)

 Finally, close the Powershell window and check if the folders have been created.

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use the Notepad to Create Multiple Folders at Once

 Though it may come as a surprise, the Windows Notepad can perform more advanced technical operations than just writing to-do lists.

 The methods above are suitable if you only want to create multiple folders without any subfolders. If you wish to create subfolders as well, then an easy way to do it is by creating a batch script via Notepad.

 Here is how you can do that:

1. Type **Notepad** in Windows search and click **Open**.
2. In the Notepad window, click type **@ECHO OFF** and click **Enter**.
3. Then type **md** followed by the folder and subfolder names enclosed in double quotes. For instance, if we want to create a MUO January folder with a Windows subfolder and a MUO February folder with an Android subfolder, we will type it down in Notepad as:  
`@ECHO OFF  
md "MUOJan"\"Windows" "MUOFeb"\"Android"`  
![Notepad command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-notepad-command.jpg)
4. After you have typed down the names of all the folders and subfolders that you want to create, navigate to **File** in the top-left corner and choose **Save as**.  

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

## 3\. Use a Third-Party Application

 Last but not least, if you think using Command Prompt and Notepad is too time-consuming, you can try using a third-party application.

 There are quite a few apps that can help you achieve this, including the following:

* [Soboloft](https://www.sobolsoft.com/file-management.htm)
* [Text 2 Folders](https://www.softpedia.com/get/System/File-Management/Text-2-Folders.shtml)
* [Folder Frenzy](https://www.softpedia.com/get/System/File-Management/Folder-Frenzy.shtml)
* [FreeCommander XE](https://freecommander.com/en/summary/)
* [XMD](https://www.softpedia.com/get/System/File-Management/XMD.shtml)

 For illustration purposes, we will be using Folder Frenzy. The steps of creating multiple folders in other applications might vary, but the basics will remain the same.

1. Download Folder Frenzy.
2. Extract the downloaded file and then launch it.
3. Click **Yes** in the confirmation prompt.  
![Clicking Yes in the UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-agreement.jpg)
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-cultivating-connections-friendly-games-growth-with-friends-on-farms/"><u>[New] In 2024, Cultivating Connections Friendly Games Growth with Friends on Farms</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-ios-leading-psp-emulators-five-star-selections/"><u>[New] In 2024, IOS Leading PSP Emulators Five Star Selections</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-rotational-realities-how-to-captivate-with-instagrams-sideways-videos-for-2024/"><u>[New] Rotational Realities How to Captivate with Instagram's Sideways Videos for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-chromebook-users-companion-to-launching-and-deleting-audacity/"><u>2024 Approved Chromebook Users Companion to Launching and Deleting Audacity</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-direct-route-uploading-from-youtube-to-dailymotion/"><u>2024 Approved Direct Route Uploading From YouTube to Dailymotion</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-expert-techniques-for-simple-iphone-screenshot-processes/"><u>2024 Approved Expert Techniques for Simple IPhone Screenshot Processes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-professional-prowess-best-webcams-to-upgrade-your-podcasting/"><u>2024 Approved Professional Prowess Best Webcams to Upgrade Your Podcasting</u></a></li>
<li><a href="https://win11.techidaily.com/compreehing-window-10-closed-caption-problems-a-quick-fix/"><u>Compreehing Window 10 Closed Caption Problems: A Quick Fix</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-analysis-of-the-google-nest-hello-exploring-features-like-facial-recognition-and-package-alerts/"><u>Comprehensive Analysis of the Google Nest Hello: Exploring Features Like Facial Recognition & Package Alerts</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-fixes-for-when-you-cant-find-d3dx941dll-in-windows-systems/"><u>Effective Fixes for When You Can't Find d3dx9_41.dll in Windows Systems</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723003389959-eliminate-lag-and-boost-frame-rates-essential-fixes-to-improve-war-thunder-gameplay-this-year/"><u>Eliminate Lag and Boost Frame Rates: Essential Fixes to Improve War Thunder Gameplay This Year</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-usb-availability-problem/"><u>Fixing Insufficient USB Availability Problem</u></a></li>
<li><a href="https://win11.techidaily.com/harness-free-note-tools-on-windows-11/"><u>Harness Free Note Tools on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-exception-reached-error-during-debugging/"><u>How to Resolve 'Exception Reached' Error During Debugging</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-non-copyrighted-meditation-sounds/"><u>In 2024, Non-Copyrighted Meditation Sounds</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pic-perfect-ranking-the-best-photo-stickering-apps-for-iphonesandroids/"><u>In 2024, Pic Perfect Ranking the Best Photo Stickering Apps for iPhones/Androids</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-viral-cellphone-alert-songs-you-cant-ignore/"><u>In 2024, Viral Cellphone Alert Songs You Cant Ignore</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-steam-dll-repair-eliminate-errors-enjoy-uninterrupted-play/"><u>Mastering Steam Dll Repair: Eliminate Errors, Enjoy Uninterrupted Play</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-system-restore-on-windows-11-quick-access-methods/"><u>Mastering System Restore on Windows 11: Quick Access Methods</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-microsoft-edges-steady-backstage-in-win11/"><u>Optimizing Microsoft Edge's Steady Backstage in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-hurdles-to-use-windows-with-steam-link/"><u>Overcoming Hurdles to Use Windows with Steam Link</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pc-predicament-simple-solutions-to-desktop-troubles/"><u>Purple PC Predicament: Simple Solutions to Desktop Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/refresh-your-screen-writers-with-a-trio-of-tricks/"><u>Refresh Your Screen' Writers with a Trio of Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-update-issues-with-error-code-0x30017-in-windows/"><u>Remedying Update Issues with Error Code 0X30017 in Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/rethinking-streaming-new-platforms-challenge-obs/"><u>Rethinking Streaming New Platforms Challenge OBS</u></a></li>
<li><a href="https://win11.techidaily.com/smoothening-windows-steam-audio-performance/"><u>Smoothening Windows Steam Audio Performance</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-re-register-bluetooth-in-pcs-device-manager/"><u>Steps to Re-Register Bluetooth in PC's Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-content-transfer-within-windows-11s-shielded-mode-microsoft-edge-app-guard/"><u>Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard</u></a></li>
<li><a href="https://win11.techidaily.com/taming-windows-endless-file-explorer-opens/"><u>Taming Windows' Endless File Explorer Opens</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-free-media-players-for-windows/"><u>The 7 Best Free Media Players for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-potential-essential-tips-for-winning-with-wsl-2/"><u>Unlock Your Potential: Essential Tips for Winning with WSL 2</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-new-era-of-widget-selection-with-win11/"><u>Unveiling The New Era of Widget Selection with Win11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-login-strategy-move-from-a-pin-to-a-password-sign-in/"><u>Upgrading Your Login Strategy: Move From a PIN to a Password Sign-In</u></a></li>
<li><a href="https://win11.techidaily.com/windows-troubleshooting-resolving-roblox-closure-request-errors/"><u>Windows Troubleshooting: Resolving Roblox Closure Request Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    