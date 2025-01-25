---
title: Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11
date: 2025-01-22T06:12:24.664Z
updated: 2025-01-24T18:53:08.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11
excerpt: This Article Describes Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11
keywords: Win11 ACLockThresh Optimize,Password Lock Failure Limit,Safe Login Windows 11,Account Lockout Threshold Adjust,Min Failed Logins Secure PC,Secure Win11 Password Attempts,Reduce Unauthorized Access, Win 11
thumbnail: https://thmb.techidaily.com/2a75585c706bda1c98b7ca78005e810cc4fa04565ec0bfaa1522a3466ddc9fcb.jpg
---

## Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-elitepixel-recorder-winos-series/"><u>[New] 2024 Approved ElitePixel Recorder WinOS Series</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-realme-12-pro-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Realme 12 Pro 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-hidden-panes-6-strategies-in-win11/"><u>Breathing Life Into Hidden Panes: 6 Strategies in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-for-a-non-opening-command-prompt-window/"><u>Bridging the Gap for a Non-Opening Command Prompt Window</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-webp-conversion-modifying-images-settings-in-chrome-windows/"><u>Bypass WebP Conversion: Modifying Images Settings in Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-wi-fi-in-windows-11-a-guide-of-8-methods/"><u>Bypassing Limited Wi-Fi in Windows 11: A Guide of 8 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/combating-app-not-uploading-issue-a-guide-to-microsofts-store/"><u>Combating App Not Uploading Issue: A Guide to Microsoft's Store</u></a></li>
<li><a href="https://some-guidance.techidaily.com/discover-the-leading-free-digital-animation-creators-for-23r-year-in-brazil/"><u>Discover the Leading Free Digital Animation Creators for 2^3_R Year in Brazil!</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-the-best-mouse-sensitivity-for-competitive-fps-games/"><u>Discovering the Best Mouse Sensitivity for Competitive FPS Games</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-technology-insights-with-the-toms-hardware-team/"><u>Dive Into Technology Insights with the Tom's Hardware Team</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-from-social-tv-viewing-to-funny-interactive-gifs-a-twitter-video-journey/"><u>In 2024, From Social TV Viewing to Funny, Interactive Gifs A Twitter Video Journey</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-fixes-to-restore-functionality-of-a-defective-headset-mic/"><u>Quick Fixes to Restore Functionality of a Defective Headset Mic</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-8-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone 8 Prevention & Solution | Dr.fone</u></a></li>
</ul></div>

