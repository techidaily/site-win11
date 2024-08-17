---
title: "Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users"
date: 2024-08-15T23:20:08.251Z
updated: 2024-08-16T23:20:08.251Z
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

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-master-looped-videos-for-maximum-instagram-impact/"><u>[New] 2024 Approved  Master Looped Videos for Maximum Instagram Impact</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-beginning-with-adobe-audition-the-fading-start/"><u>[New] Beginning with Adobe Audition  The Fading Start</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-beginner-to-expert-a-comprehensive-guide-to-looping-your-favorite-vids/"><u>[New] In 2024, From Beginner to Expert  A Comprehensive Guide to Looping Your Favorite Vids</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-ultimate-guide-to-using-snapchat-in-biz/"><u>[New] The Ultimate Guide to Using Snapchat in Biz</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-a-visual-voyage-through-youtubes-2017-data-deluge-for-2024/"><u>[Updated] A Visual Voyage Through Youtube's 2017 Data Deluge for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-creative-commons-legalities-explained-simply-for-2024/"><u>[Updated] Creative Commons Legalities Explained Simply for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-transcribe-speech-absolutely-gratis/"><u>[Updated] Transcribe Speech, Absolutely Gratis</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-ultimate-instagram-story-tips-and-tricks-for-2024/"><u>[Updated] Ultimate Instagram Story Tips & Tricks for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/baldurs-gate-3-wont-launch-here-are-the-solutions-you-need/"><u>Baldur's Gate 3 Won't Launch? Here Are the Solutions You Need!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-the-escape-function-in-windows-os/"><u>Breathe Life Back Into the Escape Function in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-unforeseen-security-issues-in-win10win11/"><u>Counteracting Unforeseen Security Issues in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-marketplace-failures-error-0x80073cf3/"><u>Deciphering and Resolving Windows Marketplace Failures (Error 0X80073CF3)</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-11-the-intricacies-of-its-file-system/"><u>Demystifying Windows 11: The Intricacies of Its File System</u></a></li>
<li><a href="https://win11.techidaily.com/does-file-explorer-keep-crashing-on-windows-11-try-these-fixes/"><u>Does File Explorer Keep Crashing on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-enhance-your-dell-screen-with-newest-compatible-drivers/"><u>Download and Enhance Your Dell Screen with Newest Compatible Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-screen-recording-with-audio-in-the-latest-snipping-tool-update-max-156/"><u>Efficient Screen Recording with Audio in the Latest Snipping Tool Update (Max 156)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortlessly-eliminate-black-screens-on-asus-pcs/"><u>Effortlessly Eliminate Black Screens on Asus PCs</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-0x80070194-in-onedrive-errors/"><u>Eliminating Windows' 0X80070194 in OneDrive Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/engaging-epics-youtubes-finest-storytellers-for-23-for-2024/"><u>Engaging Epics  YouTube's Finest Storytellers for '23 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/error-2e-prevention-ensure-windows-update-works/"><u>Error 2E Prevention, Ensure Windows Update Works</u></a></li>
<li><a href="https://extra-resources.techidaily.com/essential-oculus-rift-adventures-for-gamers/"><u>Essential Oculus Rift Adventures for Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-inability-to-reach-mb-services-in-windows-11-devices/"><u>Fixing the Inability to Reach MB Services in Windows 11 Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/framing-your-story-with-effective-titles/"><u>Framing Your Story with Effective Titles</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579195236-google-plays-top-kid-friendly-app-mondly-family-edition/"><u>Google Play's Top Kid-Friendly App: Mondly Family Edition!</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-solving-blue-screens-caused-by-not-handled-error/"><u>Guide to Solving Blue Screens Caused by Not Handled Error</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-y17s-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-biometric-authentication-in-11th-gen-windows/"><u>How to Enable Biometric Authentication in 11Th Gen Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-disabled-discord-overlay/"><u>How to Reactivate Windows' Disabled Discord Overlay</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-motorola-razr-40-ultra-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-swiftly-install-latest-drivers-on-your-lenovo-t430s-laptop-comprehensive-windows-walkthrough/"><u>How to Swiftly Install Latest Drivers on Your Lenovo T430s Laptop – Comprehensive Windows Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/improving-vlc-media-player-reducing-buffer-lags-on-win/"><u>Improving VLC Media Player: Reducing Buffer Lags on Win</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-iphone-12-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From iPhone 12</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-htc-u23-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your HTC U23 Phone FRP Lock</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-photomod-editor-skills-review/"><u>In 2024, PhotoMod Editor Skills Review</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-file-explorer-with-onedrive-integration/"><u>Initiating File Explorer with OneDrive Integration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-rdp-troubleshooting-in-windows-oses/"><u>Mastering RDP Troubleshooting in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-reset-for-mail-and-calendars-in-w11/"><u>Mastering the Reset for Mail & Calendars in W11</u></a></li>
<li><a href="https://win11.techidaily.com/meet-the-new-wave-exciting-laptops-from-ifa-2023/"><u>Meet the New Wave - Exciting Laptops From IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-network-nooks-for-your-windows-11s-mac/"><u>Navigating the Network Nooks for Your WIndows 11'S MAC</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-harmonyvoices-mastering-cross-platform-audio-synchronization-in-adobe-premiere-pro/"><u>New HarmonyVoices Mastering Cross-Platform Audio Synchronization in Adobe Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-issues-of-not-allowing-file-writes-on-windows-11/"><u>Overcoming Issues of Not Allowing File Writes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-stuck-on-size-errors-with-easy-solutions-for-windows-discousers/"><u>Overcoming Stuck-On-Size Errors with Easy Solutions for Windows DiscoUsers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-office-activation-roadblocks/"><u>Overcoming Windows Office Activation Roadblocks</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-measures-eliminate-email-from-logon-window/"><u>Privacy Measures: Eliminate Email From Logon Window</u></a></li>
<li><a href="https://win11.techidaily.com/reawakening-computers-top-8-windows-restart-techniques/"><u>Reawakening Computers: Top 8 Windows Restart Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/silent-speakers-unveil-audio-steps-immediately/"><u>Silent Speakers? Unveil Audio Steps Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/spruce-up-your-windows-mail-and-schedule-with-pics/"><u>Spruce Up Your Window's Mail & Schedule With Pics</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-revealing-hidden-windows-drives/"><u>Strategies for Revealing Hidden Windows Drives</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-tweaks-to-the-android-resource-management-system/"><u>Surgical Tweaks to the Android Resource Management System</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-calendars-ifttt-meets-microsoft-to-do/"><u>Syncing Calendars: IFTTT Meets Microsoft To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-beginners-guide-to-microsoft-copilot/"><u>The Ultimate Beginner's Guide to Microsoft Copilot</u></a></li>
<li><a href="https://win-forum.techidaily.com/third-party-uninstaller-do-i-really-need-it-revo-uninstaller/"><u>Third-Party Uninstaller - Do I Really Need It? - Revo Uninstaller</u></a></li>
<li><a href="https://hardware-help.techidaily.com/transform-your-digital-adventures-the-essential-guide-to-geforce-rtx-2080-ti-driver-upgrades/"><u>Transform Your Digital Adventures: The Essential Guide to GeForce RTX 2080 Ti Driver Upgrades</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-resolving-issues-with-your-non-functioning-bose-sound-system/"><u>Troubleshooting Guide: Resolving Issues with Your Non-Functioning Bose Sound System</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-size-calculation-powershell-ways/"><u>Unveiling the Art of Size Calculation: PowerShell Ways</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-old-pcs-less-windows-more-efficiency/"><u>Upgrading Old PCs: Less Windows, More Efficiency</u></a></li>
<li><a href="https://extra-resources.techidaily.com/what-to-expect-when-boosting-performance/"><u>What to Expect When Boosting Performance</u></a></li>
<li><a href="https://win11.techidaily.com/win-sound-troubleshooting-overcoming-silence-hurdles/"><u>Win Sound Troubleshooting: Overcoming Silence Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-screen-sharing-disabling-pin-during-cast/"><u>Windows 11 Screen Sharing: Disabling PIN During Cast</u></a></li>
<li><a href="https://win11.techidaily.com/windows-explorer-excellence-the-ultimate-six-strategies-for-copying-filefolder-paths/"><u>Windows Explorer Excellence: The Ultimate Six Strategies for Copying File/Folder Paths</u></a></li>
</ul></div>
