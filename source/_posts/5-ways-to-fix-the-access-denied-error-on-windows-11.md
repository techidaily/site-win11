---
title: 5 Ways to Fix the “Access Denied” Error on Windows 11
date: 2024-07-13T11:06:35.350Z
updated: 2024-07-14T11:06:35.350Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Fix the “Access Denied” Error on Windows 11
excerpt: This Article Describes 5 Ways to Fix the “Access Denied” Error on Windows 11
keywords: Windows 11 Access Errors,Denied Login Fixes,Win11 Permissions,Access Issue Resolution,Fixing User Rights,Windows 11 Error Triggers,Correcting Access Issues
thumbnail: https://thmb.techidaily.com/614e0e5c423fbfce776b4242bea85cadda084bd0ef851e6cf9024dcc8525ee26.jpg
---

## 5 Ways to Fix the “Access Denied” Error on Windows 11

### Quick Links

* [Why Are You Getting the "Access Denied" Error?](#why-are-you-getting-the-quot-access-denied-quot-error)
* [Check the Filesystem's Permissions](#check-the-filesystem-39-s-permissions)
* [Set Your Account to Administrator](#set-your-account-to-administrator)
* [Enable the Hidden Administrator Account](#enable-the-hidden-administrator-account)
* [Take Ownership of the File](#take-ownership-of-the-file)
* [Disable Your Third-Party Antivirus Software](#disable-your-third-party-antivirus-software)

### Key Takeaways

* The "Access Denied" error on Windows 11 indicates a lack of permissions. Check system permissions and grant full control to your user account.
* Make your account the computer's administrator to fix Access Denied errors. Set the account to an admin in User Accounts settings to gain access.
* You can also enable the hidden Administrator account in Windows 11 for unrestricted access to files and folders. Switch to this account to bypass severe access problems.

 When you encounter the "Access Denied" error in Windows 11, it can feel like you're being locked out of your own computer. While having trouble accessing your files, directories, and folders is frustrating, don't panic—with a few simple tweaks, you can regain access to your system.

## Why Are You Getting the "Access Denied" Error?

 The Access Denied error is a common issue on Windows systems that indicates you don't have permission to view a file or folder. This is because your system has not granted access to that directory for the user account you're currently using. Simply put, you're using an unauthorized account to access paths, folders, and files on your computer or external drives from other computers.

 In some cases, ownership issues and file encryptions can also lead to this error. It's also possible that your third-party antivirus software has prohibited access. Some programs can mistake a genuine setup wizard as a threat—usually a false positive detection.

 Below are some common fixes for the Access Denied error on Windows 11\.

## 1\. Check the Filesystem's Permissions

 This is a simple solution you can try to ensure your account has the proper access to the file or folder you are opening:

1. Locate the file, folder, or directory you are trying to access. Right-click on it and choose **Properties** from the menu.
2. Go to the **Security** tab and click the **Edit**button.  
![The Security tab under Properties of a File on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-properties.png)
3. Choose your username from the list and check the box beside **Full control** in the **Allow** column under the **Permissions for User** section. Then, click **OK**.  
![A screenshot showing the settings for changing permissions for users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/user-settings.png)

**Note:** If your username is not on the list, you have to add it manually and then change its permissions.

 You can also try [restoring the default permissions using the icacls command](https://www.makeuseof.com/reset-user-permissions-default-windows/) in Command Prompt. Resetting permissions with **icacls** can help resolve access issues caused by changes to the default permissions.

## 2\. Set Your Account to Administrator

 In most cases, the Access Denied error can be fixed by making your user account a computer administrator. Here's how you can set your account to admin:

1. Press **Win** \+ **R** to open **Run**. Type **control userpasswords2** and click **OK.**
2. On the **User Accounts** window, check the box beside **Users must enter a username and password to use this computer**. If this isn't present, skip this step.  
![The users tab displaying users in a computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/the-users-tab-displaying-users-in-a-computer.png)
3. Select your account and click the **Properties** button below it.
4. Next, go to the **Group Membership** tab. Choose **Administrator** from the menu, then click **Apply** and **OK**.  
![Group membership tab for selecting standard user or administrator account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/group-membership-tab-for-selecting-standard-user-or-administrator-account.png)

 Now, restart your computer and see if it resolves the problem. Otherwise, move to the next step.

## 3\. Enable the Hidden Administrator Account

 Your Windows 11 system has a hidden administrator account with more privileges than a regular account. You can enable this to access files, folders, and paths restricted to regular users—it's especially helpful if you're [unable to switch your user account from standard to administrator](https://www.makeuseof.com/cannot-change-account-type-administrator-windows/).

1. Open Windows search by pressing **Win** \+ **S**.
2. Next, type **CMD**, right-click Command Prompt, and click **Run as administrator.**
3. On the Command Prompt, run the following command: **net user administrator /active:yes**. This will unlock the administrator account.  
![Prompt for enabling the hidden admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/prompt-for-enabling-the-hidden-admin-account-in-windows.png)
4. Log off the current account and switch to the newly enabled Administrator account. Using this account, you won't run into access problems, as it has more privileges than a normal admin account.
5. Once you're done with the Administrator account, log off and sign into your main account again. Repeat steps 1 and 2, then run this command: **net user administrator /active:no.** This will disable the Administrator account.

 Switching back to your main account will cause the error to appear again. If you need to constantly access the files, use the hidden Administrator account to make the necessary changes to your system and fix the ownership or access issue. You might also consider copying the items to another location your usual account can access.

## 4\. Take Ownership of the File

 As mentioned previously, the "Access Denied" error sometimes stems from ownership problems. If this is the cause of the error, [taking ownership of the file](https://www.makeuseof.com/windows-10-11-own-folder/) can instantly give you the access you need:

1. Locate the folder or file you want to access and right-click on it. Click **Properties** from the menu.
2. Go to the **Security** tab and click the **Advanced** button.  
![Security tab in the Properties tab of a file in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/security-tab-in-the-properties-tab-of-a-file-in-windows.png)
3. Next, look for the **Owner** section on the top of the window and click **Change**. This will open a new dialog box.  
![Permissions page for a file in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/permissions-page-for-a-file-in-windows-11.png)
4. In the **Select User or Group** window, type your username or **Administrators** in the **Enter the object name** field.  
![Select user or group tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/select-user-or-group-tab.png)
5. Then, click the **Check Names** and **OK** buttons to save your changes.  
![Select user or group tab for a file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/select-user-or-group-tab-for-a-file.png)
6. Next, click **Apply.**
7. You'll see a Windows Security prompt. Click **OK**.
8. In the main interface, click **OK** to save changes.

 Apart from doing it manually, you can also take ownership of the file using the Command Prompt. Follow the steps below if you prefer typing commands instead:

1. Open Command Prompt through Windows search by pressing **Win** \+ **S** and typing **CMD**. Click **Run as administrator** in the Command Prompt tab from the result.
2. In the Command Prompt, type or paste the following commands and press **Enter** after each:  
   * **takeown /f "path\_to\_folder"/r /d y**  
   * **icacls "path\_to\_folder"/grant administrators:F /t**

 You need to replace the "path\_to\_folder" section with the path to the inaccessible file or folder. Here's how you can obtain the path:

1. Navigate to the file or folder in question.
2. Right-click it and select **Copy as path**.
3. Replace "path\_to\_folder" with the copied path. For instance, **"C:\\Users\\HP\\Downloads\\Literature review sources"**  
![Prompt for taking ownership of a file via CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/prompt-for-taking-ownership-of-a-file-via-cmd.png)

 Restart your computer once you're done with the steps above to check if the problem is resolved. But usually, after running these commands, you should regain access to the files and folders.

## 5\. Disable Your Third-Party Antivirus Software

 On the off chance that the issue isn't resolved, consider turning off your third-party antivirus software.

[Antivirus software is necessary to protect your system](https://www.makeuseof.com/do-you-need-antivirus-protection/) from threats and malicious actors. However, it can cause errors, such as access-denied issues and false positives. For example, many users have reported receiving the "Access Denied" error when attempting to install certain apps, and the main reason ends up being their security program.

 To check if this is also your case, temporarily disable your third-party antivirus program and try to access the file or install the program. If the error does not appear, your antivirus software is likely the cause, and you should consider another program to protect your computer. Otherwise, use the Windows 11 built-in security program: Microsoft Defender.

 Resolving the "Access Denied" error is straightforward and does not require a lot of technical steps. You can regain control over your files and system by employing a few key strategies. Simply ensure your user account has the necessary permissions and, if needed, elevate your privileges to an administrator level.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/updated-character-choreography-compendiums-for-2024/"><u>[Updated] Character Choreography Compendiums for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-git-with-github-desktop-for-windows-users/"><u>Navigating Git with GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-window-hacks-restore-off-screen-on-windows-1011/"><u>Hidden Window Hacks: Restore Off-Screen on Windows 10/11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-video-selfie-verfication-is-it-really-useful-for-2024/"><u>[New] Instagram Video Selfie Verfication - Is It Really Useful for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-windows-11-when-you-cant-rename-folders/"><u>8 Ways to Fix Windows 11 When You Can’t Rename Folders</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-launch-windows-11-on-mac-through-parallels/"><u>Essential Steps to Launch Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-samsung-galaxy-f15-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Samsung Galaxy F15 5G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leap-ahead-your-in-store-purchase-speed-on-ms-platform/"><u>Leap Ahead Your In-Store Purchase Speed on MS Platform</u></a></li>
<li><a href="https://win11.techidaily.com/explore-and-manage-windows-11-writable-components/"><u>Explore and Manage Windows 11' Writable Components</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-tiletime-effortless-video-mosaics-on-both-oses/"><u>[Updated] 2024 Approved  TileTime  Effortless Video Mosaics on Both OSes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-screencast-savvy-a-comprehensive-examination-of-techniques-and-tools/"><u>[Updated] In 2024, Screencast Savvy  A Comprehensive Examination of Techniques & Tools</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-gaps-in-file-explorer-indexing/"><u>Correcting Gaps in File Explorer Indexing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-seamlessly-integrate-zoom-into-your-life-via-windows-10/"><u>[Updated] Seamlessly Integrate Zoom Into Your Life via Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-a-disabled-app-in-windows/"><u>How to Unblock a Disabled App in Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-mycams-journey-from-concept-to-reality-explored/"><u>[New] In 2024, MyCam's Journey From Concept to Reality Explored</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-take-notes-on-windows-11-without-downloading-software/"><u>5 Ways to Take Notes on Windows 11 Without Downloading Software</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-system-audio-windows-11-mixer-configuration-steps/"><u>Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/curing-store-failures-the-quick-fix-for-error-code-x00000000-in-windows-11/"><u>Curing Store Failures: The Quick Fix for Error Code X00000000 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exploring-m1-capabilities-apples-laptop-dilemma/"><u>Exploring M1 Capabilities  Apple's Laptop Dilemma</u></a></li>
<li><a href="https://win11.techidaily.com/easing-your-system-taming-cpu-hits-using-windows-monitor/"><u>Easing Your System: Taming CPU Hits Using Window's Monitor</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-unveiling-major-modifications-in-windows-movie-maker/"><u>[Updated] Unveiling Major Modifications in Windows Movie Maker</u></a></li>
<li><a href="https://win11.techidaily.com/decorate-your-screen-space-saving-spotlight-images-as-walls/"><u>Decorate Your Screen Space: Saving Spotlight Images as Walls</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-top-9-changes-in-win11-february-2023/"><u>Unveiling the Top 9 Changes in Win11 February 2023</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-nokia-g42-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Nokia G42 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-unused-disk-space-in-windows-efficiently/"><u>Harnessing Unused Disk Space in Windows Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/the-ultimate-guide-to-cheap-film-editing-software-for-2024/"><u>The Ultimate Guide to Cheap Film Editing Software for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/find-your-perfect-match-top-8-mirrorless-cameras-for-live-streams-for-2024/"><u>Find Your Perfect Match  Top 8 Mirrorless Cameras For Live Streams for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-error-0x7e1-on-win1011/"><u>How to Reverse Error 0X7E1 on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-storage-space-a-window-into-w10-and-w11-disks/"><u>Mastering Your Storage Space: A Window Into W10 & W11 Disks</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-dual-logins-eliminating-mixed-account-errors/"><u>Conquering Dual Logins: Eliminating Mixed Account Errors</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-windows-startup-setup-options/"><u>A Step-by-Step Breakdown of Windows Startup Setup Options</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-engage-more-with-facebook-sharing-panoramic-photos-via-iosandroid-apps/"><u>[New] 2024 Approved  Engage More with Facebook  Sharing Panoramic Photos via iOS/Android Apps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-the-disconnect-on-snapchat-are-they-blocked/"><u>[Updated] In 2024, The Disconnect on Snapchat  Are They Blocked?</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-cybersecurity-essential-windows-protection-tips/"><u>Mastery in Cybersecurity: Essential Windows Protection Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-glitches-solutions-guide/"><u>Unraveling WINDOWS 11 Glitches: Solutions Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-restoring-functionality-of-ccleaner-in-windows-1011-pcs/"><u>Guide for Restoring Functionality of CCleaner in Windows 10/11 PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-editors-path-to-seamless-inshot-joins-for-2024/"><u>The Editor's Path to Seamless Inshot Joins for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-how-to-do-transitions-on-inshot-video-editor/"><u>[New] How to Do Transitions on Inshot Video Editor?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-insta-lives-guide-to-downloads-and-creative-techniques/"><u>Mastering Insta Lives  Guide to Downloads & Creative Techniques</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-essential-guide-to-action-screening-saving/"><u>[Updated] In 2024, Essential Guide to Action Screening Saving</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-iphone-6s-plus-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your iPhone 6s Plus and iPad</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exclusive-gathering-of-top-tier-no-fee-vectr-and-illustration-sources-for-2024/"><u>Exclusive Gathering of Top-Tier No-Fee Vectr and Illustration Sources for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-extract-hd-pics-from-facebook-profile/"><u>2024 Approved  Extract HD Pics From Facebook Profile</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-navigating-the-monetization-maze-on-youtube/"><u>[New] Navigating the Monetization Maze on Youtube</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-success-elevating-winning-frames/"><u>Fast-Track to Success: Elevating Winning Frames</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-oppo-find-x6-pro-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Oppo Find X6 Pro</u></a></li>
</ul></div>
