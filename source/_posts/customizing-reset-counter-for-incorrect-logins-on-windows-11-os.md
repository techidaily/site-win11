---
title: Customizing Reset Counter for Incorrect Logins on Windows 11 OS
date: 2024-10-24T06:23:42.950Z
updated: 2024-10-27T08:12:45.414Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Reset Counter for Incorrect Logins on Windows 11 OS
excerpt: This Article Describes Customizing Reset Counter for Incorrect Logins on Windows 11 OS
keywords: Custom Reset Windows Login,Personalized Login Attempts,Increase Login Retries,Windows 11 Login Errors,Alter Counter for Logins,Manage Failed Credentials,Adjusted Incorrect Login Count
thumbnail: https://thmb.techidaily.com/ed5ee8baad91072b118b2d67f1083103fa228337347cb369c95ebc26efcbbaf5.jpg
---

## Customizing Reset Counter for Incorrect Logins on Windows 11 OS

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-subtlety-in-volume-reduction-for-audacity-projects/"><u>[New] 2024 Approved Subtlety in Volume Reduction for Audacity Projects</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-the-perfect-aesthetic-with-controlled-lighting/"><u>[Updated] In 2024, Crafting the Perfect Aesthetic with Controlled Lighting</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-friendly-reminder-how-to-chill-at-someones-tiktok-party/"><u>2024 Approved Friendly Reminder How To Chill at Someone's TikTok Party</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-reserve-memory-feature/"><u>Decoding Windows Reserve Memory Feature</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-active-directory-printer-error-on-win-1011/"><u>Eliminating Active Directory Printer Error on WIN 10/11</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-your-pc-with-windows-11-touch-features/"><u>Enhance Your PC with Windows 11 Touch Features</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-to-unblock-system-tools-in-windows-11/"><u>Essential Techniques to Unblock System Tools in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-solving-the-mystery-of-a-malfunctioning-wacom-drawing-tablet/"><u>Expert Guide: Solving the Mystery of a Malfunctioning Wacom Drawing Tablet</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-achieve-crystal-clear-audio-a-home-speaker-maintenance-manual/"><u>How to Achieve Crystal Clear Audio: A Home Speaker Maintenance Manual</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-13-pro-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi Redmi Note 13 Pro 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-tech-interfaces-ai-and-windows-software-blend/"><u>Reimagining Tech Interfaces: AI and Windows Software Blend</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-windows-desktop-icons-and-menus/"><u>Restoring Functionality to Windows Desktop Icons and Menus</u></a></li>
<li><a href="https://fox-direct.techidaily.com/revealing-the-smarts-of-z2-play-mobile-for-2024/"><u>Revealing the Smarts of Z2 Play Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-blue-screen-error/"><u>Understanding and Remedying Blue Screen Error</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Vivo T2 Pro 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    