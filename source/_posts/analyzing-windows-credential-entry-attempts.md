---
title: Analyzing Windows Credential Entry Attempts
date: 2024-07-13T11:03:49.710Z
updated: 2024-07-14T11:03:49.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Analyzing Windows Credential Entry Attempts
excerpt: This Article Describes Analyzing Windows Credential Entry Attempts
keywords: Windows Credential Attacks,Password Entry Analysis,Security Credential Checks,Access Credential Monitoring,Cybersecurity Alert System,User Credential Tracking,Intrusion Detection Services
thumbnail: https://thmb.techidaily.com/c9e5ca8d00ac8479f694130618d3f9a3080c0193f44d3a38cfaa7537d0961fac.png
---

## Analyzing Windows Credential Entry Attempts

 Windows lets you create multiple user accounts to let multiple users use a single computer. But what if you suspect someone to have accessed your PC or user account without your knowledge?

 While physically monitoring your computer all the time is not feasible for most people, the built-in Windows log utility, Event Viewer, can reveal the recent activities on your computer, including login attempts. Here we show you how to audit failed and successful login attempts in Windows using Event Viewer and other methods.

## How to Enable Logon Auditing via Group Policy Editor

 You need to enable logon auditing in Group Policy Editor to be able to view login audit in Event Viewer. While this feature may be enabled by default on some computers, you can also enable logon auditing manually by following these steps.

 Note that Group Policy Editor is only available on the Pro, Edu, and Enterprise edition of the Windows OS. If you are on the Home edition, follow our guide to [enable gpedit in the Windows home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

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

 The [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

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

 Similarly, for failed login attempts, review**Event ID 4625** . In the**Properties** dialog, you can find reasons for the failed login attempt and the affected user account. If you find multiple instances of unsuccessful attempts, consider learning [how to limit the number of failed login attempts to protect your Windows PC](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) .

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
<li><a href="https://win11.techidaily.com/taking-out-trash-onedrive-from-your-pcs-file-explorer/"><u>Taking Out Trash: OneDrive From Your PC's File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-10-online-stores-for-personalized-box-designs/"><u>Top 10 Online Stores for Personalized Box Designs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-shuttered-creations-sudden-delete-incidents/"><u>[New] In 2024, Shuttered Creations  Sudden Delete Incidents</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-streams-stopping-abrupt-download-drops/"><u>Optimize Windows Streams: Stopping Abrupt Download Drops</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-optimal-cloud-audio-devices/"><u>In 2024, Optimal Cloud Audio Devices</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-audio-hurdles-with-windows-11-system-upgrades/"><u>Overcoming Xbox Audio Hurdles with Windows 11 System Upgrades</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-stay-snappin-strategies-for-unbroken-streaks/"><u>[New] Stay Snappin'  Strategies for Unbroken Streaks</u></a></li>
<li><a href="https://facebook.techidaily.com/no-one-left-behind-facebook-group-membership-shout-outs/"><u>No One Left Behind: Facebook Group Membership Shout-Outs</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/boost-creativity-and-engagement-10-best-sources-of-free-slide-show-patterns/"><u>Boost Creativity and Engagement - 10 Best Sources of Free Slide Show Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-usefulness-of-pagefilesys-backup-storage/"><u>Decoding Windows’ Usefulness of Pagefile.sys Backup Storage</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-freedom-through-jokes-ranking-the-most-hilarious-social-media-prisons/"><u>[New] In 2024, Freedom Through Jokes  Ranking the Most Hilarious Social Media Prisons</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-automatic-detect-of-proxy-issues/"><u>Fixing Windows' Automatic Detect of Proxy Issues</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-equipment-guide-for-dynamic-documentary-making/"><u>[Updated] Equipment Guide for Dynamic Documentary Making</u></a></li>
<li><a href="https://win11.techidaily.com/windows-program-commands-keybinding-setup/"><u>Windows Program Commands: Keybinding Setup</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-excellence-in-emoji-creation-leading-discotools/"><u>[Updated] 2024 Approved  Excellence in Emoji Creation  Leading DiscoTools</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-utilizing-qr-scanners-in-windows/"><u>The Ultimate Guide to Utilizing QR Scanners in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-top-meme-maker-apps-for-android-and-ios-devices/"><u>Updated In 2024, Top Meme Maker Apps for Android and iOS Devices</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sync-windows-plus-android-via-flow-app/"><u>Streamlining Sync: Windows + Android via Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-video-illumination-masters-editor-reviews-for-2024/"><u>Updated Video Illumination Masters Editor Reviews for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-accessing-and-saving-fb-stories-made-simple-5-top-tactics-mobiledesktop-for-2024/"><u>[New] Accessing & Saving FB Stories Made Simple  5 Top Tactics (Mobile/Desktop) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/securing-access-how-to-use-windows-11s-security-interface/"><u>Securing Access: How to Use Windows 11'S Security Interface</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-preserve-your-animated-fun-discover-the-best-9-gif-recorder-apps-for-pc/"><u>[New] 2024 Approved  Preserve Your Animated Fun  Discover the Best 9 GIF Recorder Apps for PC</u></a></li>
<li><a href="https://driver-install.techidaily.com/model-c6515-software-updates-guide/"><u>Model C6515: Software Updates Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-premier-mac-tools-beyond-bandicam/"><u>[Updated] In 2024, Premier Mac Tools Beyond Bandicam</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-school-inspired-themes-for-win-11/"><u>Turn On School-Inspired Themes for Win 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-seamless-screen-record-for-windows-11/"><u>2024 Approved  Seamless Screen Record for Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-it-is-easy-to-separate-the-audio-from-the-video-in-davinci-resolve-but-to-avail-of-this-feature-you-need-to-follow-proper-steps-and-this-a/"><u>New 2024 Approved It Is Easy to Separate the Audio From the Video in DaVinci Resolve. But, to Avail of This Feature, You Need to Follow Proper Steps, and This Article Is All About It</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-new-browsing-potential-with-gesture-controls-in-microsoft-written-by-ai/"><u>Unlocking New Browsing Potential with Gesture Controls in Microsoft' Written by AI</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-iphone-x876-owners-must-have-gif-apps-guide/"><u>In 2024, IPhone X/8/7/6 Owners' Must-Have GIF Apps Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-blue-screen-crisis-tackle-wdf-complaints/"><u>Windows Blue Screen Crisis: Tackle WDF Complaints</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-using-luts-in-spark-ar-and-download-free-luts/"><u>2024 Approved  Using LUTs in Spark AR & Download Free LUTs</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-package-open-failures-in-win11win10-systems/"><u>Navigating Package Open Failures in Win11/Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-screen-share-in-teams/"><u>Steps to Restore Screen Share in Teams</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-insiders-guide-to-pro-windows-10-expertise/"><u>[New] Insider's Guide to Pro WINDOWS 10 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-programs-without-admin-privileges-on-windows/"><u>How to Uninstall Programs Without Admin Privileges on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/typingpros-guide-to-swift-typing-using-typingaid/"><u>TypingPros Guide to Swift Typing Using TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ring-the-mechanisms-of-noteworthy-youtube-discussions-for-2024/"><u>Exploring the Mechanisms of Noteworthy YouTube Discussions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-windows-11-theme-archive/"><u>The Forgotten Windows 11 Theme Archive</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oneplus-11r-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked OnePlus 11R Phone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-oppo-reno-11-5g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Oppo Reno 11 5G Black and White | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-from-apple-iphone-12-mini-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes From Apple iPhone 12 mini?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
</ul></div>
