---
title: "Win 11: Rename Your User Account Directory"
date: 2024-07-13T10:21:10.228Z
updated: 2024-07-14T10:21:10.228Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Rename Your User Account Directory"
excerpt: "This Article Describes Win 11: Rename Your User Account Directory"
keywords: Win XP Renaming,Win PC NewName,QuickWinRenameUser,ChangePCDirectory,SetWinAccountPath,XPUserRenamingTip,WindowsUserDirChange
thumbnail: https://thmb.techidaily.com/2597cd92a0acd8548892430a7d1a31aad74db81001d653dab278938ebfa823a1.jpg
---

## Win 11: Rename Your User Account Directory

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-final-countdown-for-windows-xp-7-and-81-lifeline-on-microsoft/"><u>The Final Countdown for Windows XP, 7 & 8.1 Lifeline on Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-net-not-installed-app-warning/"><u>Solving Windows' .NET Not Installed App Warning</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-5-cameras-for-precision-slow-mo/"><u>[New] Prime 5 Cameras for Precision Slow-Mo</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1715859834138-new-navigating-through-top-ps2-games-on-android-devices-a-compre-written-in-english/"><u>[New] Navigating Through Top PS2 Games on Android Devices - A Compre Written in English.</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-high-def-monitor-list-top-10-picks/"><u>In 2024, The Ultimate High-Def Monitor List  Top 10 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-code-navigating-through-lost-windows-1110-patches/"><u>Unlock the Code: Navigating Through Lost Windows 11/10 Patches</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-10-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 10 & 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/capture-call-transcript-for-study-for-2024/"><u>Capture Call Transcript for Study for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-curbing-virtual-disk-service-malfunction/"><u>Strategies: Curbing Virtual Disk Service Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/unique-visuals-for-your-window-terminal/"><u>Unique Visuals for Your Window Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-grant-write-access-for-steam-folders-in-win-11/"><u>Techniques to Grant Write Access for Steam Folders in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winmedia-server-error/"><u>Troubleshooting WinMedia Server Error</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-a-deep-dive-into-digital-platform-wealth-dailymotion-and-youtube-comparison/"><u>2024 Approved  A Deep-Dive Into Digital Platform Wealth  Dailymotion & YouTube Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/neutralizing-windows-update-triggers/"><u>Neutralizing Windows Update Triggers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-write-error-in-windows-11-os/"><u>Resolving File Write Error in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-scheduler-issues-restore-smoothness/"><u>Tackle Windows Scheduler Issues, Restore Smoothness</u></a></li>
<li><a href="https://win11.techidaily.com/must-remember-tips-for-clean-installation-of-windows/"><u>Must-Remember Tips for Clean Installation of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-unseen-the-emergence-of-ai-futures/"><u>Windows Unseen: The Emergence of AI Futures</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-repairing-your-windows-headsets-microphone/"><u>Addressing and Repairing Your Windows Headset's Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-display-driver-found-on-windows-11/"><u>Overcoming No Display Driver Found on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-realme-gt-5-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Realme GT 5 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-issue-0xca00a009/"><u>Overcoming Windows Update Issue #0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pc-transferring-preferences-from-one-to-another/"><u>Securing Your PC: Transferring Preferences From One to Another</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://win11.techidaily.com/boost-typing-prowess-changing-and-adding-keyboards-for-win-11/"><u>Boost Typing Prowess: Changing and Adding Keyboards for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-how-to-view-excel-files-in-notepad/"><u>Tips: How to View Excel Files in Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/1719363401331-win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again!</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-desktop-menus-in-win-1011/"><u>Troubleshooting Non-Responsive Desktop Menus in Win 10/11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-shaky-to-steady-mastering-video-stabilization-in-after-effects/"><u>New From Shaky to Steady Mastering Video Stabilization in After Effects</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-you-play-mp4-on-samsung-galaxy-f34-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can you play MP4 on Samsung Galaxy F34 5G?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-the-code-to-content-creator-commerce-with-carminati-ajay/"><u>[New] Unlocking the Code to Content Creator Commerce with Carminati (AJay)</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-inaccessible-secure-boot-in-windows-bios/"><u>Solving the Puzzle of Inaccessible Secure Boot in Windows BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workday-the-top-5-apps-to-skyrocket-windows-efficiency/"><u>Optimize Your Workday: The Top 5 Apps to Skyrocket Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-techniques-for-effective-qr-scanning-on-pcs/"><u>Pioneering Techniques for Effective QR Scanning on PCs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-how-to-do-voiceover-on-tiktok-in-2024/"><u>[New] How to Do Voiceover on TikTok, In 2024</u></a></li>
</ul></div>
