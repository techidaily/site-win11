---
title: Rename User's Home Path on Windows 11 Easily
date: 2024-12-11T04:41:01.258Z
updated: 2024-12-12T18:32:49.423Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rename User's Home Path on Windows 11 Easily
excerpt: This Article Describes Rename User's Home Path on Windows 11 Easily
keywords: Win11 HomePath Rename Guide,Renewing Windows 11 Profile,Update PC User Path,Change Home Drive Name Win11,Win11 Profile Edit Tips,Easy Win11 HomePath Changes,Customizing User Home Folder
thumbnail: https://thmb.techidaily.com/1c82bb77bafb99b9b6611b5302d1fb010d446c70d3f6bad7daef0045c02e4cb1.png
---

## Rename User's Home Path on Windows 11 Easily

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-essential-methods-for-livestreaming-sporting-action-successfully/"><u>[New] 2024 Approved Essential Methods for Livestreaming Sporting Action Successfully</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-acclaimed-websites-for-google-pixel-tonal-sounds/"><u>[Updated] Acclaimed Websites for Google Pixel Tonal Sounds</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-instant-upload-share-pics-directly-from-your-camera-roll/"><u>[Updated] In 2024, Instant Upload Share Pics Directly From Your Camera Roll</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-seamless-speed-control-the-editors-essential-handbook/"><u>[Updated] Seamless Speed Control The Editor's Essential Handbook</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-your-complimentary-access-to-50-premium-youtube-banners-in-2024/"><u>[Updated] Your Complimentary Access to 50 Premium YouTube Banners, In 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-how-to-use-video-titles-and-youtube-tags-for-more-views/"><u>2024 Approved How to Use Video Titles and YouTube Tags for More Views?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-12-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme 12 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://network-issues.techidaily.com/comwin-harmony-achieved-post-update/"><u>ComWin Harmony Achieved Post-Update</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-rectifying-iphone-image-issues-in-windows/"><u>Essential Tips for Rectifying iPhone Image Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-streamlining-browsing-with-lowered-process-count/"><u>Guide to Streamlining Browsing with Lowered Process Count</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-oneplus-ace-2-pro-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our OnePlus Ace 2 Pro Phone Screen?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-from-iphone-15-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide from iPhone 15 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-resolution-for-anydesk-windows/"><u>Mastering Error Resolution for AnyDesk Windows</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-errors-unveiled-and-solved-for-w11-users/"><u>OneDrive Errors Unveiled & Solved for W11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/repair-keyboard-woes-solving-f-keys-issues-in-win-11/"><u>Repair: Keyboard Woes - Solving F-Keys Issues in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-crafting-your-own-speech-to-text-app-with-windows/"><u>Step-by-Step Guide to Crafting Your Own Speech-to-Text App with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-optimize-your-windows-lockscreen-settings/"><u>Streamline and Optimize Your Windows Lockscreen Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-optimal-performance-with-easy-directx-downloads-and-updates/"><u>Unlock Optimal Performance with Easy DirectX Downloads & Updates</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-setting-up-guide/"><u>Windows 11 Setting Up Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    