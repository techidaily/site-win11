---
title: How to Cut Off Others' Access in the WIndows Network
date: 2024-07-13T10:07:52.930Z
updated: 2024-07-14T10:07:52.930Z
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
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-zte-blade-a73-5g-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from ZTE Blade A73 5G</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-writable-html-in-email-settings/"><u>Addressing Windows 11' Writable HTML in Email Settings</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-ultimate-list-of-video-editing-essentials-incorporating-soundtracks-from-the-most-popular-platforms/"><u>New 2024 Approved The Ultimate List of Video Editing Essentials Incorporating Soundtracks From the Most Popular Platforms</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-oppo-find-n3-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Oppo Find N3 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-typing-speed-7-latency-fixes-revealed/"><u>Enhance Windows 11 Typing Speed: 7 Latency Fixes Revealed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-optimal-screen-record-settings-for-facetime-conversations/"><u>[Updated] In 2024, Optimal Screen Record Settings for FaceTime Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-hibernate-depression-in-windows/"><u>Combatting Hibernate Depression in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-vanished-panes-top-strategies-to-recover-off-screen-apps-on-win-10/"><u>Breathe Life Into Vanished Panes! Top Strategies to Recover Off-Screen Apps on Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-corrupted-filesystems-in-windows-11/"><u>Correcting Corrupted Filesystems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-peace-sleep-functions-in-windows/"><u>Bringing Peace: Sleep Functions in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-fcpx-xml-essentials-what-you-need-to-know-for-2024/"><u>Updated FCPX XML Essentials What You Need to Know for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-easily-implemented-phonetic-adjustment-features-exploration-of-functions-regulations-and-diverse-methods/"><u>Updated Easily Implemented Phonetic Adjustment Features Exploration of Functions, Regulations, and Diverse Methods</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-restrictive-settings-from-steam-libraries-win-11/"><u>Eradicating Restrictive Settings From Steam Libraries Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-reno-11f-5g-phone-without-google-account-by-drfone-android/"><u>How to Unlock Oppo Reno 11F 5G Phone without Google Account?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-techniques-to-ensure-uninterrupted-video-capturing/"><u>[Updated] In 2024, Techniques to Ensure Uninterrupted Video Capturing</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-motorola-moto-g23-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Motorola Moto G23 phone? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/top-3-best-mp3-volume-boosters-online/"><u>Top 3 Best MP3 Volume Boosters Online</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-file-access-failures-in-windows/"><u>Correcting File Access Failures in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-motorola-razr-40-ultra-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Motorola Razr 40 Ultra FRP</u></a></li>
<li><a href="https://win11.techidaily.com/assigning-custom-codes-to-windows-software/"><u>Assigning Custom Codes to Windows Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-superior-sound-capture-insiders-list-of-the-best-9-microphones-online/"><u>2024 Approved  Superior Sound Capture  Insider's List of the Best 9 Microphones Online</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-macs-finest-the-ultimate-mp3-conversion-software-roundup/"><u>Updated In 2024, Macs Finest The Ultimate MP3 Conversion Software Roundup</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-shoot-and-score-top-techniques-for-great-youtube-cinematography/"><u>In 2024, Shoot and Score  Top Techniques for Great YouTube Cinematography</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-powerful-tools-for-windows-users/"><u>Conjuring Powerful Tools for Windows Users</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-handle-installation-hiccups-win11/"><u>Clearing Up Confusion: How to Handle Installation Hiccups (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-beginners-guide-to-github-desktop-for-windows-users/"><u>A Compreenas Beginners Guide to GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-ip-command-prompt-guide-for-pcs/"><u>Discover Your IP: Command Prompt Guide for PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unveiling-the-secrets-to-verified-instagram-images-for-2024/"><u>[Updated] Unveiling the Secrets to Verified Instagram Images for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleash-your-stream-potential-on-youtube-with-just-a-handful-of-followers/"><u>2024 Approved  Unleash Your Stream Potential on YouTube with Just a Handful of Followers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-how-to-record-youtube-videos/"><u>2024 Approved  How to Record YouTube Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-add-cinematic-shake-to-images-using-ps/"><u>2024 Approved  Add Cinematic Shake to Images Using PS</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-office-hours-the-top-5-task-boosting-tools-for-win-11/"><u>Elevate Your Office Hours: The Top 5 Task-Boosting Tools for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/digging-into-drive-labels-c-and-d-unpacked/"><u>Digging Into Drive Labels: C & D Unpacked</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-rearranged-letters-in-windows-system/"><u>Eradicating Rearranged Letters in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-achieving-caption-excellence-an-overview-of-premium-internet-tools/"><u>[Updated] Achieving Caption Excellence  An Overview of Premium Internet Tools</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/clear-your-screen-clutter-advanced-window-organization-win11-and-10/"><u>Clear Your Screen Clutter: Advanced Window Organization (Win11 & 10)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-crafting-compelling-narratives-with-spotify-ads/"><u>[New] Crafting Compelling Narratives with Spotify Ads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-poco-c65-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Poco C65 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-navigating-the-social-sea-identifying-unfollowers-on-instagram/"><u>[New] 2024 Approved  Navigating the Social Sea  Identifying Unfollowers on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
</ul></div>
