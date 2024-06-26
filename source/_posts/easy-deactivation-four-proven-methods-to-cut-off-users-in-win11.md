---
title: "Easy Deactivation: Four Proven Methods to Cut Off Users in Win11"
date: 2024-06-25T10:12:10.281Z
updated: 2024-06-26T10:12:10.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easy Deactivation: Four Proven Methods to Cut Off Users in Win11"
excerpt: "This Article Describes Easy Deactivation: Four Proven Methods to Cut Off Users in Win11"
keywords: Win11 Deactivate Guide,Quick User Blocking Win11,Win11 Account Lockout,Easy Win11 Unauthorized Access,Methods to Stop Users in Win11,Proven User Removal Win11,Secure Win11 User Deactivation
thumbnail: https://thmb.techidaily.com/6dd8f57eda55f51f780fa0fbffb1950bf2ad081249b06af69891f71aad7773d2.jpg
---

## Easy Deactivation: Four Proven Methods to Cut Off Users in Win11

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you[add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .
4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
3. PowerShell will not return a success message after the user account is disabled.
4. If you need to enable the account again, type the following command and press Enter:  
`Enable-LocalUser -Name &ldquo;NewUser&rdquo;`
5. In the above command replace NewUser with your user account name.

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to[lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

## 3\. Disable a User Account Using the Command Prompt

 Another way to disable a local user account is via the Command Prompt. It is a command-line utility that you can use to disable Microsoft or local user accounts.

To disable a user account using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** box. Next, press**OK** while holding the**Ctrl + Shift** key to open the elevated Command Prompt. Click**Yes** if prompted by User Account Control.
3. In the Command Prompt window, type the following command to find all the available user accounts on your PC:  
`net user`
4. Locate the user account name in the return list.  
![command prompt net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user.jpg)
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
7. Next, type**exit** and press Enter to close Command Prompt.
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

## 4\. Disable a User Account From the Computer Management Console

 The Computer Management Console gives system administrators access to advanced tools such as Task Scheduler, Event Viewer, Device Manager, etc. Another useful Computer Management feature is Local Users and Groups.

 Local User and Groups lets you manage user accounts and groups on your Windows computer. While the Computer Management console is available on all versions of Windows, Local User and Groups is only available on the Pro, Edu, and Enterprise edition of the OS.

 To disable user accounts using the Local Users and Groups Management console:

1. Click on the**Search icon** in**Taskbar** .
2. Type**computer management** and click on**Computer Management** from the search result.
3. In the**Computer Management** console, expand**System Tools** .  
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to[enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

## There Are Many Ways to Disable a User Account on Windows 11

 Disabling a user account lets you restrict access to a specific user account without deleting the account completely. This way, if you need to restore the account at a later stage, you can enable it and continue using it without restoring files and folders.

 That said, removing a user account on Windows 11 is not a complicated process. Just log in to your administrator account and block sign-in or remove user accounts from Settings, and you're pretty much done.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-void-recovering-startups-on-windows/"><u>Bridging the Void: Recovering Startups on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-link-your-windows-product-key-to-a-microsoft-account/"><u>How to Link Your Windows Product Key to a Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/wrapping-windows-games-in-christmas-carols/"><u>Wrapping Windows Games in Christmas Carols</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-stability-solutions-for-recurring-crashes/"><u>Windows UI Stability: Solutions for Recurring Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-console-collapse-avoiding-sudden-df-closures/"><u>Counteracting Console Collapse: Avoiding Sudden DF Closures</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-bar-evolution-story-1985present/"><u>The Windows Bar Evolution Story (1985–Present)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-menu-items-in-windows-11-desktop/"><u>Addressing Frozen Menu Items in Windows 11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-10plus-free-tiktok-video-editing-appswebsite-on-mac/"><u>[Updated] 2024 Approved  10+ Free TikTok Video Editing Apps/Website on Mac</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/eco-editing-essentials-30plus-free-templates-for-ambitious-filmmakers/"><u>Eco-Editing Essentials  30+ Free Templates for Ambitious Filmmakers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-xiaomi-redmi-k70e-lock-screen-password-by-drfone-android/"><u>How To Change Xiaomi Redmi K70E Lock Screen Password?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-selecting-the-finest-screen-recorders-1-to-5-android-for-2024/"><u>[Updated] Selecting the Finest Screen Recorders, #1 to #5 (Android) for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-from-broadcast-to-box-viewing-facebook-streams-on-roku/"><u>[Updated] From Broadcast to Box  Viewing Facebook Streams on Roku</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-12-pro-5g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 12 Pro 5G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-a-list-of-the-top-spongebob-voice-generators/"><u>2024 Approved A List of The Top SpongeBob Voice Generators</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-9-premium-portable-microphones-for-podcasters/"><u>Updated Top 9 Premium Portable Microphones for Podcasters</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-x90s-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-top-5-apps-for-capturing-precise-android-displays/"><u>[Updated] 2024 Approved  Top 5 Apps for Capturing Precise Android Displays</u></a></li>
</ul></div>
