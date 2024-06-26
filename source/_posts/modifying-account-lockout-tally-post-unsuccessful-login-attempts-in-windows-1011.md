---
title: Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
date: 2024-06-25T11:30:37.109Z
updated: 2024-06-26T11:30:37.109Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
excerpt: This Article Describes Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11
keywords: WIN10/11 Account Lock,Unsuccessful Login Limit,Windows Lockout Settings,Preventing Bruteforce Attacks,Adjust Lockout Policy,Access Control in Win10/11,Manage Failed Logins
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
---

## Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11

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

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/windows-11-quick-guide-to-open-sticky-notes/"><u>Windows 11: Quick Guide to Open Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-threshold-post-failed-access-on-w10w11/"><u>Tweaking the Lockout Threshold Post-Failed Access on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/are-your-keyboard-arrow-keys-not-working-try-these-fixes-for-windows/"><u>Are Your Keyboard Arrow Keys Not Working? Try These Fixes for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-faulty-windows-update-error/"><u>Correcting Faulty Windows Update Error</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-100mbps-wired-internet-limit-in-windows/"><u>Break Free From 100Mbps Wired Internet Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-telnet-activation-on-modern-windows/"><u>Quick Guide to Telnet Activation on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-reactivating-a-greyed-out-secure-boot-in-bios/"><u>Steps for Reactivating a Greyed Out Secure Boot in BIOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-compendium-best-of-the-bunch-historical-youtubes-for-study-for-2024/"><u>[Updated] Channel Compendium  Best of the Bunch - Historical YouTubes For Study for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-ultimate-guide-to-mastering-sound-inversion-top-audio-reversers-for-2024/"><u>The Ultimate Guide to Mastering Sound Inversion Top Audio Reversers for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-manufacture-mirthful-animations-on-giphy/"><u>2024 Approved  Manufacture Mirthful Animations on Giphy</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-best-practices-for-transforming-tiktok-content-into-gifs/"><u>[Updated] Best Practices for Transforming TikTok Content Into GIFs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-creating-continuous-viewing-pleasure-on-television-for-2024/"><u>[New] Creating Continuous Viewing Pleasure on Television for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-top-5-timelapse-recording-software/"><u>2024 Approved  Top 5 Timelapse Recording Software</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-iphone-se-2020-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile iPhone SE (2020) online without SIM Card?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-build-a-career-in-graphic-design/"><u>In 2024, How to Build A Career In Graphic Design</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-easy-guide-to-start-product-review-channel/"><u>2024 Approved  Easy Guide to Start Product Review Channel</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-best-tools-for-video-recording-focus-on-apeaksofts-advantages/"><u>[New] The Best Tools for Video Recording – Focus on Apeaksoft's Advantages</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>