---
title: Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
date: 2024-08-15T23:19:01.115Z
updated: 2024-08-16T23:19:01.115Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
excerpt: This Article Describes Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11
keywords: Windows Login Limit Adjustment,Account Lockout Management (Win10),Win11 Unauthorized Access Control,Failed Logins Security Measures,Lockout Counter Tuning W10/W11,Resetting Login Attempts Windows,Enhancing Account Protection WS20
thumbnail: https://thmb.techidaily.com/84dab43ab035d91cb56a4eae408b40758af9a9a2b096c95f61afee80ed15090c.jpg
---

## Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11

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
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-12-methods-to-posted-facebook-videos-not-showing-up/"><u>[New] 2024 Approved  12 Methods to Posted Facebook Videos Not Showing Up</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ideal-online-places-to-raise-audience-numbers/"><u>[New] Ideal Online Places to Raise Audience Numbers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-perfect-your-video-nine-essential-filters-for-live-streaming/"><u>[New] Perfect Your Video  Nine Essential Filters for Live Streaming</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-prime-selection-of-affordable-online-video-recorders/"><u>[New] The Prime Selection of Affordable Online Video Recorders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-bring-your-vision-to-life-youtube-trailers-using-filmoras-magic/"><u>[Updated] In 2024, Bring Your Vision to Life  YouTube Trailers Using Filmora's Magic</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-infuse-your-tiktok-with-popular-anime-themes-and-styles/"><u>2024 Approved  Infuse Your TikTok with Popular Anime Themes & Styles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-vivo-y17s-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Vivo Y17s Phone When You Forget the Password</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-stop-the-background-from-automatically-changing-on-windows-11/"><u>6 Ways to Stop the Background From Automatically Changing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-the-new-era-of-laptops-at-ifa-2023/"><u>A Journey Into the New Era of Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-perfect-sizing-of-your-pics-with-these-six-windows-11-tactics/"><u>Achieve Perfect Sizing of Your Pics with These Six Windows 11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-filter-keys-on-microsoft-os/"><u>Activating/Deactivating Filter Keys on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-qt-platform-support-error-for-app-starts/"><u>Addressing 'No Qt Platform Support' Error for App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-runtime-exceptions-your-ultimate-guide-for-windows-users/"><u>Addressing Runtime Exceptions: Your Ultimate Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alert-it-admin-limited-power/"><u>Addressing Windows Alert: IT Admin Limited Power</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-steam-transfers-averting-sudden-halt/"><u>Amplify Windows Steam Transfers: Averting Sudden Halt</u></a></li>
<li><a href="https://win11.techidaily.com/android-transition-post-subsystem-discontinuation-whats-next/"><u>Android Transition Post-Subsystem Discontinuation: What's Next?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-of-taskbar-in-modern-win11/"><u>Boosting Functionality of Taskbar in Modern Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-screen-legibility-win11-scaling-guide/"><u>Boosting Screen Legibility: Win11 Scaling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-run-handbrake-in-windows/"><u>Breaking Barriers: Run HandBrake in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-method-purging-every-correspondence-via-gmail-app-on-mobile-devices/"><u>Comprehensive Method: Purging Every Correspondence via Gmail App on Mobile Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elite-gaming-spectacle-cut-to-best-7-shooters-for-2024/"><u>Elite Gaming Spectacle  Cut to Best 7 Shooters for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-realme-c51-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Realme C51? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/learn-how-to-solve-youtube-video-distorted-issue/"><u>Learn How to Solve YouTube Video Distorted Issue</u></a></li>
<li><a href="https://win11.techidaily.com/1719350786682-operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-ultimate-selection-of-frames-for-professional-ig-artistry-for-2024/"><u>The Ultimate Selection of Frames for Professional IG Artistry for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
</ul></div>
