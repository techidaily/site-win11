---
title: Setting Failed Logon Retry Timeframe in Win 10/11
date: 2024-06-25T09:41:51.145Z
updated: 2024-06-26T09:41:51.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
excerpt: This Article Describes Setting Failed Logon Retry Timeframe in Win 10/11
keywords: Win 10 Login Recovery,Windows 10 Reset Attempts,Manage Logon Retries,Reconfigure Login Delays (Win10/11),Windows Timeout for Failed Logins,Setting Login Retry Interval (Win10),Adjusting Login Retries (Windows 10)
thumbnail: https://thmb.techidaily.com/128652f3635b5c02571aebd32ea42bdf5de3d8228fe08a4a4993ce8bcc5b8b84.png
---

## Setting Failed Logon Retry Timeframe in Win 10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/explaining-and-correcting-the-msvcr110dll-deficit/"><u>Explaining & Correcting the msvcr110.dll Deficit</u></a></li>
<li><a href="https://win11.techidaily.com/key-practices-in-the-pursuit-of-a-pristine-windows-setup/"><u>Key Practices in the Pursuit of a Pristine Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-retry-interval-for-unsuccessful-login-attempts/"><u>Adjusting Retry Interval for Unsuccessful Login Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-delay-in-windows-11-keys-7-proven-methods/"><u>Reduce Delay in Windows 11 Keys: 7 Proven Methods</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-unresponsive-mail-alerts-on-windows-11/"><u>How to Overcome Unresponsive Mail Alerts on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-oneplus-nord-ce-3-lite-5g-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass OnePlus Nord CE 3 Lite 5G FRP</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-samsung-galaxy-s24-ultra-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Samsung Galaxy S24 Ultra Phone that is Locked?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-find-joy-one-anime-at-a-time-youtubes-best-channels-list/"><u>[New] Find Joy, One Anime at a Time  YouTube's Best Channels (List)</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-7-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 7 Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-mastering-macbook-air-beginners-guide-to-screen-recording/"><u>[Updated] In 2024, Mastering MacBook Air  Beginner's Guide to Screen Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-public-domain-zen-soundscape/"><u>[Updated] Public Domain Zen Soundscape</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-samsung-galaxy-f14-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Samsung Galaxy F14 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-essential-techniques-for-music-layering-in-fb-media/"><u>[Updated] In 2024, The Essential Techniques for Music Layering in FB Media</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>