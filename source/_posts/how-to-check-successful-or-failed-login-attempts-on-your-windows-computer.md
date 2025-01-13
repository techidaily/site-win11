---
title: How to Check Successful or Failed Login Attempts on Your Windows Computer
date: 2025-01-12T02:20:00.698Z
updated: 2025-01-13T02:00:25.089Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close Group Policy Editor and move to the next set of steps to view login attempts in Event Viewer.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-effortless-techniques-for-second-rate-signature-cleanup/"><u>[New] In 2024, Effortless Techniques for Second-Rate Signature Cleanup</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-odds-comprehensive-take-on-vegas-pro-2021/"><u>[New] Navigating the Odds Comprehensive Take on Vegas Pro 2021</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-transforming-views-11-keys-to-thriving-in-facebook-video-marketing/"><u>[New] Transforming Views 11 Keys to Thriving in Facebook Video Marketing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-snap-into-hilarity-meme-creation-made-simple/"><u>[Updated] Snap Into Hilarity Meme Creation Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-digital-brushstroke-with-these-7-apps-on-win10/"><u>Discover Your Digital Brushstroke with These 7 Apps on Win10</u></a></li>
<li><a href="https://win-data.techidaily.com/erleichternde-schritte-zum-abrufen-von-google-drive-dokumenten-im-offline-modus-zwei-ansatze-erklart/"><u>Erleichternde Schritte Zum Abrufen Von Google Drive Dokumenten Im Offline-Modus: Zwei Ansätze Erklärt</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-casting-with-chrome-to-your-amazon-firestick/"><u>Guide: Casting with Chrome to Your Amazon Firestick</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unjam-the-sluggish-windows-11-search-bar-in-interface-settings/"><u>How to Unjam the Sluggish Windows 11 Search Bar in Interface Settings</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/precise-and-wireless-the-sabrent-portable-traveling-mouse-with-high-quality-cable-connections/"><u>Precise & Wireless: The Sabrent Portable Traveling Mouse with High-Quality Cable Connections</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-trust-in-windows-hello-with-easy-fixes/"><u>Reinstating Trust in Windows Hello with Easy Fixes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/save-200-on-alienwares-spectacular-32-4k-240hz-oled-gaming-display-aw3225qf/"><u>Save $200 on Alienware’s Spectacular 32 4K, 240Hz OLED Gaming Display: AW3225QF</u></a></li>
<li><a href="https://win11.techidaily.com/shake-off-slowness-windows-11s-accelerated-fixes/"><u>Shake Off Slowness: Windows 11'S Accelerated Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-web-surfing-how-to-test-your-windows-connection/"><u>Smooth Web Surfing: How to Test Your Windows Connection</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-access-navigating-file-shares-on-latest-windows-update/"><u>Streamlined Access: Navigating File Shares On Latest Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/swift-fixes-addressing-error-code-0x80040610-in-outlook-and-windows/"><u>Swift Fixes: Addressing Error Code 0X80040610 in Outlook and Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-ungrouping-taskbar-elements/"><u>Techniques for Ungrouping Taskbar Elements</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-art-of-balancing-video-quality-and-adsense-revenue/"><u>The Art of Balancing Video Quality & AdSense Revenue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/trustworthy-and-safe-the-best-of-free-software-downloads/"><u>Trustworthy and Safe: The Best of Free Software Downloads</u></a></li>
</ul></div>

