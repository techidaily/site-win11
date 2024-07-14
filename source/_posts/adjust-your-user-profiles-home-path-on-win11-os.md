---
title: Adjust Your User Profiles' Home Path on Win11 OS
date: 2024-07-13T11:25:03.252Z
updated: 2024-07-14T11:25:03.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Your User Profiles' Home Path on Win11 OS
excerpt: This Article Describes Adjust Your User Profiles' Home Path on Win11 OS
keywords: Win11 Profile Settings,Change Windows Profile,Update HomePath,Win11 Profile Adjust,HomePath Customize,Win11 User Path Edit,Profiles Update in Win11
thumbnail: https://thmb.techidaily.com/a1f466c594234ad34f641e87364869a2929ae1aee45db635b3f848c5daefbda2.jpg
---

## Adjust Your User Profiles' Home Path on Win11 OS

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
5. Next, click on **I don’t have this person’s sign-in information.**  
![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)

1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

## How to Change the User Profile Folder Name Using the Registry Editor

 You can modify the registry entries associated with your user account to change the user profile folder name in Windows 11\.

 This process involves modifying your registry entries, so we recommend you create a restore point. You can [use the restore point to restore your PC](https://www.makeuseof.com/use-system-restore-windows/) if something goes wrong during the process.

 To change the user profile folder name:

1. Sign out from your current user account and log in with a built-in or newly created administrator account
2. Next, press **Win + R** to open the **Run** dialog.
3. Type **netplwiz** and click **OK** to open the **User Accounts** dialog.
4. Here, select your **user account** and click on **Properties**.  
![User accounts properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-accounts-properties.jpg)
5. In the **User Properties** dialog, you’ll see your **User name** and **Full name.**

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
2. Close the **User Account** dialog and perform a restart.
3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
`wmic useraccount get name,SID`
5. Here, note the **SID** for the user account you want to change the user profile folder name. In this case, the **SID** for the username **tashr** is **S-1-5-21-200486166-247335145-1769094253-1001.**

 Now that we have the SID, we must enter it into the Registry Editor. To do that, follow these steps:

1. Press **Win + R**, type **regedit,** and click **OK** to open **Registry Editor.**
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`
3. Inside the **ProfileList** key, locate and click on the key name identical to the **SID** you noted earlier.
4. In the right pane, right-click on **ProfileImagePath** value and select **Modify**.  
![Modify profile image path in the registry editor.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/modify-profile-image-path-registry-editor.png)
5. Enter a name you want for the profile folder and click **OK**.  
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-saturated-chatgpt-windows-error/"><u>Addressing Saturated ChatGPT Windows Error</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-sleek-and-speedy-the-best-lightweight-video-editing-programs/"><u>Updated Sleek and Speedy The Best Lightweight Video Editing Programs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-charting-the-course-with-youtubes-top-makeup-influencers/"><u>2024 Approved  Charting the Course with YouTube's Top Makeup Influencers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-vivo-y78-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Vivo Y78 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-step-by-step-strategies-for-sizzling-tiktok-videos-via-mac-editing-for-2024/"><u>[Updated] Step-by-Step Strategies for Sizzling TikTok Videos via Mac Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-microsofts-shielded-browsing/"><u>Activating Prints with Microsoft's Shielded Browsing</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-mastering-discord-message-pinning-essentials/"><u>[Updated] 2024 Approved  Mastering Discord  Message Pinning Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-stepwise-approach-to-snagging-youtube-playlists-efficiently/"><u>In 2024, Stepwise Approach to Snagging YouTube Playlists Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-blue-screens-in-your-daily-computing-life/"><u>Beating Back Blue Screens in Your Daily Computing Life</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-youtube-viewing-on-chrome-windows/"><u>Achieving Flawless YouTube Viewing on Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-cursor-signal-strength-in-win-11-os/"><u>Boosting Cursor Signal Strength in Win 11 OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/complete-guide-to-record-google-meet-for-free-as-hostpaticipants/"><u>Complete Guide to Record Google Meet for Free [As Host/Paticipants]</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-honor-90-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-customized-windows-cmd/"><u>Boosting Productivity with Customized Windows Cmd</u></a></li>
<li><a href="https://extra-tips.techidaily.com/bringing-back-windows-photo-viewer-a-quick-guide-for-win-11-users-for-2024/"><u>Bringing Back Windows Photo Viewer  A Quick Guide for Win 11 Users for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-step-into-tomorrow-installation-guide-for-windows-11/"><u>A Step Into Tomorrow  Installation Guide for Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-share-on-apple-iphone-12-pro-drfone-by-drfone-ios/"><u>How to Screen Share on Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-creating-dynamic-time-lapse-with-your-gopro-hero-series-for-2024/"><u>[New] Creating Dynamic Time-Lapse with Your GoPro Hero Series for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-create-music-for-free-top-10-recording-software-options-for-2024/"><u>New Create Music for Free Top 10 Recording Software Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mismatch-of-speaker-assignment-due-to-another-app/"><u>Avoiding Mismatch of Speaker Assignment Due to Another App</u></a></li>
<li><a href="https://win11.techidaily.com/banish-already-in-use-errors-and-unique-device-naming/"><u>Banish 'Already in Use' Errors and Unique Device Naming</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-user-management-via-windows-terminal/"><u>Advanced User Management via Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/boost-performance-using-ntfs-file-compression-wisely/"><u>Boost Performance: Using NTFS File Compression Wisely</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-high-quality-video-capture-for-tech-enthusiasts/"><u>[Updated] 2024 Approved  High-Quality Video Capture for Tech Enthusiasts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-expedite-growth-on-tiktok-with-these-top-strategies/"><u>In 2024, Expedite Growth on TikTok with These Top Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://discord-videos.techidaily.com/key-tips-for-locating-your-preferred-discord-server-for-2024/"><u>Key Tips for Locating Your Preferred Discord Server for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-ultimate-guide-to-banner-and-art-design-for-your-youtube-channel/"><u>In 2024, The Ultimate Guide to Banner & Art Design for Your YouTube Channel</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-tray-displaying-cpu-and-memory-usage/"><u>Boosting System Tray: Displaying CPU & Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-easy-to-use-logo-making-tools-for-everyone-free-download/"><u>In 2024, Easy-to-Use Logo Making Tools for Everyone - FREE Download</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-how-to-nail-your-tweets-with-correct-videos-for-2024/"><u>[Updated] How to Nail Your Tweets with Correct Videos for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-unlock-the-potential-of-your-videos-with-our-comprehensive-list-of-best-free-converters-onlineoffline/"><u>In 2024, Unlock the Potential of Your Videos with Our Comprehensive List of Best Free Converters (Online/Offline)</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-poco-x5-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Poco X5 Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>