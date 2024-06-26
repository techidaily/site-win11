---
title: Adjusting Retry Interval for Unsuccessful Login Attempts
date: 2024-06-25T09:49:32.120Z
updated: 2024-06-26T09:49:32.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
excerpt: This Article Describes Adjusting Retry Interval for Unsuccessful Login Attempts
keywords: Login Retry Adjustment,Unsuccessful Login Handling,Increase Login Retries,Manage Failed Logins,Login Attempt Limits,Optimize Login Intervals,Success Rate for Login Attempts
thumbnail: https://thmb.techidaily.com/4ac54b51c1cafa3a284440c31d27701c82afd968d6a73268fe3b019a529c7811.jpg
---

## Adjusting Retry Interval for Unsuccessful Login Attempts

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
<li><a href="https://win11.techidaily.com/powerful-techniques-for-unlocking-your-system-writable-files/"><u>Powerful Techniques for Unlocking Your System' Writable Files</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-telnet-enablement-in-win11/"><u>Step-by-Step: Telnet Enablement in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-update-your-amd-radeon-graphics-drivers-on-windows-11/"><u>How to Update Your AMD Radeon Graphics Drivers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-ram-cache-cleanse-procedures/"><u>Step-by-Step: Windows RAM Cache Cleanse Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-a-list-of-quick-access-techniques-for-credentials-in-win11/"><u>Break the Code: A List of Quick Access Techniques for Credentials in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-routes-for-customizing-windows-11-settings-app/"><u>Reboot Routes for Customizing Windows 11 Settings App</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-remove-programs-without-permission-in-windows/"><u>Steps to Remove Programs Without Permission in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premier-general-knowledge-trivia-hubs/"><u>Premier General Knowledge Trivia Hubs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-verdict-on-toolwiz-top-notch-mobile-photo-editor/"><u>In 2024, The Verdict on Toolwiz  Top-Notch Mobile Photo Editor?</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-xs-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone XS Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-lava-yuva-3-pro-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-obs-tutorial-broadcasting-on-youtube-from-home/"><u>In 2024, OBS Tutorial  Broadcasting on Youtube From Home</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-rookie-riches-economical-channels-for-monetization/"><u>[New] Rookie Riches  Economical Channels for Monetization</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-honor-x9b-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Honor X9b | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-best-of-the-best-top-12-audio-converters-for-any-format/"><u>New In 2024, The Best of the Best Top 12 Audio Converters for Any Format</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-cutting-edge-editors-toolkit-the-definitive-list-of-10-reaper-plugins-to-enhance-your-workflows/"><u>Updated 2024 Approved Cutting-Edge Editors Toolkit The Definitive List of 10 Reaper Plugins to Enhance Your Workflows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-chromebooks-premium-free-video-capture-extensions/"><u>In 2024, Chromebook's Premium Free Video Capture Extensions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>