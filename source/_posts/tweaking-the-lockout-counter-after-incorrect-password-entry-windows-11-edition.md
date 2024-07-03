---
title: Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
date: 2024-06-25T11:43:11.687Z
updated: 2024-06-26T11:43:11.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
excerpt: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
keywords: Win11 Password Error Fix,Lockout Counter Update Win11,Correct Pass Retry Options Win11,Preventing Incorrect Login Windows,Windows 11 Lockout Revision,Resetting Windows 11 Login Attempts,Adjusting Password Failures Win11
thumbnail: https://thmb.techidaily.com/a6de986a3fdb94c7142abb7e1738397c8994a30f493de897d20f957481bc1b83.jpg
---

## Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition

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
<li><a href="https://win11.techidaily.com/how-to-reestablish-network-connection-after-failure-in-windows-11/"><u>How to Reestablish Network Connection After Failure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-how-to-locate-and-utilize-hidden-windows-11-enhancements/"><u>Fix the Gap: How to Locate & Utilize Hidden Windows 11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-icon-visibility-windows-11s-hidden-menus/"><u>Elevate Icon Visibility: Windows 11'S Hidden Menus</u></a></li>
<li><a href="https://win11.techidaily.com/stalling-windows-auto-updates-four-methods/"><u>Stalling Windows Auto-Updates: Four Methods</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mastering-the-art-of-hash-tracking-top-apps-reviewed-fbtwitterinsta-for-2024/"><u>[Updated] Mastering the Art of Hash Tracking  Top Apps Reviewed (FB/Twitter/Insta) for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tiktoks-biggest-winners-on-the-twittersphere/"><u>[Updated] TikTok's Biggest Winners on the Twittersphere</u></a></li>
<li><a href="https://animation-videos.techidaily.com/are-you-head-over-heels-with-3d-animation-design/"><u>Are You Head Over Heels With 3D Animation Design?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-navigating-beyond-wirecast-for-broadcast-solutions/"><u>[Updated] Navigating Beyond WireCast for Broadcast Solutions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-portrait-perfection-the-best-video-editing-apps-for-ios-and-android-for-2024/"><u>New Portrait Perfection The Best Video Editing Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pinterest-content-powered-free-high-speed-download-apps-reviewed/"><u>[New] Pinterest Content Powered  Free, High-Speed Download Apps Reviewed</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-strategic-blending-elevating-video-sequence-harmony-for-2024/"><u>[Updated] Strategic Blending  Elevating Video Sequence Harmony for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-finding-the-ideal-soundtrack-for-unboxing-content/"><u>[Updated] Finding the Ideal Soundtrack for Unboxing Content</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>