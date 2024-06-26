---
title: Severing Non-Primary Users in the Windows Ecosystem
date: 2024-06-25T10:00:03.246Z
updated: 2024-06-26T10:00:03.246Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Severing Non-Primary Users in the Windows Ecosystem
excerpt: This Article Describes Severing Non-Primary Users in the Windows Ecosystem
keywords: Non-Windows Users Separation,Primary Windows Users First,Windows Primaries Priority,Eliminate Non-Users,Windows Core User Focus,Exclude External OS Users,Windows Ecosystem Maintenance
thumbnail: https://thmb.techidaily.com/8a48baa92cdc76a86f454f4bf37afbb0816527695359221f913b5285fa5c2939.jpg
---

## Severing Non-Primary Users in the Windows Ecosystem

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-no-notification-policy-for-ws11-cameras/"><u>Bypassing No-Notification Policy for WS11 Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-pristine-windows-display-perfection/"><u>Crafting Pristine Windows Display Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-network-shield-controls-on-windows/"><u>Mastering Network Shield Controls on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-streaming-fb-video-content-on-television-devices/"><u>[New] Streaming FB Video Content On Television Devices</u></a></li>
<li><a href="https://techidaily.com/top-iphone-15-pro-message-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top iPhone 15 Pro Message Recovery Software | Stellar</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-switching-picture-in-picture-on-macios-effortlessly/"><u>[Updated] Switching Picture-in-Picture on Mac/iOS Effortlessly</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-vidvault-prodigies-mastering-the-download-of-tweeted-videos-for-2024/"><u>[Updated] VidVault Prodigies  Mastering the Download of Tweeted Videos for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-proportions-a-guide-to-video-aspect-ratios/"><u>2024 Approved  Ideal Proportions  A Guide to Video Aspect Ratios</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-cutting-edge-notebooks-and-tools-to-elevate-your-editing-game/"><u>[New] Cutting Edge  Notebooks and Tools to Elevate Your Editing Game</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-offering-the-best-understanding-of-performing-imovie-slow-motion-video/"><u>New Offering The Best Understanding of Performing iMovie Slow Motion Video</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-rhythm-revolution-tiktoks-newest-and-most-popular-rap-hits/"><u>[Updated] 2024 Approved  Rhythm Revolution  TikTok's Newest and Most Popular Rap Hits</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-tiktok-to-facebook-social-media-linking-guide/"><u>[New] In 2024, TikTok-to-Facebook Social Media Linking Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-foremost-6-online-spaces-dominating-b2b-interactions/"><u>In 2024, Foremost 6 Online Spaces Dominating B2B Interactions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>