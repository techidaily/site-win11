---
title: "Disabling Users with Precision: Four Easy Techniques on Win11"
date: 2024-08-15T23:43:40.365Z
updated: 2024-08-16T23:43:40.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disabling Users with Precision: Four Easy Techniques on Win11"
excerpt: "This Article Describes Disabling Users with Precision: Four Easy Techniques on Win11"
keywords: Win11 Security Disable,Precision User Lockout,Win11 Control Methods,Enhance Win11 Safety,Easy Tech Lockdown,Windows 11 Secure Halt,Techniques to Lock PC
thumbnail: https://thmb.techidaily.com/de2b8c65401e9876b1b1a5fbf84a14916f9f22a18062d51200fd6852f871f665.jpg
---

## Disabling Users with Precision: Four Easy Techniques on Win11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to [enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevate-entertainment-a-thousand-gaming-channels/"><u>[New] 2024 Approved  Elevate Entertainment  A Thousand Gaming Channels</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-funimate-pro-apk-a-complete-guide/"><u>[New] Funimate Pro APK  A Complete Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-radiance-and-refine-essential-editing-secrets-revealed/"><u>[New] Radiance and Refine  Essential Editing Secrets Revealed</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-step-by-step-guide-to-effective-screen-recording-with-mobizen/"><u>[New] Step-by-Step Guide to Effective Screen Recording with Mobizen</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-the-easy-way-to-mix-and-match-youtube-playlist-order/"><u>[New] The Easy Way to Mix and Match YouTube Playlist Order</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unleash-the-full-spectrum-of-sound-best-apps-for-music-videos/"><u>[New] Unleash the Full Spectrum of Sound  Best Apps for Music Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-a-step-by-step-for-delving-into-fb-archives/"><u>[Updated] In 2024, A Step-by-Step for Delving Into FB Archives</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-cutting-edge-top-11-list-of-soundscape-capturers/"><u>[Updated] In 2024, Cutting-Edge Top 11 List of Soundscape Capturers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-ultimate-guide-to-cross-platform-movie-capture/"><u>[Updated] In 2024, The Ultimate Guide to Cross-Platform Movie Capture</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-loop-video-magic-keep-your-followers-hooked-with-instagram-boomers-for-2024/"><u>[Updated] Loop Video Magic  Keep Your Followers Hooked with Instagram Boomers for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-instagram-4-pro-tips-for-looped-video-content-for-2024/"><u>[Updated] Mastering Instagram  4 Pro Tips for Looped Video Content for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-stepping-stones-from-youtube-ads-to-monetary-success/"><u>[Updated] Stepping Stones From YouTube Ads to Monetary Success</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-the-comprehensive-guide-to-acquiring-instagram-ringtones-and-creating-noteworthy-chimes/"><u>[Updated] The Comprehensive Guide to Acquiring Instagram Ringtones & Creating Noteworthy Chimes</u></a></li>
<li><a href="https://win11.techidaily.com/0x8004def5-on-onedrive-unraveling-windows-11-troubles/"><u>0X8004DEF5 on OneDrive - Unraveling Windows 11 Troubles</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-creating-a-professional-periscope-presence/"><u>2024 Approved  Creating a Professional Periscope Presence</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-in-depth-look-at-tomtom-bandit-camera-series/"><u>2024 Approved  In-Depth Look at TomTom Bandit Camera Series</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-your-windows-photo-app/"><u>A Comprehensive Guide to Fixing Your Windows Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-group-policies-with-the-gpresult-command/"><u>A Deeper Dive Into Group Policies with the GPResult Command</u></a></li>
<li><a href="https://win11.techidaily.com/a-scholarly-approach-to-embracing-hdr-in-windows-11-workflows/"><u>A Scholarly Approach to Embracing HDR in Windows 11 Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-mend-windows-1011-discord-errors/"><u>A Step-by-Step Approach to Mend Windows 10/11 Discord Errors</u></a></li>
<li><a href="https://win11.techidaily.com/a-visionary-approach-to-taskbar-design-essential-improvements-for-microsofts-new-release/"><u>A Visionary Approach to Taskbar Design: Essential Improvements for Microsoft's New Release</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-finding-documents-with-windows-11-taskbar-search-feature/"><u>Accelerate Finding Documents with Windows 11 Taskbar Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/access-gpos-securely-a-guide-to-win11s-tools/"><u>Access GPOs Securely: A Guide to Win11's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-windows-10-navigating-as-a-first-timer/"><u>Accessible Windows 10: Navigating as a First-Timer</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-full-control-with-admin-cmd-role/"><u>Achieve Full Control with Admin CMD Role</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-seamless-software-operation-with-4-key-pcts/"><u>Achieve Seamless Software Operation with 4 Key PCTs</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-terminal-for-quake-interface/"><u>Activating Windows Terminal for Quake Interface</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audacitys-portaudio-hiccup-on-windows-11-and-11/"><u>Addressing Audacity’s PortAudio Hiccup on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-audio-playback-on-windows/"><u>Addressing Disrupted Audio Playback on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-profile-not-valid-issue-for-users-in-windows/"><u>Addressing Profile Not Valid Issue for Users in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-utorrent-setup-problems-on-microsoft-windows/"><u>Addressing uTorrent Setup Problems on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11s-unresponsive-wi-fi-detection/"><u>Addressing Windows 11'S Unresponsive Wi-Fi Detection</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-configuration-for-optimal-android-resource-use/"><u>Advanced Configuration for Optimal Android Resource Use</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-mobile-devices-for-windows-mic-input/"><u>Amplify Mobile Devices for Windows Mic Input</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-infrastructure-with-windows-software/"><u>Augmenting Linux Infrastructure with Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-chaos-tidy-up-your-icons/"><u>Avoid Visual Chaos: Tidy Up Your Icons</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-fluff-remove-windows-search-images/"><u>Avoid Visual Fluff: Remove Windows Search Images</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-management-application-hiccups/"><u>Avoid Windows Management Application Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-edge-how-to-get-rid-of-it-in-w11/"><u>Avoiding Edge: How to Get Rid of It in W11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/barriers-to-success-unveiling-the-reasons-behind-teredos-non-qualification/"><u>Barriers to Success: Unveiling the Reasons Behind Teredo's Non-Qualification</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-oneplus-ace-2v-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove OnePlus Ace 2V Fingerprint Lock</u></a></li>
<li><a href="https://win11.techidaily.com/boost-notability-of-your-scribbles-with-strategic-sticky-note-placement-in-win-os/"><u>Boost Notability of Your Scribbles with Strategic Sticky Note Placement in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/break-through-windows-barriers-be-an-admin-now/"><u>Break Through Windows Barriers - Be an Admin Now</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windowsstore-app-folder-secrets/"><u>Breaking Into WindowsStore App Folder Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/1719302930005-bypass-incompatibility-woes-in-windows-xp-7-and-8-easily/"><u>Bypass Incompatibility Woes in Windows XP, 7 & 8 Easily.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722193330070-gpt-4-universally-accessible-6-reasons-to-persist-with-platinum-plan/"><u>GPT-4 Universally Accessible; 6 Reasons to Persist with Platinum Plan</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-xiaomi-redmi-note-12r-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Xiaomi Redmi Note 12R to iPhone | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 with a Mask On</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-elevate-your-edit-6-essential-adobe-premiere-pro-tips-and-techniques/"><u>New 2024 Approved Elevate Your Edit 6 Essential Adobe Premiere Pro Tips and Techniques</u></a></li>
<li><a href="https://program-issues.techidaily.com/no-more-bugs-updated-euro-truck-simulator-terrific-for-pc-with-improved-performance-and-stability/"><u>No More Bugs! Updated Euro Truck Simulator Terrific for PC with Improved Performance and Stability</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-vivo-v27e-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Vivo V27e Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/reclaiming-functionality-of-asus-internal-cam/"><u>Reclaiming Functionality of Asus Internal Cam</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-ai-communication-7-insider-tricks-to-elevate-your-prompt-skills/"><u>Revolutionize AI Communication: 7 Insider Tricks to Elevate Your Prompt Skills</u></a></li>
<li><a href="https://driver-download.techidaily.com/seamlessly-install-updated-drivers-on-your-lenovo-t430s-laptop-the-fast-way-with-windows/"><u>Seamlessly Install Updated Drivers on Your Lenovo T430s Laptop: The Fast Way with Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/smooth-strategy-perfecting-your-instagram-grid-for-2024/"><u>Smooth Strategy  Perfecting Your Instagram Grid for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-oppo-find-x7-ultra-by-drfone-android/"><u>Top 10 Password Cracking Tools For Oppo Find X7 Ultra</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleash-creativity-with-these-7-cutting-edge-ai-tools-for-flawless-presentations/"><u>Unleash Creativity with These 7 Cutting-Edge AI Tools for Flawless Presentations</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/valkomman-swedens-hjartlig-visa/"><u>Välkomman: Sweden's Hjärtlig Visa</u></a></li>
</ul></div>
