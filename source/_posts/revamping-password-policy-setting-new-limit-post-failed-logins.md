---
title: "Revamping Password Policy: Setting New Limit Post Failed Logins"
date: 2024-06-25T11:41:26.754Z
updated: 2024-06-26T11:41:26.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revamping Password Policy: Setting New Limit Post Failed Logins"
excerpt: "This Article Describes Revamping Password Policy: Setting New Limit Post Failed Logins"
keywords: Strong Passwords Now,Updated Login Policies,Safe Access Guidelines,Prevent Unauthorized Entry,Password Expiry Rules,Enhanced Security Measures,Limit Failed Logins Impact
thumbnail: https://thmb.techidaily.com/dadc574a72620fb10d26a05d18b7bc541d4008da38e3f5b8b4a33a2f717ba587.jpg
---

## Revamping Password Policy: Setting New Limit Post Failed Logins

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
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-type-mistakes-in-windows-11-zerox-error/"><u>Solutions for Correcting Type Mistakes in Windows 11 Zerox Error</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/basics-on-windows-exepe-files-an-overview/"><u>Basics on Windows EXE/PE Files: An Overview</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-incorporating-copy-and-move-commands-in-win-11/"><u>Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-modify-calculators-color-scheme-dark/"><u>How To Modify Calculator's Color Scheme (Dark)</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-photo-viewer-a-step-by-step-guide-for-11-users/"><u>Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-realme-11-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Realme 11 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-filmora-free-trial-vs-torrent-which-one-is-safe-and-legit/"><u>In 2024, Filmora Free Trial vs Torrent Which One Is Safe and Legit?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-calculate-image-dimensions-with-ease-a-ratio-finder-for-2024/"><u>New Calculate Image Dimensions with Ease A Ratio Finder for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-realme-gt-neo-5withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Realme GT Neo 5with/without a PC</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-nokia-c12-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Nokia C12 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-blueprints-for-successful-docu-screenplays/"><u>[New] Blueprints for Successful Docu-Screenplays</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-apps-to-create-engaging-whatsapp-status-videos-free-and-paid-for-2024/"><u>Best Apps to Create Engaging WhatsApp Status Videos (Free & Paid) for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-uncompromised-creativity-best-macos-big-sur-editing-tools-ranked/"><u>In 2024, Uncompromised Creativity  Best macOS Big Sur Editing Tools Ranked</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-innovative-approaches-to-network-broadcast-with-vlc/"><u>[New] 2024 Approved  Innovative Approaches to Network Broadcast with VLC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-free-photo-editing-unleashed-android-and-iphones-top-tools-ranked/"><u>[Updated] Free Photo Editing Unleashed – Android & iPhone's Top Tools Ranked</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>