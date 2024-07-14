---
title: Efficient Methods for Bulk Folder Formation in Windows 10/11
date: 2024-07-13T09:56:13.676Z
updated: 2024-07-14T09:56:13.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Methods for Bulk Folder Formation in Windows 10/11
excerpt: This Article Describes Efficient Methods for Bulk Folder Formation in Windows 10/11
keywords: Win Folder Efficiency,W10 Folder Organization,W11 Auto Folders,Bulk Folder Creation,Windows Optimized Storage,Quick Folder Setup,Folder Formation Tips
thumbnail: https://thmb.techidaily.com/cdded6aa8f500657d1cc67ca7b77cb926c32d80c757bf8e50b4e15a0eac70eb2.jpg
---

## Efficient Methods for Bulk Folder Formation in Windows 10/11

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-youtube-on-fb-maximizing-auto-play-efficiency/"><u>[New] YouTube on FB  Maximizing Auto-Play Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/7-rapid-responses-to-combat-windows-app-failures/"><u>7 Rapid Responses to Combat Windows App Failures</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-of-ms-error-lookup-in-w11/"><u>A Comprehensive Walkthrough of MS Error Lookup in W11</u></a></li>
<li><a href="https://win11.techidaily.com/5-proven-methods-to-clean-your-win11s-dns-cache/"><u>5 Proven Methods to Clean Your Win11's DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-task-management-in-microsoft-project/"><u>Accelerate Task Management in Microsoft Project</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dimension-of-cleanliness-windows-eraser-feature/"><u>A New Dimension of Cleanliness: Windows' Eraser Feature</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719346431441-navigate-through-common-snip-and-sketch-screen-capture-issues/"><u>Navigate Through Common Snip & Sketch Screen Capture Issues.</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-investors-guide-to-choosing-yt-channels/"><u>The Investor's Guide to Choosing YT Channels</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unveiling-underground-favorites-in-the-world-of-memes-for-2024/"><u>[New] Unveiling Underground Favorites in the World of Memes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-restoring-lost-windows-update/"><u>A Beginner's Guide to Restoring Lost Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unparalleled-dramatic-audio-experiences/"><u>2024 Approved  Unparalleled Dramatic Audio Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-a-glimpse-into-virtual-frontiers-with-jaunt-vr/"><u>[Updated] A Glimpse Into Virtual Frontiers with Jaunt VR</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/quick-start-to-youtube-success-creating-business-and-personal-channels-on-phone/"><u>Quick Start to YouTube Success  Creating Business & Personal Channels on Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Poco C51 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-understanding-absence-of-direct-messages/"><u>[Updated] 2024 Approved  Understanding Absence of Direct Messages</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-enable-or-disable-ntfs-file-compression-in-windows-11/"><u>4 Ways to Enable or Disable NTFS File Compression in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/d3d-launch-unsuccessful-repair-complete/"><u>D3D Launch Unsuccessful, Repair Complete</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-tweet-to-facebook-a-step-by-step-guide/"><u>2024 Approved  Tweet to Facebook  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-11-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-if-the-c-drive-keeps-filling-up-for-no-reason-on-windows/"><u>6 Fixes if the C: Drive Keeps Filling Up for No Reason on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/1719364636660-self-hosted-windows-gptclone-via-gpt4all/"><u>Self-Hosted Windows GPTClone via GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
</ul></div>
