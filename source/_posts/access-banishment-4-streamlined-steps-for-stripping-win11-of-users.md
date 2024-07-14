---
title: "Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users"
date: 2024-07-13T11:15:54.718Z
updated: 2024-07-14T11:15:54.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users"
excerpt: "This Article Describes Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users"
keywords: Win11 Banning,User Removal Win11,Win11 Banishment Guide,Stripping Users From Win11,Win11 Access Forbidden,Win11 User Exclusion Steps,Win11 Unauthorized Removal
thumbnail: https://thmb.techidaily.com/2921f580a005bca983d6da9a3afb73cd46b3297303a92739f51d69c3aa21056e.jpg
---

## Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you [add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

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

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to [lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

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

 To install the tool, follow our guide to [enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

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
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-lsa-error-on-windows-systems/"><u>Fixing LSA Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-a-parallels-driven-path-for-windows-11-installation/"><u>Embark on a Parallels-Driven Path for Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-sudden-invisibility-issues-in-pc-gaming/"><u>Eradicating Sudden Invisibility Issues in PC Gaming</u></a></li>
<li><a href="https://extra-resources.techidaily.com/choosing-the-finest-10-free-subtitles-editors-online/"><u>Choosing the Finest 10 Free Subtitles Editors Online</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-social-network-showdown-tiktok-vs-snap/"><u>[Updated] In 2024, Social Network Showdown  TikTok Vs Snap</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-panasonics-hx-a1-the-wearable-action-camera-revealed/"><u>2024 Approved  Panasonic’s HX-A1 - The Wearable Action Camera Revealed</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-beyond-gopro-quik-top-pc-video-editing-software-options/"><u>In 2024, Beyond GoPro Quik Top PC Video Editing Software Options</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-a-list-guide-to-instagram-photo-mastery-for-2024/"><u>[New] The A-List Guide to Instagram Photo Mastery for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/skyrocket-your-channels-with-these-essential-freegame-tags-for-youtube/"><u>Skyrocket Your Channels with These Essential FreeGame Tags for YouTube</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-top-10-favorite-discothemes-a-curated-list-from-bestdiscord/"><u>[Updated] Top 10 Favorite DiscoThemes - A Curated List From BestDiscord</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-valid-temp-directory-in-windows-11-os/"><u>Ensuring a Valid Temp Directory in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-senior-accessibility-on-legacy-computers/"><u>Enhancing Senior Accessibility on Legacy Computers</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-harmonyvoices-mastering-cross-platform-audio-synchronization-in-adobe-premiere-pro-for-2024/"><u>Updated HarmonyVoices Mastering Cross-Platform Audio Synchronization in Adobe Premiere Pro for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-androids-favorite-companions-for-nintendo-3ds-games/"><u>[Updated] 2024 Approved  Android's Favorite Companions for Nintendo 3DS Games</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-best-youtube-video-ideas-to-spark-inspiration-for-youtube-channels/"><u>[Updated] Best YouTube Video Ideas to Spark Inspiration [For YouTube Channels]</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-personalized-taskbar-in-w11-windows/"><u>Crafting a Personalized Taskbar in W11 Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-speedy-social-stardom-likes-plus-videos-on-instagram-guide/"><u>In 2024, Speedy Social Stardom  Likes + Videos on Instagram Guide</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-precision-in-perception-advanced-techniques-for-taming-tangled-sounds-for-2024/"><u>Updated Precision in Perception Advanced Techniques for Taming Tangled Sounds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-add-folder-not-possible-issue-with-windows-onedrive/"><u>Combatting 'Add Folder Not Possible' Issue with Windows OneDrive</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-realme-narzo-60-pro-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Realme Narzo 60 Pro 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/streamline-your-slides-with-these-4-youtube-video-inclusion-methods-for-2024/"><u>Streamline Your Slides with These 4 YouTube Video Inclusion Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstructions-a-guide-to-windows-11s-search-problems/"><u>Clearing Obstructions: A Guide to Windows 11'S Search Problems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-easy-steps-for-achieving-facebooks-prestigious-blue-badge-for-2024/"><u>[Updated] Easy Steps for Achieving Facebook's Prestigious Blue Badge for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevate-your-online-presence-secrets-of-youtube-live-with-wirecast/"><u>[New] 2024 Approved  Elevate Your Online Presence  Secrets of Youtube Live with WireCast</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-user-experience-tailoring-windows-via-alomware-applications/"><u>Elevate User Experience: Tailoring Windows via AlomWare Applications</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-reverting-customized-windows-configurations/"><u>Effective Methods: Reverting Customized Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://screen-capture.techidaily.com/cultivating-excellence-the-best-seed-strategy-in-valheim-for-2024/"><u>Cultivating Excellence  The Best Seed Strategy in Valheim for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-3gp-video-format-what-is-3gp-format-and-how-to-play-it/"><u>Updated 2024 Approved 3GP Video Format What Is 3GP Format And How To Play It?</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-photo-cropping-apps-how-to-crop-photos-on-iphone/"><u>2024 Approved  Photo Cropping Apps  How to Crop Photos on iPhone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-an-in-depth-look-at-time-lapse-photography-using-ipad/"><u>In 2024, An In-Depth Look at Time-Lapse Photography Using iPad</u></a></li>
</ul></div>
