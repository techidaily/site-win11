---
title: "Master Profile Management: Name Alteration in W11"
date: 2024-09-24T18:41:30.482Z
updated: 2024-09-28T17:03:13.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master Profile Management: Name Alteration in W11"
excerpt: "This Article Describes Master Profile Management: Name Alteration in W11"
keywords: Profile Mastery,Name Change Guide,Altering Usernames,W11 Update,Username Revision,Personal Info Management,ID Modification Tips
thumbnail: https://thmb.techidaily.com/8614a77f9e633f7b68cb429db560c3992306d2b5be6c80ea6d2432a854e4bb42.jpg
---

## Master Profile Management: Name Alteration in W11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-examining-vidma-as-a-video-recorder-for-screens/"><u>[New] 2024 Approved Examining Vidma as a Video Recorder for Screens</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-how-to-acquire-standardized-thumbnails-from-youtube-online-and-desktop-options/"><u>[New] In 2024, How To Acquire Standardized Thumbnails From Youtube Online & Desktop Options</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-from-clueless-to-confident-configuring-zoom-made-simple/"><u>[Updated] In 2024, From Clueless to Confident Configuring Zoom Made Simple</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-navigating-teamsnap-photo-functions-for-effective-collaboration/"><u>[Updated] In 2024, Navigating TeamSnap Photo Functions for Effective Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/free-and-fast-the-ultimate-list-of-mac-screen-recorders-for-2024/"><u>Free and Fast The Ultimate List of Mac Screen Recorders for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-oneplus-nord-n30-se-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock OnePlus Nord N30 SE Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-techniques-for-effective-qr-scanning-on-pcs/"><u>Pioneering Techniques for Effective QR Scanning on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-distribution-the-ultimate-sefx-guide-for-win11/"><u>Streamlining File Distribution: The Ultimate SEFx Guide for Win11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-underground-guide-5-unauthorized-uses-of-ai/"><u>The Underground Guide: 5 Unauthorized Uses of AI</u></a></li>
</ul></div>

