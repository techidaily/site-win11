---
title: "Windows 11: The Art of User Termination"
date: 2024-11-22T21:40:25.110Z
updated: 2024-11-27T18:34:27.051Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: The Art of User Termination"
excerpt: "This Article Describes Windows 11: The Art of User Termination"
keywords: Win11UserExitArt,WindowsTermFlaw,OSUserLockout,PCKillMechTech,EndWinSession,UserEndProcedure,TerminateOSTrick
thumbnail: https://thmb.techidaily.com/34062c0c76761441d1daaab882479cf039a7dd266a5c393fca1f08310200c903.jpg
---

## Windows 11: The Art of User Termination

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/tart-now-best-online-learning-for-new-youtubers-for-2024/"><u>[New] Start Now Best Online Learning for New YouTubers for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-micro-music-moments-character-compositions/"><u>[Updated] Micro-Music Moments Character Compositions</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ing-standout-youtube-thumbnails-with-ease/"><u>Crafting Standout YouTube Thumbnails with Ease</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-steps-to-get-the-latest-toshiba-laptop-drivers-for-your-windows-pc/"><u>Easy Steps to Get the Latest Toshiba Laptop Drivers for Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-lost-wifi-connections-on-windows/"><u>Guidelines for Restoring Lost WiFi Connections on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-does-atandt-handle-international-roaming-charges-and-policies/"><u>How Does AT&T Handle International Roaming Charges and Policies?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-realme-11-pro-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Realme 11 Pro Android SIM Unlock APK</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-textbooks-top-8-effective-learning-techniques-for-windows/"><u>Master the Textbooks: Top 8 Effective Learning Techniques for Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-no-downloads-needed-10-free-online-video-compression-solutions/"><u>New In 2024, No Downloads Needed 10 Free Online Video Compression Solutions</u></a></li>
<li><a href="https://solve-help.techidaily.com/premier-tools-for-precise-ssd-imaging-flawless-data-duplication-apps/"><u>Premier Tools for Precise SSD Imaging: Flawless Data Duplication Apps</u></a></li>
<li><a href="https://win11.techidaily.com/securing-steam-readwrite-success-in-os-x/"><u>Securing Steam Read/Write Success in OS X</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-clearing-black-pixels-in-winsteam/"><u>Techniques for Clearing Black Pixels in WinSteam</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-edge-cutting-edge-visual-notes-methodology/"><u>The Obsidian Edge: Cutting-Edge Visual Notes Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-solutions-for-overcoming-hypervisorbsod-in-windows/"><u>Top 5 Solutions for Overcoming HYPERVISOR_BSOD in Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-7-utilities-for-tailoring-and-enhancing-your-macs-user-interface/"><u>Top 7 Utilities for Tailoring and Enhancing Your Mac's User Interface</u></a></li>
<li><a href="https://sound-issues.techidaily.com/trouble-free-methods-correcting-error-in-playing-test-audio-signal/"><u>Trouble-Free Methods: Correcting Error in Playing Test Audio Signal</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-potential-with-top-notch-fps-counters-for-windows-11-gamers/"><u>Unleashing Your Potential with Top-Notch FPS Counters for Windows 11 Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-pc-potential-top-tips-to-troubleshoot-broken-keyboard-commands-in-windows/"><u>Unlocking PC Potential: Top Tips to Troubleshoot Broken Keyboard Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-character-viewer-in-windows-11/"><u>Unveiling the Character Viewer in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    