---
title: "Power Play: Four Strategies for Removing User Entries From Win11"
date: 2024-08-16T00:44:32.361Z
updated: 2024-08-17T00:44:32.361Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Power Play: Four Strategies for Removing User Entries From Win11"
excerpt: "This Article Describes Power Play: Four Strategies for Removing User Entries From Win11"
keywords: Win11 Privacy Controls,Remove Win11 Users,Win11 Admin Guide,Secure Win11 Environment,Win11 User Removal,Manage Win11 Users,Strategies for Win11 Management
thumbnail: https://thmb.techidaily.com/a362218194355c666b0860326aa79761dfe27d2518f12f424f4610cd1ffe517b.jpg
---

## Power Play: Four Strategies for Removing User Entries From Win11

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
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, type**exit** and press Enter to close Command Prompt.
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-supercharge-your-farming-fun-in-stardew-valley-top-7-upgrades/"><u>[New] 2024 Approved  Supercharge Your Farming Fun in Stardew Valley (Top 7 Upgrades)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-srt-extraction-procedure-from-zipped-contents/"><u>[New] Srt Extraction Procedure From Zipped Contents</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-tweeting-at-the-top-discover-how-to-watch-in-full-hd-for-2024/"><u>[New] Tweeting at the Top  Discover How to Watch in Full HD for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-youtube-equipment-for-gaming-channels-best-gaming-gears/"><u>[New] YouTube Equipment for Gaming Channels - Best Gaming Gears</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-framing-perfection-a-filmmakers-guide-to-cinematic-youtube-videos/"><u>[Updated] 2024 Approved  Framing Perfection  A Filmmaker's Guide to Cinematic YouTube Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-from-snapshots-to-videos-your-maccam-adventure/"><u>[Updated] 2024 Approved  From Snapshots to Videos  Your MacCam Adventure</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-money-making-the-ultimate-13-beginners-guide-to-reddit/"><u>[Updated] Mastering Money-Making  The Ultimate 13 Beginner's Guide to Reddit</u></a></li>
<li><a href="https://win11.techidaily.com/10-essential-steps-for-accessing-windows-nettools/"><u>10 Essential Steps for Accessing Windows NetTools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-memorable-youtube-names/"><u>2024 Approved  The Ultimate Guide to Memorable YouTube Names</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-infinix-zero-5g-2023-turbo-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-inadvertent-chrome-tab-openings-on-pc/"><u>A Quick Fix for Inadvertent Chrome Tab Openings on PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/altering-output-displays-in-window-based-os/"><u>Altering Output Displays in Window-Based OS</u></a></li>
<li><a href="https://win11.techidaily.com/archive-your-cortana-trails-on-a-pc-operating-system/"><u>Archive Your Cortana Trails on a PC Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-fix-restoring-functionality-to-windows-charmap/"><u>Comprehensive Fix: Restoring Functionality to Windows CharMap</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-command-prompt-for-ultimate-control/"><u>Configuring Command Prompt for Ultimate Control</u></a></li>
<li><a href="https://driver-error.techidaily.com/controller-fault-notification-at-idedevice/"><u>Controller Fault Notification at Idedevice</u></a></li>
<li><a href="https://extra-tips.techidaily.com/decoding-slug-lines-for-effective-writing/"><u>Decoding Slug Lines for Effective Writing</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-dilemma-is-removing-pagefilesys-advisable/"><u>Deletion Dilemma: Is Removing Pagefile.sys Advisable?</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-downfalls-of-modern-standby-in-windows-os/"><u>Dissecting the Downfalls of Modern Standby in Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-apple-iphone-xs-max-in-3-ways-drfone-by-drfone-virtual-ios/"><u>Edit and Send Fake Location on Telegram For your Apple iPhone XS Max in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/efficient-techniques-for-adobe-presenter-capture-for-2024/"><u>Efficient Techniques for Adobe Presenter Capture for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-vivo-x-fold-2-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Vivo X Fold 2 Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-counter-strike-global-offensive-not-opening-in-windows-11/"><u>How to Fix Counter-Strike: Global Offensive Not Opening in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-fall-guys-connection-errors-on-windows/"><u>How to Fix Fall Guys Connection Errors on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-f25-pro-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo F25 Pro 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-x100-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo X100 Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-cutting-edge-of-uhd-with-lgs-27ud68/"><u>In 2024, Exploring the Cutting-Edge of UHD with LG's 27UD68</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-samsung-galaxy-s24-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Samsung Galaxy S24 FRP Without Computer</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-popular-pictures-the-backstage-story/"><u>In 2024, Popular Pictures  The Backstage Story</u></a></li>
<li><a href="https://win11.techidaily.com/interfacing-with-the-core-of-windows-print-system/"><u>Interfacing with the Core of Windows Print System</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-ethernet-connection-fixes/"><u>Navigating Through Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-run-as-admin-errors-a-guide/"><u>Overcoming Run as Admin Errors: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-steam-friends-list-step-by-step-guide-windows-11/"><u>Reconnect Steam Friends List: Step-by-Step Guide, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/regulating-pcs-to-prevent-windows-11-overheats/"><u>Regulating PCs to Prevent Windows 11 Overheats</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-stability-issues-with-praey-for-the-gods-on-desktop-pcs/"><u>Resolving Stability Issues With Praey: For The Gods on Desktop PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-admin-oversight-of-chromium-and-microsoft-edge-browsing-experience/"><u>Revamping Admin-Oversight of Chromium & Microsoft Edge Browsing Experience</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-the-w11-desktop-step-by-step-guide/"><u>Revamping the W11 Desktop: Step-by-Step Guide</u></a></li>
<li><a href="https://driver-download.techidaily.com/solution-for-the-undetectable-tl-wn722n-wifi-adapter-on-windows-platforms/"><u>Solution for the Undetectable TL-WN722N WiFi Adapter on Windows Platforms</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-fires-of-rubicon-pc-issues-a-comprehensive-guide-to-enjoying-armored-core-natively-on-your-computer/"><u>Solving 'Fires of Rubicon' PC Issues: A Comprehensive Guide to Enjoying Armored Core Natively on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/speedy-solutions-tackling-slow-response-times-on-your-keyboard/"><u>Speedy Solutions: Tackling Slow Response Times on Your Keyboard</u></a></li>
<li><a href="https://some-approaches.techidaily.com/switch-to-picture-in-picture-while-watching-youtube-for-2024/"><u>Switch to Picture in Picture While Watching YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-transition-from-stuck-in-windows-1011-s-mode/"><u>Tactics to Transition From Stuck in Windows 10/11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-connect-your-device-bluetooth-error-in-windows-11/"><u>Troubleshooting Connect Your Device Bluetooth Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-transformation-of-heic-files-into-jpeg/"><u>Uncomplicated Transformation of HEIC Files Into JPEG</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-joy-essential-list-of-free-media-players-for-windows/"><u>Unleash Joy: Essential List of Free Media Players for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-git-with-github-desktop-and-windows-11/"><u>Unveiling the Power of Git with GitHub Desktop & Windows 11</u></a></li>
</ul></div>
