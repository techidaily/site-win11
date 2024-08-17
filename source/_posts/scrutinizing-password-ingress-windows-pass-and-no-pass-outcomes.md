---
title: "Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes"
date: 2024-08-15T23:45:04.509Z
updated: 2024-08-16T23:45:04.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes"
excerpt: "This Article Describes Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes"
keywords: Windows Pass Access,Password Entry Analysis,Pass Security Checks,No-Password Scenarios,Login Protocol Review,Windows Authentication,Password Ingress Study
thumbnail: https://thmb.techidaily.com/c68e5dfe066870e624209e946a88b5eb21db8406cf2fae44c9a446c53d02efdc.jpg
---

## Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
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
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-skills.techidaily.com/new-premiere-music-collections-for-visual-media/"><u>[New] Premiere Music Collections for Visual Media</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-step-in-step-approach-hulu-recording-tutorial-for-diverse-systems/"><u>[Updated] 2024 Approved  Step-In-Step Approach  Hulu Recording Tutorial for Diverse Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-explore-the-best-ever-ios-platforms-for-ps2-games/"><u>[Updated] In 2024, Explore the Best-Ever IOS Platforms for PS2 Games</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-magic-behind-immersive-world-creation/"><u>[Updated] The Magic Behind Immersive World Creation</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-discovering-the-syma-x5c-the-premier-drone-for-rookies/"><u>2024 Approved  Discovering the Syma X5C  The Premier Drone for Rookies</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-instagram-sound-essentials-for-personalization/"><u>2024 Approved  Instagram Sound Essentials for Personalization</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-look-of-window-11s-search-field/"><u>Altering the Look of Window 11'S Search Field</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-act-equalizing-pc-and-mobile-internet-speeds/"><u>Balancing Act: Equalizing PC & Mobile Internet Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-windows-access-denied-error-code-0x80070522/"><u>Correcting the Windows Access Denied Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-cpu-gpu-and-ram-usage-figures-on-pcs/"><u>Deciphering CPU, GPU, & RAM Usage Figures on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-reasons-for-preserving-your-win-11-alerts/"><u>Discover the Reasons for Preserving Your Win 11 Alerts</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-official-logitech-g29-steering-wheel-drivers-for-windows-users/"><u>Download the Official Logitech G29 Steering Wheel Drivers for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-browsing-post-windows-installation/"><u>Effortless Browsing Post-Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-user-biometric-use-by-domains/"><u>Enabling/Disabling User Biometric Use by Domains</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-updating-halt-from-e8024002e/"><u>Eradicating Windows Updating Halt From E:8024002E</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/essential-20-hysterical-detention-cell-gifs-to-amplify-your-online-joy-for-2024/"><u>Essential 20 Hysterical Detention Cell Gifs to Amplify Your Online Joy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-a-simple-pin-a-comprehensive-approach-to-switching-passwords-in-windows-11/"><u>From a Simple PIN: A Comprehensive Approach to Switching Passwords in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/future-trends-how-machine-learning-is-reshaping-the-way-we-find-information-online/"><u>Future Trends: How Machine Learning Is Reshaping the Way We Find Information Online</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722964440152-get-the-newest-canon-d530-firmware-version-free-download-available-now/"><u>Get the Newest Canon D530 Firmware Version – Free Download Available Now</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-overcoming-geforce-nows-xc0f1103f-problem-in-win11/"><u>Guides to Overcoming GeForce Now’s Xc0f1103f Problem in Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-reinstall-hardware-drivers-in-windows-11107-by-drivereasy-guide/"><u>How to use Device Manager to reinstall hardware drivers in Windows 11/10/7</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-honor-magic-6-lite-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Honor Magic 6 Lite to iPhone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-motorola-razr-40-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Motorola Razr 40 to iPod | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-y78tfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo Y78tFRP Lock</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-oppo-a56s-5g-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Oppo A56s 5G to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-insights-new-folder-formation-in-windows-11/"><u>Innovative Insights: New Folder Formation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instant-setup-acquiring-adobe-reader-via-ms-store/"><u>Instant Setup: Acquiring Adobe Reader via MS Store</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/july-2024-release-of-updated-passwords-for-popular-d-link-routers-and-modems/"><u>July 2024 Release of Updated Passwords for Popular D-Link Routers and Modems</u></a></li>
<li><a href="https://win11.techidaily.com/keep-it-neat-how-to-make-windows-recycle-bin-self-cleanse/"><u>Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-key-combinations-for-effortless-recalibration/"><u>Mastering Windows: Key Combinations for Effortless Recalibration</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-windows-0x80242016-update-fails/"><u>Navigating Past Windows' 0X80242016 Update Fails</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsofts-safe-mode-only-constraint/"><u>Navigating Through Microsoft's Safe Mode Only Constraint</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-issues/"><u>Navigating Through Windows 10/11'S Recycle Bin Issues</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-startup-changing-boot-timeout-in-windows-11/"><u>Optimize Startup: Changing Boot Timeout in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/procedures-for-resolving-unresponsive-installation-on-windows-os/"><u>Procedures for Resolving Unresponsive Installation on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/screen-notes-made-easy-winning-sticky-pad-solutions-for-pc/"><u>Screen Notes Made Easy: Winning Sticky Pad Solutions for PC</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smart-pc-enhancement-add-gmail-bar-to-taskbar-border/"><u>Smart PC Enhancement: Add Gmail Bar to Taskbar Border</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-blue-screen-errors-with-vmware-on-win11/"><u>Strategies to Address Blue Screen Errors with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/the-science-behind-windows-11s-streamlined-file-safety-measures/"><u>The Science Behind Windows 11’S Streamlined File Safety Measures</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-line-up-of-artistic-software-for-windows-10/"><u>The Ultimate Line-Up of Artistic Software for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-making-ai-images-with-paint-tool-sai/"><u>Transform Windows 11: Making AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unlock-creative-potential-strategic-use-of-strikethrough/"><u>Unlock Creative Potential  Strategic Use of Strikethrough</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-potential-with-latest-patch-details/"><u>Unlocking Windows 11'S Potential with Latest Patch Details</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-taskbar-while-running-full-screen-edges/"><u>Unveiling Hidden Taskbar While Running Full Screen Edges</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
</ul></div>
