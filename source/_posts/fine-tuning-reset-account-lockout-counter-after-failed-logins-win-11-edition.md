---
title: Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
date: 2024-08-15T23:48:35.756Z
updated: 2024-08-16T23:48:35.756Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
excerpt: This Article Describes Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition
keywords: Reset Lockout Windows,Login Failures Fix,Account Unlock Procedure,Win11 Password Recovery,Security Audit for Logins,Counter Failed Attempts,Lockout Settings Win 11
thumbnail: https://thmb.techidaily.com/3854233be38a7a3b692f6b1c87d1917c44d3f0b5ad0376d97a1f07070c0cf22e.jpg
---

## Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-direct-compare-obs-and-twitch-studio-benefits-for-2024/"><u>[New] Direct Compare  OBS and Twitch Studio Benefits for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-flame-the-fire-enhancing-your-snapstreak-game-for-2024/"><u>[New] Flame the Fire  Enhancing Your Snapstreak Game for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-unpublished-photography-scrutiny-and-complementary-selections/"><u>[New] In 2024, Unpublished Photography Scrutiny & Complementary Selections</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-unveiling-the-pathway-to-monetizing-your-instagram-content/"><u>[New] In 2024, Unveiling the Pathway to Monetizing Your Instagram Content</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-xsplit-archive-assessing-video-game-splits-for-2024/"><u>[New] XSplit Archive  Assessing Video Game Splits for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-audience-attracting-innovations-in-fb-video-ad-design-for-2024/"><u>[Updated] Audience-Attracting Innovations in FB Video Ad Design for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-turning-product-analysis-into-income-via-video-platforms/"><u>[Updated] In 2024, Turning Product Analysis Into Income via Video Platforms</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-deciphering-the-language-of-youtube-live-images/"><u>2024 Approved  Deciphering the Language of YouTube Live Images</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-measures-for-disk-read-failure-windows/"><u>Corrective Measures for Disk Read Failure Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-taskmanager-stays-top-focused/"><u>Ensuring TaskManager Stays Top-Focused</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-tips-recording-every-moment-of-skype-on-obs/"><u>Essential Tips  Recording Every Moment of Skype on OBS</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722972354679-find-and-apply-the-latest-windows-printer-drivers-for-your-epson-tm-t88v-step-by-step-download-guide/"><u>Find and Apply the Latest Windows Printer Drivers for Your EPSON TM-T88v - Step by Step Download Guide!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-manipulate-cover-page-editor-in-win11/"><u>How to Access and Manipulate Cover Page Editor in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-implement-windows-rollback-mechanism-via-system-restore/"><u>How to Effectively Implement Windows' Rollback Mechanism via System Restore</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-yellowed-lcd-on-computer-screens/"><u>How to Fix Yellowed LCD on Computer Screens</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-c67-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on C67 5G</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-outlook-failed-error-in-windows/"><u>How to Rectify the 'Outlook Failed' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-safely-and-quickly-upgrade-your-surface-computers-software/"><u>How to Safely and Quickly Upgrade Your Surface Computers' Software</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-play-40c-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor Play 40C to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-issues-with-5ghz-wireless-networks/"><u>Navigating Windows 11 Issues with 5GHz Wireless Networks</u></a></li>
<li><a href="https://win11.techidaily.com/pro-win-efficiency-selecting-the-best-apps-for-window-11-users/"><u>Pro-Win Efficiency: Selecting the Best Apps for Window 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/proposing-a-new-vision-for-windows-11s-taskbar-functionality/"><u>Proposing a New Vision for Windows 11'S Taskbar Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solutions-for-common-cc-problems-on-win11/"><u>Quick Solutions for Common CC Problems on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-the-basics-of-windows-backup-configurations/"><u>Regaining the Basics of Windows Backup Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-windows-1011s-faulty-recycle-bin-error/"><u>Rejuvenating Windows 10/11'S Faulty Recycle Bin Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-broken-links-between-your-epson-scanner-and-printing-device/"><u>Repair Broken Links Between Your Epson Scanner and Printing Device</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-affordable-windows-10-a-comprehensible-guide/"><u>Secrets to Affordable Windows 10: A Comprehensible Guide</u></a></li>
<li><a href="https://win11.techidaily.com/self-sufficient-windows-patch-application/"><u>Self-Sufficient Windows Patch Application</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-oneplus-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from OnePlus</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-healing-defective-windows-registry-entries/"><u>Step-by-Step: Healing Defective Windows Registry Entries</u></a></li>
<li><a href="https://win11.techidaily.com/windows-evolution-retro-revamped-to-the-era-of-98/"><u>Windows Evolution Retro-Revamped: To the Era of 98</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-cpu-state-showcase-at-peak-levels/"><u>Windows Guide: CPU State Showcase at Peak Levels</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-warhammer-40k-boltgun-fix-pc-stutter-issues/"><u>Winning at Warhammer 40K Boltgun: Fix PC Stutter Issues</u></a></li>
</ul></div>
