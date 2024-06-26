---
title: Tweaking the Lockout Threshold Post-Failed Access on W10/W11
date: 2024-06-25T11:44:40.556Z
updated: 2024-06-26T11:44:40.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Lockout Threshold Post-Failed Access on W10/W11
excerpt: This Article Describes Tweaking the Lockout Threshold Post-Failed Access on W10/W11
keywords: Failed Access Prevention,Windows 10 Security,Access Control Settings,W10 Lockout Adjustment,W11 Post-Access Threshold,Update Account Lockouts,Access Failure Management
thumbnail: https://thmb.techidaily.com/88b9d1a1839e87bc852a7b88397e12987972348fa38a161adde19f109b06aa2c.jpg
---

## Tweaking the Lockout Threshold Post-Failed Access on W10/W11

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
<li><a href="https://win11.techidaily.com/streamlining-data-views-tabbing-in-windows-explorer/"><u>Streamlining Data Views: Tabbing in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://win11.techidaily.com/scrutinizing-password-ingress-windows-pass-and-no-pass-outcomes/"><u>Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-email-notifications-in-windows-environment/"><u>Reviving Stalled Email Notifications in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launch-failures-fixing-windows-speech-recognition/"><u>Overcoming Launch Failures: Fixing Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manipulate-windows-gpu-priority-settings/"><u>How to Manipulate Windows GPU Priority Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pioneering-cloud-innovation-the-best-providers-of-2024/"><u>[New] Pioneering Cloud Innovation  The Best Providers of 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-your-online-impact-with-effective-backlink-strategies/"><u>Elevate Your Online Impact with Effective Backlink Strategies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-3-proven-methods-to-enhance-your-music-archives/"><u>[Updated] 2024 Approved  3 Proven Methods to Enhance Your Music Archives</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-starry-nights-in-focus-advice-on-night-portraiture/"><u>2024 Approved  Starry Nights in Focus  Advice on Night Portraiture</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unlocking-aspect-ratios-the-key-to-facebook-video-success/"><u>In 2024, Unlocking Aspect Ratios  The Key to Facebook Video Success</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-learn-to-stream-lol-with-these-simple-steps-3-ways-for-2024/"><u>[New] Learn to Stream LOL with These Simple Steps (3 Ways) for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-premier-10-moba-titles-for-android-devotees/"><u>[Updated] 2024 Approved  Premier 10 MOBA Titles for Android Devotees</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-must-have-add-ons-for-your-gopro-adventure/"><u>2024 Approved  Must-Have Add-Ons for Your GoPro Adventure</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-constructive-communication-leads-to-more-subscribers/"><u>[Updated] 2024 Approved  Constructive Communication Leads to More Subscribers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>