---
title: Adjusting Windows 10/11 Login Lockout Interval
date: 2024-06-25T09:56:23.303Z
updated: 2024-06-26T09:56:23.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows 10/11 Login Lockout Interval
excerpt: This Article Describes Adjusting Windows 10/11 Login Lockout Interval
keywords: Win10/11 Account Lock Time,Windows Login Cooldown,Adjusting Lockout Timers,Modify Window Logon Delay,Reset PC Login Intervals,Shorten Windows Lockouts,Tweak Windows Logon Timer
thumbnail: https://thmb.techidaily.com/1734faea8dc6fb99b0356fb7510aa58c46806122f440ead1dafd4f608890d169.png
---

## Adjusting Windows 10/11 Login Lockout Interval

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
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-extracting-sids-from-users-on-windows-11/"><u>Unraveling the Mystery: Extracting SIDs From Users on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-improper-thx-surround-in-windows/"><u>Addressing Improper THX Surround in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-one-sided-windows-headphone-sound-loss/"><u>Fixing One-Sided Windows Headphone Sound Loss</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-failed-security-codes-in-game-launcher-windows-edition/"><u>Quick Fixes for Failed Security Codes in Game Launcher Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/win32keygen-understanding-identifying-and-neutralizing-its-threat-to-windows/"><u>Win32/Keygen: Understanding, Identifying & Neutralizing Its Threat to Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unleash-potential-best-free-safe-followers-enhancing-your-feed-iosandroid/"><u>[Updated] Unleash Potential  Best Free, Safe Followers Enhancing Your Feed (iOS/Android)</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-strumming-success-a-comprehensive-look-at-the-top-5-guitar-recorders/"><u>Updated Strumming Success A Comprehensive Look at the Top 5 Guitar Recorders</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/launch-xp-movie-editor-for-seamless-editing/"><u>Launch XP Movie Editor for Seamless Editing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-what-lies-beneath-the-true-meanings-in-emoji/"><u>[Updated] In 2024, What Lies Beneath  The True Meanings in Emoji</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/seamless-tweet-integration-on-facebook-platform/"><u>Seamless Tweet Integration on Facebook Platform</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-the-secrets-to-successful-rapid-subscribing-on-youtube-for-2024/"><u>Unlocking the Secrets to Successful Rapid Subscribing on YouTube for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/tailoring-your-timeline-a-step-by-step-guide-to-editing-lengthy-audios-in-imovie-on-ios-devices-for-2024/"><u>Tailoring Your Timeline A Step-by-Step Guide to Editing Lengthy Audios in iMovie on iOS Devices for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-humorous-hits-lifetime-access-to-memes/"><u>[New] Humorous Hits  Lifetime Access to Memes</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-comedy-classics-a-curated-15-channel-collection-for-humor/"><u>[Updated] Comedy Classics  A Curated 15-Channel Collection for Humor</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-collective-chronicle-converter/"><u>[New] Collective Chronicle Converter</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>