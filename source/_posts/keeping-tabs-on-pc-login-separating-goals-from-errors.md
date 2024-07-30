---
title: "Keeping Tabs on PC Login: Separating Goals From Errors"
date: 2024-07-29T15:44:06.188Z
updated: 2024-07-30T15:44:06.188Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![event viewer security logon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon.jpg)
4. Next, select**Security** .
5. In the right pane, locate the**Event 4624** entry. It is a user logon event ID, and you may find multiple instances of this ID in the event log.
6. To find failed login attempts, locate**Event ID 2625** entries instead.
7. Next, select the**Event 4624** entry you want to view, and Event Viewer will display all the related information in the bottom section. Alternatively, right-click on the event entry and select**Properties** to view detailed information in a new window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Decipher the Logon Entries in Event Viewer

 While Event ID 4624 is associated with logon events, you will likely find multiple instances of this entry occurring every few minutes in the log. This is due to Event Viewer recording every logon event (whether from the local user account or system services such as Windows Security) with the same event ID**(Event 4624**).

![event viewer security logon event properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties.jpg)

 To identify the source of login, right-click on the event record and select**Properties** . In the**General** tab, scroll down and locate the**Logon information** section. Here, the**Logon Type** field indicates the kind of logon that occurred.

 For example,**Logon Type 5** indicates a service-based login, while**Logon Type 2** indicates user-based login. Know more about the different logon types in the table below.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![event viewer security logon event properties details 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/event-viewer-security-logon-event-properties-details-1.jpg)

 Next, scroll down to the**New Logon** section and locate the**Security ID** . This will show the user account that was affected by the logon.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-video-recordings.techidaily.com/new-creating-simple-videos-top-10-youtube-projects-anyone-can-do/"><u>[New] Creating Simple Videos  Top 10 YouTube Projects Anyone Can Do</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-simple-steps-for-turning-your-smartphone-into-an-effective-camera/"><u>[Updated] 2024 Approved  Simple Steps for Turning Your Smartphone Into an Effective Camera</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-hasty-thumbnail-crafting-for-fortnite-gameplay/"><u>[Updated] In 2024, Hasty Thumbnail Crafting for Fortnite Gameplay</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-evolution-of-streaming-youtube-tv-in-focus-for-2024/"><u>[Updated] The Evolution of Streaming  YouTube TV In Focus for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-vivo-v29-pro-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Vivo V29 Pro? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-obstacles-when-installing-java/"><u>Addressing Common Obstacles When Installing Java</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-enhancement-in-wt-with-personalized-schemes/"><u>Aesthetic Enhancement in WT with Personalized Schemes</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-control-set-active-hours-to-avoid-surprises-on-windows-11/"><u>Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deactivating-mouse-speed-sensitivity-in-windows-1011/"><u>Deactivating Mouse Speed Sensitivity in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-made-easy-essential-windows-fixers-guide/"><u>Debugging Made Easy: Essential Windows Fixers Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://win11.techidaily.com/determine-your-pcs-wattage-usage-on-windows-system/"><u>Determine Your PC's Wattage Usage on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://win11.techidaily.com/easy-paths-back-to-success-in-steam-gaming/"><u>Easy Paths Back to Success in Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-edge-and-keep-your-system-clean-w11/"><u>Eliminate Edge and Keep Your System Clean (W11)</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-photoshopping-in-windows-11-without-hurdles/"><u>Enabling Photoshopping in Windows 11 Without Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/1719222893625-eradicate-failed-capture-on-windows-devices-today/"><u>Eradicate Failed Capture on Windows Devices Today!</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-write-unavailable-issue-in-windows/"><u>Eradicating 'Write Unavailable' Issue in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-motorola-moto-g13-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Motorola Moto G13</u></a></li>
<li><a href="https://win11.techidaily.com/exemplary-protection-in-a-new-era-selecting-four-for-windows-11/"><u>Exemplary Protection in a New Era: Selecting Four for Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-samsung-galaxy-m14-5g-by-drfone-android/"><u>Full Guide to Unlock Your Samsung Galaxy M14 5G</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-itel-p55t-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Itel P55T to Roku | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-samsung-galaxy-s23-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Samsung Galaxy S23 for Streaming | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-win10s-elite-screen-recording-and-capture-software-selection/"><u>In 2024, Win10's Elite Screen Recording & Capture Software Selection</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keep-win10-fresh-actions-for-those-who-skip-11/"><u>Keep Win10 Fresh: Actions for Those Who Skip 11</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-clarity-with-windows-11s-enhanced-photo-app/"><u>Maximizing Image Clarity with Windows 11'S Enhanced Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-connection-error-restoring-mb-link-on-windows-11/"><u>Overcoming Connection Error: Restoring MB Link on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships.</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-lost-connection-top-9-remedies-for-missing-bluetooth-on-win-11/"><u>Revive the Lost Connection: Top 9 Remedies for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-robloxs-restrictive-error-403-on-pc/"><u>Unraveling Roblox's Restrictive Error 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
</ul></div>
