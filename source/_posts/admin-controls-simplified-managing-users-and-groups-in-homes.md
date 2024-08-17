---
title: "Admin Controls Simplified: Managing Users & Groups in Homes"
date: 2024-08-16T00:35:15.394Z
updated: 2024-08-17T00:35:15.394Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Admin Controls Simplified: Managing Users & Groups in Homes"
excerpt: "This Article Describes Admin Controls Simplified: Managing Users & Groups in Homes"
keywords: User Management at Home,Group Control Basics,Simplify Admin Access,Homesite User Guide,Easy Group Settings,Manage Users Efficiently,Simplified Admin Tools
thumbnail: https://thmb.techidaily.com/1382e80fe89cdc85e3f86df652866f8b806d3041c2bfdfcea85ed48c584b9f54.JPG
---

## Admin Controls Simplified: Managing Users & Groups in Homes

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-10-best-hash-monitoring-apps-for-major-social-platforms-fbtwitterinsta/"><u>[New] 2024 Approved  10 Best Hash Monitoring Apps for Major Social Platforms (FB/Twitter/Insta)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevating-video-visibility-through-thumbnails/"><u>[New] 2024 Approved  Elevating Video Visibility Through Thumbnails</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-beaming-login-logout-directions/"><u>[New] Beaming Login / Logout Directions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-hitch-free-methods-igtv-and-story-sharing-for-2024/"><u>[New] Hitch-Free Methods  IGTV and Story Sharing for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-freezeframe-stop-and-screen-retain-guide/"><u>[New] In 2024, FreezeFrame  Stop & Screen Retain Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-premium-list-the-finest-4k-monitors-with-recording-features-for-2024/"><u>[New] Premium List  The Finest 4K Monitors with Recording Features for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-sky-hdr-perfection-top-website-reviews-for-2024/"><u>[New] Sky HDR Perfection - Top Website Reviews for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/imeos-edge-over-youtube-what-the-data-says-for-2024/"><u>[New] Vimeo’s Edge Over YouTube? What the Data Says for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-eliminating-odd-shades-a-step-by-step-guide-to-flawless-greenscreens/"><u>[Updated] In 2024, Eliminating Odd Shades  A Step-by-Step Guide to Flawless Greenscreens</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-ultimate-guide-to-hash-trackers-fb-twt-and-ig-networks/"><u>[Updated] The Ultimate Guide to Hash Trackers  FB, Twt & IG Networks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mastering-video-descriptions-on-instagram/"><u>2024 Approved  Mastering Video Descriptions on Instagram</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-motorola-moto-g23-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola Moto G23 Unlock Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/6-high-performance-windows-video-editors-unveiled/"><u>6 High-Performance Windows Video Editors Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/6-methods-to-supercharge-virtual-machine-speed-in-windows/"><u>6 Methods to Supercharge Virtual Machine Speed in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-confusion-five-windows-cures-to-unsupported-boots/"><u>Clearing Up the Confusion: Five Windows Cures to Unsupported Boots</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolving-inbox-notifications-on-pcs/"><u>Comprehensive Guide to Resolving Inbox Notifications on PCs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/dissecting-the-role-and-value-of-snapchats-ai-with-6-reasons/"><u>Dissecting the Role and Value of Snapchat's AI with 6 Reasons</u></a></li>
<li><a href="https://win11.techidaily.com/elite-screen-grabbers-5-non-windows-counterparts-to-snipping-tool/"><u>Elite Screen Grabbers: 5 Non-Windows Counterparts to Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-vivo-y36i-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Vivo Y36i?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-top-10-filmora-traits-fueling-video-magic/"><u>In 2024, The Top 10 Filmora Traits Fueling Video Magic</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quick-start-deploying-and-operating-the-codegpt-tool-inside-your-visual-studio-environment/"><u>Quick Start: Deploying and Operating the CodeGPT Tool Inside Your Visual Studio Environment</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today!</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-window-11-experience-with-these-6-desired-android-apps/"><u>Revamp Your Window 11 Experience with These 6 Desired Android Apps</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-mastering-window-commands-and-shortcuts/"><u>Streamline Your Workflow: Mastering Window Commands & Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80040610-restoring-smooth-functionality-to-outlook/"><u>Tackling Error 0X80040610: Restoring Smooth Functionality to Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-windows-compatible-webp-viewer-tools/"><u>Top 4 Windows-Compatible WebP Viewer Tools</u></a></li>
<li><a href="https://win11.techidaily.com/transformational-taskbar-update-windows-system-resources-in-view/"><u>Transformational Taskbar Update: Windows System Resources in View</u></a></li>
<li><a href="https://games-able.techidaily.com/unite-for-success-strategies-for-2p-gameplay-in-switchs-minecraft/"><u>Unite for Success: Strategies for 2P Gameplay in Switch’s Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-top-free-must-have-for-win11/"><u>Unleash Potential: Top Free Must-Have for Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updating-your-skills-regularly/"><u>Updating Your Skills Regularly</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-13-mini-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 13 mini i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/yourphone-in-windows-98-should-you-exercranize-it/"><u>YourPhone in Windows 9/8: Should You Exercranize It?</u></a></li>
</ul></div>
