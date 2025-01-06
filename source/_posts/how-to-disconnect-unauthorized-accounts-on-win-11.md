---
title: How to Disconnect Unauthorized Accounts on Win 11
date: 2024-12-30T20:39:34.039Z
updated: 2025-01-06T19:21:07.523Z
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

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/ed-deciphering-digital-marketing-the-power-of-youtube-keywords-for-2024/"><u>[Updated] Deciphering Digital Marketing The Power of YouTube Keywords for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/affordable-4k-hd-hisense-50-inch-tv-review-the-best-value-in-large-screens/"><u>Affordable 4K HD Hisense 50-Inch TV Review: The Best Value in Large Screens</u></a></li>
<li><a href="https://tech-revival.techidaily.com/battle-of-creativity-determining-top-chatbots-mastery-with-a-common-creative-challenge/"><u>Battle of Creativity: Determining Top Chatbot's Mastery with a Common Creative Challenge</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722978378333-easy-update-process-for-epson-printers-on-windows-10-find-out-now/"><u>Easy Update Process for Epson Printers on Windows 10 - Find Out Now!</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-of-resources-windows-application-size/"><u>Efficient Use of Resources: Windows Application Size</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-how-to-fix-errors-on-windows-11/"><u>Ensuring a Valid Temp Directory: How to Fix Errors on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-game-audio-issues-a-2024-roadmap-for-pc-gamers/"><u>Fixing Game Audio Issues: A 2024 Roadmap for PC Gamers</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-locked-iphone-xs-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>Forgot Locked iPhone XS Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80073d26-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error 0X80073D26 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-couldnt-be-installed-on-the-microsoft-store/"><u>How to Fix This App Couldn’t Be Installed on the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-fix-the-0x80071a90-windows-problem/"><u>How to Quickly Fix the 0X80071a90 Windows Problem</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/in-2024-free-msnbc-live-online-stream-for-the-latest-shows-for-all-devices/"><u>In 2024, Free MSNBC Live Online Stream for the Latest Shows for All Devices</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-master-videoleap-to-capture-up-close-footage/"><u>In 2024, Master Videoleap to Capture Up-Close Footage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/inside-windows-10-a-snapshot-of-its-transformation-for-2024/"><u>Inside Windows 10 A Snapshot of Its Transformation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-enhancing-win-11s-context-menu/"><u>Mastering the Art of Enhancing Win 11'S Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-winget-efficiency-on-modern-windows-pcs/"><u>Resurrecting Winget Efficiency on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-windows-11-icons-to-their-full-form/"><u>Revive Your Windows 11 Icons to Their Full Form</u></a></li>
<li><a href="https://win11.techidaily.com/securely-delete-files-at-the-click-setting-up-a-trash-bin-for-permanent-deletion-in-windows-pcs-11/"><u>Securely Delete Files at the Click: Setting up a Trash Bin for Permanent Deletion in Windows PCs (11)</u></a></li>
<li><a href="https://win-online.techidaily.com/mpgwmv-wmf-movavi/"><u>영구인 MPG/WMV를 전자보감 WMF로 대체 - Movavi 솔루션</u></a></li>
</ul></div>

