---
title: How to Disconnect Unauthorized Accounts on Win 11
date: 2024-12-21T17:37:57.844Z
updated: 2024-12-22T16:41:24.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disconnect Unauthorized Accounts on Win 11
excerpt: This Article Describes How to Disconnect Unauthorized Accounts on Win 11
keywords: Win 11 Account Lockout,Remove Unauthorized Logins,Windows PC Security Hack,Disable Spyware Login,Prevent Unauthorized Access,Secure Win 11 Sign-Ins,Stop Illicit Accounts Win 11
thumbnail: https://thmb.techidaily.com/292b65daa58a3cb7189f78d0565b817f09110724b35903d3b3e9b8eb64f84eb9.jpg
---

## How to Disconnect Unauthorized Accounts on Win 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-verifying-ad-revenue-for-channels/"><u>[New] Verifying Ad Revenue for Channels</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-best-12-screensavers-with-no-time-caps/"><u>[Updated] Best 12 Screensavers with No Time Caps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-netflix-archive-the-complete-guide-to-screencapturing-your-views/"><u>[Updated] In 2024, Netflix Archive The Complete Guide to ScreenCapturing Your Views</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-the-ultimate-filter-guide-to-superior-zoom-quality/"><u>[Updated] In 2024, The Ultimate Filter Guide to Superior Zoom Quality</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-film-making-mastery-guidebook/"><u>2024 Approved Film Making Mastery Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-vibrancy-to-windows-extended-volume-controls/"><u>Bring Back Vibrancy to Windows’ Extended Volume Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bring-holiday-cheer-with-windows-store-gifts/"><u>Bring Holiday Cheer with Windows Store Gifts</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-alive-silent-office-outlook-mail-feeds/"><u>Bringing Alive Silent Office Outlook Mail Feeds</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windowed-world-exiting-wired-networks-at-100mbps/"><u>Bypassing the Windowed World: Exiting Wired Networks at 100Mbps</u></a></li>
<li><a href="https://win11.techidaily.com/changing-functionality-of-fn-keys-in-windows-11-pcs/"><u>Changing Functionality of FN Keys in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-notification-banishment-for-windows-users/"><u>Chrome Notification Banishment for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-verification-failures-when-downloading-apps/"><u>Circumventing Verification Failures when Downloading Apps</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-black-screen-problem-in-windows-marketplace/"><u>Clearing Up Black Screen Problem in Windows Marketplace</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-iphone-14-pro-max-drfone-by-drfone-ios/"><u>How Do You Remove Restricted Mode on iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-dive-into-the-world-of-cosmetics-launching-a-beauty-channel/"><u>In 2024, Dive Into the World of Cosmetics Launching a Beauty Channel</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-realme-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Realme ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win-blog.techidaily.com/mov-m4a-m4b-movavi/"><u>MOV 以及 M4A, M4B 等多種格式的直接 MOVAVI 無限制免費解碼器 - 適用於任何平台的優化</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    