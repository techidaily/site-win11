---
title: "Keeping Tabs on PC Login: Separating Goals From Errors"
date: 2024-07-13T09:43:23.435Z
updated: 2024-07-14T09:43:23.435Z
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
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/5-top-realistic-text-to-speech-ai-voice-generators-you-may-like-for-2024/"><u>5 Top Realistic Text to Speech AI Voice Generators You May Like for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-best-10-customizable-filters-for-personalized-videos/"><u>2024 Approved  Best 10 Customizable Filters for Personalized Videos</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-vivo-y17s-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Vivo Y17s Phone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastery-in-making-your-art-a-successful-nft-with-top-7-tools/"><u>In 2024, Mastery in Making Your Art a Successful NFT with Top 7 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://video-capture.techidaily.com/an-easy-to-follow-methodology-for-initiating-a-productive-skype-conversation-among-various-os-users/"><u>An Easy-to-Follow Methodology for Initiating a Productive Skype Conversation Among Various OS Users</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-to-unknown-not-initialized-in-windows/"><u>Step-by-Step Fix to 'Unknown Not Initialized' In Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-create-a-custom-slide-show-in-powerpoint/"><u>Updated 2024 Approved How to Create a Custom Slide Show in PowerPoint</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-solve-package-problems-in-windows-oses/"><u>Strategies to Solve Package Problems in Windows OSes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-oppo-a2-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Oppo A2</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-ultimate-5-display-choices-for-ps5/"><u>[Updated] In 2024, Ultimate 5 Display Choices  For PS5</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-transforming-facebook-videos-steps-to-high-definition/"><u>[Updated] 2024 Approved  Transforming Facebook Videos  Steps to High Definition</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-installing-new-drivers-in-windows-11/"><u>Mastering the Art of Installing New Drivers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-profitable-pathways-8-steps-for-youtube-earning/"><u>In 2024, Profitable Pathways  8 Steps for YouTube Earning</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/professional-setup-for-screen-capture-during-games/"><u>Professional Setup for Screen Capture During Games</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/why-gamers-should-trust-windows-vision-and-performance/"><u>Why Gamers Should Trust Windows' Vision and Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-realme-note-50-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Realme Note 50 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-boot-and-tpm-activationdeactivation-in-vbox-70/"><u>Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-amplifying-your-digital-footprint-the-ins-and-outs-of-using-voxal-voice-changer-on-discord/"><u>New 2024 Approved Amplifying Your Digital Footprint The Ins and Outs of Using Voxal Voice Changer on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fixes-conquering-the-fatal-javascript-glitch-in-discord-win-11/"><u>Step-by-Step Fixes: Conquering the Fatal Javascript Glitch in Discord Win 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-essence-of-burst-in-gopro-filming-techniques/"><u>The Essence of Burst in GoPro Filming Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-the-art-of-action-shots-with-gopro-for-2024/"><u>Mastering the Art of Action Shots with GoPro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-os-security-patches/"><u>Navigating Windows OS Security Patches</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-14-pro-max-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/operating-unity-windows-rolls-out-across-apple-pc-mac-android-world/"><u>Operating Unity: Windows Rolls Out Across Apple, PC, Mac, Android World</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-conductors-toolkit-unpackaging-the-finest-digital-audio-workstations-for-2024/"><u>New The Conductors Toolkit Unpackaging the Finest Digital Audio Workstations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/maxing-out-melodies-best-5-apps-for-boosting-windows-audio-by-100plus/"><u>Maxing Out Melodies: Best 5 Apps for Boosting Windows' Audio By 100%%+</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-free-and-fabulous-the-best-4k-video-editing-software-options/"><u>In 2024, Free and Fabulous The Best 4K Video Editing Software Options</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-using-lesser-known-windows-11-assets-efficiently/"><u>Pro-Tips for Using Lesser Known Windows 11 Assets Efficiently</u></a></li>
<li><a href="https://games-able.techidaily.com/7-essential-edge-advantages-that-make-it-a-gamers-browser/"><u>7 Essential Edge Advantages that Make It a Gamer's Browser</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-oppo-reno-10-pro-5g-using-video-repair-utility-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix Corrupt video files of Oppo Reno 10 Pro 5G using Video Repair Utility?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-os-public-ip-command-prompt-tricks/"><u>Accessing OS Public IP: Command Prompt Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-oppo-find-x6-pro-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Oppo Find X6 Pro Phone Password Using Emergency Call</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-catchy-counterpoint-the-best-backwards-song-videos-of-this-year/"><u>In 2024, Catchy Counterpoint The Best Backwards Song Videos of This Year</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/to-keep-or-not-to-delete-the-case-of-pagefilesys/"><u>To Keep or Not to Delete: The Case of Pagefile.sys</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-revolutionize-your-content-harnessing-the-power-of-fb-lives-for-2024/"><u>[New] Revolutionize Your Content  Harnessing the Power of FB Lives for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-how-to-do-screen-recording-on-ipad/"><u>[Updated] In 2024, How to Do Screen Recording on iPad?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-xs-max-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>iPhone XS Max Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
</ul></div>
