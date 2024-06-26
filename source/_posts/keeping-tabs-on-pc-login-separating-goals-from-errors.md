---
title: "Keeping Tabs on PC Login: Separating Goals From Errors"
date: 2024-06-25T09:41:11.912Z
updated: 2024-06-26T09:41:11.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Keeping Tabs on PC Login: Separating Goals From Errors"
excerpt: "This Article Describes Keeping Tabs on PC Login: Separating Goals From Errors"
keywords: PC Login Security,Avoiding Login Errors,Secure Access Monitoring,PC Login Tracking,Safe Login Practices,Error-Free Login Goals,Tabs on PC Entry
thumbnail: https://thmb.techidaily.com/df14118d9f463815cdf73b98eeffe83796c8ab688c142d4fe510c3cae0e58079.jpg
---

## Keeping Tabs on PC Login: Separating Goals From Errors

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

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

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
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-strategies-your-file-explorer-fixes/"><u>Rebooting Strategies: Your File Explorer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-0x800f0922-update-problem-in-windows-11/"><u>Troubleshoot 0X800f0922 Update Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/direct-paths-unveiling-windows-11-calculator/"><u>Direct Paths: Unveiling Windows 11 Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-cybersecurity-essential-windows-protection-tips/"><u>Mastery in Cybersecurity: Essential Windows Protection Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/masterful-videography-top-15-cameras-selection-guide/"><u>Masterful Videography  Top 15 Cameras Selection Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-insights-tracking-your-insta-posts-viewers-for-2024/"><u>[New] Mastering Insights  Tracking Your Insta Posts' Viewers for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-a-gamers-treasure-chest-top-5-ways-to-record-vr-games-professionally/"><u>In 2024, A Gamer's Treasure Chest  Top 5 Ways to Record VR Games Professionally</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-flex-your-content-collection-with-tiktok-downloads/"><u>[New] Flex Your Content Collection with TikTok Downloads</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-5-leading-photo-video-makers-for-breathtaking-slideshows/"><u>New 2024 Approved 5 Leading Photo Video Makers for Breathtaking Slideshows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-recovering-from-a-mistaken-tiktok-reload/"><u>[New] 2024 Approved  Recovering From a Mistaken TikTok Reload</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-honor-x9a-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Honor X9a FRP Bypass</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-evolutionary-saga-of-vr-worlds/"><u>2024 Approved  The Evolutionary Saga of VR Worlds</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-realme-v30t-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Realme V30T Location on Skout | Dr.fone</u></a></li>
</ul></div>
