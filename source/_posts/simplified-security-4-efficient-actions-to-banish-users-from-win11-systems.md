---
title: "Simplified Security: 4 Efficient Actions to Banish Users From Win11 Systems"
date: 2024-08-08T13:17:10.684Z
updated: 2024-08-09T13:17:10.684Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplified Security: 4 Efficient Actions to Banish Users From Win11 Systems"
excerpt: "This Article Describes Simplified Security: 4 Efficient Actions to Banish Users From Win11 Systems"
keywords: Win11 Security Tips,User Bans in Windows,Win11 Ban Protection,Simplified Win11 Safety,Efficient Win11 Actions,Secure Win11 Systems,Win11 Unauthorized Blocking
thumbnail: https://thmb.techidaily.com/09207a7f08746a7a51db3d8aa3727dd060158727f29a32ea31aadbe48cebcd72.jpg
---

## Simplified Security: 4 Efficient Actions to Banish Users From Win11 Systems

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you[add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .
4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
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
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/024-approved-enhance-your-youtube-journey-with-analytic-know-how/"><u>[New] 2024 Approved  Enhance Your YouTube Journey with Analytic Know-How</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-leading-edge-technology-in-capturing-virtual-meetings-5-top-picks-for-2024/"><u>[New] Leading Edge Technology in Capturing Virtual Meetings (5 Top Picks) for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-novel-approaches-to-saving-instagram-stories-for-2024/"><u>[New] Novel Approaches to Saving Instagram Stories for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-secret-vlc-tactics-for-optimal-viewing-experience/"><u>[New] Secret VLC Tactics for Optimal Viewing Experience</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-social-media-savvy-making-memorable-facebook-reels-for-2024/"><u>[New] Social Media Savvy  Making Memorable Facebook Reels for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-5-mac-voice-capture-apps-compiling-peak-performances/"><u>[New] Top 5 Mac Voice Capture Apps  Compiling Peak Performances</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-top-flight-tech-best-drone-gimbals-for-2024/"><u>[New] Top Flight Tech  Best Drone Gimbals for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-visionary-vistas-the-ultimate-list-of-motivating-ig-images/"><u>[New] Visionary Vistas  The Ultimate List of Motivating IG Images</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-impressive-initiations-podcasting-prose-poems/"><u>[Updated] Impressive Initiations  Podcasting Prose Poems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-social-streaming-success-maximizing-video-impact-with-desktop-integration-on-facebook/"><u>[Updated] In 2024, Social Streaming Success  Maximizing Video Impact with Desktop Integration on Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-audioanalyzer-reaction-to-recordings/"><u>2024 Approved  AudioAnalyzer  Reaction to Recordings</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-maximizing-views-on-tiktok-unboxing-content/"><u>2024 Approved  Maximizing Views on TikTok Unboxing Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-spy-on-fb-chronicles-unseen/"><u>2024 Approved  Spy on FB Chronicles, Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://win11.techidaily.com/7-common-concerns-against-moving-to-windows-11/"><u>7 Common Concerns Against Moving to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-fixes-for-troublesome-email-notifications-in-windows/"><u>9 Essential Fixes for Troublesome Email Notifications in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-snap-configurations-via-powertoys/"><u>A Comprehensive Guide to Windows Snap Configurations via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-tutorial-on-windows-11-hotspot-setup-procedures/"><u>A Comprehensive Tutorial on Windows 11 Hotspot Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-a00f429f-in-windows-camera-functionality/"><u>Addressing Error A00F429F in Windows' Camera Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies!</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-pc-a-guide-to-optimizing-windows-11-options/"><u>Adjusting Your PC: A Guide to Optimizing Windows 11 Options</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-the-non-functional-windows-enter-key/"><u>Ameliorating the Non-Functional Windows Enter Key</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/amplify-your-footage-the-power-of-enhancer-22/"><u>Amplify Your Footage  The Power of Enhancer 2.2</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-unlicensed-adobe-errors/"><u>Avoid Windows 'Unlicensed' Adobe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-manual-inputs-embracing-ai-in-windows-operations/"><u>Beyond Manual Inputs: Embracing AI in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-capabilities-upgrading-to-virtualbox-70-in-win11/"><u>Boost Your VM Capabilities: Upgrading to VirtualBox 7.0 in Win11</u></a></li>
<li><a href="https://program-issues.techidaily.com/comprehhavie-solution-overcoming-nioh-2-game-instability/"><u>Comprehhavie Solution: Overcoming Nioh 2 Game Instability</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-the-logitech-unifying-receiver-software-compatible-with-windows/"><u>Download the Logitech Unifying Receiver Software Compatible with Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-zte-axon-40-lite-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked ZTE Axon 40 Lite Phone | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-infinix-note-30-5g-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Infinix Note 30 5G</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-cutting-the-excess-a-guide-to-shortening-youtube-videos/"><u>In 2024, Cutting the Excess  A Guide to Shortening YouTube Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-magnify-marvel-the-ultimate-10-camera-lens-guide/"><u>In 2024, Magnify Marvel  The Ultimate 10 Camera Lens Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-your-blueprint-to-mastering-the-snapchat-boomerang-skill/"><u>In 2024, Your Blueprint to Mastering the Snapchat Boomerang Skill</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mac-users-video-gems-a-showcase/"><u>Mac User's Video Gems: A Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/1719335120399-python-package-installation/"><u>Python Package Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/1719336618337-quick-fix-guide-overcome-incompatibility-in-windows-xp/"><u>Quick-Fix Guide: Overcome Incompatibility in Windows XP</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-premier-screen-picks-for-ps5-and-xbox-games-for-2024/"><u>The Premier Screen Picks for PS5 and Xbox Games for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-lava-storm-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Lava Storm 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719320103482-windows-xbox-not-working-fix-it-fast/"><u>Windows Xbox Not Working? Fix It Fast!</u></a></li>
</ul></div>
