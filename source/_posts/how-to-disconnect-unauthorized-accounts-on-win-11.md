---
title: How to Disconnect Unauthorized Accounts on Win 11
date: 2025-01-31T01:57:35.196Z
updated: 2025-02-04T09:07:13.240Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  

![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-revolutionizing-remote-work-selecting-the-best-live-streamers/"><u>[Updated] In 2024, Revolutionizing Remote Work Selecting the Best Live Streamers</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-illuminate-focus-leading-lines-in-iphone-composition/"><u>2024 Approved Illuminate Focus Leading Lines in iPhone Composition</u></a></li>
<li><a href="https://os-tips.techidaily.com/breathing-fresh-life-into-your-vintage-iphone-ultimate-guide-for-a-newer-experience/"><u>Breathing Fresh Life Into Your Vintage iPhone - Ultimate Guide for a Newer Experience</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-consistent-note-taking-space-in-windows-11/"><u>Creating a Consistent Note-Taking Space in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-system-performance-by-troubleshooting-devices-dm/"><u>Enhancing System Performance by Troubleshooting Devices (DM)</u></a></li>
<li><a href="https://fox-tips.techidaily.com/essential-techniques-resolving-windows-10-glitches-and-optimizing-system-functionality/"><u>Essential Techniques: Resolving Windows 10 Glitches and Optimizing System Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-refine-user-access-in-windows-environment/"><u>Guidelines to Refine User Access in Windows Environment</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-11-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover iPhone 11 Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-g54-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola G54 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-art-of-amplifying-audience-engagement-on-igtv/"><u>In 2024, The Art of Amplifying Audience Engagement on IGTV</u></a></li>
<li><a href="https://win11.techidaily.com/network-fixation-six-easy-ways-to-get-windows-network-hardware-working-again/"><u>Network Fixation: Six Easy Ways to Get Windows Network Hardware Working Again</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-motorola-moto-g04-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Motorola Moto G04 has been deleted</u></a></li>
<li><a href="https://win11.techidaily.com/restore-the-lost-search-feature-in-windows-11s-tm-environment/"><u>Restore the Lost Search Feature in Windows 11'S TM Environment</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ess-offline-experience-best-playlist-downloader-tools-reviewed/"><u>Seamless Offline Experience Best Playlist Downloader Tools Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/sleuthing-out-stealthy-cyber-menaces-on-pcs/"><u>Sleuthing Out Stealthy Cyber Menaces on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-wi-fi-connectivity-issues-in-winmc-minecraft/"><u>Tackling Wi-Fi Connectivity Issues in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-mechanism-of-winos-gpu-ordering-suspension/"><u>Understanding the Mechanism of WinOS GPU Ordering Suspension</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-weather-app-picks-compiled/"><u>Window's Best Weather App Picks, Compiled</u></a></li>
<li><a href="https://win11.techidaily.com/winning-choices-top-windows-tools-for-video-conversion/"><u>Winning Choices: Top Windows Tools For Video Conversion</u></a></li>
</ul></div>

