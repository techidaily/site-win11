---
title: A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
date: 2024-06-25T10:22:00.771Z
updated: 2024-06-26T10:22:00.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
excerpt: This Article Describes A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11
keywords: Win11 Login Halt,Windows 11 Unregister,Session Lockout WIn11,End Non-Registered Sessions,Disable Unauthorized Access,Stop Unlogged Users WIn11,User Account Termination Win11
thumbnail: https://thmb.techidaily.com/698acf9899d7549d0c21beb422c9a4efb393d0c106634028a5e9ccbf41fc2d01.jpg
---

## A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11

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
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-hyper-v-installation-on-w11-home-edition/"><u>Mastering Hyper-V Installation on W11 Home Edition</u></a></li>
<li><a href="https://win11.techidaily.com/setting-custom-keys-for-windows-applications/"><u>Setting Custom Keys for Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-non-existent-drive-letters-on-windows-causes-corrections/"><u>Understanding Non-Existent Drive Letters on Windows: Causes, Corrections</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-bsod-with-vmware-on-win11/"><u>Strategies to Overcome BSOD with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-a-journey-with-the-taskbar-through-time/"><u>Windows UI: A Journey with the Taskbar Through Time</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/file-forwarding-made-easy-top-5-methods-to-upload-directly-on-pc-for-2024/"><u>File Forwarding Made Easy  Top 5 Methods to Upload Directly on PC for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-ranking-the-top-avchd-video-editors/"><u>New In 2024, Ranking the Top AVCHD Video Editors</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-enhancing-film-quality-with-simplified-audio-layer-control-in-premiere-pro-2023/"><u>New In 2024, Enhancing Film Quality with Simplified Audio Layer Control in Premiere Pro 2023</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-exploring-screen-capture-with-apowersoft-no-cost-involved-in-2024/"><u>[Updated] Exploring Screen Capture with Apowersoft, No Cost Involved, In 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/visual-narratives-instagram-carousel-for-2024/"><u>Visual Narratives  Instagram Carousel for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/engaging-audiences-making-popular-youtube-shorts/"><u>Engaging Audiences  Making Popular YouTube Shorts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigate-angular-video-transitions-on-android-devices-for-2024/"><u>Navigate Angular Video Transitions on Android Devices for 2024</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-a-basic-guidebook-to-live-selling-in-todays-digital-world-for-2024/"><u>Updated A Basic Guidebook To Live Selling in Todays Digital World for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-honor-90-gt-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-apple-iphone-12-easily-and-safely-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change GPS Location on Apple iPhone 12 Easily & Safely | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>