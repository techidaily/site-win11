---
title: The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes
date: 2024-07-13T10:17:51.730Z
updated: 2024-07-14T10:17:51.730Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes
excerpt: This Article Describes The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes
keywords: Win Folder Creation Tips,Mass Window Folder Make,Quick Create Folders WIN,Efficient Windows Folder Trick,Click-to-Folders in OS X,Optimize WIN Folder Creation,Speed Up File Organizing Win
thumbnail: https://thmb.techidaily.com/4abc1e0d974f64940dfb669b21c754808ce4ab1e9a63c263741b581b4fbcec72.jpg
---

## The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes

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
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-personalized-timelength-upload-on-youtube/"><u>[New] Personalized Timelength Upload on YouTube</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-ultimate-list-of-10-budget-friendly-discord-voice-recorder-tools/"><u>[Updated] Ultimate List of 10 Budget-Friendly Discord Voice Recorder Tools</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-techniques-for-reducing-tempo-in-audio-waves/"><u>Updated 2024 Approved Techniques for Reducing Tempo in Audio Waves</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/a-critical-look-at-the-latest-camera-recording-systems-for-2024/"><u>A Critical Look at the Latest Camera Recording Systems for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/strategizing-effective-movie-sneak-peeks/"><u>Strategizing Effective Movie Sneak Peeks</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pro-cameras-who-wins-gopro-and-garmin-virb-comparison/"><u>In 2024, Pro Cameras, Who Wins? GoPro & Garmin VIRB Comparison</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-record-your-gameplay-with-ease-3-simple-solutions/"><u>Updated 2024 Approved Record Your Gameplay with Ease 3 Simple Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-y56-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo Y56 5G</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-realme-narzo-n53-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-audio-output-on-microsofts-read-aloud-functionality/"><u>Resetting Audio Output on Microsoft's Read Aloud Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-access-to-system-fixes-windows-10-and-11-key-setups/"><u>Strategic Access to System Fixes: Windows 10 & 11 Key Setups</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-tips-elevating-your-projects-with-movie-maker-in-win11/"><u>Expert Tips  Elevating Your Projects with Movie Maker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/navigating-the-world-of-youtube-shorts-a-filmmakers-handbook-for-2024/"><u>Navigating the World of YouTube Shorts  A Filmmaker's Handbook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-defeat-synthetic-followers-for-true-popularity-peak/"><u>[Updated] 2024 Approved  Defeat Synthetic Followers for True Popularity Peak</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-strategic-approaches-to-dominating-spotifys-ad-space/"><u>2024 Approved  Strategic Approaches to Dominating Spotify's Ad Space</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/emystifying-the-world-of-youtube-and-its-keywords/"><u>[New] Demystifying the World of YouTube and Its Keywords</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-poco-m6-pro-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Poco M6 Pro 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-iphone-7-plus-by-drfone-ios/"><u>How To Factory Unlock Your Telstra iPhone 7 Plus</u></a></li>
</ul></div>
