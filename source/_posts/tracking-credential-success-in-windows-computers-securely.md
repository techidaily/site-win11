---
title: Tracking Credential Success in Windows Computers Securely
date: 2024-08-28T00:50:14.974Z
updated: 2024-08-29T00:50:14.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tracking Credential Success in Windows Computers Securely
excerpt: This Article Describes Tracking Credential Success in Windows Computers Securely
keywords: Windows Credential Guard,Secure Tracking Methods,Safeguard PC Security,Password Management Tips,Windows Authentication,Cybersecurity for PC,Data Protection Strategies
thumbnail: https://thmb.techidaily.com/bdc516c407f1c047ce69fce10934901af5b77e56306af6bf8cabd1b35043cc3e.jpg
---

## Tracking Credential Success in Windows Computers Securely

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-mics-on-mission-find-the-best-for-your-youtube-channels-vision-and-voice/"><u>[New] 2024 Approved  Mics on Mission  Find the Best for Your YouTube Channel’s Vision & Voice</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-channels-standing-with-these-tactics/"><u>[New] In 2024, Elevate Your Channel's Standing with These Tactics</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-the-fastest-way-to-scan-windows-files/"><u>[New] In 2024, The Fastest Way to Scan Windows Files</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-storage-odyssey-navigating-cloud-leaders-of-2024/"><u>[New] The Ultimate Storage Odyssey  Navigating Cloud Leaders of 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-earning-edge-reached-for-subscribers-above-500/"><u>[Updated] 2024 Approved  Earning Edge Reached for Subscribers Above 500</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-edit-like-a-pro-10-must-know-tips-for-newbies/"><u>[Updated] 2024 Approved  Edit Like a Pro  10 Must-Know Tips for Newbies</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-lenssplit-viewer-insight/"><u>[Updated] 2024 Approved  LensSplit Viewer Insight</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-guide-to-video-to-audio-10-best-tools-reviewed-for-2024/"><u>[Updated] Expert Guide to Video-to-Audio  #10 Best Tools Reviewed for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-analyzing-authenticity-point-in-visual-identity-sharing-platforms/"><u>[Updated] In 2024, Analyzing Authenticity’ Point in Visual Identity Sharing Platforms</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-strategies-for-syncing-zoom-meetings-across-devices-for-2024/"><u>[Updated] Strategies for Syncing Zoom Meetings Across Devices for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-pcs-finest-ps3-simulators-for-gaming-enthusiasts/"><u>2024 Approved  PC's Finest PS3 Simulators for Gaming Enthusiasts</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-starting-and-participating-in-zoom-meetings-from-android-devices/"><u>2024 Approved  Starting and Participating in Zoom Meetings From Android Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-honor-x7b-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Honor X7b | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discover-the-critical-considerations-for-purchasing-a-new-video-game-console-today/"><u>Discover the Critical Considerations for Purchasing a New Video Game Console Today</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-your-zexmte-bluetooth-device-driver-for-windows-versions-xpvista7/"><u>Download Your ZexMTE Bluetooth Device Driver for Windows Versions (XP/Vista/7)</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-data-handling-enabledisable-ntfs-compression-in-win11/"><u>Efficient Data Handling: Enable/Disable NTFS Compression in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-cmd-shortcuts-for-streamlined-workflow/"><u>Essential Windows Cmd Shortcuts for Streamlined Workflow</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-the-best-15-standout-stop-motion-films-of-all-time/"><u>Explore the Best  15 Standout Stop-Motion Films of All Time</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-source-disk-unreadable-issue-in-windows-systems/"><u>Fixing Source Disk Unreadable Issue in Windows Systems</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-nokia-c32-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-lost-wifi-connections-on-windows/"><u>Guidelines for Restoring Lost WiFi Connections on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cure-inactive-usb-ports-and-devices-in-microsoft-os/"><u>How to Cure Inactive USB Ports & Devices in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-system-restore-to-revert-windows/"><u>How to Use System Restore to Revert Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-cricket-iphone-12-for-free-by-drfone-ios/"><u>In 2024, How To Unlock Cricket iPhone 12 for Free</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovating-with-snapchats-new-highlight-feature-for-2024/"><u>Innovating with Snapchat's New Highlight Feature for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/installation-procedures-windows-11-and-vmware-workstation-17/"><u>Installation Procedures: Windows 11 & VMWare Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-textbooks-top-8-effective-learning-techniques-for-windows/"><u>Master the Textbooks: Top 8 Effective Learning Techniques for Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/niche-networking-on-youtube-from-phone-small-scale-approach-for-2024/"><u>Niche Networking on Youtube From Phone, Small-Scale Approach for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-system-idleness-altering-boot-timeout-in-win11/"><u>Reducing System Idleness: Altering Boot Timeout in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenate-old-pcs-with-windows-11-to-go-and-rufus-tutorial/"><u>Rejuvenate Old PCs with Windows 11, To Go & Rufus Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-cant-share-desktop-across-screens/"><u>Resolving Error: Can’t Share Desktop Across Screens</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-league-disconnects-in-windows-os/"><u>Resolving League Disconnects in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-zip-operations-on-windows-systems/"><u>Seamless Multi-Zip Operations on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-prime-viewing-fixing-windows-11-audio-subtitle-discrepancies/"><u>Seamless Prime Viewing: Fixing Windows 11 Audio-Subtitle Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/securing-steam-readwrite-success-in-os-x/"><u>Securing Steam Read/Write Success in OS X</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/smart-shoppers-checklist-what-to-inspect-in-a-pre-owned-ipad/"><u>Smart Shopper's Checklist: What To Inspect In A Pre-Owned iPad</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-function-keys-not-adjusting-display-brighness-on-win-11/"><u>Solutions for Function Keys Not Adjusting Display Brighness on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-the-steam-lag-in-windows-11-gaming-environment/"><u>Solutions to the Steam Lag in Windows 11 Gaming Environment</u></a></li>
<li><a href="https://tech-revival.techidaily.com/solving-pc-launch-problems-for-outriders-enthusiasts-guide/"><u>Solving PC Launch Problems for Outriders Enthusiasts (Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stabilize-changing-printer-on-desktop-os/"><u>Steps to Stabilize Changing Printer on Desktop OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-alleviating-usb-shortage-on-pcs/"><u>Strategies for Alleviating USB Shortage on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-salvaging-deleted-files-from-your-system/"><u>Swiftly Salvaging Deleted Files From Your System</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-clearing-black-pixels-in-winsteam/"><u>Techniques for Clearing Black Pixels in WinSteam</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-complete-process-of-scheduling-google-meets-for-2024/"><u>The Complete Process of Scheduling Google Meets for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-edge-cutting-edge-visual-notes-methodology/"><u>The Obsidian Edge: Cutting-Edge Visual Notes Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-exploration-windows-display-breaks/"><u>The Ultimate Exploration: Windows Display Breaks</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-buying-windows-11-keys/"><u>The Ultimate Guide to Buying Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-solutions-for-overcoming-hypervisorbsod-in-windows/"><u>Top 5 Solutions for Overcoming HYPERVISOR_BSOD in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-picks-best-xbox-hdd-models-reviewed-for-2024/"><u>Top Picks  Best Xbox HDD Models Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-11-select-6-must-install-android-apps/"><u>Transforming Windows 11: Select 6 Must-Install Android Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-potential-with-top-notch-fps-counters-for-windows-11-gamers/"><u>Unleashing Your Potential with Top-Notch FPS Counters for Windows 11 Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-pc-potential-top-tips-to-troubleshoot-broken-keyboard-commands-in-windows/"><u>Unlocking PC Potential: Top Tips to Troubleshoot Broken Keyboard Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unplugging-issues-keeping-usbs-active-on-windows-11/"><u>Unplugging Issues: Keeping USBs Active on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-character-viewer-in-windows-11/"><u>Unveiling the Character Viewer in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-video-on-the-go-10-best-free-speed-adjustment-apps-for-mobile-editing/"><u>Updated In 2024, Video on the Go 10 Best Free Speed Adjustment Apps for Mobile Editing</u></a></li>
</ul></div>
