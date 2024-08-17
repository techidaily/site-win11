---
title: Analyzing Windows Credential Entry Attempts
date: 2024-08-15T23:31:13.300Z
updated: 2024-08-16T23:31:13.300Z
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

![event viewer security logon event failed attemptjpg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-failed-attemptjpg.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
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
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-deleting-facebook-stories-laptop-and-mobile-guide-for-2024/"><u>[New] Deleting Facebook Stories  Laptop & Mobile Guide for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-must-have-mac-frame-captures-handbook-limited-to-156-characters-for-2024/"><u>[New] Must-Have Mac Frame Captures Handbook (Limited to 156 Characters) for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-vegas-pros-21-landmark-release-a-complete-analysis/"><u>[New] Vegas Pro's '21 Landmark Release - A Complete Analysis</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-rhythmic-instagrams-a-step-by-step-music-guide-for-2024/"><u>[Updated] Rhythmic Instagrams  A Step-by-Step Music Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-poco-c51-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-qt-platform-support-error-for-app-starts/"><u>Addressing 'No Qt Platform Support' Error for App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alert-it-admin-limited-power/"><u>Addressing Windows Alert: IT Admin Limited Power</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-of-taskbar-in-modern-win11/"><u>Boosting Functionality of Taskbar in Modern Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-screen-legibility-win11-scaling-guide/"><u>Boosting Screen Legibility: Win11 Scaling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://win-blog.techidaily.com/end-the-frustration-solve-constant-freezes-in-diablo-iii/"><u>End the Frustration - Solve Constant Freezes in Diablo III</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-on-apple-watch-or-iphone-13-pro-by-drfone-ios/"><u>How To Bypass Activation Lock On Apple Watch Or iPhone 13 Pro?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-samsung-galaxy-s23-fe-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/maximizing-chatgpts-potential-in-academia/"><u>Maximizing ChatGPT's Potential in Academia</u></a></li>
<li><a href="https://buynow-info.techidaily.com/navigating-the-switch-landscape-a-closer-look-at-the-lite-model-and-oled-upgrade/"><u>Navigating the Switch Landscape: A Closer Look at the Lite Model and OLED Upgrade</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-on-your-apple-iphone-xs-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status On Your Apple iPhone XS</u></a></li>
<li><a href="https://win11.techidaily.com/1719350786682-operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-7-thrilling-new-features-of-bard-ai-unveiled-at-the-2023-google-io/"><u>Top 7 Thrilling New Features of BARD AI Unveiled at the 2023 Google I/O</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
<li><a href="https://facebook.techidaily.com/who-monitors-your-uploaded-imagery/"><u>Who Monitors Your Uploaded Imagery?</u></a></li>
</ul></div>
