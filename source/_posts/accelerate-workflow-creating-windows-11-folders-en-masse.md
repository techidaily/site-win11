---
title: "Accelerate Workflow: Creating Windows 11 Folders En Masse"
date: 2024-07-13T10:49:07.173Z
updated: 2024-07-14T10:49:07.173Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-innovative-approaches-to-capturing-skype-calls-on-obs/"><u>[Updated] 2024 Approved  Innovative Approaches to Capturing Skype Calls on OBS</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-management-app-collapses/"><u>Prevent Windows Management App Collapses</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pathways-three-keys-to-gaming-files/"><u>Windows Pathways: Three Keys to Gaming Files</u></a></li>
<li><a href="https://win11.techidaily.com/unmasking-the-undisclosed-instructions-for-accessing-windows-personal-character-console/"><u>Unmasking the Undisclosed: Instructions for Accessing Windows’ Personal Character Console</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-live-tv-saving-made-simple-with-free-software-tools/"><u>[New] 2024 Approved  Live TV Saving Made Simple with Free Software Tools</u></a></li>
<li><a href="https://win11.techidaily.com/old-school-keys-new-horizon-initiate-windows-11-with-windows-7-key/"><u>Old-School Keys, New Horizon: Initiate Windows 11 with Windows 7 Key</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-for-windows-11-widgets-a-comprehensive-list-of-enhancements/"><u>New Horizons for Windows 11 Widgets: A Comprehensive List of Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/showcasing-taskmanager-preeminent-style/"><u>Showcasing TaskManager Preeminent Style</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-honor-magic5-ultimate-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Honor Magic5 Ultimate Hard Reset | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-whats-winning-in-the-world-of-2023-tweets/"><u>[Updated] 2024 Approved  What's Winning in the World of 2023 Tweets</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-unleash-the-power-of-words-how-to-enchant-tinder-users-with-a-bio/"><u>[New] In 2024, Unleash the Power of Words  How to Enchant Tinder Users with a Bio</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-creativity-exquisite-text-effects-for-adobes-affects/"><u>In 2024, Unleash Creativity  Exquisite Text Effects For Adobe's Affects</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transformative-techniques-mastering-lut-application-in-post-production/"><u>2024 Approved  Transformative Techniques  Mastering LUT Application in Post-Production</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unpacking-tunefab-written-review-on-latest-tech-for-screen-recording-for-2024/"><u>Unpacking Tunefab' Written Review on Latest Tech for Screen Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swift-surfing-steps-for-windows-based-network-speed-verification/"><u>Swift Surfing: Steps for Windows-Based Network Speed Verification</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-tips-for-converting-snapshots-directly-from-the-app-for-2024/"><u>Quick Tips for Converting Snapshots Directly From the App for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/sound-sufferers-fix-your-fading-keyboard-tone/"><u>Sound Sufferers! Fix Your Fading Keyboard Tone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-unrivaled-7-best-virtual-meetings-security-centric-ranking/"><u>[Updated] 2024 Approved  Unrivaled 7 Best Virtual Meetings  Security-Centric Ranking</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-overcoming-steam-file-locks/"><u>Swift Strategies for Overcoming Steam File Locks</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-tablet-navigation-in-windows/"><u>Troubleshooting Non-Responsive Tablet Navigation in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-directx-installation-and-upgrades/"><u>The Ultimate Guide to DirectX Installation and Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/title-shaping-desktop-interface-with-icon-distance-manipulation/"><u>Title: Shaping Desktop Interface with Icon Distance Manipulation</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-your-roadmap-to-sourcing-videos-on-social-media-fb-edition/"><u>[Updated] Your Roadmap to Sourcing Videos on Social Media (FB Edition)</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-enhanced-video-playback-and-app-functionality-with-chromes-pip/"><u>Unlock Enhanced Video Playback and App Functionality with Chrome’s PIP</u></a></li>
<li><a href="https://win11.techidaily.com/address-extra-monitor-issue-on-w11-os/"><u>Address Extra Monitor Issue on W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-interruptexceptionnothandled-in-w11-bsods/"><u>Resolving INTERRUPT_EXCEPTION_NOT_HANDLED in W11 BSODs</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-and-fix-hidden-cameras-in-windows-device-hub/"><u>Uncover & Fix Hidden Cameras in Windows' Device Hub</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-address-microsoft-store-monochrome-issue/"><u>Steps to Address Microsoft Store Monochrome Issue</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mix-masters-ideal-dj-videos-to-download/"><u>2024 Approved  Mix Masters  Ideal DJ Videos to Download</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-windows-hello-fingerprint-recognition-issues/"><u>Quick Fixes to Windows Hello Fingerprint Recognition Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-outlook-folder-unreadable-error-steps-for-personal-computers/"><u>Resolve 'Outlook Folder Unreadable' Error: Steps for Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-microsoft-store-use-in-windows-11/"><u>Streamlining Microsoft Store Use in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-bluetooth-pairing-fail-in-windows-devices/"><u>Steps to Tackle Bluetooth Pairing Fail in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-pythons-socket-module-for-windows-network-files/"><u>Utilizing Python's Socket Module for Windows Network Files</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-lost-connection-fixes-for-wifi-failures-in-win11/"><u>Reviving Your Lost Connection: Fixes for Wifi Failures in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-synapse-glitches-in-1011-windows-edition/"><u>Repairing Synapse Glitches in 10/11 Windows Edition</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-fundamentals-of-using-windows-odbc-connectivity/"><u>The Fundamentals of Using Windows' ODBC Connectivity</u></a></li>
</ul></div>
