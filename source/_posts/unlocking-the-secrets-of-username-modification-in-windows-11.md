---
title: Unlocking the Secrets of UserName Modification in Windows 11
date: 2024-07-13T10:48:59.686Z
updated: 2024-07-14T10:48:59.686Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking the Secrets of UserName Modification in Windows 11
excerpt: This Article Describes Unlocking the Secrets of UserName Modification in Windows 11
keywords: Win11 UserName Changer,UpdateUserProfileWin11,EditUsernameWin11,UserModifyWin11Tools,PersonalizeWin11Screen,WindowsProfileUpdateWin11,CustomUserNameWindows 11
thumbnail: https://thmb.techidaily.com/bb00ebc3d89d1362ca9b186657d254b37c10a245e721f7dc9d791e4530e6a65b.jpeg
---

## Unlocking the Secrets of UserName Modification in Windows 11

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
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-your-photos-a-comprehensive-guide-to-facetune/"><u>[New] Mastering Your Photos  A Comprehensive Guide to Facetune</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-mastering-smooth-playback-on-instagram-videos/"><u>[Updated] 2024 Approved  Mastering Smooth Playback on Instagram Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-zerocomplicationlivecast-your-simple-pathway-to-livestreaming-a-podcast/"><u>[New] ZeroComplicationLivecast  Your Simple Pathway to Livestreaming a Podcast</u></a></li>
<li><a href="https://some-techniques.techidaily.com/finding-the-perfect-balance-mastering-iphone-photo-blurring-for-2024/"><u>Finding the Perfect Balance  Mastering iPhone Photo Blurring for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-8-iphone-selfie-stick-choices-revealed/"><u>Top 8 iPhone Selfie Stick Choices Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/the-swift-way-to-access-control-panel/"><u>The Swift Way to Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-7-comedy-youtube-video-ideas-that-only-funny-people-are-allowed-to-try/"><u>[Updated] 7 Comedy YouTube Video Ideas That Only Funny People Are Allowed to Try</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-steps-for-windows-sandbox-configuration-in-11/"><u>The Essential Steps for Windows Sandbox Configuration in 11</u></a></li>
<li><a href="https://win11.techidaily.com/ux3405-vs-macbooks-asuss-oled-showdown/"><u>UX3405 vs MacBooks: Asus's OLED Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-comprehensible-guide-to-swapping-facial-gender-in-snapchat-images/"><u>[Updated] In 2024, Comprehensible Guide to Swapping Facial Gender in Snapchat Images</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-the-fullscreen-realm-choosing-a-cms/"><u>Entering the Fullscreen Realm  Choosing a CMS</u></a></li>
<li><a href="https://win11.techidaily.com/winning-with-linux-the-windows-integration-edge/"><u>Winning with Linux: The Windows Integration Edge</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-device-discovery-razer-and-windows-11-compatibility/"><u>Unlocking Device Discovery: Razer and Windows 11 Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/countering-dxgideviceremoved-failsafe-techniques/"><u>Countering DXGI_DEVICE_REMOVED Failsafe Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-hitching-a-ride-on-stream-success-obs-plus-zoom/"><u>[New] Hitching a Ride on Stream Success  OBS + Zoom</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease!</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eradicating-system-call-failed-problem-in-windows-11/"><u>Steps for Eradicating System Call Failed Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-keystroke-chaos-an-effective-guide-to-repair-common-windows-shortcut-issues/"><u>Banish Keystroke Chaos! An Effective Guide to Repair Common Windows Shortcut Issues</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-for-local-admin-credentials-on-windows-11/"><u>Stealth Mode for Local Admin Credentials on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-mystery-of-the-blank-steam-window/"><u>Dealing With the Mystery of the Blank Steam Window</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unresponsive-task-issues-in-windows-os/"><u>Addressing 'Unresponsive Task' Issues in Windows OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-threefold-mastery-in-copy-for-social-media-campaigns-increasing-impact-with-every-word-for-2024/"><u>[New] Threefold Mastery in Copy for Social Media Campaigns – Increasing Impact with Every Word for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-vms-from-windows-host-to-linux-guest-with-hyper-v/"><u>Setting Up VMs: From Windows Host to Linux Guest with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-lock-screen-stop-timer-glitch/"><u>Troubleshooting Windows Lock Screen Stop-Timer Glitch</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-substitutes-for-winmovie-new-windows-editors/"><u>[Updated] In 2024, Substitutes for WinMovie  New Windows Editors</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-startup-launching-windows-and-notebooks-effortlessly/"><u>Accelerated Startup: Launching Windows and Notebooks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blink-quick-fixes-for-input-lag-on-latest-microsoft-os/"><u>Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-the-gains-from-dxvk-adoption/"><u>Windows Users - The Gains From DXVK Adoption</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-file-management-customizing-explorer-comments/"><u>Tips for Efficient File Management: Customizing Explorer Comments</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-windows-defender-error-0x80004004/"><u>Deciphering & Correcting Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-email-banners-in-windows-os/"><u>Solving Disabled Email Banners in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-upgrade-failure-in-windows-11-error-0x800f0922/"><u>Steps to Fix Upgrade Failure in Windows 11 - Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/"><u>Renaissance PC: Refresh with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/the-definitive-guide-on-defeating-windows-11s-0x8007045d-error/"><u>The Definitive Guide on Defeating Windows 11'S 0X8007045D Error</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-artistic-freedom-starting-microsoft-paint-on-windows-11/"><u>Unlocking Artistic Freedom: Starting Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-screen-dream-realized-android-plus-windows-11-collaboration/"><u>A Dual-Screen Dream Realized: Android + Windows 11 Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/sync-windows-display-avoiding-overscan-limitations/"><u>Sync Windows Display: Avoiding Overscan Limitations</u></a></li>
</ul></div>
