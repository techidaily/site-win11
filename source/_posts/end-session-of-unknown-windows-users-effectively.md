---
title: End Session of Unknown Windows Users Effectively
date: 2024-07-13T11:00:01.087Z
updated: 2024-07-14T11:00:01.087Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/updated-mastering-profits-a-comprehensive-vimeo-revenue-strategy/"><u>[Updated] Mastering Profits  A Comprehensive Vimeo Revenue Strategy</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-preserve-audio-perfection-how-to-convert-video-to-mp3-without-quality-loss/"><u>Updated 2024 Approved Preserve Audio Perfection How to Convert Video to MP3 without Quality Loss</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-non-functional-window-11-menu-bar/"><u>Tackling Non-Functional Window 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-thx-audio-functionality-in-windows/"><u>Restoring Lost THX Audio Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/superior-pc-weather-apps-selection/"><u>Superior PC Weather Apps Selection</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlining-atheros-network-interface-updates-in-windows-11/"><u>Streamlining Atheros Network Interface Updates in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-insta-popularity-on-youtube-jake-pauls-story-unfolded/"><u>2024 Approved  Insta-Popularity on Youtube  Jake Paul’s Story Unfolded</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-harmonizing-hertz-techniques-for-consistent-audio-levels-across-video-media-for-2024/"><u>New Harmonizing Hertz Techniques for Consistent Audio Levels Across Video Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamlining-your-personal-library-from-spotify-to-youtube-music-for-2024/"><u>Streamlining Your Personal Library  From Spotify, To YouTube Music for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ten-strategies-to-keep-windows-safe-without-bitlocker-support/"><u>Ten Strategies to Keep Windows Safe without Bitlocker Support</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-intel-network-adapters-on-pcs/"><u>Step-by-Step: Setting Up Intel Network Adapters on PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-views-tabbing-in-windows-explorer/"><u>Streamlining Data Views: Tabbing in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-simple-steps-to-make-ipad-screen-captures-a-breeze/"><u>[New] Simple Steps to Make iPad Screen Captures a Breeze</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-crafting-spectacular-time-lapses-with-gopro-hero5-black/"><u>In 2024, Crafting Spectacular Time-Lapses with GoPro Hero5 Black</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80246007-in-windows-11s-update-process/"><u>Tackling Error 0X80246007 in Windows 11'S Update Process</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unbeatable-method-for-permanent-bio-link-integration-in-tiktok/"><u>[New] Unbeatable Method for Permanent Bio-Link Integration in TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-defenses-adding-firewall-to-the-context-menu/"><u>Streamlining Windows 11 Defenses: Adding Firewall to the Context Menu</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/from-novice-to-pro-an-extensive-guide-to-capturing-top-notch-audio-on-zoom-for-2024/"><u>From Novice to Pro  An Extensive Guide to Capturing Top-Notch Audio on Zoom for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-giggle-o-meter-rising-top-tiktok-joke-threads-for-laughter/"><u>[New] Giggle-O-Meter Rising  Top TikTok Joke Threads for Laughter</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-top-best-5-free-mpeg-video-joiners/"><u>2024 Approved Top Best 5 Free MPEG Video Joiners</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-superior-online-forums-and-boards/"><u>[Updated] In 2024, Superior Online Forums and Boards</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-blocking-unwanted-youtube-channels-pc-and-mobile-edition/"><u>[Updated] In 2024, Blocking Unwanted Youtube Channels  PC & Mobile Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-whisperer-guide-to-win11-menu-hiding/"><u>The Silent Whisperer Guide to Win11 Menu Hiding</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rectifying-windows-alt-key-problems-46-characters/"><u>Strategies for Rectifying Windows ALT Key Problems (46 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-samsung-galaxy-a14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-alternatives-and-step-by-step-guide-for-apowersoft-audio-recorder/"><u>In 2024, Alternatives and Step by Step Guide for Apowersoft Audio Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-tecno-pop-8-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Tecno Pop 8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-freezing-windows-netflix-interface/"><u>Reviving Freezing Windows Netflix Interface</u></a></li>
</ul></div>
