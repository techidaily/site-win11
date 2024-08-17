---
title: End Session of Unknown Windows Users Effectively
date: 2024-08-15T23:35:00.286Z
updated: 2024-08-16T23:35:00.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes End Session of Unknown Windows Users Effectively
excerpt: This Article Describes End Session of Unknown Windows Users Effectively
keywords: Windows Security Halt,Unauthorized Stop,End Windows Breach,Cease User Access,Lockdown Unknown PCs,Shut Down Anomalies,Terminate Suspicious Users
thumbnail: https://thmb.techidaily.com/848032c0813eed1e619997cdd0bea2d2fe7603582b1ae72dd2c30508b513eea6.png
---

## End Session of Unknown Windows Users Effectively

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-stream.techidaily.com/new-selective-screen-time-topping-youtube-movies/"><u>[New] Selective Screen Time  Topping YouTube Movies</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-the-development-and-application-of-vr-shopping-for-2024/"><u>[New] The Development and Application of VR Shopping for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-gain-momentum-with-these-strategies-for-trending-youtubers/"><u>[Updated] In 2024, Gain Momentum with These Strategies for Trending YouTubers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-tailoring-your-multi-task-experience-safe-area-and-pip-settings/"><u>[Updated] In 2024, Tailoring Your Multi-Task Experience  Safe Area & PIP Settings</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-integrated-sound-system-guidebook/"><u>[Updated] Integrated Sound System Guidebook</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigate-effortlessly-to-your-favorite-facebook-videos-with-these-top-addons-for-2024/"><u>[Updated] Navigate Effortlessly to Your Favorite Facebook Videos With These Top Addons for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-progression-of-vegaspro-through-its-2019-updates/"><u>[Updated] The Progression of VegasPro Through Its 2019 Updates</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-thrifty-filmmakers-action-camera-options/"><u>[Updated] Thrifty Filmmaker's Action Camera Options</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-unlock-your-creative-potential-top-7-hidden-tiktok-emojis/"><u>[Updated] Unlock Your Creative Potential  Top 7 Hidden TikTok Emojis</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-navigating-through-troubled-waters-instagram-videos-guide/"><u>2024 Approved  Navigating Through Troubled Waters  Instagram Videos Guide</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://games-able.techidaily.com/blend-into-the-background-how-to-be-offline-on-steam/"><u>Blend Into the Background: How to Be Offline on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://extra-resources.techidaily.com/curriculum-videos-top-tips-for-classroom-edits/"><u>Curriculum Videos  Top Tips for Classroom Edits</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/excellent-5-video-monitors-for-ps5-players/"><u>Excellent 5 Video Monitors for PS5 Players</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-meizu-21-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-video-buffer-issues-streamlined-vlc-on-pc/"><u>Fixing Video Buffer Issues: Streamlined VLC on PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/flawless-picture-preservation-gratis-space-plus-charged-cloud-sanctuaries-await-for-2024/"><u>Flawless Picture Preservation  Gratis Space + Charged Cloud Sanctuaries Await for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reestablish-network-connection-after-failure-in-windows-11/"><u>How to Reestablish Network Connection After Failure in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-windows-hdr-capabilities-for-cutting-edge-video-workflows/"><u>In 2024, Unlocking Windows' HDR Capabilities for Cutting-Edge Video Workflows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unmasking-imagerys-origins-a-complete-guide-to-reverse-picture-searching-in-instagram/"><u>In 2024, Unmasking Imagery's Origins  A Complete Guide to Reverse Picture Searching in Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-for-a-macos-feel-in-windows/"><u>Mastering Window Customization for a macOS Feel in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-administrator-settings-in-windows-security/"><u>Navigating Administrator Settings in Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-previous-windows-configurations/"><u>Quick Guide to Restoring Previous Windows Configurations</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-over-silent-slack-alerts-in-win-11/"><u>Regain Control Over Silent Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-no-connection-found-on-win-810/"><u>Remedying No Connection Found on Win 8/10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/samsung-galaxy-chromebook-2-analysis-a-compact-powerhouse-for-on-the-go-work/"><u>Samsung Galaxy Chromebook 2 Analysis - A Compact Powerhouse for On-the-Go Work</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-snaps-windows-strategies-for-sticky-notes/"><u>Secure Your Snaps: Windows Strategies for Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-alternative-pdf-printer-in-windows/"><u>Setting Alternative PDF Printer in Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/step-by-step-method-for-increasing-your-portable-pcs-ram/"><u>Step-By-Step Method for Increasing Your Portable PC's Ram</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ruth-behind-asmr-video-enthusiasm/"><u>The Truth Behind ASMR Video Enthusiasm</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-androidpc-junctioning/"><u>The Ultimate Guide to Android/PC Junctioning</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-past-connections-discovering-friends-timelines/"><u>Unveiling Past Connections: Discovering Friends' Timelines</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-shouldnt-use-ai-chatbots-to-generate-windows-11-keys/"><u>Why You Shouldn’t Use AI Chatbots to Generate Windows 11 Keys</u></a></li>
</ul></div>
