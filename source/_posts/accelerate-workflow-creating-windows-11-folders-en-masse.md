---
title: "Accelerate Workflow: Creating Windows 11 Folders En Masse"
date: 2024-06-25T11:40:29.385Z
updated: 2024-06-26T11:40:29.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerate Workflow: Creating Windows 11 Folders En Masse"
excerpt: "This Article Describes Accelerate Workflow: Creating Windows 11 Folders En Masse"
keywords: Win11 Folder Creation,Accelerate File Organization,Mass Windows 11 Setup,Quick Workflow Procedures,Efficient OS Customization,Batch System Files,Streamlined PC Management
thumbnail: https://thmb.techidaily.com/e591b5728fa84d66a3323b91b4ed2e3f5b0efaa53a757d0b8f7bbc674ee0d976.jpg
---

## Accelerate Workflow: Creating Windows 11 Folders En Masse

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

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

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-your-outlook-calendar-on-windows/"><u>How to Customize Your Outlook Calendar on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-winning-strategy-running-windows-11-on-mac-via-parallels/"><u>Craft a Winning Strategy: Running Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-top-12-best-tycoon-games-to-kill-time/"><u>[New] 2024 Approved  Top 12 Best Tycoon Games to Kill Time</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-a-step-by-step-igtv-translation-guide/"><u>[New] In 2024, A Step-By-Step IGTV Translation Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-realme-narzo-60-pro-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Realme Narzo 60 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-imovie-hacks-for-unique-and-memorable-youtube-openers/"><u>2024 Approved  IMovie Hacks for Unique and Memorable YouTube Openers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-lut-lovers-delight-complimentary-sets-for-djis-miniair2/"><u>In 2024, LUT Lovers Delight  Complimentary Sets for DJI's Mini/Air2</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-windows-video-editing-top-imovie-alternatives-for-pc-users/"><u>Updated In 2024, Windows Video Editing Top iMovie Alternatives for PC Users</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/efficient-onboarding-engaging-with-friends-via-instagram-live/"><u>Efficient Onboarding  Engaging with Friends via Instagram Live</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-reaper-uncovered-a-beginners-handbook-on-audio-editing-tools/"><u>In 2024, REAPER Uncovered A Beginners Handbook on Audio Editing Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>