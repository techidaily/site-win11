---
title: Streamlining the UserName Switch on Windows 11
date: 2024-07-13T10:57:35.731Z
updated: 2024-07-14T10:57:35.731Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining the UserName Switch on Windows 11
excerpt: This Article Describes Streamlining the UserName Switch on Windows 11
keywords: Win11 UserName Change,Streamlined USN Update,Quick Win11 UserSwitch,Windows 11 NameEdit,Efficient Windows USN Switch,Simple Win11 NicknameChange,Accelerated UserNameSwitchWin11
thumbnail: https://thmb.techidaily.com/4cc1197e18d9544b2124a65bfec1efb521b06ec232353dd58129a9184ba8b76a.jpg
---

## Streamlining the UserName Switch on Windows 11

 Have you got tired of using the same username for a long time? Were you assigned a random username when you created your account, but now you want to add a personal touch? If you want to change your username for any reason, Windows lets you do it easily. In fact, there are numerous ways to go about this. We have listed some of the simplest ones below.

## Before We Get Started…

 Keep in mind that the first four methods discussed below can only be used to change the username of a local user account. If you use them to change the username of a Microsoft account, the change will be reversed the next time you restart your device.

 So, if you want to change your Microsoft account username, we recommend directly using the last method—changing your username from Microsoft's website. However, if you want to change the username of a local user account, you can use one of the first four methods mentioned below.

## 1\. How to Change Your Username Using the Control Panel

 The Control Panel serves as the central hub in the Windows operating system. From changing the operating system's appearance to configuring the connected hardware, the Control Panel allows users to tailor the entire OS. Among other customizations, users can change their usernames and manage their user accounts effectively.

To change your username using the Control Panel, follow these steps:

1. Type**"Control Panel"** in Windows Search and open the**Control Panel** app. (Check out [other ways to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) )
2. Select**Large icons** from the**View by** dropdown menu if it isn't already selected.
3. Go to**User Accounts** .  
![Go to User Accounts in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-go-to-user-accounts-in-windows-control-panel.jpg)
4. Click on**Change your account name** .  
![Click on Change Your Account Name in User Account Settings in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-click-on-change-your-account-name-in-user-account-settings-in-windows-control-panel.jpg)
5. Click**Yes** in the**User Account Control (UAC)** window.
6. In the**New account name** field, type your new username.
7. After that, click on**Change Name** .  
![Click on Change Name After Entering the New Username](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-click-on-change-username-after-entering-the-new-username.jpg)
8. For this change to take effect, you need to sign out of your account and sign back in.

## 2\. How to Change Your Username Using the Run Command

 Using the Run command, Windows users can access any location on a computer whose path is known. It eliminates the need to navigate through numerous folders to reach our destination.

 Using this utility, we can access the User Accounts settings via a simple command, "netplwiz," which allows us to access the dedicated account management panel. From there, you can easily change your username.

To change your username using the Run command, follow these steps:

1. Press**Win + R** to launch the**Run command** .
2. Enter**"netplwiz"** in the**Run command** field and press**Enter** .  
![Run Netplwiz Command in the Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-run-netplwiz-command-in-the-windows-run-command.jpg)
3. Click**Yes** in the**User Account Control (UAC)** window.
4. In the**User Accounts** window, select the user account for which the username needs to be changed.
5. Click on**Properties** .  
![Go to Properties in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-go-to-properties-in-the-user-accounts-window.jpg)
6. In the**General** tab, you'll see your existing username. Rename it to your liking after removing it.
7. Once the new username has been added, click the**Apply** button and**OK** .  
![Click OK After Adding the New Name in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-click-ok-after-adding-the-new-name-in-the-user-accounts-window.jpg)
8. Then, log out of your account, and you'll be greeted with your new username on the sign-in screen when you sign in.

## 3\. How to Change Your Username From Local User and Group Management Tool

 If the "netplwiz" command does not work or gives an error when accessing the user account manager, you can use the local user and group management tool to change the username. This is the easiest way to modify your Windows username, as it allows you to simply rename your username directly—like you rename any folder.

 Here's how to change the username through the local user and group management tool:

1. Press**Win + R** to open the Run command.
2. Type**"lusrmgr.msc"** and press**Enter** .  
![Run lusrmgr.msc Command in Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-run-lusrmgr-msc-command-in-windows-run-command.jpg)
3. Click**"Yes"** in the**User Account Control (UAC)** window.
4. Select the**Users** tab in the left sidebar.
5. Find your account in the right pane.
6. Right-click the username and click**Rename** .  
![Click Rename by Right-clicking on the Account Name in the Local User and Group Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/8-click-rename-by-right-clicking-on-the-account-name-in-the-local-user-and-group-management-tool.jpg)
7. Enter the new username you want to use.

 Afterward, close the local user and group management tool, sign out of your account once, and you'll see your new username on the sign-in screen.

## 4\. How to Change Your Username Using Windows PowerShell

[Windows Powershell](https://www.makeuseof.com/what-is-windows-powershell/) , an object-oriented automation engine, was designed primarily for IT administrators to automate tasks. Still, its simplicity and ease of use make it worthwhile for laypeople without programming experience.

 Using its built-in cmdlets or writing custom scripts, you can make any changes to your Windows device that you usually make via GUI-based applications and settings. You can also change your username using it.

 To change your username using the Windows PowerShell, follow these steps:

1. Type**"Windows PowerShell"** in Windows Search and open the Windows PowerShell app.
2. Type the following command and press Enter to find your current username:  
Get-LocalUser
3. Add the following command after entering your current username and the one you want to switch to:  
Rename-LocalUser -Name "Enter your current username" -NewName "Enter the new username"
4. Hit**Enter** after adding the above command.  
![Changing Username in Windows Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/changing-username-in-windows-powershell.jpg)
5. Then, log back into your account after logging out.

## 5\. How to Change Your Profile Username From the Microsoft Website

 If you use a Microsoft account on your computer, change your username on the Microsoft website. To update your profile username on the Microsoft website, follow these steps:

1. Go to your account page on the [Microsoft website](https://account.microsoft.com/account/Account) .
2. Log in to your account if you haven't already.
3. Navigate to the**Your info** menu after logging in.
4. Click the**Edit name** button.  
![Click on Your info and Edit name to Change Username of a Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-your-info-and-edit-name-to-change-username-of-a-microsoft-account.jpg)
5. Remove your current username and add the one you wish to switch to.
6. After that, click**Save** .  
![Click on Save to Change the Username of Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-save-to-change-the-username-of-microsoft-account.jpg)

 Changing the username associated with your Microsoft account may not take effect immediately. Sometimes, you may not see the new username after signing out from your account once, as we do in the other methods. To prevent that from happening, we recommend [restarting your device](https://www.makeuseof.com/windows-restart-methods/) instead of just signing out.

## Change Your Username With Ease

 Your username doesn't have to remain the same for the rest of your life. If you decide to change it, you can use the first four methods listed above to change the current username (of your local user account) to the one you prefer. Regardless of which way you opt, ensure you sign out of your account once. Only then will this change take effect.

 You will need to change the username associated with your Microsoft account from the Microsoft website. Also, remember that changing your username does not automatically change the user profile folder name. Therefore, you'll have to change it separately.


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
<li><a href="https://change-location.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-top-15-instagram-videophoto-downloaders/"><u>[New] In 2024, Top 15 Instagram Video/Photo Downloaders</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-nokia-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Nokia</u></a></li>
<li><a href="https://win11.techidaily.com/critical-hardware-scan-tools/"><u>Critical Hardware Scan Tools</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-way-you-use-windows-11s-search-feature/"><u>Transforming the Way You Use Windows 11'S Search Feature</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-best-video-cutting-software-for-windows/"><u>Updated 2024 Approved Best Video Cutting Software for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-dev-drive-setup-in-windows-11-development-space/"><u>Demystifying Dev Drive Setup in Windows 11 Development Space</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-building-dreams-in-mc-ideal-village-housing-plans/"><u>[Updated] Building Dreams in MC  Ideal Village Housing Plans</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-connection-stop-usb-sleep-in-win-11/"><u>Ensuring Continuous Connection: Stop USB Sleep in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-audio-excellence-with-5-free-windows-apps/"><u>Elevate Audio Excellence with 5 Free Windows Apps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-innovative-techniques-for-stellar-screen-captures-with-adobe-captivity/"><u>[Updated] Innovative Techniques for Stellar Screen Captures with Adobe Captivity</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-fix-facebook-watch-video-icon-tap-missing/"><u>[New] In 2024, Fix Facebook Watch Video Icon Tap Missing</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-photo-slideshows-and-spot-corrections-on-win11s-gallery/"><u>Mastering Photo Slideshows & Spot Corrections on Win11's Gallery</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-oppo-a59-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Oppo A59 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/digital-fortifications-essential-tactics-for-access-control/"><u>Digital Fortifications: Essential Tactics for Access Control</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/exclusive-the-leading-five-fb-videos/"><u>Exclusive  The Leading Five FB Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-ultimate-fb-video-player-guide-top-picks-listed-for-2024/"><u>[Updated] Ultimate FB Video Player Guide  Top Picks Listed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-alt-codes-in-windows/"><u>Troubleshooting Non-Responsive ALT Codes in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-realme-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unifying-platforms-the-art-of-incorporating-linktree-in-tiktok-biographies-for-2024/"><u>Unifying Platforms  The Art of Incorporating Linktree in TikTok Biographies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-0x800704b3-on-windows-pcs/"><u>Addressing Error Code 0X800704B3 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-error-code-0xc0000001-on-windows/"><u>Decoding and Fixing Error Code 0XC0000001 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-best-video-edits-and-scripting-tools-in-windows-11/"><u>The Ultimate List: Best Video Edits & Scripting Tools in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-disregard-must-have-components-issue-in-win10win11/"><u>Quick Guide to Disregard Must-Have Components Issue in Win10/Win11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-action-camera-faceoff-gopro-hero-vs-yi-4k-new-edition-review/"><u>2024 Approved  Action Camera Faceoff  GoPro Hero Vs. Yi 4K - New Edition Review</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-popular-food-recipes-from-different-countries-for-2024/"><u>[Updated] Popular Food Recipes From Different Countries for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-drive-labels-the-candd-dynamics/"><u>Interpreting Drive Labels: The C&D Dynamics</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-prime-video-kingmakers-top-tweeted-and-most-watched-originals/"><u>[Updated] 2024 Approved  Prime Video Kingmakers  Top Tweeted & Most Watched Originals</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-credential-entry-attempts/"><u>Analyzing Windows Credential Entry Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-code-4-spotify-error-on-w10w11-systems/"><u>Overcoming the Code 4 Spotify Error on W10/W11 Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/experts-blueprint-revolutionizing-your-screencasting-experience-with-mobizen-for-2024/"><u>Expert's Blueprint  Revolutionizing Your Screencasting Experience with Mobizen for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-comprehensive-approach-to-linking-your-tiktok-profile/"><u>[Updated] The Comprehensive Approach to Linking Your TikTok Profile</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restricted-administrator-error-in-winsec/"><u>Overcoming Restricted Administrator Error in WinSec</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-synergistic-videos-to-skyrocket-your-follower-count/"><u>2024 Approved  Synergistic Videos to Skyrocket Your Follower Count</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-group-policy-settings-an-exploration-in-3-dimensions/"><u>Unraveling Windows Group Policy Settings: An Exploration in 3 Dimensions</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-threshold-post-failed-access-on-w10w11/"><u>Tweaking the Lockout Threshold Post-Failed Access on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-ad-ds-strategies-for-printer-troubleshooting/"><u>Win11 & AD DS: Strategies for Printer Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-advanced-taskbar-attachments/"><u>Windows 11: Advanced Taskbar Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-x0001-with-nvidia-experience-w11/"><u>Remedying Error X0001 with Nvidia Experience, W11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-tips-for-kinemasters-chroma-keying/"><u>Essential Tips for KineMaster's Chroma Keying</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-online-oasis-secure-re-entry-to-social-networks/"><u>2024 Approved  Online Oasis  Secure Re-Entry to Social Networks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-blueprint-for-blending-video-content-into-curricula/"><u>[Updated] 2024 Approved  Blueprint for Blending Video Content Into Curricula</u></a></li>
</ul></div>
