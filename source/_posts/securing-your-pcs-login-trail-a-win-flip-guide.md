---
title: "Securing Your PC's Login Trail: A Win-Flip Guide"
date: 2024-08-15T23:29:14.711Z
updated: 2024-08-16T23:29:14.711Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Securing Your PC's Login Trail: A Win-Flip Guide"
excerpt: "This Article Describes Securing Your PC's Login Trail: A Win-Flip Guide"
keywords: Secure PC Logins,Win-Flip Security Guide,Safe Computer Access,Login Tracking Protection,Cybersecurity Tips,Prevent Unauthorized Entry,Strong Password Practices
thumbnail: https://thmb.techidaily.com/2ef59ce044e2e7e5ba0e6dcc5016c001910532c3893cef165601b78313e08b44.jpg
---

## Securing Your PC's Login Trail: A Win-Flip Guide

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
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to View Failed and Successful Login Attempts in Event Viewer

 The [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) lets you view Windows logs for the application, security, system, and other events. While a useful application to troubleshoot system issues, you can use it to audit login events on your Windows PC.

 Follow these steps to view failed and successful login attempts in Windows:

1. Press the**Win key** and type**event viewer.** Alternatively, click on**Search** in the taskbar and type**event viewer.**
2. Click on**Event Viewer** from the search result to open it.
3. In the left pane, expand the**Windows Logs** section.  
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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

## How to View the Last Logon History Using Command Prompt

![view specific user last login attempt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/view-specific-user-last-login-attempt-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the Command Prompt to view the last login attempt. It is a handy way to find user-based login attempts without having to go through all the logon events in Event Viewer.

To view the login history of a specific user using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** . While holding the**Ctrl + Shift key** , click**OK** . This will open the**Command Prompt** as administrator.
3. In the Command Prompt window, type the following command and press Enter:  
`net user administrator | findstr /B /C:"Last logon"`
4. In the above command, replace "administrator" with the username to view their login history.
5. The output will show the last login time and date for the specified user.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-mov-in-the-cloud-top-six-techniques-for-windows-11-users/"><u>[New] In 2024, .MOV in the Cloud - Top Six Techniques for Windows 11 Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-ultimate-guide-to-boosting-sale-traffic-top-15-fb-analysis-tools-reviewed/"><u>[New] In 2024, The Ultimate Guide to Boosting Sale Traffic  Top 15 FB Analysis Tools Reviewed</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-expert-advice-seamless-srt-file-sharing-across-all-social-networks/"><u>[Updated] 2024 Approved  Expert Advice  Seamless SRT File Sharing Across All Social Networks</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-youtubes-top-marketing-moves-for-business-growth-unveiled/"><u>[Updated] 2024 Approved  YouTube's Top Marketing Moves for Business Growth Unveiled</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-mp3-recording-made-simple-with-skype-for-free/"><u>[Updated] In 2024, MP3 Recording Made Simple with Skype for FREE</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-banish-soundless-tweets-live-the-sounds/"><u>2024 Approved  Banish Soundless Tweets  Live the Sounds</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-superior-avi-media-player-ideal-for-all-devices/"><u>2024 Approved  Superior AVI Media Player - Ideal for All Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unleash-your-creative-potential-with-full-length-vivacut-review-24/"><u>2024 Approved  Unleash Your Creative Potential with Full-Length VivaCut Review '24</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-writable-html-in-email-settings/"><u>Addressing Windows 11' Writable HTML in Email Settings</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-handle-installation-hiccups-win11/"><u>Clearing Up Confusion: How to Handle Installation Hiccups (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-hibernate-depression-in-windows/"><u>Combatting Hibernate Depression in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-guide-choosing-every-email-with-gmails-quick-selection/"><u>Complete Guide: Choosing Every Email with Gmail's Quick Selection</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-corrupted-filesystems-in-windows-11/"><u>Correcting Corrupted Filesystems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-file-access-failures-in-windows/"><u>Correcting File Access Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/digging-into-drive-labels-c-and-d-unpacked/"><u>Digging Into Drive Labels: C & D Unpacked</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-typing-speed-7-latency-fixes-revealed/"><u>Enhance Windows 11 Typing Speed: 7 Latency Fixes Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-anydesk-troubleshooting-in-windows/"><u>Essential Techniques: AnyDesk Troubleshooting in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-limit-windows-sonic-amplification/"><u>How To Limit Windows Sonic Amplification</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-blend-voice-recordings-into-ppt-framework/"><u>In 2024, Blend Voice Recordings Into PPT Framework</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-easy-guide-to-see-youtube-liked-comments/"><u>In 2024, Easy Guide to See YouTube Liked Comments</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-expert-strategies-for-home-based-podcast-recordings/"><u>In 2024, Expert Strategies for Home-Based Podcast Recordings</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-realme-gt-neo-5-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Realme GT Neo 5 Lock Screen Password?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-nubia-red-magic-8s-proplus-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Nubia Red Magic 8S Pro+ Phone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Tecno Spark 20C? | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-seamless-mobile-broadcasting-best-budget-streamer-list/"><u>In 2024, Seamless Mobile Broadcasting  Best Budget Streamer List</u></a></li>
<li><a href="https://win11.techidaily.com/instant-use-of-snipping-tool-on-modern-windows-os/"><u>Instant Use of Snipping Tool on Modern Windows OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-apple-iphone-13-pro-fixed-drfone-by-drfone-virtual-ios/"><u>iSpoofer is not working On Apple iPhone 13 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-the-load-on-your-pc-with-efficient-wlanextexe/"><u>Lowering the Load on Your PC with Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/mending-missing-window-steam-play-integration/"><u>Mending Missing Window-Steam Play Integration</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-conflicting-camera-requests-windows-error-0xa00f4243/"><u>Mitigating Conflicting Camera Requests (Windows, Error 0xA00F4243)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-cinematic-mastery-expert-tips-for-editing-in-final-cut-pro-x/"><u>New In 2024, Cinematic Mastery Expert Tips for Editing in Final Cut Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/no-drive-letters-investigating-the-causes-and-remedies-for-windows-users/"><u>No Drive Letters: Investigating the Causes & Remedies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/pixelated-paths-walking-through-oldschool-pc-world-in-dosbox-x/"><u>Pixelated Paths: Walking Through Oldschool PC World in DOSBox-X</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-fame-formula-amplify-your-insta-presence-with-content-for-2024/"><u>Quick Fame Formula  Amplify Your Insta Presence with Content for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-se-2022-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/replacing-default-pdf-handler-in-windows-os/"><u>Replacing Default PDF Handler in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-onedrive-lockout-windows-user-guide-needed/"><u>Reverse OneDrive Lockout: Windows User Guide Needed</u></a></li>
<li><a href="https://win11.techidaily.com/rog-ally-in-question-how-does-asus-stack-up/"><u>ROG Ally in Question: How Does ASUS Stack Up?</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-large-archiving-tasks-with-windows-powershell-tips/"><u>Simplifying Large Archiving Tasks with Windows PowerShell Tips</u></a></li>
<li><a href="https://win11.techidaily.com/standby-struggles-dissecting-modern-standby-issues/"><u>Standby Struggles: Dissecting Modern Standby Issues</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-navigation-in-windows-11/"><u>Sticky Note Navigation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-counteract-the-black-screen-on-steam/"><u>Strategies to Counteract the Black Screen on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-flashing-screens-on-win1011-quick-fixes/"><u>Tackling Flashing Screens on WIN10/11: Quick Fixes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-lenovo-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Lenovo Phone Hassle-Free</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-vivo-v29-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Vivo V29 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-playbook-9-proven-fixes-for-smooth-windows-videos/"><u>The Ultimate Playbook: 9 Proven Fixes for Smooth Windows Videos</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/thumbnail-design-for-engagement-a-youtube-resizing-guide/"><u>Thumbnail Design for Engagement  A YouTube Resizing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlinked-file-program-resolution-for-windows-pc-users/"><u>Unlinked File Program Resolution for Windows PC Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unveiling-the-pathway-to-monetizing-your-instagram-content/"><u>Unveiling the Pathway to Monetizing Your Instagram Content</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-operational-health-mastering-the-top-5-availability-tests/"><u>Windows 11 Operational Health: Mastering the Top 5 Availability Tests</u></a></li>
</ul></div>
