---
title: Streamlined Storage Solutions - Instantly Generate Folders on Windows 11
date: 2024-10-09T22:08:22.592Z
updated: 2024-10-15T19:39:37.902Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlined Storage Solutions - Instantly Generate Folders on Windows 11
excerpt: This Article Describes Streamlined Storage Solutions - Instantly Generate Folders on Windows 11
keywords: WinStorage Optimization,Quick Folder Creation,Streamlined File System,Efficient Data Organization,Windows 11 Sync Storage,Instant Folders Setup,Storage Solution Simplified
thumbnail: https://thmb.techidaily.com/5b6554e76aaa2a052eebb5ed360ccf43529d16f47d56cedf742a90d738a59cc9.jpg
---

## Streamlined Storage Solutions - Instantly Generate Folders on Windows 11

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
`md "[foldername]", "[foldername]", "[foldername]", "[foldername]"`
6. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md "january", "february", "march", "april"`  
![File names command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-md-files.jpg)

 Finally, close the Powershell window and check if the folders have been created.

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
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-deciding-on-sns-hdr-its-value-proposition-explored/"><u>[New] 2024 Approved Deciding on SNS HDR Its Value Proposition Explored</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-fb-story-downloads-decoded-a-quick-and-convenient-guide-for-all-users/"><u>[New] In 2024, FB Story Downloads Decoded A Quick & Convenient Guide for All Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-uploading-success-stories-mastering-igtv-content-posting/"><u>[New] Uploading Success Stories Mastering IGTV Content Posting</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-how-to-add-text-to-youtube-video-before-or-after-uploading/"><u>[Updated] In 2024, How to Add Text to YouTube Video Before or After Uploading</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-expertise-in-visual-communication-a-guide-to-gif-creation/"><u>2024 Approved Expertise in Visual Communication A Guide to GIF Creation</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-videos-using-text-annotations-in-windows-movie-maker-for-pc-users/"><u>Enhance Your Videos Using Text Annotations in Windows Movie Maker for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/essential-strategies-for-accessing-youtube-on-the-go-mastering-the-art-of-off-premises-viewing-with-mobile-apps/"><u>Essential Strategies for Accessing YouTube on the Go: Mastering the Art of Off-Premises Viewing with Mobile Apps</u></a></li>
<li><a href="https://screen-capture.techidaily.com/expert-guide-streaming-and-saving-hulu-seasons-flawlessly-for-2024/"><u>Expert Guide Streaming and Saving Hulu Seasons Flawlessly for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/free-online-audio-compressor-options-ranked-the-top-5-picks-for-sound-enthusiasts/"><u>Free Online Audio Compressor Options Ranked: The Top 5 Picks for Sound Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-the-legacy-slamius-wizard-on-kodi-19-and-18-lasting-solutions/"><u>Guide: Setting up the Legacy Slamius Wizard on Kodi 19 & 18 – Lasting Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-easily-transform-a-gif-into-moving-image-format-a-3-step-quicktime-conversion-guide/"><u>How to Easily Transform a GIF Into Moving Image Format: A 3-Step QuickTime Conversion Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-ultimate-list-templates-for-youtube-previews/"><u>In 2024, Ultimate List Templates for YouTube Previews</u></a></li>
<li><a href="https://win11.techidaily.com/listenradioandpc/"><u>ListenRadioへのアクセス&PC上での曲録りガイド</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-mkv-file-integration-with-adobe-premiere-pro-troubleshooting-tips-and-techniques/"><u>Mastering MKV File Integration with Adobe Premiere Pro: Troubleshooting Tips and Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-multimedia-management-a-comprehensive-guide-to-using-desktop-tools-and-applications-for-various-file-uses/"><u>Mastering Multimedia Management: A Comprehensive Guide to Using Desktop Tools & Applications for Various File Uses</u></a></li>
<li><a href="https://win11.techidaily.com/mp3dailymotion/"><u>MP3への変換：Dailymotionビデオからスマートな転送ガイド</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-6-economical-action-cams-available-for-99-or-below-for-2024/"><u>Top 6 Economical Action Cams Available for $99 or Below for 2024</u></a></li>
<li><a href="https://fox-metric.techidaily.com/windowsvmware-pc/"><u>WindowsオペレーティングシステムのVMware環境への移行: 実機PCから仮想マシンへ</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    