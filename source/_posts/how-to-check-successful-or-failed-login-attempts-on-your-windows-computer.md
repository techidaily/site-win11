---
title: How to Check Successful or Failed Login Attempts on Your Windows Computer
date: 2024-08-16T00:55:15.982Z
updated: 2024-08-17T00:55:15.982Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Check Successful or Failed Login Attempts on Your Windows Computer
excerpt: This Article Describes How to Check Successful or Failed Login Attempts on Your Windows Computer
keywords: Login Status Windows,Failed Login Tracking,Windows Login Verification,Validate Windows Logins,Detect Failed Logins Windows,Successful Windows Logins,Monitor Windows Sign-Ins
thumbnail: https://thmb.techidaily.com/84772a0e20318a50277b6d80239d31259f3d754cba45388a4148935e78d13735.jpg
---

## How to Check Successful or Failed Login Attempts on Your Windows Computer

 Windows lets you create multiple user accounts to let multiple users use a single computer. But what if you suspect someone to have accessed your PC or user account without your knowledge?

 While physically monitoring your computer all the time is not feasible for most people, the built-in Windows log utility, Event Viewer, can reveal the recent activities on your computer, including login attempts. Here we show you how to audit failed and successful login attempts in Windows using Event Viewer and other methods.

## How to Enable Logon Auditing via Group Policy Editor

 You need to enable logon auditing in Group Policy Editor to be able to view login audit in Event Viewer. While this feature may be enabled by default on some computers, you can also enable logon auditing manually by following these steps.

 Note that Group Policy Editor is only available on the Pro, Edu, and Enterprise edition of the Windows OS. If you are on the Home edition, follow our guide to[enable gpedit in the Windows home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Note that if you don't configure your Group Policy for Logon Auditing, you can only view the successful login attempts in Event Viewer.

 Once you have the Group Policy Editor enabled, follow these steps to enable logon auditing:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open the**Group Policy Editor.**
3. Next, navigate to the following location:  
`Computer Configuration > Windows Settings > Security Settings > Local Policies > Audit Policy`
4. In the right pane, right-click on**Audit logon events** and select**Properties** .  
![group policy editor audit logon events properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties.jpg)
5. In the**Properties** dialog, select**Success** and**Failure** options under the**Audit these attempts** section.  
![group policy editor audit logon events properties enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/group-policy-editor-audit-logon-events-properties-enable.jpg)
6. Click**Apply** and**OK** to save the changes.

 Close Group Policy Editor and move to the next set of steps to view login attempts in Event Viewer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to View Failed and Successful Login Attempts in Event Viewer

 The[Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

 Follow these steps to view failed and successful login attempts in Windows:

1. Press the**Win key** and type**event viewer.** Alternatively, click on**Search** in the taskbar and type**event viewer.**
2. Click on**Event Viewer** from the search result to open it.
3. In the left pane, expand the**Windows Logs** section.  
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

 Similarly, for failed login attempts, review**Event ID 4625** . In the**Properties** dialog, you can find reasons for the failed login attempt and the affected user account. If you find multiple instances of unsuccessful attempts, consider learning[how to limit the number of failed login attempts to protect your Windows PC](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) .

 Below is the list of all nine**Logon Types** for logon events that you may encounter reviewing login events in Event Viewer:

| **Logon Type** | **Description**                                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Logon Type 2   | A local user logged on to this computer.                                                                                                          |
| Logon Type 3   | A user logged on to this computer from the network.                                                                                               |
| Logon Type 4   | Batch logon type without user intervention – Scheduled Tasks, etc.                                                                                |
| Logon Type 5   | Logon by system service started by Service Control Manager – Most common type                                                                     |
| Logon Type 7   | System unlocked by a local account user                                                                                                           |
| Logon Type 8   | NetworkClearText - Logon attempted over the network where the password was sent as clear text.                                                    |
| Logon Type 9   | NewCredentials – triggered when a user uses the RunAs command with the /netonly option to start a program.                                        |
| Logon Type 10  | RemoteInteractive – Generated when a computer is accessed via a remote access tool such as Remote Desktop Connection.                             |
| Logon Type 11  | CachedInteractive – When the user logged on to the computer via console using the cached credentials when the domain controller is not available. |

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Viewing Failed and Successful Login Attempts in Windows

 If you suspect someone to have logged in to your PC, the Event Viewer will likely catch and record the attempt. For this to work, you must enable the Logon Auditing policy in Group Policy Editor. You can also use Command Prompt to view a specific user's login history.

 That said, anyone who knows their way around Event Viewer can easily clear the logs. So, if anything, beefing up your Windows computer security is the best way to prevent unauthorized access. You can begin by limiting the number of failed login attempts on your Windows PC.

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-on-demand-acting-rights-form/"><u>[New] 2024 Approved  On-Demand Acting Rights Form</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-xbox-power-up-with-these-top-hard-drives-rankings/"><u>[New] 2024 Approved  Xbox Power-Up with These Top Hard Drives Rankings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-alternative-solutions-to-game-bar-recording-for-2024/"><u>[New] Alternative Solutions to Game Bar Recording for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-comparing-screen-recorders-the-leader-vs-contenders/"><u>[Updated] In 2024, Comparing Screen Recorders  The Leader Vs. Contenders</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-premiere-pro-masterclass-essential-templates-for-free/"><u>[Updated] In 2024, Premiere Pro Masterclass - Essential Templates for Free</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-quick-recap-how-to-locate-youtube-comments-post-upload/"><u>[Updated] Quick Recap  How to Locate YouTube Comments Post-Upload</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-10-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-premium-viewing-in-depth-hisense-50-h8f-4k-hdr-television-evaluation/"><u>Affordable Premium Viewing: In-Depth Hisense 50 H8F 4K HDR Television Evaluation</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-sony-xperia-1-v-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Sony Xperia 1 V Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/behind-the-scenes-how-to-master-voice-manipulation-with-free-tools-for-2024/"><u>Behind the Scenes  How to Master Voice Manipulation with Free Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-typing-prowess-changing-and-adding-keyboards-for-win-11/"><u>Boost Typing Prowess: Changing and Adding Keyboards for Win 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/boosting-snapchat-impact-select-6-excellent-video-editors-for-2024/"><u>Boosting Snapchat Impact  Select 6 Excellent Video Editors for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/enhance-your-swipe-rate-ingenious-tips-for-standout-bios-for-2024/"><u>Enhance Your Swipe Rate  Ingenious Tips for Standout Bios for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-update-cpu-drivers-in-windows/"><u>How To Update CPU Drivers In Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ideal-places-to-enjoy-vr-films/"><u>Ideal Places to Enjoy VR Films</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-from-iphone-6-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock From iPhone 6? How to Fix it?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nubia-z50-ultra-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nubia Z50 Ultra to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-switch-cards-between-apple-iphone-x-and-other-iphones-will-move-all-phone-services-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Switch Cards Between Apple iPhone X and other iPhones Will Move All Phone Services? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/japanese-salutations-key-phrases-for-perfect-greeting/"><u>Japanese Salutations: Key Phrases for Perfect Greeting</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-natural-windows-file-sorting-settings/"><u>Restoring Natural Windows File Sorting Settings</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solving-valheims-launch-difficulties-tips-for-a-smooth-startup/"><u>Solving Valheim's Launch Difficulties: Tips for a Smooth Startup</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-gaming-mastering-the-art-of-fc-mascot/"><u>Step Up Your Gaming: Mastering the Art of FC Mascot</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reopen-nvidia-control-panel-in-win-11/"><u>Steps to Reopen Nvidia Control Panel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-from-crashing-windows-1110/"><u>Steps to Stop Microsoft Teams From Crashing Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-persistent-ps4-controller-connections-in-windows/"><u>Strategies for Persistent PS4 Controller Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sync-chrome-and-pc-time-seamlessly-on-windows/"><u>Sync Chrome and PC Time Seamlessly on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-the-footprints-of-your-latest-window-use/"><u>Tracing the Footprints of Your Latest Window Use</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-microsoft-store-operation-on-windows-11/"><u>Unhindered Microsoft Store Operation on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-oppo-f25-pro-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Oppo F25 Pro 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-hidden-gems-unlocking-full-potential/"><u>Windows 11'S Hidden Gems: Unlocking Full Potential</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
</ul></div>
