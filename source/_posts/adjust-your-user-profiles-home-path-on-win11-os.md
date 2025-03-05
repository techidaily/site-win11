---
title: Adjust Your User Profiles' Home Path on Win11 OS
date: 2025-02-27T01:26:52.062Z
updated: 2025-03-05T03:42:28.378Z
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-pixel-perfect-preservation-the-best-practices-of-recording-games/"><u>[New] 2024 Approved Pixel-Perfect Preservation The Best Practices of Recording Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-expert-advice-on-quick-and-clean-ppt-captures/"><u>[New] Expert Advice on Quick and Clean PPT Captures</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-breakthrough-visuals-top-10-monitors-for-your-macbook/"><u>2024 Approved Breakthrough Visuals Top 10 Monitors For Your MacBook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-pixelpanorama-crafting-collage-vids-on-gear/"><u>2024 Approved PixelPanorama Crafting Collage Vids on Gear</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/breaking-through-the-shadows-fixes-for-obss-black-gaming-capture-for-2024/"><u>Breaking Through the Shadows Fixes for OBS's Black Gaming Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-geforce-notaxc0f1103f-issue-on-windows-pcs/"><u>Eradicating GeForce NotaXC0F1103F Issue on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-speed-up-microsoft-edge-w10-w11/"><u>How to Swiftly Speed up Microsoft Edge (W10, W11)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-insta-velocity-strategic-use-of-likes-and-videos-for-growth/"><u>In 2024, Insta Velocity Strategic Use of Likes & Videos for Growth</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-auto-startup-for-windows-audio/"><u>Mastering the Art of Auto Startup for Windows Audio</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/mastering-the-art-of-custom-karaoke-with-pcdjs-karaoki-feature-build-your-own-playlist/"><u>Mastering the Art of Custom Karaoke with PCDJ's Karaoki Feature - Build Your Own Playlist!</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-inaudibility-windows-11s-wireless-speaker-problems/"><u>Overcoming Inaudibility: Windows 11'S Wireless Speaker Problems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-7-amazing-labor-day-promotions-on-apple-products-save-up-to-120-on-airpods-according-to-zdnet/"><u>Top 7 Amazing Labor Day Promotions on Apple Products - Save Up To $120 On AirPods, According to ZDNet!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-7-essential-android-accessibility-options-for-enhanced-usability/"><u>Top 7 Essential Android Accessibility Options for Enhanced Usability</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-terminal-reset-on-win11/"><u>Understanding Terminal Reset on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveil-missing-windows-11-control-panel-features/"><u>Unveil Missing Windows 11 Control Panel Features</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-deep-dive-into-its-data-acquisition-tactics/"><u>Windows 11: A Deep Dive Into Its Data Acquisition Tactics</u></a></li>
</ul></div>

