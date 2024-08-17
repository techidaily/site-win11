---
title: Offline Process for Extra Users in Windows 11
date: 2024-08-15T23:46:01.729Z
updated: 2024-08-16T23:46:01.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Offline Process for Extra Users in Windows 11
excerpt: This Article Describes Offline Process for Extra Users in Windows 11
keywords: Win11 Offline Mode,Extra User Guide,Windows Update Separate,Remote Login Windows,Non-Internet PC Setup,User Access Windows,Offline Computer Support
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## Offline Process for Extra Users in Windows 11

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Once done, type **exit** and press Enter to close the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-efficient-screen-capture-on-mac-with-ingenious-shortcuts/"><u>[New] 2024 Approved  Efficient Screen Capture on Mac with Ingenious Shortcuts</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-10-gaming-tiktokers/"><u>[New] Top 10 Gaming Tiktokers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-elevate-your-hashtag-game-on-instagram-a-comprehensive-guide/"><u>[Updated] Elevate Your Hashtag Game on Instagram  A Comprehensive Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-photographic-magic-the-best-grid-tools-ranked/"><u>2024 Approved  Photographic Magic - The Best Grid Tools Ranked</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/amazon-echo-show-10-3rd-gen-review/"><u>Amazon Echo Show 10 (3Rd Gen) Review</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-antivirus-overkill-in-your-windows-os/"><u>Avoiding Antivirus Overkill in Your Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-computer-writes-on-new-program-placement/"><u>Deciphering Your Computer' Writes on New Program Placement</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-system-usability-in-windows-max-156/"><u>Enhancing File System Usability in Windows (Max 156)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/hashtag-hacks-for-amplifying-gamer-content-for-2024/"><u>Hashtag Hacks for Amplifying Gamer Content for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-14-to-the-previous-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 14 to the Previous iOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-pick-win-friendly-video-coders-wisely/"><u>How to Pick Win-Friendly Video Coders Wisely</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-charting-2023s-social-trend-peaks-in-graphs/"><u>In 2024, Charting 2023'S Social Trend Peaks in Graphs</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-simplified-file-conversion-for-audio-enthusiasts/"><u>In 2024, Simplified File Conversion for Audio Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-connectivity-windows-11-and-mobile-devices-unite/"><u>Innovative Connectivity: Windows 11 & Mobile Devices Unite</u></a></li>
<li><a href="https://win11.techidaily.com/instilling-windows-1011-tools-to-alert-on-new-software-versions/"><u>Instilling Windows 10/11 Tools to Alert on New Software Versions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leading-three-cameras-for-ultra-detailed-videography/"><u>Leading Three Cameras for Ultra-Detailed Videography</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-systems-to-win11-upgrade-essentials/"><u>Legacy Systems to Win11 Upgrade Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-pc-load-tips-for-managing-multimedia-tasks-on-windows/"><u>Minimize PC Load: Tips for Managing Multimedia Tasks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-settings-for-better-device-control/"><u>Navigating Windows 11 Settings for Better Device Control</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-keyboard-precise-text-pasting-hotkeys/"><u>Personalize Your Keyboard: Precise Text Pasting Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-remote-work-fast-and-memory-friendly/"><u>Revitalizing Remote Work: Fast and Memory-Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-data-effective-use-of-powertoys-lockmaster/"><u>Securing Your Data: Effective Use of PowerToys Lockmaster</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-incorporating-copy-and-move-commands-in-win-11/"><u>Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-setting-up-and-activating-the-revo-app-manager/"><u>Step-by-Step Guide: Setting Up & Activating the Revo App Manager</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-windows-update-defeat-error-0x800736cc/"><u>Swiftly Resolving Windows Update: Defeat Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-widget-personalization-on-windows-11-pcs/"><u>The Beginner's Guide to Widget Personalization on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-setting-up-permanent-delete-on-your-windows-11-and-11-pcs/"><u>The Ultimate Guide to Setting up Permanent Delete on Your Windows 11 & 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
</ul></div>
