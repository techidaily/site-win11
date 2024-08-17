---
title: How to Cut Off Others' Access in the WIndows Network
date: 2024-08-16T00:26:11.045Z
updated: 2024-08-17T00:26:11.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Cut Off Others' Access in the WIndows Network
excerpt: This Article Describes How to Cut Off Others' Access in the WIndows Network
keywords: Windows Network Restrict,Disable Remote Access,Windows Security Control,Limit Network User Access,Block External Windows Users,Secure Windows Networking,Ownership Access Cutoff
thumbnail: https://thmb.techidaily.com/af63d40e10f4812d796851153ffe13a5133162342ccf375cf2e9337e968d99eb.jpg
---

## How to Cut Off Others' Access in the WIndows Network

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-amplify-your-content-navigating-the-world-of-youtube-backlinks/"><u>[New] 2024 Approved  Amplify Your Content  Navigating the World of YouTube Backlinks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-cyberspace-cinema-collector/"><u>[New] 2024 Approved  Cyberspace Cinema Collector</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-macs-choice-of-capture-an-in-depth-look-at-premium-software-for-2024/"><u>[New] Mac's Choice of Capture  An In-Depth Look at Premium Software for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unveiling-the-ultimate-tools-for-high-quality-monitoring/"><u>[New] Unveiling the Ultimate Tools for High-Quality Monitoring</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-reducing-noise-sensitivity-in-logic-pro-mixes/"><u>[Updated] Reducing Noise Sensitivity in Logic Pro Mixes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-avoid-the-fake-out-maintaining-authenticity-in-likes/"><u>2024 Approved  Avoid the Fake-Out  Maintaining Authenticity in Likes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msresourceappname-text-glitch-in-w11/"><u>Addressing 'MsResource/AppName Text' Glitch in W11</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-a-closed-captioning-guru-windows-10-insights/"><u>Becoming a Closed Captioning Guru: Windows 10 Insights</u></a></li>
<li><a href="https://extra-resources.techidaily.com/complete-roadmap-implementing-subtitle-track-within-mp4s/"><u>Complete Roadmap  Implementing Subtitle Track Within MP4s</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-variability-between-offline-and-online-windows-installation-processes/"><u>Delving Into Variability Between Offline and Online Windows Installation Processes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-copy-paste-with-predefined-text-in-w10w11/"><u>Efficient Copy-Paste with Predefined Text in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-apple-iphone-x-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix Apple iPhone X Unavailable Issue With Ease</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-xs-max-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone XS Max Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-tecno-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Tecno Without PUK Codes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-guiding-the-gaze-leading-line-techniques-for-iphones/"><u>In 2024, Guiding the Gaze  Leading Line Techniques for iPhones</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-xiaomi-redmi-13c-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Xiaomi Redmi 13C to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/instantaneously-resolve-wireless-issues-windows/"><u>Instantaneously Resolve Wireless Issues, Windows!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-the-disappeared-disk-space-issue/"><u>Rectify the Disappeared Disk Space Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-keyboard-errors-fixing-function-keys-on-windows-11/"><u>Resolve: Keyboard Errors - Fixing Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-it-administrator-cant-do-more-warning-in-winsec/"><u>Resolving 'IT Administrator Can’t Do More' Warning in WinSec</u></a></li>
<li><a href="https://win11.techidaily.com/running-advanced-ai-on-windows-devices/"><u>Running Advanced AI on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-gaming-on-win-11-via-play-store-linkup/"><u>Seamless Android Gaming on Win 11 via Play Store Linkup</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/smart-buying-guide-key-aspects-to-verify-in-a-pre-owned-ipad/"><u>Smart Buying Guide: Key Aspects to Verify in a Pre-Owned iPad</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-scanning-problems-effectively/"><u>Tackle Windows GeForce Scanning Problems Effectively</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-ultimate-podcast-recording-playbook-a-seamless-process/"><u>The Ultimate Podcast Recording Playbook A Seamless Process</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-spark-10-pro-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Spark 10 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-quickly-resolving-operation-requirement-errors/"><u>Troubleshooting Steps for Quickly Resolving Operation Requirement Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-when-encountering-msxml4dll-is-absent/"><u>Troubleshooting Steps When Encountering 'MsXML4.DLL' Is Absent</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-the-mir4-application-error-on-pcs-steps-to-successful-resolution/"><u>Troubleshooting the MIR4 Application Error on PCs – Steps to Successful Resolution</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-unanswered-calls-a-guide-for-samsung-galaxy-watch-users/"><u>Troubleshooting Unanswered Calls: A Guide for Samsung Galaxy Watch Users</u></a></li>
<li><a href="https://win11.techidaily.com/1719276552494-unlock-windows-free-up-space-no-more-temp-files/"><u>Unlock Windows Free Up Space, No More Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-distinctions-of-windows-terminal-vs-powershell/"><u>Unraveling The Distinctions of Windows Terminal Vs. PowerShell</u></a></li>
</ul></div>
