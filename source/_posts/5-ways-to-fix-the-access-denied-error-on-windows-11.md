---
title: 5 Ways to Fix the “Access Denied” Error on Windows 11
date: 2024-06-25T11:45:19.798Z
updated: 2024-06-26T11:45:19.798Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/paint-your-thoughts-desktop-design-mastery-in-windows/"><u>Paint Your Thoughts: Desktop Design Mastery in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-way-to-self-empty-the-recycle-bin-on-windows/"><u>The Simple Way to Self-Empty the Recycle Bin on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-user-experience-in-windows-11/"><u>Transforming User Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-critical-windows-c0000022-bug/"><u>Confronting the Critical Windows C0000022 Bug</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-package-registration-problems-in-windows-operating-system/"><u>Overcoming Package Registration Problems in Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-step-by-step-creating-a-skype-group-on-both-systems/"><u>[Updated] In 2024, Step-by-Step  Creating a Skype Group on Both Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-workings-of-youtube-after-a-video-is-published/"><u>[Updated] The Workings of YouTube After a Video Is Published</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-video-enthusiasts-guide-to-the-best-photo-backdrop-swappers/"><u>2024 Approved  Video Enthusiasts' Guide to the Best Photo Backdrop Swappers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-perfect-xiaomi-device-for-amateur-filmmakers/"><u>2024 Approved  The Perfect Xiaomi Device for Amateur Filmmakers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-novice-to-visionary-the-ultimate-reddit-marketing-blueprint/"><u>2024 Approved  From Novice to Visionary  The Ultimate Reddit Marketing Blueprint</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-nokia-c02-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Nokia C02 Location | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mastering-facebook-livestreams-four-easy-steps/"><u>[New] Mastering Facebook Livestreams  Four Easy Steps</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-artisans-approach-expert-color-alteration-tactics/"><u>[New] The Artisan's Approach  Expert Color Alteration Tactics</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-professional-techniques-for-getting-rid-of-backgrounds-in-figma/"><u>[Updated] Professional Techniques for Getting Rid of Backgrounds in Figma</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>