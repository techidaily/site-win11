---
title: "Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
date: 2024-08-16T00:41:56.122Z
updated: 2024-08-17T00:41:56.122Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
excerpt: "This Article Describes Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
keywords: Win11 Security Controls,Suspending Windows Users,Admin Access Limitation,Immediate Account Lockout,User Management Tools,Secure Windows Environment,Efficient PC Safety
thumbnail: https://thmb.techidaily.com/a49d5779dbd8d3bcb3bf8423c93f4ef941ba145d1cb34757b006a9b7dc8bcdff.jpeg
---

## Security Straightforward: Quick Ways to Suspend User Accounts in Win11

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
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-explore-the-journey-creating-a-one-of-a-kind-tiktok-hash/"><u>[New] In 2024, Explore the Journey  Creating a One-of-a-Kind TikTok Hash</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-navigate-your-way-to-the-best-idevice-apps-for-extracting-content-from-facebook/"><u>[New] In 2024, Navigate Your Way to the Best iDevice Apps for Extracting Content From Facebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-the-art-of-viral-youtube-shorts-content/"><u>[New] Mastering the Art of Viral YouTube Shorts Content</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-tropical-tango-toucan/"><u>[New] Tropical Tango Toucan</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-epic-recordings-the-best-timelapse-software/"><u>[Updated] Epic Recordings  The Best Timelapse Software</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fluidity-in-filming-a-deep-dive-into-inshots-transition-features/"><u>[Updated] Fluidity in Filming  A Deep Dive Into Inshot's Transition Features</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-metaverse-makeover-easy-avatar-construction/"><u>[Updated] The Metaverse Makeover  Easy Avatar Construction</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-bring-pics-into-action-blur-technique/"><u>2024 Approved  Bring Pics Into Action  Blur Technique</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ai-enhanced-naming-mastery-for-podcast-creatives/"><u>AI-Enhanced Naming Mastery for Podcast Creatives</u></a></li>
<li><a href="https://extra-information.techidaily.com/augmenting-learning-with-vr/"><u>Augmenting Learning with VR</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/cataloging-fb-video-ratios-for-2024/"><u>Cataloging FB Video Ratios for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-ideal-12-substitutes-for-itunes-navigate-windows-and-mac-alternatives-ahead-of-2024/"><u>Discover the Ideal 12 Substitutes for iTunes: Navigate Windows & Mac Alternatives Ahead of 2024!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/elite-trailer-showcase-collection/"><u>Elite Trailer Showcase Collection</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-change-installing-and-utilizing-themes-from-the-ms-store/"><u>Embracing Change: Installing and Utilizing Themes From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-adobe-photoshop-in-windows-11-and-11/"><u>Fixing Unresponsive Adobe Photoshop in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-concepts-in-windows-display-idleness/"><u>Fundamental Concepts in Windows Display Idleness</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-time-and-date-on-win-11-ui-bar/"><u>Hiding or Showing Time & Date on Win 11 UI Bar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-failed-vms-from-vmware-in-windows-11/"><u>How to Resolve Failed VMs From VMware in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-resolve-oppo-reno-9a-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Oppo Reno 9A Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-spark-10-4g-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Spark 10 4G to PC? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-apple-iphone-15-pro-max-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From Apple iPhone 15 Pro Max? Heres the Best Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-joke-generation-made-simple-kapwing-app-guide/"><u>In 2024, Joke Generation Made Simple – Kapwing App Guide</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-gpts-error-correction-top-6-strategies-for-success/"><u>Mastering GPT's Error Correction: Top 6 Strategies for Success</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-gaming-with-playnite-and-emulators/"><u>Maximizing Windows Gaming with Playnite and Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-active-directory-printer-failures/"><u>Navigating and Resolving Active Directory Printer Failures</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-for-rapid-epic-games-access/"><u>Optimizing Windows for Rapid Epic Games Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-store-access-blockades/"><u>Overcoming Microsoft Store Access Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-11s-system-tray-secrets/"><u>Revealing Windows 11'S System Tray Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-keys-in-windows-10-and-11-with-7-hacks/"><u>Speeding Up Keys in Windows 10 & 11 with 7 Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-windows-11-interface-for-maximum-comfort/"><u>Tailoring Your Windows 11 Interface for Maximum Comfort</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-local-users-and-groups-on-win1110/"><u>The Complete Guide to Local Users and Groups on WIN11/10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unseen-drives-in-windows/"><u>Troubleshooting: Unseen Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-vac-refusal-on-windows/"><u>Understanding and Rectifying VAC Refusal on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-microsofts-copilot-key-insights-for-windows-11-users/"><u>Unlocking Microsoft's Copilot Key: Insights for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-successful-oculus-installer-on-ws11ws10/"><u>Unlocking Successful Oculus Installer on WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-of-windows-error-0xca00a009/"><u>Unpacking the Mystery of Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-custom-shortcut-for-safe-hardware-disconnect/"><u>Windows 11: Custom Shortcut for Safe Hardware Disconnect</u></a></li>
<li><a href="https://win11.techidaily.com/winstall-workflows-for-smooth-windows-11-app-installation/"><u>Winstall Workflows for Smooth Windows 11 App Installation</u></a></li>
</ul></div>
