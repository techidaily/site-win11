---
title: The Ultimate Guide to Wipe Out Email at Sign-In
date: 2024-11-26T00:38:43.329Z
updated: 2024-11-27T22:14:18.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Wipe Out Email at Sign-In
excerpt: This Article Describes The Ultimate Guide to Wipe Out Email at Sign-In
keywords: Email Sign-In Eradication Guide,Wipe Out Login SMS Attacks,Preventing Phishing on Logins,Email Authentication Systems,Secure User Identification,Anti-Phish Login Protection,Optimal Email Verification Methods
thumbnail: https://thmb.techidaily.com/9b3d4059cce82d617824aff75bbe2c1cfb1dda056b7a7373daee332b511aa58b.jpg
---

## The Ultimate Guide to Wipe Out Email at Sign-In

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.

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
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-mac-screen-recorders-top-10-free-list-for-2024/"><u>[Updated] Essential Mac Screen Recorders – Top 10 FREE List for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-video-capture-crusade-obs-vs-shadowcast/"><u>[Updated] In 2024, Video Capture Crusade OBS Vs ShadowCast</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-unblock-videos-from-twitter-in-chrome-for-2024/"><u>[Updated] Unblock Videos From Twitter in Chrome for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-honor-magic-6-pro-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Honor Magic 6 Pro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-5-essential-sites-revolutionizing-how-we-style-text/"><u>2024 Approved 5 Essential Sites Revolutionizing How We Style Text</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-apeaksofts-screen-recorder-mastery-2023-exposed/"><u>2024 Approved Apeaksoft's Screen Recorder Mastery - 2023 Exposed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/activating-grid-view-in-google-meet-webinars-a-step-by-step-guide/"><u>Activating Grid View in Google Meet Webinars A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-could-not-create-vm-issue-in-windows-os/"><u>Correcting 'Could Not Create VM' Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-clipboard-functionality-in-windows-11s-edge-shielding-mode/"><u>Enabling Clipboard Functionality in Windows 11'S Edge Shielding Mode</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-screen-resolution-in-windows-11/"><u>Fine-Tuning Screen Resolution in Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-free-tribe-50-branding-banners-ready-to-unleash/"><u>In 2024, Free Tribe 50 Branding Banners Ready to Unleash!</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-computer-controls-internationally-using-powertoys-capabilities/"><u>Master Your Computer Controls Internationally Using PowerToys' Capabilities</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-mac-users-download-vllo-and-find-the-best-alternatives/"><u>New 2024 Approved Mac Users Download VLLO and Find the Best Alternatives</u></a></li>
<li><a href="https://games-able.techidaily.com/proactive-measures-for-joining-top-notch-discord-servers/"><u>Proactive Measures for Joining Top-Notch Discord Servers</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-restore-file-editability-on-windows-devices/"><u>Solutions to Restore File Editability on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-eliminating-read-only-files-in-win10win11/"><u>Strategies for Eliminating Read-Only Files in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-stop-random-cmd-openings-on-windows-devices/"><u>Strategies to Stop Random CMD Openings on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-guide-enabling-imessage-for-non-ios-devices/"><u>The Insider’s Guide: Enabling iMessage for Non-iOS Devices</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-productivity-potential-merging-to-dot-ifttt/"><u>Unleash Productivity Potential: Merging To-Dot, IFTTT</u></a></li>
</ul></div>

