---
title: The Ultimate Guide to Grouping Files Into Windows 11 Directories
date: 2024-09-15T22:11:51.791Z
updated: 2024-09-16T16:05:20.496Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Grouping Files Into Windows 11 Directories
excerpt: This Article Describes The Ultimate Guide to Grouping Files Into Windows 11 Directories
keywords: WinGroupFilesGuide,OrganizeWindows11Dirs,FileDirectoriesInWin11,Windows11FileGrouping,GroupFilesWindows11,DirectoriesSetupWin11,Windows11FolderManagement
thumbnail: https://thmb.techidaily.com/7ba25f196f1fd36b2bff5ba5871f3da3d2f6d119166da5162e1c6bea9b39b80e.jpg
---

## The Ultimate Guide to Grouping Files Into Windows 11 Directories

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
![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
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
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-behind-the-brand-pewdiepies-financial-figures-unveiled/"><u>[New] Behind the Brand PewDiePie’s Financial Figures Unveiled</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-a-beginners-guide-to-gameye-win10/"><u>[Updated] 2024 Approved A Beginner's Guide to GamEye Win10</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-ultimate-picture-narrative-craft-pro-edition/"><u>2024 Approved Ultimate Picture Narrative Craft - Pro Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-guide-to-navigating-posting-on-altered-instagram-landscape/"><u>A Guide to Navigating Posting on Altered Instagram Landscape</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-the-iphone-13-icloud-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing the iPhone 13 iCloud Lock</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/break-barriers-join-mondlys-language-journey/"><u>Break Barriers, Join Mondly’s Language Journey</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-integration-assembling-your-digital-toolkit-in-win-11/"><u>Effortless Integration: Assembling Your Digital Toolkit in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-missing-taskbar-in-full-screen-browser-frames/"><u>Fixing Missing Taskbar in Full-Screen Browser Frames</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y100t-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y100t To Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-active-state-for-windows-11-user-interface/"><u>Reinstating Active State for Windows 11 User Interface</u></a></li>
<li><a href="https://article-files.techidaily.com/secrets-of-6-video-categories-for-viewer-retention-for-2024/"><u>Secrets of 6 Video Categories for Viewer Retention for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-override-windows-antivirusfirewall-blocking-chrome/"><u>Steps to Override Windows Antivirus/Firewall Blocking Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-settings-the-drivers-rebooting-roadmap/"><u>Tailoring Screen Settings: The Drivers' Rebooting Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-filesystem-glitches/"><u>Unlocking Windows 11'S Filesystem Glitches</u></a></li>
<li><a href="https://win-answers.techidaily.com/xbox-live-down-or-slow-heres-how-to-verify-its-current-server-status/"><u>Xbox Live Down or Slow? Here’s How To Verify Its Current Server Status!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    