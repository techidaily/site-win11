---
title: Severing Non-Primary Users in the Windows Ecosystem
date: 2024-06-25T11:28:04.703Z
updated: 2024-06-26T11:28:04.703Z
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
<li><a href="https://win11.techidaily.com/reviving-access-tackling-onedrive-logins-in-windows/"><u>Reviving Access: Tackling OneDrive Logins in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/whats-in-store-for-windows-11-with-update-22h2/"><u>What's in Store for Windows 11 with Update #22H2?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-connection-issue-on-windows-os/"><u>Fixing No Connection Issue on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-non-interactive-components-on-windows-11/"><u>How to Resolve Non-Interactive Components on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-program-commands-keybinding-setup/"><u>Windows Program Commands: Keybinding Setup</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-transfer-files-on-a-network-using-a-python-server-on-windows/"><u>How to Transfer Files on a Network Using a Python Server on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-windows-event-viewer-fixes/"><u>Strategies for Windows Event Viewer Fixes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/uniting-friends-across-operating-systems-with-skype-groups-for-2024/"><u>Uniting Friends Across Operating Systems with Skype Groups for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-achieve-filmic-quality-a-guide-to-cinematic-editing-in-fcpx/"><u>Updated 2024 Approved Achieve Filmic Quality A Guide to Cinematic Editing in FCPX</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-poco-c51-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Poco C51 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-essential-guide-to-editing-youtube-videos-seamlessly-in-imovie/"><u>[Updated] The Essential Guide to Editing YouTube Videos Seamlessly in iMovie</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-vita-video-editor-experience-full-review-and-guide-2024/"><u>[Updated] The Ultimate Vita Video Editor Experience  Full Review & Guide 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-stop-motion-magic-on-instagram-tips-and-tricks/"><u>Updated Stop Motion Magic on Instagram Tips and Tricks</u></a></li>
<li><a href="https://extra-tips.techidaily.com/budget-friendly-miniature-aerials-review-for-2024/"><u>Budget-Friendly Miniature Aerials Review for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-organic-scenes-essential-free-templates-to-elevate-filmmaking-art/"><u>2024 Approved  Organic Scenes  Essential, Free Templates to Elevate Filmmaking Art</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-poco-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Poco Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-harnessing-the-power-of-animated-graphics/"><u>[New] Harnessing the Power of Animated Graphics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>